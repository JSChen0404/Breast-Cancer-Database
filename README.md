# Breast-Cancer-Database

**Introduction**

CGBC database is a large thematic database contains around 21,000 patients diagnosed breast cancer from the cancer registry in Chang Gung memorial hospitals, Taiwan. This database comprising de-identified electronic health record (EHR) regarding the outpatient/inpatient service claims, pharmacy prescription, medical cost, and medical utilization for patients with breast cancer. Furthermore, radiology and pathology images for these patients was also included. Though deidentified, CGBCD contains detailed clinical information and requires credentialing before access. The data structure was displayed as figure 1.

**Patient Cohort**

Breast cancer cases diagnosed in six branches of Chang Gung Memorial Hospital between 2010 and 2016 will be reviewed. The case definition was determined with the cancer registry which needs clinical evidence and physician confirmed. The first record in cancer registry was defined as cancer incidence date. All diagnosis and treatment information in cancer registry was also retrieved. Finally, there were 20,966 breast cancer patients in this database.

**Data Description**

CGBCD is a relational database consisting of EHR, radiology images, and digital pathology images. For the EHR, all clinical information, including disease diagnosis, procedure, prescription, laboratory data, medical cost and utilization was recorded by medical encounter. The database retrieved period for EHR was from 2001 to 2019. In addition, cause and date of death were derived from that linked study cohort to National Death Registry by personal identification. 

**List of Tables**

All tables can be linked by an anonymous identification with “IDCODE”. 
* Inpatient expenditures by admissions (DD)
* Details of inpatient orders (DO)
* Details of inpatient approval
* Ambulatory care expenditures by visits (CD)
* Details of ambulatory care orders (OO)
* Details of outpatient approval
* Cancer registry
* National death registry
* Pathology images
* Radiology images

**Variables Characteristic**
The CGBCD contained a variety of clinical information to let researchers conducted multiple discipline researches. Some important derived factors were displayed below. A codebook for the Breast Cancer Patients Data was displayed as table 1 as an example.
* Cancer information (such as cancer staging, breast slide, meta)
* Diagnosis (reported by ICD9/10 diagnosis codes)
* Procedure (reported by ICD9/10 procedure codes)
* Prescriptions (such as name of drug, dose, frequency, path.)
* Laboratory data
* Cost
* Medical utilization
* etc.

**Requesting Datasets**

To request a dataset, please contact the Center of Artificial Intelligence in Medicine at cgmhailab@gmail.com

**License agreement**

This dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation. Permission is granted to use the data given that you agree:

1.	That the dataset comes “AS IS”, without express or implied warranty. Although every effort has been made to ensure accuracy, we (Center for Artificial Intelligence in Medicine from Chang Gung Memorial Hospital) do not accept any responsibility for errors or omissions.
2.	That you include a reference to the CGBC Dataset in any work that makes use of the dataset. Cite the following sentence: Chang Gung Breast Cancer (CGBC) database from Center for Artificial Intelligence in Medicine of Chang Gung Memorial Hospital.
3.	That you do not distribute this dataset or modified versions. It is permissible to distribute derivative works in as far as they are abstract representations of this dataset (such as models trained on it or additional annotations that do not directly include any of our data) and do not allow to recover the dataset or something similar in character.
4.	That you may not use the dataset or any derivative work for commercial purposes as, for example, licensing or selling the data, or using the data with a purpose to procure a commercial gain.
5.	That all rights not expressly granted to you are reserved by us (Center for Artificial Intelligence in Medicine, Chang Gung Memorial Hospital).

