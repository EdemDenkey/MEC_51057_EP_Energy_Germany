# MEC_51057_EP_Energy_Germany
This respository was created for a group project in the course Machine Learning for Clmate and Energy (MEC_51057_EP) at Ecole Polytechnique. We apply Machine Learning approaches to Energy related Data for Germany.

The description of the underlying datasets can be found in the Jupyter Notebook, thank you.


Dataset
SARAH-3

SARAH-3 (DOI-Link) records different parameters related to surface solar radiation. The dataset is derived from satellite imaging and generated and distributed by the European Organisation of Meteorological Satellites (EUMETSAT) Climate Monitoring Satellite Application Facility. SARAH-3 covers most of the Earth. In our project we focus on the data for Germany. The methodology for SARAH-3 was developed in 2023, it has been applied to data from 1983 to the present at 30-minute resolution. Out of the available parameters we use the solar surface irradiance (SIS) (in W/m^2), because it is the most relevant for estimating the capacity factor of solar photovoltaic cells.

There are 3 NetCDF files: Two weaks in summer 2025 with 30min resolution, two weaks in winter 2025 with 30min resolution, 2018-2025 with daily resolution.
SMARD Data - Energy Germany (Source: German Federal Network Agency):

Whole Sale Electricity Price

This CSV file contains the whole sale electricity price time series data for Germany (including Luxembourg) in €/MWh from 01.01.2019 until 31.12.2024 in hourly resolution.
Installed Generation Capacity

This CSV file contains data concerning the capacity in MW for the different sources of electrical energy installed in Germany: biomass, hydropower, wind offshore, wind onshore, PV, other renewable energies, nuclear, lignite, bituminous coal, natural gas, hydro pumped storage, other conventional energies.
The data is time series data from 01.01.2015 until 01.01.2024 with an hourly resolution.
Actual Production

This CSV file contains the actual historical electricity production for all different technologies in MWh as time series data from 01.01.2015 until 31.12.2024 in hourly resolution.
Technologies: biomass, hydropower, wind offshore, wind onshore, PV, other renewable energies, nuclear, lignite, bituminous coal, natural gas, hydro pumped storage, other conventional energies
Actual Electricity consumption (load)

This CSV file contains time series data from 01.01.2015 until 31.12.2024 in hourly resolution related to the actual electricity consumption (load) in Germany in MWh: the load, load including pumped storage, pumped storage, residual load (residual load = load - generation from renewable energies).
Merra-2 (NASA)

One .nc file contains wind speeds in m/s at 50m height over a rectangular space over Germany as daily time series data from 2015 to 2024
Another .nc file contains surface pressure in kPa over the same rectangular area as daily time series data from 2016 to 2024
Double-click to edit this empty Markdown cell

