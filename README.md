# AAMD_Geospatial
This project uses a combination of geographic information systems (GIS), remote sensing data, and API-based isochrone modeling to evaluate the potential audience reach of major U.S. art museums. 


By integrating Mapbox’s isochrone API with LandScan night-time population rasters, I calculated and visualized the population living within a 30-minute drive of five leading institutions. These population figures were then used to normalize museum performance metrics (e.g., attendance, gift shop revenue), allowing for more equitable comparisons between museums operating in vastly different demographic catchments. The results were visualized using clean, minimalist dashboards suitable for both exploratory analysis and stakeholder communication. 

Five museums were selected as the focal points of the analysis:

- The Art Institute of Chicago
- Baltimore Museum of Art
- Museum of Fine Arts Boston
- National Portrait Gallery (Washington D.C.)
- Museum of Modern Art (New York)

For each museum, a 30-minute driving isochrone was fetched using the Mapbox API. These are polygonal representations of the area reachable by car within 30 minutes. 
