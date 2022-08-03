
# Are California’s farmers planting different crops during the drought?
For this two-week class project, I want to see whether farmers are ripping up certain crops in favor of ones that use less water. To find out, I downloaded PDFs of the 2010-2020 annual crop reports from Tulare County Agricultural Commissioner's Office. I then compiled the data into a spreadsheet using Tabula and analyzed it using Panda. I used 19 commodities for the Panda analysis, but I later realized while doing the visualization that 19 crops might be too confusing for the readers, so I cut it down to 6 crops. Through the analysis, I found out things such as: the crop with the most productive value and the most productive year of each crop. 
# My data collection process
I downloaded the 2010-2020 annual crop report from [Tulare County Agricultural Commissioner's Office](https://agcomm.co.tulare.ca.us/standards-and-exclusion/crop-reports1/). I then loaded the data into Panda and analyzed it. I used Altair to visualize my results in Panda. I also used Datawrapper and Adobe Illustrator for my visualizations.  
# What my repository contains
## Jupyter notebook
* Tulare Ag.ipynb: data analysis on data from [Tulare County Agricultural Commissioner's Office](https://agcomm.co.tulare.ca.us/standards-and-exclusion/crop-reports1/)
* crops.ipynb: analysis to figure out the most productive of the 6 crops; visualization of the data using Altair
* costs.ipynb: analysis of the change in unit price of the 6 crops from 2010 to 2020
## Data
* Tulare ag production 2010-2020.csv: the annual crops report from 2010-2020
* crops.csv: cleaned data created after Panda analysis; focused on the 6 crops
* Crops unit cost: the change in unit price of the 6 crops from 2010 to 2020
## Charts
* table of the 10 most water-intensive crops in California
* small multiples of production change of the 6 crops
* stacked column chart depicting change in unit price of 6 crops from 2010 to 2020
# What I learned
I learned to use Bulma to enhance the visualization of my webpage. I learned to use Tabula to extract tables from PDFs. I also became more familiar with other tools I've learned in this class.
# Future improvements
I would like to learn to use D3 and other tools to make all of my charts interactive 