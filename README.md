⚡ EV Vehicle & Charging Demand Prediction using Data Science

This project uses a real-world dataset to analyze and predict electric vehicle (EV) demand and charging infrastructure needs across various counties. The goal is to support smarter planning and sustainability through data-driven insights.


---

🧠 Project Objective

To analyze EV registration trends and forecast future vehicle growth or charging station requirements, helping stakeholders (governments, city planners, energy providers) make informed decisions.


---

📊 Dataset Overview

File: Electric_Vehicle_Population_By_County.csv

Source: Public EV population data by county

Size: ~20,000 records

Features:

County, State

Vehicle Primary Use

EV types: BEVs, PHEVs, Total EVs

Total registered vehicles

Percent electric vehicles




---

🔍 Project Stages

✅ Week 1 – Data Analysis & Visualization

Imported and cleaned the dataset

Analyzed missing values and column types

Visualized:

Top 10 counties by EV registrations

EV type distribution (BEV vs PHEV)

Electric vehicle adoption rates



🔮 Week 2 – Model Building

Feature engineering: Encoding categorical variables

Created prediction model using:

Linear Regression / Random Forest

Evaluation metrics: RMSE, R² score


Trained model to predict EV counts or charging demand based on features like city, type, year, and range


🧪 Week 3 – Model Evaluation & Optimization

Hyperparameter tuning

Model comparison

Visualization of predicted vs actual results


🧑‍🏫 Week 4 – Presentation & Final Submission

Created project presentation (PPT)

Shared outcomes with mentors and experts



---

🛠 Technologies Used

Python

Pandas / NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook



---

📁 Folder Structure

ev-demand-prediction/
├── data/
│   └── Electric_Vehicle_Population_By_County.csv
├── notebooks/
│   ├── Week1_EV_Analysis.ipynb
│   ├── Week2_Model_Training.ipynb
├── models/
│   └── ev_predictor.pkl
├── results/
│   └── visualizations.png
├── README.md
└── requirements.txt


---

📌 Key Outcomes

Identified high-growth EV regions

Predicted EV penetration % based on current data

Estimated charging infrastructure needs per region

Built foundation for integrating AI with sustainability



---

🙋‍♂️ Author

Suryansh Dhama
B.Tech CSE (AI & ML)
📧 ydvryo@gmail.com


---

📜 License

This project is open-source under the MIT License.


