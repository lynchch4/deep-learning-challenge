# deep-learning-challenge

Success in Funding Analysis

Overview:
	The purpose of this analysis is to identify the applicants for funding with the best odds of success in stated goal. We will be looking at various factors that affect the likelihood of success for each venture and how they affect the overall success of the venture.

Results:
     (Data Processing)
	The variable that is the target for the model is the success or failure of the venture. The features that were used in the model were as follows:
-	Application Type
-	Affiliation
-	Classification
-	Use Case
-	Organization
-	Status
-	Income Amount
-	Special Considerations
-	Asking Amount
-	Name of organization

With the EIN number being removed prior to analysis, due to each one being unique to each application.

     (Compiling, Training, and Evaluating the Model)
![image](https://github.com/lynchch4/deep-learning-challenge/assets/117898475/2462cb4f-c28b-4fdb-a3d5-c4caecd782dc)


-	There were 3 layers total for the neural network model, with 120 neurons in the first layer, 30 neurons in the second, and 10 neurons in the third layer, I used the relu activation function for each layer. I added additional neurons and an additional layer to increase the model’s complexity.
-	The target model performance was achieved with an accuracy of .7566.

