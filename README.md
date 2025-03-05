 24-Hours Simulation of Disconnected area: Peak District 

INTRODUCTION
This Project is the evaluation of a Pre-Signature scheme for connectivity-limited environments.


Before running the simulation, ensure you have the following installed:
- SUMO (Simulation of Urban MObility) - [Download SUMO](https://sumo.dlr.de/docs/Downloads.php)
- Python (for scripting)

SUMO INSTALLATION
1. Download SUMO from the official website: https://sumo.dlr.de/docs/Downloads.php
2. Ensure all prerequisites are installed (e.g., Python, a C++ compiler, and necessary libraries).
3. Follow the installation instructions specific to your operating system.
   - For Windows: Run the installer and follow the prompts.
   - For Linux: Compile from source using the provided makefile.
   - For macOS: Use Homebrew or MacPorts for installation.

USAGE
To run the simulation, follow these steps:
- SUMO GUI can be launched using: 'sumogui'
- Basic command to start a simulation: 'sumo -c <configuration file>'
- Detailed usage instructions are available in the documentation.

## Project Structure
- `/networks` - Contains network files (.net.xml) defining the road networks.
- `/flows` - Contains traffic flow files (.poly.xml) specifying the traffic demand.
- `/scripts` - Contains Python scripts for simulation control.



-From the sumogui file, generate a dump file that includes all the vehicle's locations in each timestep. 
-From the DataSourceCode Folder, use the provided scripts that calculates each communication based on different requirements to generate Excel files. 
-From the ResultsSourceCode Folder, use the provided scripts to generate the graph that explains the results. 





DOCUMENTATION
Visit the official SUMO documentation at: https://sumo.dlr.de/docs/index.html



