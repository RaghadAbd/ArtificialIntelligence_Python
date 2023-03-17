Write Python program that simulate AI agent for Vacuum Cleaner (VC) with the following characteristics:

1- The task environment consist of two, equal locations {A, B}, on vertical distribution with arbitrary state {clean, dirt}.

2- VC precepts only the area where it was located, and act accordingly.

3- VC get one perception every 2 seconds

4- Dirt area can be changed into clean by applying suck action by agent, and the clean area changes to dirt area by getting random value, clean or dirt, for each area separately every 3 seconds.

5- VC will get 1 point for each clean area, whenever the Performance Measure run. Performance Measure will be run for 15 seconds.

The simulator will print the following while it is running for 60 seconds :

1- Environment state: the two locations with its dirt state, whenever the environment change.

2- The VC’s perception state: current location of VC, location’s state, and VC action.

3- Performance measure value whenever the evaluation is run and the cumulative value as well.
