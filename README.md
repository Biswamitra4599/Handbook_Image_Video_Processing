# Handbook of Image and Video Processing — Computational Companion

<p align="center">

**Independent implementations of classical image and video processing algorithms**

Inspired by *Handbook of Image and Video Processing*, edited by **Alan C. Bovik**

</p>

---

## 📖 About This Repository

This repository provides **independent implementations, experiments, visualizations, and mathematical explanations** for the image and video processing concepts covered in:

> **Alan C. Bovik (Ed.), *Handbook of Image and Video Processing***

The goal is to transform the theoretical material presented throughout the handbook into a practical computational resource.

The implementations are developed primarily in **Python**, with an emphasis on:

* Understanding the underlying mathematics
* Implementing algorithms from scratch where practical
* Comparing implementations with established scientific libraries
* Visualizing intermediate processing steps
* Evaluating algorithmic performance
* Reproducing classical image and video processing concepts
* Connecting classical methods with modern machine learning and deep learning approaches

This repository is intended for **students, researchers, engineers, and anyone learning image and video processing**.

> **Disclaimer:** This is an independent educational project. It is not affiliated with, endorsed by, or sponsored by the authors or publisher of the handbook. The repository does not reproduce copyrighted text, figures, or source code from the book.

---

# 📚 Reference

**Bovik, Alan C. (Ed.).**

*Handbook of Image and Video Processing.*

Academic Press.

The chapter titles and authors are provided here for organizational and scholarly reference. Implementations in this repository are independently developed.

---

# 🗂️ Repository Organization

The repository follows the structure of the handbook's major sections.

```text
handbook-image-video-processing/
│
├── 01_introduction/
│
├── 02_basic_image_processing/
│
├── 03_image_video_enhancement_restoration/
│
├── 04_image_video_analysis/
│
├── 05_image_compression/
│
├── 06_video_compression/
│
├── 07_image_video_acquisition/
│
├── 08_rendering_assessment/
│
├── 09_storage_retrieval_communication/
│
├── 10_applications/
│
├── datasets/
├── notebooks/
├── tests/
├── results/
│
├── README.md
├── LICENSE
├── CITATION.cff
├── requirements.txt
├── environment.yml
└── pyproject.toml
```

---

# 📑 Contents

## Section I — Introduction

### 1.1 Introduction to Digital Image and Video Processing

**Alan C. Bovik**

Topics include:

* Digital images
* Digital video
* Image formation
* Sampling
* Quantization
* Spatial resolution
* Temporal resolution
* Image-processing pipelines
* Basic image/video representations

📁 `01_introduction/`

---

# Section II — Basic Image Processing Techniques

## 2.1 Basic Gray-Level Image Processing

**Alan C. Bovik**

Topics:

* Gray-level transformations
* Image histograms
* Histogram equalization
* Contrast enhancement
* Intensity transformations
* Point processing
* Spatial filtering

📁 `02_basic_image_processing/01_gray_level_processing/`

---

## 2.2 Basic Binary Image Processing

**Alan C. Bovik and Mita D. Desai**

Topics:

* Binary images
* Thresholding
* Connected components
* Binary morphology
* Region operations
* Object extraction

📁 `02_basic_image_processing/02_binary_image_processing/`

---

## 2.3 Basic Tools for Image Fourier Analysis

**Alan C. Bovik**

Topics:

* Fourier transform
* Discrete Fourier Transform
* Fast Fourier Transform
* Frequency-domain representation
* Fourier-domain filtering
* Magnitude and phase
* Convolution theorem
* Frequency response

📁 `02_basic_image_processing/03_fourier_analysis/`

---

# Section III — Image and Video Processing

## Image and Video Enhancement and Restoration

### 3.1 Basic Linear Filtering with Application to Image Enhancement

**Alan C. Bovik and Scott T. Acton**

Topics:

* Convolution
* Correlation
* Mean filtering
* Gaussian filtering
* Sharpening
* Laplacian filtering
* Unsharp masking
* Frequency-domain filtering

📁 `03_image_video_enhancement_restoration/01_linear_filtering/`

---

### 3.2 Nonlinear Filtering for Image Analysis and Enhancement

**Gonzalo R. Arce, José L. Paredes, and John Mullan**

Topics:

* Median filtering
* Order-statistic filters
* Rank filters
* Nonlinear smoothing
* Impulse-noise removal

📁 `03_image_video_enhancement_restoration/02_nonlinear_filtering/`

---

### 3.3 Morphological Filtering for Image Enhancement and Detection

Topics:

* Erosion
* Dilation
* Opening
* Closing
* Morphological gradients
* Morphological reconstruction
* Object detection

📁 `03_image_video_enhancement_restoration/03_morphological_filtering/`

---

### 3.4 Wavelet Denoising for Image Enhancement

Topics:

* Wavelet transforms
* Multiresolution analysis
* Wavelet thresholding
* Hard thresholding
* Soft thresholding
* Wavelet-based denoising

📁 `03_image_video_enhancement_restoration/04_wavelet_denoising/`

---

### 3.5 Basic Methods for Image Restoration and Identification

Topics:

* Image degradation
* Blur models
* Inverse filtering
* Wiener filtering
* Restoration from degraded observations

📁 `03_image_video_enhancement_restoration/05_image_restoration/`

---

### 3.6 Regularization in Image Restoration and Reconstruction

Topics:

* Ill-posed inverse problems
* Regularization
* Tikhonov regularization
* Total variation
* Optimization-based reconstruction

📁 `03_image_video_enhancement_restoration/06_regularization/`

---

### 3.7 Multichannel Image Recovery

Topics:

* Multichannel observations
* Multi-sensor image recovery
* Coupled reconstruction
* Vector-valued image processing

📁 `03_image_video_enhancement_restoration/07_multichannel_recovery/`

---

### 3.8 Multiframe Image Restoration

Topics:

* Multiple observations
* Image sequences
* Motion-aware restoration
* Multi-frame reconstruction

📁 `03_image_video_enhancement_restoration/08_multiframe_restoration/`

---

### 3.9 Iterative Image Restoration

Topics:

* Iterative reconstruction
* Gradient-based optimization
* Constrained restoration
* Iterative inverse problems

📁 `03_image_video_enhancement_restoration/09_iterative_restoration/`

---

### 3.10 Motion Detection and Estimation

**Janusz Konrad**

Topics:

* Motion detection
* Optical flow
* Block matching
* Motion vectors
* Motion estimation

📁 `03_image_video_enhancement_restoration/10_motion_detection_estimation/`

---

### 3.11 Video Enhancement and Restoration

Topics:

* Video denoising
* Temporal filtering
* Motion-compensated filtering
* Video restoration

📁 `03_image_video_enhancement_restoration/11_video_enhancement/`

---

### 3.12 3-D Shape Reconstruction from Multiple Views

Topics:

* Multiple-view geometry
* Stereo reconstruction
* 3-D reconstruction
* Depth estimation

📁 `03_image_video_enhancement_restoration/12_3d_reconstruction/`

---

### 3.13 Image Sequence Stabilization, Mosaicking, and Superresolution

Topics:

* Image registration
* Video stabilization
* Image mosaicking
* Multi-frame superresolution

📁 `03_image_video_enhancement_restoration/13_stabilization_mosaicking_superresolution/`

---

# Section IV — Image and Video Analysis

## Image Representations and Image Models

Topics include:

* Computational models of human vision
* Multiscale image decompositions
* Wavelets
* Random field models
* Image modulation models
* Image noise models
* Color and multispectral image representation

📁 `04_image_video_analysis/`

---

## Image and Video Classification and Segmentation

Topics:

* Statistical image segmentation
* Texture classification
* Texture segmentation
* Video segmentation
* Adaptive segmentation
* Neural segmentation

Example methods:

* Statistical classification
* Texture descriptors
* Clustering
* Region growing
* Neural networks
* CNN-based segmentation

---

## Edge and Boundary Detection

Topics:

* Gradient operators
* Sobel
* Prewitt
* Roberts
* Laplacian
* Laplacian of Gaussian
* Canny edge detection
* Diffusion-based edge detection

---

# Section V — Image Compression

## 5.1 Lossless Coding

Topics:

* Entropy
* Huffman coding
* Arithmetic coding
* Run-length coding
* Predictive coding

---

## 5.2 Block Truncation Coding

Topics:

* Block-based representation
* Statistical moments
* Quantization
* Rate-distortion behavior

---

## 5.3 Vector Quantization

Topics:

* Vector quantization
* Codebooks
* Lloyd algorithm
* LBG algorithm
* Quantization error

---

## 5.4 Wavelet Image Compression

Topics:

* Wavelet decomposition
* Subband coding
* Coefficient quantization
* Embedded coding

---

## 5.5 JPEG Lossy Image Compression

Topics:

* DCT
* Block processing
* Quantization
* Zig-zag scanning
* Entropy coding
* Rate-distortion analysis

---

## 5.6 JPEG Lossless Image Compression

Topics:

* Predictive coding
* Lossless reconstruction
* Entropy coding

---

## 5.7 Multispectral Image Coding

Topics:

* Spectral redundancy
* Spatial redundancy
* Multispectral compression
* Transform coding

📁 `05_image_compression/`

---

# Section VI — Video Compression

Topics:

* Video coding fundamentals
* Temporal redundancy
* Spatial redundancy
* Motion estimation
* Motion compensation
* H.261
* MPEG-1
* MPEG-2
* MPEG-4
* MPEG-7
* Object-based video coding
* Spatiotemporal subband coding

📁 `06_video_compression/`

---

# Section VII — Image and Video Acquisition

## 7.1 Image Scanning, Sampling, and Interpolation

Topics:

* Sampling theorem
* Spatial sampling
* Aliasing
* Reconstruction
* Interpolation

---

## 7.2 Video Sampling and Interpolation

Topics:

* Temporal sampling
* Spatial-temporal sampling
* Frame interpolation
* Motion-aware interpolation

📁 `07_image_video_acquisition/`

---

# Section VIII — Image and Video Rendering and Assessment

## 8.1 Image Quantization, Halftoning, and Printing

Topics:

* Quantization
* Gray-level quantization
* Halftoning
* Dithering
* Digital printing

---

## 8.2 Perceptual Criteria for Image Quality Evaluation

Topics:

* Image quality
* Human visual perception
* Objective quality metrics
* Perceptual quality
* Distortion measures

Metrics may include:

```text
MSE
RMSE
PSNR
SSIM
MS-SSIM
```

📁 `08_rendering_assessment/`

---

# Section IX — Image and Video Storage, Retrieval and Communication

Topics:

* Image indexing
* Video indexing
* Content-based retrieval
* Video browsing
* Multimedia databases
* Image/video communication networks
* Digital watermarking
* Copyright protection
* Authentication

📁 `09_storage_retrieval_communication/`

---

# Section X — Applications of Image Processing

This section implements application-oriented image-processing systems.

## 10.1 Synthetic Aperture Radar

Topics:

* SAR imaging
* Range processing
* Azimuth processing
* SAR reconstruction

📁 `10_applications/01_sar/`

---

## 10.2 Computed Tomography

Topics:

* Projection data
* Radon transform
* Sinogram
* Filtered back projection
* CT reconstruction

📁 `10_applications/02_computed_tomography/`

---

## 10.3 Cardiac Image Processing

Topics:

* Cardiac imaging
* Motion analysis
* Segmentation
* Functional measurements

📁 `10_applications/03_cardiac_imaging/`

---

## 10.4 Computer-Aided Detection for Screening Mammography

Topics:

* Mammographic image processing
* Feature extraction
* Detection
* Classification

📁 `10_applications/04_mammography_cad/`

---

## 10.5 Fingerprint Classification and Matching

Topics:

* Fingerprint preprocessing
* Ridge detection
* Orientation fields
* Minutiae extraction
* Fingerprint matching

📁 `10_applications/05_fingerprint/`

---

## 10.6 Probabilistic, View-Based, and Modular Models for Human Face Recognition

Topics:

* Face representation
* Feature extraction
* Probabilistic models
* View-based recognition
* Modular recognition systems

📁 `10_applications/06_face_recognition/`

---

## 10.7 Confocal Microscopy

Topics:

* Microscopy image processing
* Noise reduction
* Contrast enhancement
* Biological image analysis

📁 `10_applications/07_confocal_microscopy/`

---

## 10.8 Bayesian Automated Target Recognition

Topics:

* Bayesian inference
* Statistical target recognition
* Feature-based classification
* Automated recognition

📁 `10_applications/08_automated_target_recognition/`

---

# 🧮 Mathematical Foundations

The repository emphasizes the mathematical foundations behind image and video processing.

Important topics include:

```text
Linear Algebra
      │
      ├── Matrix operations
      ├── Eigenvalues / Eigenvectors
      └── Singular Value Decomposition
      │
Fourier Analysis
      │
      ├── DFT
      ├── FFT
      ├── Convolution theorem
      └── Frequency-domain filtering
      │
Probability & Statistics
      │
      ├── Random variables
      ├── Probability distributions
      ├── Bayesian inference
      └── Statistical estimation
      │
Optimization
      │
      ├── Gradient descent
      ├── Regularization
      ├── Inverse problems
      └── Variational methods
      │
Multiscale Analysis
      │
      ├── Wavelets
      ├── Pyramids
      └── Multiresolution representations
```

---

# 💻 Implementation Philosophy

Each algorithm is implemented with an emphasis on **clarity before abstraction**.

Where appropriate, implementations are provided at multiple levels:

```text
Mathematical formulation
        ↓
From-scratch implementation
        ↓
NumPy implementation
        ↓
Scientific-library implementation
        ↓
Visualization
        ↓
Quantitative evaluation
```

For example:

```text
Gaussian Filtering
        │
        ├── Mathematical formulation
        │
        ├── Kernel generation
        │
        ├── Manual convolution
        │
        ├── NumPy/SciPy implementation
        │
        ├── Visualization
        │
        └── Runtime comparison
```

---

# 🐍 Technology Stack

The primary implementation language is **Python**.

Core libraries:

| Library      | Purpose                          |
| ------------ | -------------------------------- |
| NumPy        | Numerical computing              |
| SciPy        | Scientific computing             |
| scikit-image | Image processing                 |
| OpenCV       | Computer vision                  |
| PyWavelets   | Wavelet processing               |
| Matplotlib   | Visualization                    |
| pandas       | Data analysis                    |
| PyTorch      | Machine learning / deep learning |

---

# 📓 Jupyter Notebooks

Interactive notebooks are provided for concepts that benefit from visualization.

Example:

```text
notebooks/
│
├── 01_basic_image_processing.ipynb
├── 02_fourier_analysis.ipynb
├── 03_image_restoration.ipynb
├── 04_wavelets.ipynb
├── 05_segmentation.ipynb
├── 06_edge_detection.ipynb
├── 07_image_compression.ipynb
├── 08_video_processing.ipynb
└── 09_image_quality.ipynb
```

The notebooks are intended to complement, rather than replace, the implementations in the individual chapter directories.

---

# 📊 Evaluation

Algorithms are evaluated using appropriate quantitative and qualitative measures.

Common metrics include:

### Image Quality

```text
MSE
RMSE
PSNR
SSIM
MS-SSIM
```

### Compression

```text
Compression Ratio
Bits Per Pixel
Rate-Distortion
```

### Classification

```text
Accuracy
Precision
Recall
F1-score
Confusion Matrix
```

### Reconstruction

```text
Reconstruction Error
PSNR
SSIM
RMSE
```

### Computational Performance

```text
Runtime
Memory Usage
Number of Operations
Model Parameters
```

---

# 🧪 Testing

Unit tests are maintained under:

```text
tests/
```

The objective is to verify both numerical correctness and expected algorithmic behavior.

Example:

```bash
pytest tests/
```

Tests may include:

* Fourier transform consistency
* Filter correctness
* Reconstruction accuracy
* Compression/decompression consistency
* Segmentation behavior
* Numerical stability

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/<USERNAME>/handbook-image-video-processing.git

cd handbook-image-video-processing
```

Create an environment:

```bash
conda create -n hivp python=3.11
conda activate hivp
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or install the project:

```bash
pip install -e .
```

---

# 🚀 Quick Example

Example workflow:

```python
import numpy as np
from skimage import data

image = data.camera()

# Apply an image-processing algorithm
result = gaussian_filter(image, sigma=2)

# Visualize
plot_image(image)
plot_image(result)
```

Individual chapters contain more detailed examples.

---

# 📈 Learning Path

For someone learning image processing, the repository can be explored in the following order:

```text
01 Introduction
      ↓
02 Basic Image Processing
      ↓
03 Fourier Analysis
      ↓
04 Filtering
      ↓
05 Image Restoration
      ↓
06 Wavelets
      ↓
07 Segmentation
      ↓
08 Edge Detection
      ↓
09 Image Compression
      ↓
10 Video Compression
      ↓
11 Image Quality
      ↓
12 Image/Video Retrieval
      ↓
13 Applications
```

---

# 🔬 Classical Methods → Modern Methods

An additional goal of this repository is to demonstrate how classical image-processing concepts connect to modern computational imaging and machine learning.

For example:

```text
Classical Image Processing
          │
          ├── Convolution
          │       ↓
          │    CNNs
          │
          ├── Fourier Transform
          │       ↓
          │    Fourier Neural Networks
          │
          ├── Regularization
          │       ↓
          │    Learned Priors
          │
          ├── Inverse Problems
          │       ↓
          │    Deep Reconstruction
          │
          ├── Wavelets
          │       ↓
          │    Multiscale Neural Networks
          │
          └── Bayesian Models
                  ↓
              Probabilistic ML
```

This provides a bridge between **classical signal/image processing and modern AI-based image reconstruction and analysis**.

---

# 🧠 From Theory to Experiment

For each major algorithm, the preferred workflow is:

```text
Theory
  ↓
Mathematical Derivation
  ↓
Algorithm
  ↓
Implementation
  ↓
Synthetic Example
  ↓
Real Image / Video
  ↓
Visualization
  ↓
Quantitative Evaluation
  ↓
Comparison
```

This structure is intended to make the repository useful not only as a code collection but also as a **learning and research reference**.

---

# 📂 Datasets

Datasets are **not stored directly in this repository** unless their licenses explicitly permit redistribution.

Instead, dataset documentation will be provided under:

```text
datasets/
└── README.md
```

Each dataset entry should specify:

* Dataset name
* Source
* URL
* License
* Download instructions
* Expected directory structure
* Relevant experiments

---

# 📜 Reproducibility

Experiments should provide, where applicable:

```text
Random seed
Dataset information
Image resolution
Algorithm parameters
Software versions
Hardware information
Evaluation metrics
```

The goal is to make experimental results reproducible.

---

# 📌 Project Status

| Section                                 | Status |
| --------------------------------------- | :----: |
| Section I — Introduction                |    ⬜   |
| Section II — Basic Image Processing     |    ⬜   |
| Section III — Enhancement & Restoration |    ⬜   |
| Section IV — Image & Video Analysis     |    ⬜   |
| Section V — Image Compression           |    ⬜   |
| Section VI — Video Compression          |    ⬜   |
| Section VII — Acquisition               |    ⬜   |
| Section VIII — Rendering & Assessment   |    ⬜   |
| Section IX — Storage & Communication    |    ⬜   |
| Section X — Applications                |    ⬜   |

Legend:

```text
⬜ Not started
🟡 In progress
🧪 Experimental
✅ Implemented
```

---

# 🤝 Contributing

Contributions are welcome.

Possible contributions include:

* New algorithm implementations
* Bug fixes
* Unit tests
* Documentation
* Mathematical explanations
* Visualization improvements
* Benchmarking
* Dataset integration
* Modern implementations of classical algorithms

### Contribution workflow

```bash
git clone <repository>

git checkout -b feature/new-algorithm

# Implement and test

git add .
git commit -m "Add <algorithm> implementation"

git push origin feature/new-algorithm
```

Then open a pull request.

---

# ⚖️ Copyright and Attribution

This repository is an **independent educational implementation** inspired by concepts discussed in the handbook.

The repository does **not** intend to reproduce:

* Copyrighted book text
* Book figures
* Tables reproduced from the book
* Publisher-provided source code
* Other copyrighted material

All implementations are independently written.

Please consult the original book for the complete theoretical treatment and original references.

---

# 📚 Primary Reference

> **Alan C. Bovik (Editor)**
> *Handbook of Image and Video Processing*
> Academic Press

Individual chapters should additionally cite their respective chapter authors and original references where applicable.

---

# 📄 License

Unless otherwise specified, the original source code in this repository is released under the license specified in:

```text
LICENSE
```

Third-party libraries, datasets, and referenced materials remain subject to their respective licenses.

---

# ⭐ Motivation

Image and video processing is built on a remarkably rich collection of ideas:

> **Sampling → Filtering → Fourier Analysis → Restoration → Representation → Segmentation → Compression → Reconstruction → Recognition**

Many modern computer vision and computational imaging systems are extensions of these fundamental concepts.

This repository aims to make those foundations **computational, visual, reproducible, and accessible**.

---

## 🌟 If You Find This Repository Useful

Consider:

* ⭐ Starring the repository
* 🐛 Reporting issues
* 💡 Suggesting implementations
* 🤝 Contributing improvements
* 📖 Citing the original handbook

---

<p align="center">

**Learn the mathematics. Implement the algorithm. Visualize the result. Understand the intuition.**

</p>
