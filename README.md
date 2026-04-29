# Image Processing & Computer Vision - Five Mini Projects

**Course:** Image Processing & Computer Vision  
**Student Name:** Mohit Dhoundiyal  
**Roll No:** 2301010150
**Date:** April 28, 2026  

---

## Project Overview

This repository contains **five integrated mini-projects** that comprehensively cover Image Processing and Computer Vision fundamentals. Each assignment addresses real-world problems using Python with OpenCV, NumPy, and SciPy.

### Projects Summary

| # | Title | Learning Focus | Key Techniques |
|---|-------|-----------------|-----------------|
| **1** | Smart Document Scanner | Sampling & Quantization | Resolution analysis, bit-depth reduction |
| **2** | Image Restoration | Noise & Filtering | Gaussian/Salt-Pepper noise, Mean/Median/Gaussian filters |
| **3** | Medical Imaging System | Compression & Segmentation | Run-Length Encoding, Thresholding, Morphology |
| **4** | Traffic Monitoring | Feature Extraction | Edge detection, Contours, ORB features |
| **5** | Capstone: Intelligent System | End-to-End Pipeline | Integration of all techniques (Units 1-4) |

---

## Installation

### Prerequisites
- Python 3.8+
- pip or conda

### Setup Instructions

1. **Clone or navigate to the project directory:**
   ```bash
   cd image_projects
   ```
2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate          # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Dependencies
- `opencv-python` - Image processing
- `numpy` - Numerical computations
- `matplotlib` - Visualization
- `scikit-image` - Advanced image processing
- `scipy` - Scientific computing
- `Pillow` - Image I/O
- `imutils` - OpenCV utilities

---

## Project Structure

```
image_projects/
├── lab-experiments/            # Lab experiment scripts (run individually)
│   ├── asmt1_scanner/          # Assignment 1: Document Scanning
│   │   └── scanner.py          # Main scmage Restoration
│   │   └── restoration.py      # Main script - noise filtering
│   ├── asmt3_medical/          # Assignment 3: Medical Imaging
│   │   └── medical_image_system.py # Main script - compression & segmentation
│   ├── asmt4_traffic/          # Assignment 4: Traffic Monitoring
│   │   └── traffic_monitoring.py   # Main script - feature extraction
│   ├── asmt5_intelligent_system/   # Assignment 5: Capstone
│   │   └── main.py             # Main capstone script - end-to-end pipeline
│   └── common/
│       └── utils.py            # Shared utility functions
├── assets/                     # Sample images (download manually)
│   ├── asmt1/                  # Document images
│   ├── asmt2/                  # Surveillance/street images
│   ├── asmt3/                  # Medical/X-ray images
│   ├── asmt4/                  # Traffic/intersection images
│   └── asmt5/                  # General purpose images
├── outputs/                    # Generated results (auto-created)
├── requirements.txt            # Dependencies
├── run_all.py                  # Test harness (runs all 5 assignments)
├── cleanup_outputs.py          # Output cleanup utility
└── README.md                   # This file
```

### Lab Experiments Directory Structure
The `lab-experiments/` directory contains all individual assignment scripts. Each can be run independently:
- Each assignment is self-contained with its own directory
- All scripts share utilities from `common/utils.py`
- Run any assignment individually with custom images
- Use `run_all.py` to batch test all assignments

---

## Usage Instructions

### Running Individual Assignments
