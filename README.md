# Deep Learning-based Model Evaluation for Tumour Detection in Breast Ultrasound Images

This repository contains the code and outputs for my MSc dissertation:  
**"Deep Learning-based Model Evaluation for Tumour Detection in Breast Ultrasound Images"**  
Maynooth University, 2025 — Gabriela Gonçalves Simões

---

## Contents
- Jupyter notebooks for model training and evaluation:
  - `VGG16_3class.ipynb`
  - `ResNet-50_3class.ipynb`
  - `Xception_3class.ipynb`
- Preprocessing scripts (`Ultrasound_preprocessing.ipynb`) -- originally from `https://github.com/christopherkormpos/TumorNet`
- Test predictions (`outputs_*`)

---

## How to run

1. **Clone the repo**
~~~bash
   git clone https://github.com/GabrielaGSimoes/breast-ultrasound-cnn
   cd breast-ultrasound-cnn
~~~ 

2. **Get Python + Jupyter**
    Install Jupyter if not already:
~~~bash
pip install jupyterlab
~~~    

3. **Download the BUSI dataset**
The dataset is available on Kaggle:
    https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset

Unzip it

4. **Open a notebook**
~~~bash
jupyter lab notebooks/Xception_3class.ipynb
~~~
Run all cells to train or evaluate a model.

## Results
    Xception — F1 = 0.97, malignant recall = 0.98

    VGG16 — F1 = 0.96

    ResNet-50 — F1 = 0.71

    Outputs (confusion matrices, predictions) are included in notebooks.

## Reproducibility
Random seed: 42


## Citation
If you use this code, please cite:

Simões, G. G. (2025). Deep Learning-based Model Evaluation for Tumour Detection in Breast Ultrasound Images. MSc Dissertation, Maynooth University.
GitHub: https://github.com/GabrielaGSimoes/breast-ultrasound-cnn
