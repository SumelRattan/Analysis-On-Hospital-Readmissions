![Poster](https://github.com/user-attachments/assets/15e0a02e-cc08-43f5-be70-d07cc8c4b570)
Description of the Dataset

The dataset represents ten years of clinical care at 130 US hospitals and integrated delivery networks. Each row concerns hospital records of patients diagnosed with diabetes, who underwent laboratory, medications, and stayed up to 14 days. The goal is to determine the early readmission of the patient within 30 days of discharge.


Variable Description:

### "age" - Age bracket of the patient (e.g., [50-60), [60-70), etc.)
###  "time_in_hospital" - Number of days the patient stayed in the hospital (ranges from 1 to 14 days)
###  "n_procedures" - Number of procedures performed during the hospital stay
###  "n_lab_procedures" - Number of laboratory procedures performed during the hospital stay
###  "n_medications" - Number of medications administered during the hospital stay
###  "n_outpatient" - Number of outpatient visits in the year before the hospital stay
###  "n_inpatient" - Number of inpatient visits in the year before the hospital stay
###  "n_emergency" - Number of visits to the emergency room in the year before the hospital stay
###  "medical_specialty" - Specialty of the admitting physician (e.g., Cardiology, Internal Medicine)
###  "diag_1" - Primary diagnosis (e.g., Circulatory, Respiratory, Digestive, etc.)
###  "diag_2" - Secondary diagnosis (additional diagnosis besides the primary one)
###  "diag_3" - Additional secondary diagnosis (tertiary diagnosis if applicable)
###  "glucose_test" - Glucose serum level results: high (> 200), normal, or not performed
###  "A1Ctest" - A1C test result: high (> 7%), normal, or not performed
###  "change" - Indicates whether there was a change in diabetes medication ('yes' or 'no')
###  "diabetes_med" - Indicates whether a diabetes medication was prescribed ('yes' or 'no')
###  "readmitted" - Whether the patient was readmitted to the hospital ('yes' or 'no')
