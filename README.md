# Delirium

# Using large-scale electronic health record data to predict delirium in ICU units: An evidence-based machine learning approach

## Abstract

### Background
 
Delirium is a severe health condition that features sudden changes in the level of consciousness.Delirium can cause many problems such as prolonged hospital stays, unforgettable negative experiences, as well as an increased mortality rate and increased health care costs. Delirium can affect anyone, but it happens mostly to patients in ICU units. Due to the complexity of the condition,it is challenging for even physicians to spot it. To date, the mechanism behind the condition remains unclear.
 
### Objective
 
The objective of this thesis is to examine the possibility of combining machine learning and electronic health record data to discover the most critical factors that may trigger delirium. The subsequent objective is to bring any new findings to the public to compliment the current assessment tools.

### Methods
 
An experimental study was performed to discover the relationship between risk factors and delirium. Data queried from the MIMIC database was resampled to combat imbalanced classes. A comparison of the performances achieved by different learning algorithms was conducted.
 
### Results
 
There were 45,559 subjects selected for analysis, out of which 3,154 subjects were delirious patients. Except for some expected causes, such as altered mental status and alcohol withdrawal-induced delirium, patients with pneumonia, sepsis, acute respiratory failure, and heart-related disease were most prone to delirium. Delirious patients had significantly longer mechanical ventilation hours and extended stays in hospital. A positive Angus-Sepsis value and a lifted urea
lab result were both associated more frequently with delirious patients. There were no significant differences in age, gender, electrolytes, and vital signs between the delirious and non-delirious groups. K-nearest neighbors plus the combined over- and under-sampling method gave the best results in a multi-label dataset, while logistic regression using the hardness threshold sampling method was an ideal approach for a binary dataset.

### Conclusion
 
This study found that among the twenty-six variables selected for inclusion, diagnosis, urea lab result, Angus-sepsis value, length of stay in the hospital, and mechanical ventilation hours were good indicators for predicting delirium in ICU units. When based on electronic health records, machine learning could be a useful tool for the early diagnosis of delirium. If the data is heavily imbalanced, a resampling method should be applied before making any predictions. Further prospective studies are highly recommended.
 
### Keywords
 
delirium, machine learning, predict, ICU, EHR, MIMIC

### Full text 

[Full text](https://drive.google.com/file/d/1dZDxb0V8wkkkvMB6_YCJAi273aW6TkEY/view?usp=sharing)  
