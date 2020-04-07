{\rtf1\ansi\ansicpg1252\cocoartf2512
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red0\green0\blue233;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c0\c0\c93333;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid101\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa240\partightenfactor0

\f0\fs24 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 SCS_3253 MACHINE LEARNING Term Project\
SCHOOL SAFETY ZONE: WATCH YOUR SPEED PROGRAM\
Group 6: Aniket Ajit Ingale, Zlata Izvalava\
PROJECT\
The Watch Your Speed Program (WYSP) uses devices called speed display signs or driver feedback signs which contain a radar device and an LED display. The radar measures the speeds of oncoming vehicles and the LED sign displays their speeds to the passing motorists, thereby reminding them to check their speeds and to obey speed limits. The City of Toronto\'92s permanent units are installed in Safety Zones.\
We used the data recorded by permanent driver feedback signs installed in School Safety Zones. The datasets are published by Transportation Services on the City of Toronto Open Data Portal.\
Data:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'93School Safety Zone Watch Your Speed Program \'96 Detailed Speed Counts\'94 An hourly aggregation of observed speeds for each location where a Watch Your Speed Program Sign was installed in 10 km/hr speed range increments. {\field{\*\fldinst{HYPERLINK "https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-detailed-speed-counts/"}}{\fldrslt \cf3 \ul \ulc3 \strokec3 https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-detailed-speed-counts/}}\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \'93School Safety Zone Watch Your Speed Program \'96 Locations\'94 The locations and operating parameters for each location where a permanent Watch Your Speed Program Sign was installed. {\field{\*\fldinst{HYPERLINK "https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-locations/"}}{\fldrslt \cf3 \ul \ulc3 \strokec3 https://open.toronto.ca/dataset/school-safety-zone-watch-your-speed-program-locations/}}\
\pard\pardeftab720\sa240\partightenfactor0
\cf2 We explored the data recorded by the driver feedback sign #230 (approximate address - 994 Jane Street, Toronto; southbound direction of travel; speed limit - 50 km/hr) and trained different regression models for predicting an hourly count of vehicles traveling at a speed in the \'9350 km/hr and higher\'94 speed range for this location. The Polynomial Regression model (degree = 2) produced the best performance.\
Analysis of recorded data and use of the model can be helpful for understanding the situation with safety in this school safety zone and for planning measures to improve it.\
The project includes:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Notebook 1 - Download, prepare and explore the data (scs3253_project_group6_notebook1.ipynb)\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Notebook 2 - Data transformation, model training and evaluation (scs3253_project_group6_notebook2.ipynb)\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Presentation (scs3253_project_group6_presentation.pdf)\
\pard\pardeftab720\sa240\partightenfactor0
\cf2 The data will be downloaded, extracted and read into pandas DataFrames when you run the Notebook 1.\
}