# version 1

## Government free unit support

No ZOC dictates a different tactics where player cannot operate with limited combat unit groups on a battlefield. Without ZOC everybody need to flood the land with units in attempt to keep enemy units from sneaking into front line gaps. That also requires protecting back cities against flank attacks. All that requires much more units to cities ratio than in Civ 2. With that in mind current free unit supports for different governments are just ridiculously low and will definitely be overflowed during war time. Keep in mind that free unit support includes all units including 2-3 police units and 1-2 worders per city. So even in the peace time cities should maintain like 3-5 units just for police and economical development purposes. That alone may easily overflow free unit tier sucking money from economy. Not to mention supporting regular invasion army. That becomes even more pronounced in modern eras with mixed unit types required (bombardment, air, anti-air, etc.). Therefore, this mod proportionally increases free units support for all governments to make war oriented governments more viable and competing.

On top of that Feudalism free support is flattened per town/city/metro and further increased. Feudalism unit cost is decreased. It is supposed to be an ultimate war government before Fascism era and with vanilla settings it is some weak breed of Monarchy and Republic.

| government | town | city | metro | cost | comment |
| ---- | ----: | ----: | ----: | ----: | ---- |
| Despotism | 6 | 6 | 6 | 1 ||
| Monarchy | 4 | 6 | 8 | 1 | Monarchy usually used early in the game only when player still has a lot of towns but barely few cities and definitely no metros. I have increased town allowance a bit and reduced metro a bit too as it probably won't be used ever in game anyway. |
| Communism | 9 | 9 | 9 | 1 ||
| Republic | 2 | 3 | 4 | 2 | Straighten it up slightly. Should be somehow between Monarchy and Democracy. |
| Democracy | 0 | 0 | 0 | 1 ||
| Fascism | 5 | 10 | 15 | 1 ||
| Feudalism | 10 | 10 | 10 | 2 | Feudalism generally sucks comparing to Monarchy and Republic. Since unit support is the only thing it is good for let it be exceptionally good at it. I also make its support indepedent on city sizes. Degressing support is stupid. |

## Fortress and barricade

Without ZOC it is useless to build fortifications in key strategic location as invaders will just go around them. Therefore, vanilla fortresses are just never used even by human player. Fortress construction time should be *very* short so workers may erect them in large quantities even during hot war on some tactical directions.

Fortress base construction time is now 4 which allows to built it in two turns on flat terrain. Barricade base construction time is twice longer.

Fortress is also available from start.

Fortress and barricade defence bonus is decreased to 25% (50% combined) so they do not confer more protection than city walls. Otherwise, player would be tempted to just surround cities with barricades which is ridiculous.

## Barracks cost/maintenance

Barracks effectively add 1/3 on top of unit strength which is about same in unit count. So they pay off for themselves as soon as city invests [barracks cost * 3] in units. With 20 shields vanilla barracks cost it equals to three spearmen/archers or two horsemen/swordsmen. That is like nothing in the world of Civ 3 combat where units floods the battlefield. Obviously, building such cheap barracks before producing any units is no brainer. This mod increases barracks cost and maintenance to slightly correct the situation. Yet it is still must have improvement before full scale war.

Barracks cost/maintenance: 6/2

## Terrain defense bonuses

All ridiculous 10% bonuses on flat terrains and water (?) are removed. All mountains including volcano are 100%. Simple and easy to remember.

## Terrain yield

The game is strangely restrictive on food. Only terrain supporting further growth are grassland and flood plains and there are not many of them on a map. Everything else is progressively less interesting. There is no much land in game already and about 2/3 of it is filled by 0/1 food terrain. I don't think this is fixable for land tiles as a single unit food addition is going to break a game. However, I believe we can safely add extra food to coast tiles. That will at least sustain cities on tundras a little more.

Same story with shields. I feel like desert and mountains are most unattractive land types which player tries to avoid like a plague. If not food, we should give them more shields to encourage settlements there. This will add some production value to desert and mountains and make them not inferior to hills.

#### Terrain yield changes

| terrain | food | shields | commerce | irrigation | mine |
| ---- | ----: | ----: | ----: | ----: | ----: |
| Desert | 0 | 2 | 0 | +1 | +1 |
| Mountains | 0 | 1 | 0 | - | +3 |
| Coast | 2 | 0 | 2 | - | - |

## Clean wetland worker job

Wetlands are absolutely not usable and normally cleaned up to uncover grassland. I don't even understand why they are in a game if they are cleanable? Some sort of mini game that leads absolutely nowhere but just waste worker time. As such I don't absolutely see a point for them to be cleaned for such ridiculously long time. Therefore, I have significantly reduced wetland cleanup time.

## Railroad worker job

Railroad is insanely overpowered worker job that costs no shields but skyrocket food and shield yield by ridiculous numbers. Not much I can do about it because it is not configurable in editor. I just quadroupled its construction time. Hope this compensates its value.

## Strategic resources

There are two standing out strategic resources: iron and coal. They are used not only to produce slightly better units but railroad, factories and power plants as well. While inability to produce better unit could be a hindrance, the inability to build railroad/factories/plants is just a disaster that deprives player from doubling their food income and tripling/quadroupling their production. It's just not fair. To make it more evenly distributed I have increased appearance ratio for both iron and coal to 200.

Appearance ratio for late resources is increased to 160. It is not really clear to me why only few lucky could build tanks, infantry and ICBM.

All resources now have diappearance probability to allow their rotation across the globe. Disappearance probability for all resources is about doubled to increase their rotation frequency across the globe. This way each player has more chance to acquire/lose resource during the play. More fair this way and less dependency on dumb luck.

| resource | appearance ratio | disappearance probability |
| ---- | ----: | ----: |
| Horses | 160 | **200** |
| Iron | **200** | **200** |
| Saltpeter | 160 | **200** |
| Coal | **200** | **200** |
| Oil | **160** | **100** |
| Rubber | **160** | **100** |
| Aluminum | **160** | **100** |
| Uranium | **160** | **50** |

## Units

I am trying to modify standard units parameters. I will try to similarly adjust UU alternatives for these regulars if I can find them. Let me know if I missed any UU.

Generally, I am trying to follow overall game patterns and correct the outliers. Early to mid game unit costs should be proportional to each other. However, late game unit cost may go slightly up due to overall increase in production output with factories.

### Fast attackers

All fast attackers are following the same pattern: defense is half of the attack and cost is 15 times the attack value. Below is the fast units table with corrections in bold.

| unit | cost | attack | defense | movement |
| ---- | ----: | ----: | ----: | ----: |
| Chariot | 20 | 1 | 1 | 2 |
| Horseman | 30 | 2 | 1 | 2 |
| Knight | **60** | 4 | **2** | 2 |
| Cavalry | **90** | 6 | 3 | 3 |
| Tank | **240** | 16 | 8 | 2 |
| Modern Armor | **360** | 24 | 16 | 3 |

Modern Armor defense is slightly off pattern but I don't care fixing it for the very late unit. It won't change already won or lost games.

### Defenders

Defenders attack should be lower than their attack. However, there is no single pattern on that. Their attack/defense value ratio may be no more than 1/2 (Spearman, Pikeman, Musketman), about 2/3 (Rifleman, Infantry, Mech Infantry), or almost up to 1 (Guerilla, TOW Infantry). The cost pattern is not entirely clear either. I take it is defined by their defense value for pure defenders when their attack is no more than half of their defense. Whatever extra attack they have on top of half of their defense should factor into the cost as well. With that in mind below are defensive unit costs. Changed values are in bold.

| unit | cost | attack | defense | movement |
| ---- | ----: | ----: | ----: | ----: |
| Spearman | 20 | 1 | 2 | 1 |
| Pikeman | 30 | 1 | 3 | 1 |
| Musketman | **40** | 2 | 4 | 1 |
| Rifleman | **70** | 4 | 6 | 1 |
| Guerilla | 90 | 6 | 6 | 1 |
| Infantry | **110** | 6 | 10 | 1 |
| TOW Infantry | **190** | 12 | 14 | 1 |
| Mech Infantry | **210** | 12 | 18 | 2 |
| Paratrooper | 90 | 4 | 9 | 1 |
| Modern Paratrooper | 110 | 6 | 11 | 1 |

### Foot attackers

Foot attackers follows about the same pattern as fast attackers. There are just two of them: swordmen and medieval infantry. They are generally fine except swordmen has too much defense no other attacker has in ancient era. That is too much for their price. They don't even need a spearmen to defend. I lowered their defence to 1 so other contemporary attackers can effectivelly counterattack them at least. Otherwise, they are too OP and effectivelly doom anyone unluckly to not possessing iron.

| unit | cost | attack | defense | movement |
| ---- | ----: | ----: | ----: | ----: |
| Archer | 20 | 2 | 1 | 1 |
| Swordman | 30 | 3 | **1** | 1 |
| Medieval infantry | 40 | 4 | 2 | 1 |
| Longbowman | 40 | 4 | 1 | 1 |

## Research tree

First of all, I have reduced minimal research time to 1 turn. I seriously don't see point in artificial technology development impediment.

Path to Monarchy is eased up a little. This is the first government after despotism and should be accessible much earlier before Republic and Feudalism to disable exceptionally restrictive Despotism yield penalties.

Cities in Civ 3 grow exceptionally fast. They easily fall into stagnation due to aqueduct or hospital inaccessibility which is pretty boring impediment. I don't think players should be artificially restricted like that. Aqueduct is moved to Mathematic. Sanitation is moved as a followup for Engineering. I often saw cities easily grow to 12 in the early middle age and then just sitting at this number for the whole era. Ugh.

