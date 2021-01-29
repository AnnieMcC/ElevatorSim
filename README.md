# Elevator Simulation
### Program to determine the optimal number of 'steps' to get a number of waiting passengers around in a 10 storey building

Elevator Simulation is a C# console app, built in .Net Core 3.1 using Visual Studio.


* To load the program, run the following in a terminal & use the master branch

`git clone https://github.com/AnnieMcC/ElevatorSim`

* After cloning, build the project & Run

* The program requires a number of inputs, which are prompted:

`How many people are waiting for the lift (on any floor)?`

`Enter origin floor (0-10) for passenger x:`

`Enter destination floor (0-10) for passenger x:`

The last 2 prompts will be repeated for each passenger who is waiting.

* Console will output the CurrentFloor after each step, as well as any ElevatorStatus (Opening, Closing, Stopped) where passengers are entering or leaving the lift.

* Finally, the console will output the 'steps' - which equates to the number of floors passed through to transport all the waiting passengers:

`<number> steps`
