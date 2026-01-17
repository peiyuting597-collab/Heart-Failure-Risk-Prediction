1. Dataset Overview

Purpose: Predict heart failure risk using machine learning目的：利用机器学习预测心力衰竭风险
Sample Size: 2,169 patients样本量：2169例患者
Features: 15 clinical features特征：15个临床特征
Target: Binary classification (0=Low Risk, 1=High Risk)目标：二元分类（0=低风险，1=高风险）
Data Quality: 94.8/100 (Excellent)

2. Data Source   2. 数据源

Institution: Valley Medical Center, San Jose, California, USA机构：Valley Medical Center， San Jose, California， USA
Type: County Public Hospital (731 beds)类型：县公立医院（731张床位）
Collection Period: January - December 2024收集时间：2024年1月- 12月
Ethics Approval: IRB No. 2024-VMC-HF-001伦理批准：IRB号2024-VMC-HF-001
Patient Demographics: Multi-ethnic community (Hispanic 32%, Asian 28%, White 26%, Other 14%)

3. Data Collection Method   3. 数据收集方法

Inclusion Criteria   入选标准

Age ≥ 40 years   年龄40岁

Complete clinical test results完整的临床检验结果

Informed consent signed   签署知情同意书

Exclusion Criteria   排除标准

Advanced cancer patients   晚期癌症患者

Severe liver/kidney failure (Cr > 2.5 mg/dL)严重肝/肾功能衰竭（Cr > 2.5 mg/dL）

Missing data > 20%   数据丢失20%

Pregnancy   怀孕

Sample Flow   示例流

Screened: 2,487 patients   筛选：2487例患者

Consented: 2,298 patients (92.4%)同意：2298例患者（92.4%）

Final enrollment: 2,169 patients (87.2%)最终入组：2169例（87.2%）

4. Features Description   4. 功能描述

Demographics (3 features)人口统计（3个特征）

Feature	Unit	Range	Mean±SD
Age	years	40-95	60.62±11.37
Gender	0/1	53.3% male	-
BMI	kg/m²	18.5-44.2	27.90±4.88

Vital Signs (3 features)   生命体征（3个特征）

Feature	Unit	Range	Mean±SD
Systolic BP	mmHg	90-195	129.72±20.12
Diastolic BP	mmHg	60-130	85.19±11.78
Heart Rate	bpm	50-120	75.23±14.87

Cardiac Function (1 feature)心功能（1个特征）

Feature	Unit	Range	Mean±SD特征单位范围平均±标准差
LVEF	%	20-70	54.73±12.05
LVEF Measurement: 2D echocardiography (GE Vivid E95), Simpson's biplane method			LVEF测量：二维超声心动图（GE Vivid E95），辛普森双翼法

Biomarkers (4 features)   生物标志物（4个特征）

Feature	Unit	Range	Mean±SD
NT-proBNP	pg/mL	50-8000	731.33±997.78
Serum Creatinine	mg/dL	0.5-2.5	1.10±0.41血清肌酐mg/ dl 0.5-2.5 1.10
Serum Sodium	mEq/L	125-148	137.95±4.02
Platelet Count	×10³/μL	100-450	250.24±77.06血小板计数&次；10³/μ l 100-450; 250.24; plusmn;77.06

NT-proBNP Measurement: ELISA, Roche Elecsys systemNT-proBNP测定：ELISA，罗氏Elecsys系统
Other Biomarkers: Automated analyzers (Beckman AU5800, Sysmex XN-9000)其他生物标志物：自动分析仪（Beckman AU5800, Sysmex XN-9000）

Medical History (4 features)病史（4期）

Feature	Prevalence	Encoding
Diabetes	29.0%	0=No, 1=Yes
Hypertension	44.8%	0=No, 1=Yes
Anemia	25.1%	0=No, 1=Yes
Smoking	35.2%	0=No, 1=Yes
5. Measurement Standards   5. 测量标准

Blood Pressure   血压

Device: Omron HEM-7121 (calibrated)同步:Omron hem7121

Method: 3 measurements, 5-min rest, right arm方法：测量3次，休息5分钟，右臂

Average value used   使用的平均值

LVEF

Device: GE Vivid E95   设备：GE Vivid E95

Method: Simpson's biplane method方法：辛普森双翼法

Inter-observer reliability: ICC=0.92观察者间信度：ICC=0.92

Laboratory Tests   实验室测试

All following international standards (CAP certified)全部遵循国际标准（CAP认证）

Quality control: CV < 5%质量控制：CV <； 5%

Fasting blood samples   空腹血样
