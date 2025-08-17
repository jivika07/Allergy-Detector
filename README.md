📌 Allergy Detector

An AI-powered ingredient scanner built with Python, OpenCV, Pandas, and Flask that detects allergens (gluten, nuts, dairy, etc.) in food products. The system provides real-time scanning and instant alerts to help users avoid harmful ingredients.

🚀 Features

📷 Image-based detection: Scan product labels using OpenCV.

⚡ Real-time allergen identification with 85% accuracy.

🔔 Instant alert system (Flask-based notifications).

📊 Ingredient data processing with Pandas for classification.

🌐 Simple web interface for easy user interaction.

🛠️ Tech Stack

Languages: Python

Libraries: OpenCV, Pandas, NumPy

Framework: Flask

Other Tools: Jupyter Notebook, Git/GitHub

📂 Project Structure
Allergy-Detector/
│── static/            # CSS/JS files for Flask frontend
│── templates/         # HTML templates
│── data/              # Ingredient datasets
│── app.py             # Main Flask app
│── detector.py        # OpenCV + Pandas based allergen detector
│── requirements.txt   # Dependencies
│── README.md          # Project documentation

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/jivika07/Allergy-Detector
cd allergy-detector


Install dependencies

pip install -r requirements.txt


Run the Flask app

python app.py
