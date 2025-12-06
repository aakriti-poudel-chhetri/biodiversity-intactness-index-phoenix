# Biodiversity Intactness Index Change in Phoenix, Arizona

This repository contains materials for the final project for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

## About

Phoenix, located in Maricopa County, Arizona, has experienced rapid urban growth over the past two decades. Between 2001 and 2021, Maricopa County had the largest increase in developed land in the United States, driven by the expansion of residential, commercial, and transportation infrastructure. This urbanization fragments natural habitats, reduces vegetation cover, and puts pressure on local wildlife. The Biodiversity Intactness Index (BII) provides a measure of how intact ecosystems remain compared to their natural state. By analyzing BII values for Phoenix’s county subdivisions from 2017 to 2020, we can quantify how urban expansion has affected species richness and ecosystem health, revealing areas where biodiversity has declined due to increased human activity. This analysis highlights the ecological consequences of rapid city growth and can help guide future conservation planning.

## Repository Structure

```
biodiversity-intactness-index-phoenix/
│
├── README.md
├── bii-phoenix.ipynb
└── .gitignore
     └───data
         └─── tl_2020_04_cousub
         
```

## Data

A `data/` directory is created inside the `biodiversity-intactness-index-phoenix` repository. Due to the large size of data, the data folder is included in `.gitignore` and is not tracked by version control.

In this analysis, two primary datasets are used.

**Biodiversity Intactness Index (BII) Time Series**
This dataset is retrieved from the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity#overview). The dataset includes raster covering the Phoenix subdivision from 2017 and 2020. These rasters measure how intact ecosystems are compared to their natural state, providing a way to track changes in biodiversity over time. The analysis is limited to the area defined by the coordinates [-112.826843, 32.974108, -111.184387, 33.863574], covering all of the Phoenix subdivision.

**Phoenix Subdivision Shapefile** 
This dataset is retrieved from [Phoenix Subdivision Shapefile](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.2020.html#list-tab-790442341), downloaded from the Census County Subdivision files for Arizona. This shapefile provides polygon geometries for the county subdivisions, enabling spatial analysis and mapping of the BII data within the exact boundaries of Phoenix. To enhance visualization and context, shapefiles are used to show the Phoenix subdivision in relation to surrounding areas, helping to better understand the geographic distribution of biodiversity changes.

## References

Microsoft Planetary Computer. (n.d.). Biodiversity Intactness. Retrieved December 5, 2025, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity#overview

US Census Bureau. (2025b, November 26). TIGER/Line shapefiles. Census.gov. https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.2020.html#list-tab-790442341

## Course Information

 - **Course Title:** EDS 220 - Working with Environmental Datasets
 - **Term:** Fall 2025

### Teaching Team:
- **Instructor:** Dr. Carmen Galaz García

- **Co-instructor**: Dr. Annie Adams

Complete description for the this project can be found on the [Biodiversity Intactness Index Change](https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/final-project.html).

**Author:** Aakriti Poudel