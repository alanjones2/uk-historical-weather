# uk-historical-weather

The data folder in this repo contains the historical weather data from various weather stations in the UK as CSV files.

The data is derived from the Met Office text data found here

[https://www.metoffice.gov.uk/research/climate/maps-and-data/historic-station-data](https://www.metoffice.gov.uk/research/climate/maps-and-data/historic-station-data)

The original data represented null values as the string '---'. These have been replaced with null values. Also the original data distinguished between two types of sunshine measurement - this has been removed. See the Met office page, above, for more detail.

Additionally, a mean temperature column has been added. The data columns are:

- Year: year of measurement
- Month: month of measurement
- Tmax: maximum monthly temperature in ºC
- Tmin: minimum monthly temperature in ºC
- AF: number of days in the month when there was an air frost
- Rain: number of centimetres of rain in a month
- Sun: number of hours of sunshine in a month
- status: whether the data is provisional
- Date: the date - a combination of year and month
- Tmean: mean monthly temperature in ºC

This data is distributed in accordance with [UK Open Government License](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) and may be used under the same conditions.
