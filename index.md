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
  
<img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Qliksense.jpg" alt="Qlik Sense">  <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Power-BI.png" alt="Power BI">  <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/Tableau-Logo.png" alt="Tableau">  <img width="100" src="https://raw.githubusercontent.com/chinmayjk97/digital-cv/main/resources/excel.jfif" alt="Excel">

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

> [!TIP]  
> Of these Java and Kotlin were for hobby projects.

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

### Novo Nordisk

**Functional Programmer** (Apr 2024 – Present)  


### Xogene Solutions Pvt. Ltd., Pune

**Clinical Trial Transparency Analyst** (July 2021 – Nov 2022)


---

## CERTIFICATIONS & BADGES

```
Credly badges showcase
```
<!--

- [SAS® Base and Advanced – SAS Institute](https://www.credly.com/badges/8c20650d-2fd4-4e76-b4d6-1fbc3c67b3a7) [Credly Profile](https://www.credly.com/badges/8c20650d-2fd4-4e76-b4d6-1fbc3c67b3a7)
- [IBM Data Analytics with Excel and R Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/C5JQWE8W528S)
- [SQL for Data Science with R by IBM](https://www.coursera.org/account/accomplishments/certificate/VFRATFGSSAVZ)
- [Introduction to R Programming for Data Science by IBM](https://www.coursera.org/account/accomplishments/certificate/XMR6SKTR5RUB)
- [Introduction to Data Analytics by IBM](https://coursera.org/share/ebb8f0ed2b8eb4e3cfdc4c46af9d9ba0)
- [Excel Basics for Data Analysis by IBM](https://coursera.org/share/7d929965e12260e14976a59f3329223a)
- [Microsoft Power BI Desktop for Business Intelligence, Udemy](https://www.udemy.com/certificate/UC-688bb48a-6abf-4610-8145-f2747d9391ce/)
- [Python A-Z™: Python for Data Science, Udemy](https://www.udemy.com/certificate/UC-7dbc21ae-1d63-46a7-b83f-84e8bc1bf8e8/)
- [SQL- The Complete Introduction to SQL programming, Udemy](https://www.udemy.com/certificate/UC-398109d9-ea7c-4538-bbac-eb4f7ce6c7de/)
- [Data Storytelling and Data Visualization, Udemy](https://www.udemy.com/certificate/UC-355c86fe-3a77-4a45-922d-37a53b6c1493/)

-->
---

## PROJECTS
```
Excel / Power BI adhoc projects
CC scraping
MF Analysis
```

> [!NOTE]
> Below Projects are no longer maintained.

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
       alt="Pharma Knowledge YouTube Channel"/></a> YouTube Channel - Pharma Knowledge for passion  
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
