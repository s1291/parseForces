# Introduction

This is a simple script written in AWK to parse the content of `forces.dat` files generated by OpenFOAM forces function object.
 ## Note:
 Currently, the script supports only the output generated by OpenFOAM foundations version (openfoam.org).

 # How to use it
First download the script `parseForces`.
The usage is as simple as running the following command:

./parseForces --to-csv forces.dat > forces.csv

You can omit the `--to-csv` flag to get a space separated fields.

