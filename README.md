<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=salesp07.salesp07" />

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=30&center=true&vCenter=true&width=500&height=70&duration=5000&lines=Hello+Mr+EC!+👋;Our+data+presentation;+Coronary+Artery+Heart+Disease;" />
</h1>

<h3 align="center">Research from Group 5</h3>
<br/>
<div align="center">
 
**Coronary Artery heart Disease**
<ul>
<li>Subject: Data Science</li>
<li>Class: MAS2</li>
<li>Lecturer: Dr. Emmanuel Lance Christopher VI M. Plan</li>
</ul>
.

# Team Member 

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

# I. Introduction



* Cardiovascular diseases (CVDs) are like the top reason people die worldwide, killing about 17.9 million people every year, which is 31% of all deaths. Out of these, like 4 out of 5 deaths are from heart attacks and strokes, and a third of them happen to people under 70, which is considered early. Heart failure is a usual problem caused by CVDs, and this dataset has 11 features to try to predict if someone might get heart disease.

* People who already have CVD or are at high risk—maybe because they have high blood pressure, diabetes, high cholesterol, or already have the disease—need to be detected early and managed. Using a machine learning model could help a lot in finding and handling these risks.

# II. Data Discussion
</div>

* **Age:** age of the patient [years]
* **Sex:** sex of the patient [M: Male, F: Female]
* **ChestPainType:** chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
* **RestingBP:** resting blood pressure [mm Hg]
* **Cholesterol:** serum cholesterol [mm/dl]
* **FastingBS:** fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
* **RestingECG:** resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation  or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
* **MaxHR:** maximum heart rate achieved [Numeric value between 60 and 202]
* **ExerciseAngina:** exercise-induced angina [Y: Yes, N: No]
* **Oldpeak:** oldpeak = ST [Numeric value measured in depression]
* **ST_Slope:** the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
* **HeartDisease:** output class [1: heart disease, 0: Normal]

<div align="center">
  
# III. Charts and Insights
  </div>
  
![image](https://github.com/user-attachments/assets/941ca8f3-a43b-4e5f-b2a8-8f7012ffd22b)

## Age Distribution of Patients

The age distribution of the patients in the dataset is shown in the histogram with a KDE curve overlaid. The pattern of the distribution appears to be almost bell-shaped (or normal distribution), meaning most patients fall within a central age range, with fewer younger and older patients on the edges.
  
 **Key Observations**

* **Age Range:** The dataset includes patients mostly between 30 and 75 years. We can see there are barely any patients under 30 or over 75 years, as indicated by the low bars at the edges.
* **Peak Age Group**: The group with the most patients is between 55 and 60 years old, where the count reaches about 120. This suggests that the dataset has a heavy focus on middle-aged to older adults, especially those in their late 50s.
* **Symmetry**: The distribution is somewhat symmetrical around the peak age, with almost an equal number of patients on either side of the 55–60 range. This might mean the dataset is representative of middle-aged to senior adults but with fewer younger (30s) and very old (70s) patients.
 
**Implications of the Age Distribution**
 
* Focus on Middle-Aged and Older Adults: With most patients between 50 and 70 years old, this dataset aligns with the general trend of heart disease risk, which usually goes up with age. The demographic profile suggests that this dataset is likely geared towards studying heart disease among age groups that are more likely to experience cardiovascular issues. This might be helpful for targeted health measures.
* Target Population for Heart Disease Analysis: Considering the age distribution, this dataset probably represents a population more at risk for heart disease, which could be useful for healthcare strategies aimed at middle-aged and senior patients. Having a lot of patients in their late 50s might imply that early interventions and risk management could be a focus for this age group.
* Data Limitations for Younger and Very Elderly Groups: There aren’t many patients under 30 or over 75, which could be a limitation in applying any findings across all age groups. Insights gained from this dataset might not be fully applicable to very young adults or the very elderly, and collecting more data on these groups could give a fuller picture.

  => In summary, the dataset’s age distribution centers on middle-aged and senior adults, especially those aged 55–60 who are typically at higher risk for heart disease. This concentration makes the dataset relevant for heart disease studies in these age groups, which might also aid in designing preventive health measures and healthcare plans. However, while this dataset gives valuable insights into heart disease risk for middle-aged and older adults, it might require more data from younger and elderly groups to understand heart disease dynamics across the entire age range.

![image](https://github.com/user-attachments/assets/8a89f3d0-7a51-44de-8d74-bf7493165087)
## Age Distribution of Heart Disease Cases

This chart shows heart disease cases by age group, with orange indicating patients with heart disease and light blue for those without.

**Key Observations**

* **50–60 Age Group**: Highest rate of heart disease; orange segment dominates.
* **60–70 Age Group**: Also high in heart disease cases, though slightly fewer than 50–60.
* **30–40 & 40–50 Groups**: More balanced, with both affected and unaffected individuals.
* **70–80 Age Group**: Few patients, but most have heart disease, linking age to higher risk.

**Age-Related Trends**

Heart disease risk clearly goes up with age, peaking in the 50–60 range and staying high in older groups.
 
**Implications**

* **Preventive Focus**: Efforts should target the 50–70 age range with screenings and lifestyle guidance.
* **Early Screening**: Heart disease, though less common, is present in younger groups, suggesting earlier screenings could help.
* **Resource Allocation**: Healthcare should focus resources on middle-aged and older adults, especially 50+.
   
=>  Heart disease increases with age, especially from 50 onwards. Targeted interventions and resources for these age groups could help manage and reduce heart disease effectively.

![image](https://github.com/user-attachments/assets/1d7409a2-adf5-4fbe-80ba-2794637550a5)
## Cholesterol level by Heart Disease Status

This box plot shows cholesterol levels for patients with (1) and without (0) heart disease. The y-axis represents cholesterol levels.
  
**Key Observations**
  
* **Median Levels:**
  * Patients without heart disease have a median cholesterol slightly above 200 mg/dL.
  * Patients with heart disease have a somewhat higher median, suggesting elevated cholesterol might be linked to heart disease.
* **Distribution:**
  * Non-heart disease patients have a tighter range (IQR), with most cholesterol values between 175 and 275 mg/dL.
  * Heart disease patients show a broader spread, with values reaching up to 350 mg/dL, indicating more cholesterol variability in this group.
* **Outliers:**
  * The non-heart disease group has more extreme outliers, with some very high (above 400 mg/dL) and low (below 100 mg/dL) values.
  * The heart disease group has fewer outliers but a generally wider spread, showing that high cholesterol is common here.
  
**Implications**

* **Cholesterol Management:** The higher median and broader spread in the heart disease group imply that controlling cholesterol could help reduce risk. Lifestyle changes and medications could be useful for patients with elevated levels.
* **Comprehensive Screening:** Outliers suggest cholesterol alone isn’t enough to predict heart disease accurately. Screening for other risk factors (like blood pressure) would give a fuller picture.
* **Age and Lifestyle Impact:** The variability in cholesterol, especially among heart disease patients, might reflect age or lifestyle factors. Targeted programs based on these factors could improve heart disease prevention.
 
**Conclusion**

 => Higher cholesterol levels are linked to a higher risk of heart disease, but they’re not the only factor. Heart disease patients generally have a broader and higher range of cholesterol, emphasizing the importance of cholesterol management. However, a well-rounded approach considering other factors (age, lifestyle) could be more effective for prevention.



![image](https://github.com/user-attachments/assets/a8f75074-954d-4ed5-911e-8f0a33b795e2)

## Chest Pain Type and Heart Disease
  
This bar chart shows the distribution of chest pain types among patients with and without heart disease. Each chest pain type (ASY, ATA, NAP, TA) is on the x-axis, while the y-axis shows the number of patients. Orange represents those with heart disease; blue represents those without.
  
    
**Key Observations**

* **ASY (Atypical Angina)**: Mostly linked to heart disease, as shown by the dominant orange bar. Very few ASY patients don’t have heart disease, suggesting it’s a strong indicator of heart disease.
* **ATA (Asymptomatic)**: Primarily associated with patients without heart disease, shown by the large blue bar. Only a few ATA patients have heart disease, so it’s less of a risk indicator.
* **NAP (Non-Anginal Pain)**: Higher count of patients without heart disease, but some with heart disease. This type is not a major indicator but still relevant.
* **TA (Typical Angina)**: Roughly equal counts of heart disease and non-heart disease cases, suggesting it's a moderate risk factor.
  
**Implications**

* **Risk Assessment**: ASY is a strong heart disease indicator and should prompt further testing. ATA and NAP, however, are less concerning and might not need immediate action.
* **Diagnostic Prioritization**: Clinicians can use chest pain types to decide who needs urgent testing. ASY patients might be prioritized, while ATA and NAP can be lower priority.
* **Resource Allocation**: Resources can be better managed by focusing on ASY patients for immediate care, while NAP and ATA patients might follow a standard pathway.
    
**Conclusion:**

 => Atypical angina (ASY) is closely linked to heart disease, making it useful for early risk assessment. Chest pain type can help clinicians prioritize patients for faster diagnosis, especially those with ASY.


![image](https://github.com/user-attachments/assets/51811154-b544-4525-a4d1-ffb4d0dda35a)
   
## Fasting Blood Sugar Levels and Heart Disease

This bar chart shows how fasting blood sugar levels relate to heart disease. On the x-axis, 0 means blood sugar ≤120 mg/dl, and 1 means >120 mg/dl. The y-axis shows patient count, with blue for patients without heart disease and orange for those with heart disease.
          
**Key Observations**

* **Normal Fasting Blood Sugar (≤120 mg/dl)**: Most patients have normal blood sugar levels, with a slightly higher count of non-heart disease cases (blue) than heart disease cases (orange). This suggests that normal blood sugar is common in both groups, but those without heart disease slightly outnumber those with it.
* **Elevated Fasting Blood Sugar (>120 mg/dl)**: For high blood sugar patients, the majority have heart disease (orange). This shows a strong link between elevated blood sugar and heart disease, as only a few with high blood sugar do not have heart disease.
* **Overall Correlation**: High fasting blood sugar levels are associated with a higher likelihood of heart disease, making it a potential risk factor. Normal blood sugar levels, on the other hand, are more evenly spread between the groups.
  
**Implications**

* **Risk Indicator**: Elevated blood sugar (>120 mg/dl) could indicate higher heart disease risk, suggesting that monitoring blood sugar is important for identifying at-risk patients.
* **Blood Sugar Management**: Since high blood sugar correlates with heart disease, managing blood sugar through diet, lifestyle changes, and medications could help lower risk.
* **Preventive Care**: Regular screening of fasting blood sugar, especially for those with other risk factors, could be useful in preventing heart disease.
   
**Conclusion**:
    
   The chart shows a clear link between high blood sugar levels and heart disease. Patients with high blood sugar are mostly in the heart disease group, highlighting the importance of blood sugar control and monitoring as a way to reduce heart disease risk.
   

![image](https://github.com/user-attachments/assets/1d960389-e380-4e6f-b6cf-e7e7b3a4e80b)

## Age and maximum heart rate 

**Age and Max Heart Rate in Relation to Heart Disease:**

This scatter plot shows how age and maximum heart rate relate to heart disease. Each dot represents a patient, with blue for patients without heart disease and orange for those with heart disease.

**Key Observations**

* **Age and Heart Disease:** Heart disease cases (orange dots) are mostly among older patients, especially those over 50. Younger patients are more likely to be without heart disease (blue dots).
* **Max Heart Rate and Heart Disease:** Patients without heart disease (blue) tend to have higher max heart rates, often around 150 or more, regardless of age. Those with heart disease (orange) usually have lower max heart rates, often below 140, especially as they get older.
* **Trend with Age:** Max heart rate decreases as age increases, which is normal, but this decrease is more noticeable in heart disease patients, where older individuals tend to have even lower max heart rates.

**Implications**

* **Max Heart Rate as a Heart Disease Indicator:** A lower max heart rate in older patients could signal higher heart disease risk, suggesting it’s a useful metric for heart health assessment, especially in those over 50.
* **Screening Based on Age and Max Heart Rate:** Older patients with low max heart rates might need more intensive screening since they’re at higher risk for heart disease.
  
**Conclusion**
  
This chart shows that lower max heart rates are linked to heart disease, especially in older adults. Tracking max heart rate with age could help spot at-risk individuals, supporting early action for heart disease prevention.

![image](https://github.com/user-attachments/assets/383202ca-dc13-4c37-abf8-1e086e5d8f27)

## Cholesterol levels and resting blood pressure 

The scatter plot visualizes cholesterol levels and resting blood pressure among patients, differentiated by blue dots for those without heart disease and green dots for those with heart disease.

**Key Observations**

* **Cholesterol Levels:** The majority of patients, regardless of heart disease status, have cholesterol levels between 150 and 300 mg/dL. Cases with cholesterol levels reaching up to 600 mg/dL are uncommon.

* **Resting Blood Pressure:** Blood pressure ranges from 100 to 160 mmHg for both groups. There is no significant difference in blood pressure levels between patients with and without heart disease, as their ranges overlap.

* **Outliers:** Some patients show very low cholesterol levels, close to zero, likely due to missing or erroneous data.

* **No Clear Separation:** Cholesterol and blood pressure levels do not distinctly separate the two groups, indicating that these factors alone are insufficient for predicting heart disease.

**Implications**

* **Combined Risk Factors:** Cholesterol and blood pressure should be analyzed alongside other factors, such as age and chest pain type, for a more accurate heart disease risk assessment.

* **Data Cleaning:** The presence of low cholesterol outliers highlights the need for data cleaning to improve accuracy.

**Conclusion**

Higher cholesterol and resting blood pressure levels are associated with heart disease, but they are not standalone predictors. A comprehensive risk assessment must consider multiple factors, and addressing data anomalies will enhance the reliability of the analysis.

![image](https://github.com/user-attachments/assets/67920a28-e8d4-4aee-b9da-766cc47458b1)

## Cholesterol Distribution in Heart Disease Patients

This histogram with KDE overlays illustrates cholesterol levels among patients with and without heart disease. The x-axis represents cholesterol levels, while the y-axis shows patient count. Orange bars signify patients with heart disease, and blue bars represent those without.

**Key Observations**

Cholesterol Levels Near Zero: There’s a notable number of patients with cholesterol levels close to zero, all represented by the orange bar (patients with heart disease). This is likely due to missing or incorrect data, as zero cholesterol isn’t realistic.

**Typical Cholesterol Distribution:**

* **Without Heart Disease (blue):** Peaks around 200–250 mg/dL, which is in the normal to borderline-high range.

* **With Heart Disease (orange):** Peaks in the same range but with a wider spread, often extending above 250 mg/dL.

* **Higher Cholesterol and Heart Disease:** Cholesterol levels over 250 mg/dL are more common in heart disease patients, with some cases even exceeding 400 mg/dL.

* **Overlap in Ranges:** Both groups overlap significantly in the 150–250 mg/dL range, indicating that cholesterol levels alone do not clearly separate the groups.

**Implications**

* **Data Cleaning:** The instances of zero cholesterol suggest data quality issues that could affect the results. These values may need to be corrected or removed.

* **Cholesterol as a Risk Indicator:** Higher cholesterol levels are more common in heart disease patients, but due to the overlap, it’s best to consider cholesterol alongside other risk factors for a more accurate assessment.

* **Managing High Cholesterol:** Given its prevalence in heart disease cases, managing high cholesterol could be key to preventing and controlling heart disease.

**Conclusion**

High cholesterol is more prevalent among heart disease patients; however, because there is an overlap with patients without heart disease, cholesterol alone isn't a standalone predictor. Elevated cholesterol can still warrant closer monitoring, especially when combined with other risk factors. Additionally, near-zero values should be checked for accuracy to prevent skewed analysis.

![image](https://github.com/user-attachments/assets/ff231f41-5dff-4bb5-9cde-bac7cad81781)
ROC Curve - KNN

![image](https://github.com/user-attachments/assets/e26c3638-5bd2-4aed-88be-513226894cc4)
ROC Curve - Logistic Regression

![image](https://github.com/user-attachments/assets/d59e4292-22d7-4eeb-aee1-6325ae34977c)
ROC Curve - Linear Regression



# IV. Charts and Insights
**1. Smoking vs. Medical Charges**
Smokers pay way more. The box plot shows smokers have much higher charges than non-smokers. Recommendation: charge smokers more.
![image](https://github.com/user-attachments/assets/400166d9-384b-4f84-80c3-cfa311181709)
<br>

**Chart Analysis: Smoking vs Medical Charges**


**Which One is Highest?**
- **Smokers** pay significantly higher medical charges than non-smokers. The median cost for smokers is around **$35,000**, while for non-smokers it's just **$8,000**. The highest costs for smokers go over **$60,000**, compared to non-smokers who rarely exceed **$20,000**.
**Increasing/Decreasing Pattern?**
- There's no specific increasing or decreasing trend shown here because this is a comparison between two groups. What it clearly shows is a **huge difference** in medical costs between smokers and non-smokers. Smokers always have higher costs—no exceptions.
**Why is This Important?**
<br>
**=>**  Smokers are a high-risk group with much higher and more unpredictable medical expenses. This means **higher premiums** are needed for smokers to balance out the increased risk. The cost difference is too big to ignore; smokers need to pay more because they cost the company more. Straightforward decision—charge them more, minimize the company's financial risk.

**2. BMI Categories vs. Medical Charges**
People were grouped by BMI: underweight, normal, overweight, obese. The box plot shows obese people face higher charges. This means BMI is a good factor for predicting high costs.
![image](https://github.com/user-attachments/assets/ec0abee4-7214-4d00-b007-54f89cced786)
<br>

**Chart Analysis: BMI Category vs Medical Charges**



**Which One is Highest?**
- **Obese** individuals have the highest medical charges. The median cost is higher than the other BMI categories, and there are many outliers with extremely high charges (some even exceeding **$60,000**).
- **Underweight, Normal, and Overweight** categories have similar median charges, all much lower than the obese group.
**Increasing/Decreasing Pattern?**
- There is an **increasing pattern** in medical charges as BMI goes up. Medical charges steadily rise from **underweight to obese**. Obese individuals have a significant jump in costs compared to the others.
**Why is This Important?**
<br>
**=>**  Obese individuals are driving higher costs, which means they are a higher risk group. To manage this risk, insurance premiums should be higher for obese individuals. The cost difference is clear—people with higher BMIs (specifically those classified as obese) cost more in healthcare. Adjust the premiums accordingly to make sure the higher risk (higher medical expenses) is covered by higher pricing. Simple decision—higher risk, higher cost.

**3. Age vs. Medical Charges**
Charges increase with age, especially after 50. The scatter plot shows this clearly. Older people are more likely to need higher-cost insurance.
These charts directly show who has higher costs—smokers, older people, and those with higher BMI. This means insurance companies should adjust premiums accordingly.
![image](https://github.com/user-attachments/assets/85e7baca-e438-43b9-a7f9-5ddc387d20c5)
<br>

**Chart Analysis: Age vs Medical Charges**
</br>
<br>
**Which One is Highest?**
- **Smokers** always have the highest medical charges compared to non-smokers, regardless of age. The **blue dots** represent smokers, and they are consistently above the **orange dots** (non-smokers).
- As age increases, the medical charges also increase for both smokers and non-smokers, but smokers consistently pay much more. The highest charges go well above **$60,000**, mostly for older smokers.
**Increasing/Decreasing Pattern?**
- **Increasing Pattern**: Medical costs **increase with age**. The older the person, the more they pay, especially if they smoke. The charges rise for both groups, but the gap between smokers and non-smokers remains obvious and significant at every age group.
**Why is This Important?**
<br>
**=>**  Age and smoking are two major factors driving up medical costs. Older people cost more, and smokers cost way more. So, adjust the premiums—charge **older people higher premiums** based on the increased cost with age, and **charge smokers even more** to cover their significantly higher health risks. The costs aren't the same for everyone—insurance pricing needs to reflect this. Higher age and smoking mean higher costs, so premiums need to go up for these groups..
</br>

# V. Conclusion
Smoking, age, and BMI are the main factors driving medical costs. Smokers, older people, and those with high BMI should be charged higher premiums based on their risk. No fluff—just straight insights and recommendations.
</div>
