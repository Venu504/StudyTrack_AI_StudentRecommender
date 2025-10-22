🎓 Study Track – AI-Based Student Study Habit Recommender

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on student study activity and performance data to uncover learning patterns and behaviors. The analysis helps in building insights for an AI-based study recommendation system that aims to improve learning efficiency and academic outcomes.

The main objectives are to:

Understand student study habits, time management, and learning trends
Identify factors influencing performance and productivity
Perform data cleaning, feature creation, and visualizations for deeper insights
Support data-driven recommendations for personalized study plans
📂 Dataset Description
The project uses two main datasets:

Dataset Name	Description
students.csv	Contains student demographic and academic information: Student_ID, gender, NationalITy, PlaceofBirth, StageID, GradeID, SectionID, Relation, ParentAnsweringSurvey, and ParentschoolSatisfaction.
study_logs.csv	Contains student study activity and engagement metrics per semester: Student_ID, Topic, Semester, raisedhands, VisITedResources, AnnouncementsView, Discussion, StudentAbsenceDays, and Class.
🛠️ Technologies Used
Python 3.x
Pandas – Data cleaning & manipulation
Matplotlib – Visualizations
Seaborn – Statistical plots & correlations
Google Colab – Interactive notebook environment
🧼 Data Cleaning Steps
Loaded the CSV files into Pandas DataFrames
Handled missing values and removed duplicates
Converted date/time columns to proper datetime formats
Created new features such as total study hours, average session duration, etc.
Merged datasets for combined analysis on habits and outcomes
Filtered irrelevant or inconsistent entries for better accuracy
📊 Key Insights (Example Findings)
Peak study times and session durations per student
Correlation between total study hours and academic performance
Identification of highly active vs. low-engagement students
Country or department-based study pattern differences
🚀 How to Run
Clone this repository:

git clone https://github.com/Venu504/Study_Track_AI_based_Student_Study_Habit_Recommender/Milestone1_EDA.ipynb

Upload data to Google Colab:

students.csv
study_logs.csv
Milestone1_EDA.ipynb
Install dependencies (if needed):

pip install pandas matplotlib seaborn

Run the notebook cells sequentially in Google Colab

📁 Project Structure
STUDYTRACK_AI_STUDENTRECOMMENDER/ │ ├── MILESTONE 1/ │ ├── data/ │ │ ├── students.csv # Student data │ │ ├── study_logs.csv # Study activity data │ └── Milestone1_EDA.ipynb # EDA notebook │ ├── README.md # Project documentation

📚 References
Pandas Documentation
Seaborn Documentation
Matplotlib Documentation
Google Colab
👨‍💻 Author
Venu Sri Ankani venusriankani12@gmail.com

📄 License
This project is open source and available under the MIT License.

⭐ If you found this project helpful, please give it a star! ⭐
