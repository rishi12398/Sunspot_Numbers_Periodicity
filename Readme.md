# Sunspot Values Periodicity

Data Used: Monthly Mean Total Sunspot Numbers form 01/1749 to 04/2020 in CSV format
* To replicate the results, change the first row of the csv file to match the column names as : 
`year  month  fraction  value   sd  observations  indicator`

[Data](http://www.sidc.be/silso/datafiles)

Raw Data Plot:


![image](https://github.com/rishi12398/Sunspot_Numbers_Periodicity/blob/master/graphs/raw_data.png?raw=true)


After applying fast fourier transform :


![image](https://github.com/rishi12398/Sunspot_Numbers_Periodicity/blob/master/graphs/fft_zoomed_in.png?raw=true)


The peaks correspond to a period of : 10.853 years and 90.909 years
