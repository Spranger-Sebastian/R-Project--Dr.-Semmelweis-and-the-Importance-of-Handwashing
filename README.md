![ignaz_semmelweis_1860](https://github.com/user-attachments/assets/ae28b57b-0ed6-4494-a559-8e94d435b9a1)


### **Abstract**
Dr. Ignaz Semmelweis, a Hungarian physician working at the Vienna General Hospital during the mid-19th century, significantly impacted medical practices through his pioneering investigation into hand hygiene. While serving in the maternity wards, Semmelweis observed a high incidence of puerperal fever (childbed fever), which led to substantial mortality rates among mothers. Despite the prevailing medical ignorance regarding bacteria at the time, Semmelweis identified contaminated hands of medical staff as the primary transmission route of infections. On June 1, 1847, he mandated rigorous handwashing procedures, a groundbreaking and initially controversial measure. This research revisits Semmelweis' historical data, employing modern statistical techniques to quantify the impact of implementing hand hygiene protocols on maternal mortality rates, thus providing empirical validation of his seminal observations.

### **Introduction**
Ignaz Semmelweis' contributions to medical hygiene emerged from meticulous observation at Vienna General Hospital, where high maternal mortality rates from puerperal fever posed a critical health crisis. In the absence of microbiological knowledge, Semmelweis intuitively linked poor hand hygiene among medical personnel to increased infections and deaths. By introducing compulsory handwashing in June 1847, he dramatically altered the outcomes in maternity wards. This study critically reanalyzes Semmelweis' original dataset, applying statistical methodologies to affirm and measure the significance of hand hygiene interventions on patient survival, thus underscoring the enduring value of his discovery in contemporary medical practice.

### **Data and Methodology**
#### **1. Data Sources**
The data is stored as two CSV files within the `data` folder.

`yearly_deaths_by_clinic.csv` contains the number of women giving birth at the two clinics at the Vienna General Hospital between the years 1841 and 1846.

| Column | Description |
|--------|-------------|
|`year`  |Years (1841-1846)|
|`births`|Number of births|
|`deaths`|Number of deaths|
|`clinic`|Clinic 1 or clinic 2|

`monthly_deaths.csv` contains data from 'Clinic 1' of the hospital where most deaths occurred.

| Column | Description |
|--------|-------------|
|`date`|Date (YYYY-MM-DD)
|`births`|Number of births|
|`deaths`|Number of deaths|

The handwashing protocol was introduced on **June 1, 1847**, and serves as the intervention point for comparison.

#### **2. Analytical Approach**
Key statistical techniques applied in this study include:
- **Descriptive Statistics:** Calculation of mortality rates before and after the intervention.
- **t-Test:** Assessment of statistical significance in mortality rate changes.
- **Linear Regression Analysis:** Estimation of the effect size of handwashing on mortality.
- **Cohen’s d:** Measurement of the magnitude of the observed effect.
- **Correlation Analysis:** Determination of the relationship between handwashing and mortality reduction.



### **Results**
#### **1. Mortality Proportion Before and After Handwashing**

![image](https://github.com/user-attachments/assets/f59edc71-5e68-4ed9-9a0f-48bb9ff722a2)

| Handwashing Implemented | Mean Mortality Rate (%) |
|------------------------|-----------------------|
| **No** | **10.5** |
| **Yes** | **2.1** |

Following the introduction of handwashing, mortality rates decreased significantly from **10.5% to 2.1%**, underscoring the effectiveness of hygiene practices.

#### **2. Statistical Tests and Findings**
- **t-Test Results:** A Welch Two-Sample t-test reveals a statistically significant difference between pre- and post-intervention mortality rates (p-value = **1.445e-15**), confirming a robust effect.
- **Regression Analysis:** The linear regression model estimates a **8.4% reduction** in mortality attributed to handwashing (p-value = **2.99e-07**), indicating a strong association.
- **Effect Size (Cohen’s d):** A value of **-1.334** denotes a **large effect size**, reinforcing the substantial impact of handwashing practices on patient outcomes.
- **Correlation Coefficient:** The negative correlation between handwashing and mortality further substantiates the protective role of sanitation measures.

### **Discussion**
The empirical evidence strongly supports the hypothesis that handwashing significantly reduces mortality in clinical settings. The statistical significance and large effect size highlight the necessity of rigorous hygiene protocols to prevent the transmission of infectious diseases. These findings align with contemporary medical knowledge, reinforcing the importance of hand hygiene as a fundamental public health measure.

### **Conclusion**
The introduction of hand hygiene practices in 1847 led to a **statistically significant and clinically meaningful reduction in mortality rates**. This study contributes to the broader discourse on the role of sanitation in healthcare, emphasizing the continued relevance of historical lessons in modern medical practice. Future research should explore additional determinants influencing patient survival rates beyond hygiene interventions.


