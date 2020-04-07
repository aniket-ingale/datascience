#SCS_3253 MACHINE LEARNING Term Project

#SCHOOL SAFETY ZONE: WATCH YOUR SPEED PROGRAM
Group 6: Aniket Ajit Ingale, Zlata Izvalava

PROJECT
The Watch Your Speed Program (WYSP) uses devices called speed display signs or driver feedback signs which contain a radar device and an LED display. The radar measures the speeds of oncoming vehicles and the LED sign displays their speeds to the passing motorists, thereby reminding them to check their speeds and to obey speed limits. The City of Toronto’s permanent units are installed in Safety Zones.
We used the data recorded by permanent driver feedback signs installed in School Safety Zones. The datasets are published by Transportation Services on the City of Toronto Open Data Portal.
Data:
1.	“School Safety Zone Watch Your Speed Program – Detailed Speed Counts” 
An hourly aggregation of observed speeds for each location where a Watch Your Speed Program Sign was installed in 10 km/hr speed range increments.
https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-detailed-speed-counts/
2.	 “School Safety Zone Watch Your Speed Program – Locations”
The locations and operating parameters for each location where a permanent Watch Your Speed Program Sign was installed.
https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-locations/

We explored the data recorded by the driver feedback sign #230 (approximate address - 994 Jane Street, Toronto; southbound direction of travel; speed limit - 50 km/hr) and trained different regression models for predicting an hourly count of vehicles traveling at a speed in the “50 km/hr and higher” speed range for this location. The Polynomial Regression model (degree = 2) produced the best performance.

Analysis of recorded data and use of the model can be helpful for understanding the situation with safety in this school safety zone and for planning measures to improve it.

The project includes:
•	Notebook 1 - Download, prepare and explore the data (scs3253_project_group6_notebook1.ipynb)
•	Notebook 2 - Data transformation, model training and evaluation (scs3253_project_group6_notebook2.ipynb)
•	Presentation (scs3253_project_group6_presentation.pdf)

The data will be downloaded, extracted and read into pandas DataFrames when you run the Notebook 1.


