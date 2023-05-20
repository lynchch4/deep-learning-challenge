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
![image](https://github.com/lynchch4/deep-learning-challenge/assets/117898475/369f61e1-6cef-4ddc-9d99-53b8b295c133)
-	The steps that were taken to increase the model’s performance were adding an additional layer to the neural network model, increase the neurons from 80 to 120 in the first layer, increasing the epochs from 100 to 150 and adding the Name variable as a feature.

Summary:
The overall result for the model is that by increasing the complexity of the model, and adding additional features we were able to increase the accuracy of the model by 3%. The name feature was important because we were able to group agencies who had made multiple loan requests with the organization. I different model that could be used to analyze this problem is the support vector machine classifier, this would require removing or binning the ask amount as it would only allow binary options.  This model would allow us to see how likely any given venture would results in success given the factors listed for each one.	



