# Left Atrium Segmentation

Deep learning project for automated left atrium segmentation from cardiac MRI scans using U-Net architecture.

## Dataset

- **Source**: Medical Decathlon Task 02 (Heart)
- **Data**: 20 cardiac MRI scans → 4,542 2D slices with ground truth masks

## Model Architecture

- **Network**: U-Net with encoder-decoder + skip connections
- **Loss**: Dice Loss
- **Optimizer**: Adam (lr=1e-04)
- **Activation**: Sigmoid with 0.5 threshold

## Goal

Accurate left atrium segmentation for precise volume calculation in cardiac assessment.

## Setup

```bash
git clone <repo-url>
cd left-atrium-segmentation
pip install -r requirements.txt
```
