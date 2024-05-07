# InSAR_Sensitivity_Tool
InSAR Sensitivity Index Tool - Google Earth Engine App
This Google Earth Engine tool is designed to calculate the InSAR sensitivity index for a user-defined Area of Interest (AOI).


Here's how a user could interact with the tool:
Selecting Region of Interest (ROI): Users can choose their region of interest by navigating to the desired area on the map. They can then use the polygon tool located at the top-left corner of the map to draw the region they want to analyze.
Choosing Orbit and Time Span: Users can select whether they want to analyze SAR data from the ascending orbit (ASC) or the descending orbit (DSC). Additionally, they can specify the time span they want to analyze.
Loading Sensitivity Index Layer: After drawing the region of interest and selecting the orbit and time span, the tool will load the sensitivity index layer. This layer likely shows the calculated sensitivity index for the specified parameters.
Notice Below the Time Slider: This notice informs the user of the number of available images for the selected ROI and time span. It's essential because some frames may be missing, which could affect the accuracy of the sensitivity index calculation.
Handling Missing Frames: In cases where there aren't enough images available for calculating the sensitivity index, the tool likely notifies the user and may suggest adjusting the time span or selecting a different region to ensure accurate results.

Example layers:
This tool provides two layers for calculating the SAR sensitivity index of the Central Yunnan city cluster, utilizing data from both ascending and descending orbits.

Copyright@YU-RADASENS
Junjie Ou,  oujj@ynu.stu.edu.cn 
Mengshi Yang, yangms@ynu.edu.cn
