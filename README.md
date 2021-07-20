# new-survey-london-life-and-labour

To accesss original data, see:

Johnson, P. A., Bailey, R. E., Baines, D. E., Raspin, A., Hatton, T. J. (1999). New Survey of London Life and Labour, 1929-1931. [data collection]. 2nd Edition. 
UK Data Service. SN: 3758, http://doi.org/10.5255/UKDA-SN-3758-1

From this data I used regex to extract as many firm names as I could for each individual in the dataset. 
This process was the source for all firm variables in my own ammended dataset.

Columns 19:36 of my csv file are all derived using the original dataset. They fill in info on individuals (dummies indicating marriage status, child below the age of 10, if they worked in a wage board industry).
As well as local factors like local unemployment levels. 

The education variable was constructed by placing each individual into one of three bands. 
There were two major educational reforms over the life cycle of my sample, the 1893 education act which made education in London compulsory up until the age of 11, and the Fisher’s 1918 Education Act which raised the school leaving age to 14.  
These defined my three bands, with each individual’s age was used to assign them into their respective band. 

Please contact for any questions, code will be added to this repo at a later date.
