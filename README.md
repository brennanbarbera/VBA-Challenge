# VBA-Challenge

## Overview of Project
In this Project we were tasked with finding the total volume, and the losses/gains of the stock portfolio that was given to us, based on the specific stocks they wanted to check on. Technically, we were also tasked with seeing how refactoring the code in VBA and reduce runtime.
##Analysis and Challenges

### Analysis of time spent running the function
[Time of running through 2017 trackers](https://raw.githubusercontent.com/brennanbarbera/VBA-Challenge/main/Resources/2017%20screenshot.png)
With the original function we designed during the module, the code would run for a little more than half a second to process the data on 2017's trackers. With the Refactored code, the same data was presented but only took a portion of the time at approximately 0.08 seconds.

[Time of running through 2018 trackers](https://raw.githubusercontent.com/brennanbarbera/VBA-Challenge/main/Resources/2018%20ScreenShot.png)
The results from the differences in the original code to the refactored code for the 2018 time period reinforce the case that the refactored code takes only a fraction of the time to process through the data.

## Challenges and Difficulties
The largest obstacle in this challenge was simply making sure that all the variables were input correctly in all cases. Initially There was one variable that was label as plural, but when it was input later in the function it was not. This typo eluded us for a good 5 minutes

## Results

### Conclusions in regards to stock performance between 2017 and 2018
In 2017, many of the options that the client had did very very well. In the following year, very few did well. If they werre invested in order to sell to make money, they should have sold much of their options last year, and only sell ENPH and RUN in 2018. A few on the stocks that were in the red weren't huge losses, so those may not be complete losses at this point. More suggestions could be delivered if more data was on hand and if information about the companies was also on hand.
If the client were trying to support certain companies, perhaps now would be a good time to buy more of many of these stocks, depending on their liquid assets.

### Conclusions in regards to the Module 2 code and the refractored challenge code
The refactored code ran much faster than the original code, the largest difference being that the code did not have to run through a concacenated loop. Whether this is the exact cause is not 100% verified, as we did not change the original code line by line and examine the time differences there. Obviously the advantages to the refactored code are mainly that it runs faster. At this point I could not point out any cons, as the main one that comes to mind is taht maybe the refactored code is harder to read, but comparing the the two, provided both have commments, both are similiarily readable.
