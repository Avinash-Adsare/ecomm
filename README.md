# eCommerce Data Analyst

## Project Overview
This project is an **eCommerce Data Analyst** application that analyzes sales data from an eCommerce platform. The application provides insights into customer demographics, purchasing behavior, and product sales trends. It is deployed using **Streamlit**.

**Streamlit App URL:** [eCommerce Data Analyst](https://avinashecomm.streamlit.app/)

## Features
- Data visualization using **Matplotlib** and **Seaborn**.
- Data analysis using **Pandas** and **NumPy**.
- Insights into customer behavior based on **age, gender, occupation, and city category**.
- Purchase trend analysis across different product categories.
- Interactive data exploration with Streamlit.

## Technologies Used
- **Python**
- **Streamlit** (for deployment and UI)
- **Pandas** (for data manipulation)
- **NumPy** (for numerical analysis)
- **Matplotlib** & **Seaborn** (for data visualization)
- **OpenPyXL** (for handling Excel files)

## Dataset
The analysis is based on an **Excel dataset** containing 272 records and 10 columns:
- **User_ID**: Unique identifier for users.
- **Product_ID**: Unique identifier for products.
- **Gender**: Gender of the user.
- **Age**: Age group of the user.
- **Occupation**: Encoded occupation category.
- **City_Category**: City classification (A, B, or C).
- **Stay_In_Current_City_Years**: Duration of stay in the current city.
- **Marital_Status**: Marital status of the user (0 = Single, 1 = Married).
- **Product_Category**: Encoded product category.
- **Purchase**: Purchase amount spent by the user.

### Sample Dataset
| User_ID | Product_ID | Gender | Age | Occupation | City_Category | Stay_In_Current_City_Years | Marital_Status | Product_Category | Purchase |
|---------|-----------|--------|-----|------------|--------------|----------------------------|---------------|-----------------|----------|
| 1000001 | P00069042 | F | 0-17 | 10 | A | 2 | 0 | 3 | 8370 |
| 1000001 | P00248942 | F | 0-17 | 10 | A | 2 | 0 | 1 | 15200 |
| 1000001 | P00087842 | F | 0-17 | 10 | A | 2 | 0 | 12 | 1422 |
| 1000001 | P00085442 | F | 0-17 | 10 | A | 2 | 0 | 12 | 1057 |
| 1000002 | P00285442 | M | 55+ | 16 | C | 4+ | 0 | 8 | 7969 |
| 1000003 | P00193542 | M | 26-35 | 15 | A | 3 | 0 | 1 | 15227 |
| 1000004 | P00184942 | M | 46-50 | 7 | B | 2 | 1 | 1 | 19215 |
| 1000004 | P00346142 | M | 46-50 | 7 | B | 2 | 1 | 1 | 15854 |
| 1000004 | P0097242 | M | 46-50 | 7 | B | 2 | 1 | 1 | 15686 |
| 1000005 | P00274942 | M | 26-35 | 20 | A | 1 | 1 | 8 | 7871 |

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Avinash-Adsare/ecomm.git
   ```
2. Navigate to the project directory:
   ```sh
   cd ecomm
   ```
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## Usage
- The app provides an interactive dashboard to explore **eCommerce sales trends**.
- Users can analyze purchases based on different demographics.
- Visualizations help in understanding key buying patterns.

## Repository Structure
```
├── ecomm/
│   ├── app.py                 # Main Streamlit app script
│   ├── data/                  # Directory for dataset
│   ├── requirements.txt       # List of dependencies
│   ├── README.md              # Project documentation
```

## Future Improvements
- Add more **filters** for customized data analysis.
- Implement **predictive analytics** for sales forecasting.
- Integrate additional **datasets** for deeper insights.

## Author
- **Avinash Adsare**  
  [GitHub](https://github.com/Avinash-Adsare)  
  [LinkedIn](https://www.linkedin.com/in/avinash-adsare-6845421b7/)

---
**Note**: The dataset used in this project is for analysis purposes only and may not reflect real-world transactions.

