# Pneumonia Detection from Chest X-rays

This project uses deep learning to classify chest X-ray images as **Pneumonia** or **Normal (Healthy)**. It leverages transfer learning with a fine-tuned model to achieve high accuracy in detecting pneumonia from radiographic images.

## Dataset

The dataset consists of labeled chest X-ray images divided into two classes:
- Pneumonia
- Normal (Healthy)

The dataset is split into training, validation, and test sets to ensure fair evaluation.

## How to Use

1. Clone this repository.
2. Place the dataset in `train/`, `val/`, and `test/` folders.
3. Open the `pneumonia.ipynb` notebook in Google Colab or Jupyter Notebook.
4. Run all cells to train and evaluate the model.

## Requirements

- Python 3.x  
- PyTorch  
- torchvision  
- scikit-learn  
- NumPy

Install dependencies:

```bash
pip install torch torchvision scikit-learn numpy
```

### If you need the trained model weights (pneumonia.pth), feel free to email me at:
📧 k.prabhav2005@gmail.com
