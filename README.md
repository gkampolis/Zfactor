# Zfactor 

### Short description
Calculates Z (a factor measuring deviation from ideal behaviour, see below) for a simple hydrocarbon gas (composed entirely of up to three compounds: methane, ethane and propane), according to Standing's correlations.

### Slightly Longer description
User is asked to provide composition values for C1,C2 & C3 and then Z
is calculated for T(50-200F) and P(14.7 and 100-2000 psia). Main output 
is a plot of Z vs P for four different T.
Secondary output is a table of Z values for the various P & T. Currently
the table is not displayed by default, however this can be changed by
removing the percent sign "%" from the last line of the script's
.m file. Furthermore, loops are avoided.

The script is written in such a way to be easily modifiable (for example different ranges for pressure & temperature, or adding more compounds).

### What is Z?
Z is a factor that quantifies how a real gas behaves differently that an ideal gas. It's known as the gas deviation factor or the compression factor. It's a very usefull property as it allows the generalisation of ideal gas law in thermodynamics: PV=n**Z**RT.

It's defined as the ratio of the molar volume of a gas to the molar volume of an ideal gas at the same temperature and pressure. See more at [Wikipedia](https://en.wikipedia.org/wiki/Compressibility_factor "Wikipedia's page for Z").
