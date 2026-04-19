
# Deep Learning Based Disease Classification System Using CNNs

Automated disease classification system using CNN architectures
trained on medical imaging data.

## Technologies Used
- Python, TensorFlow, Keras
- ResNeXt50 (custom grouped convolution architecture)
- VGG16 (transfer learning from ImageNet)
- Keras ImageDataGenerator (data augmentation)

## What it does
- Built and evaluated CNN architectures for automated disease
  classification from chest X-ray images
- Applied three data augmentation strategies to address
  class imbalance
- Evaluated with classification report, confusion matrix,
  accuracy and loss curves across 20 epochs

## Results
- ResNeXt50: 94.70% accuracy
- VGG16: 96.76% accuracy
- Metrics: precision, recall, F1-score per class

## Dataset
Chest X-Ray (Pneumonia, COVID-19, Tuberculosis) — Kaggle
7,135 images — 4 classes: Normal, COVID-19, Pneumonia, Tuberculosis

## Files
- project_on_chest_x-ray_classification.ipynb

## How to Run
1. Clone the repo
2. Open notebook in Google Colab or Jupyter
3. Connect to Kaggle dataset and run all cells
