<!-- TITLE: Resources -->
<!-- SUBTITLE: A quick summary of Resources -->
# Description
A resource can be of three types:
* **COMPUTED** : The resource is read only, updated as frequently as possible, and gathered from other game elements
* **CENTERED** : The resource has a precise range and 0 represents perfect balance in this resource
* **CUMULATIVE** : The resource has no limit or a high limit and is accumulated overtime, then spent. They cannot support modifiers.
# Definitions

| Characteristic | Technical | Type | Range |
| --------               | --------              | -------- |-------- |
| **Population**     | `population` | COMPUTED | 0 <> INF |  
| **Goods**     | `gold` | CUMULATIVE | 0 <> INF |  
| **Army**      | `army` | CUMULATIVE | 0 <> INF | 
| **Wealth**      | `wealth` | COMPUTED | 0 <> INF |  
| **Morale**      | `morale` | CENTERED |  -10 <> 10 | 
| **Structure**      | `structure` | CENTERED | -10 <> 10 |  
| **Militarization**     | `militarization`  | CUMULATIVE | 0 <> 100 |  
| **Reputation**     | `reputation`  | CENTERED |   -10 <> 10 |  A non-modifable that cannot be increased manually.   |  
| **Threat**    | `threat`   |  CENTERED | -10 <> 10 |  
## Population
The total sum of the population of each controlled region
## Goods
Accumulates over time depending on Wealth
## Army
Naturally regenerates over time until equal to Militarization * Population
## Wealth
The total sum of the wealth of each controlled region
## Morale
Increases when the kingdom gains new territories, allies, or is wealthy. Decreases when losing territories, the ruler dies, etc…
Impacts negatively or positively on army efficiency
Morale of -10 means civil war and possibly revolution
## Structure
To every kingdom-related game calculation is applied a structure modifier ranging from -10 to +10 or from x0.5 to x2 depending on structure
## Militarization
Percentage of the population that is a soldier
## Reputation
How widely and far is the kingdom known
Travelers will know the kingdom exists from further if the kingdom has a great reputation
## Threat
Threat is calculated on the %age of map control the kingdom has
High threat will make other kingdoms more likely to attack this kingdom

