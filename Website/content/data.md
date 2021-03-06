# Key terms

  * Ecological Footprint: "A measure of how much area of biologically productive land and water an individual, population, or activity requires to produce all the resources it consumes and to absorb the waste it generates, using prevailing technology and resource management practices. The Ecological Footprint is usually measured in global hectares (gha). Because trade is global, an individual or country's Footprint includes land or sea from all over the world." [source](https://data.world/footprint)
  
  * Biocapacity: "The biocapacity of a surface represents its ability to renew what people demand. Biocapacity is therefore the ecosystems' capacity to produce biological materials used by people and to absorb waste material generated by humans, under current management schemes and extraction technologies. Biocapacity can change from year to year due to climate, management, and proportion considered useful inputs to the human economy. Biocapacity is expressed in global hectares." [source](https://data.world/footprint)
  
  * Global Hectares: "Global hectares are the accounting unit for the Ecological Footprint and biocapacity accounts. These productivity weighted biologically productive hectares allow researchers to report both the biocapacity of the earth or a region and the demand on biocapacity (the Ecological Footprint). A global hectare is a biologically productive hectare with world average biological productivity for a given year. Global hectares are useful because different land types have different productivities. A global hectare of cropland, for example, would occupy a smaller physical area than the much less biologically productive pasture land, as more pasture would be needed to provide the same biocapacity as one hectare of cropland. Because world productivity varies slightly from year to year, the value of a global hectare may change slightly from year to year." [source](https://data.world/footprint)
  
  * National Footprint and Biocapacity Accounts: "The central data set that calculates the Footprint and biocapacity of the world [...]. The ongoing development, maintenance, and upgrades of the National Footprint and Biocapacity Accounts are coordinated by the research team at Global Footprint Network and the Ecological Footprint Initiative at York University." [source](https://data.world/footprint)
  
  * Carbon Footprint: "The carbon Footprint measures CO2 emissions associated with fossil fuel use. In Ecological Footprint accounts, these amounts are converted into biologically productive areas necessary for absorbing this CO2. The carbon Footprint is included in the Ecological Footprint because it is a competing use of bioproductive space, since increasing CO2 concentrations in the atmosphere are considered to represent a build-up of ecological debt. Some carbon Footprint assessments express results in tonnes released per year, without translating this amount into area needed to sequester it." [source](https://data.world/footprint)
  
  * Consumption: "Use of goods or of services. The term consumption has two different meanings, depending on context. As commonly used regarding the Footprint, it refers to the use of goods or services. A consumed good or service embodies all the resources, including energy, necessary to provide it to the consumer. In full life-cycle accounting, everything used along the production chain is considered, including any losses along the way. For example, consumed food includes not only the plant or animal matter people eat or waste in the household, but also that lost during processing or harvest, as well as all the energy used to grow, harvest, process and transport the food." [source](https://data.world/footprint)
  
  * Calculation factor: "A generic term for factors which are used to translate a material flow expressed within one measurement system into another one. For example, a combination of two calculation factors??????yield factors??? and ???equivalence factors?????? translates hectares into global hectares. The extraction rate calculation factor translates a secondary product into primary product equivalents. Calculation factors are available for download here." [source](https://data.world/footprint)
  
 * Ecological Deficit / Reserve: "The difference between the biocapacity and Ecological Footprint of a region or country. An ecological deficit occurs when the Footprint of a population exceeds the biocapacity of the area available to that population. Conversely, an ecological reserve exists when the biocapacity of a region exceeds its population's Footprint. If there is a regional or national ecological deficit, it means that the region is importing biocapacity through trade or liquidating regional ecological assets, or emitting wastes into the global commons such as the atmosphere. In contrast to the national scale, the global ecological deficit cannot be compensated for through trade, and is therefore equal to overshoot by definition." [source](https://data.world/footprint)
  
  * Land Type: "The Earth's approximately 12 billion hectares of biologically productive land and water areas are categorized into five types: cropland, grazing land, forest land, fishing ground, and built-up land." [source](https://data.world/footprint)
  
  * Biocapacity Per Person (or Per Capita): "There were ~ 12 billion hectares of biologically productive land and water areas on Earth in 2017. Dividing by the number of people alive in that year (7.5 billion) gives 1.6 global hectares per person. This area also needs to accommodate the wild species that compete for the same biological material and spaces as humans." [source](https://data.world/footprint)
  
  * Biologically Productive Land and Water: "The land and water (both marine and inland waters) area that supports significant photosynthetic activity and the accumulation of biomass used by humans. Non-productive areas as well as marginal areas with patchy vegetation are not included. Biomass that is not of use to humans is also not included. The total biologically productive area on land and water in 2014 was approximately 12 billion hectares." [source](https://data.world/footprint)
  
# Data description 

The data set we use comes from the 2019 edition of the *National Footprint and Biocapacity Accounts* which is supervised by a team at York University???s Faculty of Environmental Studies (FES) who is part of the Ecological Footprint Initiative.

In this section, we go over the variables of the data set to better understand their meaning. The (public) data set has 12 variables and provide information on 72,186 observations on 192 countries:

  * country: Provides the name of the country under focus
  
  * Year: For each country data is provided for 55 years, from 1961 until 2016. Some countries have less observation since founded after 1961 (e.g. Armenia in 1991).
    
  * country_code: Country numerical identifier
  
  * record: For each year and for each country, eight different records are made.
  
      1. **AreaPerCap**: Area divided by population
      2. **AreaTotHA**: Total area in hectare (ha)
      3. **BiocapPerCap**: Biocapacity (in gha) divided by population
      4. **BiocapTotGHA**: Total biocapacity (in gha)
      5. **EFConsPerCap**: Ecological Footprint of consumption (in gha) divided by population
      6. **EFConsTotGHA**: Total Ecological Footprint of consumption (in gha)
      7. **EFProdPerCap**: Ecological Footprint of production (in gha) divided by population
      8. **EFProdTotGHA**: Total Ecological Footprint of production (in gha)
      
  * crop_land: The cropland Footprint provides the amount of land necessary to grow all crops consumed by humans and livestock (includes agricultural products, market animal feed, and cropped grasses used as livestock feed).  

  * grazing_land: The grazing land Footprint assesses demand for grazing land to feed livestock and the demand for grazing land in traded goods. 
  
  * forest_land: The forest products Footprint assesses human demand for the products of the world???s forests, wood used for fuel and timber and pulp used to produce derived wood products.
  
  * fishing_ground: The fishing ground Footprint represents the demands of fisheries on aquatic ecosystems. It is calculated by dividing the amount of primary production consumed by an aquatic specy over its lifetime by an estimate of the harvestable primary production per hectare of marine area.
  
  * built_up_land: The built-up land Footprint represents bioproductive land that has been physically occupied by human activities (e.g. infrastructure areas required for housing, transportation, industrial production). 
  
  * carbon: The carbon Footprint represents the area of forest land required to sequester anthropogenic carbon dioxide emissions (e.g. domestic fossil fuel combustion, electricity use, embodied carbon in traded items and electricity, transport emissions, and non-fossil-fuel sources).
  
  * total: Total Footprint (i.e. sum of carbon, built-up land, fishing ground, forest land, grazing land and crop land Footprint)
  
  * Qscore: Quality of overall country data. The National Footprint and Biocapacity Accounts uses internationally available data from multiple data sets for all countries for each year going back to 1961. 
  