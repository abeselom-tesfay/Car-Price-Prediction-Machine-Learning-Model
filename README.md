# Car Price Prediction Machine Learning Model

## Project Overview

This project implements a **Car Price Prediction** machine learning model using **Linear Regression** in Python. It predicts the selling price of a used car based on various features such as brand, year, kilometers driven, fuel type, seller type, transmission, owner history, mileage, engine capacity, maximum power, and number of seats.

The project covers data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and deployment as an interactive **web application** using Streamlit.

---

## Dataset

The dataset used for this project is available here:  
[Download Car Details Dataset](https://drive.google.com/file/d/1UIj8rOmDJn4UgqDTJezMNfzr7jh_behL/view)

---

## Features

| Feature        | Description                                  |
|----------------|----------------------------------------------|
| `name`         | Car brand (e.g., Maruti, Honda, Toyota)      |
| `year`         | Manufacturing year of the car                  |
| `km_driven`    | Total kilometers driven                        |
| `fuel`         | Fuel type (Diesel, Petrol, LPG, CNG)          |
| `seller_type`  | Seller type (Individual, Dealer, Trustmark)  |
| `transmission` | Transmission type (Manual, Automatic)         |
| `owner`        | Number of previous owners                       |
| `mileage`      | Mileage in km/l or equivalent                  |
| `engine`       | Engine capacity in CC                           |
| `max_power`    | Maximum power in bhp                            |
| `seats`        | Number of seats                                |
| `selling_price`| Target variable: Price the car is sold at     |

---

## Methodology

1. **Data Preprocessing:**
   - Handled missing values and removed duplicates.
   - Converted categorical variables into numerical form using dictionary mappings.
   - Ensured consistent data types and handled warnings for future pandas compatibility.

2. **Exploratory Data Analysis:**
   - Analyzed unique values and distributions of features.
   - Visualized relationships between features and the target price.

3. **Model Building:**
   - Split data into training and testing sets.
   - Built a **Linear Regression** model to predict car prices.
   - Evaluated model performance with appropriate metrics.

4. **Deployment:**
   - Developed a user-friendly web app using **Streamlit**.
   - Users can input car details interactively to get real-time price predictions with formatted currency output.

---

## How to Run

1. Clone the repository.

2. Create and activate a virtual environment (recommended).

3. Download the dataset from the link above and place it in the `data/` folder as `Cardetails.csv`.

4. Install dependencies:

```bash
pip install -r requirements.txt
