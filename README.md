# Drug_Classsification

In this project two Web APi's are created where in user can go to the website https://formapi.azurewebsites.net/, enter the following information in the form:

1) age
2) gender
3) Blood Pressure
4) Sodium to Potassium Ratio

Upon entering the information a second Web Api of ML algorithm(Decision Tree) is called, which tells the user which drug they should take based on the information entered.

# Drug Classification directory in this repository consists of the following files:

1) 'app.py': This file consists of the form which is a Flask Application, which helps the users to see the form and enter the information on the website.
2) 'drug200.csv' : This is the dataset on which the Decision Tree classifier algorithm was trained with an accuracy of 95%
3)  'model.pkl' : This is the trained Decision tree model. It is the our model in which all the trainable parameters are saved. Basically, once the model was evealuated it was saved as model.pkl so that the model need not be trained again.
4)  requirement.txt: This file consists of the Python libraries used in the project. This is required when deploying the model to Azure.

The Machine Learning model and Flask form can be easily deployed using Visual Studio Code Azure service.

# Working

After the Web API's have been created and deployed. 

The following are the Web API's created by me on Azure <br>

![image](https://user-images.githubusercontent.com/59137011/149164026-8184cb7a-891e-441c-8fdf-c52b8a05f257.png)


Go to the url provided by Azure for forms, in my case https://formapi.azurewebsites.net/ <br>
Upon entering the information and pressing the submit button out Web API our second Web API is called which consists of the ML model, and output(i.e which drug user should take) is displayed on the screen based on our  ML model.<br>

# INPUT

![image](https://user-images.githubusercontent.com/59137011/149164252-0d6b27cd-de0b-4bd4-9c95-d6e66fbe33f8.png)

# Output

![image](https://user-images.githubusercontent.com/59137011/149164361-2672d9de-5b30-409b-baae-0abb3f17a0cc.png)





