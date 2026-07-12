# Contour Detection using OpenCV

**This repository contains code for [Contour Detection using OpenCV](https://learnopencv.com/contour-detection-using-opencv-python-c/) blogpost**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/lylz9lzqzs2nt2q/AAC5SfEV7_ex0imh1uip9-U6a?dl=1)

## Directory Structure

**All the code files and folders follow the following structure.**

```
├── CPP
│   ├── channel_experiments
│   │   ├── channel_experiments.cpp
│   │   └── CMakeLists.txt
│   ├── contour_approximations
│   │   ├── CMakeLists.txt
│   │   └── contour_approx.cpp
│   └── contour_extraction
│       ├── CMakeLists.txt
│       └── contour_extraction.cpp
├── input
│   ├── custom_colors.jpg
│   ├── image_1.jpg
│   └── image_2.jpg
├── python
│   ├── channel_experiments
│   │   └── channel_experiments.py
│   ├── contour_approximations
│   │   └── contour_approx.py
│   └── contour_extraction
│       └── contour_extraction.py
└── README.md
```



## Instructions

### Python

To run the code in Python, please go into the `python` folder and execute the Python scripts in each of the respective sub-folders.

### C++

To run the code in C++, please go into the `cpp` folder, then go into each of the respective sub-folders and follow the steps below:

```
mkdir build
cd build
cmake ..
cmake --build . --config Release
cd ..
./build/channel_experiments
```

```
mkdir build
cd build
cmake ..
cmake --build . --config Release
cd ..
./build/contour_approximations
```

```
mkdir build
cd build
cmake ..
cmake --build . --config Release
cd ..
./build/contour_extraction
```



---

<p align="center">
  <a href="https://bigvision.ai/">
    <img src="https://bigvision.ai/logos/logo.png" alt="BigVision.AI" width="300">
  </a>
</p>

<h2 align="center">Build Production-Ready Computer Vision &amp; AI Solutions</h2>

<p align="center">
  LearnOpenCV is maintained by <a href="https://bigvision.ai/"><strong>BigVision.AI</strong></a>, a computer vision and AI consulting company. We help organizations design, build, optimize, and deploy production-ready AI solutions. Our team has deep expertise in computer vision, deep learning, multimodal AI, and edge deployment, with experience solving complex technical challenges across industries.
</p>

<p align="center">
  Have a project in mind? Talk with our expert AI solution builders.
</p>

<p align="center">
  <a href="https://bigvision.ai/expert-ai-solution-builders?utm_source=locv-github">
    <img src="https://img.shields.io/badge/Get%20in%20Touch-087EA4?style=for-the-badge" alt="Get in Touch with BigVision.AI">
  </a>
</p>
