Heart Disease

According to the Centers for Disease Control (CDC), heart disease is one of the high rank health problem that causes death for people in the US. About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking.  Other key indicator include diabetic status, obesity (high BMI), not getting enough physical activity or drinking too much alcohol. 

Detecting and preventing the factors that have the greatest impact on heart disease is very important in healthcare. Computational developments, in turn, allow the application of machine learning methods to detect "patterns" from the data that can predict a patient's condition.

Raw Data Collecting

The Behavioral Risk Factor Surveillance System (BRFSS) completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world.". The dataset was retrieved from https://www.cdc.gov/brfss/annual_data/2020/pdf/codebook20_llcp-v2-508.pdf https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

Objective
- Industry 
- Explore Data 
- Analysis Data
- Visualize Data
- learn about the data what type of data I have
- using plots to make a story
- searching for the most reason that will lead for heart disese
- Apply Encoding, Features Engineering, Feature Selection
- Build a system using a machine learning model.
- Build a system using a deep learning model
- Presentation


Conclusion 
After experimenting with different models I concluded that RandomForestClassifier with SMOTE resampling yield the best recall and precsion for the heart diseas class (91%), and  XGBClassifier (SMOTE)) yields the best recall for the no heart disease class (96%). An application of our model is to be used by medical experts in selecting the patients suspected of heart disease in order to conduct further testing on them.
# Heart-Disease-Prediction-Factors

This project contans three files for the Raw Data Collecting:
- Part 1: Data Analysis
- Part 2: Encoding, Features Engineering, Feature Selection
- Part 3: Machine Learning and Deep Learning Models
