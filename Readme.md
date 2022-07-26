Tips
In order to obtain results in GUI mode, please change user parameters in Test Plan for outputfiles such as Results.csv and DataFileLocation.csv.
In to generate HTML Report, go to Tools, Generate Report and choose select Results.csv, included user.properties file and your desired output location.
Click Generate Report.

//------------------------------------------------------------------------------------------------------------------------------------------------------
In order to obtain results while running headless, run the following command in Linux

```java
jmeter -f -n -t ~/OutletPages_V01.jmx -l ~/result.jtl -e -o resultsPage
```
