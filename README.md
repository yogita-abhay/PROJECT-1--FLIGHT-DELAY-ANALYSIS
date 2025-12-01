# PROJECT-1--FLIGHT-DELAY-ANALYSIS

### Project Overview 

Flight delay analysis involves the systematic evaluation of aircraft performance, & flight operations. This project focuses on analyzing airline performance using flight, Airport & Airline data. The project provides insights and recommendations for improving on-time performance, airline route optimization, Scheduling, flight punctuality and overall airline efficiency. This process supports decision-making in areas like planning, Arrivals and Departures. 

### Objectives:

*Reduce Arrival Variability

*Identify Root Causes

*Optimize Scheduling

*Punctuality

*Visualization

## DATASET OVERVIEWS

<img width="718" height="658" alt="image" src="https://github.com/user-attachments/assets/1057690c-b992-4d48-813b-1f622b30c389" />

## DATA MODELLING

<img width="1446" height="678" alt="image" src="https://github.com/user-attachments/assets/29e5cce3-6604-4ea6-95d6-afa7d99d52e9" />

### CHALLENGES IN DATA ANALYSIS

* Difficulty loading large data (over 1 million records) into Excel & SQL
  
* Parsing time columns (Departure Time, Wheels Off, Arrival Time, etc) required cleaning and type conversion
  
* Memory optimization issues while performing aggregation queries
  
* Difficulty in converting AM/PM to 24 hr format.
 
### FINAL KPI METRICS

• To get a complete picture of airline performance across operations and reliability.	

• Total flights, cancellations & diversions show overall network activity and reliability.	

• Weekday vs weekend and state/city-wise trends help identify demand and traffic patterns.	

• Busiest airports & routes reveal high-traffic areas that impact scheduling and delays.	

• Delay-related KPIs (average delay, delay reasons, time-of-day) help pinpoint causes and patterns of delay.

• Airline-wise delay analysis highlights the most and least punctual airlines.	

• Punctuality metrics (7-day rolling and on-time performance) track consistency over time.	

• Taxi-in/out times measure ground efficiency and turnaround speed.

• Delay correlation (departure vs. arrival) shows how early issues propagate through the system.	

• Hourly and destination-wise delay rates identify when and where performance drops the most.

### EXCEL DASHBOARD

<img width="1861" height="965" alt="image" src="https://github.com/user-attachments/assets/99dd4953-e3e5-48fb-8e27-8e1b1671ed5f" />

### POWER BI DASHBOARD

<img width="1181" height="636" alt="image" src="https://github.com/user-attachments/assets/456f8d2e-8030-4f32-9d08-f9a67d24275d" />

<img width="1361" height="769" alt="image" src="https://github.com/user-attachments/assets/658ab18a-c682-4a00-b7a2-5f7ed769892f" />

### TABLEAU DASHBOARD

<img width="1867" height="954" alt="image" src="https://github.com/user-attachments/assets/2932af1a-225f-416c-9f94-96a6816f0572" />

SQL QUERIES KPI

<img width="1274" height="732" alt="image" src="https://github.com/user-attachments/assets/0e9af314-6037-4eff-834a-9597399a0c72" />

<img width="1431" height="748" alt="image" src="https://github.com/user-attachments/assets/bd372226-ce8b-4ae5-b62c-8635158f8079" />

## TAKEAWAYS

* A total of 1.04 million flights were analyzed, around 40K flights were cancelled and 2.5K were diverted, showing minor operational disruptions.
  
* Over 1 million flights and a majority of departures categorized as Early or On-Time (56% combined).

* Weekdays handled more flights (≈769K) than weekends (≈277K), and also saw higher delays. Weekdays experienced more delays than weekends, mainly due to late aircraft and airline issues.

* Southwest and major airlines among all the airlines handled the most flights, highlighting their network strength.

* The key challenge is the volume of 421K Late Arrivals. This issue is most pronounced during high-volume weekday periods. 

* Utilize the detailed Cancellation Reasons data to perform an immediate Pareto analysis. 

* Early arrivals (≈559K) outnumbered late arrivals (≈421K), indicating overall strong flight performance.

* Major delays were linked to late aircraft and airline-related issues, rather than weather or security.


## RECOMMENDATIONS

* Improving aircraft turnaround and using predictive analytics can further reduce delays.

* High-volume weekday periods, requiring targeted optimization in scheduling (distributing flights more evenly) and turnaround processes at major hubs.

* Focus resources on weekday arrival optimization and root-cause analysis of the top cancellation factors.

* Minimize turnaround time to address “Late Aircraft” delays through better coordination between arrival and departure teams.

* Enhance predictive maintenance and analytics to identify aircraft or routes prone to delays. 

* Collaborate with air traffic control to manage peak-hour congestion, especially at major hubs like LAX and JFK.

* Monitor airline-specific performance (e.g., F9, MQ, NK) and set benchmarks for on-time improvement.








