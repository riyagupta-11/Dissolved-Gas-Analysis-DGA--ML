# DGA Analysis using Decision Tree and Random Forest Classifier

DGA ML model helps us interpret the type of fault occurring inside an oil-filled power transformer based on the concentration of dissolved gases in its insulating oil.
In simple terms, it learns the relationship between the five gases and seven fault categories, then predicts which fault category a new gas sample most likely belongs to.

What does this model helps us to understand?

1. Fault identification: It classifies transformer faults into seven categories, such as arc discharge, partial discharge, spark discharge, and different temperature-related overheating faults.

2. Gas–fault relationship: It learns patterns in the concentrations of H₂, CH₄, C₂H₆, C₂H₄ and C₂H₂ that help distinguish different fault categories.

3. Comparison of ML algorithms: It helps you compare Decision Tree and Random Forest approaches to identify which performs better on your dataset.

4. Class imbalance: It helps you investigate whether techniques such as class weighting and SMOTE improve the prediction of less-represented fault categories.

5. Prediction performance: It shows which faults your model can identify reliably and which faults it struggles to distinguish.

What are current results interpreted from this model?

Random Forest with SMOTE achieved:
- Accuracy: 70.73%
- Macro F1-score: 0.68
