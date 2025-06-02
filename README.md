# EvolutionaryGamesToolbox
This MATLAB toolbox provides simulation and analysis tools for evolutionary game tournaments based on the Iterated Prisoner's Dilemma. It supports fitness-based and imitation-based evolutionary dynamics.

# The Report
There is a report for this project that can be found in 'Report/report.pdf' that explains in detail what is this toolbox about and analyses the results of the experiments. It also provides documentation on the functions, which can also be found in 'Documentation/matlab_toolbox_documentation.txt'.
ν
# Installation instructions
1a) Unzip the folder - In case of the toolbox provided as a .zip file
- Extract the "EvolutionaryGamesToolbox.zip" file to any location on your system.
1b) Or clone the repository 
- Open Git Bash in your desired location on your system and write "git clone https://github.com/geogkioul/EvolutionaryGamesToolbox.git".

2) Open MATLAB

3) Navigate to the folder in MATLAB
- Use the MATLAB built in folder browser or use 'cd' to navigate to /EvolutionaryGamesToolbox/

4) Set path
- After navigating to the toolbox folder run the following line on MATLAB
addpath(genpath(pwd));
- This will set the path so you can run all of the toolbox's functions and scripts.

# Running the experiments
You can now run any of the examples' scripts shown in the Report by running the commands 'exampleXX' on MATLAB, where 'XX' is the example ID

Examples 1-12b are for Fitness Dynamics. Notice that examples 7-12 need an additional specifier in the end 'a' or 'b' for the version of the experiment as described on the report. So you would write 'example2' or 'example6' but 'example8a' or 'example11b'. All scripts can be found in folder 'Examples/Scrips Fitness Dynamics' while the figures produced in the folder 'Examples/Figures Fitness Dynamics'. These figures are the ones also presented in the Report.

Examples 13-24 are for Imitation Dynamics. None of them need any additional 'a' or 'b' specifiers. All scripts can be found in folder 'Examples/Scrips Imitation Dynamics' while the figures produced in the folder 'Examples/Figures Imitation Dynamics'. These figures are the ones also presented in the Report.

Full details on the parameters (B, T, J, initial populations etc) for each example can be found in the Report or in the scripts' code.