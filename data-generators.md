Data Generators
=====================

Overview/Motivation
---------------------
An important portion of a data pipeline is to understand how data enters, is transformed and exits certain portions of the pipeline. 
To understand this correctly it is important to generate data with purpose of being descriptive in mind. Thus, the data generators have
been created to fulfill the following purposes:

1. To fill in the proposed data structures with *randomized* data.
2. To demonstrate the flow and transformation of data through the stages of the pipeline
3. To generate data that is reasonable but not necessarily completely realistic.

Exposure Data Generator
--------------------------
### Description

The Exposure Data Generator creates latitude and longitude based exposure files for the primary insurer. These files are generated from
a variety of user defined inputs, as well as world population distributions. The generator was created to simulate overall geographic
population distribution of a country, in such that it is generally highly correlated with property-based exposure. This generator
approximates the geographic placement of a country's exposure, however, it does not approximate the value of exposure at a specific
geographic location.

### Methodology
The generator utilized two methods to generate data. The geographic placement of locations is done using a simple [Monte Carlo sampling] (http://en.wikipedia.org/wiki/Monte_Carlo_method)
method. The geographic distribution for this comes countrywise city populations. Thus, cities with larger portions of the population, on a country basis, are more likely
to be sampled utilitizing this method. For the construction of exposed values and financial terms a quesdo-random number generator is used to generate uniform values between
user-defined maxima and minima.

### Inputs

### Data Flow

### Output


Event Catalogue Generator
--------------------------
### Description

### Methodology

### Inputs

### Data Flow

### Output