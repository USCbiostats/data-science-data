---
name: [met_all.gz]
short-desc: [meteorological data from National Oceanic and Atmospheric Administration (NOAA) weather stations, subset to the continental U.S.]
date-collected:  2020-07-19
source-url: [ftp://ftp.ncdc.noaa.gov/pub/data/noaa/]
keywords: [weather stations, meteoroloy]
format: [gz, csv]
---

Codebook for meteorological data. For further details, particularly on quality control flags and type codes, see <ftp://ftp.ncdc.noaa.gov/pub/data/noaa/isd-format-document.pdf>

* USAFID        &emsp;US Air Force fixed weather station identification number           
* WBAN          &emsp;NOAA fixed weather station identification number
* year          &emsp;Year of measurement
* month         &emsp;Month of measurement
* day           &emsp;Day of measurement
* hour          &emsp;Hour of measurement     
* min           &emsp;Minute of measurement
* lat           &emsp;Latitude of fixed weather station   
* lon           &emsp;Longitude of fixed weather station       
* elev          &emsp;Elevation of fixed weather station     
* wind.dir      &emsp; Wind direction (angle 0-365)
* wind.dir.qc   &emsp; Wind direction quality control flag  (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* wind.type.code  &emsp;  Wind type (B=Beaufort, C=calm, N=normal,Q=squall)
* wind.sp       &emsp; Wind speed (m/s)
* wind.sp.qc    &emsp; Wind speed quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* ceiling.ht    &emsp; Ceiling height (m)
* ceiling.ht.qc &emsp; Ceiling height quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* ceiling.ht.method &emsp; Ceiling height method (A=aircraft, B=balloon,...)
* sky.cond      &emsp; Sky conditions
* vis.dist      &emsp; Visibility distance (m)
* vis.dist.qc     &emsp; Visibility distance quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* vis.var         &emsp; Visibility variability (N=not variable, V=variable)
* vis.var.qc      &emsp; Visibility variability quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* temp            &emsp; Air temperature (C)
* temp.qc         &emsp; Air temperature quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* dew.point       &emsp; Dew point temperature (C)
* dew.point.qc    &emsp; Dew point temperature quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* atm.press       &emsp; Atmospheric pressure (hPA)
* atm.press.qc    &emsp; Atmospheric pressure quality control flag (0-9; 0=passed, 1=passed, 2=suspect, 3=erroneous)
* rh              &emsp; Relative humidity (derived)
