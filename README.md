# FoodCourtTally

# Overview
Hungry but when you reached the food court it was full? Or worried about catching Covid-19 due to the high number of people in the food court? That’s what our team hopes to solve. We are implementing an application that keeps track of the available seats at a food court and displays it on a web site for people to check and make accurate decisions from there.


# Implementation
At each food court, there will be two Raspberry Pis connected with an ultrasonic sensor module for entrance and exit
These two Pis will use a distancing algorithm to determine whether a person is entering or exiting the food court 
Based on the algorithm the Pis will communicate with a third Raspberry Pi that acts as the central database that stores all the tally for the various food courts, and update it accordingly
The central database Pi will also be hosting a web server that displays the various food courts along with their updated seating tallies
