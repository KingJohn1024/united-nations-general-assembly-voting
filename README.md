# united-nations-general-assembly-voting

The purpose of this repo is to load, map and transform United Nations General Assembly voting data.


## Python environment and setup
- Python3 is required
- openpyxl is requried - https://pypi.org/project/openpyxl/
```
pip install openpyxl
```
- tableauhyperapi is required - https://pypi.org/project/tableauhyperapi/
```
 pip install tableauhyperapi
```
- pantab is required - https://pypi.org/project/pantab/
```
pip install pantab
```
My environment is running on a M1 Macbook Pro and the Tableau Hyper API is only supported on the x86 arch.  As a result my Python environment is running in x86 emulation mode via Homebrew, started via this command.
```
/usr/local/Cellar/ipython/7.22.0/bin/ipython notebook
```


## Data Details
There are 4 input files to the process:

- Core UN Voting data
  path: ./source_data/NortheasternExport4.xlsx
  description: This the main input file and the first sheet is read.  The ResolutionCode column is important is it's used later to merge the category data.  The VotingInformation column contains the string payload of votes by country.

-  ./source_data/GA Votes Working Document.xlsx - Top Level Sub level.csv

- ./source_data/GA Votes Working Document.xlsx - Top level Sub level description.csv
This file is the look table of category level values

- ./source_Data/Download-GDPcurrent-USD-countries.xlsx

## Data processing methodology

## Data pipeline to Tableau

## Cluster analysis

## Visual Output
Final dashboard outpit
![UNVoting Dashboard](/docs/images/UNVoting.Dashboard.png)

Country Cluster Analysis Visualized
![Country Clusters](/docs/images/CountryClusters.png)
