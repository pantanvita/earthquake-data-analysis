# **Earthquake Data Analysis (1965-2016)**

For Day 08 assignment, I downloaded the **[Significant Earthquakes 1965-2016](https://www.kaggle.com/datasets/usgs/earthquake-database)** dataset from Kaggle. 

 ## About the dataset

This dataset includes a record of the date, time, location, depth, magnitude, and source of every earthquake with a reported magnitude 5.5 or higher since 1965 till 2016. 
The data has been collected by The National Earthquake Information Center (NEIC). 

 ## Analysis performed

1. **Gutenberg–Richter Law (Magnitude vs Frequency)**

   * It is a classic law in seismology that states earthquake frequency decreases exponentially with magnitude.

   * This plot produces a straight line that indicates → strong scientific validation plot.

<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/37b74a9b-9ef1-408e-8a49-94369bd8f32c" />

2. **Depth vs Magnitude Relationship**
  
   * To analyze whether deeper earthquakes are generally stronger.

3. **Distribution of Earthquakes Magnitudes**

   * Compares the frequency of earthquake occurence against their magnitudes
   * The histogram represents an inverse relationship i.e. earthquakes with higher magnitudes have a lower occurence frequency and vice-versa.
   
4. **Number of Earthquakes per Year**

   * Line plot that depicts the occurence of earthquakes globally every year

5. **Earthquake Density Map (Latitude × Longitude)**

   * This plot offers visualization that uses a geographic coordinate system to show the spatial concentration of earthquake epicenters over a specific area and period.

   * Essentially, it highlights the areas on the Earth's surface where earthquakes occur most frequently. 

6. **Energy Release Estimation**
  
   * Rule followed: log10(𝐸) = 1.5𝑀 + 4.8

   * The equation is the Gutenberg-Richter relation (or similar energy-magnitude relation) which links the magnitude of an earthquake to the seismic energy it radiates.

7. **Temporal Clustering & Aftershock Behavior**

   * Temporal clustering refers to the tendency for earthquakes to group together in time, with periods of high activity followed by relative quiet.

   * This phenomenon is most prominently observed in aftershock sequences, which are series of smaller earthquakes that follow a larger "mainshock" as the Earth's crust adjusts to the sudden stress change. 

   * A rolling window highlights clustering

8. **Azimuthal Gap Analysis**

    * Azimuthal gap analysis in seismology evaluates how well seismic stations surround an earthquake's epicenter, measuring the largest angle between adjacent stations from the epicenter.
  
    * Lower the gap → better location accuracy

9. **Azimuthal Gap vs Magnitude**

    * Compares the azimuthal gap with the magnitude of the earthquake

10. **Global Earthquake map**

    * Generates an interactive map of the world highlighting most prominent areas prone to seismological activities globally

 <img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/accf71d9-17d4-48b7-92c6-ecea640ec44d" />

**NOTE:** 
This map cannot be viewed on GitHub as GitHub cannot render Folium inside notebooks. 
To view the map, run the script on your platform.

 ## Files required

 1. `database.csv.zip` (downloaded from Kaggle- https://www.kaggle.com/datasets/usgs/earthquake-database)
 2. `database.csv` (Unzipped and extracted file using Python v3.14)
 3. `earthquake-data-analysis-final.ipynb` (Python file run on Jupyter)

 ## Installations

 1. Anaconda
 2. Jupyter Notebook
 3. Python v3.9+
 4. numpy
 5. pandas
 6. matplotlib.pyplot
 7. seaborn
 8. folium
 

 ## Steps performed

 1. Installed Anaconda followed by launching Jupyter Notebook
 2. Downloaded the dataset as a .zip file locally
 3. Unzipped and extracted the file into a .csv file
 4. Performed the above mentioned analysis on Jupyter notebook
 
