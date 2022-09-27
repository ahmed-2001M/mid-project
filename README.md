# mid-project


* ### [Data](https://www.kaggle.com/datasets/mdsharibzeya/patient-survival-prediction-model?select=Data+Dictionary.csv)
  Description: Getting a rapid understanding of the context of a patient’s overall health has been particularly important during the COVID-19 pandemic as healthcare workers   around the world struggle with hospitals overloaded by patients in critical condition. Intensive Care Units (ICUs) often lack verified medical histories for incoming       patients. A patient in distress or a patient who is brought in confused or unresponsive may not be able to provide information about chronic conditions such as heart       disease, injuries, or diabetes. Medical records may take days to transfer, especially for a patient from another medical provider or system. Knowledge about chronic         conditions can inform clinical decisions about patient care and ultimately improve patient's survival outcomes. 
  
  data have 91713 row and 186 feature
  
  
  
* ### challenges
  * data have nulls
  * data have outliers
  * generate features from old features
  * filter features and take the most importanat features
  * unbalanced data

* ### features
|Indicator|Description|
|---------|-----------|
encounter_id | Unique identifier associated with a patient unit stay
hospital_id | Unique identifier associated with a hospital
patient_id | Unique identifier associated with a patient
hospital_death | Whether the patient died during this hospitalization
age | The age of the patient on unit admission
bmi | The body mass index of the person on unit admission
elective_surgery | Whether the patient was admitted to the hospital for an elective surgical operation
ethnicity | The common national or cultural tradition which the person belongs to
gender | The genotypical sex of the patient
height | The height of the person on unit admission
hospital_admit_source | The location of the patient prior to being admitted to the hospital
icu_admit_source | The location of the patient prior to being admitted to the unit
icu_admit_type | The type of unit admission for the patient
icu_id | A unique identifier for the unit to which the patient was admitted
icu_type | A classification which indicates the type of care the unit is capable of providing
pre_icu_los_days | The length of stay of the patient between hospital admission and unit admission
readmission_status | Whether the current unit stay is the second (or greater) stay at an ICU within the same hospitalization
weight | The weight (body mass) of the person on unit admission
albumin_apache | The albumin concentration measured during the first 24 hours which results in the highest APACHE III score
apache_2_diagnosis | The APACHE II diagnosis for the ICU admission
apache_3j_diagnosis | The APACHE III-J sub-diagnosis code which best describes the reason for the ICU admission
apache_post_operative | The APACHE operative status; 1 for post-operative, 0 for non-operative
arf_apache | Whether the patient had acute renal failure during the first 24 hours of their unit stay, defined as a 24 hour urine output <410ml, creatinine >=133 micromol/L and no chronic dialysis
bilirubin_apache | The bilirubin concentration measured during the first 24 hours which results in the highest APACHE III score
bun_apache | The blood urea nitrogen concentration measured during the first 24 hours which results in the highest APACHE III score
creatinine_apache | The creatinine concentration measured during the first 24 hours which results in the highest APACHE III score
fio2_apache | The fraction of inspired oxygen from the arterial blood gas taken during the first 24 hours of unit admission which produces the highest APACHE III score for oxygenation
gcs_eyes_apache | The eye opening component of the Glasgow Coma Scale measured during the first 24 hours which results in the highest APACHE III score
gcs_motor_apache | The motor component of the Glasgow Coma Scale measured during the first 24 hours which results in the highest APACHE III score
gcs_unable_apache | Whether the Glasgow Coma Scale was unable to be assessed due to patient sedation
gcs_verbal_apache | The verbal component of the Glasgow Coma Scale measured during the first 24 hours which results in the highest APACHE III score
glucose_apache | The glucose concentration measured during the first 24 hours which results in the highest APACHE III score
heart_rate_apache | The heart rate measured during the first 24 hours which results in the highest APACHE III score
hematocrit_apache | The hematocrit measured during the first 24 hours which results in the highest APACHE III score
intubated_apache | Whether the patient was intubated at the time of the highest scoring arterial blood gas used in the oxygenation score
map_apache | The mean arterial pressure measured during the first 24 hours which results in the highest APACHE III score
paco2_apache | The partial pressure of carbon dioxide from the arterial blood gas taken during the first 24 hours of unit admission which produces the highest APACHE III score for oxygenation
paco2_for_ph_apache | The partial pressure of carbon dioxide from the arterial blood gas taken during the first 24 hours of unit admission which produces the highest APACHE III score for acid-base disturbance
pao2_apache | The partial pressure of oxygen from the arterial blood gas taken during the first 24 hours of unit admission which produces the highest APACHE III score for oxygenation
ph_apache | The pH from the arterial blood gas taken during the first 24 hours of unit admission which produces the highest APACHE III score for acid-base disturbance
resprate_apache | The respiratory rate measured during the first 24 hours which results in the highest APACHE III score
sodium_apache | The sodium concentration measured during the first 24 hours which results in the highest APACHE III score
temp_apache | The temperature measured during the first 24 hours which results in the highest APACHE III score
urineoutput_apache | The total urine output for the first 24 hours
ventilated_apache | Whether the patient was invasively ventilated at the time of the highest scoring arterial blood gas using the oxygenation scoring algorithm, including any mode of positive pressure ventilation delivered through a circuit attached to an endo-tracheal tube or tracheostomy
wbc_apache | The white blood cell count measured during the first 24 hours which results in the highest APACHE III score
d1_diasbp_invasive_max | The patient's highest diastolic blood pressure during the first 24 hours of their unit stay, invasively measured
d1_diasbp_invasive_min | The patient's lowest diastolic blood pressure during the first 24 hours of their unit stay, invasively measured
d1_diasbp_max | The patient's highest diastolic blood pressure during the first 24 hours of their unit stay, either non-invasively or invasively measured
d1_diasbp_min | The patient's lowest diastolic blood pressure during the first 24 hours of their unit stay, either non-invasively or invasively measured
d1_diasbp_noninvasive_max | The patient's highest diastolic blood pressure during the first 24 hours of their unit stay, non-invasively measured
d1_diasbp_noninvasive_min | The patient's lowest diastolic blood pressure during the first 24 hours of their unit stay, non-invasively measured
d1_heartrate_max | The patient's highest heart rate during the first 24 hours of their unit stay
d1_heartrate_min | The patient's lowest heart rate during the first 24 hours of their unit stay
d1_mbp_invasive_max | The patient's highest mean blood pressure during the first 24 hours of their unit stay, invasively measured
d1_mbp_invasive_min | The patient's lowest mean blood pressure during the first 24 hours of their unit stay, invasively measured
d1_mbp_max | The patient's highest mean blood pressure during the first 24 hours of their unit stay, either non-invasively or invasively measured
d1_mbp_min | The patient's lowest mean blood pressure during the first 24 hours of their unit stay, either non-invasively or invasively measured
d1_mbp_noninvasive_max | The patient's highest mean blood pressure during the first 24 hours of their unit stay, non-invasively measured
d1_mbp_noninvasive_min | The patient's lowest mean blood pressure during the first 24 hours of their unit stay, non-invasively measured
d1_resprate_max | The patient's highest respiratory rate during the first 24 hours of their unit stay
d1_resprate_min | The patient's lowest respiratory rate during the first 24 hours of their unit stay
d1_spo2_max | The patient's highest peripheral oxygen saturation during the first 24 hours of their unit stay
d1_spo2_min | The patient's lowest peripheral oxygen saturation during the first 24 hours of their unit stay
d1_sysbp_invasive_max | The patient's highest systolic blood pressure during the first 24 hours of their unit stay, invasively measured
d1_sysbp_invasive_min | The patient's lowest systolic blood pressure during the first 24 hours of their unit stay, invasively measured
d1_sysbp_max | The patient's highest systolic blood pressure during the first 24 hours of their unit stay, either non-invasively or invasively measured
d1_sysbp_min | The patient's lowest systolic blood pressure during the first 24 hours of their unit stay, either non-invasively or invasively measured
d1_sysbp_noninvasive_max | The patient's highest systolic blood pressure during the first 24 hours of their unit stay, non-invasively measured
d1_sysbp_noninvasive_min | The patient's lowest systolic blood pressure during the first 24 hours of their unit stay, non-invasively measured
d1_temp_max | The patient's highest core temperature during the first 24 hours of their unit stay, invasively measured
d1_temp_min | The patient's lowest core temperature during the first 24 hours of their unit stay
h1_diasbp_invasive_max | The patient's highest diastolic blood pressure during the first hour of their unit stay, invasively measured
h1_diasbp_invasive_min | The patient's lowest diastolic blood pressure during the first hour of their unit stay, invasively measured
h1_diasbp_max | The patient's highest diastolic blood pressure during the first hour of their unit stay, either non-invasively or invasively measured
h1_diasbp_min | The patient's lowest diastolic blood pressure during the first hour of their unit stay, either non-invasively or invasively measured
h1_diasbp_noninvasive_max | The patient's highest diastolic blood pressure during the first hour of their unit stay, non-invasively measured
h1_diasbp_noninvasive_min | The patient's lowest diastolic blood pressure during the first hour of their unit stay, non-invasively measured
h1_heartrate_max | The patient's highest heart rate during the first hour of their unit stay
h1_heartrate_min | The patient's lowest heart rate during the first hour of their unit stay
h1_mbp_invasive_max | The patient's highest mean blood pressure during the first hour of their unit stay, invasively measured
h1_mbp_invasive_min | The patient's lowest mean blood pressure during the first hour of their unit stay, invasively measured
h1_mbp_max | The patient's highest mean blood pressure during the first hour of their unit stay, either non-invasively or invasively measured
h1_mbp_min | The patient's lowest mean blood pressure during the first hour of their unit stay, either non-invasively or invasively measured
h1_mbp_noninvasive_max | The patient's highest mean blood pressure during the first hour of their unit stay, non-invasively measured
h1_mbp_noninvasive_min | The patient's lowest mean blood pressure during the first hour of their unit stay, non-invasively measured
h1_resprate_max | The patient's highest respiratory rate during the first hour of their unit stay
h1_resprate_min | The patient's lowest respiratory rate during the first hour of their unit stay
h1_spo2_max | The patient's highest peripheral oxygen saturation during the first hour of their unit stay
h1_spo2_min | The patient's lowest peripheral oxygen saturation during the first hour of their unit stay
h1_sysbp_invasive_max | The patient's highest systolic blood pressure during the first hour of their unit stay, invasively measured
h1_sysbp_invasive_min | The patient's lowest systolic blood pressure during the first hour of their unit stay, invasively measured
h1_sysbp_max | The patient's highest systolic blood pressure during the first hour of their unit stay, either non-invasively or invasively measured
h1_sysbp_min | The patient's lowest systolic blood pressure during the first hour of their unit stay, either non-invasively or invasively measured
h1_sysbp_noninvasive_max | The patient's highest systolic blood pressure during the first hour of their unit stay, non-invasively measured
h1_sysbp_noninvasive_min | The patient's lowest systolic blood pressure during the first hour of their unit stay, non-invasively measured
h1_temp_max | The patient's highest core temperature during the first hour of their unit stay, invasively measured
h1_temp_min | The patient's lowest core temperature during the first hour of their unit stay
d1_albumin_max | The lowest albumin concentration of the patient in their serum during the first 24 hours of their unit stay
d1_albumin_min | The lowest albumin concentration of the patient in their serum during the first 24 hours of their unit stay
d1_bilirubin_max | The highest bilirubin concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_bilirubin_min | The lowest bilirubin concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_bun_max | The highest blood urea nitrogen concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_bun_min | The lowest blood urea nitrogen concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_calcium_max | The highest calcium concentration of the patient in their serum during the first 24 hours of their unit stay
d1_calcium_min | The lowest calcium concentration of the patient in their serum during the first 24 hours of their unit stay
d1_creatinine_max | The highest creatinine concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_creatinine_min | The lowest creatinine concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_glucose_max | The highest glucose concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_glucose_min | The lowest glucose concentration of the patient in their serum or plasma during the first 24 hours of their unit stay
d1_hco3_max | The highest bicarbonate concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_hco3_min | The lowest bicarbonate concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_hemaglobin_max | The highest hemoglobin concentration for the patient during the first 24 hours of their unit stay
d1_hemaglobin_min | The lowest hemoglobin concentration for the patient during the first 24 hours of their unit stay
d1_hematocrit_max | The highest volume proportion of red blood cells in a patient's blood during the first 24 hours of their unit stay, expressed as a fraction
d1_hematocrit_min | The lowest volume proportion of red blood cells in a patient's blood during the first 24 hours of their unit stay, expressed as a fraction
d1_inr_max | The highest international normalized ratio for the patient during the first 24 hours of their unit stay
d1_inr_min | The lowest international normalized ratio for the patient during the first 24 hours of their unit stay
d1_lactate_max | The highest lactate concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_lactate_min | The lowest lactate concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_platelets_max | The highest platelet count for the patient during the first 24 hours of their unit stay
d1_platelets_min | The lowest platelet count for the patient during the first 24 hours of their unit stay
d1_potassium_max | The highest potassium concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_potassium_min | The lowest potassium concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_sodium_max | The highest sodium concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_sodium_min | The lowest sodium concentration for the patient in their serum or plasma during the first 24 hours of their unit stay
d1_wbc_max | The highest white blood cell count for the patient during the first 24 hours of their unit stay
d1_wbc_min | The lowest white blood cell count for the patient during the first 24 hours of their unit stay
h1_albumin_max | The lowest albumin concentration of the patient in their serum during the first hour of their unit stay
h1_albumin_min | The lowest albumin concentration of the patient in their serum during the first hour of their unit stay
h1_bilirubin_max | The highest bilirubin concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_bilirubin_min | The lowest bilirubin concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_bun_max | The highest blood urea nitrogen concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_bun_min | The lowest blood urea nitrogen concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_calcium_max | The highest calcium concentration of the patient in their serum during the first hour of their unit stay
h1_calcium_min | The lowest calcium concentration of the patient in their serum during the first hour of their unit stay
h1_creatinine_max | The highest creatinine concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_creatinine_min | The lowest creatinine concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_glucose_max | The highest glucose concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_glucose_min | The lowest glucose concentration of the patient in their serum or plasma during the first hour of their unit stay
h1_hco3_max | The highest bicarbonate concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_hco3_min | The lowest bicarbonate concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_hemaglobin_max | The highest hemoglobin concentration for the patient during the first hour of their unit stay
h1_hemaglobin_min | The lowest hemoglobin concentration for the patient during the first hour of their unit stay
h1_hematocrit_max | The highest volume proportion of red blood cells in a patient's blood during the first hour of their unit stay, expressed as a fraction
h1_hematocrit_min | The lowest volume proportion of red blood cells in a patient's blood during the first hour of their unit stay, expressed as a fraction
h1_inr_max | The highest international normalized ratio for the patient during the first hour of their unit stay
h1_inr_min | The lowest international normalized ratio for the patient during the first hour of their unit stay
h1_lactate_max | The highest lactate concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_lactate_min | The lowest lactate concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_platelets_max | The highest platelet count for the patient during the first hour of their unit stay
h1_platelets_min | The lowest platelet count for the patient during the first hour of their unit stay
h1_potassium_max | The highest potassium concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_potassium_min | The lowest potassium concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_sodium_max | The highest sodium concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_sodium_min | The lowest sodium concentration for the patient in their serum or plasma during the first hour of their unit stay
h1_wbc_max | The highest white blood cell count for the patient during the first hour of their unit stay
h1_wbc_min | The lowest white blood cell count for the patient during the first hour of their unit stay
d1_arterial_pco2_max | The highest arterial partial pressure of carbon dioxide for the patient during the first 24 hours of their unit stay
d1_arterial_pco2_min | The lowest arterial partial pressure of carbon dioxide for the patient during the first 24 hours of their unit stay
d1_arterial_ph_max | The highest arterial pH for the patient during the first 24 hours of their unit stay
d1_arterial_ph_min | The lowest arterial pH for the patient during the first 24 hours of their unit stay
d1_arterial_po2_max | The highest arterial partial pressure of oxygen for the patient during the first 24 hours of their unit stay
d1_arterial_po2_min | The lowest arterial partial pressure of oxygen for the patient during the first 24 hours of their unit stay
d1_pao2fio2ratio_max | The highest fraction of inspired oxygen for the patient during the first 24 hours of their unit stay
d1_pao2fio2ratio_min | The lowest fraction of inspired oxygen for the patient during the first 24 hours of their unit stay
h1_arterial_pco2_max | The highest arterial partial pressure of carbon dioxide for the patient during the first hour of their unit stay
h1_arterial_pco2_min | The lowest arterial partial pressure of carbon dioxide for the patient during the first hour of their unit stay
h1_arterial_ph_max | The highest arterial pH for the patient during the first hour of their unit stay
h1_arterial_ph_min | The lowest arterial pH for the patient during the first hour of their unit stay
h1_arterial_po2_max | The highest arterial partial pressure of oxygen for the patient during the first hour of their unit stay
h1_arterial_po2_min | The lowest arterial partial pressure of oxygen for the patient during the first hour of their unit stay
h1_pao2fio2ratio_max | The highest fraction of inspired oxygen for the patient during the first hour of their unit stay
h1_pao2fio2ratio_min | The lowest fraction of inspired oxygen for the patient during the first hour of their unit stay
apache_4a_hospital_death_prob | The APACHE IVa probabilistic prediction of in-hospital mortality for the patient which utilizes the APACHE III score and other covariates, including diagnosis.
apache_4a_icu_death_prob | The APACHE IVa probabilistic prediction of in ICU mortality for the patient which utilizes the APACHE III score and other covariates, including diagnosis
aids | Whether the patient has a definitive diagnosis of acquired immune deficiency syndrome (AIDS) (not HIV positive alone)
cirrhosis | Whether the patient has a history of heavy alcohol use with portal hypertension and varices, other causes of cirrhosis with evidence of portal hypertension and varices, or biopsy proven cirrhosis. This comorbidity does not apply to patients with a functioning liver transplant.
diabetes_mellitus | Whether the patient has been diagnosed with diabetes, either juvenile or adult onset, which requires medication.
hepatic_failure | Whether the patient has cirrhosis and additional complications including jaundice and ascites, upper GI bleeding, hepatic encephalopathy, or coma.
immunosuppression | Whether the patient has their immune system suppressed within six months prior to ICU admission for any of the following reasons; radiation therapy, chemotherapy, use of non-cytotoxic immunosuppressive drugs, high dose steroids (at least 0.3 mg/kg/day of methylprednisolone or equivalent for at least 6 months).
leukemia | Whether the patient has been diagnosed with acute or chronic myelogenous leukemia, acute or chronic lymphocytic leukemia, or multiple myeloma.
lymphoma | Whether the patient has been diagnosed with non-Hodgkin lymphoma.
solid_tumor_with_metastasis | Whether the patient has been diagnosed with any solid tumor carcinoma (including malignant melanoma) which has evidence of metastasis.
apache_3j_bodysystem | Admission diagnosis group for APACHE III
apache_2_bodysystem | Admission diagnosis group for APACHE II
pred | Example mortality prediction, shared as a 'baseline' based on one of the GOSSIS algorithm development models.
