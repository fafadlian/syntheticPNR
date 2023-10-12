# syntheticPNR

## Main Note
This is the V0.2 code for the synthetic PNR data generation. 
Not every required data is uploaded here due to large size, will upload in separate link later.

## Notebooks
1. [*Airline Schedule Extractor.ipynb*](https://github.com/fafadlian/syntheticPNR/blob/main/Airline%20Schedule%20Extractor.ipynb) code for extracting and transforming airline schedules. The original airline schedule data is from [OpenSky Network 2020](https://doi.org/10.5281/zenodo.3931948)
2. [*HH_P_Gen.ipynb*](https://github.com/fafadlian/syntheticPNR/blob/main/HH_P_Gen.ipynb) code for creating synthetic population and household for each region. currently only involves countries in Europe
3. [*Routing_V0.2.ipynb*](https://github.com/fafadlian/syntheticPNR/blob/main/Routing_V0.2.ipynb) consist of several code with different functions:
   -A. listing all possible combination of Origin-Departure airports
   -B. routing algorithm for Origin-Departure Pairs based on [Dijkstra's Algorithm](https://doi.org/10.1007/BF01386390)
   -C. persona selection for synthetic population
   -D. Agent-based grouping, staging, itinerary planning, flight searching, and booking code
4. [*POI_Gen.ipynb*](https://github.com/fafadlian/syntheticPNR/blob/main/POI_Gen.ipynb) code for creating synthetic population of Subject/Person Of Interest (SOI/POI) and agent-based grouping, staging, itinerary planning, flight searching, and booking for the POI/SOI
5. [*Build_XML_V2.0.ipynb*](https://github.com/fafadlian/syntheticPNR/blob/main/Build_XML_V2.0.ipynb) code for combining flight schedule, bookings, synthetic population to XML PNR files. The format is based on [PNRGOV IATA format](https://www.iata.org/contentassets/18a5fdb2dc144d619a8c10dc1472ae80/pnrgov20xml20implementation20guide2016_1.pdf)
