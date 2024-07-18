# Reducing-Hospital-Readmissions
## 2. Executive summary
Our consulting company has been tasked with helping a hospital group improve their understanding of patient readmissions. We have been given access to ten years' worth of data on patients who were readmitted to the hospital after being discharged. Our goal is to assess whether initial diagnoses, the number of procedures, or other variables could provide insight into the probability of readmission, and to identify those patients who are at a higher risk of readmission so that the hospital can focus their follow-up calls and attention accordingly.

To achieve these objectives, we have prepared a report covering the following:

1. Analysis of the most common primary diagnosis by age group.
2. Exploration of the impact of a diabetes diagnosis on readmission rates.
3. Identification of patient groups that the hospital should focus their follow-up efforts on to better monitor patients with a high probability of readmission.

**Results**<br>
The report begins with a brief overview and cleaning of the data, followed by an explanation of the methodologies employed to extract the most valuable insights. The exploratory data analysis has indicated that:

1. **The primary disease diagnosis that is most frequently observed among different age groups is 'Circulatory'**, except for the 40-50 age group, where 'Other' is the most common diagnosis.

2. Investigation of the readmission rates concerning primary, secondary, and tertiary diagnoses reveals that:
	- **Patients diagnosed with diabetes have a higher readmission rate than those diagnosed with other conditions,** 48% for patients with diabetes against 44% for patients diagnosed with 'Other' diseases.
	- The Chi-square statistical test used to assess the dependence of primary diagnosis on readmission rate revealed that **there was a significant statistical association between primary diagnosis of diabetes and hospital readmission rate.**	
3. The hospital should concentrate its follow-up efforts on patient groups with a high likelihood of readmission, including:
	- **patients in the age range of 50 to 90 years old**
	- **patients diagnosed with diabetic, circulatory and respiratory diseases**
	- According to the machine learning models developed during the analysis, **the features that have the most significant impact on the readmission rate include:**
		- **the number of outpatient visits** in the year before a hospital stay
		- **the number of inpatient visits** in the year before a hospital stay
		- **the number of medications administered** during the hospital stay

**Key Recommandations**<br>
1. Further analysis should be conducted on patient groups identified as having a high probability of readmission to determine the specific factors contributing to their readmission rates.
2. The hospital should implement targeted intervention programs for patients in the identified age group and diagnose diabetic, circulatory, and respiratory diseases to reduce their readmission rates.
3. Evaluate the performance of different machine learning models and identify opportunities for model improvement.
4. Analyze the impact of different hospital policies and practices, such as discharge planning and post-discharge follow-up, on readmission rates.

