<div id="top"></div>

[![Stargazers][stars-shield]][stars-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

# UAV Solar-Sensor Angle Calculation

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/souravbhadra/uav-solar-sensor-angle">
    <img src="images/graphical_abstract.png" alt="Logo" width="2300" height="350">
  </a>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#datasets">Datasets</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Calculating solar-sensor zenith and azimuth angles for hyperspectral images collected by UAVs are important in terms of conducting bi-directional reflectance function (BRDF) correction or radiative transfer modeling-based applications in remote sensing. These applications are even more necessary to perform high-throughput phenotyping and precision agriculture tasks. This study demonstrates an automated Python framework that can calculate the solar-sensor zenith and azimuth angles for a push-broom hyperspectral camera equipped in a UAV. First, the hyperspectral images were radiometrically and geometrically corrected. Second, the high-precision Global Navigation Satellite System (GNSS) and Inertial Measurement Unit (IMU) data for the flight path was extracted and corresponding UAV points for each pixel were identified. Finally, the angles were calculated using spherical trigonometry and linear algebra.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

The project is built with many open source Python packages. However, following libraries are the backbone of the project:

* [pvlib](https://pvlib-python.readthedocs.io/en/stable/)
* [GDAL](https://gdal.org/)
* [GeoPandas](https://geopandas.org/en/stable/)
* [Pandas](https://pandas.pydata.org/)
* [Scipy](https://scipy.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

For this project, `anaconda` is suggested. Create a virtual environment in `anaconda` using `Python 3x`.

### Set up the notebooks

1. Create a separate environment in `conda`.
2. Install all the packages required using either `pip` or `conda`.
3. Clone the repo
4. Open the notebooks in the `notebooks` folder. Use the two notebooks chronologically.


### Datasets
The dataset provided for testing the codes is provided in Google Drive. Please follow this [link](https://drive.google.com/drive/folders/1rThYam61vmjUb0zvftqG6wvp1SsbTJpq?usp=sharing) to download the dataset and then place it in the data folder of your repository. The folder contains a HSI cube and the IMU_GPS data in txt format.

<p align="right">(<a href="#top">back to top</a>)</p>







<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact



<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Solar Sena](https://solarsena.com/)
* [pvlib](https://pvlib-python.readthedocs.io/en/stable/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/souravbhadra/uav-solar-sensor-angle/stargazers
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/souravbhadra/uav-solar-sensor-angle/network/members
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/souravbhadra/uav-solar-sensor-angle/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/souravbhadra/uav-solar-sensor-angle/blob/master/LICENSE.txt
