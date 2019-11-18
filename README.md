# The Evolution of European Motorways, 1920—2020

![alt text](https://github.com/StudioFolder/european-motorways/blob/master/VAM_European-Motorways_screen-01.png)

This repository contains the datasets created for the visualisation published here: https://www.vam.ac.uk/commission/european-motorways-1920–2020.

"The Evolution of European Motorways 1920–2020" has been commissioned by the Victoria and Albert Museum in London, and has been developed as part of the exhibition "[Cars: Accelerating the Modern World](https://www.vam.ac.uk/exhibitions/cars)," curated by Brendan Cormier (23 November 2019—19 April 2020). It shows the history and growth of motorways across Europe over a period of a hundred years, and it provides additional information on the political, economical and cultural context of their development. 

While initially collected from the sources listed below, a lot of work has been put into the analysis, integration, and refinement of the transportation network data used in the visualisation and shared here.
---

The new and updated datasets are made available here.

* **European Motorways**. The original vector files from OpenStreetMap have been simplified and consolidated, while the construction dates for each motorway's segment have been added to the dataset. Each motorways is presented as a single-line feature with the following attributes: </br>
`int_ref`: International reference number </br>
`ref`: National reference number </br>
`country`: ISO ALPHA-3 country code </br>
`start_year`: year of start of construction (`0` when unknown) </br>
`end_year`: year of end of construction </br>
`length`: length in meters </br>
</br>
An example of the attributes' table can be found below:

| int_ref        | ref           | country  | start_year  | end_year  | length  |
|:------------- |:------------- |:----- |:----- |:----- |:----- |
| E 451 | A 51 | DEU | 1933 | 1935 | 440392 |


The dataset can be downloaded from here. 

* **Pan-European Transport Corridors**. The dataset can be downloaded from here.

* **Trans-European Transport Network (TEN-T)**. The dataset can be downloaded from here.

![alt text](https://github.com/StudioFolder/european-motorways/blob/master/VAM_European-Motorways_screen-02.png)
</br></br>

***
### Initial data sources
The sources of the reference data for the transportation network and the basemap are listed below.

**Elevation data**</br>
[📦](https://www.usgs.gov/land-resources/eros/coastal-changes-and-impacts/gmted2010?qt-science_support_page_related_con=0#qt-science_support_page_related_con) Danielson, J.J., and Gesch, D.B., 2011, Global multi-resolution terrain elevation data 2010 (GMTED2010).

**Historical borders**</br>
[📦](http://nils.weidmann.ws/projects/cshapes/shapefile.html) Weidmann, Nils B., Doreen Kuse, and Kristian Skrede Gleditsch. "The Geography of the International System: The CShapes Dataset." _International Interactions_ 36, no. 1 (2010).

**Waterbodies, Cities**</br>
[📦](https://www.naturalearthdata.com/downloads/) Natural Earth 

**Motorways data (initial reference)**</br>
[📦](https://www.geofabrik.de/data/download.html)OpenStreetMap Contributors

**International E-roads Network**</br>
[📦](https://sedac.ciesin.columbia.edu/data/set/groads-global-roads-open-access-v1) Center for International Earth Science Information Network (CIESIN) / Columbia University, and Information Technology Outreach Services (ITOS) / University of Georgia. 2013. _Global Roads Open Access Data Set_, Version 1 (gROADSv1). Palisades, NY: NASA Socioeconomic Data and Applications Center (SEDAC).

**Pan-European Transport Corridors (initial reference)**</br>
[📦](https://web.archive.org/web/20110223194354/http://www.unece.org/trans/main/ter/Countries/PanEuCorridors.html) United Nations Economic Commission for Europe (UNECE).

**Trans-European Transport Network (TEN-T), initial reference**</br>
[📦](https://ec.europa.eu/transport/infrastructure/tentec/tentec-portal/site/en/maps.html) European Commission, Directorate-General for Mobility and Transport (DG MOVE).</br>[📦](https://eurogeographics.org/products-and-services/open-data/topographic-data/) EuroGlobalMap 2019, © EuroGeographics.
</br></br>

***
### Credits
The visualisation has been designed and developed by [Studio Folder](http://www.studiofolder.it/) (Marco Ferrari, Elisa Pasqual, Letizia Bernardelli, Simone S. Melis, Mattia Salvà) and [Angelo Semeraro](http://angelosemeraro.info/). The historical research for the chronological sequence of the motorways construction has been completed by Brendan Cormier and Esme Hawes (Victoria and Albert Museum).

