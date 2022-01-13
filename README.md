# All-Stocks-Analysis-Refactored
Challenge 2
#**Project to compare performance of shares 2017 and 2018.**
The purpose of the project is to help Steve make the best decision with the best tools, so a comparison is presented between two projects which, despite generating the same results, one of them may be more efficient in time, space and the steps to make the decisions that best suit Steve.

The results found were the following:

For 2017 the shares with the best profit are DQ with an 199.4% return. However, however, the total daily volume is the smallest, there was only one share that fell -7.2%. However, the stock with the highest yield is the one with the lowest volume, so other types of decisions must be made in order to invest in 2019.

****![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/2017.png)

For 2018, the stocks with the best performance were tickers ENPH and RUN, and in turn, they were the ones that reported the highest daily volume.

****![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/2018_original.png)

In this sense, one of the advantages of the project is that results can be obtained from both years with the macro carried out and in less time.

The execution times for this project were as follows:

•The 2018 runtime with the refactor script is 0.5371 seconds.

****![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/2017.png)

•Runtime 2017 with edited script is 0.3164 seconds.

****![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/2018.png)

  **The difference between the original script and the edit script**

•One of the improvements in the code is that you can do analysis of both years without having to do a code per year, it asks the question: What year would you like to run the analysis on? And the year to buy is chosen.

![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/Year.png)

An index "tickerIndex" is created which manages to add each type of index, and as a principle, it is equal to zero since each time it reads a different ticker, it will add the volume of each ticker again.

![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/INDEX.png)

Now with each LOOP it is indicated that each time it reads a row of tickers, it will add the ones that are the same, if it becomes different, it will add again until the end of the Excel table.

![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/LOOP.png)

To finish with the analysis of the actions, their return in relation to the last year is calculated with the following code.

![This is an image](https://github.com/RH015/All-Stocks-Analysis-Refactored/blob/main/Return.png)



Finally, it can be said that the advantages of improving the code are the following:

• Improve the time in which the code runs.

• You can choose the year to analyze without having to make a code for each file.










