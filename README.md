# sumo-tools
A collection of scripts and smaller codes related to SUMO

1. **sumo-run**: a bash script to conveniently set up and run a calculation.
Essentially helps you define all necessary parameters and collect all the folders
you need for the calculation.
Just make sure you have specified the $SUMODIR variable which defines the 
install directory where the SUMO executables resides. Also make sure that 
the same directory is on the PATH. E.g. for bash: in your .bashrc, add:
```bash
export SUMODIR=<SUMO install directory>
export PATH="$SUMODIR:$PATH"
```
Further instructions in the script.
