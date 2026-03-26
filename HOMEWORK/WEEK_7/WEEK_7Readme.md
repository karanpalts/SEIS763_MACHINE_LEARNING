
The dataset on the Canvas (ML_HW_Data_CellDNA.csv) contains various numeric
measurements (i.e. size, center, etc) from thousands of bacterium under microscope. The
non-zero values in the last column are the target responses that indicate the bacterium
(rows) that are interesting enough for further study. The 0s in the last column indicate the
bacterium (rows) are NOT interesting candidates for further study. Convert this target
dependent variable (last column) to binary values of either 0s or 1s for your two-class
classification.

Write a program using either Python, MatLab, or any programming language of your
choice to perform the two-class classification analysis on this dataset using the Support
Vector Machine method. You do NOT need to split data into training and testing sets.
Answer the following questions:

1. How many support vectors did you find?
   
2. List top 3 records that have the smallest **absolute** values decision values
(i.e. from wT • X + b calculation).

3. What are the decision values for the following records: 131, 165, 892, 1057 (in
Matlab), or 130, 164, 891, 1056 (in Python)? Please explain anything special
about those values of these few records? Also, what are the probabilities of
belonging to the class 1 (i.e. the 2nd class) for those records?

4. What is the precision, recall, F-measure of **EACH** of the two classes.

5. Create a ROC Curve and measure its AUC for **EACH** of the two classes.
