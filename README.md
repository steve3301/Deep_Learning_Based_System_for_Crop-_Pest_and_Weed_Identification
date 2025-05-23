🌿 Model2 – Crop Health Classification with Deep Learning
This project uses deep learning to classify crop health conditions, including diseases, pests, weeds, and healthy states, using a custom-trained image classification model.

📌 Project Overview
This deep learning model is designed to help farmers and agricultural professionals identify plant health issues using image data. The model is trained on a custom ImageFolder dataset and fine-tuned for high accuracy and real-time performance.

⚙️ Setup Instructions
Install Required Libraries:

pip install numpy pandas torch torchvision matplotlib scikit-learn

Or use the requirements.txt file:

pip install -r requirements.txt

📁 Project Structure
🧹 Data Loading & Preprocessing
Using torchvision.transforms and datasets.ImageFolder

🏗️ Model Architecture
Custom or pre-trained architecture with fine-tuning

🧪 Training, Validation & Testing
Includes loss tracking and metrics logging

📊 Visualizations
Accuracy and loss curves, confusion matrix, sample predictions

💾 Model Persistence
Saving and loading for inference/deployment

🗂️ Dataset
This project uses a custom dataset hosted on Kaggle:
🔗 Crop Pest and Disease Detection – Kaggle

Classes include:

🌾 Plant diseases

🐛 Pests

🌿 Weeds

✅ Healthy crops

The dataset is structured using class-wise folders, ideal for PyTorch's ImageFolder.

📚 Libraries Used
numpy

pandas

matplotlib

scikit-learn

torch

torchvision

📈 Results
The notebook provides:

✅ Accuracy and loss metrics

📉 Training and validation curves

📷 Sample prediction images

The final model is optimized for real-time mobile deployment, making it practical for field use.

🧑‍💻 Author
Shane Steve A – Final Year B.Tech (AI & Data Science)
Saranathan College of Engineering

👥 Team Members
Shane Steve A

Nafees Ahamed A

Sri Sabari I.T
