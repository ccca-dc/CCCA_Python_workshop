# Python Workshop 
## CCCA Data Center - From Metadata to NetCDF

## Installation

### Linux

**1. Download git Repository**
- git clone https://github.com/ccca-dc/CCCA_Python_workshop.git
- Alternatively: [ZIP](https://github.com/ccca-dc/CCCA_Python_workshop/archive/master.zip) and unzip it

**2. Download and install miniconda**
- [Download miniconda3 for Linux](https://conda.io/miniconda.html)
- Install minconda with:
    * bash Miniconda3-latest-Linux-x86_64.sh
      - Accept license
      - Choose path (default is in home directory)
      - YES to add conda in PATH environment variable (last point installer)
  * source ~/.bashrc
  * Change directory to downloaded CCCA\_Python\_workshop
  * conda env create -f environment.yml
  * ```console
    demo@ccca1 ~/CCCA_Python_workshop (git)-[master] % jupyter notebook
    ```

## Description
Due to the increasing popularity of Python in natural sciences, this workshop
will provide an overview of useful modules to deal with data sets and metadata
within the the CCCA Data Centre environment.

How to use the API (application programming interface) at the CCCA Data Centre,
short introduction how to analyze and visualize data. How to deal with
multidimensional data sets in NetCDF format, averaged in time and space, and
results exported to other formats like CSV.

## Workshop
**1. Python Basics**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/01_python-basics.ipynb)
- Topics: Dictionaries, Lists, String operations

**2. CCCA Data Center API (Application programming interface)**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/02_ckan-api.ipynb)
- Topics: Automated listing and searching of datasets including resources

**3. Python Module iris/pandas 1**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/03_iris_pandas.ipynb)
- Topics: Two-dimensional datasets, Time Series Analysis (mean, std, median, ...), DataFrame, DataSeries, Plot, Export in CSV file
Multidimensional datasets, Plot, Area Average, seasonal mean, write into CF conformal NetCDF file, convert iris cube to pandas DataFrame

**4. Python Module iris/pandas 2**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/04_climate_change_signal.ipynb)
- Topics: Work with climate change signals
Multidimensional datasets, Plot, Area Average, convert iris cube to pandas DataFrame


## Das Datenzentrum in Python – Von Metadaten bis NetCDF

## Beschreibung
Aufgrund der steigenden Beliebtheit von Python im naturwissenschaftlichen
Bereich soll dieser Workshop einen Überblick über sinnvolle Module im Umgang mit
Metadaten und Datensätzen des CCCA Data Centres vermitteln.

Über das application programming interface (API) können Metadaten im Datenportal
automatisiert erstellt, aktualisiert und gefiltert abgefragt werden. Die
Datensätze der zuvor bearbeiteten Metadaten werden beispielhaft kurz analysiert
und visualisiert. Am Ende sollen mehrdimensionale Datensätze im NetCDF Format
visualisiert, zeitlich sowie räumlich gemittelt und Ergebnisse in CSV und NetCDF
exportiert werden.

## Workshop
**1. Python Grundlagen**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/01_python-basics.ipynb)
- Inhalt: Dictionaries, Lists, String operations

**2. Datenzentrums API (Application programming interface)**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/02_ckan-api.ipynb)
- Inhalt: Automatisiertes anzeigen und suchen von Datensätzen inklusive Ressourcen

**3. Python Module iris/pandas 1**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/03_iris_pandas.ipynb)
- Inhalt: Zweidimensionale Datensätze, Zeitserienanalyse (Mittelwert, Standardabweichung, Median, ...), DataFrame, DataSeries, Plot, Export in CSV Datei
Mehrdimensionale Datensätze, Plot, Flächenmittel, saisonal Mittel, schreiben in CF konforme NetCDF Datei, Konvertieren von Zeitserien zu pandas DataFrame

**4. Python Module iris/pandas 2**
- [Python Notebook](https://nbviewer.jupyter.org/github/ccca-dc/CCCA_Python_workshop/blob/master/04_climate_change_signal.ipynb)
- Inhalt: Visualisierung und Flächenmittelung von climate change signal Daten
Mehrdimensionale Datensätze, Plot, Flächenmittel, Konvertieren von Zeitserien zu pandas DataFrame
