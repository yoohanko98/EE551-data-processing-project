# EE551-data-processing-project
# UN energy data analysis
[data source](http://data.un.org/_Docs/SYB/CSV/SYB62_263_201904_Production,%20Trade%20and%20Supply%20of%20Energy.csv)

The data linked above contains all the bulk energy consumption categories for each of the world’s regions and countries. The data begins in 1990 and has data-points every 5 years and more frequent data from recent years. A data cleaning step using regex was needed in order to convert the numbers into a format the python interpreter was able to convert into integers.

The goal of this project is to clean and format this UN-Energy dataset and plot [Supply per capita (gigajoules)] data from each identified area. By plotting different regions over time, we can visualize trends in power usage around the world over the past three decades. By plotting all these regions on the same plot, we can compare the energy usage of populations around the world. 

Hypotheses:
- Energy usage continually increases in the entire world over time
- Energy usage growth will be driven by developing countries, while energy usage in developed coutries is already high, but growing slowly