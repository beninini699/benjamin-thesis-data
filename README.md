# Salary Transparency Anchoring Experiment (Austria, Consulting Students) –  Dataset

**Author:** Benjamin Kos  
**Date:** 2025  
**DOI:** 10.5281/zenodo.17014984

## Description
This dataset contains anonymized responses (N = 99) from a within-subject Qualtrics experiment on the effect of salary transparency in Austrian job advertisements.  
Respondents evaluated consulting job postings (constant beyond Company name and minor wording changing) under three experimental conditions:  

- **T1_ND** – No salary disclosure:  “Salary: For this position, an attractive salary is envisaged.”
- **T2_MD** – Minimum salary disclosure: (Collective Bargaining Agreement, CBA)  “Salary: In accordance with the collective bargaining agreement, a minimum gross salary of EUR 3,069.98 per month is envisaged for this position. Willingness to excess payment depending on qualifications and experience.”

- **T3_RD** – Salary range disclosure: “Salary: For this position, a gross salary between EUR 3,000.00 and EUR 3,900.00 per month is envisaged, depending on qualification and experience.”

Dependent variables include salary expectations and asks, as well as perceptions of fairness, reliability, negotiability, attractiveness, confidence, and qualification.  
Demographic controls include gender, age, field of study, GPA, work experience, residence, and attitudes.

All identifiers, free-text fields, GPS, and timing/paradata were removed.  
Dataset is suitable for replication of the analysis reported in Kos (2025) bachelor thesis.

---

## Files
- `anchoring_thesis_public.csv` — Cleaned anonymized dataset  
- `anchoring_thesis_full_codebook.csv` — Full codebook with variable names, labels, codings, and
notes  
- `130725__survey_anchoring_cba_benjamin.docx`- Qualtrics survey as word  
- `README_Zenodo.md` — This document

---

## Variable Coding (Summary)

### Likert Scales
1 = Strongly disagree  
2 = Disagree  
3 = Somewhat disagree  
4 = Neither agree nor disagree  
5 = Somewhat agree  
6 = Agree  
7 = Strongly agree  

### Treatments
- **T1_ND** – No salary disclosure  
- **T2_MD** – Minimum disclosure  
- **T3_RD** – Range disclosure


### Demographic Highlights
- Gender (Male/Female)  
- Age (years)  
- Residence (Austria, Belgium, Czech Republic, France, Germany, Italy, Netherlands, Poland, Slovakia, UAE, UK, USA)  
- Education status (Bachelor current, Bachelor’s, Master current, Master’s, Other)  
- GPA (Austrian scale, inverted for regression)  
- Employment status (Employed, Maternity leave, Job seeking, Study)  
- Career drive & Negotiation skills (Likert 1–7)  

### Dependent Variables
- *“What monthly gross salary do you expect for this position?”* (`Tx_estimate`)  
- *“What monthly gross salary do you ask for in the negotiation?”* (`Tx_ask`)  
- Likert (1–7) scale items:  
  - I feel confident in my estimate (`Tx_confidence`)  
  - The salary seems fair (`Tx_fairness`)  
  - The salary is negotiable (`Tx_negotiability`)  
  - The salary information is reliable (`Tx_reliability`)  
  - This role is attractive (`Tx_attractiveness`)  
  - I am qualified for this role (`Tx_qualified`)

### Demographics
- *How old are you?* (numeric years)  
- *What best describes you?* (Male, Female, Non-binary, Rather not say, Other)  
- *In which country do you currently reside?* (recoded into EU vs. Rest of World for public release)  
- *How long have you been living in Austria?* (numeric years)  
- *Are you enrolled or did you graduate from a university in the past three years?* (Yes/No)  
- *What is your current education status?* (Bachelor current, Bachelor’s degree, Master current, Master’s degree, Other)  
- *What is your field of study?* (Econ/Business vs. Other)  
- *What is your current GPA?* (Austrian 1–5 scale, inverted in data)  
- *How many years of work experience do you have overall?*  
- *How many years of relevant work experience for this position do you have?*  
- *Your current employment status?* (Employed, Maternity leave, Job seeking, Study)  
- Attitudes (Likert 1–7):  
  - I am career driven (`dem_attitude_drive`)  
  - I am confident in my negotiation skills (`dem_attitude_negskills`)  
- *Where do you inform yourself about salaries?* (multiple choice: Family/Partner, Acquaintances, Chamber of Labor, Trade Union, AMS, Collective Agreements, Job Ads, Online Job Portals, Other)  
- Salary info sources (Family, Partner, AMS, Job Ads, Portals, etc.)  

For the full mapping, see `anchoring_thesis_full_codebook.csv`.

---

## Ethics & Anonymization
- No direct identifiers, geolocation, or response metadata included.  
- Free-text responses removed.  

---

## License
Creative Commons: **CC BY 4.0**   

---

## Citation
Kos, B. (2025). *Salary Askk & Estimate throughout transparency condittions, Within suject Anchoring Experiment (Austria, Consulting Students) –  Dataset*. 10.5281/zenodo.17014984
