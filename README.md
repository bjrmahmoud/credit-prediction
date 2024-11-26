
# Credit Prediction App 🚀

This project is a **Credit Prediction Application** that predicts loan eligibility based on user input. The model is trained on a dataset sourced from Kaggle, and the application is built using **Python**, **Flask**, and **Jupyter Notebook**.

## Features 🌟
- **Machine Learning Models**: Includes Logistic Regression, K-Nearest Neighbors (KNN), and Decision Tree for prediction.
- **User-Friendly Interface**: Built with Flask to provide an intuitive web interface for users.
- **End-to-End Workflow**: From data preparation and model training to deployment for real-world usage.

---

## Table of Contents 📖
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## Getting Started 🛠️

To get a local copy up and running, follow these steps:

### Prerequisites
- Python 3.8 or later
- Pip (Python package manager)
- Jupyter Notebook
- Flask

### Dataset
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/). Download the dataset and place it in the `data/` folder.

---

## Technologies Used ⚙️
- **Python**: Programming language for backend and machine learning.
- **Flask**: For creating the web application interface.
- **Jupyter Notebook**: For data analysis and model training.
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation and analysis.
  - `matplotlib`, `seaborn`: Visualization.
  - `sklearn`: Machine learning algorithms.
  - `pickle`: Saving and loading models.

---

## Project Workflow 📋
1. **Data Preprocessing**: Cleaned and prepared the data using Python in Jupyter Notebook.
2. **Model Training**: Trained Logistic Regression, KNN, and Decision Tree models. Saved the best-performing model using `pickle`.
3. **Web Application**: Built a Flask app to take user input, predict outcomes, and display results.

---

## Installation 🖥️

1. Clone the repository:
   ```bash
   git clone https://github.com/bjrmahmoud/credit-prediction.git
   cd credit-prediction
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run Jupyter Notebook for model training:
   ```bash
   jupyter notebook
   ```

5. Start the Flask app:
   ```bash
   python app.py
   ```

---

## Usage 📊
1. Launch the Flask app (http://127.0.0.1:5000).
2. Enter the required details in the web form.
3. Get predictions for loan eligibility in real-time.

---

## Screenshots 📸
Add screenshots here to showcase your application interface and features.

---

## Contributing 🤝
Contributions, issues, and feature requests are welcome!  
Feel free to check the :
https://github.com/bjrmahmoud/credit-prediction.git

---



## Acknowledgements 🙏
- Kaggle for the dataset.
- Flask and Python community for documentation and support.
