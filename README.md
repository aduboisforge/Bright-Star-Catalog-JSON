# Bright Star Catalog in JSON format

The Yale Bright Start Catalog is a catalog of all stars with a stellar magnitude of 6.5 or brighter (meaning that they are visible to the naked eye).  The first list of stars was originally composed by Yale astronomer Frank Schlesinger in 1930. This catalog can be accessed below:

[Visit the Yale Bright Star Catalog](http://tdc-www.harvard.edu/catalogs/bsc5.html)


This dataset is based on version 5 of this catalog.  There are 9110 entries total in this catalog.  However, the data was cleaned of entries with invalid values or stars with missing data that may cause errors in a program, such as  '00:00:00???'.   That leaves the grand total of stars listed in this JSON file as 9096 stars (because 14 stars total had missing or invalid values). 

## Data included in JSON object

- Harvard Reference Number 
- Right Ascension
- Declination
- Epoch (which is always 2000)
- Right Ascension PM
- Declination PM
- Title HD # 

### Info Not Included

The information on notes, reference numbers to notes, and Radial Velocity were not included here.  

### 'Title HD #'

Some of these values were changed (i.e. by removing a space) to make formatting the JSON object easier, so these values are not completely accurate, but the Right Ascension and Declination values are accurate and can be used for calculations.

### License

You are free to use this JSON file however you wish free of charge.
