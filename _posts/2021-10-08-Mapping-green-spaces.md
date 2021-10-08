---
layout: post
title:  "Mapping public green spaces in Manchester"
subtitle: "Using python and geopandas to analyse access to green space"
author: camila
categories: [ spatial analysis ]
tags: [ python, geopandas, matplotlib, spatial analysis, open data ]
image: gmcr_green_areas.png
source: https://github.com/neperiana/data-science-projects/blob/mapping-green-areas/mapping_urban_green_areas/mapping_mcr_green_spaces.ipynb
---

The benefits of having public green areas around when living in a densily populated city are many, from encouraging exercise or providing spaces for socializing to decreasing noise and air pollution.

I aim to map public green areas in Manchester and how they distribute accroding to it population. Fields in Trust have done an amazing job at mapping the whole of the UK and stablishing their green-space-index, but I aim to have my own go at it using python and geopandas.

### GIS and spatial analysis
tbs

### Where to find geo open data
tbc

### Geopandas for data manipulation
tbd

```python
fp = 'data/boundary_lines/district_borough_unitary_region.shp'
df = gpd.read_file(fp)
```

~~~
fp = 'data/boundary_lines/district_borough_unitary_region.shp'
df = gpd.read_file(fp)
~~~
{: .language-python}

### Mapping with matplotlib
tbc

### Running spatial calculations
tbc

### To wrap-up
tbd
