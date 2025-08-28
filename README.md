# 🎓 Student Performance Analysis 📊📚  

## 📌 Project Overview  
This project analyzes a **Student Performance dataset** to uncover insights about academic outcomes.  
It explores how different factors such as **gender, parental education, test preparation, and lunch type** affect student scores in **Math, Reading, and Writing**.  

Through **EDA, visualizations, feature scaling, and clustering**, the project segments students into performance groups and evaluates patterns.  


## 🎯 Objective  
To analyze student performance data and understand:  
- How demographic and socio-economic factors affect scores  
- Differences in subject performance (**Math, Reading, Writing**)  
- How students can be grouped into **High, Medium, and Low performers** using clustering  


## 📑 Dataset Details  
- **Filename**: `student_performance.csv`  
- **Source**: Kaggle  
- **Key Columns**:  
  - `gender` → Male/Female  
  - `parental_level_of_education` → Parental qualification (e.g., Bachelor’s, Master’s, High school)  
  - `test_preparation_course` → Completed or not  
  - `lunch` → Standard/Free or reduced lunch  
  - `math_score` → Math exam marks  
  - `reading_score` → Reading exam marks  
  - `writing_score` → Writing exam marks  


## ⚙️ Tools & Technologies Used  

**Programming Language**:  
- Python 3.x 🐍  

**Python Libraries**:  
- `pandas` → Data loading & preprocessing  
- `matplotlib` & `seaborn` → Visualization (boxplots, barplots, distribution plots)    


## 🔁 Project Workflow  

🔹 **Step 1: Importing Libraries**  
Loaded essential Python libraries for data handling, visualization, and clustering.  

🔹 **Step 2: Data Loading & Exploration**  
- Loaded dataset using `pd.read_csv()`  
- Used `.head()` and `.info()` to understand structure  
- Checked for missing values and dataset balance using `.value_counts()`  

🔹 **Step 3: Data Cleaning & Preprocessing**  
- Converted categorical features (like gender, test preparation) into clean formats  
- Handled missing/null values if any  

🔹 **Step 4: Exploratory Data Analysis (EDA)**  
- **Grouped analysis** → Average scores based on gender, parental education, and lunch type  
- **Boxplots** → Checked score distributions & outliers  
- **Bar charts** → Compared performance across categories  


## ✨ Key Highlights  
- 📊 **Subject-wise Analysis**: Compared Math, Reading, and Writing scores across groups  
- 👨‍👩‍👧 **Parental Education Impact**: Higher education level → Better student performance  
- 🍴 **Lunch Type Effect**: Students with standard lunch performed better  
- 📦 **Outlier Detection**: Identified unusual score patterns using boxplots  
   

## ❓ Key Questions Answered  
1. How do gender and parental education affect student scores?  
2. Which subject (Math, Reading, Writing) do students perform best in?  
3. Do students who completed test preparation courses score better?  


## 🚀 Future Enhancements  
- ✅ Build a predictive model (Logistic Regression / Random Forest) to predict pass/fail  
- 📈 Perform correlation analysis among subjects  
- 🖥️ Create an interactive dashboard in **Power BI** or **Streamlit** for better insights  
- 🌐 Integrate socio-economic data (income, family background) for deeper analysis  


## 🧠 Conclusion  
This project demonstrates how **data science techniques** can be applied to education.  
By analyzing and student performance data, we uncover key insights that can help:  

- Teachers focus on weaker groups  
- Schools design better preparation strategies  
- Policymakers understand socio-economic impacts on education  
