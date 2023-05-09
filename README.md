# energy_data_analysis
It has been well documented that there is a positive relationship between energy demand and GDP. I became interested in exploring if this positive relationship translates to energy supply and GPD when I was studying Data Science with Python and I was analyzing these datasets for a similar task.

In this analysis I used Pandas, SciPy, and Matplotlib to clean, merge, analyze, and plot data and results from two datasets: energy supply and GDP. The sources of these datasets are the [United Nations](https://unstats.un.org/unsd/energystats/data/) for the former and the [World Bank](https://data.worldbank.org/) for the latter.

I used Pandas to clean the datasets removing unnecessary rows and columns, revising and formatting names of countries in order to merge the datasets, and computing the GDP per capita among other tasks. This analysis was done for the year of 2013 since the energy supply dataset only contained data for that year. I estimated the Pearson correlation coefficients (PCC) for both energy supply and energy supply per capita and plotted the relationships for each.

The obtained PCC for energy supply per capita and energy supply are 0.553 and 0.881 respectively. As expected, these results suggest that the known positive relationship between energy demand and GDP is also reflected in a positive correlation between energy supply and GDP. This makes sense since one would expect that as GDP increases, the increase in energy demand would drive an increase in energy supply. The higher positive correlation of energy supply in comparison to energy supply per capita suggests that the relationship between energy supply and economic productivity may not be as strong at the individual level. This observation can also be clearly identified in the plots. This may be due to differences in population sizes, culture and customs around energy usage, and differences in economic development. However, more detailed analysis is needed to identify causes.

This repository includes the present README file and a Jupyter Notebook with the analysis and results.
