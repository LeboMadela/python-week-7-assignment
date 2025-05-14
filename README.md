# python-week-7-assignment
# 🩺 Medical Dataset Analysis and Visualization

This project analyzes a medical dataset to explore patterns and trends related to patient health indicators such as age, heart rate, blood pressure, cholesterol (blood sugar), CK-MB, and Troponin levels. It includes data cleaning, statistical analysis, and data visualization using Python tools such as pandas, matplotlib, and seaborn.

## 📌 Project Structure

- `Medicaldataset.csv`: The dataset used for analysis.
- `medical_analysis.ipynb`: Jupyter Notebook containing the full workflow (loading, cleaning, analyzing, and visualizing the data).
- `medical_analysis.py`: Python script version of the notebook (optional).
- `README.md`: This documentation file.

## ✅ Objectives

- Load and clean a real-world medical dataset.
- Perform exploratory data analysis (EDA) on patient attributes.
- Compute basic statistics and group-wise summaries.
- Visualize key patterns using different types of plots.

## 🔍 Dataset Features

Each record in the dataset includes the following attributes:

- `Age`: Patient's age  
- `Gender`: 0 = Female, 1 = Male  
- `Heart rate`: Beats per minute  
- `Systolic blood pressure`: mm Hg  
- `Diastolic blood pressure`: mm Hg  
- `Blood sugar`: (used as a proxy for cholesterol)  
- `CK-MB`: Cardiac enzyme level  
- `Troponin`: Protein biomarker for heart attack  
- `Result`: Diagnosis output — `positive` or `negative`

## 📊 Visualizations Included

- **Line Chart**: Blood sugar trends across age  
- **Bar Chart**: Average systolic blood pressure by test result  
- **Histogram**: Distribution of CK-MB levels  
- **Scatter Plot**: Relationship between troponin and heart rate, colored by diagnosis  

## ⚙️ Tools Used

- Python 3.x  
- Jupyter Notebook (Anaconda)  
- pandas  
- matplotlib  
- seaborn  

## ▶️ How to Run

1. Clone the repository or download the ZIP:
   git clone https://github.com/LeboMadela/python-week-7-assignment.git

2. Open the Jupyter Notebook:
   jupyter lab

3. Run Week-7-Assignment.ipynb step-by-step to view the results.

🙋‍♀️ Author
Moleboheng Madela
For questions or collaboration, feel free to reach out!

