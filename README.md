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

## Design:
A regression model analysis was conducted that encompasses many features and among them the apartment's price. To gather apartment data Aqar.com has been scraped, one of the top and most visited online real estate agencies in KSA. I utilized several regression models and tested for the best fit; to ensure the best predictor tool.

## Algorithms:

* Clean: The dataset had duplicate observations, NaN values, and spaces in between the categorical features, so we used pandas library to prepare the data for the regression model.

* Preprocessing:Used transformation methods in order to apply to standardize the values at an equivalent scale and to linearize some of the features that are not linear.

# Models
<img width="433" alt="image" src="https://user-images.githubusercontent.com/89771282/145726206-b3b868e2-0254-404c-906a-d081ed773723.png">


<img width="175" alt="image" src="https://user-images.githubusercontent.com/89771282/145726233-c6428381-c4e5-403c-8421-d81894205a08.png">


<img width="164" alt="image" src="https://user-images.githubusercontent.com/89771282/145726266-0e488622-0dbf-4363-ab51-4a6283f40cdd.png">

<img width="440" alt="image" src="https://user-images.githubusercontent.com/89771282/145726284-5e4c743e-37ff-4538-903e-cabb3fb88b4e.png">

<img width="180" alt="image" src="https://user-images.githubusercontent.com/89771282/145726294-da6b4f39-a9a2-4788-9201-4fa27db077e4.png">

<img width="175" alt="image" src="https://user-images.githubusercontent.com/89771282/145726233-c6428381-c4e5-403c-8421-d81894205a08.png">


<img width="164" alt="image" src="https://user-images.githubusercontent.com/89771282/145726266-0e488622-0dbf-4363-ab51-4a6283f40cdd.png">

<img width="440" alt="image" src="https://user-images.githubusercontent.com/89771282/145726284-5e4c743e-37ff-4538-903e-cabb3fb88b4e.png">


<img width="479" alt="image" src="https://user-images.githubusercontent.com/89771282/145726326-6f3a0b1d-5678-4eab-a2b8-084b316711f3.png">


<img width="175" alt="image" src="https://user-images.githubusercontent.com/89771282/145726341-5d0af433-b086-4f5f-9d76-e61041af8959.png">

<img width="440" alt="image" src="https://user-images.githubusercontent.com/89771282/145726347-14c4ec21-a9aa-4e2c-b1c5-e9eba427f380.png">


<img width="212" alt="image" src="https://user-images.githubusercontent.com/89771282/145726474-31936cf5-fc22-4ec3-89d5-f60f06738b1c.png">


<img width="451" alt="image" src="https://user-images.githubusercontent.com/89771282/145726465-19f824d6-3c14-42c6-b85d-0d1ef644b9d0.png">




## Tools:

Language: Python:

* Data Scraping libraries: Selenium

* EDA Libraries: Pandas, numpy, seaborn, matplotlib، Missingno

* Model Building Libraries: sklearn and Model Testing libraries sklearn
 
 
