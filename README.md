# Stock-Analysis
## Overview 
### Purpose 
The purpose of this challenge was to refactor the code to allow Steve to analyze a variety of stocks effeciently. More specifically, it wil allow Steve to analyze the stocks over different periods of time in order to determine the rate of return. This will allow him to quickly understand whether or not his parents are investing in the correct stock. 

### Background
Steve's parents wanted to in DAQO, so they came to him to do the analysis in order to determine if they were making the correct choice. To do this we built him a macro in order to efficiently analyze all the data he had. The first code allowed Steve to only analyze one stock at a time. Which would prove to become extremely ineffecient as the number of stocks in the market would increase. After analyzing the DAQO, Steve recognized that the rate of return was -63% and then wanted to look at the other stocks in the market. The second code allowed steve to analyze the entire stock market over different time periods and compare the rates of return. This would be more effecient then analyzing each ticker. However, we wanted to optimize the code in order to save Steve as much time as possible with the same accuracy.

## Results
### Data 

***Timer Data***

The original all stock analysis 2017 took 0.5429688 seconds and the 2018 took 0.5351562 seconds. The refactored all stock analysis 2017 toook 0.1132812 seconds and the 2018 took 0.1171875 seconds. The refactored analysis was 5 times faster at analyzing the stock market.

All Stocks Analysis 2017
<img width="424" alt="All Stocks Analysis 2017 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334782-0aaeab00-f05f-11ea-92ea-c74bcd822f09.png">

All Stocks Analysis 2018
<img width="420" alt="All Stocks Analysis 2018 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334836-8c9ed400-f05f-11ea-80a6-f01b175f421a.png">

All Stocks Analysis Refactored 2017
<img width="423" alt="All Stocks Analysis Refactored 2017 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334750-d5a25880-f05e-11ea-94e3-e3b80c43f388.png">

All Stocks Analysis Refactored 2018
<img width="421" alt="All Stocks Analysis Refactored 2018 - Timer Data" src="https://user-images.githubusercontent.com/68453460/92334765-f10d6380-f05e-11ea-99c2-4c8ab9d4e54e.png">

***Stock Market Performance***

The DQ stock that Steve's parents want to invest had a negative return in 2018, however had a positive return in 2017. Over both years, it would have a positive return of 136%. The stock performance shows  ENPH and RUN stock had a postive return in both 2017 and 2018. In 2018, all stocks had a decreased rate of return compared to 2017. Additionally, the data shows that TERP had a negative return in both 2017 and 2018. 

2017 All Stocks Analysis 
<img width="267" alt="All Stocks Analysis Refactored 2017" src="https://user-images.githubusercontent.com/68453460/92334806-3cc00d00-f05f-11ea-9a14-512c55f9f8fb.png">

2018 All Stocks Analysis
<img width="273" alt="All Stocks Analysis Refactored 2018 - Return" src="https://user-images.githubusercontent.com/68453460/92334808-3df13a00-f05f-11ea-98ce-2e317331252a.png">

### Analysis
From the data above we can conclude that refactoring the data was beneficial in saving Steve time when doing an all stock Analysis. The data also shows Steve that DQ is not the ideal stock for his parents to invest in. The best stock to invest in based on both 2017 and 2018 data is the ENPH and then RUN. The worst stock to invest in is TERP as it had a negative return both years. 

## Summary
### Advantages & Disadvantages of Refactoring Code in General
There are multiple advantages to refactoring code:
1. Increase the speed it takes to populate data.
2. It can make the code cleaner and easier to understand. 
3. Make the code more simple and improves readability. This can make it easier to create a pseudocode to use for similar types of analysis. In the case of steve, he can use it to analyze different stock markets. 
4. Improve the maintainability. For this refactored code in particular, it can used for different stock markets. It would just require minor recoding for it to work for other stock markets. The code is also designed to work for Steve to continue to add data from previous or future years. 

Even with these advantages, there are disadvantages to refactoring code:
1. Refactoring can take time and create more bugs than were present before refactoring. 
2. It can also be risky if someone else is trying refactor the code. If the code was built so it is simple to understand, it can be both time consuming and cause many errors. 

### Advantages & Disadvantages of Refactoring Code in VBA
The advantage to refactoring code in VBA specifically is that it increases the speed in populating the data, improves the readility and and maintainability. As mentioned above, now Steve is able to use this similar pseudocode to analyze other stock markets and just make or request minor changes to the code. This makes his analysis efficient for all clients, not just his parents. 

The disadvantage when refactoring code is that it creates more bugs. When refactoring the data set for Steve, there were many bugs that were found and it was much more time consuming to refactor the code. It was much more complicated to build the code to ensure that it was readible and easy to maintain. 
