# Real_Estate_Solution
This app has been built using Streamlit and deployed with Streamlit community cloud

[Visit the app here](https://realestatesolution.streamlit.app/)

password - streamlit

This application predicts housing prices based on inputs derived from the Real Estate dataset. The model aims to help users estimate property values by leveraging machine learning predictions.

## Features
- User-friendly interface powered by Streamlit.
- Input form to enter details such as property location, house size, number of rooms, and other relevant factors.
- Real-time prediction of housing prices based on the trained model.
- Accessible via Streamlit Community Cloud.

## Dataset
The application is trained on the **Real Estate dataset**, a widely used dataset for evaluating housing prices. It includes features like:
- Location
- House size
- Number of rooms
- Age of the property
- Proximity to amenities
- And other factors influencing housing prices.

## Technologies Used
- **Streamlit**: For building the web application.
- **Scikit-learn**: For model training and evaluation.
- **Pandas** and **NumPy**: For data preprocessing and manipulation.
- **Matplotlib** and **Seaborn**: For exploratory data analysis and visualization (if applicable).

## Model
The predictive model is trained using the Real Estate dataset. It applies preprocessing steps like encoding categorical variables and scaling numerical features. The regression model used is Random Forest.

## Future Enhancements
* Adding support for multiple datasets.
* Incorporating explainability tools like SHAP to provide insights into predictions.
* Adding visualizations to better represent user input and model predictions.

## Installation (for local deployment)
If you want to run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/paulhehehe/regression_application-main.git
   cd regression_application-main
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

#### Thank you for using the Real_Estate_Solution Application! Feel free to share your feedback.

