********************************************************************************
Generated centennial weather data for Maktau Kenya
********************************************************************************

Paper Title: Evaluating AquaCrop yield predictions against measured data and
             simulated rainfall variability in rainfed semi-arid agrosystems
             in Kenya

Authors: Morice R. O. Odhiambo, Juuso Tuure, Janne Heiskanen, Sheila Wachiye,
         Kevin Z.  Mganga, Pirjo S. A. Mäkelä, Laura Alakukku, Petri Pellikka,
         Matti Räsänen

Corresponding Author: Morice R. O. Odhiambo  
Contact Information: morice.odhiambo@helsinki.fi

Date: 01/01/2026

********************************************************************************
Dataset Overview:
********************************************************************************
This dataset contains the 100-year simulated weather data for Maktau in Kenya.
The stochastic weather generator Long Ashton Research Station Weather Generator
(LARS-WG) version 8.0 (Semenov et al., 2002, Semenov, 2024) was used to generate
the weather data for the baseline period of 2013–2024.
The data was a daily time-series for precipitation (mm), maximum and minimum
temperature (°C) and solar radiation (MJ/m²/day⁻¹).
The data was applied in the AquaCrop-OSPy—the open-source python implementation
of AquaCrop model (Kelly and Foster, 2021) to simulate maize yields, 
crop evapotranspiration and plant–available soil water,
inorder to deepen our understanding of the interactions between rainfall variability,
 plant–available soil water and maize yields.

********************************************************************************
Dataset Contents:
********************************************************************************
1. Raw Simulated Weather Data

**Simulated Weather Data**  
The data is labeled as follows:
- `year` – Year for the growing season
- `jday` – Julian day/Day of the Year (DOY)
- `tmin`: Minimum temperature (°C) 
- `tmax`: Maximum temperature (°C) 
- `rain`: Rainfall (mm)
- `rad`: Solar radiation (MJ/m²/day⁻¹)

File:
- `maktau-100-years-generated-weather-data.txt`

********************************************************************************
2. Data Usage & Citation:
********************************************************************************
If you use this dataset or scripts, please cite it.
********************************************************************************
3. References:
- Semenov, M.A., Barrow, E.M., Lars-Wg, A., 2002. A stochastic weather generator for
  use in climate impact studies. User Man Herts UK 1–27.
- Semenov, M.A., 2024. LARS-WG stochastic weather generator for climate change impact
  assessment. Zenodo. https://doi.org/10.5281/zenodo.10632391
- Kelly, T.D., Foster, T., 2021. AquaCrop-OSPy: Bridging the gap between research and 
  practice in crop-water modeling. Agricultural Water Management 254, 106976.
 https://doi.org/10.1016/j.agwat.2021.106976

4. Contact Information:
********************************************************************************
For questions or further details, please contact:

- **Corresponding Author**: Morice R. O. Odhiambo
- **Email**: morice.odhiambo@helsinki.fi

********************************************************************************