# Hate Speech Classification
## 📝 Description
This repository contains code, models, and resources for building and evaluating a NLP model focused on [specific task, e.g., hate speech classification]. The model leverages advanced NLP techniques, including word embeddings, Recurrent Neural Networks (RNNs), and Transformer models like BERT, to accurately analyze and classify text data.
## ⏳Dataset
- Download the dataset for custom training
- https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset

## 🔗🖥️ Installation
## 🛠️ Requirements
- python 3.8+
- numpy 
- pandas 
- tensorflow
- matplotlib
- seaborn
- nltk
- regex
- scikit-learn
- from-root
- google-cloud-storage
- fastapi==0.78.0
- uvicorn==0.18.3
- Jinja2==3.1.2

## ⚙️ Setup
### 👨‍🏭 Project Workflows

- constants
- config_enity
- artifact_enity
- components
- pipeline
- app.py

### 👨‍💻 How to run
```bash
conda create -n hate python=3.8 -y
```

```bash
conda activate hate
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```
### 💿 Gcloud cli
https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe

```bash
gcloud init
```