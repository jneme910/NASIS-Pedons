# NASIS-Pedons
This repository contains ArcGIS Tools that query soil pedons from the National Soils Information System (NASIS) and compiles a spatial dataset from them.

Tool Runs Python 
1. Get Bounding box coordinates --- Calculated from ArcGIS
2. KSSL: WEB_ANALYSIS_PC_PEDON_NUMBER_SUM -- Send Coords to NASIS -- Returns the number of pedons that are within bounding box
3. KSSL: 'WEB_EXPORT_PEDON_BOX_COUNT -- Returns a list of PedonIDs that are within bounding box
4. KSSL: WEB_AnalysisPC_MAIN_URL_EXPORT
