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



- Cardiovascular diseases (CVDs) are like the top reason people die worldwide, killing about 17.9 million people every year, which is 31% of all deaths. Out of these, like 4 out of 5 deaths are from heart attacks and strokes, and a third of them happen to people under 70, which is considered early. Heart failure is a usual problem caused by CVDs, and this dataset has 11 features to try to predict if someone might get heart disease.

- People who already have CVD or are at high risk—maybe because they have high blood pressure, diabetes, high cholesterol, or already have the disease—need to be detected early and managed. Using a machine learning model could help a lot in finding and handling these risks.
<br>

# II. Data Discussion
</div>

- **Age:** age of the patient [years]
- **Sex:** sex of the patient [M: Male, F: Female]
- **ChestPainType:** chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- **RestingBP:** resting blood pressure [mm Hg]
- **Cholesterol:** serum cholesterol [mm/dl]
- **FastingBS:** fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- **RestingECG:** resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation  or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- **MaxHR:** maximum heart rate achieved [Numeric value between 60 and 202]
- **ExerciseAngina:** exercise-induced angina [Y: Yes, N: No]
- **Oldpeak:** oldpeak = ST [Numeric value measured in depression]
- **ST_Slope:** the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- **HeartDisease:** output class [1: heart disease, 0: Normal]

<div align="center">
  </div>
# III. Charts and Insights
![image](https://github.com/user-attachments/assets/941ca8f3-a43b-4e5f-b2a8-8f7012ffd22b)
<div align="center">
**Age Distribution of Patients**
      </div>
   <br>
The age distribution of the patients in the dataset is shown in the histogram with a KDE curve overlaid. The pattern of the distribution appears to be almost bell-shaped (or normal distribution), meaning most patients fall within a central age range, with fewer younger and older patients on the edges.
  <br>
   <br>
 **Key Observations**
   <br>
- **Age Range:** The dataset includes patients mostly between 30 and 75 years. We can see there are barely any patients under 30 or over 75 years, as indicated by the low bars at the edges.
- **Peak Age Group**: The group with the most patients is between 55 and 60 years old, where the count reaches about 120. This suggests that the dataset has a heavy focus on middle-aged to older adults, especially those in their late 50s.
- **Symmetry**: The distribution is somewhat symmetrical around the peak age, with almost an equal number of patients on either side of the 55–60 range. This might mean the dataset is representative of middle-aged to senior adults but with fewer younger (30s) and very old (70s) patients.
  <br>
   <br>
**Implications of the Age Distribution**
  <br>
- Focus on Middle-Aged and Older Adults: With most patients between 50 and 70 years old, this dataset aligns with the general trend of heart disease risk, which usually goes up with age. The demographic profile suggests that this dataset is likely geared towards studying heart disease among age groups that are more likely to experience cardiovascular issues. This might be helpful for targeted health measures.
- Target Population for Heart Disease Analysis: Considering the age distribution, this dataset probably represents a population more at risk for heart disease, which could be useful for healthcare strategies aimed at middle-aged and senior patients. Having a lot of patients in their late 50s might imply that early interventions and risk management could be a focus for this age group.
- Data Limitations for Younger and Very Elderly Groups: There aren’t many patients under 30 or over 75, which could be a limitation in applying any findings across all age groups. Insights gained from this dataset might not be fully applicable to very young adults or the very elderly, and collecting more data on these groups could give a fuller picture.
  <br>
  => In summary, the dataset’s age distribution centers on middle-aged and senior adults, especially those aged 55–60 who are typically at higher risk for heart disease. This concentration makes the dataset relevant for heart disease studies in these age groups, which might also aid in designing preventive health measures and healthcare plans. However, while this dataset gives valuable insights into heart disease risk for middle-aged and older adults, it might require more data from younger and elderly groups to understand heart disease dynamics across the entire age range.

![image](https://github.com/user-attachments/assets/8a89f3d0-7a51-44de-8d74-bf7493165087)
**Age Distribution of Heart Disease Cases**
This chart shows heart disease cases by age group, with orange indicating patients with heart disease and light blue for those without.
 <br>
  <br>
**Key Observations**
50–60 Age Group: Highest rate of heart disease; orange segment dominates.
60–70 Age Group: Also high in heart disease cases, though slightly fewer than 50–60.
30–40 & 40–50 Groups: More balanced, with both affected and unaffected individuals.
70–80 Age Group: Few patients, but most have heart disease, linking age to higher risk.
 <br>
  <br>
**Age-Related Trends**
Heart disease risk clearly goes up with age, peaking in the 50–60 range and staying high in older groups.
 <br>
  <br>
**Implications**
- **Preventive Focus**: Efforts should target the 50–70 age range with screenings and lifestyle guidance.
- **Early Screening**: Heart disease, though less common, is present in younger groups, suggesting earlier screenings could help.
- **Resource Allocation**: Healthcare should focus resources on middle-aged and older adults, especially 50+.
=>  Heart disease increases with age, especially from 50 onwards. Targeted interventions and resources for these age groups could help manage and reduce heart disease effectively.

![image](https://github.com/user-attachments/assets/1d7409a2-adf5-4fbe-80ba-2794637550a5)
Cholesterol level by Heart Disease Status

![image](https://github.com/user-attachments/assets/a8f75074-954d-4ed5-911e-8f0a33b795e2)
The distribution of different chest pain types

![image](https://github.com/user-attachments/assets/51811154-b544-4525-a4d1-ffb4d0dda35a)
Heart Disease By farsting blood sugar level

![image](https://github.com/user-attachments/assets/1d960389-e380-4e6f-b6cf-e7e7b3a4e80b)
Age and maximum heart rate 

![image](https://github.com/user-attachments/assets/383202ca-dc13-4c37-abf8-1e086e5d8f27)
Cholesterol levels and resting blood pressure 

![image](https://github.com/user-attachments/assets/67920a28-e8d4-4aee-b9da-766cc47458b1)
Shows the distribution of cholesterol levels 

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
