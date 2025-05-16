# Medical Image Segmentation using U-Net (PyTorch)

This project demonstrates the use of a pre-trained U-Net model for medical image segmentation. U-Net is a powerful convolutional neural network architecture specifically designed for biomedical image processing tasks. This example showcases how to load a trained model and perform inference on sample test images.

## Project Overview

- **Model:** U-Net (pre-trained)
- **Framework:** PyTorch
- **Task:** Semantic segmentation of medical images
- **Application:** Highlighting anatomical structures in biomedical images
- **Hardware:** CPU (for demonstration purposes)

## Features

- Load and use a pre-trained U-Net model for inference
- Segment medical images with high localization accuracy
- Visualize input images and their corresponding segmented outputs
- Easy to run on Google Colab (no GPU required)

## File Structure

- `Medical_Image_Segmentation.ipynb` – Main Jupyter notebook with step-by-step implementation
- `README.md` – Project overview and instructions

## Getting Started

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Run each cell sequentially to:
   - Install dependencies
   - Load the pre-trained U-Net model
   - Perform segmentation on sample medical images
   - Visualize results

## Requirements

numpy==1.23.5
pandas==2.2.2
matplotlib==3.9.0
opencv-python-headless==4.10.0.82
torch==2.3.1
torchvision==0.18.1
scikit-image==0.24.0
nibabel==5.2.1
scikit-learn

## How it Works

The notebook loads a pre-trained U-Net model from remote storage and applies it to segment sample biomedical images. The U-Net model’s architecture is based on an encoder-decoder structure with skip connections, enabling precise localization even with limited data. Since the demo runs on a CPU, it emphasizes model behavior and output over performance.

## Results

The model successfully segments anatomical features from test images, demonstrating its effectiveness in biomedical image analysis tasks.

## Credits

- U-Net architecture: Olaf Ronneberger et al., "U-Net: Convolutional Networks for Biomedical Image Segmentation"
- PyTorch: https://pytorch.org/

## License

This project is for educational and demonstration purposes.
