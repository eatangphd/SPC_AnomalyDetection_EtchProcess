# 🔬 Semiconductor Process Integration Toolkit

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZhVuZGrC9vp9mhN_6m6ZvARIaL3YncWB?usp=sharing)

## 📋 Overview

**Semiconductor Process Integration Toolkit** is a Python-based portfolio project demonstrating core skills required for semiconductor process integration engineering. Using simulated etch process data, it applies Statistical Process Control (SPC), Fault Detection & Classification (FDC), root cause analysis, and process capability (CpK) calculations — all directly transferable to high-volume manufacturing environments at Intel, TSMC, and other fabs.

### 🎯 Key Features

- **SPC Control Charts**: Real-time process monitoring with 3σ upper/lower control limits
- **FDC Anomaly Detection**: Isolation Forest algorithm to flag process excursions (parallel to fab fault detection)
- **Root Cause Analysis**: Correlation matrix identifying relationships between etch rate and process parameters (temperature, pressure)
- **Process Capability (CpK)**: Quantifies process performance against specification limits
- **Quality Event Form (QEF) Simulation**: CAPA-style summary with root cause hypothesis and disposition recommendations
- **Google Colab Ready**: Run instantly in your browser without installation

## 🚀 Quick Start

### Run in Google Colab (Recommended)

Click the badge below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZhVuZGrC9vp9mhN_6m6ZvARIaL3YncWB?usp=sharing)

### 📈 Sample Ouput
Process Capability Analysis (CpK)
================================
- Upper Spec Limit (USL): 160 nm/min
- Lower Spec Limit (LSL): 140 nm/min
- Process Mean: 150.2 nm/min
- Process Std Dev: 2.85
- Cp: 1.17
- CpK: 1.09


### 🤝 Contributing
Feel free to fork this project and adapt it for your own use case. Pull requests are welcome!

### 📝 License
This project is open source and available under the MIT License.

### ⭐ Acknowledgments
- Built with **Python** in **Google Colab** and **DeepSeek**
- Visualization powered by **Matplotlib** and **Seaborn**
- Machine learning anomaly detection via **Scikit-learn Isolation Forest**
- Inspired by semiconductor process control methodologies used at **Intel**, **TSMC**, and **Micron**

Inspired by semiconductor process control methodologies used at Intel, TSMC, and Micron

### 📧 Contact email: liz21atang@gmail.com
**Elizabeth (Epse Kombe) Atang**: [![LinkedIn](https://upload.wikimedia.org/wikipedia/commons/8/81/LinkedIn_icon.svg)](https://www.linkedin.com/in/elizabeth-atang-phd)

### Project Link: [![GitHub](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/eatangphd/SPC_AnomalyDetection_EtchProcess)




