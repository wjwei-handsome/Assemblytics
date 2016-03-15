# Assemblytics - an analytics tool for the detection and analysis of assembly-based variants

Assemblytics is available online at http://qb.cshl.edu/assemblytics/

If you would like a stand-alone version (for instance to comply with rules preventing upload of data to a third-party website), this repository contains all the code for running Assemblytics yourself, from unique anchor filtering and calling variants to creating the output plots and summary tables. 

To run Assemblytics, simply copy all the scripts in this repository into your path and make them executable (chmod +x script_name) if necessary.

Follow the instructions at http://qb.cshl.edu/assemblytics/ for how to prepare your data and get a delta file for Assemblytics. 

Then run as:
```
Assemblytics delta_file output_prefix unique_anchor_length path_to_R_scripts

```
