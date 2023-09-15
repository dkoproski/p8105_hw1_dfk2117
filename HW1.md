Hw1
================
2023-09-14

# Loading Required Libraries

``` r
library(moderndive)
library(tidyverse)
```

# Looking at the dataset

``` r
data("early_january_weather")
?early_january_weather
nrow(early_january_weather)
```

    ## [1] 358

``` r
ncol(early_january_weather)
```

    ## [1] 15

Looking at “?early_january_weather”, the variables in the data set are
as follows: “origin” refers to the weather station the data came from;
the variables year, month, day, and hour describe the time of recording;
“temp” is the weather station’s temperature reading in Fahrenheit;
“dewp” is the dewpoint in Fahrenheit; “humid” is the relative humidity;
“wind_dir” is the wind’s direction in degrees; “wind_speed” is the wind
speed in miles per hour; “wind_gust” is the wind gust speed in miles per
hour; “precip” is the precipitation in inches; “pressure” is the
atmospheric pressure in millibars; “visib” is visibility in miles; and
finally time_hour is the day, month, year and time of the reading as a
single variable. The “early_january_weather” data set has 358 rows, and
15 columns.
