# Bright Star Catalog in JSON format

The Yale Bright Start Catalog is a catalog of all stars with a stellar magnitude of 6.5 or brighter (meaning that they are visible to the naked eye).  The first list of stars was originally composed by Yale astronomer Frank Schlesinger in 1930. This catalog can be accessed below:

[Visit the Yale Bright Star Catalog](http://tdc-www.harvard.edu/catalogs/bsc5.html)


This dataset is based on version 5 of this catalog.  There are 9110 entries total in this catalog.  However, the data was cleaned of entries with invalid values or stars with missing data that may cause errors in a program, such as  '00:00:00???'.  That leaves the grand total of stars listed in this JSON file as 9096 stars (because 14 stars total had missing or invalid values).

## Data included in JSON object

- Harvard Reference Number 
- Right Ascension
- Declination
- Epoch (which is always 2000)
- Right Ascension PM
- Declination PM
- Title HD # (number used to refer to stars)

### Info Not Included

The information on Notes and not reference number were not included here.  The R-Velocity values were also not included, but are in the catalog.

### Where are the star names?

Not every star that we can see actually has a name.  Only about 1000 have names like Polaris, out of the 9110 stars that we can see (as least from what I've read) so Title HD Number is a system used by astronomers to refer to stars instead.

### License

You are free to use this JSON file however you wish free of charge.
