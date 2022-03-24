# MTA TURNSTILE DATA

The New York subway MTA turnstile data is a series of data files containing cumulative number of entries and exits by station, turnstile, date and time. Data files are produced weekly, data records are collected typically every 4 hours with some exceptions.<br/> 

In this analysis we use data from the June Months between 2018-2021.Data size is 3276100. We used the data from the link below.<br/> 
### Data: http://web.mta.info/developers/turnstile.html

Variables included in initially processed data:

- **C/A =**  *Control Area (e.g., A002)*
- **Unit =**  *Remote Unit for a station (e.g., R051)*
- **Scp =** *Subunit Channel Position represents an specific address for a device (e.g., 02-00-00)*
- **Station =** *C/A + unit, locating a station*
- **Turnstile =** *C/A + unit + SCP, locating a turnstile*
- **Station =** *Represents the station name the device is located at*
- **Date =** *Represents the date (MM-DD-YY)*
- **Time =** *Represents the time (hh:mm:ss) for a scheduled audit event*
- **Datetime =** *date + time (MM-DD-YY hh:mm:ss)*
- **Desc =** *Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)*
- **Entries =** *The comulative entry register value for a device*
- **Exits =** *The cumulative exit register value for a device*
- 
## OBJECTIVE AND GOAL
WomenTechWomenYes is holding an annual gala, and aims to invite as many interested individuals as possible.That's why, to find out the which stations and days in a week are the busiest in the resource.

- Finding the busiest stations.
- Finding the busiest time of the day by busiest station.
- Finding day with highest traffic per station.

## EXPLORATORY DATA ANALYSIS
Looked For Duplicated And Null Values In The Data Set.
Dropped Some Columns From The Data And Changed The Names Of Them.
Added The Day Column To Data Set.

![image](https://user-images.githubusercontent.com/97549619/159938160-c841d65f-d05f-4048-bbc3-3f2b67b488c7.png)



