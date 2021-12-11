# Aqar.com: Price Prediction of Rent Apartments in Riyadh

Hatim Alshehri

## Abstract:
[Aqar](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjtpu7c3Nz0AhXElNUKHaHKClcYABAAGgJ3cw&ae=2&ohost=www.google.com&cid=CAESQeD2Nbsq4c-_YK6Cc3y6tsvc33W-lwRchB7NisN0xw598oFkCCbo5xxSOnRU4MOb6WYl187RVuSlEi09YSv0UxOg&sig=AOD64_0c67nn2GY2DfEk25nRRvTK1LlE5Q&q&adurl&ved=2ahUKEwjb4-bc3Nz0AhWVAWMBHcdIAfMQ0Qx6BAgCEAE) is a website specialized in Saudi real estate. The project's goal is to extracting data,
for rent apartments in the Riyadh region from Aqar website,
and generate a regression model to predict the prices of apartments.


## Data:
Data scraped from [Aqar](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjtpu7c3Nz0AhXElNUKHaHKClcYABAAGgJ3cw&ae=2&ohost=www.google.com&cid=CAESQeD2Nbsq4c-_YK6Cc3y6tsvc33W-lwRchB7NisN0xw598oFkCCbo5xxSOnRU4MOb6WYl187RVuSlEi09YSv0UxOg&sig=AOD64_0c67nn2GY2DfEk25nRRvTK1LlE5Q&q&adurl&ved=2ahUKEwjb4-bc3Nz0AhWVAWMBHcdIAfMQ0Qx6BAgCEAE) website using Selenium tool.

<br />

**The data scraped is described by 14 features as follows:**
<br />
* Field Description:
<br />

| Field Name  | Description |
| ----------- | ----------- |
| District    |  Apartment districts/neighborhoods             |
| Category    | (e.g., snigal/fmaily)                          |
| Bedrooms    | Number of bedrooms                             |
| Livingrooms | Number of Livingrooms                          |
| Bathrooms   | Number of Bathrooms                            |
| Furnished   | Does apartment has Furnished (e.g., yes/no)    |
| Kitchen     | Does apartment has Kitchen (e.g., yes/no)      |
| Garage      | Does apartment has Kitchen (e.g., yes/no)      |
| Elevator    | Does apartment has Elevator (e.g., yes/no)     |
| AC          | Does apartment has AC (e.g., yes/no)           |
| Region      | Apartment region in Riyadh (e.g., west/north)  |
| floor_number|    Apartment floor number                      |
| AGE         |    Property age                                |
| Price       | Apartment rent price per year                  |

 

## Tools:

Language: Python:

* Data Scraping libraries: Selenium

* EDA Libraries: Pandas, numpy, seaborn, matplotlib، Missingno

* Model Building Libraries: sklearn and Model Testing libraries sklearn



 
 
 
