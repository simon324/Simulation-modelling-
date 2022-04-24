# Simulation-modelling-
Optimization of a hospitals planning system

Now: 14 time slots urgent patients a week
(should range between 10 and 20)

Aim: hospital wants to revise the distribution of the time slots
Trade off waiting time elective patients/urgent patients taking opening/closing hours into account

Strategy 1:
Urgent patients served at end of morning/end of day
=> increase number of slots there
Strategy 2:
Evenly distribute number of urgent patient time slots in a particular day
Strategy 3:
Urgent patient time slot is planned after every six elective patient time slots
How to evaluate: Simulate patient arrivals and scan durations 

Rule 1: FCFS
Appointment time = start time of assigned time slot
Rule 2: Bailey-Welch
Rule 3: Blocking Rule
Rule 4: Benchmarking Rule

