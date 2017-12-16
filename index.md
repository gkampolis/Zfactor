# Short Description
Zscipt calculates calculates Z for a simple gas (composed entirely of up to three compounds: methane, ethane and propane), for various Pressures and Temperatures, according to Standing's correlations. 

# Somewhat Longer Description

User is asked to provide composition values for C1 (methane), C2 (Ethane) & C3 (propane) and then Z is calculated for a range of temperatures (50-200 F) and pressures (14.7 and 100,200,300...2000 psia). The main output is a plot of Z vs P for four different T (50/100/150/200 F). Secondary output is a table of Z values for the various P & T (see the "Notes" section below on how to enable this). Calculations are made according to Standing's correlations.

***

#### Notes
- Currently the table is not displayed by default, however this can be changed by removing the percent sign "%" from the last line of the script's .m file.
- Oilfield units are assumed, i.e. psia for pressure and Fahrenheit for temperature.
- Composition input should be in decimal form -- do not assume a percent sign (see below). Composition essentially adds up to 1 and not 100.


#### Example: Composition Input

 - Correct: 0.85
 - *False: 85*
 - *False: 85 %*

***

## Contact

Drop me a line on twitter: [@gkampolis](http://twitter.com/gkampolis).
Or find out more on my [site](http://www.gkampolis.com).

