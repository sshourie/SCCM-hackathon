This project was part of a [datathon](https://sccm.org/Research/Discovery-Research-Network/datascience/Datathon) with Society of Critical Care Medicine (SCCM), which involved coloration with clinicians and pharmacists to develop a data-driven model for care of critically ill patients using large health record databases.

#### Problem Description:

> Are there differences in sedative agent selection in adult patients on invasive mechanical ventilation based on race

#### Databases: 

We used two critical care databases:[ MIMIC-IV](https://physionet.org/content/mimiciv/2.2/) (Medical Information Mart for Intensive Care) database and the [eICU collborative research database. ](https://eicu-crd.mit.edu/about/eicu/)

#### BigQuery and Colab: 

We used [BigQuery](https://console.cloud.google.com/bigquery?project=sccm-datathon) to easily explore the large datasets using SQL. 

The colab/ipynb notebooks on this repository are definetly not perfect as they were done in collobration, are messy, untidy, buggy etc.


#### Sample projects from SCCM on how to work on the databases:

Notebook 1 (eICU): Exploring the patient table. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/01_explore_patients.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 2 (eICU): Severity of illness. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/02_severity_of_illness.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 3 (eICU): Summary statistics. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/03_summary_statistics.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 4 (eICU): Timeseries. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/04_timeseries.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 5 (eICU): Mortality prediction. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/05_mortality_prediction.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 6 (eICU): Acute kidney injury. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/06_aki_project.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 7 (eICU): Project work. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/07_project_work.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Notebook 8 (MIMIC): Weekend effect on mortality. <a href="https://colab.research.google.com/github/MIT-LCP/sccm-datathon/blob/master/mimic-weekend-effect.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
