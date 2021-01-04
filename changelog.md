# version 1

## Free unit support

No ZOC dictates a different tactics where player cannot operate with limited combat unit groups on a battlefield. Without ZOC everybody need to flood the land with units in attempt to keep enemy units from sneaking into gaps betwen units. That also requires protecting back cities against flank attacks. This combined requires higher units to cities ratio than in Civ 2. With that in mind current free unit supports for different governments are just ridiculously low and will definitely be overflowed during war time. That becomes even more pronounced in moderr eras with mixed arms and supporting units. Therefore, this mod proportionally increases free units support for all governments to make war oriented governments more viable and competing.

On top of that Feudalism free support is flattened per town/city/metro and further increased. Feudalism unit cost is decreased. It is supposed to be an ultimate war government before Fascism era and with vanilla settings it is some weak breed of Monarchy and Republic.

| government | town | city | metro | cost |
| ---- | ----: | ----: | ----: | ----: |
| Despotism | 6 | 6 | 6 | 1 |
| Monarchy | 3 | 6 | 12 | 1 |
| Communism | 9 | 9 | 9 | 1 |
| Republic | 2 | 4 | 6 | 2 |
| Democracy | 0 | 0 | 0 | 1 |
| Fascism | 5 | 10 | 15 | 1 |
| Feudalism | 10 | 10 | 10 | 2 |

## Walls defense bonus

Walls defense bonus is increased to 100%. Anything lower is just ridiculous and encourages surrounding city with barricades instead. Cities should be most protected asset. I don't know how it will behave now with town-city-metro transition. Should walls diappear in metro but stay in city? Didn't test.

Walls cost is also increased to refled stronger defense bonus and potentially longer usage.

## Fortress and barricades construction time

Without ZOC it is useless to build fortifications in key strategic location as invaders will just go around them. Therefore, vanilla fortresses are just never used even by human player. Fortress constrution time should be *very* short so workers may erect them in large quantities even during hot war on some tactical directions.

Fortress base construction time is now 4 which allows to built it in two turns on flat terrain to quickly gain extra 50% defense bonus. Barricade base construction time is 16 which is four times longer as it confers 100% defense bonus comparable to city walls.

Fortress is also available from start.

## Barracks cost/maintenance

Barracks effectivelly add 1/3 on top of unit strength which is about same in unit count. So they pay off for themselves as soon as city invests [barracks cost * 3] in units. With 20 shields vanilla barracks cost it is three spearmen/archers/horsemen or two swordsmen. That is like nothing in the world of Civ 3 combat where units floods the battlefield. Obviously, building a barracks before producing any units is no brainer. This mod increases barracs cost and maintenance to slightly correct the situation. Yet it is still must have improvement before full scale war.

Barracks cost/maintenance: 6/2

## Temple cost

Temple is a must have in new settlements to expand their available working radius. It is not a luxury. Vanilla cost is too unaffordable for new settlements. It should be reduced at least slightly.

Temple cost: 4

## Terrain defense bonuses

All ridiculous 10% bonuses on flat terrains and water (?) are removed. All rough terrains (forest, jungle, march, hills) now confer 50% bonus. All mountains including volcano are 100%. Simple and easy to remember.

## Terrain yield

The game is strangely restrictive on food. Only terrain supporting further growth are grassland and flood plains and there are not many of them on a map. Everything else is progressively less interesing. There is no much land in game already and about 2/3 of it is filled by 0/1 food terrain. I don't think this is fixable for land tiles as a single unit food addition is going to break a game. However, I believe we can safely add extra food to all water tiles. That will at least sustain cities on tundras a little more.

Same story with shields. I feel like desert and mountains are most unattractive land types which player tries to avoid like a plague. If not food, we should give them more shields to encourage settlements there. This will turn desert and moutain at least not inferior to hills.

| terrain | food | shields | irrigation | mine |
| ---- | ----: | ----: | ----: | ----: |
| Desert | 0 | 2 | +1 | +1 |
| Mountains | 0 | 1 | - | +3 |

## Clean wetland worker job

Wetlands are absolutely not usable and normally cleaned up to uncover grassland. I don't even understand why they are in a game if they are cleanable? Some sort of minigame that leads absolutely nowhere but just waste worker time. As such I don't absolutely see a point for them to be cleaned for such ridiculously long time. Therefore, I have significantly reduced this worker job.

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

Modern Armor defense is slightly off pattern but I don't care fixing it for the very late unit. It won't fix already won or lost games.

### Defenders

Defenders attack is lower than their attack. However, there is no sinlge pattern on that. Their attack/defense value ratio may be no more than 1/2 (Spearman, Pikeman, Musketman), about 2/3 (Rifleman, Infantry, Mech Infantry), or almost up to 1 (Guerilla, TOW Infantry). The cost pattern is not entirely clear either. I take it is defined by their defense value for pure defenders when their attack is no more than half of their defense. Whatever extra attack they have on top of half of their defense should factor into the cost as well. With that in mind below are defensive unit costs. Bolded are changed values.

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

## Research pace

