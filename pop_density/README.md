## Population density disaggregated with Corine land cover 2000

### Description

Raster data on population density using Corine Land Cover 2000 inventory.

### Provenance information

Due to the user interface at EEA website, automated retrieval is not possible. Hence all data have been downloaded manually.

resources: `data/org`  
retrieved_from: http://www.eea.europa.eu/data-and-maps/data/population-density-disaggregated-with-corine-land-cover-2000-2  
retrieved_date: 2016-12-05  
retrieved_by: Joona Lehtomäki <joona.lehtomaki@gmail.com>  
modified_date: 2016-12-06  
modified_by: Joona Lehtomäki <joona.lehtomaki@gmail.com>  

### Folder structure and processing

```
├── org                 <- Original data received from EEA website.
└── pop_density         <- Processed and filtered files
```

The files in sub-directory `org` are as they have been received from EEA. Folder `pop_density` contains processed files. The processing steps are the following:

1. Copy and rename dataset and README file

See [Snakemake file](https://github.com/VUEG/data-EEA/blob/master/pop_density/Snakefile) for details.

### Metadata

#### Cell values


For further information, see the following documents:

+ `data/org/population-density-disaggregated-with-corine-land-cover-2000-2.pdf`

#### Geospatial

Following metadata applies to all individual species rasters in the dataset.

```
"tiled": false,
"transform": [
  100.0,
  0.0,
  1500000.0,
  0.0,
  -100.0,
  5310000.0
],
"lnglat": [
  5.766179047748763,
  51.15894538872371
],
"count": 1,
"bounds": [
  1500000.0,
  940000.0,
  6550000.0,
  5310000.0
],
"nodata": -2147483648.0,
"res": [
  100.0,
  100.0
],
"interleave": "band",
"driver": "GTiff",
"crs": "+ellps=GRS80 +lat_0=52 +lon_0=10 +no_defs +proj=laea +towgs84=0,0,0,0,0,0,0 +units=m +x_0=4321000 +y_0=3210000",
"shape": [
  43700,
  50500
],
"width": 50500,
"colorinterp": [
  "grey"
],
"compress": "lzw",
"height": 43700,
"dtype": "int32"

```

### License

EEA standard re-use policy: unless otherwise indicated, re-use of content on the EEA website for commercial or non-commercial purposes is permitted free of charge, provided that the source is acknowledged (http://www.eea.europa.eu/legal/copyright). Copyright holder: Joint Research Centre (JRC).

### Contributors

+ Joona Lehtomäki (<joona.lehtomaki@gmail.com>)

### References

+ Gallego F.J., 2010, A population density grid of the European Union, Population and Environment. 31: 460-473
http://doi.org/10.1007/s11111-010-0108-y
