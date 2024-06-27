# Data Product Canvas - Berlin LOR Housing Stock

## Input Ports

**Input ports define the format and protocol in which data can be read (database, file, API, visualizations)**

This data product uses statistical crime data provided
by [Polizei Berlin](https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin/) available under the following
URLs

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)
* [Fallzahlen&HZ%202013-2022.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202013-2022.xlsx)
* [Fallzahlen&HZ%202014-2023.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202014-2023.xlsx)

## Data Product Design

**Describe everything you need to design a data product on a conceptual level.**
**Ingestion, storage, transport, wrangling, cleaning, transformations, enrichment, augmentation, analytics, SQL
statements, or used data platform services.**

* [converts Excel data into csv](../lib/transform/data_csv_converter.py)

## Output Ports

**Output ports define the format and protocol in which data can be exposed (db, file, API, visualizations)**

The data of this data product is available under the following URLs

* [berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00.csv)
* [berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00.csv)
* [berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00.csv)
* [berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00.csv)
* [berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00.csv)
* [berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00.csv)
* [berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00.csv)
* [berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00.csv)
* [berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00.csv)
* [berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00.csv)
* [berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00.csv)
* [berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-crime-atlas-source-aligned/main/data/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00.csv)

## Metadata

### Ownership

**Domain, data product owner, organizational unit, license, version and expiration date**

* ownership: Open Lifeworlds
* domain: statistics
* license: CC-BY-4.0

### Schema

**Attributes, data types, constraints, and relationships to other elements**

* `offences`: total number of offences
* `robbery`: total number of cases of robberies
* `street_robbery_purse_snatching`: number of street robberies and purse snatching
* `bodily_harm`: total number of cases of bodily harm
* `dangerous_and_grievous_bodily_harm`: number of cases of dangerous and grievous bodily harm
* `deprivation_of_liberty_coercion_threat_stalking`: number of cases of deprivation of liberty, coercion, threat,
  stalking
* `theft`: total number of theft cases
* `motor_vehicle_theft`: number of vehicle theft cases
* `theft_from_motor_vehicle`: number of cases of theft from motor vehicle
* `bicycle_theft`: number of bicycle theft cases
* `residential_burglary`: number of cases of residential burglary
* `fire_offences`: total number of fire offences
* `arson`: number of cases of arson
* `damage_to_property`: total number of cases of damage to property
* `damage_to_property_by_graffiti`: number of cases of damage to property by graffiti
* `narcotics_offences`: number of narcotics offences
* `kieztaten`: number of offences with a strong connection to the offender's place of residence

### Semantics

**Description, logical model**

### Security

**Security rules applied to the data product usage e.g. public org, internal, personally identifiable information (PII)
attributes**

## Observability

### Quality metrics

**Requirements and metrics such as accuracy, completeness, integrity, or compliance to Data Governance policies**

### Operational metrics

**Interval of change, freshness, usage statistics, availability, number of users, data versioning, etc.**

### SLOs

**Thresholds for service level objectives to up alerting**

## Consumer

**Who is the consumer of the Data Product?**

## Use Case

**We believe that ...**
**We help achieving ...**
**We know, we are getting there based on ..., ..., ...**

We believe that this data product can be used to derive any kind of data based product.

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

This data product is source-aligned since the contained csv files represent the source data.

## Ubiquitous Language

**Context-specific domain terminology (relevant for Data Product), Data Product polysemes which are used to create the
current Data Product**

* **LOR**: (German: Lebensweltlich orientierte Räume) life-world oriented spaces
* **district**: (German: Bezirk)
* **forecast area**: (German: Prognoseraum)
* **district region**: (German: Bezirksregion)
* **planning area**: a spatial unit whose spatial development is planned by the public authorities

---
This data product canvas uses the template
of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).
