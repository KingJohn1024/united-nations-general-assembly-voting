# united-nations-general-assembly-voting

The purpose of this repo is to load, map and transform United Nations General Assembly voting data.

There are 4 input files to the process:

1. ./source_data/NortheasternExport4.xlsx
This the main input file and the first sheet is read.  The ID column is important is it's used later to merge the category data.  The VotingInformation column contains the string payload of votes by country.

2. ./source_data/GA Votes Working Document.xlsx - Top Level Sub level.csv

3. ./source_data/GA Votes Working Document.xlsx - Top level Sub level description.csv
This file is the look table of category level values

4. ./source_Data/Download-GDPcurrent-USD-countries.xlsx
