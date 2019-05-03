# delirium

# Using a large-scale EHR record to predict delirious patients in ICU units: an evidence-based machine learning approach

## Abstract

### Background
 
Delirium is a severe health condition with the feature of sudden changes in the level of consciousness. Delirium could cause many problems such as prolonged hospital stays, unforgettable negative experiences as well as increased mortality rate and health care cost. Delirium can affect anybody, but it happens mostly to patients in the ICU units. Due to the complexity of the disease, it is challenging to spot delirious patients even for physicians. To date, the mechanism behind the disease remains unclear.  
 
### Objective
 
To exam the possibility of combining machine learning and EHR to discover the most critical factors that may trigger delirium. After that, bring new findings to the public as a compliment to the current assessment tools.
 
### Methods
 
An experimental study was performed to discover the relationship between risk factors and delirium. Data queried from MIMIC database was resampled to combat imbalanced classes. A comparison of performances among different learning algorithms was conducted.
 
### Results
 
There were 45,559 samples selected for analyzing, out of which 3154 subjects were delirious patients. Except for some expected causes such as altered mental status and alcohol withdrawal-induced delirium, patients with pneumonia, sepsis, acute respiratory failure, and heart-related disease were the most common group that prone to delirium.  Delirious patients had also significantly longer mechanical ventilation hours and an extended stay in hospital.  A positive Angus-Sepsis value and a lifted urea lab result were more associated with delirious patients.  There were no significant differences in age, gender, electrolytes and vital signs between delirium and non-delirium group. K-nearest neighbors (KNN) plus the combined over- and under sampling method gave the best results in a multilabel dataset, while logistic regression (LR) with hardness threshold sampling method was an ideal approach for a binary dataset.  

### Conclusion
 
The study demonstrates that machine learning could provide an excellent opportunity for predicting delirious patients in ICU units from EHR records.  Further prospective studies are highly recommended.
 
### Keywords
 
delirium, machine learning, predict, ICU, EHR, MIMIC
