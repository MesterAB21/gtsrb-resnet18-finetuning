# GTSRB Traffic Sign Classification with ResNet18

A deep learning project using **ResNet18 fine-tuning and transfer learning** to classify traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

## Dataset Preview

<img width="479" height="477" alt="image" src="https://github.com/user-attachments/assets/dd25d345-d79a-4c65-bba7-1e6d3ff93b3d" />

The GTSRB dataset contains more than **50,000 images across 43 traffic sign classes**, including speed limits, warning signs, and mandatory instructions.

- **Dataset:** [German Traffic Sign Recognition Benchmark](https://benchmark.ini.rub.de/gtsrb_dataset.html)
- **Model:** ResNet18
- **Framework:** PyTorch
- **Approach:** Transfer learning and fine-tuning
- **Task:** Multi-class image classification
- **Test Accuracy:** Approximately **91%**

## Methodology

- Applied image transformations compatible with pretrained ResNet18.
- Used transfer learning with a pretrained ImageNet model.
- Froze and unfroze model layers during fine-tuning.
- Applied learning-rate scheduling and early stopping.
- Evaluated predictions on unseen traffic-sign images and analyzed classification errors.

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Objective

Develop a model capable of recognizing and classifying traffic signs across 43 categories, supporting traffic-sign recognition research and intelligent transportation applications.

## Dataset Reference

Stallkamp et al., *The German Traffic Sign Recognition Benchmark: A multi-class classification competition*, IJCNN, 2011.
