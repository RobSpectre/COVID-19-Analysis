***************
COVID-19 Analysis
***************

Collection of data sources and notebooks analyzing data from the COVID-19 pandemic.


**Table of Contents**


.. contents::
    :local:
    :depth: 1
    :backlinks: none


Installation
==========

1) Clone the repository.

.. code-block:: bash

    git clone https://github.com/RobSpectre/COVID-19-Analysis.git


2) Copy the (optional) matplotlib style from childsafe.ai.

.. code-block:: bash

    cd COVID-19-Analysis
    cp childsafai.mplstyle ~/.config/matplotlib/stylelib/

3) Add Google Maps API key to `local_settings.py` assigned to `GOOGLE_API_KEY`.

4) Launch Jupyter Notebook.

.. code-block:: bash

    jupyter notebook



Contents
============


Notebooks
----------

* `COVID-19 NYC ER Visits`_: Analysis of ER visits for COVID-19 like
  symptoms.
* `COVID-19 NYC Hospital Beds`_: Analysis and occupancy projection for NYC
  hospital beds.
* `COVID-19 New York State Hospitalizations`_: Analysis of New York State
  hospitalizations, ICU admissions, discharges, and intubations.
* `COVID-19 US Cases`_: Analysis of the `New York Times COVID-19 Data`_ repo
  from `The New York Times`_.
* `COVID-19 US Testing`_: Analysis of testing data from 
  `The Covid Tracking Project`_, a project by `Alexis Madrigal`_ from 
  `The Atlantic`_.


Data
----------

* `epiquery_nyc_ili_diseases.xlsx`_: Daily count of visits to New York City
  emergency rooms presenting influenza-like symptoms since 1 Jan 2016. Taken
  from NYC Department of Health's `EpiQuery`_.
* `epiquery_nyc_respiratory_diseases.xlsx`_: Daily count of visits to New York City
  emergency rooms presenting respiratory symptoms since 1 Jan 2016. Taken
  from NYC Department of Health's `EpiQuery`_.
* `new_york_state_hospitaliztion_and_discharge.xlsx`_: New York State
  hospitalizations, ICU admissions, discharges, and intubations for COVID-19
  patients. Manually collected from Governor Cuomo's daily press briefings.
* `nyc_hospital_beds.csv`_: List of New York City Hospitals with total
  hospital beds and ICU beds. Scraped from `New York State Department of Health`_. 
* `nyc_hospital_region_mapping.csv`_: Mapping of counties in
  `nyc_hospital_beds.csv`_ to New York boroughs.


Meta
============

* Written by `Rob Spectre`_
* Released under `MIT License`_
* Software is as is - no warranty expressed or implied.


.. _COVID-19 NYC ER Visits: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/COVID%2019%20NYC%20ER%20Visits.ipynb
.. _COVID-19 NYC Hospital Beds: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/COVID-19%20NYC%20Hospital%20Beds.ipynb
.. _COVID-19 New York State Hospitalizations: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/COVID-19%20New%20York%20State%20Hospitalizations.ipynb
.. _COVID-19 US Cases: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/COVID-19%20US%20Cases.ipynb
.. _COVID-19 US Testing: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/COVID-19%20US%20Testing.ipynb
.. _EpiQuery: https://a816-health.nyc.gov/hdi/epiquery/visualizations?PageType=ts&PopulationSource=Syndromic&Topic=1&Subtopic=39
.. _New York State Department of Health: https://profiles.health.ny.gov/hospital/bed_type/Total+Beds
.. _The Covid Tracking Project: https://covidtracking.com/
.. _New York Times COVID-19 Data: https://github.com/nytimes/covid-19-data
.. _The New York Times: https://nytimes.com
.. _The Atlantic: https://www.theatlantic.com/
.. _Alexis Madrigal: https://twitter.com/alexismadrigal
.. _epiquery_nyc_ili_diseases.xlsx: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/data/epiquery_nyc_ili_diseases.xlsx
.. _epiquery_nyc_respiratory_diseases.xlsx: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/data/epiquery_nyc_respiratory_diseases.xlsx
.. _new_york_state_hospitaliztion_and_discharge.xlsx: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/data/new_york_state_hospitaliztion_and_discharge.xlsx
.. _nyc_hospital_beds.csv: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/data/nyc_hospital_beds.csv
.. _nyc_hospital_region_mapping.csv: https://github.com/RobSpectre/COVID-19-Analysis/blob/master/data/nyc_hospital_region_mapping.csv
.. _Rob Spectre: http://www.brooklynhacker.com
.. _MIT License: http://opensource.org/licenses/MIT

