### Biological data preprocessing by Markus Lindh, original scripts by Luuk van der Heijden developed for processing North Sea phytoplankton data

# EMODnet-Biology-Phytoplankton-Baltic
Analysis of phytoplankton species in the Baltic Sea

This is the Github repository of the EMODnet Biology product described here:
...website TBD...

## Information on how to use the R code
Startup requirements:
1.) Create a new R project in R Studio
2.) Save R Markdown files in the main folder of the R project
3.) Create a folder called "data" and subfolders "derived_data" and "raw_data"
4.) In the subfolder "raw_data" create two additional subfolders called "byDataset" and "byTrait"
5.) Run R code using the R Markdown files .Rmd in sequence, i.e. 1a, 1b, 2, 3 and 4a. Using the "knit" function in R Studio will run the scripts, save output data and produce html output for Rmd files 1a, 1b, 2 and 3 while a pdf output is created when running Rmd file 4a.
6.) Follow the instructions and annotations in the respective R Markdown files

Questions can be addressed to shark@smhi.se

## Information on input data and preprocessing
Data was derived from the:
 - Estonian part of the Gulf of Finland
 - Danish part of the Skaggerak
 - Finnish part of the Gulf of Finland
 - Danish part of the Kattegat
 - German part of the Kattegat
 - Norwegian part of the Skaggerak
 - Swedish part of the Skaggerak
 - Russian part of the Gulf of Finland
 - Finnish part of the Gulf of Bothnia
 - Swedish part of the Gulf of Bothnia
 - Latvian part of the Gulf of Riga
 - Estonian part of the Gulf of Riga
 - Latvian part of the Baltic Sea
 - Estonian part of the Baltic Sea
 - Finnish part of the Baltic Sea
 - Lithuanian part of the Baltic Sea
 - Polish part of the Baltic Sea
 - Russian part of the Baltic Sea
 - Swedish part of the Baltic Sea
 - German part of the Baltic Sea
 - Danish part of the Baltic Sea
 
The following datasets were used:
"785 Continuous Plankton Recorder (Phytoplankton)"
"2453 SHARK - Marine phytoplankton monitoring in Sweden since 1983"
"2722 PANGAEA - Data from various sources"
"4424 ICES Phytoplankton Community dataset"
"5664 Phytoplankton data for Danish marine monitoring (ODAM) from 1988 - 2016"
"2463 Polish Monitoring Programme - Monitoring of the Baltic Sea: phytoplankton"
"5724 Finnish Baltic Sea phytoplankton monitoring, KPLANK database"
"5727 SHARK - Regional monitoring and monitoring projects of Epibenthos in Sweden since 1994"
"2455 SHARK - National Epibenthos monitoring in Sweden since 1992"
"1985 NODC World Ocean Database 2001: Plankton Data"
"5840 IFCB110-SMHI: Imaging flow cytometry from SMHI in Tangesund 2016"
"6021 Phytoplankton composition, biomass and abundance in Estonian territorial waters 1993-2016"

The timespan used was "1995-01-01" until "2020-05-31"

This preprocessing resulted in a aggregated dataset corresponding to 2021 unique species in 16444 unique locations (lat and long).
