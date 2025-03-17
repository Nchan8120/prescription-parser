# prescription-parser
A doctor prescription parser using CRF model. Takes a prescription as a sentence as input and find/label the words in the sentence with one of the already pre-defined labels.


### Problem: SEQUENCE PREDICTION - Label words in a sentence
#### Input : Doctor Prescription in the form of a sentence split into tokens
- Ex: Take 2 tablets once a day for 10 days

#### Output : FHIR Labels
- ('Take', 'Method')
- ('2', 'Qty') 
- ('tablets', 'Form')
- ('once', 'Frequency')
- ('a', 'Period') 
- ('day', 'PeriodUnit')
- ('for', 'FOR')
- ('10', 'Duration')
- ('days', 'DurationUnit') 
