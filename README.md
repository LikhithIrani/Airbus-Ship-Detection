Airbus Ship Detection

This project is an implementation and analysis of the Airbus Ship Detection Challenge on Kaggle. The goal is to detect ships in satellite images using machine learning and computer vision techniques.

---

📁 Project Structure

ML-Project/
├── .gitignore
├── README.md
├── airbus_ship_detection_analysis.ipynb
└── data/
├── test_v2/
├── train_v2/
└── ... (other data files)

---

⚙️ Setup Instructions

1. Clone the Repository

git clone https://github.com/yourusername/Airbus-Ship-Detection.git
cd Airbus-Ship-Detection

2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate # On macOS/Linux
venv\Scripts\activate # On Windows

3. Install Dependencies

pip install -r requirements.txt

If you don’t have a requirements.txt, you can generate one using:
pip freeze > requirements.txt

4. Download the Dataset

- Download the Airbus Ship Detection dataset from Kaggle:
  https://www.kaggle.com/competitions/airbus-ship-detection

- Extract the dataset into the data/ directory so it looks like this:

data/
├── train_v2/
├── test_v2/
├── train_ship_segmentations_v2.csv

---

🚀 Running the Notebook

Open airbus_ship_detection_analysis.ipynb and run all cells sequentially to train the model and visualize results.

Key Features

- Data preprocessing and visualization
- Ship mask generation from encoded pixels
- Model training using convolutional neural networks (CNNs)
- Evaluation and prediction on test images
