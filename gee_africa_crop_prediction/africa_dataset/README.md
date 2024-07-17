# Dataset Information
This folder contains the respective datasets for the fusion tasks

1. `building_block_cropyield_data`: Consists of the crop yields data from the [Our World in Data](https://ourworldindata.org/crop-yields)
2. `building_block_data_from_gee`: Consists of the cropland area as well as the environmental variables extracted through the Google Earth Engine
3. `merged_data_yield.csv`: This is the finalized dataset utilized throughout the EDA and the modelling section in the Assignment

`merged_data_yield.csv` Column Information: 
- country
- year
- cropland_area (Sq km)
- ndvi_mean (no unit)
- temperature_mean (K)
- average_annual_precipitation_mm (mm)
- clay_mean_value (g/kg)
- sand_mean_value (g/kg)
- nitrogen_mean_value (cg/kg)
- phh2o_mean_value (no unit)
- soc_mean_value (dg/kg)
- wheat_yield_tonnes_per_hectare
- rice_yield_tonnes_per_hectare
- bananas_yield_tonnes_per_hectare
- maize_yield_tonnes_per_hectare
- soybean_yield_tonnes_per_hectare
- potatoes_yield_tonnes_per_hectare
- beans_yield_tonnes_per_hectare
- peas_yield_tonnes_per_hectare
- cassava_yield_tonnes_per_hectare
- cocoa_beans_yield_tonnes_per_hectare
- barley_yield_tonnes_per_hectare

Dataset Size: (294, 22)