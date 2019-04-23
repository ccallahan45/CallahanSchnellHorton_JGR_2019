# CallahanSchnellHorton_JGR_2019
Processed data for Callahan et al., JGR, "Multi-index attribution of extreme winter air quality in Beijing, China."

The ./data/ folder in this repository includes processed data for each air quality index from NCEP/NCAR R1 reanalysis and the CESM-Large Ensemble. It also includes final data used for constructing Figures 2-5. Figure 1 was constructed directly from the NCEP/NCAR R1 reanalysis without intermediate data.

"PPI1" refers to the original Pollution Potential Index created from Zou et al. (2017); "PPI2" refers to the new Pollution Potential Index created using equal weights for the two components (see paper text). All figures use PPI1.

Figure 2 was created directly from the processed index data ("R1_xx_1979-2016.nc") along with Beijing embassy PM2.5 data ("beijing_pm25_data_2010-2016.nc"). "RATIOS_xx.rds" are the files used to create Figure 3 (return period ratios). "LENS_TRENDS_xx.rds" are used to create Figure 4 (trends boxplots) and "IV_PERCENTS_xx.rds" are used to create Figure 5 (ratios of forced trend to internal variability).
