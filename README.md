# Medical-Data-Analyser


### Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [ProjectObjectives](#project-objectives)
- [Tools and Technologies](#tools-and-technologies)
- [Key Features](key-features)
- [Key Insights](#key-insights)
- [Clone Repository](#clone-repository)



### Project Overview
This project analyzes a medical examination dataset to uncover patterns related to heart disease and overall health indicators. The goal is to transform raw medical data into clear, human-readable insights that can support better understanding of health risks. The dataset includes patient information such as age, gender, blood pressure, cholesterol levels, lifestyle habits, and heart disease status.


### Dataset
The dataset contains medical records used to analyze cardiovascular health. The dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/scientificstephen/medical-examination-dataset-analysis)



### Project Objectives
- Clean and explore medical data
- Convert coded values into human-readable labels (Yes/No, Normal/High, etc.)
- Analyze heart disease distribution
- Identify relationships between health indicators
- Create simple visualizations for better understanding



### Tools and Technologies
- Python
- Pandas
- Matplotlib



### Key Features
1. Data Cleaning & Preparation
   - Converted age from days to years
   - Transformed coded values into readable labels:
     - Heart disease → Yes / No
     - Smoking, alcohol, activity → Yes / No
     - Cholesterol & glucose → Normal / Above Normal / Well Above Normal
     - Gender → Man / Woman
    
2. Feature Engineering
   - Created a new BMI (Body Mass Index) column using:
     ```python
     BMI = weight / (height in meters)^2
     ```

3. Data Analysis
   - Counted and compared heart disease cases
   - Calculated percentages of patients with and without heart disease
   - Analyzed averages of:
     - Age
     - Weight
     - Blood pressure
     - BMI
    
   - Grouped results by heart disease status
  
  
4. Data Visualization
   - Bar charts:
     - Heart disease distribution
     - Cholesterol levels
     - Glucose levels
    
   - Histograms:
     - Age distribution
     - BMI distribution
    
   - Scatter plot:
     - BMI vs systolic blood pressure
    


### Key Insights
- The dataset shows a nearly balanced distribution between patients with and without heart disease
- Higher BMI and blood pressure tend to be associated with heart disease
- Lifestyle factors such as smoking and activity can be explored further for deeper insights


### Clone Repository
```bash
git clone https://github.com/tdiba/medical-data-analyser.git
```





