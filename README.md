#  Car Dealers Performance Analysis – Exploratory Data Analysis (EDA)

##  Author

**Moses Precious**
Data Analyst | Excel · Power BI · EDA

#  Project Objective
This Project is an end-to-end Exploratory Data Analysis of a car sales dataset spanning **January 2022 to December 2023**, examining dealer performance, regional revenue, customer income behaviour, product preferences, and sales trends across 30 car brands and 7 regions.

-----

## 📁 Dataset Overview
This project uses a dataset retrieved from Kaggle to analyze car sales trends across multiple regions and brands. The dataset has been imported into Microsoft Excel for exploration, visualization, and reporting.

Dataset details 
The data contains 23,906 rows, 17 column, the data ranges from January 2022 - December 2023, About 30 car brands were covered and this dataset contains 7 regions 


## Key Statistics

|Metric                    |Value         |
|--------------------------|--------------|
|Total Cars Sold           |23,906        |
|Total Revenue             |$671,525,465  |
|Average Sale Price        |$28,090       |
|Median Sale Price         |$23,000       |
|Min Sale Price            |$1,200        |
|Max Sale Price            |$85,800       |
|Avg Customer Annual Income|$830,840      |
|Auto Transmission Sales   |12,571 (52.6%)|
|Manual Transmission Sales |11,335 (47.4%)|

-----

## Workbook Sheets

|Sheet                              |Description                                                    |
|-----------------------------------|---------------------------------------------------------------|
|**Car Sales.xlsx - car_data**      |Original raw dataset (23,906 rows × 16 columns)                |
|**Working Sheet**                  |Cleaned dataset with added `Income Range` classification column|
|**DASHBOARD**                      |Car Dealers Performance Analysis visual dashboard              |
|**Net Revenue**                    |Pivot — total revenue per dealership                           |
|**Income vs purchasing power**     |Avg car price by customer income bracket                       |
|**Sales Per car dealer**           |Revenue breakdown per individual dealer                        |
|**Money spent on cars per region** |Total spend by dealer region                                   |
|**Sheet6**                         |Transmission type count (Auto vs Manual)                       |
|**Top three best performing deale**|Monthly revenue for top 3 dealers                              |

-----

##  EDA Areas Explored

### 1.  Sales Trend Analysis

- Monthly and yearly sales performance across 2022 and 2023
- Identification of peak and slow sales periods

### 2.  Dealer Performance

- Revenue ranking across **28+ dealerships**
- Top 3 best-performing dealers tracked monthly
- Net revenue contribution per dealer

### 3.  Regional Analysis

- Total sales spend across **7 regions:** Aurora, Austin, Greenville, Janesville, Middletown, Pasco, Scottsdale
- Identification of highest and lowest revenue-generating regions

### 4.  Income vs Purchasing Power

- Customer segmentation into **3 income brackets:** Lower, Middle, Upper Income
- Average car price per income group to understand purchasing behaviour
- Finding: All income groups show similar average spend (~$27K–$28K)

### 5.  Product & Feature Analysis

- **30 car brands** including Ford, Toyota, BMW, Mercedes-B, Audi, Porsche and more
- **5 body styles:** SUV, Sedan, Passenger, Hatchback, Hardtop
- **2 engine types:** Double Overhead Camshaft (DOHC) & Overhead Camshaft (OHC)
- **2 transmission types:** Auto (52.6%) vs Manual (47.4%)
- **3 color options:** Black, Red, Pale White

### 6.  Customer Demographics

- Gender distribution of buyers
- Annual income range: $10,080 – $11,200,000
- Income segmentation and its influence on car choice

-----

##  Key Insights

- Total revenue crossed **$671M** across just 2 years, showing a strong sales volume
- **Auto transmission** is slightly more popular than Manual (52.6% vs 47.4%)
- Customer income level has **minimal impact** on average car price — all brackets spend around $27K–$28K
- Regional spending varies significantly — Austin generated notably higher revenue
- The top 3 dealers consistently outperform others month over month

-----

##  Tools Used

- **Microsoft Excel** – Data cleaning, pivot tables, and working sheet preparation
- **Microsoft EXCEL** – Interactive dashboard (Car Dealers Performance Analysis)
- **Power Query** – Data transformation and income range classification
- **DAX** – KPI measures and calculated columns

-----

##  How to Use

1. Open `Car_Sales_xlsx_-_car_data.xlsx` in Excel or Power BI
1. Start with the **Working Sheet** for the fully cleaned dataset
1. Explore the pivot sheets for pre-summarized analysis
1. Open the **DASHBOARD** sheet for the full visual report
1. Use slicers (Year, Dealer, Region) to interact with the dashboard

-----

## 📄 License

This project is for portfolio and educational purposes on
