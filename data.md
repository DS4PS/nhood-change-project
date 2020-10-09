---
title: "Project Data"
---





```r
dat <- read.csv( "https://github.com/Nonprofit-Open-Data-Collective/machine_learning_mission_codes/blob/master/DATA/MISSION.csv?raw=true", stringsAsFactors=F )
```

Read RDS version:

```r
dat <- readRDS( gzcon( url( "https://github.com/Nonprofit-Open-Data-Collective/machine_learning_mission_codes/blob/master/DATA/MISSION.rds?raw=true" )))
```

<br> 
<br> 

-------------------

# Overview of the Data




## Raw Data Sources

Project data comes from three sources. 

**Harmonized Census Tracts:** 

[Longitudinal Tracts Data Base](https://s4.ad.brown.edu/projects/diversity/Researcher/Bridging.htm)

* [Codebook](data/LTDB-codebook.pdf) 
* [Variables Constructed from the US Population Samples (long form questions)](data/LTDB_Std_All_Sample.zip)  
* [Variables Constructed from the Full US Population (short form questions)](data/LTDB_Std_All_fullcount.zip)  


**New Market Tax Credits Database:**

[Program Overview and Tract Eligibility Requirements](https://www.cdfifund.gov/programs-training/Programs/new-markets-tax-credit/Pages/default.aspx)

[Data Download](https://www.cdfifund.gov/awards/state-awards/Pages/default.aspx)


**Low Income Housing Tax Credits Database:** 

[Data Download](https://lihtc.huduser.gov/)

Look for the section labeled: "If you want a complete list of projects for the entire U.S., click here to download a ZIP archive of the entire LIHTC Database in dBase format."

