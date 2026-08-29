<div align="center">

🌊 AI-ENABLED WATER WELL PREDICTOR 🤖

Predict. Classify. Protect Groundwater. 🌍

PRJ-314 · Mini Project (CSE7102)
B.Tech. Computer Engineering (Artificial Intelligence & Machine Learning)
Presidency University

<br>










</div>

💧 The Big Idea

Groundwater is one of India's primary freshwater resources, yet conventional well-site assessment can depend on slow, resource-intensive manual surveys.

AI-Enabled Water Well Predictor proposes a software-only, sensor-free approach that uses historical groundwater and climate data to:

🔮 Predict groundwater levels → 📊 quantify prediction confidence → ⚠️ classify well risk → 🧭 support practical groundwater decisions

The project works with historical data spanning 1994–2025 and benchmarks Random Forest against XGBoost to investigate effective tree-based machine-learning approaches for groundwater prediction.

🎯 Problem Statement

Problem Statement Number: PRJ-314
Category: Software
Difficulty: Medium

Design and develop a solution for an AI-enabled water well predictor using modern technologies to improve performance, automation, security, scalability, and real-world usability.

🚀 What Makes This Project Different?

Conventional Approach 🏚️

Our Approach 🤖

Manual field surveys

AI-assisted prediction

Resource-intensive assessment

Software-based workflow

Sensor/IoT dependency may be required

No sensors or IoT required

Assessment can be slow

Automated prediction pipeline

Raw measurements can be difficult to interpret

Safe / Declining / Critical risk classification

Limited decision support

Visual trends + feature importance

🔥 Core Innovation

The project combines groundwater-level prediction with a practical well-risk classification layer, turning a numerical prediction into an easier-to-understand decision-support output.

🧠 AI/ML Pipeline

┌─────────────────────┐
│   🌐 DATA SOURCE    │
│ Groundwater +       │
│ Climate Data        │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│   🧹 PREPROCESSING  │
│ Cleaning • Features │
│ Preparation         │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│   🧠 MODEL TRAINING │
│ Random Forest       │
│       vs            │
│ XGBoost             │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│   🔮 PREDICTION     │
│ Groundwater Level   │
│       (meters)      │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│   ⚠️ RISK ENGINE    │
│ Safe / Declining /  │
│ Critical            │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│   📊 STREAMLIT UI   │
│ Prediction + Trends │
│ + Feature Importance│
└─────────────────────┘

🧩 System Architecture

Input Layer

🌎 Region / station
📅 Date / time period
🌧️ Historical climate information
💧 Historical groundwater information

Processing Layer

Data preprocessing

Feature preparation

Model training

Validation

Performance comparison

Intelligence Layer

Two tree-based approaches are benchmarked:

🌲 Random Forest Regressor

⚡ XGBoost

Decision Layer

The system produces:

📏 Predicted groundwater level in meters

🎯 Model confidence indicator / prediction interval

🚨 Well-risk classification

📈 Historical groundwater trend

🧠 Feature-importance breakdown

📊 Expected Output

The system is designed to provide a practical dashboard experience:

🔮 Groundwater Prediction

A predicted groundwater level in meters for the selected station and time period.

🎯 Confidence Indicator

A prediction interval / error margin based on validation performance.

⚠️ Well-Risk Classification

Classification

Meaning

🟢 SAFE

Suitable / relatively favorable groundwater condition

🟡 DECLINING

Groundwater condition indicates a declining trend

🔴 CRITICAL

High-risk condition requiring attention

📈 Supporting Visualizations

Historical groundwater trend

Feature-importance breakdown

The project therefore aims to move beyond simply predicting a number and provide interpretable decision support.

🖥️ User Experience

The final output is planned through a Streamlit interface.

User
 │
 ├── Select Region
 │
 ├── Select Date / Period
 │
 ▼
AI Water Well Predictor
 │
 ├── 🔮 Predicted Groundwater Level
 │
 ├── 🎯 Confidence / Error Margin
 │
 ├── ⚠️ Well Risk Category
 │
 ├── 📈 Historical Trend
 │
 └── 🧠 Feature Importance

🛠️ Technology Stack

👨‍💻 Programming



📦 Data & Numerical Processing

Pandas

NumPy

🧠 Machine Learning

scikit-learn

Random Forest Regressor

XGBoost

📐 Model Evaluation

The project specifies:

R²

RMSE

MAE

📊 Visualization

Matplotlib

Seaborn

🌐 Application / Deployment

Streamlit

🔧 Development & Version Control

Jupyter Notebook

Google Colab

VS Code

GitHub

📚 Dataset

Dataset Source

Kaggle — India Groundwater Climate Time-Series (1994–2025)

The project uses historical groundwater and climate data covering a long time period to build and evaluate prediction models.

📌 Dataset access requires a Kaggle account according to the project requirements.

🧪 Model Evaluation

The project benchmarks two major tree-based approaches:

🌲 Random Forest Regressor

An ensemble-based regression approach used as one of the primary prediction models.

⚡ XGBoost

A gradient-boosting approach evaluated against Random Forest.

📏 Evaluation Metrics

R²    → Goodness of fit
RMSE  → Magnitude of prediction error
MAE   → Average absolute prediction error

The project literature review indicates that tree-based ensemble approaches are well suited to this problem, while no single model is assumed to dominate; therefore, Random Forest vs XGBoost benchmarking is part of the proposed methodology.

🌍 SDG Alignment

🌱 United Nations Sustainable Development Goals

The project is aligned with SDG 9 as stated in the project review.

Industry, Innovation and Infrastructure

The proposed solution emphasizes:

💻 Scalable software

💰 Low-cost implementation

📡 No specialized sensor/IoT hardware

🤖 AI-assisted decision support

🌎 Potential real-world groundwater management applications

💻 System Requirements

Requirement

Specification

💻 OS

Windows / macOS / Linux

🐍 Python

3.8+

🧠 IDE

Jupyter / Google Colab / VS Code

📦 Libraries

Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn, Streamlit

📊 Dataset

Kaggle access

⚙️ Processor

Intel i3 or above

🧮 RAM

Minimum 4 GB · 8 GB recommended

💾 Storage

At least 2 GB free

🎮 GPU

Not required

📡 IoT Hardware

None required

⚡ Getting Started

The review document specifies the technology stack and environment, but does not provide a finalized installation command sequence. The commands below are a conventional project setup example rather than information directly stated in the review.

1️⃣ Clone the repository

git clone https://github.com/anubhab16/ai-water-well-predictor.git
cd ai-water-well-predictor

2️⃣ Create a virtual environment

python -m venv venv

Activate it:

Windows

venv\Scripts\activate

macOS / Linux

source venv/bin/activate

3️⃣ Install dependencies

pip install pandas numpy scikit-learn xgboost matplotlib seaborn streamlit

4️⃣ Run the Streamlit application

streamlit run app.py

⚠️ Replace app.py with the actual application entry point if the repository uses a different filename.

📁 Suggested Project Structure

ai-water-well-predictor/
│
├── 📂 data/
│   └── groundwater_climate_data.csv
│
├── 📂 notebooks/
│   └── model_training.ipynb
│
├── 📂 models/
│   ├── random_forest/
│   └── xgboost/
│
├── 📂 src/
│   ├── preprocessing.py
│   ├── training.py
│   ├── prediction.py
│   └── risk_classification.py
│
├── 📂 visualizations/
│   ├── groundwater_trend.py
│   └── feature_importance.py
│
├── 📄 app.py
├── 📄 requirements.txt
├── 📄 README.md
└── 📄 LICENSE

This structure is a recommended organization for the project README; the uploaded review does not specify the repository's exact folder structure.

🔗 Project Repository

⭐ GitHub

Repository:
https://github.com/anubhab16/ai-water-well-predictor

<a href="https://github.com/anubhab16/ai-water-well-predictor">
<img src="https://img.shields.io/badge/⭐%20View%20Project%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

🗓️ Project Roadmap

The project review includes a project timeline / Gantt chart. The detailed task-by-task dates are presented visually in the review material.

Overall Flow

📚 Literature Review
       ↓
🧹 Data Preparation
       ↓
🧠 Model Development
       ↓
⚖️ RF vs XGBoost Benchmarking
       ↓
🔮 Prediction System
       ↓
⚠️ Risk Classification
       ↓
📊 Streamlit Interface
       ↓
🚀 Final Deployment / Demonstration

🔮 Future Potential

Based on the project's stated objective of improving performance, automation, security, scalability, and real-world usability, the system is positioned as a foundation for a broader groundwater decision-support platform.

Potential directions can include:

📍 Expanding geographic coverage

📊 More extensive model benchmarking

🧠 Improving prediction confidence estimation

🌐 Scaling the Streamlit application

🗺️ Richer geographical visualization

🔄 More frequent data updates

🏛️ Integration into groundwater-management workflows

📖 Research Foundation

The project review references research covering machine learning, deep learning, ensemble methods, and groundwater-level prediction.

Selected References

Rohde, M. M., Biswas, T., Housman, I. W., Campbell, L. S., Klausmeyer, K. R., & Howard, J. K. (2021). A machine learning approach to predict groundwater levels in California reveals ecosystems at risk. Frontiers in Earth Science, 9, 784499.

Davari, S., Eslamian, S., Jamali, M., & Safavi, H. R. (2025). Application of machine learning algorithms for groundwater level prediction in the Najafabad plain. Scientific Reports.

Jesse, G. et al. (2025). A systematic review of machine learning models for groundwater level prediction. Applied Computing and Geosciences, 28, 100303.

Sarkar, H., Mishra, R., & Ojha, C. S. P. (2025). Application of machine learning techniques in the evaluation of local groundwater level using field gravity data. Hydrology Research, 56(5), 383–396.

Pham, Q. B. et al. (2022). Groundwater level prediction using machine learning algorithms in a drought-prone area. Neural Computing and Applications, 34, 10751–10773.

Chen, H.-Y., Vojinovic, Z., Lo, W., & Lee, J.-W. (2023). Groundwater level prediction with deep learning methods. Water, 15(17), 3118.

Khan, J., Lee, E., Balobaid, A. S., & Kim, K. (2023). A comprehensive review of conventional, machine learning, and deep learning models for groundwater level (GWL) forecasting. Applied Sciences, 13(4), 2743.

Thakur, A., Chandel, A., & Shankar, V. (2025). Prediction of groundwater levels using a long short-term memory (LSTM) technique. Journal of Hydroinformatics, 27(1), 51–68.

Ali, A. S. A. et al. (2024). An overview of deep learning applications in groundwater level modeling. Applied Computational Intelligence and Soft Computing, 2024, 9480522.

Feng, F., Ghorbani, H., & Radwan, A. E. (2024). Predicting groundwater level using traditional and deep machine learning algorithms. Frontiers in Environmental Science, 12, 1291327.

👥 Meet the Team

🧑‍💻 Project Contributors

#

Contributor

Roll Number

Role

01

Anubhab Parashar

20231COM0043

👨‍💻 Team Member

02

Aman Kundu

20231COM0088

👨‍💻 Team Member

03

Avdhesh Ghansela

20231COM0082

👨‍💻 Team Member

🤝 Team Philosophy

Three minds. One mission. Smarter groundwater decisions. 💧🧠🌍

👨‍🏫 Under the Guidance Of

Mr. Muthuraj V

Associate Professor
School of Computer Science and Engineering
Presidency University

Academic Coordination

HoD / Team Leader: Dr. Gopal K Shyam

Program Project Coordinator: Ms. Sumita Guddin

School Project Coordinator: Mr. Muthuraju V

Panel No.: 25

🎓 Academic Information

Institution: Presidency University
School: School of Computer Science and Engineering
Program: B.Tech. Computer Engineering (Artificial Intelligence & Machine Learning)
Course: Mini Project — CSE7102
Project ID: PRJ-314
Review: Review-1
Date: 29-08-2026

🏆 Project Vision

             💧 WATER
                │
                ▼
        📊 HISTORICAL DATA
                │
                ▼
           🧠 AI / ML
                │
        ┌───────┴───────┐
        ▼               ▼
   🔮 PREDICTION     ⚠️ RISK
        │               │
        └───────┬───────┘
                ▼
       📊 DECISION SUPPORT
                │
                ▼
          🌍 BETTER WATER
           MANAGEMENT

Our goal is simple:

Use AI to make groundwater assessment more accessible, scalable, and actionable. 🌱

<div align="center">

💧 Predict Smarter. Manage Better. Protect Tomorrow. 🌍

⭐ If this project inspires you, consider giving the repository a star!

<br>

Built with 🧠 AI + 💻 Python + 🌊 Groundwater Data + ❤️ Teamwork

<br>

PRJ-314 · CSE7102 · Presidency University

</div>
