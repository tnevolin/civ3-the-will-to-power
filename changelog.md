# Governments

No ZOC dictates a different tactics where player cannot operate with limited combat unit groups on a battlefield. Without ZOC everybody need to flood the land with units in attempt to keep enemy from sneaking into gaps. That also requires protecting back cities against flank attacks. All that requires much more units to cities ratio than in Civ 2. With that in mind current free unit supports for different governments are just ridiculously low and will definitely be overflowed during war time. Keep in mind that free unit support includes all units including 2-3 police units and 1-2 workers per city. So even in the peace time cities should maintain like 3-5 units just for police and economical development purposes. That alone may easily overflow free unit tier sucking money from economy. Not to mention supporting regular invasion army. That becomes even more pronounced in modern eras with mixed unit types required (bombardment, air, anti-air, etc.). Therefore, this mod increases free units support for war oriented governments to make them more viable and competing.

Feudalism free support is flattened per town/city/metro and further increased. I don't see much point in slaughtering own citizens to increase army support (???). Feudalism unit cost is decreased. It is supposed to be an ultimate early war oriented viable choice. It sucks at anything else. So should as well be good at army support.

Republic free support is streamlined for aestetic purposes. I also gave it 1 police to put it somewhat between Democracy and other governments.

Democracy unit cost is increased. I don't see much sense in having it lower than Republic's one for the most income rich government option.

| government | town | city | metro | cost | police |
| ---- | ----: | ----: | ----: | ----: | ----: |
| Despotism | 6 | 6 | 6 | 1 | 2 |
| Monarchy | 4 | 6 | 8 | 1 | 3 |
| Communism | 8 | 8 | 8 | 1 | 4 |
| Republic | 2 | 3 | 4 | 2 | 1 |
| Democracy | 0 | 0 | 0 | 3 | 0 |
| Fascism | 6 | 10 | 14 | 1 | 4 |
| Feudalism | 10 | 10 | 10 | 1 | 3 |

# Fortress and barricade

Without ZOC it is useless to build fortifications in key strategic location as invaders will just go around them. Therefore, vanilla fortresses are just never used even by human player. Fortress construction time should be *very* short so workers may erect them in large quantities even during hot war on some tactical directions.

Fortress base construction time is now 4 which allows to built it in two turns on flat terrain. Barricade base construction time is twice longer.

Fortress is also available from start.

Fortress and barricade defence bonus is decreased to 25% (50% combined) so they do not confer more protection than city walls. Otherwise, player would be tempted to just surround cities with barricades which is ridiculous.

# Barracks cost/maintenance

Barracks effectively add 1/3 on top of unit strength which is about same in unit count. So they pay off for themselves as soon as city invests [barracks cost * 3] in units. With 20 shields vanilla barracks cost it equals to three spearmen/archers or two horsemen/swordsmen. That is like nothing in the world of Civ 3 combat where units floods the battlefield. Obviously, building such cheap barracks before producing any units is no brainer. This mod increases barracks cost and maintenance to slightly correct the situation. Yet it is still must have improvement before full scale war.

Barracks cost/maintenance: 6/2

# Terrain defense bonuses

All ridiculous 10% bonuses on flat terrains and water (?) are removed. All mountains including volcano are 100%. Simple and easy to remember.

# Terrain yield

The game is strangely restrictive on food. Only terrain supporting further growth are grassland and flood plains and there are not many of them on a map. Everything else is progressively less interesting. There is no much land in game already and about 2/3 of it is filled by 0/1 food terrain. I don't think this is fixable for land tiles as a single unit food addition is going to break a game. However, I believe we can safely add extra food to coast tiles. That will at least sustain cities on tundras a little more.

Same story with shields. I feel like desert and mountains are most unattractive land types which player tries to avoid like a plague. If not food, we should give them more shields to encourage settlements there. This will add some production value to desert and mountains and make them not inferior to hills.

#### Terrain yield changes

| terrain | food | shields | commerce | irrigation | mine |
| ---- | ----: | ----: | ----: | ----: | ----: |
| Desert | 0 | 2 | 0 | +1 | +1 |
| Mountains | 0 | 1 | 0 | - | +3 |
| Coast | 2 | 0 | 2 | - | - |

# Clean wetland worker job

Wetlands are absolutely not usable and normally cleaned up to uncover grassland. I don't even understand why they are in a game if they are cleanable? Some sort of mini game that leads absolutely nowhere but just waste worker time. As such I don't absolutely see a point for them to be cleaned for such ridiculously long time. Therefore, I have significantly reduced wetland cleanup time.

# Railroad worker job

Railroad is insanely overpowered worker job that costs no shields but skyrocket food and shield yield by ridiculous numbers. Not much I can do about it because it is not configurable in editor. I just quadroupled its construction time. Hope this compensates its value.

# Strategic resources

Appearance ratio for late resources is increased to 160. It is not really clear to me why only few lucky could build tanks, infantry and ICBM.

All resources now have diappearance probability to allow their rotation across the globe. Disappearance probability for all resources is about doubled to increase their rotation frequency across the globe. This way each player has more chance to acquire/lose resource during the play. More fair this way and less dependency on dumb luck.

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

# Units

Units strength and price is generally well balanced in ancient and medieval eras. Later, however, strange thing happens. Units strength start growing rapidly and even jumpy. Whereas, cost almost doesn't grow at all. Combined with quadrupled production power due to factories/plants/railroad it makes discovering new unit a critical winning strategy effectively obsoleting swarm of previous generation units.

## Proposed modifications

Units are distributed more evenly across the tech tree. Their strength is modified to make smoother progressions and give players something to fight with in every era with or without strategical resources.

Contemporary attackers and defenders have comparable strength to avoid obvious prevailing of attack or defense at certain historical periods.

Most of the attackers have their slow/fast counterpart as in vanilla. This is just more emphasized.

Resource requirements for some critical defender units are lifted to ensure everybody can defend well enough.

## Tables

### Defenders

| unit | advancement | C | A | D | M | R | explanation |
| ---- | ---- | ----: | ----: | ----: | ----: | :----: | ---- |
| Spearman | | 20 | 1 | 2 | 1 | | |
| Pikeman | Code of Laws | 30 | 1 | 3 | 1 | | Does not require resource to build. Moved earlier to match raised attack of swordsman and horseman. Otherwise, it is almost never used being superseded by musketman pretty quickly. |
| Musketman | | 40 | 2 | 4 | 1 | + | |
| Rifleman | | 60 | 4 | 6 | 1 |  | |
| Infantry | | 90 | 6 | 9 | 1 | + | |
| Mechanical Infantry | Motorized Transportation | 120 | 8 | 12 | 2 | + | Lowered in tech tree and defender rank. Not an ultimate defender anymore. |
| TOW Infantry | | 160 | 12 | 16 | 2 |  | Reclassified as an ultimate anti-tank missile defense unit. Becomes mobile too. There is no need for another attacker in modern era. |

### Attackers

| unit | advancement | C | A | D | M | R | explanation |
| ---- | ---- | ----: | ----: | ----: | ----: | :----: | ---- |
| Archer | | 20 | 2 | 1 | 1 | | |
| Chariot | | 30 | 2 | 1 | 2 | + | |
| Swordsman | | 30 | 3 | 1 | 1 | + | |
| Horseman | | 45 | 3 | 1 | 2 | + | |
| Longbowman | | 40 | 4 | 2 | 1 | | |
| Knight | | 60 | 4 | 2 | 2 | + | |
| Medieval infantry | Physics | 60 | 6 | 3 | 1 | + | New unit in Conquests that was essentially a longbowman duplicate. Made stronger and appearing later to fill up the gap in late medieval slow attacker. |
| Cavalry | | 90 | 6 | 3 | 2 | + | Speed reduced to not make it that fast and let cavalry army attack 4 times! |
| Guerrilla | Electricity | 90 | 9 | 6 | 1 | | An intermediary attacker between cavalry and marines. Moved slightly early up the tree since not requiring rubber. |
| Marine | | 120 | 12 | 10 | 1 | | An ultimate slow attacker. Defense increased to make use in sole amphibious operations. |
| Tank | | 180 | 12 | 8 | 2 | + | |
| Modern Armor | | 240 | 16 | 12 | 3 | + | |

### Paratroopers

| unit | C | A | D | M | R |
| ---- | ----: | ----: | ----: | ----: | :----: |
| Paratrooper | 130 | 4 | 9 | 1 | + |
| Modern Paratrooper | 180 | 6 | 12 | 1 | + |

### Artillery

| unit | C | A | D | M | bombardment | range | rate of fire |
| ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Catapult | 20 | 0 | 0 | 1 | 4 | 1 | 1 |
| Trebuchet | 30 | 0 | 0 | 1 | 6 | 1 | 1 |
| Cannon | 40 | 0 | 0 | 1 | 8 | 1 | 1 |
| Artillery | 120 | 0 | 0 | 1 | 12 | 2 | 2 |
| Radar Artillery | 160 | 0 | 0 | 2 | 16 | 2 | 2 |

### Aircrafts

| unit | C | A | D | M | bombardment | range | rate of fire |
| ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Fighter | 80 | 4 | 2 | 1 | 3 | 6 | 1 |
| Bomber | 180 | 0 | 2 | 1 | 12 | 10 | 3 |
| Jet Fighter | 160 | 8 | 4 | 1 | 3 | 9 | 1 |
| Stealth Fighter | 200 | 8 | 6 | 1 | 6 | 12 | 2 |
| Stealth Bomber | 300 | 0 | 5 | 1 | 18 | 16 | 3 |

### Warships

| unit | C | A | D | M | bombardment | range | rate of fire |
| ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Frigate | 60 | 2 | 2 | 5 | 3 | 1 | 2 |
| Ironclad | 150 | 5 | 5 | 3 | 6 | 1 | 2 |
| Destroyer | 300 | 12 | 8 | 8 | 6 | 1 | 2 |
| Cruiser | 370 | 15 | 10 | 6 | 7 | 1 | 2 |
| AEGIS Cruiser | 370 | 15 | 10 | 7 | 6 | 2 | 2 |
| Battleship | 450 | 18 | 12 | 5 | 8 | 2 | 2 |
| Submarine | 150 | 8 | 4 | 4 | 0 | 0 | 0 |
| Nuclear Submarine | 200 | 8 | 4 | 5 | 0 | 0 | 0 |
| Carrier | 250 | 1 | 8 | 7 | 0 | 0 | 0 |

### Missiles

| unit | C | A | D | M | bombardment | range | rate of fire |
| ---- | ----: | ----: | ----: | ----: | ----: | ----: | ----: |
| Cruise Missile | 60 | 0 | 0 | 1 | 16 | 4 | 3 |
| Tactical Nuke | 500 | 0 | 0 | 1 | 0 | 0 | 0 |
| ICBM | 800 | 0 | 0 | 1 | 0 | 0 | 0 |

# Unit upgrade paths

I tried to streamline upgrade paths wherever possible. Each normal unit upgrades to chain of unique units and the last unique unit upgrades to the next level normal unit. This keeps upgrade paths transparent.

Upgrade paths for warrior, archer, swordsman, longbowman are merged together. They are all considered attacker units and archer/longbowman are not that drastically distinct from warrior/swordsman. So their upgrade path now is: warrior -> archer -> swordsman -> longbowman -> medieval infantry (plus all unique units along the way). I don't see much point to keep producing warriors while archer become awailable. They do make the cheapest police unit in the game but, I guess, game is still perfectly playable without them.

# Research tree

First of all, I have reduced minimal research time to 1 turn. I seriously don't see point in artificial technology development impediment.

Path to Monarchy is eased up a little. This is the first government after despotism and should be accessible much earlier before Republic and Feudalism to lift exceptionally restrictive Despotism yield penalties.

Cities in Civ 3 grow exceptionally fast. They easily fall into stagnation due to aqueduct or hospital inaccessibility which is pretty boring impediment. I don't think players should be artificially restricted like that. Aqueduct is moved to Mathematic. Sanitation is moved as Engineering successor. I often saw cities easily grow to 12 in the early middle age and then just sitting at this number for the whole era. Ugh.

# Production multipliers

Railroad already about doubles production. Then factories and power plants come in quick succesion effectively quadroupling production together with railroad. I like production but this is definitely too much. I have cut all factories and power plant bonues in half.

