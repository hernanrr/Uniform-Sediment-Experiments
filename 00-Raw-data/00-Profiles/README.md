# Water surface elevation and bed elevation profiles
These are water surface elevation and bed elevation profiles taken during the course of the experiments.

They files are organized first by water flow rate and then by experiment type, whether equilibirum run or aggradational run. 

Each filename is divided into fields which specify, from left to right:
1. Sediment mass feed rate, in grams per minute (g/min);
2. Volumetric water flow rate, in liters per second (lps);
3. Date the measurement was taken, in ISO 8601 format (YYYYMMDD); 
4. Sequential numbering of the measurement (xxx);
5. Type of experiment, whether an equlibrium or aggradational run. 

For example, the file `16000-20lps-20150806-002-eq.csv` has the information for the second set of measurements taken on the 6th of August of 2015, with a sediment feedrate of 16 kg/min and a water flow rate of 20 l/s. 

The file contents are formated in three columns, with the column header on the second row, as seen, for example, in the first 5 rows of file `1000-30lps-20140718-001-eq.csv`: 

Run|20140718-001-eq|1000
--|--|--
x (m)|WS (m)|BED (m)
2|37|16
2.1|37|16
2.2|36.5|15

It should be noted that, despite the mass feed rate being included in the first row of the files, it is not reliably there in all files. Defer to the information in the file name. 
