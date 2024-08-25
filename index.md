<!--h1 without bottom border-->
<h1 align="center">Hi <img width="35" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/waving.gif">, I'm Chinmay Kulkarni</h1>

<div align="center">
  <img  src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/3fd577e1c9a28f951aefc528ca4e44e854866219/resources/snake.svg"
       alt="snake" />
</div>

<div align="center"> <h3 style="display: inline-block" align="center">Confusion is part of Programming :) </h3></div>


## CAREER SUMMARY

Experienced professional with 3+ years of experience in Life sciences Analytics and clinical trials domain. Passion-driven and self-learnt reporting tools from Coursera and Udemy. Strong willingness and enthusiastic team player with knowledge of clinical data, statistics, and analytics.

<br><br>

## KEY STRENGTHS & SKILLS

### Domains   
- 📊 Business Analytics  
- 💊 Clinical Data Management (CDM)  
- ✍ Medical Writing  

### Technical Skills
- **Data Visualization Tools:** 
  
 <a href="https://chinmayjk97.github.io/digital-cv/#projects"> <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Qliksense.jpg" alt="Qlik Sense"> <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Power-BI.png" alt="Power BI"> <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Tableau-Logo.png" alt="Tableau">  <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/excel.jfif" alt="Excel"></a>

- **Programming Languages:**

SQL
```sql
-- Retrieve all patients with abnormal lab results
SELECT 
    patient_id,
    lab_test,
    lab_value
FROM 
    lab_tests
WHERE 
    lab_value > upper_reference_limit
    OR lab_value < lower_reference_limit;
```

SAS
```sas
/* Calculate the mean and standard deviation of a variable */
proc means data=clinical_data mean std;
    var blood_pressure;
run;
```

R
```r
# Load necessary libraries
library(dplyr)

# Calculate summary statistics for clinical data
clinical_summary <- clinical_data %>%
    group_by(patient_id) %>%
    summarise(
        mean_bp = mean(blood_pressure, na.rm = TRUE),
        sd_bp = sd(blood_pressure, na.rm = TRUE)
    )
```

Python
```python
import pandas as pd
clinical_data = pd.read_csv('clinical_data.csv')

# Calculating Summary Statistics for cholesterol
cholesterol_summary = clinical_data['cholesterol'].agg(['median', 'quantile']).rename({'0.25': 'Q1', '0.75': 'Q3'})
print(cholesterol_summary)

# Filter patients with high cholesterol
high_cholesterol = clinical_data[clinical_data['cholesterol'] > 200]
print(high_cholesterol.head())
```

Java
```java
package com.cjk.pharmaassist;

import androidx.appcompat.app.AppCompatActivity;


public class MainActivity extends AppCompatActivity{
    private static final String TAG = "MainActivity";

    @Override
    public void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        Log.d(TAG, "onCreate on MainActivity executed");
    }
```

Kotlin
```kotlin
fun main() {
    println("Hello World!")
}
```
<!-- tags colours https://github.com/orgs/community/discussions/16925#discussioncomment-10157785-->
<blockquote class="tip">
<p><span>💡 TIP</span><br>
Of these Java and Kotlin were for hobby projects.</p>
</blockquote>

- **Clinical Systems:** IWRS, RTSM, EDC, DMW, ePID, SDTM
- **Regulatory Databases:** Clinicaltrials.gov, EMA (EudraCT), PubMed, ISRCTN, Springer Nature
- **Proficient in MS Office:** Advanced Excel, Word, PowerPoint  

<br>

---

<br>

## 🎯 Goals
✅ Medical Writing  
✅ Clinical Data Management  
✅ Data Analytics  
⏩ Clinical Results - *Biostatistics - Statistical Programming*  
⏩ _TBD ..._

> End Goal is Finding **Ikigai**:
> 
> <a href="https://www.linkedin.com/pulse/ikigai-how-find-your-career-mojo-anne-wilson-sfhea"><img width="500" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Ikigai.jpg"
       alt="ikigai model" /></a>
       

## WORK EXPERIENCE

| Organization |     |
| :-----: | :--- |
| <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/novo.png" width="50"/><br>Novo Nordisk | Functional Programmer<br><i>Nov 2022 – Present</i><br><br><b>Domains:</b><br> - 📊 Business Analytics<br>- 💊 Clinical Data Management (CDM)|
| <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/xogene.png" width="50"/><br>Xogene Solutions | Clinical Trial Transparency Analyst<br><i>July 2021 – Nov 2022</i><br><br><b>Domains:</b><br> - ✍ Medical Writing   | 

---

## CERTIFICATIONS & BADGES

- Programming:
  - [IBM Data Analytics with Excel and R Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/C5JQWE8W528S)
  - [SQL for Data Science with R by IBM](https://www.coursera.org/account/accomplishments/certificate/VFRATFGSSAVZ)
  - [SQL- The Complete Introduction to SQL programming, Udemy](https://www.udemy.com/certificate/UC-398109d9-ea7c-4538-bbac-eb4f7ce6c7de/)
  - [Introduction to R Programming for Data Science by IBM](https://www.coursera.org/account/accomplishments/certificate/XMR6SKTR5RUB)
  - [Introduction to Data Analytics by IBM](https://coursera.org/share/ebb8f0ed2b8eb4e3cfdc4c46af9d9ba0)
  - [Excel Basics for Data Analysis by IBM](https://coursera.org/share/7d929965e12260e14976a59f3329223a)
  - [Python A-Z™: Python for Data Science, Udemy](https://www.udemy.com/certificate/UC-7dbc21ae-1d63-46a7-b83f-84e8bc1bf8e8/)
    
<a href="https://www.credly.com/badges/af1c7824-d8c6-494b-b1d1-42d1f3ff4d62/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Data%20Science%20with%20R%20-%20Capstone%20Project.png" alt="Data Science with R - Capstone Project" width="150"/>
</a>
<a href="https://www.credly.com/badges/eb7df71f-2a7e-411f-988f-58742136168d/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Data%20Analysis%20with%20R.png" alt="Data Analysis with R" width="150"/>
</a>
<a href="https://www.credly.com/badges/ac944718-4b9e-4bdf-b7db-7610e3f36882/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Excel%20Essentials%20for%20Data%20Analytics.png" alt="Excel Essentials for Data Analytics" width="150"/>
</a>
<a href="https://www.credly.com/badges/092650e5-8787-42a0-bb53-4425f180ad9f/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/SQL%20for%20Data%20Science%20with%20R%20Essentials.png" alt="SQL for Data Science with R Essentials" width="150"/>
</a>
<a href="https://www.credly.com/badges/8102b667-eff2-4636-a471-d19fad31d068/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/R%20Programming%20for%20Data%20Science%20Essentials.png" alt="R Programming for Data Science Essentials" width="150"/>
</a>
<a href="https://www.credly.com/badges/ff86ac06-cd03-4396-a300-9ad4640d11b7/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Data%20Analytics%20Essentials.png" alt="Data Analytics Essentials" width="150"/></a>



 - SAS Certifications:
   - [Programming Essentials](https://www.credly.com/badges/66dfefd4-c8f3-4c16-9cee-585df5a7c58a/public_url)
   - [Data Manipulation Techniques](https://www.credly.com/badges/03491c4e-3ef2-4976-8bac-e87423705654/public_url)
   - [SAS SQL Essentials](https://www.credly.com/badges/ae812d61-0dd3-4314-a329-969edb80f43d/public_url)
   - [SAS Macro Essentials](https://www.credly.com/badges/f94b12e3-5cee-4bff-9570-5e01713c18b0/public_url)
   - [Programming Advanced Techniques](https://www.credly.com/badges/8c20650d-2fd4-4e76-b4d6-1fbc3c67b3a7/public_url)  

<a href="https://www.credly.com/badges/8c20650d-2fd4-4e76-b4d6-1fbc3c67b3a7/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/SAS.png" alt="SAS Programming Advanced Techniques" width="150"/></a>  x5  

- Visualizations:
  - [Microsoft Power BI Desktop for Business Intelligence, Udemy](https://www.udemy.com/certificate/UC-688bb48a-6abf-4610-8145-f2747d9391ce/)
  - [Data Storytelling and Data Visualization, Udemy](https://www.udemy.com/certificate/UC-355c86fe-3a77-4a45-922d-37a53b6c1493/)
  - [Tableau Desktop Specialist](https://www.credly.com/badges/fca2122a-1589-4881-b055-9c20c2f66ad9/public_url)
  
<a href="https://www.credly.com/badges/8ec0ac7c-04a9-4e7a-8f28-66db5dff58f7/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Data Visualization & Dashboard Essentials.png" alt="Data Visualization & Dashboard Essentials" width="150"/>
</a>
<a href="https://www.credly.com/badges/26d9a715-31fe-4c7b-9815-afd4f9cf077f/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Data Visualization with R.png" alt="Data Visualization with R" width="150"/>
</a>
<a href="https://www.credly.com/badges/fca2122a-1589-4881-b055-9c20c2f66ad9/public_url" target="_blank">
 <img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/badges/Tableau%20Desktop%20Specialist.png" alt="Tableau Desktop Specialist" width="150"/>
</a>  


---

## PROJECTS

- Credit Card Statement Scrapping & Analysis

<div align="center">
<img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Credit Card Statement Scrapping & Analysis.png" alt="Credit Card Statement Scrapping & Analysis.png" width="700"/> 
</div>  

- Mutual Portfolio Analysis
<div align="center">
<img src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Mutual Portfolio Analysis.png" alt="Mutual Portfolio Analysis.png" width="700"/> 
</div> 


```
Excel / Power BI adhoc projects
```

<blockquote class="note">
<p><span>📌 Note</span><br>
Below Projects are no longer maintained.</p>
</blockquote>

- **PharmaAssist** Android App  
The objective of developing PharmaAssist was to provide my colleagues easy access to academic books and other relevant study material and also to utilize my programming passion.
<div align="center">
<img src="https://raw.githubusercontent.com/chinmayjk97/PharmaAssist/master/images/Showcase-1.jpeg" alt="PharmaAssist App" width="500"/> 
<img src="https://raw.githubusercontent.com/chinmayjk97/PharmaAssist/master/images/Showcase-2.jpeg" alt="PharmaAssist App" width="500"/> 
</div>  
- Watch the Promo Video:  
<div align="center">
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=5K2faPpquR8" target="_blank">
 <img src="http://img.youtube.com/vi/5K2faPpquR8/maxresdefault.jpg" alt="Watch the video" width="560"/>
</a>
</div> 

- Creator for <a href="https://www.youtube.com/c/PharmaKnowledge"><img width="20" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/youtube.png"
       alt="Pharma Knowledge YouTube Channel"/></a> <b>YouTube Channel</b> - Pharma Knowledge for passion  
   The objective was to deliver the educational content in Audio-Visual format for better understanding. Earlier I had uploaded .ppt files converted to video, but later learnt to develop videos from scratch using Adobe Premiere Pro - The best video according to me is [Understanding Clinical Trials | Drug Discovery | The Journey of Medical Research](https://www.youtube.com/watch?v=0Y2lkSyeQf8).
<br><br>  
<div align="center">  
<a href="https://www.youtube.com/c/PharmaKnowledge"><img width="400" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/PK_Cover.jpg"
       alt="Pharma Knowledge YouTube Channel" /></a>  
</div>  

***

<div align="center">
<h3>🤙 Contact Me </h3> <a href="[https://www.linkedin.com/in/azzar-budiyanto/](https://www.linkedin.com/in/chinmay-kulkarni97/)" target="blank"><img align="center"
         src="https://img.shields.io/badge/linkedin-%231DA1F2.svg?style=for-the-badge&logo=linkedin&logoColor=white"
         alt="Chinmay Kulkarni Linkedin Profile" height="30"/></a>
</div>
