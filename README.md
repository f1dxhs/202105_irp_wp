# IRP


<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#the-data">The Code</a>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project


Wildfire forecasting problems usually rely on complex grid based mathematical models, mostly involving CFD and Celluar Automata, but these methods have always been computationally expensive and difficult to deliver a fast decision pattern. In this paper, we provide machine learning based approaches that solve the problem of high computational effort and time consumption. This paper predicts the burning duration of a known wildfire by RF(random forest), KNN, and XGBoost regression models and also image based, like CNN and Encoder. Model inputs are based on the map of landscape features provided by satellites and the corresponding historical fire data in this area. This model is trained by happened fire data and landform feature map and tested with most recent real value in the same area. By processing the input differently to obtain the optimal outcome, the system is able to make fast and relatively accurate future predictions based on landscape images of known fires.

<!-- GETTING STARTED -->
## Getting Started

To perform our algorithms, please follow the instructions below.

### Prerequisites
We built this project with tool Jupyter notebook, platform Google Colab and language Python


### Installation

1. git clone our repository:
   ```sh
   git clone git@github.com:ese-msc-2021/irp-hx221.git
   ```
2. Since we deployed the project on Google Colab, we need to install all required models. 
   ```sh
    !pip install fiona==1.8.20
    !pip install geojson==2.5.0
    !pip install shapely==1.8.0
    !pip install geopandas
    !pip install reverse_geocoder
   ```
3. If you want to execute them locally, you can install Tensorflow2 (GPU) using pip or conda.
   We provide a guide to install via `pip` (https://www.tensorflow.org/install/gpu) 
   ```sh
   # Requires the latest pip
   pip install --upgrade pip

   # Current stable release for CPU and GPU
   pip install tensorflow==2.3.0

   ```
<!-- THE Code -->
## The Code

Our code consists of six part, including all the data gathering, data processing, modeling and training process. For performing output, you can just focusing on the last one.
First part gives all the required moudels. 
Part 2-3 introduce the data processing and data gathering
Part 4-5 gives model detail
Last Part shows the result plot

<!-- LICENSE -->
## License

Distributed under the MIT License.

Copyright <Hansong Xiao 2022>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<!-- CONTACT -->
## Contact

We appreciate any suggestions from you in advance! You may contact those experts:

Sibo, Cheng- sibo.cheng@imperial.ac.uk<br>
Hansong, Xiao- hansong.xiao@imperial.ac.uk<br>

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
