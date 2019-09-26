<!-- TITLE: Resources -->
<!-- SUBTITLE: A quick summary of Resources -->

# Description
Region resources work identically as Realm [Resources](/kingdoms-game/realms/resources).
# Definitions
| Characteristic | Technical | Type | Range |
| --------               | --------              | -------- |-------- |
| **Population**     | `population` | CUMULATIVE | 0 <> INF |  
| **Wealth**     | `wealth` | CENTERED | -10 <> 10 |  
| **Development**      | `civilization` | CUMULATIVE | 0 <> 100 | 
| **Defense**      | `defense` | COMPUTED | 0 <> INF | 

## Population
The total number of inhabitants in the region
## Wealth
The natural wealth of the region. A high wealth combined with a good development will make the controlling realm wealthier.
## Development
Technological development of the region's infrastructures. It's the percentage of wealth that can be exploited from this region.
## Defense
The defense is computed from a few attributes:

| Value | Description | 
| -------- | -------- | 
| Topographical defense value   | The natural practibility of the terrain |
| Additional values ||
| Travelers on the region  | Travelers will increase the defense of the region by their Martial characteristic if they're loyal to the controlling kingdom. The controlling kingdom is not affected by that defense increment. |
| Stationed army  | The defense is increased by the population * kingdom's militarization |