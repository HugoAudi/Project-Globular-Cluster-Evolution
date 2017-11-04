# Project-Globular-Cluster-Evolution
Here we share all the files and codes for our project

1. DESCRIPTION OF THE FOLDER:

In the folder Python Codes and Files are placed all the files containint the Python codes (with extension .ipy) and all the data files generated by the python codes (with extension .dat)

In the Geneva group data file the stellar evolution model data is contained and it has everything we need. The file geneva_data.dat is the same file with same data but just with some deleted rows so the python code can read it properly.

In the evolution.ipy python code file we open the geneva data and we separate the data for different initial stellar masses, because we want the evolution for different stars with different stellar masses. And we save files for each initial mass

The M*.dat files contain all needed data in order to make the stellar evolution plots on the HR diagrams. We have a data file for each initial mass containing the logTe, logL and the Age.

In the evolution2.ipy python code file we open the M*.dat files and plot the stellar evolution paths in the HR diagram. In this file I also tried to make an animation of the stellar evolution but didn't manage to do it right so I left it commented. 

In the plot_glob_clust.ipy the code for creating a plot of the globular cluster is contained.

***********************************************************************************************************************

2. WORK DONE:

So far we have managed to download all the needed data for the stellar evolution and managed to do the evolution plots in the HR diagram.

04.11.2017 (Marko):
- The Initial Mass Function has been utilized to compute the numbers of stars dN for each M within a given mass interval dM.
This is done in the file imf.ipy
- The file plot_glob_clust.ipy has been updated and now the plot contains the correct distribution of number of stars per certain mass based on the calculations of dN in the file imf.ipy and the size of the stars corresponds to their mass. 

***********************************************************************************************************************

3. WORK TO BE DONE:

1) Next we need to do the animation of the evolution.
First, we can build an animation of the evolution of single star with respect to time.
After this we can build the animation of the evolution on the HR for the whole cluster.

2) We need to build the plot with the spatial distribution of stars within the globular cluster.
  - we need to figure out how to do the colors.


**********************************************************************************************************************

4. SOME COMMENTS:

My python codes are scripts and executed in the terminal. We can use jupyter as well.

Download the folder Python Codes and Files to start working on the project, because it contains the needed data files.



