
# 🚀 Credit Prediction App 🌟

Welcome to the **Credit Prediction Application**!  
This project uses state-of-the-art machine learning models to predict **loan eligibility** based on user inputs. The app offers an **interactive web interface** built with Flask, and is **containerized with Docker** for effortless deployment.

📊 **Models Used**: Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree  
📁 **Dataset Source**: [Loan Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

---

## 📋 Table of Contents

- [✨ Features](#-features)  
- [💻 Technologies Used](#-technologies-used)  
- [🌐 Example Prediction Interface](#-example-prediction-interface)  
- [⚙️ Installation](#️-installation)  
  - [1️⃣ Clone the Repository](#1️⃣-clone-the-repository)  
  - [2️⃣ Place the Model File](#2️⃣-place-the-model-file)  
  - [3️⃣ Install Dependencies (if running locally)](#3️⃣-install-dependencies-if-running-locally)  
- [🛠️ Usage](#️-usage)  
- [🚢 Deployment](#-deployment)  
  - [🔧 Local Deployment with Docker](#-local-deployment-with-docker)  
  - [🌍 Access the Application](#-access-the-application)  
- [📂 Project Structure](#-project-structure)  
- [🤝 Contributing](#-contributing)  
- [🎉 Acknowledgments](#-acknowledgments)  
- [📝 License](#-license)

---

## ✨ Features

- 🔍 **Multi-Model Approach**: Combines Logistic Regression, K-Nearest Neighbors, and Decision Tree algorithms for robust predictions.  
- 💡 **Interactive Web Interface**: Provides an easy-to-use form for users to check loan eligibility.  
- 🐳 **Dockerized Application**: Ensures consistency and smooth deployment across systems.  
- ⚡ **Pre-trained Model Integration**: Models are serialized with **pickle** for quick and efficient predictions.

---

## 💻 Technologies Used

- **Programming Language**: Python 3.x 🐍  
- **Python Libraries**:  
  - 📊 Data Handling: `numpy`, `pandas`  
  - 🤖 Machine Learning: `scikit-learn`  
  - 💾 Model Persistence: `pickle`  
  - 🌐 Web Framework: Flask  
- 🐳 **Containerization**: Docker  
- 🎨 **Front-End Design**: HTML/CSS (via Flask templates).

---

## 🌐 Example Prediction Interface

Here’s a preview of the prediction form:  

<img src="images/image.png" alt="Credit Prediction Form" width="600">

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/bjrmahmoud/credit-prediction.git
cd Credit_Prediction
```

### 2️⃣ Place the Model File

Ensure the trained **`model.pkl`** file is in the root directory.

### 3️⃣ Install Dependencies (if running locally)

```bash
pip install -r requirements.txt
```

---

## 🛠️ Usage

1. Start the Flask application locally:  
   ```bash
   python app.py
   ```
2. Open your browser and go to:  
   ```
   http://127.0.0.1:5000
   ```
3. Fill in the form with details such as:  
   - **Credit History**: 0 or 1  
   - **Married**: 0 (No) or 1 (Yes)  
   - **Coapplicant Income**: Numeric value  
4. Click **"Predict"** to see the loan eligibility result.  

---

## 🚢 Deployment

### 🔧 Local Deployment with Docker

1. Build the Docker image:  
   ```bash
   docker build -t credit-prediction-app .
   ```
2. Run the Docker container:  
   ```bash
   docker run -p 5000:5000 credit-prediction-app
   ```
3. Access the application in your browser:  
   ```
   http://localhost:5000
   ```

---

## 📂 Project Structure

```
/Credit_Prediction
│
├── app.py                 # Flask application
├── Dockerfile             # Docker configuration
├── docker-compose.yml     # Optional: Docker Compose file
├── requirements.txt       # Python dependencies
├── model.pkl              # Trained machine learning model
├── credit_model.ipynb     # Jupyter notebook with model training code
├── templates/             # HTML templates for the web interface
│   └── index.html         # Main page with the form
└── static/                # Static files (CSS, images)
```

---

## 🤝 Contributing

Contributions are always welcome! 🎉  

1. **Fork this repository**.  
2. Create a new branch for your feature:  
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes and push them:  
   ```bash
   git commit -m "Add new feature"
   git push origin feature-branch
   ```
4. Open a **Pull Request**.  

---

## 🎉 Acknowledgments

- **Kaggle**: For the [Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset).  
- **Flask**: For making web development simple and flexible.  
- **Docker**: For enabling seamless deployment.  
- **scikit-learn**: For its powerful machine learning tools.  

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.  

---

**Happy Predicting! 🚀**
