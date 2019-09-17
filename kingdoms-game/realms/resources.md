<!-- TITLE: Resources -->
<!-- SUBTITLE: A quick summary of Resources -->
# Description
A resource can be of three types:
* **COMPUTED** : The resource is read only, updated as frequently as possible, and gathered from other game elements
* **CENTERED** : The resource has a precise range and 0 represents perfect balance in this resource
* **CUMULATIVE** : The resource has no limit or a high limit and is accumulated overtime, then spent
# Definitions

| Characteristic | Technical | Type | Range | Info
| --------               | --------              | -------- |-------- |-------- |
| **Population**     | `population` | COMPUTED | 0 <> INF | Has a positive effect on the outcome of battles   | 
| **Goods**     | `gold` | CUMULATIVE | 0 <> INF |  Useful in duels or to resist an assassination  | 
| **Army**      | `army` | CUMULATIVE | 0 <> INF | Helps relation with surrounding realms  | 
| **Wealth**      | `wealth` | CENTERED |-10 <> 10 |  Helps economy and cultural management    | 
| **Morale**      | `morale` | CENTERED |  -10 <> 10 | Useful to befriend travelers and keep popularity  | 
| **Structure**      | `structure` | CENTERED | -10 <> 10 |   A random chance that things go better than they should. Make very arrogant.  | 
| **Militarization**     | `militarization`  | CUMULATIVE | 0 <> 100 |   A costy characteristic that counteracts Arrogance.   | 
| **Reputation**     | `reputation`  | CENTERED |   -10 <> 10 |  A non-modifable that cannot be increased manually.   |  
| **Threat**    | `threat`   |  CENTERED | -10 <> 10 |   A non-modifable characteristic that gives bonuses to social interactions.   | 
