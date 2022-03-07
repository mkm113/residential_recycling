# residential_recycling
This dataset was assembleded for the Winter 2022 quarter for the iSchool at the University of Washington. It analyzes the amount of waste, recycling rates, diversion rates, and costs for the cities of Atlantic City, New York, San Francisco, and Seattle. The intended audience of this readily accessible data are citizens looking to be more informed of their city's recycling initiatives. 

Included is a table with raw. These findings assist in the cross-analysis of urban cities and their municipal performance. Duplicate variables were not calculated, and all fields have been filled. All of these findings are also availabele to view in .xlxs and .csv formats.

# Table of Contents #

* Naming
* Data Dictionary
* Metadata
* Security
* Contact

# Naming #

Naming for the files should be as follows:

                 year_datasettype
      
*Year* refers to the year of the data being reported, and 

where *datasettype* indicates whether this is raw data ("raw") or normalized data ("normal").

This naming convention originally contained a third value for municipalities. Due to the possibility of a future expansion of municipal scope, this consideration was excluded from the final naming convention. Rather, annual updates to the metadata keyword and description attributes should be made according to added city programs.

# Data Dictionary #

| Variable | Variable Name | Measurement Unit | Allowed Values | Definition |
| -------- | ------------- | ---------------- | -------------- | ---------- |
| city_Program | City Program | String | U.S. City Names | City Name | 
| metal | Metal Tonage | Numerical | Integers greater than 0| Total tonage of metal recycled in 2017 |  
| paper | Pater Tonage | Numerical | Intergers greater than 0 | Total tonnage of paper recycled in 2017 |  
| plastic | Plastic Tonnage | Numerical | Number greate rthan 0  | Total tonnage of plastic recycled in 2017 |  
| average_Cost | Average Cost Per Ton | Numerical | Numbers greater than 0 (USD) | Average cost of recycling a ton of materials in 2017 (USD) | 
| diversion_Rate | Diversion Rate | Numerical | Numbers between 0-100 (%) | Total percentage of diverted landfill materials (2017) | 
| population | Population Size | Numerical | Integers greaer than 0 | Population size (people) |  
| area | Area | Numerical | Numbers greater than 0 (miles squared) | Area of city (miles squared) | 

# Metadata #

| Attribute | Value |
| --------- | ----- |
| accessLevel | Public | 
| accrualPeriodicity | R/P1Y | 
| fn | Keiko Martinez | 
| hasEmail | mailto:mkm13@uw.edu |  
| describedBy | https://github.com/mkm113/residential_recycling | 
| description | This dataset analyzes tonnage production sizes, recycling rates, diversion rates, and costs of four prominent recyclable materials pertaining to four cities in the United States: Atlantic City, New York, San Francisco, and Seattle. The intended audience are citizens. This dataset has been curated for a class at the University of Washington for the Winter 2020 Quarter.| 
| accessURL | https://github.com/mkm113/residential_recycling/blob/master/2017_raw.csv | 
| downloadURL | https://github.com/mkm113/residential\_recycling/raw/master/2017\_raw.csv | 
| format | CSV | 
| mediaType| CSV | 
| issued | 2020-3-07 | 
| keyword | "recycling", "diversion", "atlantic city”, “new york", "san francisco", "seattle", "california", “washington” “new jersey” “2017” | 
| landingPage | https://github.com/mkm113/residential_recycling | 
| language | en-us | 
| modified | 2022-03-07 | 
| publisher | Keiko Martinez | 
| references | https://www.nj.gov/dep/dshw/recycling/stat_links/2017finalreport.pdf
https://dsny.cityofnewyork.us/wp-content/uploads/2018/04/2017-Waste-Characterization-Study.pdf
https://sfpublicworks.org/sites/default/files/Recology%20San%20Francisco%20 Companies%27%20Annual%20Report%20for%20Rate%20Year%202017.pdf, http://www.seattle.gov/Documents/Departments/SPU/Documents/2017Recyclin gProgramReport.pdf | 
| Rights | This dataset and all associated repositories are freely available to all | 
| temporal | 2020/P1Y | 
| theme | recycling, diversion | 
| title | Urban Recycling Program Comparisons | 


# Security #

This dataset is freely available for public viewing and use.

# Contact # 

Keiko Martinez mkmartinez93@gmail.com
