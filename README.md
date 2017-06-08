# FinalProject
Discrete Event Simulation

# Notes
This is the implementation of a simple discrete event simulation project explained at the main.pdf file of this repository. 


It is based on the event-scheduling approach where the activities happening in the system are modelled as Event classes. 
In this implementation Event objects have a timestamp and refer to the relevant Task object, as they are created they are scheduled in a priorirty queue called FutureEventsList prioritized wrt time and they also create schedule new Event objects forming a chain.
The chain starts with TaskCpuArrivalEvent and finishes with OutFreeEvent when there are no more work to be done with the tasks.


There are two implementations, in python and c++. I first implemented it in python since I am more comfortable with it, then ported to C++.






