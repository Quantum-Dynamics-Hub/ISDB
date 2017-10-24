# ISDB
Input (and) Structure Data Base

The points of this repository are:
a) to keep molecular/solid-state structures easily accessible to everyone, presumably in a number of common formats so that one potential users won't need to spend days figuring out how to create this or that complicated structure;
b) to provide input files for certain types of calculations. Again so that other users would know how exactly you got certain results or run certain types of calculations - these could be examples of calculations (a.k.a tutorials) or some study-tailored input files.
c) to help other people reproduce your results by running your simulations as they are.

So, in summary, the motto would be: organization - time-saver - reproducibility

Rules and practices (under development):

a) For each structure you'd like to provide, please create a SEPARATE FOLDER;
b) In each folder provide the TEXT DOCUMENT with a detailed description of every item in the folder. Try providing as much information as possible: what the file represents, any reference data and links that you might used to prepare the structure, the procedure/methodology/protocol on how the structure was obtained. If you are describing the input file, explain what it does, which program and which version it can work with, perhaps the computational enviroments, or even the way to run the calculation. Exaplain the content of the input files, especially the geometry (how was is obtained, or if this geometry is the same provided in any other files deposited, what are the units, etc).
c) For each structure, try creating the files in other formats, e.g. (.xyz, .in, .gau, etc.)
d) If any of the files you publish here was used in a published work, please provide the reference to the published paper where it is utilized (and don't change it after! or at least, indicate the snapshot of the github history tree which was used in the published work). This will REALLY BE HELPFUL to others.
c) You are welcome to deposit the human-readable output files, but only if they are not excessively large. Otherwise, you could simply deposit the most relevan part of that output file. 
d) Please, for any output file deposited, provide ALL the input files needed to reproduce it. If some of the files are commonly-available on internet (e.g. basis sets or pseudopotentials), it will suffice to provide the References or links (URLs) to them
e) Since this repository is for data files (which can quickly become a space issue), please abstain from very frequent file changes or the commits of some intermediate quality/test data. E.g. don't deposit files with weird geometry that resulted from protentially-erroneous calculations. Make sure, the files you are depositing are meaningful and might be of use to other people. 
