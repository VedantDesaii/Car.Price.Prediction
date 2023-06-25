# Car.Price.Prediction
The project is a car price prediction model that aims to predict the selling price of used cars.
The development of the project took place in Jupyter Notebook, utilizing various libraries and techniques.
One-hot encoding was applied to handle categorical variables, allowing them to be used in the machine learning model.
Seaborn, a data visualization library, was used to create a pair plot, which visualizes the relationships between different features of the dataset.
Hyperparameter tuning was performed on the ExtraTreesRegressor algorithm, optimizing its parameters to improve the model's performance.
The evaluation of the Random Forest Regression model involved calculating metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
The model's results were visualized using scatter plots, showcasing the predicted prices against the actual prices, and a hyperplane to represent the regression model's fit.
A heatmap was created to illustrate the correlation between different features of the dataset.
Additionally, an interactive front-end part of the project was developed using Flask, a web application framework in Python.
The Flask web application loaded the trained regression model and provided a user-friendly interface via HTTPS.
Users could input car details, such as the year, present price, kilometers driven, owner count, fuel type, seller type, and transmission type.
The application then utilized the loaded model to predict the selling price of the car based on the provided information.
Overall, this project aimed to build a car price prediction model using machine learning techniques. It involved data preprocessing, visualization, model evaluation, and the development of an interactive web interface to provide predictions to users.
