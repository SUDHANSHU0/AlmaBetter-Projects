<div align='left'>
    <a href='https://www.almabetter.com/'>
        <img height='30px' src='images/almabetter_logo.jpeg'>
</div>
<div align='left'>
    <a href='https://www.almabetter.com/'>
        AlmaBetter
    </a><br>
    <p>Machine Learning Project</p>
</div>

<br><br>
<div align="center">
  <img src="images/heart.jpg" alt="" width="300" height="200">  
</div><br>
<!-- Title -->
<p align="center">
    <div style="
    color: #00FFFF;
    test-align:center;
    font-size: 35px;
    font-weight: 500;
    width: 600px;
    overflow: hidden;
    white-space: nowrap;
    border-right: 3px solid #00FFFF;
    box-sizing: border-box;
    animation: typing 5.5s steps(40, end), blink 0.9s step-end infinite;
    ">
    Heart Disease Prediction Project
    </div>
    <style>
    @keyframes typing {
        from {
        width: 0;
        }
        to {
        width: 100%;
        }
    }
    @keyframes blink {
        50% {
        border-color: transparent;
        }
    }
    </style>
</p>

Heart disease is one of the leading causes of mortality worldwide. Early prediction of heart disease can save lives by enabling timely medical intervention. This project demonstrates the use of machine learning to analyze patient data and predict the likelihood of heart disease.

---

<!-- Table of content -->
## Table of Contant

* About this Project.
* Key Concepts.
* Project steps.
* What Data set cointains?
* Main library to be used.
* Business Objective.
* Insights from data.
* Conclusion.
* License.
* Acknowledgment.

<br>

---

## Key Concepts

- **Machine Learning Approach:**
  - Supervised Learning (Classification)
  - Predictive modeling with patient data

- **Data Insights:**
  - Feature engineering for healthcare datasets
  - Data visualization to understand key factors

- **Model Evaluation:**
  - Evaluation metrics to measure model accuracy
  - Comparison of different classification algorithms

## Project Steps

1. **Data Preparation:**
   - Cleaning and preprocessing the dataset
   - Handling missing values and scaling features

2. **Exploratory Data Analysis (EDA):**
   - Visualizing trends and correlations

3. **Model Development:**
   - Implementing classification models
   - Fine-tuning hyperparameters for optimization

4. **Evaluation and Deployment:**
   - Testing model performance on unseen data
   - Providing actionable insights

<!-- Table of content -->
---

<details>
    <summary style="font-size: 20px; text-align: center;">
    What Data Set Contains?
</summary>
<br>
    <p style="font-size:13px; test-align: left;">
    1. age: Age of the patient (Numeric).<br>
    2. sex: Gender of the patient. Values: 1 = male, 0 = female.<br>
    3. cp: Chest pain type. Values: 0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal pain, 3 = Asymptomatic, 4 = Psychogenic Chest Pain.<br>
    4. trestbps: Resting Blood Pressure (in mm Hg) (Numeric).<br>
    5. chol: Serum Cholesterol level (in mg/dl) (Numeric).<br>
    6. fbs: Fasting blood sugar > 120 mg/dl. Values: 1 = true, 0 = false.<br>
    7. restecg: Resting electrocardiographic results. Values: 0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy.<br>
    8. thalach: Maximum heart rate achieved (Numeric).<br>
    9. exang: Exercise-induced angina. Values: 1 = yes, 0 = no.<br>
    10. oldpeak: ST depression induced by exercise relative to rest (Numeric).<br>
    11. slope: Slope of the peak exercise ST segment. Values: 0 = Upsloping, 1 = Flat, 2 = Downsloping.<br>
    12. ca: Number of major vessels (0-3) colored by fluoroscopy. Values: 0, 1, 2, 3.<br>
    13. thal: Thalassemia types. Values: 1 = Normal, 2 = Fixed defect, 3 = Reversible defect.<br>
    14. target: Outcome variable (heart attack risk). Values: 1 = more chance of heart attack, 0 = less chance of heart attack.<br>
    </p>
</details>

---

<details>
<summary style="font-size: 20px; text-align:center;">
    Main Library to be used
</summary>
    <br>
    <p style="font-size:13px;">
        NumPy for computationally efficient operations.<br>
        Pandas for data manipulation, aggregation.<br>
        Matplotlib and Seaborn for visualisation and behaviour with respect to the target variable.<br>
        sklearn for builing and traning model for ML.
    </p>
</details>

---

<details>
<summary style="font-size:20px; text-align:center">
    What do you suggest the client to achieve Business Objective ?
</summary>
    <br>
<p style="font-size:14px">
1. Leverage Predictive Insights for Preventative Healthcare<br>
Goal: Use the predictive model to identify high-risk individuals for early intervention.<br>
Actions:<br>
Partner with healthcare providers to integrate the model into routine check-ups.
Develop an alert system for doctors and patients based on predictions.
Offer personalized health improvement plans using insights from the model.<br><br>
2. Create a Scalable and User-Friendly Solution<br>
Goal: Make the prediction tool accessible to a broader audience.<br>
Actions:<br>
Develop a mobile application or web platform with user-friendly interfaces for patients and practitioners.
Incorporate multilingual support to expand the tool’s reach.<br><br>
3. Expand Services with Data-Driven Decision Making<br>
Goal: Use patient data to enhance healthcare strategies and services.<br>
Actions:<br>
Analyze aggregated data to identify patterns and trends in heart disease risk factors.
Provide healthcare providers with actionable reports to optimize their resource allocation.<br><br>
4. Focus on Continuous Model Improvement<br>
Goal: Enhance the model's accuracy and relevance.<br>
Actions:<br>
Continuously update the dataset to reflect the latest medical insights and demographics.
Incorporate advanced machine learning techniques like ensemble methods or deep learning.
Include additional features like genetic data, lifestyle metrics, or regional factors.<br><br>
5. Promote Awareness and Adoption<br>
Goal: Increase awareness and engagement with the solution.<br>
Actions:<br>
Conduct public health campaigns to educate people on the importance of heart disease prediction.
Collaborate with insurance companies to offer premium discounts for users participating in predictive programs.<br><br>
6. Explore Revenue Models<br>
Goal: Monetize the solution sustainably.<br>
Actions:<br>
Offer subscription plans for healthcare providers and organizations to use the tool.
Partner with research institutions for sponsored studies leveraging your predictive capabilities.
Provide data insights as a service to pharmaceutical and healthcare companies.<br><br>

</p>
</details>

---

<details>
    <summary style="font-size: 20px; text-align:center;">
        Insights from Dataset
    </summary>
    <br>
    <div style="display: flex; align-items: center; justify-content: center; gap: 20px;">
        <!-- Image -->
        <img src="images/Types of chest pain.png" alt="" width="400" height="300">
        <div>
            <p>0 = Typical angina</p>
            <p>1 = Atypical angina</p>
            <p>2 = Non-anginal pain</p>
            <p>3 = Asymptomatic</p>
            <p>4 = Psychogenic Chest Pain</p>
        </div>
    </div><br>

---
<p style="font-size:15px; text-align:center">Chances of Heart Attack in patient</p>
<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">
    <img src="images/chances of heart attack.png" alt="chances of heart attack" width="400" height="300">
    <div>
        <p>0 = Less chances of Heart attack</p>
        <p>1 = More chances of Heart attack</p>
    </div>
</div>

---
<p style="font-size:15px; text-align:center">Correlation and feature affacting heart attack</p>
<div align="center">
  <img src="images/Feature_importance.png" alt="feature affecting heart attack" width="500" height="400">  <img src='images/corr_heatmap.png' alt='correlation heatmap' width='500' height='400'>
</div>
<br>
</details>


---

## Conclusion

The Heart Disease Prediction Project highlights the importance of leveraging data-driven approaches to enhance healthcare decision-making. Through machine learning, this project provides a framework for analyzing patient data and predicting health risks effectively. By contributing to this project, you can gain valuable insights into both data science and its impactful applications in healthcare.

---

<!-- License -->
## License
Distributed Under **MIT License**. See `LICENSE.txt` for more information.

---

### Acknowledgments

This project is dedicated to enhancing healthcare outcomes through innovative technologies and collaborative efforts.

<p align="right" > Created with 🧠 by <a href="https://github.com/KushangShah">Kushang Shah</a></p>
<p align="right"> <img src="https://komarev.com/ghpvc/?username=kushang&label=Profile%20views&color=0e75b6&style=flat" alt="kushang" /> </p>