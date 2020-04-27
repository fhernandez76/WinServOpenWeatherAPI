# WinServOpenWeatherAPI
Example of Windows service for calling Open Weather API

The Windows service was programmed for .Net Framework 4.5.2 and above.

The following parameters are part of the configuration of Windows Service:

  *. Interval: represents the number of seconds each time the Windows Service will consult Openn Weather API, by default is configured to 300 seconds (5 minutes)
  
  *. StartTime.  time at which the WinServ considers a valid operation time
  
  *. FinishTime.  time at which the WinServ considers a not valid operation time
  
  *. OWApiID.  ID to call Open Weather API
  
  *. City.  Name of the city to consult Open Weather API
  
  *. Country.  Name of the country where the city is allocated.
  
  *. Units.  System in which the results will be returned, can be either metric (C) or imperial (F)
  
  *. URL.  URI of API to consult
  
  *. OutputFile.  Name and path of the destination file (CSV file)
  
  *. FieldDelimiter.  Character that will be used in CSV file as field delimiter, by default "," is defined.
