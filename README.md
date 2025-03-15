# 🧼 Dr. Semmelweis & The Life-Saving Power of Handwashing 🚑  

![Ignaz Semmelweis 1860](https://github.com/user-attachments/assets/ae28b57b-0ed6-4494-a559-8e94d435b9a1)  

## **📜 Abstract**  
In the mid-19th century, **Dr. Ignaz Semmelweis**, a Hungarian physician, revolutionized medical hygiene by proving that **handwashing drastically reduced maternal mortality rates**. Working at the Vienna General Hospital, he observed that **puerperal fever (childbed fever) was being spread by doctors delivering babies after performing autopsies—without washing their hands**. In **June 1847**, Semmelweis introduced **mandatory handwashing**, leading to a **dramatic drop in mortality rates**.  

This project **revisits Semmelweis’ original data** and applies **modern statistical analysis** to quantify the impact of hand hygiene on patient survival.  

---

## **📖 Introduction**  
**How many lives could have been saved if doctors had trusted the data?**  

During the 1840s, **maternity ward mortality rates were alarmingly high**, but the cause was unknown. **Germ theory didn’t exist yet**, and many doctors believed illnesses were caused by "bad air" rather than poor hygiene.  

Semmelweis' **data-driven approach** challenged these assumptions. This project **analyzes his findings using statistical and data visualization techniques**, proving that **handwashing was the key to reducing mortality**—even before bacteria were discovered.  

---

## **📊 Data & Methodology**  
### **1️⃣ Data Sources**  
The dataset consists of two CSV files stored in the `data/` folder.

| 📁 Dataset | 🔍 Description |
|------------|-----------------------------------------------------|
| `yearly_deaths_by_clinic.csv` | Birth and mortality data from **two clinics** (1841-1846). |
| `monthly_deaths.csv` | Monthly birth and death data from **Clinic 1**, where most deaths occurred. |

📌 **Key Event:** The **handwashing protocol was introduced on June 1, 1847**, making it a crucial intervention point for analysis.  

---

### **2️⃣ Analytical Approach**  
This study applies **statistical and data science techniques** to quantify the impact of hand hygiene on mortality rates.

- **📊 Descriptive Statistics:** Mortality rates before and after intervention.
- **📈 t-Test:** Statistical significance of mortality rate reduction.
- **📉 Regression Analysis:** Measuring handwashing’s impact on survival.
- **📊 Cohen’s d:** Quantifying effect size.
- **🔍 Correlation Analysis:** Relationship between handwashing and mortality rates.

---

## **📈 Results & Key Findings**  
### **1️⃣ Mortality Rates Before & After Handwashing**  
Following the introduction of hand hygiene, **mortality dropped from 10.5% to 2.1%**!  

![Mortality Rate Drop](https://github.com/user-attachments/assets/f59edc71-5e68-4ed9-9a0f-48bb9ff722a2)  

| 🚑 **Handwashing Implemented?** | 🏥 **Mean Mortality Rate (%)** |
|----------------------|---------------------|
| ❌ **No (Before 1847)** | **10.5%** |
| ✅ **Yes (After 1847)** | **2.1%** |

📌 **This data confirms that handwashing reduced mortality by nearly 80%.**  

---

### **2️⃣ Statistical Tests & Findings**  
**📊 Statistical significance:**  
✔ **t-Test:** p-value = **1.445e-15** (highly significant!)  
✔ **Regression Analysis:** 8.4% mortality reduction (p = **2.99e-07**)  
✔ **Effect Size (Cohen’s d):** **-1.334** (large effect!)  
✔ **Correlation:** Strong **negative correlation** between handwashing & mortality  

🔥 **Conclusion:** The results confirm that **handwashing had a massive impact on reducing deaths**, even before germ theory was accepted.

---

## **📢 Discussion & Key Takeaways**  
1️⃣ **Data saved lives—even when people ignored it.**  
   - Despite overwhelming evidence, many doctors **refused to believe** Semmelweis' findings, delaying progress.  

2️⃣ **Statistical proof is crucial for medical advancements.**  
   - **Evidence-based policies** (like handwashing & vaccines) have saved millions of lives since then.  

3️⃣ **Clean hands = fewer deaths.**  
   - This historical case proves the importance of **basic hygiene in preventing infectious diseases**.  

---

## **📝 Conclusion**  
This analysis confirms that **Dr. Semmelweis’ handwashing policy drastically reduced mortality rates**, even before germ theory was known. His work laid the foundation for **modern hygiene practices in hospitals**.  

👉 This project is a testament to **why data science matters in real-world decision-making**—sometimes, **the data is right before our eyes, and we just need to act on it.**  

---

## **💻 How to Run the Analysis**  
To reproduce this analysis:  
```bash
# Clone the repository
git clone https://github.com/Spranger-Sebastian/R-Project--Dr.-Semmelweis-and-the-Importance-of-Handwashing.git
cd handwashing-analysis

# Open R and run the script
Rscript analysis.R

```

## 🌍 Connect & Contribute  

💡 **Feedback or suggestions?** Feel free to **fork this repo, open an issue, or connect with me on LinkedIn!**  

📧 **Email:** [sebastianspranger@icloud.com](mailto:sebastianspranger@icloud.com)  
💼 **LinkedIn:** [Sebastian Spranger](https://www.linkedin.com/in/sebastian-spranger-62a467115/)  
📂 **GitHub:** [Sebastian’s GitHub](https://github.com/Spranger-Sebastian)  
🔗 **Full Project Repository:** [GitHub Link](https://github.com/Spranger-Sebastian/R-Project--Dr.-Semmelweis-and-the-Importance-of-Handwashing)  
