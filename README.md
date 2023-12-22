## Predicting diabetes
### Dataset
The dataset used in this project is originally from the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK). This project aims at building a logistic regression model to predict diabetes, based on certain diagnostic measurements used as predictors (see below). The outcome variable is a binary one indicating whether or not the patients have diabetes. The resampling method Monte Carlo simulation is used to cross-validate the model.

The R code in this project for data visualization and logistic regression was written in R Markdown and knitted to html.
#### Variable description
* `Preganancies`: Number of times pregnant
* `Glucose`: Plasma glucose concentration in an oral glucose tolerance test
* `BloodPressure`: Diastolic blood pressure (mm Hg)
* `SkinThickness`: Triceps skinfold thickness(mm)
* `Insulin`: Two hour serum insulin
* `BMI`: Body Mass Index
* `DiabetesPedigreeFunction`: Diabetes pedigree function
* `Age`: Age in years
* `Outcome`: Whether or not the patients have diabetes. 0 for no and 1 for yes. 
### Data source
[Diabetes Healthcare: Comprehensive Dataset-AI](https://www.kaggle.com/datasets/deependraverma13/diabetes-healthcare-comprehensive-dataset) 
### References
* Gelman, A., Hill, J., & Vehtari, A. (2020). *Regression and other stories*. Cambridge University Press.
* Kuhn, M., & Silge, J. (2022). *Tidy modeling with R*. O'Reilly Media, Inc.
