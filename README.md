# Capsicum Plant Analysis 🌶️

This project uses a Jupyter Notebook to analyze and classify different varieties of capsicum (bell pepper) plants based on various attributes.

## 📘 Project Contents

- `Capsicum_Plant_Analysis.ipynb`: Main notebook containing analysis, visualizations, and classification steps.

## 🔍 Features

- Data loading and preprocessing
- Visualization of plant characteristics
- Classification model (e.g., Decision Tree, SVM, etc.)
- Performance evaluation

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Ryanbastian123/Capsicum_Plant_Analysis.git
   cd Capsicum_Plant_Analysis
## 📁 Dataset Setup

This notebook relies on a Capsicum Leaf Dataset that must be stored in your Google Drive.

### 📥 Step 1: Download the Dataset

Download the dataset from your preferred source or link (e.g., Kaggle or shared drive).  
Make sure the folder contains images or files used in the notebook.

> Example folder structure:
> ```
> /MyDrive/Capsicum_Dataset/
> ├── Green/
> ├── Red/
> └── Yellow/
> ```

### 📤 Step 2: Upload to Google Drive

Upload the dataset folder (e.g., `Capsicum_Dataset`) to your Google Drive root or a known path.

---

### 🔗 Step 3: Connect Google Drive in the Notebook

In the first code cell of your notebook, mount Google Drive like this:

```python
from google.colab import drive
drive.mount('/content/drive')
