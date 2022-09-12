# team-project-sunrisers
team-project-sunrisers created by GitHub Classroom

Implement an end2end Airport Management system that can be configured for a given airport (Web interface or Mobile app interface with supporting Backend APIs), that integrates Airline Flight Schedules, Gate Assignments, Baggage Claim assignment for arriving flights

The emphasis here is on team collaboration, so the points awarded will be based on individual contributions to the team and how the team performed overall.  

Components:

APIs - input and output of API should be in JSON and should include error handling and validation of inputs
APIs will be demonstrated using a Web/mobile UI
UI is accessed by Passengers (Customers) and Airline employees and Airport employees (3 roles)

APIs should support following functionality:

Retrieve Flight arrivals and departures and Gate assignments - based on time durations (next hour, next 2 hours, next 4 hours) - this data will be displayed in multiple monitors throughout the airport - viewable by all users
Implement a Random Gate assignment for Arriving and Departing flights - designed to prevent conflicting assignments - allow for an hour for each flight to be at the gate (for arrivals and for departures)

Airport employees :
//check
Enable or disable one or more gates for maintenance
Assign Baggage Carousel number to Arriving flights - the system should prevent conflicting assignments
Baggage Claim information will be displayed in multiple monitors in the Arrival area

Airline employees:

Add or update the schedule of flights belonging to their airline relevant to that airport (arrivals and departures)
APIs and UI functionality will be available based on Roles specified above
Assume Gates are distributed in multiple terminals (1, 2, 3 to keep it simple)
Assume Gates are labeled as A1-A32, B1-B32 and C1-C32
Deploy API to AWS in an Auto Scaled EC2 Cluster with Load Balancer (or another cloud provider)
Develop a Web or mobile UI that will make use of the APIs
Create your own database with mock data - use SFO or SJC as an example airport for your data

Sprint Task sheet:
https://docs.google.com/spreadsheets/d/1xVN1TYFBGojNXxERLfRykjC6AGKlkUP404rh5YZaU9U/edit#gid=0
