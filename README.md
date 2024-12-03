# Statistics for P114 programs using the instruments at the 2p2 (GROND, WFI and FEROS)

A script to check the ESO archive for the available science data for a list of programs, obtaining the number of files, total exposure times and total execution times (assuming specific overheads).
Based on the allocated time (in hours) for Category-A (PID_A) and the time asked for in the proposal (PID_B), the fraction of completeness is also calculated.
The script requires an input  file ( e.g. P114_pi.list) containing:
name,first_name,email,PID_A,PID_B,instr,A [hr],B [hr],comments (optional).

It also writes 2 different versions of a *.csv file, containing all this information, in case you want to create your own visualisation.

The script does not download any data, only provides a table with the amount of data available in the for each listed program and provides a table in pdf format.
