# Supply-Chain-Shipment-Price-Data-Analysis

Exploratory data analysis has been performed using Python - Pandas, Matplotlib and Seaborn libraries.

### Data Cleaning and Manipulation

* Data cleaning and manipulation were done on **7000+** records of data.
* Dropped **Item Description** and **Molecule/Test Type** columns as they were not necessary for the analysis. 
* Other columns could have also been dropped so that the dataset size will be reduced and it will be easier for processing.
* Filtered rows from **Weight (Kilograms)** and **Freight Cost (USD)** columns which had object datatype.
* Changed datatypes of **Weight (Kilograms)**, **Freight Cost (USD)**, **Scheduled Delivery Date**, **Delivered to Client Date** and **Delivery Recorded Date** columns.
* Analysis and visualization were executed to present key insights on freight cost based on the country, shipment mode and manufacturing site.

### Key Insights 
* Total orders: 5572
* Total orderlines: 6175
* Total projects: 130
* Total freight cost $68687760.27
* Nigeria, Zambia and Côte d'Ivoire are the top 3 countries based on Freight Cost (USD).
* Sierra Leone, Angola and Mali are the bottom 3 Countries based on Freight Cost (USD).
* Based on Shipment mode, the freight cost was maximum for Air, followed by Truck, Air Charter and Ocean.
* Top 3 Manufacturing Site by Freight Cost:Aurobindo Unit III, India, Mylan (formerly Matrix) Nashik and Hetero Unit III Hyderabad IN.


![image](https://github.com/ritusantra/portfolio/blob/main/images/Shipment.png)
