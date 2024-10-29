In this document, we present the workflow for reproducing the analysis. The following code can be used to obtain the results shown in the main document starting from any telemetry data, enabling the reproduction of the analysis for other species, diseases, and ecosystems with a few modifications. To minimize changes in the code, we recommend organizing the starting telemetry data for each study area with one row per GPS location and with the following columns:

ID: Individual identifier
SP: Species
lat: Location latitude (WGS 84)
long: Location longitude (WGS 84)
TIME: Location time of the day
DATE: Location date

However, other data structures can also be used if modifying the code.

Note that we carried out the analysis for two study areas: Doñana National Park (DNP) and Sierra de San Pedro (SSP). Although the workflow is designed for one study area, results for both study areas are presented, with repeated code hidden for better understanding.
