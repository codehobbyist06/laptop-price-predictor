# LAPTOP PRICE PREDICTOR
This is a machine learning project which allows us to predict the price of a laptop which fits within the given specifications.

It takes as input values like Brand, Type, Ram, Screen size, etc. and predicts the estimated price of the laptop with these set of features using the Random Forest regression algorithm.

Following is a demonstration of the application:

![project_gif](https://user-images.githubusercontent.com/65885804/155505644-f35dd264-78e0-4fdb-8a84-2b00dbecdea8.gif)

# Setup the project locally
1. Clone the git repository.
```
git clone https://github.com/codehobbyist06/laptop-price-predictor.git
cd laptop-price-predictor
```
2. Install all the required packages.
```
python -m pip install -r requirements.txt
```
3. Run the application.
```
streamlit run app.py
```
The application is deployed on heroku and can be found [here](https://laptop-price-predictor-ml.herokuapp.com/).
