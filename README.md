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
## Project Goals and Approach
To aim of  the which stations and days in a week are the busiest in the traffic would allow us to reach more participants That’s why,

- Finding the busiest stations.
- Finding the busiest time of the day by busiest station.
- Finding day with highest traffic per station.
