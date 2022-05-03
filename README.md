# stocks-analysis
### Overview:
  The purpose of this project was to analyze green energy stocks to help educate customers on the best green stocks to invest in. 
### Results
![2017](https://github.com/JTGonzaga/stocks-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![2018](https://github.com/JTGonzaga/stocks-analysis/blob/main/Resources/VBA_Challenge_2018.png)
  As we can see, the market did far better overall in 2017 versus 2018. The only two stocks that posted a positive return in 2018 were ENPH and RUN. If I were to invest in any of the green stocks displayed, I would heavily consider those two over any others. 
  
  Original execution times:
  
 ![first_2017](https://github.com/JTGonzaga/stocks-analysis/blob/main/Resources/first_2017.png)
 ![first_2018](https://github.com/JTGonzaga/stocks-analysis/blob/main/Resources/first_2018.png)
 
 Refactored execution times:
 
 ![new_2017](https://github.com/JTGonzaga/stocks-analysis/blob/main/Resources/2017_timer.png)
 ![new_2018](https://github.com/JTGonzaga/stocks-analysis/blob/main/Resources/2018_timer.png)
 
  Unsuprisingly, the refactored code ran in about 1/6 of the time versus the original code.
  
 ### Summary
  There are a few advantages and disadvantages to refactoring the code. A definitive advantage is the amount of time to run the code and produce results. The results were given back in less than a second in both instances, but for a larger dataset this change would be exponentially different. Disadvantages to refactoring the code is that it takes longer to write the code. If someting needs to be done quickly a few times, it might be a better decision to write the code to be less efficient to development time.
  Applied to the original VBA script, the time to recieve results was signifigantly faster but the challenge did take longer to refactor.
