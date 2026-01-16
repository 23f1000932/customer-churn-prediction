Customer Churn Prediction & Analysis 📉
=======================================

**A comprehensive data science project combining high-performance machine learning with a modern, interactive web interface.**

📌 Project Overview
-------------------

In the competitive banking sector, customer retention is paramount. This project analyzes a dataset of over **165,000 bank records** to identify the key drivers behind customer churn.

The solution is divided into two major components:

1.  **The Analysis Core (`.ipynb`):** A robust machine learning pipeline using XGBoost to predict churn probability with high accuracy.

2.  **The Presentation Layer (Web App):** A polished, interactive portfolio website built with React and Tailwind CSS to communicate insights to stakeholders.

🧠 Part 1: The Machine Learning Pipeline
----------------------------------------

The core analysis is documented in `kaggle-assingnment-2.ipynb`. This notebook details the end-to-end data science workflow.

### Key Highlights

-   **Objective:** Predict the `exit_status` (binary classification) of a customer based on demographics and behavior.

-   **Algorithm:** **XGBoost Classifier** (Extreme Gradient Boosting).

-   **Performance Metrics:** Optimized for **F1-Score** to balance Precision and Recall, ensuring we capture as many potential churners as possible without excessive false alarms.

    -   *Approx. F1-Score:* ~0.89

    -   *Accuracy:* ~94%

### Workflow Steps

1.  **Data Preprocessing:** Handling missing values, categorical encoding (One-Hot/Label Encoding for Geography/Gender), and feature scaling.

2.  **Exploratory Data Analysis (EDA):** Uncovering trends such as:

    -   The sharp rise in churn risk for customers over age 45.

    -   Geographical disparities (e.g., higher churn rates in Germany).

3.  **Feature Engineering:** Creating new metrics like interaction ratios to improve model sensitivity.

4.  **Model Training:** Tuning XGBoost hyperparameters for optimal convergence.

🌐 Part 2: The Web Application
------------------------------

To move beyond static notebooks, I developed a single-page interactive website (`index.html`) to showcase the project findings.

**Live Demo:** [Link to your GitHub Page] *(Replace with actual link after deployment)*

### Tech Stack

-   **Core:** React 18 (via CDN for zero-build deployment).

-   **Styling:** Tailwind CSS (Dark Mode aesthetic).

-   **Visualization:** Recharts for responsive, animated graphs.

-   **Icons:** Lucide React.

### Website Features

-   **Interactive Data Explorer:** A searchable table allowing users to filter the dataset by Name or Country in real-time.

-   **Visual Dashboards:** Animated charts displaying Age Distribution and Churn by Geography.

-   **Live Churn Simulator:** A functional demo section where users can adjust sliders (Age, Credit Score, Products) to see how the model calculates risk probability dynamically.

-   **Glassmorphism UI:** Modern design with floating elements, gradients, and smooth scroll animations.

🚀 How to Run
-------------

### Running the Notebook

1.  Ensure you have Python installed with `pandas`, `numpy`, `xgboost`, and `scikit-learn`.

2.  Open `kaggle-assingnment-2.ipynb` in Jupyter Lab, VS Code, or Google Colab.

3.  Ensure `train.csv` and `test.csv` are in the correct directory path.

4.  Run all cells to reproduce the analysis.

### Deploying the Website (GitHub Pages)

The website is designed as a **Single File Application**. You do not need `npm` or `node_modules`.

1.  Create a new repository on GitHub (e.g., `churn-prediction-portfolio`).

2.  Upload the `index.html` file to the root of the repository.

3.  Go to **Settings** -> **Pages**.

4.  Under **Branch**, select `main` (or `master`) and hit **Save**.

5.  Your site will be live in ~60 seconds at `https://<your-username>.github.io/<repo-name>/`.

👨‍💻 Author
------------

**Ayan Hussain** *IIT Madras - BS in Data Science and Applications*

-   **Location:** Jahnavi Residency, D Gate IISC, Bangalore

-   **Phone:** +91 7081012288

-   **Email:** ayanhussain4212@gmail.com

-   **LinkedIn:** [Profile Link](https://www.google.com/search?q=https://www.linkedin.com/in/ayan-hussain-58752626b "null")

*Built with ❤️ using Data Science & React.*
