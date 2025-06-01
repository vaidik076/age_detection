# Age Group Detection using CNN

This project uses a Convolutional Neural Network (CNN) to classify a person’s age group from their face image. The model was trained on the UTKFace dataset and predicts one of the following age groups:

- Child
- Teen
- Young Adult
- Adult
- Middle-aged
- Senior

## 📁 Project Structure

- `age_model_checkpoint.weights.h5`: Saved model weights
- `age_group_predictor.ipynb`: Jupyter notebook with all training and testing steps
- `main_script.py`: (Optional) Script version of the notebook
- `requirements.txt`: List of dependencies
- `data/`: Sample images for testing

## ⚙️ Setup Instructions

1. Clone the repository:

### 📥 Dataset

Download the UTKFace dataset from the official repository:
[https://susanqq.github.io/UTKFace/](https://susanqq.github.io/UTKFace/)

After downloading, extract the dataset and place it inside the `data/` folder like this:

