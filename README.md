# Arcgis_RPY_to_OPK
Conversion tool for converting Roll, Pitch, Yaw/heading to Omega, Phi, Kappa values, for use in ArcGIS pro stereomapping.

Tool creates Omega, Phi, Kappa field if they are not present in the table view, then calculates them based on selected Roll, Pitch, Yaw fields. 
Make sure that the file/table is not open in ArcGIS while running the tool, or the updatecursor used to calculate the new values might not 
acquire a lock.
