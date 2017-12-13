
Items table

  ProjectID                 DOI                                                                                  ItemType
  ------------------------- ------------------------------------------------------------------------------------ --------------------------
  ARC Grant ID or similar   Digital object identifier                                                            Dataset, Article, Report
  LP0990134                 [*10.1016/j.atmosenv.2011.05.004*](https://doi.org/10.1016/j.atmosenv.2011.05.004)   Article

Participants table

  PersonID                 ProjectID
  ------------------------ -------------------------
  Internal on ACEMS page   ARC Grant ID or similar
  sam-clifford             LP0990134

Authorship table

  PersonID       DOI
  -------------- ------------------------------------------------------------------------------------
  sam-clifford   [*10.1016/j.atmosenv.2011.05.004*](https://doi.org/10.1016/j.atmosenv.2011.05.004)

Projects table

  ProjectID                 Funding amount   Start date   End date
  ------------------------- ---------------- ------------ ------------
  ARC Grant ID or similar   \$                            
  LP0990134                 774000           2010-10-25   2014-12-31

People table (maybe already in reportal)

  PersonID       ORCID                 Other attributes
  -------------- --------------------- ------------------
  sam-clifford   0000-0002-3774-3882   

We then discussed the data sources that we have access to.

In terms of open data, we discussed:

- [Australian Flights Data](https://github.com/ropenscilabs/ozflights)
- [Australian Road Deaths](https://github.com/ropenscilabs/ozroaddeaths)
- UK police data: [UKpolice R package](http://ukpolice.njtierney.com/), [UK police data website](https://data.police.uk/)
- [Pedestrian count data in Melbourne](https://cran.r-project.org/web/packages/rwalkr)
- [E atlas data](http://eatlas.org.au/eatlas-georss-items/40)

We then discussed the different datasets that we each work with

- Earl Duncan:
    - Cancer Registry data (private data, cannot share - simulated data is available for use)
        -   Each row is aggregated at the SA2 level, for the number of people with cancer, and diagnosis of cancer, and other demographic
        - ABS data: Population estimates for each area + shapefiles
            
- Jia
    - [Canadian temperature data](http://climate.weather.gc.ca/)
    - Berkeley Growth data: heights of boys + girls in California (available online)
    - Google flu trends data (available online)
    - Fruit fly data (available online)
        - birth rate of fruit flies + different experimental conditions (diff flies fed different things)
    - Gene data for different expressions (Available online)
        - Different conditions for different people
    - Traffic data (possibly cannot share)
        -   Speed, flow, density, and flow of cars in Melbourne
        
- Terun
    - Dengue Fever data (private data)
        - Number of dengue fever cells in a particular cell culture
        - Trying to estimate the number viruses in a particular cell culture
    - Patient level data, and their immunoglobolin response to a virus
        - Collected from patients who are affected by Dengue

- Arthur
    - [Growth measurement of children](https://hbgdki.github.io/hbgd/#intro)(need permission to use it, but it is possible to access)
        - SES info, height, weight
        - Interested in the incident of Diahorrea
        - [Global Health Analytic platform (GHAP)](https://rdrr.io/github/HBGDki/ghap/)
        - [R packages which have data](https://stefvanbuuren.github.io/brokenstick/mainfunctions.html)

-   Sam Clifford
    - Coral Reef data (coral data, from 1990s - Now)
        - [Virtual Reef](https://www.virtualreef.org.au/)
        - http://virtualreef.org.au/api/vw\_ElicitationsCompleted
    - Citizen science coral reef data (possibly available for sharing)
        - Pointed camcorder at the sea floor and recorded
        - Derived estimates of the amount of the coral and other things
        - Other data available from this project:
            - Each row has a grid location and contains the raw data
            - Professional survey data
            - User provided data
            - Grid of locations
            - Available via a JSON feed.
            - 24,040 instances of an individual point in an image
    - Air quality data (could possible be served up online)
        - QLD State GVT provides data
        - Possibly discuss other datasets of use
            - [Airquality measurement](https://github.com/ropensci/rtimicropem)
            - https://github.com/maelle/usaqmindia
            - https://github.com/ropensci/ropenaq
            
- Andrés
    - Anomaly detection
    - Powerline data
        - [Report available as PDF](https://www.energy.vic.gov.au/__data/assets/pdf_file/0022/41719/R_D_Report_-__Marxsen_Consulting_-_Vegetation_conduction_ignition_tests_final_report_15_July_2015_DOC_15_183075_-_external_.PDF)
        - [Data available as separate files, but the main data package is the Gen3i files](https://www.data.vic.gov.au/data/dataset/powerline-bushfire-safety-program-vegetation-conduction-ignition-test-report)
            - When fires might start from the powerlines
            - Data taken from department of conservation, can download from online, but [Uses a proprietary file format](https://www.hbm.com/en/4648/perception-pnrf/)
        - Performances of groups
            - League of Legends data - Game level data
                - Every minute, what every player has done (Moved to position, killed other player)
                - Summary of a game
                - Tools for including include:
                    - [Public API for accessing the data](https://developer.riotgames.com/api-methods/)
                    - [R Riot LoL](https://gist.github.com/RyanHope/96665b0da636515917cc),
                    - [Game On Python](https://github.com/szhan/game-on)
                    - [RioNet](https://github.com/aj-r/RiotNet).
        -   Testing algorithms (classification, optimisation)
            - Collect features of each dataset E.g., the number of classes in iris dataset
            - Collected data from [University of California Irvine](https://archive.ics.uci.edu/ml/index.php)
            - machine learning data and [OpenML](https://www.openml.org/).
                -   Which contains many datasets, mostly used for benchmarking
                -   Collates the features from the datasets. These are saved into a dataset, (number offeatures, what models was used)

- Tom
    - Olliveti faces dataset (available online)
            -   400 images
            -   10 reps for each individual
            -   Grayscale
            -   Used to develop image recognition
            -   Could be interesting to access the different images data
-   Rhys
    -   Bitcoin Data
