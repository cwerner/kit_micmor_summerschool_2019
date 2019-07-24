# Lecture: ETL, EDA
#inspiration #summerschool 

## Extract-Transform-Load
- classic data workflow
- explain history: "extract, transform, load (ETL) is the general procedure of copying data from one or more sources into a destination system which represents the data differently from the source(s) or in a different context than the source(s). The ETL process became a popular concept in the 1970s and is often used in data warehousing" [wikipedia](https://en.wikipedia.org/wiki/Extract,_transform,_load)
- "A properly designed ETL system extracts data from the source systems, enforces data quality and consistency standards, conforms data so that separate sources can be used together, and finally delivers data in a presentation-ready format so that application developers can build applications and end users can make decisions." *source:* Ralph., Kimball, (2004). The data warehouse ETL toolkit : practical techniques for extracting, cleaning, conforming, and delivering data. Caserta, Joe, 1965-. Indianapolis, IN: Wiley. ISBN 978-0764579233. OCLC 57301227.
- **Extract:** access specific for each format, urls, web scraping - including schemata valiudation
- **Transform:** data cleansing, format modification, data selection, encoding, data sorting/ ordering, deduplication 
- **Load:** into final system (direct or scheduled), additional archive
- tools: separate scripts, airflow, luigi

## Data Formats, data ingestion
- csv: very common, many varieties (xls even worse, don't use - but you have to be able to ingest)
- databases: sql, nosql, object-stores, ...
- scientific data: netcdf, hdf
- json: web, scraping etc.; flexible but unwieldy (geojson)
- buckets (S3, gcp buckets etc.)
- web protocols: opendap and others 
- databases: SQL et al., no details; data models, schemata: SQL-alchemy
- features of notebook: 
	- data validation: 
		- visual inspection
		- write a test! (packages: ingest (from anaconda), the ne mentioned in python bytes)
		- schemata
		- change over time: features are not necessarily static
		- version of feature properties, set bounds and valid ranges
	- data transformation:
		- data cleansing
		- date/ time parsing
		- aggregation (always keep raw data!)
		- generate new features


Data cleansing:
- validity
- accuracy
- completeness
- consistency
- uniformity

Integrity: accuracy + consistency + some validation (unspecific concept, do not use).

