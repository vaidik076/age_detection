# Age Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to detect the age group of a person from an image using the UTKFace dataset.

## 👶 Age Groups
The model classifies images into the following age groups:
- Child (0-12)
- Teen (13-19)
- Young Adult (20-29)
- Adult (30-44)
- Middle-aged (45-59)
- Senior (60+)

## 🧠 Model Accuracy
- Achieved test accuracy: **87.16%**

## 🛠 Requirements
Install dependencies with:

```bash
pip install -r requirements.txt


🚀 Usage

def predict_age_group(img_path):
    img = cv2.imread(img_path)
    img = cv2.resize(img, (64, 64)) / 255.0
    img = np.expand_dims(img, axis=0)

    prediction = model.predict(img)
    predicted_class = np.argmax(prediction)

    age_groups = ['Child', 'Teen', 'Young Adult', 'Adult', 'Middle-aged', 'Senior']
    return age_groups[predicted_class]

📦 Files
age_detection.ipynb - Main notebook

age_detection_model.h5 - Trained age detection model

requirements.txt - Python dependencies

📸 Dataset
This project uses the UTKFace dataset, which contains over 20,000 face images with age, gender, and ethnicity labels.

Note: Dataset is not included due to size. Download it separately from:
UTKFace Dataset on Kaggle

🤝 License
Free to use for academic and non-commercial purposes.