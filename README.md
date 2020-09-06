# Stock-Analysis
## Overview 
### Purpose 
The purpose of this challenge was to refactor the code to allow Steve to analyze a variety of stocks effeciently. More specifically, it wil allow Steve to analyze the stocks over different periods of time in order to determine the rate of return. This will allow him to quickly understand whether or not his parents are investing in the correct stock. 

### Background
Steve's parents wanted to in DAQO, so they came to him to do the analysis in order to determine if they were making the correct choice. To do this we built him a macro in order to efficiently analyze all the data he had. The first code allowed Steve to only analyze one stock at a time. Which would prove to become extremely ineffecient as the number of stocks in the market would increase. After analyzing the DAQO, Steve recognized that the rate of return was -63% and then wanted to look at the other stocks in the market. The second code allowed steve to analyze the entire stock market over different time periods and compare the rates of return. This would be more effecient then analyzing each ticker. However, we wanted to optimize the code in order to save Steve as much time as possible with the same accuracy.

## Results
### Data 
The original all stock analysis 2017 took 0.5429688 seconds and the 2018 took 0.5351562 seconds. The refactored all stock analysis 2017 toook 0.1132812 seconds and the 2018 took 0.1171875 seconds. The refactored analysis was 5 times faster at analyzing the stock market.

### Timer Data
All Stocks Analysis 2017
<img width="424" alt="All Stocks Analysis 2017 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334782-0aaeab00-f05f-11ea-92ea-c74bcd822f09.png">

All Stocks Analysis 2018
<img width="420" alt="All Stocks Analysis 2018 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334836-8c9ed400-f05f-11ea-80a6-f01b175f421a.png">

All Stocks Analysis Refactored 2017
<img width="423" alt="All Stocks Analysis Refactored 2017 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334750-d5a25880-f05e-11ea-94e3-e3b80c43f388.png">

All Stocks Analysis Refactored 2018
<img width="421" alt="All Stocks Analysis Refactored 2018 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334765-f10d6380-f05e-11ea-99c2-4c8ab9d4e54e.png">

The DQ stock that Steve's parents want to invest had a negative return in 2018, however had a positive return in 2017. Over both years, it would have a positive return of 136%. The stock performance shows  ENPH and RUN stock had a postive return in both 2017 and 2018.In 2018, all stocks had a decreased rate of return compared to 2017. 

## Stock Market Performance
2017 All Stocks Analysis 
<img width="267" alt="All Stocks Analysis Refactored 2017" src="https://user-images.githubusercontent.com/68453460/92334806-3cc00d00-f05f-11ea-9a14-512c55f9f8fb.png">

2018 All Stocks Analysis
<img width="273" alt="All Stocks Analysis Refactored 2018 - Return" src="https://user-images.githubusercontent.com/68453460/92334808-3df13a00-f05f-11ea-98ce-2e317331252a.png">
