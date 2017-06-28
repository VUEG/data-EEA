## Corine Land Cover (CLC) 2012, Version 18.5.1

### Description

CORINE Land Cover (CLC) was initiated in the late 1980s to standardize data
collection on land in Europe to support environmental policy development. The
reference year of the first CLC inventory was 1990, and the update cycle has
become 6 years. The number of participating countries has increased over time -
currently 39, including 33 European Environment Agency (EEA) member countries
and six cooperating countries, with a total area coverage of over 5,8 Mkm2. The
project is coordinated by the EEA under the framework of the Copernicus
programme and implemented by national teams under the management and quality
control of the EEA.

Ortho-corrected high spatial resolution satellite images provide the geometrical
and thematic basis for mapping. In-situ data (e.g. topographic maps,
ortho-photos, and ground survey data) are essential ancillary information. The
basic technical parameters of CLC (i.e. 44 classes in nomenclature, 25 hectares
minimum mapping unit (MMU) and 100 meters minimum mapping width) have not
changed since the beginning of the project, therefore the results of the
different inventories are comparable. The mapping method is computer assisted
photo-interpretation (CAPI) in majority of countries, however some countries
apply semi-automatic methodologies by integrating existing land use data,
digital classification of satellite images or cartographic generalisation of
high-resolution, national land use/land cover data.

CORINE Land Cover Changes (CLCC) are derived from satellite imagery by the
direct mapping of changes based on image-to-image comparison. Change mapping
applies a 5 ha MMU to pick up much more detail in CLCC layer than in CLC status
layer.

Two European validation studies have shown that the achieved accuracy is above
the specified minimum (85 %) for CLC, as well as for CLCC.

CLC is widely used in indicator development, environmental modelling and land
use/land cover change analysis in the European context. It can contribute to a
wide range of studies with European coverage, e.g.: ecosystem mapping, modelling
the impacts of climate change, landscape fragmentation by roads, abandonment of
farm land and major structural changes in agriculture, urban sprawl, water
management.

### Provenance information

Due to the user interface at EEA website, automated retrieval is not possible.
Hence all data have been downloaded manually.

resources: `data/org`
retrieved_from: http://land.copernicus.eu/pan-european/corine-land-cover/clc-2006/view
retrieved_date: 2017-06-28
retrieved_by: Joona Lehtomäki <joona.lehtomaki@gmail.com>
modified_date: 2017-06-28
modified_by: Joona Lehtomäki <joona.lehtomaki@gmail.com>

### Folder structure and processing

```
├── org                 <- Original data received from EEA website.
└── clc_2012            <- Processed and filtered files
```

The files in sub-directory `org` are as they have been received from EEA. Folder
`clc_2012` contains processed files. The processing steps are the following:

1. Unzip and rename dataset and README file

See [Snakemake file](https://github.com/VUEG/data-EEA/blob/master/clc2006/Snakefile) for details.

### Metadata

#### Cell values

For further information, see the following documents:

+ `data/org/population-density-disaggregated-with-corine-land-cover-2000-2.pdf`

#### Geospatial

Following metadata applies to all individual species rasters in the dataset.

```

```

### License

http://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32013R1159

### Contributors

+ Joona Lehtomäki (<joona.lehtomaki@gmail.com>)
