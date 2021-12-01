## Conventions
Arrows mean that the particular subject goes into something else. Rounded squares are the program itself, while sharp squares are specific input/libraries/events that can be connected with other things. The hexagonal shapes mean you're in the program itself, and that they are pieces of the program.

## Level 0
* **Xbox Controller Input**: user inputs data via Xbox Controller (or something of the like)
* **2D Combat Simulation on Unity/Python**: essentially the program runs with the input given by the Xbox Controller input
* **Execute Scenario**: display the changes caused by the controller input running through the 2D combat sim

## Level 1
* **Xbox Controller Input**: user inputs data via Xbox controller (or something of the like)
* **Script**: data is run through scripts created by the developers to tell what data is being manipulatied
* **Adjustment of Paramters**: If the user is opting to adjust paramters, adjust those the user specified
* **Confirmation**: If the user chooses to confirm, confirm settings
* **Execute Simulation Scenario**: Run the simulation after the user confirms the settings
* **Results from Simulation**: Display resulting data to the user after the scripts are run for executing the scenario
* **Python/Unity Engine**: Internal mechansims of the program to be run

## Level 2
* **User**: The person who is interacting with the program
* **Xbox Controller Input**: The tool for which the user uses to interact with the program
* **Script**: data input by the user is run through scripts created by the developer
* **Libraries**: scripts are created from the Python/Unity libraries, so they are used in the scripts
* **Adjusting Parameters**: if the user choosed to adjust the parameters, it would impact the below areas
  * **Entities**: how many entities are present in the simulation for interaction with the environment, teams are chosen
  * **Projectile Speed**: speed at which projectiles move, like bullets, environmental projectiles (like rocks, cars, etc)
  * **Lighting**: how dark the environment is, this may impact entity accuracy
  * **Weapon Type**: what kind of weapons will be used in the simulation (think COD classes)
  * **Gravity**: how strong the gravity in the environment is. May impact projectile paths, entity motion
* **Confirming Parameters**: user chooses to confirm the parameters they adjust/don't adjust prior to confirmation
* **Run Scenario**: occurs after the user confirms the parameters for the simulation to run
* **Determine Results**: occurs while simulation is running, which entities survive, how long the scenario runs for, etc.
* **GUI**: runs for displaying the results and shows what occurs in the sim
* **Visual Simulation**: Displays to user what occurs in the scenario
* **Display Results**: After sim is finished, displays the resulting data presented from the simuation
