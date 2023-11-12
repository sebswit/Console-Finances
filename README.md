# Console Finances

## About Me
My name is Sebastian Switakowski and im learning to become front-end developer. I'm at the begining of my journey, currently learning basics of JavaScript.
## Overview
Purpose of this task was learn to work on two dimensional array in JavaScript. I've learned to use loop and logic comparsion to scoop highest, lowest and average values. Also I've learned how to compare array elements and find difference between them.

* To find number of months I've used 'arr.length'.
* To find 'Total $' I've used loop starting from first record and adding value until it reaches 86 samples ('arr.lenght').
* To find 'Highets Profit/Highets Loss' I've used same loop and logic comparsion for result ( see lines 112-119).
* To find 'Averange change' I had to compare all records with loop but this time backwards (see line 128-131) that requires starting from second record ( i=1 ) and acumulate 'countOfDifferences' with ++ to have 86 of samples(see line 138).
* To find 'Greatest Increase/Decrease' I've used same loop(backwards) and logic comparsion(lines 158-166).
* To obtain two decimal points in 'Average change' result I've used "parseFloat().toFixed(2)"  (see line 145)
* Example of line 137 "sumOfDifferences += difference" is short of "sumOfDifferences = sumOfDifferences + difference" - concatenation

## Instructions
1. Open 'index.html' in browser.
2. Right-click on a blank page and select 'inspect'.
3. Select tab 'Console'.

In console you'll se folowing lines:
  
 * Financial Analysis 
 * Total Months: 86
 * Total: $38382578
 * Highets Profit: 1170593
 * Highest Loss: -1196225
 * Average Change: -2315.12
 * Greatest Increase in Profits/Losses: month: Feb-2012, amount: 1926159
 * Greatest Decrease in Profits/Losses: month: Sep-2013, amount: -2196167
## Resources
Resources used to create this project can be found at:
[!] https://developer.mozilla.org/;
* https://stackoverflow.com/;
* https://learnprogramming.online/,
* https://www.freecodecamp.org/,
* https://www.codecademy.com
## Copyright
The project has been created for learning purposes and is no copyright on it.  

