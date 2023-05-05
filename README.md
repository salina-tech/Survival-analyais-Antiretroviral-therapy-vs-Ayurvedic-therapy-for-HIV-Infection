# Antiretroviral-therapy-vs-Ayurvedic-therapy-for-HIV-Infection

HIV infection remains a significant public health concern, and while antiretroviral therapy (ART) has been the standard of care for HIV-positive patients for many years, alternative treatments such as Ayurvedic therapy (AT) are also being used. 

The purpose of this project was to compare the survival rates of patients with HIV infection who received either antiretroviral therapy (ART) or ayurvedic therapy (AT).

The study dataset contains information on the time to death for a total of n patients with HIV infection, including those treated with ART (n_ART) and those treated with AT (n_AT). The key variables of interest are:
•	"Time of event": the time in days from study enrollment to death or censoring
•	"Total no. of patients died in both groups": the total number of patients who died during the study period
•	"No of patients died - ART group": the number of patients who died while receiving ART
•	"No of patients died - AT group": the number of patients who died while receiving AT
•	"Live at start of day": the number of patients alive at the start of each day of the study

Assumptions:
•	Non-informative censoring: This assumption states that the probability of censoring (i.e., a patient being lost to follow-up or withdrawing from the study) is not related to the patient's survival time or the event of interest (i.e., death). 
•	Proportional hazards: This assumption states that the hazard (i.e., the risk of death) for each treatment group is proportional over time.

Analysis: 
- Survival analysis using the Kaplan-Meier estimator and the Nelson-Aalen estimator to compare the survival curves and hazard rates between the ART and AT groups.
- Log-rank test to determine whether the difference in survival between the two groups was statistically significant. The test indicated a significant difference (p < 0.05) in survival between the ART and AT groups, suggesting that ART is more effective in prolonging survival in patients with HIV infection.

Conclusion:
The analysis suggests that ART is more effective than AT in prolonging survival in patients with HIV infection. These findings may have important implications for the treatment of HIV-positive patients and warrant further investigation.
