# Flux-footprint-estimation-under-hetergoneous-condition
# README file 
## Sensitivity of analytical flux footprint models in diverse source-receptor configurations: A Field experimental study
This README file describes the data used in the study that are obtained for EC flux tower. Raw data at 10 Hz frequency obtained from three synchronized EC towers were analyzed to estimate the fluxes using EddyPro software, version 6.2.1 and was further averaged at half-hourly time interval.
The experimental setup consisted of three EC flux towers with one each located in the cotton T3 (Zm = 3 m) and sugarcane T2 (Zm = 6 m) fields to capture the homogeneous fluxes originated from individual fields, with a third, taller tower located in the sugarcane field T1 (Zm = 8 m) to capture the mixed fluxes originated from both the fields

**EC flux System Components**
3D sonic anemometer,
One open-path fast response infrared gas analyzer (IRGASON-EB-IC, Campbell Sci. Inc., USA),
logger (CR3000, Campbell Sci.Inc., USA)

**1) Overview of the data file contents**
The folder containd the EddyPRO  version 6.2.1. output files with the Timepstamp.These data files are provided as comma-separated values (CSV) formating. Missing data records are indicated by the -9999 value.

**2) Variable List**
Eddy pro full output variables can be accessed 
[Variable List](https://www.licor.com/env/support/EddyPro/topics/output-files-full-output.html)

# List of Data
The field experiments took place from 13 March2017 - 20 December2017 and we conducted the following experiments. All the experimental data are kept in .csv file in the respective folders named corresponding to the observations

1. EC_fluxdata folder contains observed EC fluxes from the three EC systems during the experimental period . Het, Cot ,and Sug represnts the EC fluxes from T1, T3, and T2.
 Ust ,Lin, ASin, LE, Uin,Xin, CO2, WUE,and wdir represents friction vlocity,Obukhov length, Atmospheric stability, Latent heat of Evaporation, mean wind speed, upwind distance, CO2 flux, Water Use Efficiency, and wind direction respectively. 

2. Flux_aggregation_and_Parameter_aggregation folder contains flux footprint predicted by the FFP and K&M model considering Arithmetic average, Area-weighted average, and Effective input parameter for the calculation of effective roughness length (zoeff).
FFP and K&M performance under these three flux aggregation and parameter aggregation is in the respective file that is further used to calculate the relatve bias between the observed and predicted flux footprit considering heteroginity of canopy surface.

3.Supplementary folder consisits of K&M and FFP flux footprint prediction considering parameter and flux aggregation and also has the observed CO2 flux values that is further used to compute the biases between observed and predicted values.

4.WUE folder consists daily averaged water use efficiency calculated and measured for the homogeneous and hetreogeneous fluxes.

For any query please contact the corresponding author.contact.shwetakumari.me@gmail.com
