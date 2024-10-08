A pharmacy has a batch processing system for its orders. Orders are collected throughout the day and the medicine is produced during a set of hours. They want to reduce wastage and are considering shifting to a just in time model. The data from over 8000 orders is collected in an excel file and provided to the analyst to load into R.

The Medication Waste Dashboard is created using R. It has three tabs: Descriptive Analytics, Regression Model and Hours of Supply. 

The Descriptive Analytics tab has five interactive sections: a sidebar to choose any individual drug, two value boxes that display the total amount of money wasted as well as the dose quantity, and two histograms: one indicates cancelation by the hour and the other shows dollar wasted by the hour. 
![MWR1](MWR1.png)

The second tab is a regression model of the drug wastage by hour, with a confidence interval of 95%. For each drug and at each hour it shows the dollar amount of wastage.
![MWRR](MWRR.png)

The final tab displays the cost savings if the pharmacy shifts to a just in time production mode from the batch processing mode.
![MWR3](MWR3.png)
