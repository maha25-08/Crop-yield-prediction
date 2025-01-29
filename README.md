This project aims to predict crop yield and production based on agricultural data from India. The system utilizes machine learning models to predict crop production and yield in kilograms, helping farmers make informed decisions about crop production.
Dataset
The dataset used for this project contains various agricultural attributes such as state, district, crop, season, area, and production. It includes information on the crop year, temperature, humidity, and soil moisture. These attributes are used to train a model that can predict the crop production and yield based on the given input data.

Dataset Columns:
State_Name: Name of the state where the crop is grown.
District_Name: Name of the district where the crop is grown.
Crop_Year: The year when the crop is cultivated.
Season: The season during which the crop is grown (e.g., Rabi, Kharif).
Crop: The type of crop grown (e.g., rice, wheat).
Area: Area of land under cultivation (in acres).
Production: Total crop production (in kilograms).
Temperature: Average temperature during the growing season (in degrees Celsius).
Humidity: Average humidity during the growing season (in percentage).
Soil_Moisture: Moisture content in the soil (in percentage).

Dataset Location:
File path: data/crop_modified.xlsx
This dataset is used to train machine learning algorithms like KNN and Naive Bayes to predict crop yield and production.

HTML File - crop.html
The crop.html file provides the front-end interface for the Crop Yield Prediction System. Users can input agricultural data, including state, district, crop, area, year, and season, into a form. After submission, the predicted crop production and yield are displayed on the same page.

Key Sections:
Meta Tags: Includes responsive design settings and character encoding.
Title: Displays "Crop Yield Prediction System" on the browser tab.

Form:
Collects input data from users (state, district, crop, area, year, season).
Sends the data for prediction.
Predicted Results: After form submission, the page dynamically displays predicted values for crop production and yield (in kilograms and kilograms per acre).
Footer: Contains copyright information and credits.
Bubble Animation: Decorative effect to add visual interest.
HTML File Location:
File path: templates/crop.html

CSS File - style.css
The style.css file provides styling for the webpage to enhance its appearance and user experience. It ensures that the page is visually appealing, easy to navigate, and responsive across various devices.

Key Sections:
General Styling:
Sets the background color and font for the body.
Centers the main content with a clean layout.
Form Styling:
The form inputs (text fields) are styled for ease of use.
Includes padding, borders, and placeholder text styling.
The submit button has a custom background color and hover effect for interactivity.
Text Styling:
Headings and subheadings are styled for emphasis, with bold font weight for main titles.
Clear spacing for form labels for better readability.

CSS File Location:
File path: static/css/style.css
