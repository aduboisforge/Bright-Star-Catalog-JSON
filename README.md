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

## Entry format

This is an array of objects with the following format:

`[{"harvard_ref_#":1,"RA":"00:05:09.90","DEC":"+45:13:45.00","Epoch":2000,"RA PM":"-00.012","DEC PM":"-00.018","MAG":"6.70","Title HD":"A1Vn"},
{"harvard_ref_#":2,"RA":"00:05:03.80","DEC":"-00:30:11.00","Epoch":2000,"RA PM":"+00.045","DEC PM":"-00.060","MAG":"6.29","Title HD":"gG9"},
{"harvard_ref_#":3,"RA":"00:05:20.10","DEC":"-05:42:27.00","Epoch":2000,"RA PM":"-00.009","DEC PM":"+00.089","MAG":"4.61","Title HD":"K0III"},
{"harvard_ref_#":4,"RA":"00:05:42.00","DEC":"+13:23:46.00","Epoch":2000,"RA PM":"+00.045","DEC PM":"-00.012","MAG":"5.51","Title HD":"G5III"},
{"harvard_ref_#":5,"RA":"00:06:16.00","DEC":"+58:26:12.00","Epoch":2000,"RA PM":"+00.263","DEC PM":"+00.030","MAG":"5.96","Title HD":"G5V"} . . . ]`

### Info Not Included

The information on notes, reference numbers to notes, and Radial Velocity were not included here.  

### 'Title HD #'

Some of these values were changed (i.e. by removing a space) to make formatting the JSON object easier, so these values are not completely accurate, but the Right Ascension and Declination values are accurate and can be used for calculations.

### License

This is released into the Public Domain, use this JSON file however you wish free of charge.
