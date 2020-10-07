# Absence_Code_Classification

### Introduction:
This project aims to classify raw absence codes and descriptions from school districts into my organization's standard absence code. 
When we receive absence codes and descriptions from our partner school districts or regional data centers (that are groups of multiple school districts), we map their codes to our standard codes to ensure data consistency across districts. 
 
 
### Purpose:
We look at these information:
  1) Absence codes that are mostly one to a few letters
  2) Absence descriptions that range from a few words to a few short sentences
  
Then, we map them to the organization's absence status:
  * Absent = 1 if it is considered absent or
  * Absent = 0 if it is considered present.
  
  
### Project Structure:
1) Exploring and clean data
2) Pre-processing texts field (absence descriptions) using Natual Language Processing techniques
3) Creating a bag-of-words model using TF-IDF vectorizer
4) Building models
5) Tuning hyperparameters

