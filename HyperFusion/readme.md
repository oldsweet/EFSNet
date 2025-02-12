# EFSNet: Efficient Frequency Selective Network for Hyperspectral Image Super-Resolution

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)]()
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()

## 📖 Abstract
Hyperspectral image super-resolution (SR) aims to generate high-resolution images from low-resolution hyperspectral images. Considering the significant differences in the dependency of features across various frequency domains in SR tasks, some methods perform SR reconstruction in the frequency domain. However, simply using Fourier or wavelet transforms to decompose features into fixed frequency components lacks flexibility and fails to dynamically focus on modeling high-value features. In this paper, we propose a dynamic spectral frequency selection model that decomposes features into disentangled frequency sub-bands. Specifically, we combine wavelet transform and wavelet decomposition, enabling simple frequency decomposition and selection, allowing the network to adaptively choose the most valuable frequency features for modeling.

## 📦 Requirements
- Python 3.8+
- PyTorch 1.6+
- CUDA 11.1+

## 📂Dataset
- [Pavia University](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)
- [Chikusei](https://naotoyokoya.com/Download.html)
- [Houston](https://hyperspectral.ee.uh.edu/?page_id=459)

## 🛠️Usage
Place the dataset in the dataset directory, and run the following command:
```bash
python main.py 
```

## 🔍 Contact

If you have any questions or suggestions, please submit an Issue or send a email to <lbs23@mails.jlu.edu.cn>.
