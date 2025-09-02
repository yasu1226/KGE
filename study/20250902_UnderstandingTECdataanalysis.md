## Summary
Today’s work can be summarized in two main points. First, TEC data were filtered to include only observation points within 200 km of the epicenter. Second, data were further filtered to focus on points with the largest TEC variations during the 10 minutes prior to the earthquake and visualized accordingly.

-----------------
## Understanding TEC data analysis
- Grasped the processing steps of the observational data plotting program
- Confirmed how to implement a distance filter within 200 km of the epicenter
- Zoomed in the map to focus on the Noto Peninsula area
  <img width="712" height="489" alt="image" src="https://github.com/user-attachments/assets/2c74ae55-62aa-4436-84e4-5296de4ec868" />

- Reviewed the use and benefits of a band-pass filter for extracting TEC variations
  - Organized the method of using a band-pass filter to extract TEC variations within a specific frequency range while suppressing the influence of noise and low/high-frequency components. This approach allows for clear visualization of relevant variations, such as pre-earthquake TEC anomalies.  
------------

## Improving TEC data visualization
- Added English labels to the colorbar
  <img width="1055" height="367" alt="image (74)" src="https://github.com/user-attachments/assets/97bd9f09-857a-4dca-9994-2cbb46ef0efe" />

- Evaluated and reviewed the indicator used for TEC variation magnitude
---------
## Extraction of top TEC variation points before the earthquake

- Calculated TEC variation over the 10 minutes prior to the earthquake
- Extracted and plotted only the top 20 points with the largest variation
- Enabled visual confirmation of variation magnitude using a color map
---------------
