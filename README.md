# Mach24 Rocket Simulation
Actual Simulation Files used in the Mach 24 Rocketry Competition


As part of a student led organisation within the University of Limerick, I was the Simulations Team Lead in charge of simulating the rocket that our team both designed and built, in order to simulate the launch, and flight trajectories
To do this I used an open-source Python based software called RocketPy, and using parameters specific to our rocket, ran large batches of scenarios, and analysed output data to inform design decisions


RocketPy is best run within Google Colab:
Mach24-Sionna-SimWeather-FlightSim.ipynb - Uses Pre-Set simulated weather instructions such as wind speed and direction (easiest to run for testing) 
Mach24-Sionna-FlightSim.ipynb - Uses GPS to pull the weather forcast for the specified location (location currently set to Campbeltown Airport, Scotland, where Mach 24 was held) 



To run either notebook just click the button in the top to 'Open in Colab' 
Once connected upload the 4 files needed to the Colab instance:
	* AirfoilDegreesCSV.csv
	* Cesaroni_3419L645-P.eng
	* DragOnCSV.csv
	* DragOffCSV.csv
	
Then click 'Run All'




Mach24-Sionna-SimWeather-FlightSim.ipyn should already be pre-ran and have the graphs and other outputs already created and visible by just opening the file in GitHub
