# GOAT
README

***1. SYSTEM REQUIREMENTS***

All software dependencies and operating systems (including version numbers)：
Microsoft Windows 10

Software version that has been tested on：
R version 4.3.1 (2023-06-16)

Required R libraries:
readxl ==1.4.3
e1071 == 1.7-14

Any required non-standard hardware：
Not applicable.


***2. INSTALLATION GUIDE***

Not applicable.


***3. INSTRUCTIONS***

Before running, make sure "repository.R", "test" and "preset" files are in "src/" folder.

Before running, set the root path (line 3).

Lines 43-216  Input stationary.file and dynamic.file, output four lines of odds, dynamic and static model parameters for the day. 

Lines 220-256 Input solo.odds, output 2 rows of odds and pre.window.size accumulated over 3 days.

Lines 258-335 Input cum.odds, output risk level and 4 cutoff.

***4. POSTSCRIPT***

Our R code implementation generates fully reproducible results, because random seeds are set to fixed values to guarantee identical randomization.

Total expected run time on a 'normal' desktop computer:
5s
