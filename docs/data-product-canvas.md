
# Data Product Canvas - Berlin LOR Crime Atlas (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data product providing Berlin LOR crime data
* updated: 2025-10-27

## Input Ports

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202012-2021.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202012-2021.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202013-2022.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202013-2022.xlsx)

### Kriminalitätsatlas Berlin

* owner: Polizei Berlin
* url: https://daten.berlin.de/datensaetze/kriminalit%C3%A4tsatlas-berlin

**Files**

* [Fallzahlen&HZ%202014-2023.xlsx](https://www.kriminalitaetsatlas.berlin.de/K-Atlas/bezirke/Fallzahlen&HZ%202014-2023.xlsx)

## Transformation Steps

* [Data extractor](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/extract/data_extractor.py) extracts data from inout ports
* [Data copier](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_converter.py) converts Excel files to CSV format
* [Data aggregator](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_aggregator.py) aggregates data to be used as output ports

## Output Ports

### Berlin Lor Crime Atlas 2012 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2012-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2012-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2012-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2012-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-csv/berlin-lor-crime-atlas-2012-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2012 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2012-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2012-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2012-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2012-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00-parquet/berlin-lor-crime-atlas-2012-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2013 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2013-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2013-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2013-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2013-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-csv/berlin-lor-crime-atlas-2013-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2013 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2013-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2013-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2013-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2013-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00-parquet/berlin-lor-crime-atlas-2013-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2014 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2014-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2014-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2014-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2014-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-csv/berlin-lor-crime-atlas-2014-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2014 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2014-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2014-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2014-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2014-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00-parquet/berlin-lor-crime-atlas-2014-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2015 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2015-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2015-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2015-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2015-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-csv/berlin-lor-crime-atlas-2015-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2015 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2015-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2015-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2015-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2015-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00-parquet/berlin-lor-crime-atlas-2015-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2016 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2016-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2016-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2016-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2016-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-csv/berlin-lor-crime-atlas-2016-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2016 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2016-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2016-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2016-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2016-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00-parquet/berlin-lor-crime-atlas-2016-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2017 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2017-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2017-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2017-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2017-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-csv/berlin-lor-crime-atlas-2017-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2017 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2017-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2017-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2017-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2017-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00-parquet/berlin-lor-crime-atlas-2017-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2018 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2018-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2018-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2018-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2018-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-csv/berlin-lor-crime-atlas-2018-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2018 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2018-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2018-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2018-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2018-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00-parquet/berlin-lor-crime-atlas-2018-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2019 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2019-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2019-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2019-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2019-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-csv/berlin-lor-crime-atlas-2019-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2019 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2019-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2019-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2019-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2019-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00-parquet/berlin-lor-crime-atlas-2019-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2020 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2020-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2020-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2020-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2020-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-csv/berlin-lor-crime-atlas-2020-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2020 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2020-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2020-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2020-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2020-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00-parquet/berlin-lor-crime-atlas-2020-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2021 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2021-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2021-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2021-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2021-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-csv/berlin-lor-crime-atlas-2021-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2021 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2021-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2021-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2021-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2021-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00-parquet/berlin-lor-crime-atlas-2021-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2022 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2022-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2022-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2022-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2022-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-csv/berlin-lor-crime-atlas-2022-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2022 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2022-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2022-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2022-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2022-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00-parquet/berlin-lor-crime-atlas-2022-00-frequency-numbers-forecast-areas.parquet)

### Berlin Lor Crime Atlas 2023 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2023-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2023-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2023-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2023-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-csv/berlin-lor-crime-atlas-2023-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2023 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet
* updated: 2025-10-27

**Files**

* [berlin-lor-crime-atlas-2023-00-case-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-case-numbers-city.parquet)
* [berlin-lor-crime-atlas-2023-00-case-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-case-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2023-00-case-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-case-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2023-00-case-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-case-numbers-forecast-areas.parquet)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-frequency-numbers-city.parquet)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-frequency-numbers-district-regions.parquet)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-frequency-numbers-districts.parquet)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00-parquet/berlin-lor-crime-atlas-2023-00-frequency-numbers-forecast-areas.parquet)

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).