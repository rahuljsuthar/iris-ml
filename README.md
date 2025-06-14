# 🌸 Iris Flower Classification Web App (using Streamlit & scikit-learn)

This is a simple web application built using **Streamlit** and **Scikit-learn** that predicts the species of an iris flower based on input features like sepal length, sepal width, petal length, and petal width.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Setup Instructions (Local)](#setup-instructions-local)
- [Deploy to Streamlit Cloud](#deploy-to-streamlit-cloud)
- [How It Works](#how-it-works)
- [Screenshots](#screenshots)
- [License](#license)

---

## 📖 About the Project

The Iris dataset is one of the most famous datasets in the world of machine learning. It includes three species of iris flowers — *Setosa*, *Versicolour*, and *Virginica* — with 150 total observations and four features per sample.

This app allows users to interactively:
- Input feature values via sliders.
- Predict the flower species.
- See the predicted class label.

---

## 🛠 Tech Stack

- **Python 3.10+**
- **Streamlit** – for creating the interactive UI
- **scikit-learn** – for building and training the ML model
- **pandas** & **numpy** – for data manipulation

---

## ⚙️ Setup Instructions (Local)

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/iris-ml-app.git
   cd iris-ml-app
2. Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate

3. Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt

Open your browser and navigate to https://irisproject1.streamlit.app/


 How It Works
Loads the Iris dataset using sklearn.datasets.load_iris.

Trains a RandomForestClassifier on the full dataset.

Accepts user input for all four iris features.

Uses the trained model to predict and display the flower species

file:///D:/LEARN%20python/iris%20ml/Iris_dataset_scatterplot.svg

