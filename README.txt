Authors: - Méwen JEANNENEY
	 - Roland DENIZOT
	   ESILV A4 DIA4

Subject: QSAR Biodegradation Data Set

Purpose: Study the relationships between chemical structures and biodegradation of molecules.

Tasks: - Data-Visualization
       - Modelizations ith machine learning models, customization of hyperparameters

Conclusions:
Customizing hyperparameters is a good idea to improve the model and scaling is not always necessary, it depends on the dataset.
Finally, the best model is the RandomForestClassifier with hyperparameters boosted. (This value can change due to the split if we re-run the model but the 4 best models are always the same and the boost of hyperparameters is always efficient).
