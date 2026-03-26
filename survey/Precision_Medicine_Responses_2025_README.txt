--------------------
GENERAL INFORMATION 
--------------------
This readme file was generated on 2026-03-03 by Simona Jasaityte.


Title of Dataset: Precision_Medicine_Responses_2025.csv
Description of Dataset: Precision_Medicine_Responses.csv contains responses to a GP2 survey circulated to participating principal investigators (PIs). It includes questions on past and future involvement in clinical trials.
Identifiable information and names of clinical trials have been redacted.
Date of Data Collection: April-May 2025


----------------------------------------
DATA SPECIFIC INFORMATION
----------------------------------------
Date of Creation: 2026-03-03
Description of Data:
- A cleaned version of the automatically recorded GoogleForms survey responses
- Each row represents an individual responder - a principal investigator (PI) of a lab/study, representing a cohort
- Two respondents (PI-01 and PI-41) submitted two responses each to represent two different cohorts they lead and have contributed to GP2. In these cases, their entries were consolidated into a single row, and the corresponding cohort names are listed across GP2_cohort_1, GP2_cohort_2, and GP2_cohort_3 columns. All other respondents, if applicable, listed multiple cohorts they are involved in within a single submission, and their cohort names were split across three columns, in the same way as above.
- NA indicates an empty response / missing information.


Column descriptions:
- ID: Principal Investigator’s anonymised ID
- Name: Redacted name of the PI
- Email: Redacted email address of the PI
- GP2_cohort_1: Free text response to question ”Short name of cohort involved in GP2 (GP2 code if known)” (1st cohort)
- GP2_cohort_2: Free text response to question “Short name of cohort involved in GP2 (GP2 code if known)” (2nd cohort)
- GP2_cohort_3: Free text response to question “Short name of cohort involved in GP2 (GP2 code if known)” (3rd cohort)
- N_cohorts_submitted: Total number of cohorts submitted by the PI in the form
- 1_Trial_capability: Response to the question “1. PD/Movement disorder drug trials capability”
        Single choice:
        “My centre has previously recruited movement disorders patients to a drug trial”
        “My centre has drug trials infrastructure and we would like to be involved in future trials”
        “My centre does not currently have drug trial infrastructure but we would like to develop this”
        “We do not have capacity to be involved in drug trials”
        “I'm unsure”
- 2_Site_involved_in_trials: Response to the question “2. Has your site been or do you plan to be involved in an interventional clinical trial for any Parkinsonian condition between 01/01/2022 and 01/01/2026?”
Single choice:
“Yes”
“No”
“Not sure”
- 3_Site_name: Response to the question “3. What is the name of the University or Hospital (legal entity) where your interventional clinical trials are run?”
Free text (redacted)
- Region: Region where the PI is primarily based (allocated based on response in “3_Site_name”)
        “AFR”: Africa
        “ASIA”: Asia
        “CSAMR”:Central and Southern America
“EUR:” Europe
“MDE”: Middle East
“NAMR”:  North America
“OCEANIA”: Australia, New Zealand, Papua New Guinea and Pacific Islands
- 4_Single_vs_multi_centre: Response to question “4. Is your GP2 cohort a single centre or multi-centre cohort?”
        Single choice:
“Single Centre”
“Multi-Centre”
- 5_Actively_recruiting: Response to question “5. Is your cohort actively recruiting new patients?”
        Single choice:
        “Yes”
        “No”
        “Other:” [free text]
- 6_Names_Trials_Engaged: Response to question “6. Which trials are you / have you been engaged in? Please answer for main study site.  You can select multiple trials and add information on trials not listed”
        Multiple choice:
Redacted list of clinical trials
“NONE / PREFER NOT TO ANSWER”
- 7_Industry_contact_consent: Response to question “7. Would you be happy for GP2 to connect you with pharmaceutical companies regarding potentially trial-eligible patients in your cohort?”
        Single choice:
        “Yes”
        “No”
        “Other:” [free text]
- 8_Biomarkers_collecting: Response to question “8. Which biomarkers is your site currently collecting for some of your patients?”
        Multiple choice:
        “MRI”
“PETscan”
“DATscan”
“Blood for Plasma/Serum”
“CSF”
“Skin biopsy”
“Post-mortem brain donation”
“Smell testing”
“Not sure”
“None”
Other: [free text]
- 8_Biomarkers_collecting_MRI - Response to question 8 split into separate columns
If “MRI” was selected, and “Not sure” was not selected = “Yes”
If “MRI” was selected, and “Not sure” was selected = “Yes”
If “MRI” was not selected and “Not sure” was not selected = “No”
If “MRI” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_PETscan - Response to question 8 split into separate columns
If “PETscan” was selected, and “Not sure” was not selected = “Yes”
If “PETscan” was selected, and “Not sure” was selected = “Yes”
If “PETscan” was not selected and “Not sure” was not selected = “No”
If “PETscan” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_DATscan - Response to question 8 split into separate columns
If “DATscan” was selected, and “Not sure” was not selected = “Yes”
If “DATscan” was selected, and “Not sure” was selected = “Yes”
If “DATscan” was not selected and “Not sure” was not selected = “No”
If “DATscan” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_Blood_Plasma_Serum - Response to question 8 split into separate columns
If “Blood for Plasma/Serum” was selected, and “Not sure” was not selected = “Yes”
If “Blood for Plasma/Serum” was selected, and “Not sure” was selected = “Yes”
If “Blood for Plasma/Serum” was not selected and “Not sure” was not selected = “No”
If “Blood for Plasma/Serum” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_CSF - Response to question 8 split into separate columns
If “CSF” was selected, and “Not sure” was not selected = “Yes”
If “CSF” was selected, and “Not sure” was selected = “Yes”
If “CSF” was not selected and “Not sure” was not selected = “No”
If “CSF” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_Skin_biopsy - Response to question 8 split into separate columns
If “Skin biopsy” was selected, and “Not sure” was not selected = “Yes”
If “Skin biopsy” was selected, and “Not sure” was selected = “Yes”
If “Skin biopsy” was not selected and “Not sure” was not selected = “No”
If “Skin biopsy” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_Brain - Response to question 8 split into separate columns
If “Post-mortem brain donation” was selected, and “Not sure” was not selected = “Yes”
If “Post-mortem brain donation” was selected, and “Not sure” was selected = “Yes”
If “Post-mortem brain donation” was not selected and “Not sure” was not selected = “No”
If “Post-mortem brain donation” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_Smell_testing - Response to question 8 split into separate columns
If “Smell testing” was selected, and “Not sure” was not selected = “Yes”
If “Smell testing” was selected, and “Not sure” was selected = “Yes”
If “Smell testing” was not selected and “Not sure” was not selected = “No”
If “Smell testing” was not selected and “Not sure” was was selected = NA
- 8_Biomarkers_collecting_Not_sure - Response to question 8 split into separate columns
If “Not sure” was selected = “Yes”
If “Not sure” was not selected = “No”
- 8_Biomarkers_collecting_Other - Response to question 8 split into separate columns
If “Other” was selected, and “Not sure” was not selected = “Yes”
If “Other” was selected, and “Not sure” was selected = “Yes”
If “Other” was not selected and “Not sure” was not selected = “No”
If “Other” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible: Response to question” 9. Which biomarkers would you be able to collect for some of your patients in the future with resources?”
Multiple choice:
        “MRI”
“PETscan”
“DATscan”
“Blood for Plasma/Serum”
“CSF”
“Skin biopsy”
“Post-mortem brain donation”
“Smell testing”
“Not sure”
“None”
Other: [free text]
- 9_Biomarkers_possible_MRI - Response to question 9 split into separate columns
If “MRI” was selected, and “Not sure” was not selected = “Yes”
If “MRI” was selected, and “Not sure” was selected = “Yes”
If “MRI” was not selected and “Not sure” was not selected = “No”
If “MRI” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_PETscan - Response to question 9 split into separate columns
If “PETscan” was selected, and “Not sure” was not selected = “Yes”
If “PETscan” was selected, and “Not sure” was selected = “Yes”
If “PETscan” was not selected and “Not sure” was not selected = “No”
If “PETscan” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_DATscan - Response to question 9 split into separate columns
If “DATscan” was selected, and “Not sure” was not selected = “Yes”
If “DATscan” was selected, and “Not sure” was selected = “Yes”
If “DATscan” was not selected and “Not sure” was not selected = “No”
If “DATscan” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_Blood_Plasma_Serum - Response to question 9 split into separate columns
If “Blood for Plasma/Serum” was selected, and “Not sure” was not selected = “Yes”
If “Blood for Plasma/Serum” was selected, and “Not sure” was selected = “Yes”
If “Blood for Plasma/Serum” was not selected and “Not sure” was not selected = “No”
If “Blood for Plasma/Serum” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_CSF - Response to question 9 split into separate columns
If “CSF” was selected, and “Not sure” was not selected = “Yes”
If “CSF” was selected, and “Not sure” was selected = “Yes”
If “CSF” was not selected and “Not sure” was not selected = “No”
If “CSF” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_Skin_biopsy - Response to question 9 split into separate columns
If “Skin biopsy” was selected, and “Not sure” was not selected = “Yes”
If “Skin biopsy” was selected, and “Not sure” was selected = “Yes”
If “Skin biopsy” was not selected and “Not sure” was not selected = “No”
If “Skin biopsy” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_Brain - Response to question 9 split into separate columns
If “Post-mortem brain donation” was selected, and “Not sure” was not selected = “Yes”
If “Post-mortem brain donation” was selected, and “Not sure” was selected = “Yes”
If “Post-mortem brain donation” was not selected and “Not sure” was not selected = “No”
If “Post-mortem brain donation” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_Smell_testing - Response to question 9 split into separate columns
If “Smell testing” was selected, and “Not sure” was not selected = “Yes”
If “Smell testing” was selected, and “Not sure” was selected = “Yes”
If “Smell testing” was not selected and “Not sure” was not selected = “No”
If “Smell testing” was not selected and “Not sure” was was selected = NA
- 9_Biomarkers_possible_Not_sure - Response to question 9 split into separate columns
If “Not sure” was selected = “Yes”
If “Not sure” was not selected = “No”
- 9_Biomarkers_possible_Other - Response to question 9 split into separate columns
If “Other” was selected, and “Not sure” was not selected = “Yes”
If “Other” was selected, and “Not sure” was selected = “Yes”
If “Other” was not selected and “Not sure” was not selected = “No”
If “Other” was not selected and “Not sure” was was selected = NA
- 10_SAA_generated: Response to question” 10. Have you generated synuclein seeding assay data on CSF?
        Single choice:
        “Yes”
        “No”
        “Other:” [free text]


-----------------------
DATA ACCESS AND SHARING
-----------------------
Publications based on this dataset:
Kajsa Atterling Brolin, Lara M. Lange, Emily Navarro-Jones … Huw R Morris, Global Parkinson’s Genetics Program (GP2) Bridging Genetics and Precision Medicine in Parkinson’s Disease through GP2