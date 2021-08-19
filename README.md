# weather-database
Daily updated weather station database in SQLITE3 format.

Brand weather station: [DAZA WT1081][dazawt1081]

Date of begin: 2020-01-15

Data collected:
 - Outside temperature (ºC)
 - Heat index (ºC)
 - Dew point (ºC)
 - Humidity (%)
 - Pressure (mbar)
 - Rain (mm)
 - Rain index (mm/hr)
 - Wind (velocity (m/s), direction, max, RMS, average)
 - Other values
 
 Time, moonrise and moonset, sunrise and sunset are calculated.


This data is collected and stored on a Raspberry Pi with [WeeWx][weewx]. You can view [database documentation here][database1] and [here][database2].

[//]: # ()
   [weewx]: <http://weewx.com/>
   [dazawt1081]: <http://www.meteostar.com.ar/descargas/estaci%C3%B3n-meteorol%C3%B3gica-wt1081-meteostar.pdf>
   [database1]: <https://weewx.com/docs/usersguide.htm#Database>
   [database2]: <http://www.weewx.com/docs/customizing.htm#The_database>
