# Ultrasonic bed elevation measurements (sonar data)
These are ultrasonic bed elevation measurements taken at six points aling the flume centerline, in the test reach. 

They files are organized first by water flow rate and then by experiment type, whether equilibirum run or aggradational run. 

Each filename is divided into fields which specify, from left to right:
1. Sediment mass feed rate, in grams per minute (g/min);
3. Date the measurement was taken, in ISO 8601 format (YYYYMMDD); 
2. Volumetric water flow rate, in liters per second (lps);
4. Type of experiment, whether an equlibrium or aggradational run. 

For example, the file `8000-20141031-30lps-eq.csv` has the information for the set of measurements taken on the 31st of October of 2014, with a sediment feedrate of 8 kg/min and a water flow rate of 30 l/s. 

The file contents are comma-delimited. 

It should be noted that the sonar probe numbers are not sequential in the downstream direction. Their location is specified in each file in either centimeters or millimeters from the flume origin. Their ordering, from downstream-most to upstream-most goes are follows: 3, 1, 2, 4, 5, 6. 
