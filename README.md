# Stroke data prediction using PySpark

In this project work on healtcare dataset, in particular stroke data. There are 5110 observations and 12 variables. I considered the variable 'stroke' as response varaible and others as predictors.

I start with data cleaning, that comprehends NA, null and Nan detection and treament; varaible casting and conversion and, finally, graphic exploration.

Then I preprocessed data by encoding string varaibles through StringIndexer, OneHotEncoder, and Vector Assembler; in order to arrange X and Y for models.

In the end I fitted Logistic Regression and Random Forest models whith training and test split approach.
