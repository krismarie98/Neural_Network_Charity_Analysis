# Neural_Network_Charity_Analysis
## Overview of Analysis:
### The purpose of this analysis is to use neural networks to predict which organization will be succesful if funded by Alphabet Soup. Once the initial machine learning model is set up, we attempted to create different model in order to get a higher accuracy score.
## Results:
### Data Preprocessing:
* What variable(s) are considered the target(s) for your model?
The variable that is considered a target for this model is the column "Is Successful."
* What variable(s) are considered to be the features for your model?
The variables that are considered to be features for this model are application types, affiliations, ask amount, special considerations, income amount, status, organizations, use cases, and classifications. Each of these columns were further broken down into separate columns to represent the diferent answers.
![image](https://user-images.githubusercontent.com/112527054/216475674-d515d689-7853-4b06-9a69-94b8905b68ee.png)
* What variable(s) are neither targets nor features, and should be removed from the input data?
The two columns that were removed from the data set were the EIN columns and the name columns. This is because they did not add value to the question posed.
### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
With the first attempt I choose to keep the original model I did with two hidden layers and with all the activations function the same using relu except the output layer which used sigmoid. For teh second attempt I choose to add a third layer and increase the number of nodes for each layer. Additionally, the output layer was changed to tanh. For the third attempt I still had three hidden layers but increased the node amount and changed the output  activation function back to sigmoid. I was hoping that by adding the additional layers and chaning the ouput function that the models accuracy would increase.
* Were you able to achieve the target model performance?
I was not able to achieve the target model perfomance, my accuracy did not increase a significant amount.
![image](https://user-images.githubusercontent.com/112527054/216475783-95a4dbe3-4a85-42bf-a07a-225333061cf0.png)
![image](https://user-images.githubusercontent.com/112527054/216475834-274a7c8a-01cc-410b-b5ec-b6d738b62166.png)
![image](https://user-images.githubusercontent.com/112527054/216475889-92488d50-4eee-4f7f-888a-3e041cb77aef.png)
* What steps did you take to try and increase model performance?
I added additional hidden layers and more nodes within those hidden layers. I also changed the output activation function.
## Summary:
### From the first neural network the accuract was at .7074 and the later models did not improve even a percent.Overall I tried differnt ways to make neural networks work but I beleive other methods may get a better results such as random forest or SVM. Neural networks may be too complicated for this data.I would reccomment further test tocompare the different models with the neural network route.
