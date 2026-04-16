# data

## Dimensions

GlobalTemperatures: 3192 rows × 9 columns  
GlobalLandTemperaturesByCountry: 577462 rows × 4 columns  

## Glimpse Output

Rows: 3,192
Columns: 9
$ dt <date> 1750-01-01, 1750-02-01, ...
$ LandAverageTemperature <dbl> 3.034, 3.083, ...
...

## GlobalLandTemperaturesByCountry.csv

- `dt` : Date of the temperature observation
- `AverageTemperature` : Average temperature for the country (°C)
- `AverageTemperatureUncertainty` : Uncertainty associated with the average temperature
- `Country` : Name of the country

## GlobalTemperatures.csv

- `dt` : Date of temperature observation
- `LandAverageTemperature` : Avg. global land temperature (°C)
- `LandAverageTemperatureUncertainty` : Uncertainty associated with the land avg. temperature
- `LandMaxTemperature` : Max. recorded land temperature (°C)
- `LandMaxTemperatureUncertainty` : Uncertainty of the max. temperature
- `LandMinTemperature` : Min. recorded land temperature (°C)
- `LandMinTemperatureUncertainty` : Uncertainty of the min. temperature
- `LandAndOceanAverageTemperature` : Combined avg. temperature of land and ocean (°C)
- `LandAndOceanAverageTemperatureUncertainty` : Uncertainty of the combined avg. temperature