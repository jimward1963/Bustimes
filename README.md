# Bustimes
A basic analysis of the punctual arrival of buses
## Background
The arrival of buses operated by Bus Eireann in Galway city is not always punctual. As a regular bus user on the 401 route, I sometimes wait up to half an hour after the scheduled time for a bus at peak times of day, sometimes longer. Here, I attempt to simulate the 401 route for buses, bearing in mind that they are supposed to arrive every 20 minutes starting on the hour. I include a standard deviation of 15 minutes. Other variables are the number of passengers at stops (a Poisson distribution), and whether the driver is experienced (more than 1 year of service) or not (this is a categorical variable).

## Timetable
Buses on the 401 route depart every 20 minutes on the hour. The service lasts daily from 7.30 AM till 11.30 PM (16 hours).

## References

Bus Eireann Timetable (401 Route) 2018

https://docs.scipy.org/doc/numpy/reference/routines.random.html
