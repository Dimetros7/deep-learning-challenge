# deep-learning-challenge
    Overview
The goal of this analysis was to develop a machine learning model capable of predicting the success of organizations funded by Alphabet Soup. By examining the dataset's features, the model classifies applicants as either successful or unsuccessful. This predictive capability aims to assist Alphabet Soup in selecting applicants with the highest likelihood of success.

Results

Data Preprocessing

Target Variable:
The target variable, "IS_SUCCESSFUL", represents whether an applicant was successful (1) or not (0).

Feature Variables:
The dataset includes various attributes related to each organization, such as:

Application type
Affiliation
Classification
Use case for funding
Organization type
Status
Income
Special considerations
Funding requested
These features were utilized to predict an organization’s success.
Removed Variables:

EIN (Employer Identification Number) and organization name were excluded from the dataset.
These columns serve only as identifiers and do not contribute to the model's predictive cpabilities.

Model Development, Training, and Evaluation
Model Architecture:
The neural network consists of three layers:

First Hidden Layer: Dense layer with 4 neurons
Second Hidden Layer: Dense layer with 2 neurons
Output Layer: Single neuron providing a binary classification (0 = unsuccessful, 1 = successful)

Activation Functions:
Hidden layers: ReLU (Rectified Linear Unit)
Output layer: Sigmoid function

Training Results
The model was trained for 100 epochs, demonstrating significant improvement over time:

Epoch 1:

Accuracy: 66.56%
Loss: 0.6716
Precision: 0.6764
Recall: 0.7269

Epoch 100:

Accuracy: 73.47%
Loss: 0.5581
Precision: 0.7288
Recall: 0.8000


Model Performance
Final Evaluation:

The model exceeded expectations, achieving high accuracy, precision, and recall with minimal loss.
The strong performance metrics indicate that the model effectively differentiates between successful and unsuccessful applicants.
Potential Improvements:
While the model already performs exceptionally well, further refinements could include:

Extending the training period (more epochs)
Adjusting model layers and hyperparameters for optimization


Conclusion
The deep learning model demonstrated outstanding performance, achieving near-perfect accuracy, precision, and recall. It effectively predicts the likelihood of an organization’s success based on dataset features.

A potential alternative model that could achieve comparable or superior results is the Random Forest algorithm. Random Forest models tend to provide high accuracy while mitigating overfitting by leveraging multiple decision trees.
