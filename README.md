# Yellow-Fever-Outbreaks-and-Reactive-Vaccination-in-Africa-2010-2025-A-Scoping-Review-and-Analysis
These files contain the data and anaylsis files for the original article:

Carlos Haring BA, Sayana Lee MPH, David Dowdy MD PhD, Seth D. Judson MD MHS. Yellow Fever Outbreaks and Reactive Vaccination in Africa, 2010-2025: A Scoping Review
and Analysis. __________________________



Datasets (located in the "data" folder): YF_Outbreaks.csv

- contains data on cases, deaths, index case dates, outbreak declaration dates, local reactive vaccination campaign start dates, mass reactive vaccination campaign start dates, outbreak notification dates, The corresponding dictionary is called "YF_outbreaks_datadictionary.csv".

YF_RVCs.csv

- contains data on reactive vaccination campaign start dates, reactive vaccination campaign end dates, target vaccination population, the percentage vaccinated, the number vaccinated, geographic location indicators, type coverage measurement, what outbreak the RVC is linked too, and vaccination grouping information. The corresponding dictionary is called "YF_RVC_datadictionary.csv".

xlsx files for the csv files above are available with colorcoded sheets that connect data to the corresponding urls it was sourced from.

Analysis files (located in the "src" folder): YF_oubreak_anaylsis.rmd

- Contains the R code that was used to anaylsis the YF_Outbreaks.csv data. Specifically the code used to do the descriptive and statistical anaylsis on the case fatality rate, the total cases reported, and the time to the reactive vaccination campeigns. Figure 1, Figure 2, and Table 1 were created using the code in this file. 

YF_RVC_anaylsis.rmd

- Contains the R code that was used to anaylsis the YF_RVC.csv data. Specifically the code used to do the descriptive and statistical anaylsis reacitve vaccination coverage and the vaccination rate (% of target population vaccination per day). Table 2S was created using the code in this file.

Figures (located in the "figs folder")

figure_1
- Timing of index case to reactive vaccination for yellow fever in Africa, 2010-2025:

figure_2
- Case fatality ratio of yellow fever outbreaks in Africa, 2010-2025

table_1
- Yellow fever outbreaks in Africa (2010-2025) included in RVC analysis

table_2S
- Yellow fever reactive vaccination campaigns in Africa (2010-2025) included in the analysis




