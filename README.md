#  NY Motor Vehicle Collisions

The Motor Vehicle Collisions data contains details on each vehicle involved in the crash. Each row represents a motor vehicle involved in a crash.

For this project my vehicle make and year parameter was ('HOND', 'SUZI', 'MITS', 'CADI') and years (2018-2020).

# Analysis 1:
For the make of the vehicles (using the VEHICLE_MAKE attribute) to be processed by
each team, count the number of accidents that each one of those vehicles make were
involved in for each of the years given to you (in the parameter file). Plot them as a bar
graph with vehicle_make on the X-axis and count on the Y-axis. For each vehicle make,
there will be two bars and year can be shown at the top of the bar. This can also be
visualized in other ways. Analyze the vehicle makes for smallest and largest counts using
data from the internet.


## Result:

- HOND has the highest accident count (80,069), with a sharp peak in 2019 (47,595), followed by a drop in 2020 (19,034).
- SUZI has the lowest accident numbers across all years, with 2019 showing the highest count (511).
- MITS and CADI also peaked in 2019
- 2020 saw a sharp decline in accidents for all vehicle makes, likely due to COVID-19 restrictions and reduced traffic.

### Potential Reasons for 2019 Peak:

- Increased vehicle sales or more active drivers on the road.
- Potential environmental or policy factors affecting traffic and accident rates.
- Higher traffic congestion leading to a spike in collisions.


### Potential Reasons for 2020 Drop:

- COVID-19 lockdowns led to fewer vehicles on the road.
- Work-from-home culture reduced commuting-related accidents.
-Travel restrictions and economic slowdowns affected vehicle movement.


# Analysis 2:
Compare monthly accidents (# of accidents in each month) for each vehicle make (using
the vehicle_make attribute) for given years (given to you in the parameter file). Plot
them as a line graph for each vehicle make for every month (as X-axis) and count as Y- axis.
Analyse whether some months are more accident prone than others? Try to justify
your findings with data (summer vs winter months, holidays/long weekends, snow
season in New York City, any other events that happen in New York City for that given year using data from the internet). This is another visualization using different aggregate
values.

## Result:

## The monthly breakdown reveals accident seasonality patterns:

- Winter months (Nov – Feb) show fluctuations, likely due to icy roads, poor visibility, and bad weather.
- Summer months (June – August) also have moderate accident peaks, possibly due to increased travel and vacations.
- Early months of 2020 (Jan – March) still had significant accidents, but a sharp decline occurred from April onwards (lockdowns).

# Analysis 3:
For each type of vehicle (using the vehicle_type attribute) given in the parameters file,
plot the count as a percentage of crashes each unique type of vehicle was involved in.
You can visualize this using a pie chart. Below is the sample visualization for the whole
dataset (you will have to clean your data of “no value”/unknown and merge similar
types such as TAXI and Taxi). Analyze the result in any way possible using data from the
internet. if a specific vehicle type is more likely to be involved in an accident using the
total number of such vehicles.

## Result:

- Sedans (52,503 accidents) have the highest accident rate, likely due to their popularity.
- SUVs (34,047 accidents) are the second most involved in crashes, potentially due to higher speeds and increased road presence.
- Taxis (1,982 accidents) have a notable share, likely because of high road exposure.
- Motorcycles (886 accidents) and Trucks (547 accidents) show relatively fewer accidents but could have higher severity.
- Bicycles (2 accidents) have the lowest representation.



## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



## References
- NYC Open Data - Motor Vehicle Collisions Dataset: [https://data.cityofnewyork.us](https://data.cityofnewyork.us)
- New York City Department of Transportation (NYC DOT) - Traffic Reports: [https://www.nyc.gov/html/dot/html/home/home.shtml](https://www.nyc.gov/html/dot/html/home/home.shtml)
- National Highway Traffic Safety Administration (NHTSA): [https://www.nhtsa.gov/](https://www.nhtsa.gov/)
- COVID-19 Impact on Traffic Patterns: [https://www.transportation.gov/](https://www.transportation.gov/)
