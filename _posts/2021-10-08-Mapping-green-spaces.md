---
layout: post
title:  "Mapping public green spaces in Manchester"
subtitle: "Using python and geopandas to analyse access to green space"
author: camila
categories: [ spatial analysis ]
tags: [ python, geopandas, matplotlib, spatial analysis, open data ]
image: 001_gmcr_green_areas.png
source: https://github.com/neperiana/data-science-projects/blob/mapping-green-areas/mapping_urban_green_areas/mapping_mcr_green_spaces.ipynb
---

The benefits of having public green areas around when living in a densily populated city are many, from encouraging exercise or providing spaces for socializing to decreasing noise and air pollution.

I aim to map public green areas in Manchester and how they distribute according to it population. Fields in Trust have done an amazing job at mapping the whole of the UK and stablishing their [green-space-index](https://www.fieldsintrust.org/green-space-index), but I aim to have my own go at running an spatial analysis using python and geopandas.

### GIS and spatial analysis
GIS stands for Geographic Information System and it is a spatial system that enables the creation, management, analysis and mapping of all types of data. GIS allows to understand information within their geographic context, being able to spot geographical patterns, which would be very defficult to spot without the aid of a map. This type of analysis is called spatial analysis, and it is commonly used across many industries to discover patterns, incidents and coordinate spatial resources.

There are a few main concepts that is perhaps best to tackle first:

<center>
    <figure>
        <img src='./../images/001_gmcr_green_areas/coordinate_vs_projection.png' figcaption='hola'>
        <figcaption><i>Difference between GCS and PCS.</i></figcaption>
    </figure>
</center>

* A **geographic coordinate system** (GCS) is a reference framework that defines the locations of features on a model of the earth. It’s shaped like a globe—spherical. Its units are angular, usually degrees.

* A **projected coordinate system** (PCS) is flat. It contains a GCS, but it converts that GCS into a flat surface, by projecting points into the plane. Its units are linear, for example in meters. Note that not all projections conserve area, therefore two shapes with same area.

### Where to find geo open data
tbc

### Geopandas for data manipulation
tbd

```python
fp = 'data/boundary_lines/district_borough_unitary_region.shp'
df = gpd.read_file(fp)
```

### Mapping with matplotlib
tbc

### Running spatial calculations
tbc

### To wrap-up
tbd
