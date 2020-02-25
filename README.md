![alt text](https://avatars0.githubusercontent.com/u/60004912?s=200&v=4 "MarE-Fuel logo")

# Fuel demand for the Esbjerg case

*MarE-Fuel: WP1.T2*

- Date: 2020-02-28
- Author: [tilseb](mailto:tilseb@dtu.dk)


## Idea
Deriving annual maritime fuel demand profiles for relevant ports located around the North Sea area. These fuel demand profiles could be deployed in an energy system model in order to analyse at which costs they can be supplied, i.e. from production close to Esbjerg. Esbjerg seems to be a favourable location for several reason:

1. In the center of the North-Sea region, very large ports close by
2. Low population density
3. Exceptional good wind conditions
4. Shallow water for near shore wind farms
5. Good infrastructure in place, i.e. port, power and gas grid connection

=> Five important aspects that potentially lead to low production and transport costs.

## Research questions
The analysis aims at answering the following research questions:
- Under which conditions could Esbjerg become an alternative (maritime) fuel hub?
- What electricity prices do we expect?
- What would be the produced volumes?

## Method
We use a bottom up data analysis to derive the maritime fuel demand profiles to be served by an Esbjerg production in order to derive the additional electricity demand for producing alternative fuels. This leads subsequently to variable primary energy profiles to be implemented in the regional energy system modelling Balmorel, which includes electricity and heat sectors.


## Data
Primary sources in order to derive the energy consumption:
- Cargo based on [Eurostat](https://ec.europa.eu/eurostat/data/database)
- Distance based on [MarineTraffic](https://www.marinetraffic.com/en/ais/home/centerx:-12.0/centery:25.0/zoom:4)
- Energy demand per ship type: [Kristensen2015](https://www.danishshipping.dk/en/policy/klimapolitik/beregningsvaerktoejer/download/Basic_Model_Linkarea_Link/806/energy-demand-and-emissions-of-marine-engines-september-2015.pdf)

Countries considered:
- Belgium
- Germany
- Denmark
- Netherlands
- Norway
- United Kingdom

## Assumptions
We believe that large amounts on long routes will be the focus area for implementing alternative fuel infrastructure not only in Europe, but also by the trade partner entities.

- Considering only the two largest ports per country
- Considering only long range (> 1000 km)
- Considering only routes with large trade volumes (> 5 Mt/route/year on average)


## Implementation
The data processing is implemented in an jupyter notebook (esbjerg.ipynb), using the *Panadas* module. The script is released under an open license on [github](https://github.com/mare-fuel/esbjerg_demand).

## Results

According to this study, a preliminary __362__ __PJ__ of maritime fuel could potentially be served by an Esbjerg production, based on data for 2017 and at a respective transport work of approx. __5__ __Gtkm__. [Statistics Denmark](https://www.statbank.dk/ENE3H) reported for 2017 __452__ __PJ__ fuel oil bunkered by Danish operated ships abroad. Thus, on a net bases Denmark would be able to fuel a major share of its fleets energy demand by domestic renewable production.

## Conclusion
During the second project meeting with the project partners and the advisory board it was consensus that the fuel demand side will not be a limiting factor for the economic production of electrofuels in Esbjerg. Thus, the MarE-Fuel project will not continue deriving high resolution fuel demand profiles for relevant ports around the North Sea area.
