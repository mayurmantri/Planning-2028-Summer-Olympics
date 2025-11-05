# Planning the 2028 Summer Olympics  
### Predictive Analysis & Strategic Insights Using Python and Tableau

## 📌 Project Introduction
This data analytics project was developed as part of my professional portfolio to demonstrate predictive modelling, exploratory analysis, and data-driven decision support for the upcoming **Los Angeles 2028 Summer Olympics**.

Using historical Olympic datasets, the project answers key business questions relevant to event planning, including expected athlete participation, gender distribution trends, host country performance patterns, and the geographic spread of athlete participation.

A Tableau dashboard was designed to visually communicate the insights, supported by statistical modelling and data preparation completed in Python.

## 📊 Interactive Dashboard
[Click here to view the interactive Tableau dashboard](https://public.tableau.com/views/Olympics_Data_Analysis_17615937750060/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## ✅ Business Problems & Analytical Solutions

### **1. How many athletes are expected to participate in 2028?**
- **Approach:** Ordinary Least Squares (OLS) Regression was implemented in Python using historical athlete participation data.
<img width="1672" height="721" alt="image" src="https://github.com/user-attachments/assets/75016b50-abe0-454c-bd33-0d9416a6416f" />

- **Outcome:** The model predicts approximately **12,044 athletes** in 2028, with an **R-squared value of 0.908**, showing strong model performance and reliability.
- **Business Value:** Authorities can plan logistics, accommodation, transport, security and facility requirements more accurately based on projection rather than assumptions.

---

### **2. What will the gender distribution look like?**
<img width="1363" height="460" alt="image" src="https://github.com/user-attachments/assets/a54f9b5a-f335-4124-8897-df4e1fdd15fd" />

- **Approach:** Gender trends were analysed and visualised using Tableau doughnut charts.
- **Insight:** Female participation has steadily increased. The ratio in the last Olympics (2020) is:
  - Male: **52.2%**
  - Female: **48.8%**
- **Business Value:** As participation approaches a 50-50 balance, organisers must allocate equal facilities, amenities, training areas, medical support and accommodation.

---

### **3. Do host countries gain a competitive advantage?**

<img width="1356" height="426" alt="image" src="https://github.com/user-attachments/assets/82f1a252-e33b-4117-a99c-9c98d318bd8b" />

- **Approach:**  
  A comparative analysis of **average proportion of medals** was carried out between host nations and non-host nations.

- **Insight:**  
  Host countries consistently demonstrate a higher share of medals when compared to their performance in years where they are not the host.

- **Business Value:**  
  This result helps stakeholders understand:
  - Strategic advantages for host nations (home support, reduced travel stress, familiar environment).
  - Policy implications for competitive neutrality.
  - Better forecasting of medal expectations for the host.

---

### **4. Which countries send the maximum number of athletes?**
<img width="1345" height="415" alt="image" src="https://github.com/user-attachments/assets/2a03a20b-4586-493d-b379-f3ccd8755a2e" />

- **Approach:**  
  A global choropleth map visualised athlete participation by country.

- **Insight:**  
  Nations such as the **United States, Japan, and Australia** send the largest contingents.  
  Higher athlete volume typically correlates with:
  - Larger training ecosystems
  - Higher sports funding
  - Operational complexity

- **Business Value:**  
  Countries with large delegations will require more facilities, housing and logistics, allowing organisers to allocate resources intelligently.

---

## 🛠️ Tools & Technologies Used
| Tool | Purpose |
|------|---------|
| **Python (Pandas, NumPy)** | Data cleaning and preprocessing |
| **Statsmodels / Scikit-learn** | OLS regression modelling and validation |
| **Matplotlib & Seaborn** | Exploratory visualisation |
| **Tableau** | Interactive dashboard and advanced charts |
| **Jupyter Notebook** | Development and documentation environment |

---

## ✅ Conclusion
This project demonstrates how data science can support large-scale event planning. Through regression forecasting, gender analytics, comparative performance analysis and geographic insights, the study provides actionable findings for future Olympic preparation.

The solution is scalable, data-driven, and adaptable for more complex scenarios such as sport-wise forecasting, economic impact modelling and athlete cluster segmentation.

---

## 📂 Project Deliverables
- Python data analysis notebook  
- Tableau dashboard (visual insights)  
- Regression model prediction results  
- Cleaned datasets

---

## 👤 Author
**Mayur Mantri**  
Data Analyst | Visual Storyteller 

