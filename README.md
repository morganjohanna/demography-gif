# Demography GIF
A visual representation of how fertility rates, life expectancy, and population have changed around the world 1960-2013, modeled on [Hans Rosling's presentation on BBC4](https://youtu.be/jbkSRLYSojo).

Data were provided by instructors, originally from Gapminder (free data from World Bank via gapminder.org, cc-by license).

This repo includes only the code and the final graphic, no data or individual plot files. It was the first data project I completed with Python and it took me around 1 day at the time.

## Design and Implementation
Data are imported, cleaned, and tidied appropriately from 4 sources into a single, tidy dataframe. A scatterplot is created and exported for each year using a for loop; another is used to append them into a single .gif using imagio.

## Next
This was fun to make (with a very satisfying visual output), but the data were pretty extensively explored during the course. I'd be interested to use a similar technique to see how age and sex distributions change over time, especially tying sex distributions to fertility rates to attempt to visualize female infanticide.