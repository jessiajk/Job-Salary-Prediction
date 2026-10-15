# CareerWorth — Job Salary Prediction

**An ML-powered web application for data-driven salary estimation.**

CareerWorth is a machine learning web application that predicts estimated job salaries using **Linear Regression**, trained on a dataset containing more than **250,000 job records**. Built with Python, Flask, and Scikit-learn, the application helps job seekers explore potential salary expectations and supports recruiters in making informed compensation estimates.

## Overview

Determining an appropriate salary can be challenging for both job seekers and recruiters. CareerWorth addresses this challenge by providing an accessible, data-driven approach to salary estimation.

Users can enter relevant profile and job details to generate an estimated salary prediction. The application also provides dataset insights, model performance information, and details about the project and its development team.

## Key Features

* **Salary Prediction:** Estimate salaries using a trained Linear Regression model.
* **Interactive User Interface:** Enter relevant details through a user-friendly web interface.
* **Data Insights Dashboard:** Explore dataset statistics and model performance.
* **Project Information:** Learn about the project's objectives, technologies, and development team.
* **Machine Learning Integration:** Apply a model trained on more than 250,000 job records to generate predictions.

## Application Sections

| Section           | Description                                                |
| ----------------- | ---------------------------------------------------------- |
| Home              | Introduction to CareerWorth and its purpose.               |
| Salary Prediction | Enter job-related details and receive an estimated salary. |
| Dashboard         | Explore dataset insights and model performance metrics.    |
| About             | View project information and team details.                 |

## Technology Stack

* **Programming Language:** Python
* **Web Framework:** Flask
* **Machine Learning:** Scikit-learn
* **Model:** Linear Regression
* **Data Processing:** Pandas, NumPy
* **Frontend:** HTML, CSS, JavaScript
* **Deployment:** Render

*The technology list should reflect the libraries and tools actually used in your implementation.*

## How It Works

1. **Data Preparation:** A dataset containing over 250,000 job records is used for model development.
2. **Model Training:** A Linear Regression model is trained using the prepared data.
3. **User Input:** Users provide the job or profile details required by the application.
4. **Salary Estimation:** The trained model processes the input and generates an estimated salary.
5. **Results and Insights:** Users view their prediction and can explore available dataset and model information.

## Installation and Setup

Follow these steps to run CareerWorth locally.

### Prerequisites

* Python 3.9 or later
* pip
* Git

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_DIRECTORY>
```

Replace the placeholders with your actual repository URL and project directory.

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

If your main Flask file is named `app.py`, run:

```bash
python app.py
```

Open the local URL displayed in your terminal, typically:

`http://127.0.0.1:5000`

## Deployment

CareerWorth can be deployed as a Flask web service on [Render](https://render.com/).

Typical deployment configuration:

**Build Command**

```bash
pip install -r requirements.txt
```

**Start Command**

```bash
gunicorn app:app
```

Ensure that `gunicorn` is listed in `requirements.txt`, and verify that your entry-point filename and Flask application variable match the start command.

## Project Objectives

* Develop a practical application of machine learning for salary estimation.
* Demonstrate the use of Linear Regression on a large job-record dataset.
* Build an accessible web interface for interacting with a trained model.
* Present dataset insights and model performance through a dashboard.
* Explore how predictive analytics can support career planning and compensation decisions.

## Limitations

* Salary predictions depend on the quality, coverage, and representativeness of the training dataset.
* Estimated salaries may differ from actual compensation due to location, experience, industry, market conditions, and other factors.
* Predictions are estimates and should not be treated as guaranteed salaries or professional compensation advice.

## Team

**Team Insight Coders**
Department of Artificial Intelligence and Data Science

This mini-project demonstrates the integration of machine learning, data processing, and web development to address a practical career-related problem.

## Future Enhancements

Potential improvements include:

* Evaluating additional regression algorithms.
* Enhancing feature engineering and model evaluation.
* Expanding salary insights by role, location, and experience.
* Improving the dashboard with additional visualizations.
* Regularly updating the dataset to reflect changing job-market trends.

## License

No license has been specified yet. Add a `LICENSE` file if you intend to distribute the project under an open-source license.

---

**CareerWorth — Making salary expectations more data-driven.**
