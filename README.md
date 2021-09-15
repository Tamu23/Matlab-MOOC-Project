# Matlab-MOOC-Project
Final Project for Matlab programming MOOC on Coursera (Vanderbilt U)

The task is to create a Matlab app with various controls that visualizes Covid Data present in the accompanying data file.
OOP basics and programming skills are being tested. Certain requirements for the app are mentioned on the project submission web page of the MOOC.
Open 'Covidapp_snip.png' image file for a look at the app GUI.
Many of the features/requirements are as follows:
- A Country list box. The first entry is 'Global' and it displays the total data of all countries. This data is not provided seperately in the data file, and has been calculated in the app.
- A State/Province list box. It changes items with change in country selection.
- A radio button selection to choose to display cases, deaths, or both. If both are to be displayed, deaths are displayed according to a y-axis on the right side.
- A radio button selection to choose to display cumulative or daily data display. The data file contains cumulative data by default. Daily numbers are calculated in the app.
- A slider to average data over N points, where N-1 points are the values preceeding the current data value. Display changes automatically as the slider moves. Only integer values are allowed.
- The display has a title that changes as the above mentioned selections change. The x-axis labels are custom-coded in the app.
- The start-date is 22nd Jan 2020. The end date is 30th Jan 2021, and it has not been hard-coded into the app, in case newer data-files are to be used.
