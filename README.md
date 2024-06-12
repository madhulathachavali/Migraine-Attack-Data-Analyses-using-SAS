# Migraine-Attack-Data-Analyses-using-SAS

Comprehensive analysis of patient demographics, clinical assessments, laboratory tests, and summaries of patient data.

## 1. Summary of Patient Demographics Data:

## Demographics of Patients

### Table 1. Average Age of Patients by Gender

| Gender | N  | Mean Age |
|--------|----|----------|
| F      | 12 | 31.25    |
| M      | 8  | 38.00    |

## Analysis of Smoking and Alcohol

### Table 2. Analysis of Smoking and Alcohol

|          | Smoking | Alcohol | 
|----------|---------|---------| 
| N        | 16      | 17      | 
| Y        | 4       | 3       | 

## Analysis of Smoking History and Alcohol Consumption

### Table 3. Analysis of Smoking History and Alcohol Consumption

| Label                   | N   | Mean | Std Dev |
|-------------------------|-----|------|---------|
| No. of Cigars smoked    | 30  | 7.87 | 1.74    |
| No. of years smoked     | 30  | 10.60| 3.84    |
| No. of Drinks per week  | 24  | 3.42 | 0.50    |

### Insights:
1. Female patients experiencing migraine attacks tend to have a lower average age than male patients.
2. A considerable portion of migraine patients report both smoking and alcohol consumption, indicating potential lifestyle factors influencing migraine occurrence.
3. Migraine sufferers have smoked an average of 7.87 cigars over a mean duration of 10.60 years, reflecting a notable smoking history among this population.

## 2. Clinical Examination Analysis

### Visit 1
### Analysis of Clinical Examination

#### Table 4. Means of Blood Pressure and Pulse Rate

| Label                      | N  | Mean  | Std Dev |
|----------------------------|----|-------|---------|
| Pulse                      | 20 | 75.40 | 5.32    |
| Systolic Blood Pressure    | 20 | 122.20| 10.68   |
| Diastolic Blood Pressure   | 20 | 75.80 | 7.81    |

#### Table 5. Summary of Other Diseases

| Label                      | N  | Percent |
|----------------------------|----|---------|
| Cardio                     |    |         |
| NAD                        | 18 | 90.00   |
| NS                         | 1  | 5.00    |
| S1S2N                      | 1  | 5.00    |
| Respiratory                |    |         |
| Clear NVBS                 | 1  | 5.00    |
| NAD                        | 19 | 95.00   |
| Abdomen                    |    |         |
| Liver Palpable             | 1  | 5.00    |
| NAD                        | 17 | 85.00   |
| Soft and no mass felt      | 1  | 5.00    |
| Soft and non tada          | 1  | 5.00    |
| Central Nervous System     |    |         |
| Clinically N               | 1  | 5.00    |
| NAD                        | 19 | 95.00   |

*Note: No patients were found with Angina, Myoinfa, Allergy and Cerinc.*

### Insights: 

1. The majority of patients have normal pulse rate, systolic blood pressure (SBP), and diastolic blood pressure (DBP) with the following statistics:
   
   a. Pulse Rate: Mean of 75.40 beats per minute, standard deviation of 5.32.

   b. Systolic Blood Pressure (SBP): Mean of 122.20 mmHg, standard deviation of 10.68.

   c. Diastolic Blood Pressure (DBP): Mean of 75.80 mmHg, standard deviation of 7.81.
2. Most of the patients show no significant abnormalities in their cardiovascular, respiratory, abdominal, and central nervous systems.
  
3. A small percentage of patients exhibit minor issues.

## 3. Lab Testing Data Analysis

## Lab Testing

### Table 6. Analysis of Patient Blood History Data

| Label              | N  | Mean     | Std    |
|--------------------|----|----------|--------|
| SC                 | 20 | 0.72     | 0.11   |
| Hemoglobin         | 19 | 12.34    | 1.21   |
| Urea               | 20 | 17.56    | 11.08  |
| White Blood Cells  | 17 | 10,670.59| 1,382.37|
| Sodium             | 13 | 124.38   | 7.87   |
| Neutrophils        | 20 | 68.85    | 3.66   |
| Eosinophils        | 11 | 4.18     | 7.63   |
| Basophils          | 4  | 0.50     | 0.58   |
| Potassium          | 13 | 4.47     | 0.32   |
| Lymphocytes        | 20 | 27.05    | 7.21   |
| Sugar              | 20 | 111.70   | 26.32  |
| Monocytes          | 17 | 1.94     | 0.75   |
| Platelets          | 20 | 2.22     | 0.56   |
| SB                 | 20 | 0.76     | 0.11   |
| SGOT               | 20 | 26.40    | 17.37  |
| SGPT               | 20 | 27.65    | 22.91  |

### Table 7. Summary of Urine Analysis, Pregnancy, and ECG

| Label                | N  | Percent |
|----------------------|----|---------|
| **Urine Analysis**   |    |         |
| Normal               | 1  | 6.67    |
| NAD                  | 12 | 80.00   |
| Within Normal Limits | 2  | 13.33   |
| **Pregnancy**        |    |         |
| Not Applicable       | 5  | 33.33   |
| Negative             | 10 | 66.67   |
| **ECG**              |    |         |
| Clinically N         | 1  | 6.67    |
| NAD                  | 1  | 6.67    |
| Normal               | 1  | 6.67    |
| Within Normal Limits | 12 | 80.00   |

## Migraine Attack

### Table 8. Averages of Time Since Initial Attack (Month), Frequency, and Duration

| Label                          | N  | Mean   | Std Dev |
|--------------------------------|----|--------|---------|
| Time Since Initial Attack (Months) | 15 | 108.60 | 88.11   |
| Frequency Of Attack In A Month      | 20 | 5.50   | 5.50    |
| Duration Of Attack (Hours)          | 20 | 171.00 | 252.52  |

### Table 9. Analysis of Side Effects Due to Migraine Attack

| Label          | N  | Percent |
|----------------|----|---------|
| **Aura**       |    |         |
| N              | 13 | 65.00   |
| Y              | 7  | 35.00   |
| **Nausea**     |    |         |
| N              | 4  | 20.00   |
| Y              | 16 | 80.00   |
| **Blurred Vision** | |         |
| N              | 14 | 70.00   |
| Y              | 6  | 30.00   |
| **Photophobia** |   |         |
| N              | 10 | 50.00   |
| Y              | 10 | 50.00   |
| **Phonophobia** |   |         |
| N              | 6  | 30.00   |
| Y              | 14 | 70.00   |

### Table 10. Analysis of Patient History based on Drug Intake for Migraine

| Drug Condition | Drug       | Generic         | Dose      | Continued | Dose           | Discontinuation | Duration         |
|----------------|------------|-----------------|-----------|-----------|----------------|-----------------|------------------|
| migraine       | flenarin   |                 | 1T1D      | N         |                | 30 days         | 180 days         |
| migraine       |            |                 | 1BD       | N         |                | 30 days         | 180 days         |
| migraine       | sinarest   |                 | 1 Tab     | N         |                | 7 days          | 60 days          |
| migraine       | sumo       |                 | 1 Tab     | N         |                | 7 days          | 60 days          |
| migraine       | clotan     |                 | 200 mg    | N         |                | 3 days          | 60 days          |
| migraine       | diclofenac |                 | 50 mg bd  | Y         | 100 per day    |                 | 365 days         |
| migraine       | paracetamol|                 | 650 mg    | N         |                | 14 days         | 180 days         |
| migraine       | ibuprofen  |                 | 400 mg    | N         |                | 14 days         | 365 days         |
| migraine       | sibelium   | flunarazine     | 10 mg OD  | N         |                | 7 days          | 30 days          |
| migraine       | indual     | proprawl 40 mg  | 40 mg OD  | N         |                | 7 days          | 30 days          |
| migraine       | proxyron   |                 |           | N         |                |                 | SOS              |
| migraine       | suminat    | sundriptan      | 50 mg OD  | N         |                | 2 days          | 1 day            |
| migraine       |            |                 |           |           |                |                 |                  |
| migraine       | AMT 25     | amytrypliline   | 25 mg     | N         |                | 3 days          | 7 days           |
| migraine       | Dolo       | paracetamol     | 650 mg    | N         |                | 1 day           | SOS              |
| migraine       | proxyron   |                 |           | N         |                |                 |                  |
| migraine       | sibdlium   | flunorozine     |           | N         |                |                 |                  |
| migraine       | brufen     | ibuprofen       | 400       |           |                |                 | SOS              |
| migraine       | vasograin  | ergotamine caffeine paracetamol | 1 Tab  | Y         | 1 tab per attack|                  | 2190 days        |
| migraine       | sibellium  |                 |           | N         |                | 2 days          | 30 days          |
| migraine       | dolopar    |                 |           | N         |                | 7 days          | on and off       |
| migraine       | sumo       | paracetamol and nimesulide |   N         |                | 7 days          | 365 days on & off|
| migraine       | indenal    | proprawl        | 40 mg     | N         |                | 7 days          | 3 days           |
| migraine       | sibellium  | flunorozine     | 10 mg     | N         |                | 7 days          | 3 days           |
| migraine       | duodil     |                 |           | N         |                | 7 days          | 3 days           |
| migraine       |            |                 |           |           |                |                 |                  |
| migraine       | dolo       | paracetamol     | 650 mg    | N         |                | 30 days         | 180 days         |
| migraine       | crocin     | paracetamol     | 500 mg    | N         |                | 15 days         | 90 days          |
| migraine       | flurazine  |                 |           | N         |                | 14 days         | 180 days         |
| migraine       | dolo       | paracetamol     | 650 mg    | N         |                | 14 days         | 180 days         |

### Table 11. Analysis of Patient History based on Drug Intake for other than Migraine

| Drug Condition | Drug          | Generic      | Dose     | Continued | Dose | Discontinuation | Duration  |
|----------------|---------------|--------------|----------|-----------|------|-----------------|-----------|
| others         | neupro        |              | 20 mg BD | N         |      | 180 days        | 7 days    |
| others         | theoasthalin  |              | on and off|          |      |                 | 9125 days |
| others         | asthalin inhaler |           |          |           |      |                 | 3650 days |

### Insights:
1. Diclofenac (50 mg bd) is frequently used for managing migraines, with some patients taking it for up to 365 days.
2. Other commonly used medications include paracetamol (650 mg) and ibuprofen (400 mg), often taken as needed (SOS) or for short durations (7-14 days).
3. The extensive use of various medications underscores the necessity for personalized treatment plans to manage migraine symptoms effectively.
4. For non-migraine conditions, patients often use medications like theoasthalin intermittently over extended periods (up to 9125 days), indicating the chronic management of respiratory conditions.
5. Asthalin inhalers are also used long-term (up to 3650 days), highlighting the need for sustained treatment in certain chronic conditions.

## 4. Summary of Patient Status

### Table 22. Analysis of Functional Capability and Global Evaluation

| Label                      | N  | Percent |
|----------------------------|----|---------|
| **Functional Disability**  |    |         |
| 0                          | 14 | 70.00   |
| 1                          | 2  | 10.00   |
| 2                          | 4  | 20.00   |
| **Patient Global Evaluation** | |         |
| excellent                  | 9  | 45.00   |
| good                       | 5  | 25.00   |
| poor                       | 2  | 10.00   |
| satisfactory               | 4  | 20.00   |
| **Investigation Global Evaluation** | |    |
| effective                  | 4  | 20.00   |
| not effective              | 5  | 25.00   |
| very effective             | 11 | 55.00   |
| **Patient Study Status**   |    |         |
| Y                          | 20 | 100.00  |

### Insights: 

#### Functional Disability:

70% of patients reported no functional disability (score 0), indicating a high level of functionality despite their condition.
10% of patients had a mild functional disability (score 1).
20% of patients experienced moderate functional disability (score 2).

#### Patient Global Evaluation:

45% of patients rated their overall condition as excellent, suggesting effective management or mild severity of their symptoms.
25% of patients rated their condition as good, indicating satisfactory control over their symptoms.
20% of patients rated their condition as satisfactory, while 10% rated it as poor, highlighting that a minority of patients still struggle with significant issues.

#### Investigation Global Evaluation:

55% of patients found their treatment to be very effective, showing a majority benefit significantly from their current treatment plans.
20% of patients rated their treatment as effective.
25% of patients found their treatment not effective, indicating a need for alternative approaches or further investigation.
Patient Study Status:

All patients (100%) were fully compliant and involved in the study (status Y), ensuring the reliability and completeness of the data collected.

*******************************************************;













 
