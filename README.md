<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=salesp07.salesp07" />

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=30&center=true&vCenter=true&width=500&height=70&duration=5000&lines=Hello+Mr+EC!+👋;Our+data+presentation;+Coronary+Artery+Heart+Disease;" />
</h1>

<h1 align="center">    Research from Group 5.</h1>

<div align="center">


<h1>Coronary Artery heart Disease 🫀.</h1>
<h2 align="center">Subject: Data Science 📊.</h2>
<h2 align="center">Class: MAS2 🧑🏻‍🎓.</h2>
<h2 align="center">Lecturer: Dr. Emmanuel Lance Christopher VI M. Plan 🧑🏻‍🏫.</h2>

<h1>Team Member</h1> 

<table>
  <tr>
    <th>Student Number</th>
    <th>Student Name</th>
    <th>Tasks Done</th>
    <th>Remarks by Leader</th>
    <th>Student Evaluation</th>
  </tr>
  <tr>
    <td>22080306</td>
    <td>Nguyễn Khoa Đàm</td>
    <td>2 Charts</td>
    <td></td>
    <td>100%</td> 
  </tr>
  <tr>
    <td>22080314</td>
    <td>Nguyễn Thái Hoàng (Leader)</td>
    <td>Introduction and Conclusion</td>
    <td></td>
    <td>100%</td>
  </tr>
  <tr>
    <td>22080327</td>
    <td>Bùi Tấn Minh</td>
    <td>1 Chart</td>
    <td>Attended 3/5 meetings</td>
    <td>80%</td>
  </tr>
  <tr>
    <td>22080335</td>
    <td>Trần Vũ Hoàng Nguyên</td>
    <td rowspan='2'>3 Charts</td>
    <td></td>
    <td>100%</td>
  </tr>
  <tr>
    <td>22080344</td>
    <td>Nguyễn Công Toàn</td>
    <td></td>
    <td>100%</td>
  </tr>
</table>
.
<h1>I. Introduction</h1>
<br>
 Cardiovascular diseases (CVDs) are like the top reason people die worldwide, killing about 17.9 million people every year, which is 31% of all deaths. Out of these, like 4 out of 5 deaths are from heart attacks and strokes, and a third of them happen to people under 70, which is considered early. Heart failure is a usual problem caused by CVDs, and this dataset has 11 features to try to predict if someone might get heart disease. 
<br>
 This study focuses on analyzing a dataset containing information from 918 patients. Each patient is described by various features such as age, blood pressure, cholesterol levels, maximum heart rate, and chest pain types. The dataset also includes a binary target variable, HeartDisease, which indicates whether a patient has been diagnosed with heart disease (1 = presence, 0 = absence). 
 <br>
 The goal of this analysis is to explore patterns and relationships between these features and the presence of heart disease. This includes 3 main core. Firtsly, studying Feature Relationships: This means looking at how things like cholesterol levels, blood pressure, and chest pain are linked to heart disease. Secondly, rating Predictive Models: Using methods like Logistic Regression and K-Nearest Neighbors (KNN), we can figure out if a patient could have heart disease based on their health data. Finally is helping Doctors Make Decisions: The goal is to give useful information and data to doctors so they can detect heart disease early, focus on patients who need help and use medical resources wisely.

<br>
<h1>II. Data Discussion</h1>
</div>

* **Age:** age of the patient [years]
* **Sex:** sex of the patient [M: Male, F: Female]
* **ChestPainType:** chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
* **RestingBP:** resting blood pressure [mm Hg] millimetres of mercury
* **Cholesterol:** serum cholesterol [mm/dl] milligrams (mg) per deciliter
* **FastingBS:** fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
* **RestingECG:** resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality] (T wave inversions and/or ST elevation  or depression of > 0.05 mV [Minute Ventilation] )
* **MaxHR:** maximum heart rate achieved [Numeric value between 60 and 202]
* **ExerciseAngina:** exercise-induced angina [Y: Yes, N: No]
* **Oldpeak:** oldpeak = ST [Numeric value measured in depression]
* **ST_Slope:** the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping] (ST segment slope)
* **HeartDisease:** output class [1: heart disease, 0: Normal]

<h1 align="center">III. Data Cleaning</h1>
<br>

![image](https://github.com/user-attachments/assets/91b0605a-fc9a-414a-a0f4-11c7fd3b95c6)
- The dataset contains 918 records with no missing or duplicate data, which is great. However, there are some issues like invalid values in RestingBP (0), Cholesterol (0), and Oldpeak (-2.0), along with an unusually high cholesterol level of 603.
- To fix this, anomalies should be investigated and corrected, data ranges validated with experts, and outliers handled carefully.
- Moving forward, it's important to do a final review and set up regular checks to keep the data clean and reliable for analysis.
<br>

![image](https://github.com/user-attachments/assets/c86128bd-7ea2-4457-826c-340505f78889)
- Complete and Clean Data: All columns are filled, and there are no duplicate records, ensuring the dataset is consistent and ready for analysis.However, in the Cholesterol, there are a bunch of value=0. We handle this by taking he median value of others values.
- Detected Issues: Some values need attention, such as RestingBP (0), Cholesterol (0), and Oldpeak (-2.0), which are invalid, and a cholesterol value of 603, which seems unusually high.
- Next Steps: Work with experts to confirm data accuracy, fix these issues, and set up processes to maintain data quality going forward.

<br>
<h1 align="center">IV. Charts and Insights</h1>

## Age Distribution of Patients
![image](https://github.com/user-attachments/assets/ba670568-f539-46d4-871a-035104ea1e33)



The age distribution of the patients in the dataset is shown in the histogram with a KDE curve overlaid. The pattern of the distribution appears to be almost bell-shaped (or normal distribution), meaning most patients fall within a central age range, with fewer younger and older patients on the edges.
  
 **Main Point:**

* **Age Range:** The dataset includes patients mostly between 30 and 75 years. We can see there are barely any patients under 30 or over 75 years, as indicated by the low bars at the edges.
* **Peak Age Group**: The group with the most patients is between 55 and 60 years old, where the count reaches about 120. This suggests that the dataset has a heavy focus on middle-aged to older adults, especially those in their late 50s.
* **Symmetry**: The distribution is somewhat symmetrical around the peak age, with almost an equal number of patients on either side of the 55–60 range. This might mean the dataset is representative of middle-aged to senior adults but with fewer younger (30s) and very old (70s) patients.
 
**Meaning of the Age Distribution:**
 
* Focus on Middle-Aged and Older Adults: With most patients between 50 and 70 years old, this dataset aligns with the general trend of heart disease risk, which usually goes up with age. The demographic profile suggests that this dataset is likely geared towards studying heart disease among age groups that are more likely to experience cardiovascular issues. This might be helpful for targeted health measures.
* Target Population for Heart Disease Analysis: Considering the age distribution, this dataset probably represents a population more at risk for heart disease, which could be useful for healthcare strategies aimed at middle-aged and senior patients. Having a lot of patients in their late 50s might imply that early interventions and risk management could be a focus for this age group.
* Data Limitations for Younger and Very Elderly Groups: There aren’t many patients under 30 or over 75, which could be a limitation in applying any findings across all age groups. Insights gained from this dataset might not be fully applicable to very young adults or the very elderly, and collecting more data on these groups could give a fuller picture.

  => In summary, the dataset’s age distribution centers on middle-aged and senior adults, especially those aged 55–60 who are typically at higher risk for heart disease. This concentration makes the dataset relevant for heart disease studies in these age groups, which might also aid in designing preventive health measures and healthcare plans. However, while this dataset gives valuable insights into heart disease risk for middle-aged and older adults, it might require more data from younger and elderly groups to understand heart disease dynamics across the entire age range.
<br>

## Age Distribution of Heart Disease Cases
![image](https://github.com/user-attachments/assets/2d4be382-4307-46bd-9ea1-e90f3f238f43)



This chart shows heart disease cases by age group, with orange indicating patients with heart disease and light blue for those without.

**Main Point:**

* **50–60 Age Group**: Highest rate of heart disease; orange segment dominates.
* **60–70 Age Group**: Also high in heart disease cases, though slightly fewer than 50–60.
* **30–40 & 40–50 Groups**: More balanced, with both affected and unaffected individuals.
* **70–80 Age Group**: Few patients, but most have heart disease, linking age to higher risk.

**Age-Related Trends:**

Heart disease risk clearly goes up with age, peaking in the 50–60 range and staying high in older groups.
 
**Meaning:**

* **Preventive Focus**: Efforts should target the 50–70 age range with screenings and lifestyle guidance.
* **Early Screening**: Heart disease, though less common, is present in younger groups, suggesting earlier screenings could help.
* **Resource Allocation**: Healthcare should focus resources on middle-aged and older adults, especially 50+.
   
=>  Heart disease increases with age, especially from 50 onwards. Targeted interventions and resources for these age groups could help manage and reduce heart disease effectively.
<br>


## Cholesterol level by Heart Disease Status
![image](https://github.com/user-attachments/assets/1d7409a2-adf5-4fbe-80ba-2794637550a5)


This box plot shows cholesterol levels for patients with (1) and without (0) heart disease. The y-axis represents cholesterol levels.
  
**Main Point**
  
* **Median Levels:**
  * Patients without heart disease have a median cholesterol slightly above 200 mg/dL.
  * Patients with heart disease have a somewhat higher median, suggesting elevated cholesterol might be linked to heart disease.
* **Distribution:**
  * Non-heart disease patients have a tighter range (IQR), with most cholesterol values between 175 and 275 mg/dL.
  * Heart disease patients show a broader spread, with values reaching up to 350 mg/dL, indicating more cholesterol variability in this group.
* **Outliers:**
  * The non-heart disease group has more extreme outliers, with some very high (above 400 mg/dL) and low (below 100 mg/dL) values.
  * The heart disease group has fewer outliers but a generally wider spread, showing that high cholesterol is common here.
  
**Main Point:**

* **Cholesterol Management:** The higher median and broader spread in the heart disease group imply that controlling cholesterol could help reduce risk. Lifestyle changes and medications could be useful for patients with elevated levels.
* **Comprehensive Screening:** Outliers suggest cholesterol alone isn’t enough to predict heart disease accurately. Screening for other risk factors (like blood pressure) would give a fuller picture.
* **Age and Lifestyle Impact:** The variability in cholesterol, especially among heart disease patients, might reflect age or lifestyle factors. Targeted programs based on these factors could improve heart disease prevention.
 
**Conclusion:**

 => High cholesterol is connected to a higher risk of heart disease, but it’s not the only thing to consider. People with heart disease often have higher cholesterol, which shows why managing it is important. However, taking other factors into account, like age and lifestyle, might be an even better way to prevent heart disease in the future.
<br>

## Chest Pain Type and Heart Disease

![image](https://github.com/user-attachments/assets/6ad18538-4f77-4768-b7bc-f4ca50868bcf)


  
This bar chart shows the distribution of chest pain types among patients with and without heart disease. Each chest pain type (ASY, ATA, NAP, TA) is on the x-axis, while the y-axis shows the number of patients. Orange represents those with heart disease; blue represents those without.
  
    
**Main Point:**

* **ASY (Atypical Angina)**: Mostly linked to heart disease, as shown by the dominant orange bar. Very few ASY patients don’t have heart disease, suggesting it’s a strong indicator of heart disease.
* **ATA (Asymptomatic)**: Primarily associated with patients without heart disease, shown by the large blue bar. Only a few ATA patients have heart disease, so it’s less of a risk indicator.
* **NAP (Non-Anginal Pain)**: Higher count of patients without heart disease, but some with heart disease. This type is not a major indicator but still relevant.
* **TA (Typical Angina)**: Roughly equal counts of heart disease and non-heart disease cases, suggesting it's a moderate risk factor.
  
**Meaning:**

* **Risk Assessment**: ASY is a strong heart disease indicator and should prompt further testing. ATA and NAP, however, are less concerning and might not need immediate action.
* **Diagnostic Prioritization**: Clinicians can use chest pain types to decide who needs urgent testing. ASY patients might be prioritized, while ATA and NAP can be lower priority.
* **Resource Allocation**: Resources can be better managed by focusing on ASY patients for immediate care, while NAP and ATA patients might follow a standard pathway.
    
**Conclusion:**

 => Atypical angina (ASY) is closely linked to heart disease, making it useful for early risk assessment. Chest pain type can help clinicians prioritize patients for faster diagnosis, especially those with ASY.

<br>

## Fasting Blood Sugar Levels and Heart Disease
![image](https://github.com/user-attachments/assets/51811154-b544-4525-a4d1-ffb4d0dda35a)
   



The bar chart shows the connection between fasting blood sugar levels and heart disease. On the x-axis, have zero person with blood sugar levels 120 mg/dl or lower, and 1 means people with blood sugar levels above 120 mg/dl. The y-axis shows the number of patients. Blue bars show people without heart disease, and orange bars show people with heart disease. This chart helps us see if higher blood sugar is related to heart disease.

**Main Point:**

* **Normal Fasting Blood Sugar (≤120 mg/dl)**: Most patients have normal blood sugar levels, with a slightly higher count of non-heart disease cases (blue) than heart disease cases (orange). This suggests that normal blood sugar is common in both groups, but those without heart disease slightly outnumber those with it.
* **Elevated Fasting Blood Sugar (>120 mg/dl)**: For high blood sugar patients, the majority have heart disease (orange). This shows a strong link between elevated blood sugar and heart disease, as only a few with high blood sugar do not have heart disease.
* **Overall Correlation**: High fasting blood sugar levels are associated with a higher likelihood of heart disease, making it a potential risk factor. Normal blood sugar levels, on the other hand, are more evenly spread between the groups.
 
**Meaning:**

* **Risk Indicator**: Elevated blood sugar (>120 mg/dl) could indicate higher heart disease risk, suggesting that monitoring blood sugar is important for identifying at-risk patients.
* **Blood Sugar Management**: Since high blood sugar correlates with heart disease, managing blood sugar through diet, lifestyle changes, and medications could help lower risk.
* **Preventive Care**: Regular screening of fasting blood sugar, especially for those with other risk factors, could be useful in preventing heart disease.
 
**Conclusion:**:
 
=> The chart shows a clear link between high blood sugar levels and heart disease. Patients with high blood sugar are mostly in the heart disease group, highlighting the importance of blood sugar control and monitoring as a way to reduce heart disease risk.
<br>

## Age and maximum heart rate 
![image](https://github.com/user-attachments/assets/6787b4a9-34c6-488d-ade8-c4eecbb37052)



This scatter plot shows how age and maximum heart rate relate to heart disease. Each dot represents a patient, with blue for patients without heart disease and orange for those with heart disease.

**Main Point:**

* **Age and Heart Disease:** Heart disease cases (orange dots) are mostly among older patients, especially those over 50. Younger patients are more likely to be without heart disease (blue dots).
* **Max Heart Rate and Heart Disease:** Patients without heart disease (blue) tend to have higher max heart rates, often around 150 or more, regardless of age. Those with heart disease (orange) usually have lower max heart rates, often below 140, especially as they get older.
* **Trend with Age:** Max heart rate decreases as age increases, which is normal, but this decrease is more noticeable in heart disease patients, where older individuals tend to have even lower max heart rates.

**Meaning:**

* **Max Heart Rate as a Heart Disease Indicator:** A lower max heart rate in older patients could signal higher heart disease risk, suggesting it’s a useful metric for heart health assessment, especially in those over 50.
* **Screening Based on Age and Max Heart Rate:** Older patients with low max heart rates might need more intensive screening since they’re at higher risk for heart disease.
  
**Conclusion:**
  
=> This chart shows that lower max heart rates are linked to heart disease, especially in older adults. Tracking max heart rate with age could help spot at-risk individuals, supporting early action for heart disease prevention.

<br>

## Cholesterol levels and resting blood pressure 
![image](https://github.com/user-attachments/assets/b2e9e282-cb61-4143-a661-9b6491dbd472)




The scatter plot visualizes cholesterol levels and resting blood pressure among patients, differentiated by blue dots for those without heart disease and green dots for those with heart disease.

**Main Point:**

* **Cholesterol Levels:** Most of the patients, regardless of heart disease status are having cholesterol levels reaching 150 to 300 mg/dL. In some cases the cholesterol levels reaching up to 600 mg/dL are rare.

* **Resting Blood Pressure:** Blood pressure ranges from 100 to 160 mmHg for both groups. There is no significant difference in blood pressure levels between patients with and without heart disease, as their ranges overlap.

* **Outliers:** Some patients show very low cholesterol levels, close to zero, likely due to missing or erroneous data.

* **No Clear Separation:** Cholesterol and blood pressure levels do not distinctly separate the two groups, indicating that these factors alone are insufficient for predicting heart disease.

**Meaning:**

* **Combined Risk Factors:** Cholesterol and blood pressure should be analyzed alongside other factors, such as age and chest pain type, for a more accurate heart disease risk assessment.

* **Data Cleaning:** The presence of low cholesterol outliers highlights the need for data cleaning to improve accuracy.

**Conclusion:**

=> High cholesterol and resting blood pressure levels are linked to heart disease, but they are not the only predictors. A full risk check needs to look at many factors together. Fixing any unusual data will also make the analysis more reliable.

<br>


## Cholesterol Distribution in Heart Disease Patients
![image](https://github.com/user-attachments/assets/27810d67-31b8-4eda-bf1e-11312688ef28)



This histogram with KDE overlays illustrates cholesterol levels among patients with and without heart disease. The x-axis represents cholesterol levels, the y-axis shows patient count. Orange bars show patients with heart disease, and blue bars represent those without.

**Cholesterol Distribution for Patient Who Have And Not Have Heart Disease:**

* Patients without heart disease (orange curve) have a slightly broader distribution compared to those with heart disease (blue curve).
* Both groups highest around same cholesterol levels (200–250 mg/dL).
**Higher Cholesterol Levels (>300 mg/dL):**

* Higher cholesterol levels are observed in both groups but are more frequent in patients without heart disease.
* This could suggest that high cholesterol alone is not a definitive predictor of heart disease.
**Lower Cholesterol Values (<150 mg/dL):**

* Patients with heart disease exhibit a more noticeable representation in this range, suggesting that low cholesterol levels might still occur in heart disease cases.

**Conclusion:**

=> Cholesterol levels alone are not enough to tell that patients have heart disease or not, given the large overlap in the 200–250 mg/dL range. We need to combine others factors to identify a patient have heart disease or not.
<br>



## K-Nearest Neighbors (KNN) Model Performance
![image](https://github.com/user-attachments/assets/29ff85e6-83eb-4ef9-8cf6-65424957ee95)



**Classification Metrics:**
* **Accuracy:** The KNN model hit 85.32% accuracy.
    * **No Heart Disease (Class 0):**
        * **Precision:** 80%
        * **Recall:** 87%
        * **F1-Score:** 0.83
    * **Heart Disease (Class 1):**
        * **Precision:** 90%
        * **Recall:** 84%
        * **F1-Score:** 0.87

* **Averages:** Both macro and weighted averages are around 0.85, which mean that the model handles both classes pretty evenly.
* **AUC:** The KNN model scored an AUC of 0.92, showing it’s pretty good at showing the difference between heart disease and no heart disease patients.

**Strengths:**

* Competitive AUC of 0.92, close to Logistic Regression.
* Precision and recall metrics for Class 1 reflect those of Logistic Regression, ensuring effective heart disease classfications.
* High adaptability to nonlinear data relationships.

**Insights for Medical Applications:**

* KNN’s performance makes it a viable option for diagnostic support tools where real-time predictions are necessary.
* Its adaptability to complex relationships can be advantageous in datasets with nonlinear trends.
* However, the computational cost in large datasets may make it less ideal for real-time or resource-constrained environments.

**Summary:** KNN is reliable for predicting heart disease, with solid recall for spotting non-heart disease cases (87%) and high precision (90%) for detecting heart disease. Great choice if we need a consistent classifier.

<br>
<br>

    
## Logistic Regression Model Performance

![image](https://github.com/user-attachments/assets/b88e8910-3113-45a6-9bdc-ca5357b0aeef)




**Classification Metrics:**

* Accuracy: Same as KNN, with 85.32% accuracy.
* Classification Metrics:
    * No Heart Disease (Class 0):
      * **Precision:** 80%
      * **Recall:** 87%
      * **F1-Score:** 0.83
    * Heart Disease (Class 1):
      * **Precision:** 90%
      * **Recall:** 84%
      * **F1-Score:** 0.87
    * **Averages:** Macro and weighted averages around 0.85, consistent across both classes.
    * **AUC:** Slightly better than KNN with an AUC of 0.93.
  
**Strengths:**

* High AUC of 0.93 show the different between patients with and without heart disease.
* Precision of 90% make sure a low rate of false positives, making it reliable for classification true heart disease cases.
* Balanced performance in both classes, as demonstrated by the almost equal macro and weighted averages.

  
**Insights for Medical Applications:**

* Logistic Regression is well-suited for classification patients at risk, make sure most cases are accurately classified.
* The high AUC suggests it is effective for testing programs, where false negatives must be minimum.
* Recommended for medical that need models that can be easily understood, as Logistic Regression coefficients offer clear insights into the factors that contribute.

**Summary:** Logistic Regression performs about the same as KNN in accuracy but have a higher AUC, making it slightly better for classify heart disease and non-heart disease cases. Ideal for applications where diagnostic accuracy matters a bit more.

<br>
<br>



## Linear Regression Model Performance
![image](https://github.com/user-attachments/assets/284398c2-f616-4b35-9b12-9f56ba80ed53)




**Classification Metrics:**
* **MSE:** Got a mean squared error of 0.114, shows the average squared difference between predicted probabilities and actual outcomes. A low MSE means the model fits well.
* **Accuracy (with 0.5 threshold):** 84.29% accuracy.
    * **Classification Metrics:**
        * **No Heart Disease (Class 0):**
        * **Precision:** 78%
        * **Recall:** 87%
        * **F1-Score:** 0.82
    * **Heart Disease (Class 1):**
        * **Precision:** 90%
        * **Recall:** 82%
        * **F1-Score:** 0.86
    * **Averages:** Macro and weighted averages hover around 0.84, so it’s balanced but slightly lower than the other models.
    * **AUC:** Scored an AUC of 0.92, close to KNN but lower Logistic Regression’s AUC about 0.93.

**Strengths:**

* The model has strong predictive ability, especially in identifying patients with heart disease (Class 1). With a high precision of 90%, it minimum false positive
* An AUC=0.92 confirms the model's strong in spotting between classes across varying thresholds.

**Weaknesses:**

* Slightly lower precision (78%) for patients without heart disease (Class 0) show the potential overprediction of heart disease patient, which may lead to unnecessary secondary tests.

**Medical Applications**
* **Screening Programs:** The model is ideal for initial heart disease check especially in high-risk populations. Its high recall for detecting heart disease make sure that most cases are classify.
* **Preventive Interventions:** By accurately predicting at-risk individuals, medical providers can get resources for preventive measures like lifestyle recommend or early medical steps.
* **Resource Optimization:** Efficiently classifies patients into risk categories, allowing targeted diagnostics and treatment, reducing unnecessary tests for low-risk individuals.

**Sumary:** The linear regression model achieves strong accuracy (84.29%) and AUC (0.92), making it reliable for predicting heart disease, with high precision (90%) for identifying high risk patients. However, slightly lower precision for "No Heart Disease" suggests sometimes misdiagnosed. 
# V. Conclusion
In conclusion, this analysis shows that heart disease risk is related to several factors, such as age, cholesterol, blood pressure, blood sugar, and chest pain type. The results suggest that middle-aged and older adults, especially those with high cholesterol, high blood sugar, or certain chest pain types, have a higher risk. However, no single factor alone can predict heart disease. Looking at multiple factors together gives a clearer understanding.

Between the models tested, both Logistic Regression and K-Nearest Neighbors worked well for predicting heart disease, with Logistic Regression being a bit more accurate. This may make it a better choice for this data. Overall, a balanced approach that includes careful monitoring, focusing on high-risk factors, and keeping data accurate could help in preventing and managing heart disease effectively.


