# Retinal_Segmentetion_With_Bi_Level_Class_Balancing

This project performs semantic segmentation of retinal blood vessels from grayscale fundus images using a convolutional neural network (U-Net architecture).

## 🧠 Project Objective

The goal is to accurately extract fine blood vessel structures from retinal images, aiding early diagnosis of diseases like diabetic retinopathy, glaucoma, and hypertensive retinopathy.

## 📂 Dataset Structure

Ensure the following directory format before running the notebook:

#project/
│
├── data/
│ ├── images/ ← Retinal images (e.g., .jpg/.png)
│ └── masks/ ← Binary masks of vessels (same filenames)
├── Retinal_Segmentation_Complete.ipynb
├── requirements.txt
└── README.md

markdown
Copy
Edit

## ⚙️ Features

- U-Net model built using TensorFlow/Keras
- Preprocessing with OpenCV
- Image/mask resizing and normalization
- Binary cross-entropy loss and accuracy tracking
- Visualization of training accuracy and validation accuracy

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/retinal-vessel-segmentation.git
   cd retinal-vessel-segmentation
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Retinal_Segmentation_Complete.ipynb
📊 Results
The model achieves decent segmentation accuracy on the validation set with minimal epochs. Further improvements can be done by:

Adding data augmentation

Using deeper U-Net variants

Using Dice Loss instead of BCE

👨‍💻 Author
Safal Swayam
Aspiring AI Specialist & Deep Learning Researcher
