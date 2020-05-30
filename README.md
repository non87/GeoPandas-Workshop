# GeoPandas-Workshop
Contains the material for the GeoPandas Spring 2020 Workshop.

The workshop is divided into two parts. Part 1 regards the foundation of Pandas Part 2 introduces GeoPandas. Both parts consists of Notebook plus external data to be analyzed. The data is contained in this same repository, be sure to download the entire depository.

## Note on Versioning

This workshop was created using Python 3.6, Pandas 1.0.3 and GeoPandas 0.7. The versions of Pandas and GeoPandas are critical for the correct execution of the code. You can follow the instructions below to get the correct versions on your machine or you can run the code on Google Collaboratory.

## How to Run the Notebooks
The notebooks require Pandas, GeoPandas, matplotlib and numpy. The code requires that your version of Pandas and GeoPandas is up to date. To be sure that is the case you can use the Google Collaboratory version of the notebooks. 
To use the colaboratory version, it is sufficient to open the following links, let your browser load the file and click on the "open in colab" icon that will appear on top of the file:

1.   [Part 1 on Colab](https://github.com/aarcher07/stats_models/blob/master/Linear%20Modelling%20in%20R.pdf , "Click here to access the first notebook in your browser")
2.   [Part 2 on Colab](https://github.com/non87/GeoPandas-Workshop , "Click here to access the second notebook in your browser") -- this is still to be created.

If you prefer to use your local machine, then you can create a specific Anaconda environment with this line of code:

`conda create -c conda-forge -n geopandas_workshop python=3.6 matplotlib numpy geoPandas pandas`

It is important that you specify conda-forge as a channel in order to get the last version of GeoPandas. The default channel still distributes version 0.6 at this time.

