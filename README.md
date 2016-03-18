# NFIRS
A collection of scripts to analyze aggregated National Fire Incident Reporting system 
[(NFIRS)](https://www.nfirs.fema.gov/) data supplied by [FEMA](https://www.fema.gov). 

# R code (using Google style guide)
Packages include:  
* dplyr  
* readr  
* lubridate  
* gdata  
* stringr  

Functions:  
* mdy2, mdy_hms2 - timestamp parsing after padding with zeros  
* ReadNFIRS  
  + ReadAll  
  + ReadBasic  
  + ReadAddress  
  + ReadInjury  
  + ReadHazmat  

2014 Data available on by request from FEMA or on AWS 
[7zip](https://s3.amazonaws.com/cpsm.nfirs/NFIRS-2014/NFIRS2014.7z)
[RData](https://s3.amazonaws.com/cpsm.nfirs/NFIRS-2014/NFIRS2014.RData)
