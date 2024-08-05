
## About The Project

Soft tissue sarcoma (STS) is a kind of cancer, which people can develop at any age and at nearly any location in the body. It is a less common cancer, which creates challenges for research outcomes and seeking to improve care. 

One means of clinical research is through databases. Often these databases include patient diagnoses and procedures with the use of ontologies. One common ontology is the International Classification of Diseases (ICD), which gives a code that for particular diagnoses. Unfortunately, searching clinical databases for ICD codes related to STS may miss patients who have that diagnosis, but do not have an appropriate associated code. 

An alternative means for identifying patients with STS is through the direct search of pathology reports. In this project, we utilized NLP techniques to classify pathology reports.  This particular project is for myxofibrosarcoma, which is a kind of STS. Each pathology report is read, and counts made for terms of emphasis, negation, etc.  Then a series of decisions are made to classify that report as either:
- representing a myxofibrosarcoma
- representing a diagnosis other than myxofibrosarcoma
- requiring manual review for ultimate classification

The list of relevant terms, and the sequential model for classification, are being made publically available here as part of publishing this project as a peer-reviewed paper. We hope that doing so will facilitate researchers and others with improvement and external validation of the model. 

## Getting Started

One document has all the relevant terms, and the regular expression terms utilized to identify them from the pathology reports.

One document has the code for the model.

Of note, no personal health information is anywhere in these files. The raw data is not publically available. However, the included documentation could be utilized to run and check the model on any group of pathology reports. 

## Roadmap

- Future plans are to replicate this process for all the non-ultrarare soft tissue sarcomas, including desmoid fibromatosis
- Additionally, aim to make use of this code easier, by generating it as a program which can point to a list of pathology reports and provide classification of all the diagnoses

