<h1 align="center"> IR Image Stitching</h1>

---

<details open="open">
  <summary >Table of Contents</summary>
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
        <li><a href="#installation">Installation</a></li>
        <li>
          <a href="#running-this-project">Running this project</a>
          <ul>
        <li><a href="#preprocessing">Preprocessing</a></li>
        <li><a href="#dominant-frame-selection">Dominant Frame Selection</a></li>
        <li><a href="#stitching">Stitching</a></li>
         </ul>
          </li>
        </ul>
    </li>
    <li><a href="#contributers">Contributers</a></li>
  </ol>
</details>

## About The Project
Blended multiple infrared images from different datasets using perspective blending after performing some preprocessing and feature matching steps.


### Built With
* [OpenCV](https://opencv.org/)
* [Numpy](https://numpy.org/)

## Getting Started

For Image Stitching follow these simple steps.

### Installation

1. Copy the CV_Assignment1.ipynb in Colab 
2. Upload the dataset on your Drive.

### Running this project
#### Preprocessing
1. Copy the image dataset path from drive and paste it in cv2_imread
2. Replace the output path with the path where you want to save it.

#### Dominant Frame Selection
1. Copy the image path, from preprocessing results.
2. The one with maximum value is the Dominant frame

#### Stitching
1. Replace imdir1 in Perspective Blending with preprocessing results. 
2. Replace result in Perspective Blending with the dominant frame or with first image from the preprocessing results.
3. Replace feature_extractor in feature mapping with the method you want to use.

## Contributers
* **Arya Dwivedi**
* **Deepanshu Jain**
* **Gargi Singh**
* **Naveen Kumar**
* **Sanya Agrawal**



