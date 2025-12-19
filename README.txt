######README######

analysis_data_ELM - original data file taken from Ivimey-Cook and Sultanova et al (2025)
Means_dat - Processed data with lnVR and lnCVR
Analysis - code for all data processing and statistical analyses 

Analysis_data_ELM column names (from Ivimey-Cook and Sultanova et al (2025)): 
id = 1:911 unique individual ID
Author list: list of authors
title: title of paper
Year: year paper was published (extracted from Scopus/WoS)
m_control: control lifespan measure
n_control: sample size for control
sd_control: standard deviation for control (left blank if not available)
se_control: standard error for control (left blank if not available)
m_treatment: treatment lifespan measure
n_ treatment: sample size for treatment
sd_ treatment: standard deviation for treatment (left blank if not available)
se_ treatment: standard error for treatment (left blank if not available)
m_Measure: median or mean lifespan
m_raw: Whether raw data was given to calculate measures.
m_time: unit of lifespan measure
m_Location: Location of lifespan measure in the paper.
Species: species sampled
Treatment_Type: Type of treatment used (e.g. fasting, percent reduction, rapamycin..)
Treatment_Overall: Broad treatment groups (Rapamycin, Metformin, DR).
Treatment_Name: Treatment name in paper
Sex: Sex studied
Strain: The name of any strain used if appropriate.
Other Variables: Whether any other variables tested in the experiment.
Notes: Additional notes
mice900_keep: whether or not the mice paper passed the 900 day rule.

Additional columns in Means_dat are generated in Analysis.rmd under the "Effect size calculation"
