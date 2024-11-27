# Awesome Solar and Photovoltaic Energy Forecasting
This repository contains a list of awesome resources for solar and photovoltaic energy (forecasting),
as well as All Sky Imagers (camera installations that capture as much sky as possible). The list is not exhaustive and will be updated regularly. If you have any suggestions, please feel free to contribute.

Research Datasets will be added soon.

Bibliography files can be found in the `bibliography` directory.

## Table of Contents

- [All Sky Cameras: Hardware and analysis](#all-sky-cameras)

- [Research Datasets and resources](#research-datasets-and-resources)

- [Computer Vision: Image processing and forecasting](#computer-vision)

- [Deep Learning and AI: Image processing and forecasting](#deep-learning-and-ai)

- [Solar and Photovoltaic Energy Facts in Germany (German)](#solar-and-photovoltaic-energy-writeups)


## All Sky Cameras

All Sky Cameras (ASC) are camera installations that capture as much sky as possible. They are used in solar and photovoltaic energy forecasting to predict cloud cover and solar radiation. The following resources provide information on the hardware and analysis of All Sky Imagers.

- **LAMSkyCam: A low cost and miniature ground based sky cam**
    <details>
    <summary>Details</summary>
    Construction and evaluation of a low-cost and miniature ground-based sky camera for cloud cover estimation. Focus lies on the low-cost and easy assembly of components to build a sky camera. The camera is evaluated for cloud cover estimation and compared to a commercial camera.
    </details>

- **Total Sky Imager Model 880 Status and Testing Results**
    <details>
    <summary>Details</summary>
    The Total Sky Imager Model 880 (TSI-880) is a ground-based camera that captures images of the sky.
    Once sold commercially, the TSI-800 is now discontinued.
    This paper provides information on the camera's hardware and testing results.
    </details>

- **Validation of an all-sky imager-based nowcasting system for industrial PV plants**
    <details>
    <summary>Details</summary>
    This paper presents a nowcasting system for industrial photovoltaic plants based on an all-sky imager.
    The system is validated using data from a photovoltaic plant in Germany.
    </details>

- **WAHRSIS: A low-cost high-resolution whole sky imager with near-infrared capabilities**
    <details>
    <summary>Details</summary>
    Wide Angle High-Resolution Sky Imaging System (WAHRSIS) is a low-cost, high-resolution whole sky imager with near-infrared capabilities.
    This paper covers the modifications done to the camera, as well as the geometric and radiometric calibration.
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
    </details>

- **Cloud Detection on Ground-Based Sky Images with Brightness Reduction of Circumsolar Region**
    <details>
    <summary>Details</summary>
    This paper presents a cloud detection algorithm for All Sky Images.
    The algorithm is based on the brightness reduction of the circumsolar region to adjust contrast.
    This makes it easier to detect clouds commonly obstructed by the sun's flare.
    </details>

- **Feature Extraction from Whole-Sky Ground-Based Images for Cloud-Type Recognition**
    <details>
    <summary>Details</summary>
    This paper presents a method for cloud-type recognition based on feature extraction from whole-sky ground-based images.
    The method uses a combination of texture and color features to classify cloud types.
    Features include statistical measurements or fourier transforms.
    </details>

- **Sun Position Identification in Sky Images for Nowcasting Application**
    <details>
    <summary>Details</summary>
    This paper presents different methods for sun position identification in sky images.
    These include solar angle-based, image processing-based, and neural network-based techniques,
    which are then compared in terms of accuracy and computational complexity.
    </details>

- **The Use of Euclidean Geometric Distance on RGB Color Space for the Classification of Sky and Cloud Patterns**
    <details>
    <summary>Details</summary>
    This paper presents a method for classifying sky and cloud patterns based on Euclidean geometric distance in RGB color space.
    The method is evaluated on a dataset of sky images and compared to other classification methods.
    </details>

### Nowcasting

This subsection contains resources on nowcasting, which is the prediction of weather conditions in the near future.

- **Estimation of solar irradiance using ground-based whole sky imagers**
    <details>
    <summary>Details</summary>
    This paper presents a method for estimating solar irradiance using ground-based whole sky imagers
    and their corresponding cloud cover information and connected cloud movement.
    </details>

- **Very short-term solar irradiance forecast using all-sky imaging and real-time irradiance measurements**
    <details>
    <summary>Details</summary>
    This paper presents how All Sky Images can be used to estimate cloud motion and use it for short-term solar irradiance forecasting when combined with online irradiance measurements.
    </details>

- **Cloud Radiative Effect Study Using Sky Camera**
    <details>
    <summary>Details</summary>
    This paper presents a method for studying cloud radiative effects using sky cameras.
    With a focus on the impact of cloud on the total solar irradiance reaching the earth's surface,
    the instantaneous cloud radiative effect is calculated using sky camera images.
    </details>

## Solar and Photovoltaic Energy Writeups

This section contains writeups and facts about solar and photovoltaic energy. As of now, the resources are only available in German.