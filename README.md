# Customer Churn Prediction

This project aims to **predict customer churn** using machine learning techniques. By analyzing customer data, the model identifies patterns that indicate whether a customer is likely to leave a service.

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Contributing](#contributing)
- [License](#license)

## 📊 Overview

**Customer churn prediction** is crucial for businesses to retain customers and improve services. This project utilizes an **Artificial Neural Network (ANN)** to predict churn based on various customer attributes.

## 🗃️ Dataset

The dataset used is `Churn_Modelling.csv`, which contains the following information:

- **Customer ID**
- **Credit Score**
- **Geography**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited** (Churn Indicator)

## 📁 Project Structure

- `**ANN.ipynb**`: Jupyter Notebook for building and training the ANN model.
- `**SalaryRegression.ipynb**`: Notebook for salary regression analysis (optional).
- `**app.py**`: Flask application to serve the model.
- `**model.h5**`: Trained ANN model file.
- `**label_encoder_gender.pkl**`: Label encoder for the 'Gender' feature.
- `**onehot_encoder_geography.pkl**`: One-hot encoder for the 'Geography' feature.
- `**scaler.pkl**`: Scaler for feature normalization.
- `**requirements.txt**`: List of required Python packages.

## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KiranKatamneni/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt

## 🚀 Usage
1. **Run the Flask application:**:
   ```bash
   python app.py

2. **Access the application**:
   Open your web browser and navigate to http://localhost:5000 to use the churn prediction interface.

## 🧠 Model Details

- **Algorithm**: Artificial Neural Network (**ANN**)
- **Framework**: **Keras** with **TensorFlow** backend
- **Preprocessing Steps**:
  - **Label Encoding** for **'Gender'**
  - **One-Hot Encoding** for **'Geography'**
  - **Feature Scaling** using **StandardScaler**

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. **Fork** the repository.
2. **Create a branch** for your feature or bug fix.
3. **Commit** your changes with clear messages.
4. **Push** to your fork.
5. Submit a **pull request** describing your changes.

Let’s build something great together! 🚀

## 📝 License

This project is open-source and available under the **MIT License**.  
Feel free to use, modify, and share with attribution.
