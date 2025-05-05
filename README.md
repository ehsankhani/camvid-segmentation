# camvid-segmentation
Semantic segmentation on the CamVid dataset using deep learning models implemented in PyTorch. This project trains and evaluates a segmentation model to label urban driving scenes.

This project performs semantic segmentation on the [CamVid dataset](https://github.com/lih627/CamVid). It leverages PyTorch and deep learning techniques to classify each pixel in urban driving scenes.

## 📁 Features

- Preprocessing and loading of CamVid images and labels
- Deep learning model (e.g., U-Net) for segmentation
- Training and validation pipeline
- Visualization of model predictions

## 🧰 Requirements

Before running the notebook, set up a Python environment and install the dependencies listed in `requirements.txt`.

### 🔹 Option 1: Using `venv` (Standard Virtual Environment)

```bash
# Create a virtual environment
python -m venv venv

# Activate the environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Upgrade pip (recommended)
pip install --upgrade pip

# Install the required packages
pip install -r requirements.txt'
```


### 🔹 Option 2: Using conda (Anaconda/Miniconda)
```bash
# 1. Create a conda env
conda create -n camvid-env python=3.12

# 2. Activate it
conda activate camvid-env

# 3. Ensure pip is available
conda install pip

# 4. Install dependencies
pip install -r requirements.txt
```

## 🚀 How to Run
Clone the repo
```bash
git clone https://github.com/ehsankhani/camvid-segmentation
cd camvid-segmentation
```
### -Install dependencies
Use either the venv or conda instructions above.
### -Launch Jupyter Notebook
```bash
jupyter notebook camvid-segmentation.ipynb
```
### Follow the notebook to:

- Load & preprocess images
- Train the segmentation model
- Evaluate & visualize predictions

📂 Dataset
Download the CamVid dataset from the official site and place it under a folder named data/ (or adjust paths in the notebook).
-- link to the dataset : [CamVid dataset](https://github.com/lih627/CamVid)
```
CamVid-main/
├── CamVidColor11/
├── CamVidGray/
├── CamVid_Label/
├── CamVid_RGB/
├── SegNetanno/
├── .gitignore
├── best_model.pth
├── camvid_data.py
├── camvid_test.txt
├── camvid_train.txt
├── camvid_trainval.txt
├── camvid_val.txt
├── LICENSE
├── camvid-segmentation.ipynb
├── README.md
├── requirements.txt
├── segmentation_examples.png
└── training_metrics.png
```
