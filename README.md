# 🩺 Machine Learning for Depression Prediction

![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)
![Library](https://img.shields.io/badge/Library-Scikit--learn-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project uses machine learning to analyze various stress-related factors and predict the likelihood of depression. The entire workflow, from data cleaning and exploratory analysis to model training and evaluation, is contained within the primary Jupyter Notebook.

## 📸 Key Analysis Screenshot

![Feature Importance Chart](./screenshot.png)


## 📂 Project Structure

The repository contains the following files in the root directory:

```bash
.
├── DepressionData.csv      # The raw dataset used for the project.
├── README.md               # You are here!
├── Test.ipynb              # The primary Jupyter Notebook containing the full analysis.
└── Untitled-1.ipynb        # A scratchpad notebook used for initial tests (can be ignored).
```

## 🚀 Project Workflow

The analysis in `Test.ipynb` follows these key steps:
1.  **Data Cleaning & Preprocessing:** The `DepressionData.csv` dataset is loaded, cleaned, and prepared for machine learning.
2.  **Exploratory Data Analysis (EDA):** Visualizations are used to uncover patterns and correlations between stress factors and mental health outcomes.
3.  **Model Training:** Several classification models (e.g., Logistic Regression, Random Forest) are trained to predict depression risk.
4.  **Model Evaluation:** Models are evaluated using metrics like accuracy, precision, and recall to select the best performer.
5.  **Conclusion:** The results are summarized, and the most significant factors contributing to depression risk are identified.

## 🛠️ Tech Stack

-   **Core Language:** Python
-   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
-   **Environment:** Jupyter Notebook

## ⚙️ Setup and Installation

To run this analysis on your local machine, please follow these steps.

### Prerequisites

-   [Git](https://git-scm.com/)
-   Python 3.10.x
-   [Jupyter Notebook or JupyterLab](https://jupyter.org/install)

### Installation Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Create and activate a virtual environment:**

    -   **On Windows:**
        ```bash
        python -m venv venv
        venv\Scripts\activate
        ```

    -   **On macOS/Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```

3.  **Install the required dependencies:**
    *(Note: It is recommended to create a `requirements.txt` file from your environment using `pip freeze > requirements.txt`.)*
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```

## ▶️ Running the Analysis

1.  **Start the Jupyter environment:**
    ```bash
    jupyter notebook
    ```

2.  **Open the notebook:**
    Once the Jupyter interface opens in your browser, click on `Test.ipynb` to open it. You can then run the cells sequentially to reproduce the entire analysis.


This project is licensed under the MIT License.
```
