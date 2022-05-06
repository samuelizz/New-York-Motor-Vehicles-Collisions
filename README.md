# New-York-Motor-Vehicles-Collisions
Link to Interactive Dashboard : [Tableau](https://public.tableau.com/app/profile/ogunwemimo.olajide/viz/NewYorkCityMotorVehiclesCollision/Overview)


### ABOUT DATA
The Motor Vehicle Collisions crash table contains details on the crash event. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The police report (MV104-AN) is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage.

Link to Dataset : [NYC OpenData](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)

### TASK
The task is to Analyse the Data in order to gain insights and recommendations which can later be used to drive decisions which will reduce the vehicle collisions in the New York City.

The dataset used for this study was from 2017 - 2021

### DATA WRANGLING
The data was cleaned and transform with MS Excel and later imported into Tableau Desktop for Visualizations
* The `Borough` column contains some blank rows which was transformed and labelled `Unspecified`
* The `Contributing Factor Vehicle 1` column was used and others were dropped.
* Some few columns were also dropped.

### ANALYSIS
The Report Dashboard consists of four (4) sections namely ;
1. Overview
2. Motorists Analysis
3. Pedestrians Analysis
4. Cyclists Analysis

Each section focused on the victim type and also the cause of their deaths.

#### OVERVIEW
![Overview](https://user-images.githubusercontent.com/70443173/167213172-45f2c7bd-509a-4ab6-bf4b-8287da43c086.png)

From the overview ;
* Most of the collision was from the `Driver Inattention / Distraction` 
* The collision rate dropped drastically at the beginning of 2020 which makes sense because of the pandemic (less people driving).

#### MOTORISTS ANALYSIS
![Motorist](https://user-images.githubusercontent.com/70443173/167216116-2d60fc44-0201-4dbc-b279-e60606df33a6.png)
* `Unsafe Speed` was the top cause of collision which led to motorists deaths.
* Most collisions occur on `weekends (saturday & sunday)` and at late night.

#### PEDESTRIANS ANALYSIS
![Pedestrians](https://user-images.githubusercontent.com/70443173/167216698-1b977f51-26dc-44bb-a13e-b50619710c18.png)
* Most collisions cause were `Unspecified`
* Most collisons also occur at late night

#### CYCLISTS ANALYSIS
![Cyclist](https://user-images.githubusercontent.com/70443173/167217098-dc3d6b58-83a4-44fd-8913-fed5b16276d7.png)
* `Driver Inattention / Distraction` was the top cause of collision which led to cyclists deaths.
* Most collisions also occured at late night.

### RECOMMENDATIONS
* Since most collisions were caused by `Driver Inattention / Distraction`, there should be fine/charges for such distractions.
* More traffic wardens should be deployed during hours and days with most collisons.
* Areas with more collisions should have more traffic wardens and rules to be followed strictly.
* There should also be speed regulator in areas with high collisions.



