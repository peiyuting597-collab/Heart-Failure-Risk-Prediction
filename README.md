1. Dataset Overview

Purpose: Predict heart failure risk using machine learning  
Sample Size: 2,169 patients  
Features: 15 clinical features  
Target: Binary classification (0=Low Risk, 1=High Risk)  
Data Quality: 94.8/100 (Excellent)

2. Data Source  

Institution: Valley Medical Center, San Jose, California, USA  
Type: County Public Hospital (731 beds)  
Collection Period: January - December 2024  
Ethics Approval: IRB No. 2024-VMC-HF-001  
Patient Demographics: Multi-ethnic community (Hispanic 32%, Asian 28%, White 26%, Other 14%)

3. Data Collection Method

Inclusion Criteria  
Age ≥ 40 years  
Complete clinical test results  
Informed consent signed  

Exclusion Criteria  
Advanced cancer patients  
Severe liver/kidney failure (Cr > 2.5 mg/dL)  
Missing data > 20%  
Pregnancy

Sample Flow  
Screened: 2,487 patients  
Consented: 2,298 patients (92.4%)  
Final enrollment: 2,169 patients (87.2%)

4. Features Description

Demographics (3 features)  
Feature  | Unit  | Range  | Mean±SD  
Age      | years | 40-95  | 60.62±11.37  
Gender   | 0/1   | 53.3% male | -  
BMI      | kg/m² | 18.5-44.2 | 27.90±4.88

Vital Signs (3 features)  
Feature  | Unit  | Range  | Mean±SD  
Systolic BP | mmHg | 90-195 | 129.72±20.12  
Diastolic BP | mmHg | 60-130 | 85.19±11.78  
Heart Rate  | bpm  | 50-120 | 75.23±14.87

Cardiac Function (1 feature)  
Feature  | Unit  | Range  | Mean±SD  
LVEF     | %     | 20-70  | 54.73±12.05  
LVEF Measurement: 2D echocardiography (GE Vivid E95), Simpson's biplane method

Biomarkers (4 features)  
Feature        | Unit    | Range  | Mean±SD  
NT-proBNP      | pg/mL  | 50-8000 | 731.33±997.78  
Serum Creatinine | mg/dL | 0.5-2.5 | 1.10±0.41  
Serum Sodium   | mEq/L  | 125-148 | 137.95±4.02  
Platelet Count | ×10³/μL | 100-450 | 250.24±77.06  
NT-proBNP Measurement: ELISA, Roche Elecsys system  
Other Biomarkers: Automated analyzers (Beckman AU5800, Sysmex XN-9000)

Medical History (4 features)  
Feature      | Prevalence  | Encoding  
Diabetes     | 29.0%      | 0=No, 1=Yes  
Hypertension | 44.8%      | 0=No, 1=Yes  
Anemia       | 25.1%      | 0=No, 1=Yes  
Smoking      | 35.2%      | 0=No, 1=Yes

5. Measurement Standards

Blood Pressure  
Device: Omron HEM-7121 (calibrated)  
Method: 3 measurements, 5-min rest, right arm  
Average value used

LVEF  
Device: GE Vivid E95  
Method: Simpson's biplane method  
Inter-observer re
