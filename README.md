Heart Failure Risk Prediction Dataset心力衰竭风险预测数据集
About this Dataset   关于本数据集
This dataset contains clinical data from 2,169 patients collected at Valley Medical Center (San Jose, California) during 2024. It is designed for developing machine learning models to predict heart failure risk based on 15 clinical features.该数据集包含2024年在Valley Medical Center （San Jose, California）收集的2169名患者的临床数据。它旨在开发机器学习模型，根据15个临床特征预测心力衰竭风险。
Dataset Highlights   数据集亮点

✅ High Quality: 94.8/100 quality score, 0% missing data✅高质量：94.8/100质量分数，0%缺失数据
✅ Real Clinical Data: Collected from a county public hospital serving diverse community✅真实临床数据：来自服务于不同社区的县级公立医院
✅ Well-Documented: Detailed measurement methods and quality control procedures✅文件完备：详细的测量方法和质量控制程序
✅ Balanced Classes: 65% low risk, 35% high risk✅均衡类别：65%低风险，35%高风险
✅ Validated: Random Forest accuracy 81.34%, ROC-AUC 0.87✅验证：随机森林准确率81.34%,ROC-AUC 0.87


Quick Facts   快速的事实
Attribute   属性Value   价值Samples   样品2,169 patients   2169名患者Features   特性15 clinical features   15临床特点Target   目标Binary (0=Low Risk, 1=High Risk)二元（0=低风险，1=高风险）Data Source   数据源Valley Medical Center, CA加州山谷医疗中心Collection Period   收集期间Jan-Dec 2024Missing Data   缺失的数据0%Format   格式CSV, UTF-8   CSV, utf - 8Size   大小140 KB

Features Overview   功能概述
📊 Demographics (3)   📊人口统计(3)

Age: 40-95 years   年龄：40-95岁
Gender: Female/Male   性别:女性/男性
BMI: 18.5-44.2 kg/m²   BMI: 18.5-44.2 kg/m²；

💓 Vital Signs (3)   💓生命体征(3)

Systolic BP: 90-195.5 mmHg收缩压：90-195.5 mmHg
Diastolic BP: 60-130 mmHg舒张压：60-130 mmHg
Heart Rate: 50-120 bpm   心率：每分钟50-120次

🫀 Cardiac Function (1)   🫀心功能(1)

LVEF (Left Ventricular Ejection Fraction): 20-70% ⭐ Most Important Feature (31.5%)LVEF（左心室射血分数）：20-70%⭐

🧪 Biomarkers (4)   🧪生物标志物(4)

NT-proBNP: 50-8000 pg/mL ⭐ Second Most Important (10.3%)NT-proBNP: 50-8000 pg/mL⭐第二重要（10.3%）
Serum Creatinine: 0.5-2.5 mg/dL血清肌酐：0.5-2.5 mg/dL
Serum Sodium: 125-148 mEq/L血清钠：125-148 mEq/L
Platelet Count: 100-450 ×10³/μL血小板计数：100-450倍/ μ L

📋 Medical History (4)   📋病史(4)

Diabetes: Yes/No (29% prevalence)糖尿病：是/否（患病率29%）
Hypertension: Yes/No (45% prevalence)高血压：是/否（45%患病率）
Anemia: Yes/No (25% prevalence)贫血：是/否（25%患病率）
Smoking: Yes/No (35% prevalence)吸烟：是/否（患病率35%）


What Makes This Dataset Special?这个数据集的特别之处是什么？
🏥 Real-World Clinical Data🏥真实世界临床数据

Collected from actual hospital patients, not simulated收集自真实的医院病人，而非模拟
Diverse patient population reflecting real community demographics多样化的患者群体反映了真实的社区人口统计
Standard clinical practice measurements and protocols标准临床实践测量和方案

📈 Excellent for ML   📈非常适合ML

Perfect for Binary Classification: Balanced target variable完美的二元分类：平衡的目标变量
Feature Importance: Clear ranking from Random Forest analysis特征重要性：从随机森林分析中明确排名
Ready for SHAP Analysis: Interpretable features with clinical meaning准备进行SHAP分析：具有临床意义的可解释特征
Multiple Algorithm Support: Works well with XGBoost, LightGBM, Random Forest, Neural Networks多种算法支持：与XGBoost， LightGBM，随机森林，神经网络工作良好

🔬 Scientific Rigor   🔬科学严谨性

IRB Approved: Ethics approval (2024-VMC-HF-001)IRB批准：伦理批准（2024-VMC-HF-001）
Quality Controlled: Dual independent data entry, 100% consistency check质量控制：双重独立数据录入，100%一致性检查
Standardized Measurements: International guideline-compliant protocols标准化测量：符合国际准则的协议
Validated Reliability: Inter-rater ICC > 0.85经验证的信度：interrater ICC >； 0.85


Potential Use Cases   潜在用例
🤖 Machine Learning   🤖机器学习

Binary classification model development二元分类模型开发
Ensemble learning experiments集成学习实验
Feature selection studies特征选择研究
Hyperparameter optimization benchmarks超参数优化基准

🧠 Explainable AI   🧠可解释的AI

SHAP value analysis   shape值分析
LIME interpretability   石灰可解释性
Feature importance ranking特征重要性排序
Clinical decision rule extraction临床决策规则提取

🎓 Educational   🎓教育

Healthcare ML tutorials   医疗保健ML教程
Medical data science courses医学数据科学课程
Kaggle competition practiceKaggle比赛练习
Student projects   学生项目

🏥 Clinical Research   🏥临床研究

Risk stratification models风险分层模型
Early warning systems   早期预警系统
Comparative algorithm studies比较算法研究
Biomarker validation   生物标志物的验证
