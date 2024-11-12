
# Custom Named Entity Reconition with spaCy
This project involves building a custom Named Entity Recognition (NER) system using the spaCy library to identify and classify critical entities in text. The model is tailored to extract information across specific domains, categorizing entities into Legal, Health, and Banking. By leveraging spaCy’s powerful NLP capabilities, along with a structured annotation pipeline, this NER system facilitates accurate extraction and visualization of entities, making it highly applicable for data redaction, compliance, and information extraction tasks.



## Parameters
NER system includes comprehensive entity recognition for categories like:-
NAME,ORG,GPE,DATE,EMAIL,PHONE,MEDICATION,HEALTH,AGE,TIME,ACCOUNT,IFSC,PAN,ACN,MONEY

ACN-Aadhar Card Number,
GPE-Geopolitical entity

## Features
Custom Entity Recognition for Specific Domains 

Entity Annotation with NER Annotator

Efficient Data Pipeline for Model Training

Color-Coded Visualization with spaCy’s displacy


## Screenshots

![App Screenshot](https://github.com/sidheshsahu/Custom_NER/blob/main/Screenshot%202024-11-12%20183627.png)




![App Screenshot](https://github.com/sidheshsahu/Custom_NER/blob/main/Screenshot%202024-11-12%20183650.png)



## Applications
Data Redaction: Redacts sensitive information in documents by detecting and masking Legal, Health, and Banking information.

Information Extraction: Supports applications where extracting specific entity types is critical, such as compliance, legal document review, and financial audits.
