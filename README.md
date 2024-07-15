# House-Price-Prediction-System
House price prediction in Bangalore is crucial for informed investment decisions, helping buyers and investors navigate the dynamic real estate market. Accurate predictions support urban planning and policy-making, ensuring sustainable development in one of India's fastest-growing cities.House prices in Bangalore are growing rapidly, driven by the city's booming IT industry and increasing demand for residential properties. The real estate market has seen significant appreciation rates, making it a hotspot for both investors and homebuyers.In this project, we aim to predict the prices of houses in Bengaluru.

# Dataset:  
 https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data 
The dataset, downloaded from Kaggle, contains 13,322 rows and 9 columns.

# Plan of Action

- **Import Libraries**
- **Data Cleaning**
- **Feature Engineering**
- **Dimensionality Reduction**
- **Outlier Detection**
- **One-Hot Encoding**
- **Model Building**
  - Cross-validation model
  - Find the best model using GridSearchCV
  - Test the model on a sample of properties
- **Export the Model**

### Column Information and Relevance for Price Prediction

**Area Type:**
The 'Area Type' column categorizes properties into Built-up Area, Carpet Area, Plot Area, and Super built-up Area. While it provides classification, the actual area size (total_sqft) more directly influences house prices than the type of area.

**Availability:**
The 'Availability' column indicates when properties will be available, with entries like specific dates or statuses (e.g., Immediate Possession). While important for scheduling, availability status does not significantly affect property intrinsic value or pricing.

**Location:**
The 'Location' column lists various localities in Bengaluru, influencing house prices due to varying demand and infrastructure. With 1305 unique values, location is crucial for predicting property values.

**Size:**
The 'Size' column specifies the number of bedrooms (e.g., 1 BHK to 43 Bedroom). It directly indicates property size and significantly impacts house prices, making it essential for accurate price prediction.

**Society:**
The 'Society' column lists residential community names. While providing specific details, it generally has less impact on house prices compared to broader factors like location and property size.

**Total Square Feet (total_sqft):**
The 'total_sqft' column denotes property size in square feet. Crucial for price prediction, it quantifies property area, a key determinant of property value in Bengaluru's real estate market.

**Bath:**
The 'bath' column indicates the number of bathrooms in each property. Significant for property value, more bathrooms typically enhance convenience and luxury, influencing pricing decisions.

**Balcony:**
The 'balcony' column counts the number of balconies in each property. Important for livability and attractiveness, properties with more balconies often command higher prices due to enhanced outdoor space and views.

**Price:**
The 'price' column represents the sale price of properties in Bengaluru, directly reflecting their financial value and serving as the primary target for price prediction models.







