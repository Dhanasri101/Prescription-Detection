# Prescription-Detection
Recoginzing handwritten names of medicines prescribed by doctor's.

Overview
This project is designed to recognize handwritten prescriptions and match them with an existing database of medicines. It uses Optical Character Recognition (OCR) techniques along with Deep Learning models to extract and interpret text from handwritten prescriptions.

Features:
Handwritten prescription recognition using OCR and CNN models
Matching extracted text with a medicine database
User-friendly interface for pharmacists to verify and process prescriptions

Prerequisites:
Ensure you have the following installed:
Python 3.8+
pip (Python package manager)
Git (for cloning the repository)
Virtual environment (optional but recommended)
Installation
1. Clone the Repository
git clone https://github.com/Infi-09/Doctor-Prescripton-Handwritten-Recoginition.git
cd Doctor-Prescripton-Handwritten-Recoginition
2. Set Up Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
3. Install Dependencies

Usage:
1. Run the Application
python main.py
This will start the application and allow users to input prescription images for processing.
2. Testing the Model
To test the OCR and recognition model on sample data:
python test_model.py --image sample_prescription.jpg
3. Training the Model (If Needed)
If you want to retrain the model with a new dataset:
python train_model.py --dataset path_to_dataset
