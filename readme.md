# Predicting Counseling Dropout Risk

In counseling, specifically in substance abuse recovery programs, clients often discontinue treatment before completion. These dropouts can hinder recovery outcomes and strain support systems. By using machine learning to predict which clients are more likely to leave early, we can design proactive interventions to improve retention and care quality.

This project builds a predictive pipeline using anonymous client data to identify clients at risk based on demographic, clinical, and psychosocial features. Decsion trees and Neural Networks were used in this project.


---

## Features Used

This project uses structured, interpretable features that are commonly associated with treatment engagement and risk of dropout. The features span demographic, behavioral, and clinical domains:

- **Age** – Client's age at intake
- **Gender** – Male or Female
- **Employed** – Employment status at the time of intake
- **Housing_Status** – Stability of housing (e.g., stable, unstable, homeless)
- **Education_Level** – Highest education level completed
- **Used_Before_Puberty** – Whether substance use began before puberty
- **Polysubstance_Use** – Use of multiple substances concurrently
- **HIV_Status** – Positive or negative HIV diagnosis
- **Chronic_Illness** – Presence of other chronic medical conditions
- **Single_Parent_Household** – Whether raised in a single-parent household
- **Prior_Rehab** – Has previously been in rehabilitation or counseling
- **Race** – Self-identified race or ethnicity
- **Substance_Use_Duration_Years** – Total years of substance use
- **Treatment_Type** – Voluntary or court-mandated participation
- **Arrest_History** – History of arrest or criminal justice involvement
- **Marital_Status** – Relationship status (e.g., single, married, divorced)

To understand how each feature varies across clients who complete vs. those who drop out, we plotted distributions grouped by treatment outcome.

🔍 **Example: Gender Distribution by Completion Status**

![Gender Distribution](images/gender.png)

