VolunteerStats
===================

Overview
--------------
Repository for volunteer stats data RDF cubes, published at: http://data.gmdsp.org.uk/themes/volunteering

Usage
-------

Open data on volunteering is published by Macc at: https://www.manchestercommunitycentral.org/policy-and-influence/open-data

This project takes this data and models the data into RDF data cubes, utilising the GMDSP Generic Stats Cube (https://github.com/GMDSP-Linked-Data/GenericStatsCube) project and the W3C Data Cube ontology (http://www.w3.org/TR/vocab-data-cube/)

Methodology
------------

- Raw data is transformed in Open Refine (http://openrefine.org/), with the RDF Extension (http://refine.deri.ie/)
- Data is also "de-normalised" see: http://blogs.worldbank.org/opendata/unpivoting-data-excel-open-refine-and-python
- Each Open Refine project within this repository, also contains the RDF Skeleton, which can be applied to new/updated datasets

Resources
-------------

- The complete Open Refine project for each facet of volunteering stats is included in the /RefineProjects directory
- The relevant JSON steps to apply the RDF Skeleton is also included in the /RefineProjects directory
