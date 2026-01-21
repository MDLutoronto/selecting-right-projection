---
title: "Selecting the right projection"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Selecting the right projection

Unsure of which projection to use in your GIS work? This tutorial will help you figure out your options.

For an accessible introduction to coordinate systems and map projections, please see the [Coordinate Systems and Projections](http://guides.scholarsportal.info.myaccess.library.utoronto.ca/geoportal/maps#s-lg-box-4434794) page in the Scholars GeoPortal user guide.

How do you decide what projected coordinate system is best for your map? If your GIS project is ultimately destined to be a printed map, you may choose to select one [based on its visual appeal](http://en.wikipedia.org.myaccess.library.utoronto.ca/wiki/List_of_map_projections), possibly a conformal projection that accurately preserves the shapes of landmasses. However, if you are conducting spatial analysis that involves accurate measures of areas or distances, you should ensure that your chosen projection minimizes this type of distortion, perhaps by opting for a true equal\-area projection. Other projections are suited for the representation of particular countries or regions, and were designed to minimize the distortion of both angles and distances across the areas they are tailored towards.

Some other things to keep in mind when selecting a projection:

* What coordinate system are your other datasets stored in? Many multi\-purpose geospatial datasets, especially those that cover large areas, tend to be stored in geographic coordinate systems (that is, not projected), so users can decide for themselves which projection is suitable for their needs. Changing from one projected coordinate system to another can introduce rounding errors that can lead to distortions in the resulting map. However, some geospatial data distributors tend to distribute their datasets in a projection well\-suited for their use – for example, the Ontario Ministry of Natural Resources frequently uses a Lambert Conformal Conic projection, while the City of Mississauga distributes datasets in UTM NAD83 Zone 17N. Looking at the projections that other datasets are stored in may give you an idea of which one is best for your area of study.
* Certain projections are better suited to larger and smaller scales of maps (remember, larger scale \= smaller area, smaller scale \= larger area; in other words, a map of Toronto would be at a larger scale than a map of Canada).
* ArcGIS organizes projected coordinate systems in folders named according to particular geographies or shared properties. Browsing through these folders may give you an idea of what projections might be suitable. For example, if working in Canada, take a look within the Projected Coordinate Systems \> Continental \> North America and Projected Coordinate Systems \> National Grids \> Canada folders.

Technique: [Projecting](/technique/projecting) \| Tools: [ArcGIS](/tools/arcgis), [Global Mapper](/tools/global-mapper-0), [QGIS](/tools/qgis) \| Data Format: [Raster](/data-format/raster), [Vector](/data-format/vector)**Date Created:** 2016\-04\-26**Updated:** 2021\-09\-02
