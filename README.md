# Land-Reclamation-and-Population-Density-Estimation-for-Singapore-using-Remote-Sensing
Course project for MECE E4520 : Data Science for Mechanical Systems

**NOTE: **
The files "Landsat8_image_processing_initial_experimentation.ipynb" and "Landsat_Image_processing_final_experiments.ipynb" files are very large and hence cannot be previewed.
Please download the .ipynb files or the .html files of the same to view them.

Land Reclamation analysis is done by operating on Landsat images to extract information to keep track of Land area of Singapore (SG) over the years.

The Total land area is extracted from Landsat 8 images of Singapore for 2013 to 2020 and the data for 1960 to 2012 is taken from https://data.gov.sg/.

Landsat 8 images are charachterised by a combination of path number and row number.
For Singapore, path number = 125 and row number = 59.
These Landsat images cover large areas of Malaysia and Indonesia as well. 

The file "Extracting_SG_from_Landsat8_images.ipynb" contains the code to crop out Singapore from the original Landsat image.
The code to crop Landsat images using Shapefiles from Google Earth was written by referring https://github.com/arvindnswamy/RemoteSensing.

The file "Landsat8_image_processing_initial_experimentation.ipynb" contains the code for the initial experiments done to segregate water from land inclusing methods to reduce cloud cover and NDWI.

The file "Landsat_Image_processing_final_experiments.ipynb" contains code for the final pipeline used to create binary images segregating land and water.

The file "Population_data_World_Bank.ipynb" contains code for extracting the historical population data of Singapore using data from the World Bank.

The file "Predicting the future of SG.ipynb" contains code that fits Machine Learning models to Land Reclamation and Population data to predict future Population Density estimates.

The file "FutureWork_Population_density_and_Housing_density_analysis_from_HDB Data.ipynb" contains some starter code for future work as described in the project report.






