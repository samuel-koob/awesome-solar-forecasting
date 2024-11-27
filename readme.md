# Awesome Solar and Photovoltaic Energy Forecasting
This repository contains a list of awesome resources for solar and photovoltaic energy (forecasting),
as well as All Sky Imagers (camera installations that capture as much sky as possible). The list is not exhaustive and will be updated regularly. If you have any suggestions, please feel free to contribute.

Research Datasets will be added soon.

Bibliography files can be found in the `bibliography` directory.

## Table of Contents

- [All Sky Cameras: Hardware and Analysis](#all-sky-cameras)

- [Research Datasets and Resources](#research-datasets-and-resources)

- [Computer Vision: Image Processing and Forecasting](#computer-vision)

- [Photovoltaic Forecasting](#Nowcasting-using-All-Sky-Images)

- [Solar and Photovoltaic Energy Facts in Germany (German)](#solar-and-photovoltaic-energy-writeups)


## All Sky Cameras

All Sky Cameras (ASC) are camera installations that capture as much sky as possible. They are used in solar and photovoltaic energy forecasting to predict cloud cover and solar radiation. The following resources provide information on the hardware and analysis of All Sky Imagers.

- **LAMSkyCam: A low cost and miniature ground based sky cam**
    <details>
    <summary>Details</summary>
    Construction and evaluation of a low-cost and miniature ground-based sky camera for cloud cover estimation. Focus lies on the low-cost and easy assembly of components to build a sky camera. The camera is evaluated for cloud cover estimation and compared to a commercial camera.

    - [DOI Url](https://doi.org/10.1016/j.ohx.2022.e00346)
    - DOI: 10.1016/j.ohx.2022.e00346

    </details>

- **Total Sky Imager Model 880 Status and Testing Results**
    <details>
    <summary>Details</summary>
    The Total Sky Imager Model 880 (TSI-880) is a ground-based camera that captures images of the sky.
    Once sold commercially, the TSI-800 is now discontinued.
    This paper provides information on the camera's hardware and testing results.

    - DOI: 10.2172/1020735
    </details>

- **Validation of an all-sky imager-based nowcasting system for industrial PV plants**
    <details>
    <summary>Details</summary>
    This paper presents a nowcasting system for industrial photovoltaic plants based on an all-sky imager.
    The system is validated using data from a photovoltaic plant in Germany.

    - [Url](https://elib.dlr.de/115452/)
    </details>

- **WAHRSIS: A low-cost high-resolution whole sky imager with near-infrared capabilities**
    <details>
    <summary>Details</summary>
    Wide Angle High-Resolution Sky Imaging System (WAHRSIS) is a low-cost, high-resolution whole sky imager with near-infrared capabilities.
    This paper covers the modifications done to the camera, as well as the geometric and radiometric calibration.

    - [DOI Url](https://doi.org/10.1117/12.2052982)
    - DOI: 10.1117/12.2052982
    </details>

## Research datasets and resources

This section contains useful datasets and resources for solar and photovoltaic energy forecasting.

- **Stanford Univ. Solar Forecasting Dataset**
    <details>
    <summary>Details</summary>

    This dataset is connected to the work `SKIPP'D — a SKy Images and Photovoltaic Power Generation Dataset for Short-term Solar Forecasting`, which covers the details of the dataset.
    More information can be found on the GitHub repository:
    https://github.com/yuhao-nie/Stanford-solar-forecasting-dataset
    </details>

- **AllSkyCam.com: User contributed images**
    <details>
    <summary>Details</summary>
    AllSkyCam.com is a website where users can upload images from their All Sky Imagers. It contains several installations from around the US.

    More information can be found on the website:
    https://www.allskycam.com/
    </details>

## Computer Vision

This section contains resources on image processing and forecasting using computer vision techniques.
Focus lies on cloud (-type) and sun identification and segmentation.

### Cloud and Sun Identification / Segmentation

- **A method for cloud detection and opacity classification based on ground based sky imagery**
    <details>
    <summary>Details</summary>
    This paper presents a cloud detection algorithm for All Sky Images.
    The algorithm is based on comparing red-to-blue ratio differences of pixels to clear-sky-library values.

    - [Url](https://amt.copernicus.org/articles/5/2881/2012/)
    - DOI: 10.5194/amt-5-2881-2012
    </details>

- **Cloud Detection on Ground-Based Sky Images with Brightness Reduction of Circumsolar Region**
    <details>
    <summary>Details</summary>
    This paper presents a cloud detection algorithm for All Sky Images.
    The algorithm is based on the brightness reduction of the circumsolar region to adjust contrast.
    This makes it easier to detect clouds commonly obstructed by the sun's flare.

    - DOI: 10.1109/ECTICon.2018.8619940
    </details>

- **Feature Extraction from Whole-Sky Ground-Based Images for Cloud-Type Recognition**
    <details>
    <summary>Details</summary>
    This paper presents a method for cloud-type recognition based on feature extraction from whole-sky ground-based images.
    The method uses a combination of texture and color features to classify cloud types.
    Features include statistical measurements or fourier transforms.

    - [Url](https://journals.ametsoc.org/view/journals/atot/25/1/2007jtecha959_1.xml)
    - DOI: 10.1175/2007JTECHA959.1
    </details>

- **Sun Position Identification in Sky Images for Nowcasting Application**
    <details>
    <summary>Details</summary>
    This paper presents different methods for sun position identification in sky images.
    These include solar angle-based, image processing-based, and neural network-based techniques,
    which are then compared in terms of accuracy and computational complexity.

    - DOI: 10.3390/forecast2040026
    </details>

- **The Use of Euclidean Geometric Distance on RGB Color Space for the Classification of Sky and Cloud Patterns**
    <details>
    <summary>Details</summary>
    This paper presents a method for classifying sky and cloud patterns based on Euclidean geometric distance in RGB color space.
    The method is evaluated on a dataset of sky images and compared to other classification methods.

    - [Url](https://journals.ametsoc.org/view/journals/atot/27/9/2010jtecha1353_1.xml)
    - DOI: 10.1175/2010JTECHA1353.1
    </details>

## Nowcasting using All Sky Images

This subsection contains resources on nowcasting, which is the prediction of weather conditions in the near future.

- **Estimation of solar irradiance using ground-based whole sky imagers**
    <details>
    <summary>Details</summary>
    This paper presents a method for estimating solar irradiance using ground-based whole sky imagers
    and their corresponding cloud cover information and connected cloud movement.

    - DOI: 10.1109/IGARSS.2016.7730887
    </details>

- **Very short-term solar irradiance forecast using all-sky imaging and real-time irradiance measurements**
    <details>
    <summary>Details</summary>
    This paper presents how All Sky Images can be used to estimate cloud motion and use it for short-term solar irradiance forecasting when combined with online irradiance measurements.

    - [DOI Url](https://doi.org/10.1016/j.renene.2019.05.069)
    - DOI: 10.1016/j.renene.2019.05.069
    </details>

- **Cloud Radiative Effect Study Using Sky Camera**
    <details>
    <summary>Details</summary>
    This paper presents a method for studying cloud radiative effects using sky cameras.
    With a focus on the impact of cloud on the total solar irradiance reaching the earth's surface,
    the instantaneous cloud radiative effect is calculated using sky camera images.

    - [DOI Url](https://doi.org/10.1109/USNC-URSI.2017.8074899)
    - DOI: 10.1109/USNC-URSI.2017.8074899
    </details>

- **A broadband simplified version of the Solis clear sky model**
    <details>
    <summary>Details</summary>
    This paper presents a simplified version of the Solis clear sky model.
    It aims to resolve the issue of the model's complexity and computational cost by using a broadband approach.
    The accuracy of the simplified model is then compared to the original model.

    - [DOI Url](https://doi.org/10.1016/j.solener.2008.02.009)
    - DOI: 10.1016/j.solener.2008.02.009
    </details>

- **A new airmass independent formulation for the Linke turbidity coefficient**
    <details>
    <summary>Details</summary>
    A new formulation for the Linke turbidity coefficient is presented in this paper.
    The focus lies on making the coefficient more independent of solar geometry.
    As a result, two new simple clear sky models for global and direct normal irradiance are proposed.

    - [DOI Url](https://doi.org/10.1016/S0038-092X(02)00045-2)
    - DOI: 10.1016/S0038-092X(02)00045-2
    </details>

- **The Estimation of Clear Sky Global Horizontal Irradiance at the Equator**
    <details>
    <summary>Details</summary>
    This paper presents a regression method to parameterise one selection of multiple proposed empirical clear sky models for the estimation of clear sky global horizontal irradiance at the equator.
    The developed model is then validated using data from different stations in Singapore.

    - [DOI Url](https://doi.org/10.1016/j.egypro.2012.07.019)
    - DOI: 10.1016/j.egypro.2012.07.019
    </details>

## Solar and Photovoltaic Energy Writeups

This section contains writeups and facts about solar and photovoltaic energy. As of now, the resources are only available in German.

- **Aktuelle Fakten zur Photovoltaik in Deutschland**
    <details>
    <summary>Details</summary>
    This writeup provides an overview of the current state of photovoltaic energy in Germany.
    It is written in a way for the general public to understand the current situation and future prospects of photovoltaic energy
    and aims to answer common questions about the topic as well as busting myths.

    - [Url](https://www.ise.fraunhofer.de/content/dam/ise/de/documents/publications/studies/aktuelle-fakten-zur-photovoltaik-in-deutschland.pdf)
    </details>