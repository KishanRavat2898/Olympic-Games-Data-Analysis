🏅 Olympic Games Data Analysis Web Application

An interactive Olympic Games data analysis web application built using Python, Pandas, and Streamlit, providing deep insights into Olympic history through visualizations and statistics.

This project is inspired by the CampusX (Nitish Singh) Olympic Analysis project and has been debugged, fixed, and modernized to work correctly with the latest Python and Pandas versions.

🚀 Features
📊 Medal Tally

Overall medal tally

Year-wise medal tally

Country-wise medal tally

Dynamic filtering using dropdowns

🌍 Overall Analysis

Number of Olympic editions

Participating nations over time

Sports and events trends

Athlete participation trends

Heatmap of sports vs years

🏳️ Country-wise Analysis

Year-wise medal performance of a selected country

Sports in which a country excels

Top 10 athletes of a country

🧑 Athlete-wise Analysis

Age distribution of athletes

Medal-wise age comparison

Sport-wise age distribution

Height vs weight analysis

Male vs female participation trends

🛠️ Tech Stack

Language: Python

Web Framework: Streamlit

Data Analysis: Pandas, NumPy

Visualization: Plotly, Matplotlib, Seaborn

IDE: PyCharm

Version Control: Git & GitHub

📂 Project Structure
Olympic-Games-Data-Analysis/
│
├── app.py                  # Main Streamlit application
├── helper.py               # Data analysis & aggregation logic
├── preprocessor.py         # Data cleaning and preprocessing
├── athlete_events.csv      # Olympic athlete dataset
├── noc_regions.csv         # Country-region mapping
├── README.md               # Project documentation
└── requirements.txt        # Project dependencies

⚙️ How to Run Locally
1️⃣ Clone the repository
git clone https://github.com/KishanRavat2898/Olympic-Games-Data-Analysis.git
cd Olympic-Games-Data-Analysis

2️⃣ Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the Streamlit app
streamlit run app.py

🧠 Key Contribution & Debugging Work
❌ Issues in Original Code

KeyError: 'Name'

KeyError: 'index'

Pandas value_counts().reset_index() API incompatibility

✅ Fix Applied

Explicitly named columns during aggregation to ensure merge compatibility with modern Pandas versions.

Example fix:

.reset_index(name='Medals')

🔖 Project Origin & Attribution

This project is inspired by the Olympic Analysis project by Nitish Singh (CampusX).

Original repository:
https://github.com/campusx-official

My Contributions:

Debugged multiple runtime errors

Fixed Pandas API breaking changes

Ensured full application stability

Made the project production-ready

📈 Future Improvements

Deploy on Streamlit Cloud

Add caching for faster performance

Improve UI design

Extend dataset to recent Olympics

👨‍💻 Author

Kishan Ravat
Final Year B.Tech Student
Aspiring Data Analyst / Data Scientist

GitHub: https://github.com/KishanRavat2898
