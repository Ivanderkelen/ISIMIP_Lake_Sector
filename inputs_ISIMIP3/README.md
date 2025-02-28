## Input lake morphology data to use in ISIMIP3 global lakes simulations <br />
## However, we reccommend using the netcdf files in the folder **[inputs_ISIMIP3_netcedf]** <br />

**Hylak_id.tif (from [lake_identification]:** unique lake identifier, shared by HydroLAKES and GLOBAthy<br />
**Lake_type.tif (from [lake_identification]:** HydroLAKES indicator for lake type; 1:Lake; 2:Reservoir; 3:Lake control (i.e. natural lake with regulation structure)<br />
**HL_selected (from [lake_identification]:** shapefile collection of the final selected lakes for each pixel. Please, find the HL_selected.shp file in lake_identification/output <br />
**HLid_biglakes.tif (from [lake_identification]:** ID of big lakes, for plotting purposes <br />
**biglakes_mask (from [lake_identification]:**  mask for plotting big lakes <br />

**A_raster.tif (from [Hypsographics]):** lake surface area, in square kilometers <br />
**Dmax_raster (from [Hypsographics]):** maximum lake depth, in meters <br />
**Dmean_raster (from [Hypsographics]):** mean lake depth, in meters <br />
**V_raster.tif (from [Hypsographics]):** Total lake volume, in km3)<br />
**Vd_raster.tif (from [Hypsographics]):** Volume development (unitless) <br />

**[rasters_hypsographic]:** Rasters with the hypsographic information from [Hypsographics] in raster format. Generated with Calculate_rasters.R and the file isimip.sh (this is just for running the R file in Undarius) <br />
