#Project Description.
## Background:
**RTS (Road TO Success) is A company that have several vending machines that sells drinks , food and electronics.
RTS want to put their vending machines in best places to gain benefit.**

## Project Scope: 
### ***Where to put vending machines in summer?***
**RTS focus on where to put vending machines that sells drinks, foods and electronics in stations that have most traffic in the summer.By analysing the given data Im going to find top stations , best entries per station ,and daily trafic per week to do mantenance and refill vending machines.**


## Data Description:

**Main data : New York City: MTA turnstile data (http://web.mta.info/developers/turnstile.html).
I'm taking three months (summer) in three years 2017/18/19 (total 9 months).
My Dataset has 7809430 rows and 11 columns**
### culomns:
* C/A      = Control Area 
* UNIT     = Remote Unit for a station
* SCP      = Subunit Channel Position represents an specific address for a device
* STATION  = Represents the station name the device is located at
* LINENAME = Represents all train lines that can be boarded at this station.
* DIVISION = Represents the Line originally the station.
* DATE     = Represents the date (MM-DD-YY)
* TIME     = Represents the time (hh:mm:ss) for a scheduled audit event
* DESc     = Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)
           -1. Audits may occur more that 4 hours due to planning, or troubleshooting activities. 
           -2. Additionally, there may be a "RECOVR AUD" entry: This refers to a missed audit that was recovered. 
* ENTRIES  = The comulative entry register value for a device
* EXIST    = The cumulative exit register value for a device

## Tools:
    1- SQLite,DB browser, SQLAlchemy.
    2- Python,Pandas,Numpy.
    3- Seaborn and Matplotlib.
