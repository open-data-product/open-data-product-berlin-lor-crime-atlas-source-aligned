
# Data Product Canvas - Berlin LOR Crime Atlas (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data product providing Berlin LOR crime data
* updated: 2025-07-06

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
* [Data CSV aggregator](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_aggregator.py) aggregates data to be used as output ports

## Output Ports

### Berlin Lor Crime Atlas 2012 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2012-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2012-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2013 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2013-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2013-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2014 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2014-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2014-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2015 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2015-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2015-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2016 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2016-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2016-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2017 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2017-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2017-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2018 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2018-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2018-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2019 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2019-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2019-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2020 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2020-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2020-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2021 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2021-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2021-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2022 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2022-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2022-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2023 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/02-silver/berlin-lor-crime-atlas-2023-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2023-00-case-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-case-numbers.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/02-silver/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-frequency-numbers.csv)

### Berlin Lor Crime Atlas 2012 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2012-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2012-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2012-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2012-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2012-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2012-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2012-00/berlin-lor-crime-atlas-2012-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2013 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2013-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2013-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2013-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2013-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2013-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2013-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2013-00/berlin-lor-crime-atlas-2013-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2014 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2014-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2014-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2014-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2014-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2014-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2014-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2014-00/berlin-lor-crime-atlas-2014-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2015 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2015-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2015-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2015-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2015-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2015-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2015-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2015-00/berlin-lor-crime-atlas-2015-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2016 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2016-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2016-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2016-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2016-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2016-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2016-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2016-00/berlin-lor-crime-atlas-2016-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2017 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2017-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2017-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2017-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2017-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2017-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2017-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2017-00/berlin-lor-crime-atlas-2017-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2018 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2018-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2018-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2018-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2018-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2018-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2018-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2018-00/berlin-lor-crime-atlas-2018-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2019 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2019-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2019-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2019-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2019-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2019-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2019-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2019-00/berlin-lor-crime-atlas-2019-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2020 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2020-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2020-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2020-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2020-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2020-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2020-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2020-00/berlin-lor-crime-atlas-2020-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2021 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2021-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2021-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2021-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2021-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2021-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2021-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2021-00/berlin-lor-crime-atlas-2021-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2022 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2022-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2022-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2022-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2022-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2022-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2022-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2022-00/berlin-lor-crime-atlas-2022-00-frequency-numbers-forecast-areas.csv)

### Berlin Lor Crime Atlas 2023 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-crime-atlas-2023-00
* updated: 2025-07-06

**Files**

* [berlin-lor-crime-atlas-2023-00-case-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-case-numbers-city.csv)
* [berlin-lor-crime-atlas-2023-00-case-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-case-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2023-00-case-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-case-numbers-districts.csv)
* [berlin-lor-crime-atlas-2023-00-case-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-case-numbers-forecast-areas.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-frequency-numbers-city.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-frequency-numbers-district-regions.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-frequency-numbers-districts.csv)
* [berlin-lor-crime-atlas-2023-00-frequency-numbers-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-crime-atlas-source-aligned/main/data/03-gold/berlin-lor-crime-atlas-2023-00/berlin-lor-crime-atlas-2023-00-frequency-numbers-forecast-areas.csv)

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).