# ADS-B_Flight_Data_Datascraping_and_preprocessing_and_EDA
This notebook helps to scrape the data and process the json format to the csv 
**You can scrape or parse only the historical flight data**
**For educational purpose only**
Steps:
1. You can choose the flight which you want to do EDA
2.Search for the specific flight number on the search bar at Flight radar24 
![image](https://user-images.githubusercontent.com/55647096/202170103-95117014-80ef-440d-baea-df94b0c1d26b.png)
3.Then select specific flight from the history list
![image](https://user-images.githubusercontent.com/55647096/202168478-11c274af-67bd-47da-b332-afbeb77fd007.png)
4.Then click the play button which will direct you to the new tab
5. At the address bar you can find the id as shown in the fig
![image](https://user-images.githubusercontent.com/55647096/202167786-2b7417ff-2b85-456b-a4ff-b373236192ff.png)
6. Now paste the id at the end of this link and give it a try by opening on new tab 
"https://api.flightradar24.com/common/v1/flight-playback.json?flightId= YOUR_FLIGHT_ID_HERE"
7.Now you can get the json format like this 
![image](https://user-images.githubusercontent.com/55647096/202169078-7f8ebfa1-b0e5-402e-aae6-d81af4245fa2.png)
8.Need to copy all the json maually and use this link to generate json format file https://json-generator.com/\
9. You are good to go use the notebook and follow the guidelines there to process json and EDA on it.
