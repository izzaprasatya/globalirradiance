# solar-irradiance
This is the pyGRASS code for automating the yearly solar irradiance analysis using the r.sun module in GRASS GIS, a process that is time-consuming when performed manually. Useful DEM-derived parameters, such as slope and aspect, were already computed using the r.slope.aspect module. The Linke turbidity coefficient is based on average Linke turbidity values for tropical climates, while the albedo coefficient is derived from the land use type of the area of interest, which is dense mixed forest and plantation (characterized by high canopy cover and moisture). The r.colors module is used to apply an intuitive color scheme to the output. Additionally, the r.univar module is employed for further analysis, particularly to determine the maximum, minimum, and average radiation values for each month.
