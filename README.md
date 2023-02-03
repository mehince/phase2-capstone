![Header](./Photos/employee_burnout_cropped.png)

# Predicting Employee Attrition Using Decision Trees and Random Forests
Employees leave companies and organizations every day for different reasons such as being fired, retiring, or resigning. If a company is looking to hire and retain more employees, how can they improve the strategies they use to do so?

## Business Understanding
**Employees** are the heart of any company or organization - without employees, work doesn't get done and money doesn't get made. If an organization's **upper leadership and/or human resources staff** can determine why an employee may leave, they can use this information to **create more effective hiring and retention practices.** 

## Data Understanding
The data used in this project was retrieved from [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) but was originally collected by IBM's human resources department.

This data is in the form of a survey given to employees. The features are relatively self-explanatory, but there isn't much information regarding where this data was collected from other than what was previously mentioned.

The features in this analysis be later used to train predictive models to determine whether an employee will leave a company. After tuning and other improvements, this could be useful for upper leadership and/or human resources staff to identify changes that need to be made to more effectively hire or retain employees.

Although there were no missing values in this dataset, it is a small dataset relative to what is generally used to effectively train a machine learning model. This limitation of data means that there is a limitation to how well the machine learning models trained on the data perform. Additionally, some values such as Gender, JobRole, and MaritalStatus needed to be encoded for the machine learning model to use in its predictions.

Another limitation of this data is that there is a class imbalance - there is a much higher number of employees who stayed at IBM than left in this dataset. This class imbalance was addressed by resampling the data using SMOTE (Synthetic Minority Oversampling TEchnique).

## Model(s) and Evaluation
First, an untuned decision tree model was used to get a baseline for later models' performance. 

## Conclusion

## Repository Navigation

## Sources
[Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
[Learning about SMOTE](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/)
[Understanding Random Forests](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)
[Using Random Forest Model](https://towardsdatascience.com/random-forest-in-python-24d0893d51c0)
