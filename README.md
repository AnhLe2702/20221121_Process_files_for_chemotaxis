# 20221121_Process_files_for_chemotaxis
This code allows merging of multiple csv files into 1 large file, then number the values in the TID column with an increment of 1 for each new cell detected in the PID column
This code is specifically used for processing csv files for chemotaxis analysis to allow for computing directionality index later on when using the Chemotaxis tool later. It merges the MTrackJ/Points files together and automatically number the TID correctly whenever a new cell (when the ID in the PID column goes back to 1) is detected. 
