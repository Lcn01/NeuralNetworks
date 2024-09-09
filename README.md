# NeuralNetworks
This is my code notebook and churn CSV file for my Neural Networks course from UT Austin's Postgraduate Certification in AI/ML: Business Applications. In this project, I built a neural network for a bank that would enable the bank to accurately predict customer churn.

The data was first loaded into a Jupyter Notebook, where exploratory data analysis was performed and the data was visualized using Seaborn. Next the data was split into train, test, and validation sets and the model was built using Tensorflow. Six different neural networks were created:

* SGD Optimizer
* Adam Optimizer
* Adam with Dropout
* Adam with SMOTE
* SGD with SMOTE
* Adam with SMOTE and Dropout

Once these networks were all created and evaluated, the final model (Adam with SMOTE and Dropout) was selected based on the recall score on the validation data set. Once the chosen model was run on the test set, a final recall score of .77 was reached and business insights and recommendations were given based on the exploratory data analysis and model results.
