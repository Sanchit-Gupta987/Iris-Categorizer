# Iris Species Predictor

This is a simple web application built with Streamlit that predicts the species of an Iris flower based on its sepal and petal measurements. It uses a pre-trained Random Forest Classifier model.

## How It Works

The application trains a `RandomForestClassifier` on the classic Iris dataset from Scikit-learn. Users can input the sepal length, sepal width, petal length, and petal width using interactive sliders.

When the "Predict" button is clicked, the app uses the trained model to predict the Iris species (`setosa`, `versicolor`, or `virginica`). The prediction is then displayed, and the input values along with the result are added to a history table shown at the bottom of the page.

## Deployment Location

Currently deployed on streamlit - https://sg-ml-demonstration.streamlit.app/ 
<small>PS: Might have to click a reactivate button</small>

## How to Run

1.  **Install Dependencies:**
    Install the packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run the App:**
    Save the code as a Python file and run the following command in your terminal:
    ```bash
    streamlit run ml_app.py
    ```
    Your web browser will automatically open with the application running.
