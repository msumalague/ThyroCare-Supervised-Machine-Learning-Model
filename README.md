# ThyroCare-Supervised-Machine-Learning-Model
Supervised Machine Learning Model for Thyroid Disease Classification 

## Thyroid Diseases Dataset
These reports were available at https://rb.gy/jbazib. These data were constructed
containing the following:
1. Age
2. Sex
3. On_thyroxine
4. Query_on_thyroxine
5. On_antithyroid_medi
cation
6. Sick
7. Pregnant
8. Thyroid_surgery
9. l131_treatment
10. Query_hypothyroid
11. Query_hyperthyroid
12. Lithium
13. Goiter
14. Tumor
15. Hypopituitary
16. Psych
17. TSH_measured
18. TSH
19. T3_measured
20. T3
21. TT4_measured
22. TT4
23. T4U_measured
24. T4U
25. FTI_measured
26. FTI
27. TBG_measured
28. TBG
29. Referral_source
30. Target
31. ID

## Data Preprocessing

The cleaned data of different thyroid diseases (hyperthyroidism, hypothyroidism
and euthyroid) underwent synthetic data generation using MOSTLY AI which pioneered
the generation of synthetic data for the development of AI models and software testing.
Exploratory Data Analysis was carried out to see the correlation and significant
relationship between the variables. These data were inspected and encoded in csv files.
Then, it underwent preprocessing using python, NumPy and pandas to get an overview of
the data types, fill null values, label categorical values, and remove outliers and

## Training and Testing the ML Algorithms
Following data preprocessing, the dataset was split for the modeling process using
the Sci-Kit Learn Library. The dataset was divided into eighty percent (80%) training sets
and twenty percent (20%) validation sets.
unnecessary variables to ensure the performance of the model. 
