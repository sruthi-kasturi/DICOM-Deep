# DicomDeep

Welcome to **DicomDeep**! This repository is dedicated to the innovative processing and analysis of DICOM images. Our goal is to provide a comprehensive toolkit for reading, processing, and visualizing medical images, focusing on extracting meaningful insights through advanced image processing techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Processing Steps](#processing-steps)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributors](#contributors)

## Project Overview

**DicomDeep** is a cutting-edge project designed to work with medical images in the DICOM format. This project encompasses loading DICOM images, processing them to extract specific windows, and visualizing these images for detailed analysis. The techniques and methods used aim to aid medical professionals in gaining deeper insights from medical scans.

## Dataset

The dataset used in this project consists of 223 DICOM images provided in a zipped folder (`Dicom Images.zip`). The images are processed to sort, extract the middle slice, and visualize them using lung and bone window settings.

### Example File

An example DICOM file (`fee31f793e55.dcm`) is provided to demonstrate the format and structure of the dataset.

## Processing Steps

1. **Load the DICOM Images:**
   - Extract the DICOM images from the provided zip file.
   - Load the images into a list for processing.

2. **Sort the Images:**
   - Sort the images based on the `InstanceNumber` attribute to ensure proper sequence.

3. **Extract and Visualize Specific Windows:**
   - Define lung and bone window settings for the images.
   - Extract these windows from the DICOM images to highlight specific features.
   - Visualize the original and windowed images side-by-side in a 1x3 grid to compare different views.

4. **Save the Processed Images:**
   - Save the visualized images as 16-bit depth PNG files for high-quality analysis and reporting.

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/dicomdeep.git
   cd dicomdeep

2. Run the processing script:
Follow the instructions in the provided scripts to process and visualize the DICOM images.

## Dependencies
- Python 3.7+
- NumPy
- Matplotlib
- pydicom
- os
- zipfile

## Contributors
Sruthi Kasturi
For questions or collaboration, feel free to contact me at skastur6@asu.edu
