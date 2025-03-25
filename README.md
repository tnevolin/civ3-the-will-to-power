# Civilization 3 Conquest - The Will to Power - mod

The Will to Power is a playing experience enhancement mod for Civilization 3 Conquest created using standard game scenario editor.

The purpose of the mod is to make playing experience smoother and long lasting.

# Research

* Minimal research time is reduced to 1 turn. No point in artificial technology development impediment.
* Path to Monarchy is eased up a little. This is the first government after despotism and should be accessible much earlier before Republic and Feudalism to lift exceptionally restrictive yield penalties.
* Aqueduct is moved to Mathematic. Sanitation is moved as Engineering successor. Cities grow exceptionally fast. They easily fall into stagnation due to aqueduct or hospital inaccessibility which is pretty boring impediment.
* Map Making enables sea movement. Astronomy enables ocean movement. This is to facilitate island transportation and discovery. Otherwise, it takes too long.

# Units

* Changes in strength/cost and appearance time to make sure all units are usable in their time.
* Unit strength does not jump too fast allowing previous generation units to play their role.
* Cost of more powerful units is increased as strength advantage is a serious bonus in this game.

## Upgrade paths

I tried to streamline upgrade paths wherever possible. Each normal unit upgrades to chain of unique units and the last unique unit upgrades to the next level normal unit. This keeps upgrade paths transparent.

* Upgrade paths for archer, swordsman, longbowman are merged together. They are all considered attacker units and archer/longbowman are not that drastically distinct from warrior/swordsman. So their upgrade path now is: archer/swordsman -> longbowman -> medieval infantry (plus all unique units along the way).
* Warrior upgrades to Longbowman. Never used them after that point.

## Concepts

* Overall unit strength progression is smoothened out to avoid immediate previous generation obsoletion.
* Units withing classes are spreaded out along tech tree to prolong their use.
* Defenders are cheap and tough but weak.
* Attackers are about 50% stronger than same era defenders. They easily beat them on flat land but not that easy in rough terrain and cities.
* Slow attackers are moderately tough. They can survive in rought terrain and play supportive defense role.
* Fast (mounted) attackers are fragile and cannot withstand the counterattack. They still benefit from first strike and disengagement.
* The above does not apply to motorized/armored modern attackers. The era of the foot soldiers sunset so they have better defense/offense ratio similar to previous era foot soldiers.
* Basic defenders (Spearman, Pikeman, Rifleman) do not require resources to ensure adequate defense at all times.
* Artillery strength is doubled to make them more usable in not even that huge groups.
* Early ships movement rate increased by 1 to let them cross gaps between land easier.
* Transport capacity is doubled to make them usable in transferring large armies.
* Warship bombardment range is increased tremendously to assist in land operations.

## Defenders

| unit | era | advancement | cost | att | def | mov | res |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | :----: |
| Spearman | Ancient Times - early | Bronze Working | 20 | 1 | 2 | 1 |  |
| Pikeman | Ancient Times - late | Code of Laws | 30 | 1 | 3 | 1 |  |
| Musketman | Middle Ages - middle | Chemistry | 40 | 2 | 4 | 1 | + |
| Rifleman | Industrial Ages - early | Nationalizm | 60 | 3 | 6 | 1 |  |
| Infantry | Industrial Ages - middle | Steel | 90 | 4 | 8 | 1 | + |
| Mechanical Infantry | Modern Times - early | Motorized Transportation | 120 | 5 | 10 | 2 | + |
| TOW Infantry | Modern Times - late | Smart Weapons | 160 | 6 | 12 | 2 |  |

* Pikeman, Musketman are slightly moved around the tech tree to spread out and utilize their usage time.
* Infantry is moved to a different research branch (Steel) but it still uses rubber (Replaceable Parts). This way it becomes slightly more difficult to beeline from the beginning of the age.
* TOW is reclassificed as an ultimate anti-tank mobile missile defense. There is no need for another attacker in modern era.

## Slow Attackers

| unit | era | advancement | cost | att | def | mov | res |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | :----: |
| Archer | Ancient Times - early | Warrior Code | 20 | 2 | 1 | 1 |  |
| Swordsman | Ancient Times - early | Iron Works | 30 | 3 | 2 | 1 | + |
| Longbowman | Middle Ages - early | 40 | 4 | 3 | 1 |  |
| Medieval infantry | Middle Ages - late | Physics | 60 | 6 | 4 | 1 | + |
| Guerilla | Industrial Ages - early | Electricity | 90 | 8 | 5 | 1 |  |
| Marine | Industrial Ages - late | Amphibious War | 120 | 10 | 7 | 1 |  |

* Longbowman is tougher than Knight to serve as field defender.
* Medieval infantry is another copy of Longbowman and Knight appearing at the same time. Reclassified as next generation foot attacker between Longbowman and Guerilla by both strength and appearance time.
* Guerilla moved earlier to increase its lifespan before Marine obsolete it. Also reclassified as an attacker with increased offense strength.
* Marine is slightly tougher as the last standing foot soldier to still be somewhat useful in early tak era.

## Fast Attackers

| unit | era | advancement | cost | att | def | mov | res |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | :----: |
| Chariot | Ancient Times - early | The Wheel | 30 | 2 | 1 | 2 | + |
| Horseman | Ancient Times - late | Horseback Riding | 45 | 3 | 1 | 2 | + |
| Knight | Middle Ages - early | Chivalry | 60 | 4 | 2 | 2 | + |
| Cavalry | Middle Ages - late | Military Tradition | 90 | 6 | 2 | 2 | + |
| Tank | Industrial Ages - late | Motorized Transportation | 180 | 12 | 6 | 2 | + |
| Modern Armor | Modern Times - early | Synthetic Fibers | 240 | 16 | 10 | 3 | + |

* Cavalry speed reduced to match all mounted units and not be as fast as modern tank.

## Paratroopers

| unit | era | advancement | cost | att | def | mov | res |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | :----: |
| Paratrooper | Industrial Ages - late | Advanced Flight | 130 | 4 | 9 | 1 | + |
| Modern Paratrooper | Modern Times - early | Synthetic Fibers | 180 | 6 | 12 | 1 | + |

## Artillery

| unit | era | advancement | cost | mov | bomb | range | rate |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | ----: |
| Catapult | Ancient Times - early | Mathematics | 20 | 1 | 8 | 1 | 1 |
| Trebuchet | Middle Ages - early | Engineering | 30 | 1 | 12 | 1 | 1 |
| Cannon | Middle Ages - late | Mettalurgy | 40 | 1 | 16 | 1 | 1 |
| Artillery | Industrial Ages - middle | Replaceable Parts | 120 | 1 | 24 | 2 | 2 |
| Radar Artillery | Modern Times - late | Robotics | 200 | 0 | 0 | 2 | 32 | 2 | 3 |

## Aircrafts

| unit | era | advancement | cost | att | def | mov | bomb | range | rate |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Fighter | Industrial Ages - late | Flight | 80 | 4 | 2 | 1 | 3 | 6 | 1 |
| Bomber | Industrial Ages - late | Flight | 180 | 0 | 2 | 1 | 12 | 10 | 3 |
| Jet Fighter | Modern Times - early | Rocketry | 160 | 8 | 4 | 1 | 3 | 9 | 1 |
| Stealth Fighter | Modern Times - late | Stealth | 200 | 8 | 6 | 1 | 6 | 12 | 2 |
| Stealth Bomber | Modern Times - late | Stealth | 300 | 0 | 5 | 1 | 18 | 16 | 3 |

## Transports

| unit | era | advancement | cost | att | def | mov | capacity |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | ----: |
| Curragh | Ancient Times - early | Alphabet | 15 | 1 | 1 | 3 | 2 |
| Galley | 	Ancient Times - late | Map Making | 30 | 1 | 1 | 4 | 4 |
| Caravel | Middle Ages - middle | Astronomy | 40 | 1 | 2 | 5 | 6 |
| Galleon | Middle Ages - late | Magnetism | 50 | 1 | 2 | 5 | 8 |
| Transport | Industrial Ages - middle | Combustion | 100 | 1 | 2 | 6 | 12 |

## Warships

| unit | era | advancement | cost | att | def | mov | bomb | range | rate |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Curragh | Ancient Times - early | Alphabet | 15 | 1 | 1 | 3 | 0 | 0 | 0 |
| Frigate | Middle Ages - late | Magnetism | 60 | 2 | 2 | 5 | 3 | 3 | 2 |
| Ironclad | Industrial Ages - early | Ironclad | 150 | 5 | 5 | 3 | 6 | 3 | 2 |
| Destroyer | Industrial Ages - middle | Combustion | 300 | 12 | 8 | 8 | 6 | 3 | 2 |
| Cruiser | Industrial Ages - middle | Combustion | 370 | 15 | 10 | 6 | 7 | 3 | 2 |
| AEGIS Cruiser | Modern Times - late | Robotics | 370 | 15 | 10 | 7 | 6 | 4 | 2 |
| Battleship | Industrial Ages - late | Mass Production | 450 | 18 | 12 | 5 | 8 | 4 | 2 |
| Submarine | Industrial Ages - late | Mass Production | 150 | 8 | 4 | 4 | 0 | 0 | 0 |
| Nuclear Submarine | Modern Times - early | Fission | 200 | 8 | 4 | 5 | 0 | 0 | 0 |
| Carrier | Industrial Ages - late | Mass Production | 250 | 1 | 8 | 7 | 0 | 0 | 0 |

## Missiles

| unit | era | advancement | cost | att | def | mov | bomb | range | rate |
| ---- | ---- | ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Cruise Missile | Modern Times - early | Rocketry | 60 | 0 | 0 | 1 | 16 | 4 | 3 |
| Tactical Nuke | Modern Times - early | Space Flight | 500 | 0 | 0 | 1 | 0 | 0 | 0 |
| ICBM | Modern Times - middle | Satellites | 800 | 0 | 0 | 1 | 0 | 0 | 0 |

# Governments

I found myself using about 1-3 combat units per city at all time. More is usually not needed as they die in war. All support is linear for town-city-metro to avoid sudden support jump by founding/captuing a small town and encourage growing metroes.

| government | `town` | `city` | `metr` | cost | police | selling point |
| ---- | ----: | ----: | ----: | ----: | ----: | ---- |
| Despotism | 6 | 6 | 6 | 1 | 2 | Good support for early war |
| Monarchy | 4 | 4 | 4 | 1 | 3 | No war weareness |
| Feudalism | 4 | 6 | 8 | 2 | 3 | Massive army support |
| Communism | 4 | 5 | 6 | 1 | 4 | Low corruption in large empire |
| Fascism | 4 | 6 | 8 | 1 | 4 | Massive army support |
| Republic | 0 | 1 | 2 | 2 | 1 | Money cow |
| Democracy | 0 | 0 | 0 | 3 | 0 | Super money cow |

* Democracy is the biggest money cow and pays for units a lot even at peace time.
* Republic metroes support minimal 1 police + 1 worker. Anything above is pricey.
* Monarchy cities support minimal 3 police + 1 worker. Anything above costs a little. Becomes obsolete in Industrial Ages.
* Feudalism allows 2 extra military units per city on top of police/worker support. Useful to wage massive war.
* Communism supports police/workers plus minimal army. Corruption is low for large empires.
* Fascism support is increased to make it an ultimate mass war choice in modern era.
* Republic support is decreased and unit cost increased to reduce its appeal as the most universal government of all eras. Now it is impossible to wage massive and long wars with it.
* Democracy is an ultimate peaceful development choice heavily penalized for ANY units.

# Terrain and improvements

## Fortress and barricade

Without ZOC it is useless to build fortifications in key strategic location as invaders will just go around them. Therefore, vanilla fortresses are just never used even by human player. Fortress construction time should be *very* short so workers may erect them in large quantities even during hot war on some tactical directions.

* Fortress base construction time is 4 (two turns build time on flat terrain). Barricade base construction time is 8.
* Fortress is available from start.
* Fortress and barricade defence bonus is decreased to 25% (50% combined) so they do not confer more protection than city walls. Otherwise, player would be tempted to just surround cities with barricades which is ridiculous.

## Defense bonuses

All ridiculous 10% bonuses on flat terrains and water (?) are removed. All mountains including volcano are 100%. Simple and easy to remember.

## Wetland

Wetlands are absolutely not usable and normally cleaned up to uncover grassland. I don't even understand why they are in a game if they are cleanable? Some sort of mini game that leads absolutely nowhere but just waste worker time. As such I don't absolutely see a point for them to be cleaned for such ridiculously long time. Therefore, I have significantly reduced wetland cleanup time. Player also can found cities direcly on wetland.

## Railroad

Railroad is insanely overpowered not requiring investment/maintenance but skyrocketing food and shield yield by ridiculous numbers. Not much I can do about it because it is not configurable in editor. I just quadroupled its construction time. Hope this compensates its value.

## Yield

The game is strangely restrictive on food. Only terrain supporting further growth are grassland and flood plains and there are not many of them on a map. Everything else is progressively less interesting. There is no much land in game already and about 2/3 of it is filled by 0/1 food terrain. I don't think this is fixable for land tiles as a single unit food addition is going to break a game. However, I believe we can safely add extra food to coast tiles. That will at least sustain cities on tundras a little more.

Same story with shields. I feel like desert and mountains are most unattractive land types which player tries to avoid like a plague. If not food, we should give them more shields to encourage settlements there. This will add some production value to desert and mountains and make them not inferior to hills.

| terrain | food | shields | commerce | irrigation | mining | road |
| ---- | ----: | ----: | ----: | ----: | ----: | ----: |
| Desert | 0 | 2 | 0 | +1 | +1 | +1 |
| Tundra | 1 | 1 | 0 | +1 | +1 | +1 |
| Hills | 1 | 1 | 0 | +1 | +2 | +1 |
| Mountains | 0 | 1 | 0 | - | +3 | +1 |
| Coast | 2 | 0 | 2 | - | - | - |
| Sea | 2 | 0 | 1 | - | - | - |

* Desert generates one more shield to be viable as a production source at least.
* Tundra is irrigable making it possible to settle on.
* Hills are irrigable to minimally support cities in mountain ranges without access to normal food terrain.
* Mountains are ultimate shield producer. Should shine next to flood plains or other food sources.
* Coast and Sea generate one more food to sustain harsh terrain (Desert, Tundra, Hills, Mountains) works good with Harbor.

## Strategic resources

* Appearance ratio for late resources is increased to 160. It is not really clear to me why only few lucky could build tanks, infantry and ICBM.
* All resources now have diappearance probability to allow their rotation across the globe. Disappearance probability for all resources is about doubled to increase their rotation frequency across the globe. This way each player has more chance to acquire/lose resource during the play. More fair this way and less dependency on dumb luck.

| resource | appearance ratio | disappearance probability |
| ---- | ----: | ----: |
| Horses | 160 | 200 |
| Iron | 160 | 200 |
| Saltpeter | 160 | 200 |
| Coal | 160 | 200 |
| Oil | 160 | 100 |
| Rubber | 160 | 100 |
| Aluminum | 160 | 100 |
| Uranium | 160 | 50 |

# Buildings

## Barracks

Barracks effectively add 1/3 on top of unit strength which is about same in unit count. So they pay off for themselves as soon as city invests [barracks cost * 3] in units. With 20 shields vanilla barracks cost it equals to three spearmen/archers or two horsemen/swordsmen. That is like nothing in the world of Civ 3 combat where units floods the battlefield. Obviously, building such cheap barracks before producing any units is no brainer. This mod increases barracks cost and maintenance to slightly correct the situation. Yet it is still must have improvement before full scale war.

* Barracks cost/maintenance: 6/2

## Production multipliers

Railroad already about doubles production. Then factories and power plants come in quick succesion effectively quadroupling production together with railroad. I like production but this is definitely too much. I have cut all factories and power plant bonues in half.

