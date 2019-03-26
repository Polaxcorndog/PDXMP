SUMMARY FOR PLAYERS

- Colonies are less directly profitable and cost more in upkeep
- Britain gets a mobilization size penalty from enacting The British Raj to reflect reliance on colonial troops
- Naval unit cap is now more dependent on core ports
- Naval units are now more balanced vis-a-vis cost, build limit, stats, and colonial points
- Literacy is harder to raise and more reliant on social reforms
- Late game artillery (post-1900) is about 25% less murderous
- Late game infantry (post-1900) is a bit more effective w/ infiltration tacitcs and stormtrooper training
- Gas defense is more likely to spawn when at war
- Wars cause a little more damage to pops
- War exhaustion is still crippling but not debilitating
- More iron, coal, sulfur, and oil should generally be available to balance MP shortages
- Constitutional Monarchies can't switch parties (HPM v0.4 change, not mine)
- Colonial and treaty port CBs require certain techs to unlock (HPM v0.4 change, not mine, see ModDB for more info)
- Cotton, rubber, and oil will be a bit more evenly distributed across historical production areas

FULL CHANGELOG 0.1.1

- Fixed Transfer CB CTD (oops)
- Reduced Cut Down To Size Infamy cost (9 infamy down from 13)
- Constitutiona Monarchies can no longer switch parties (Bug, wasnt working as intended)
- Social reforms such as education, and healthcare now carry minimum social spending costs (10% per level, total of 80% for maxed reforms.)
- Taking Core Territory, is now cheaper. (50% down from 70% cost)

FULL CHANGELOG 0.1

Incorporated all changes to “defines.lua” from last version, including:

- Increased overseas provinces support cost (0.06 up from 0.015)
- Decreased diplomat travel time (7 days down from 14)
- Increased always available loan amount (5000 up from 2000)
- Increased factory surplus paychecks (50% up from 30%)
- Increased factory max savings (10000 up from 1500)
- Increased minimum army maintenance (50% up from 5%)
- Increase minimum naval maintenance (50% up from 10%)
- Reverted dig-in speed to original time (5 days down from 10)
- Increased soldier to pop damage (0.3 up from 0.2)
- Removed added war goal Jingoism requirement
- Increased war subsidies amount (30% up from 20%)
- Removed infamy loss from releasing puppets (down from -2)
- Reduced AI likelihood to build naval bases (50% down from 75%)
- Reduced AI likelihood to build forts (25% down from 50%)


Naval Unit Changes

- Increased battleship build limit per port (3 up from 2)
- HPM v.0.4 increased battleship supply amounts, as well as added telephones, fuel, and regular clothes. I did not adjust any of these values
- HPM v0.4 also increased colonial points per battleship (25 up from 15). I did not adjust these values
- Increased the colonial point value of commerce raiders (8 up from 4)
- Increased the naval supply limit usage of commerce raiders (4 up from 3)
- HPM v0.4 increased supply cost of commerce raiders, and added ammunition, regular clothes, and coal. I did not adjust any of these values
- Increased the colonial points of cruisers (16 up from 8)
- HPM v0.4 increased supply costs of cruisers. I did not adjust any of these values
- Reduced the colonial points from dreadnoughts (22 down from 30)
- Increased the dreadnought build limit per port (2 up from 1)
- Increased the hull strength of dreadnoughts (90 up from 80)
- Increased the gun power of dreadnoughts (65 up from 60)
- Increased the fire range of dreadnoughts (.85 up from .8)
- Unlike other ships, HPM v0.4 did NOT adjust any of the supply values for dreadnoughts
- Increased the naval supply limit usage of frigates (2 up from 1)
- Increased the naval supply limit usage of ironclads (6 up from 3)
- HPM v0.4 increased supply costs of ironclads and added regular cloths, coal, and tobacco. I did not adjust any of these values
- Increased naval supply limit usage of man-o-wars (4 up from 2)
- Reduced colonial points from monitors (10 down from 15)
- Increased naval supply limit usage of monitors (6 up from 3)
- HPM v0.4 increased supply costs of monitors and added regular clothes, fuel, coal, and tobacco. I did not adjust any of these values


Balance Changes

- HPM v0.4 increased the "core_pop_militancy_modifier" from reactionary demands. I did not adjust this value
- Reduced the education efficiency boost from "Total Reform" (50% down from 75%)
- Reduced the administrative efficiency boost from "Total Reform" (20% down from 30%)
- Added the "High Quality Ore" triggered modifier
- Reduced the war exhaustion reduction from "Total War" for the 1st Great War (-2.5 down from -3)
- Reduced the war exhaustion reduction from "Total War" for the 2nd Great War (-1.75 down from -2)
- added military staff systems for wallachia, moldavia, ottomans, greece, serbia, brazil, mexico, chile, and bolivia.
- Reduced the boost to artillery support from "Indirect Artillery Fire" technology (50% down from 100%)
- Reduced the boost to artillery defense from "Indirect Artillery Fire" technology (1.5 down from 2)
- Reduced the boost to artillery support from "Heavy Armament" technology (50% down from 100%)
- Increased frontline unit attack damage from "Stormtrooper Training" (4 up from 1)
- Increased engineer unit attack/defense from "Stormtrooper Training" (2 up from 1)
- Increased tank attack from "Human Wave vs Spearhead" (4 up from 1)
- Increased the defense boost from "Helmet Mass Production" invention for infantry and guards (1 up from 0.5)
- Added attack boost from "Helmet Mass Production" invention for infantry and guards (+1 up from 0)
- Increased unlock rate of "Gas Defense" from being at war with a country possessing "Gas Attack" (15% up from 5%)
- Increased unlock rate of "Gas Defense" from neighboring a country possessing "Gas Attack" (5% up from 1%)
- Added -5% mobilization size penalty to Britain for the "British Raj" modifier
- Added -10% tax penalty to Britain for the "British Raj" modifier
- Added 0.1 research point boost to "Dutch East India" modifier
- Made KUK's second reactionary party have State Capitalism
- Reduced education efficiency boost from "Darwinism" (10% down from 50%)
- Reduced max war exhaustion penalty to factory throughput (-80% down from -100%)
- Reduced max war exhaustion penalty to RGO throughput (-80% down from -100%)
- Increased education efficiency from "Acceptable Schools" reform (10% up from 7.5%)
- Increased education efficiency from "Good Schools" reform (15% up from 10%)
- Added staggered pensions cost to education reforms (10, 20, and 30%)
- Increased education efficiency from "Child labor Illegal" reform (+5% up from 2%)
- Increased education efficiency penalty from "Child Labor Restricted" reform (-5% up from -3%)


Mod Flavor

- Changed mod name from HPM to PDXMP
- Added in player - player transfer state and colonies cb
- localized the cbs added
- added in decisions to allow player to player money transfers in game
- localized the decisions and events.
- added impassable terrain for most of the pyrennes
- added new map and flag frames


RGO and Goods Changes

- Required having unlocked "Synthetic Dye" invention for province owner to enact "End of Natural Dyes" decision
- HPM v0.4 added an after 1870 year requirement, added an option to enact this decision if you posses a dye factory already, and increased the unemployment required, to enact "End of Natural Dyes" decision. I did not adjust either of these values
- Reduced the unemployment required in other provinces that benefit from the dye switches to help ensure the RGOs switch (0.4 down from 0.5)
- HPM v0.4 added many new overseas maintenance goods. I removed ammunition, small arms, canned food, steel, fuel, and radios.
- Increased base price of cotton (2.3 up from 2.0)
- Increased base price of iron (4.0 up from 3.5)
- HPM v0.4 increased the output of many late game factories (autos, planes, barrels, synth oil, steamer shipyards, lux. clothes, lux. furniture, steel, clothes, explosives, canned food, dye, liquor, fertilizer, etc.). I did not change any of these values
- Increased the output of machine parts factories (2.25 up from 2.06)
- Increase the same state bonus of machine parts factories (.15 up from 0.125)
- Added synthetic sulphur factory
- Reduced the coal input for steamer shipyards (25 down from 30)
- Reduced the iron input for steel factories (18 down from 20)
- Increase same state bonus for steel factory iron (0.2 up from 0.125)
- Increased the output of artillery factories (1.5 up from 1.38)
- Reduced the fabric input for clipper shipyards (80 down from 100)
- Reduced the steel input for clipper shipyards (20 down from 30)
- Reduced clipper shipyards output (10 down from 12) ***Last version was 9.6 but HPM v0.4 increased it to boost profitability but we reduced the inputs, accomplishing the same goal
- HPM v0.4 reduced furniture factory output (11.45 down from our 11.45). I did not adjust this value
- HPM v0.4 reduced paper mill output (19.6 down from our 12). I did not adjust this value
- HPM v0.4 increased clothes factory fabric input (40 up from our 35). I did not adjust this value
- HPM v0.4 reduced fabric factory output (43.7 down from our 45). I did not adjust this value
- HPM v0.4 reduced cement factory output (2.77 down from our 3). I did not adjust this value
- HPM v0.4 reduced glass factory output (16.7 down from our 18). I did not adjust this value
- Increased dye RGO output (0.24 up from 0.22)
- Added oil change to Bucharest (#664)
- Added "Iron Events"
- Added mid/late game Iron RGO changes in Sweden and the Low Countries
- Added mid/late game "High Quality Iron Ore" modifier to select provinces in Sweden and the Low Countries
- Added Moorhead (#157) and Duluth (#158) to high quality iron ore provinces
- Reduced mean time to happen of iron RGO changes
- Added nerf to Chinese and Korea starting iron output
- Tractors provide 15% more cotton output instead of 3%
- Power loom now provides 20% more cotton instead of 0%
- reaping machine now provies 20% more grain and fruit instead of 15%
- Threshing machine now provides 20% more grain and fruit instead of 15%
- slaughterblock now provides 20% more cattle and wool instead of 10%
- electric machinery now provides 2% more machine parts instead of 0%
- refigirators now provide 20% more cattle, fruit, and fish instead of 15%
- pit coal now provides 80% more coal instead of 50%
- coke now provides 150% more coal instead of 50%
- Advanced ore now provides 30% more iron instead of 25%
- bessemer steel now provides 30% more iron instead of 0%
- reworked medicine technologies tree, and invention discovery.
- inorganic chemistry is now a 1850 tech, organic is now 1870, electricity is 1880, and polymers is 1907.
- lowered chances for pop growth modifiers to be unlocked early on in medicine tree.
- Increased RGO output of "Compound Steam Engines" for coal, iron, oil, and sulfur (15% up from 10%)
- Increased RGO output of "Steam Turbine" for coal, iron, oil, and sulfur (25% up from 15%)
- Increased RGO output of "Combustion Engine" for coal, iron, oil, and sulfur (25% up from 15%)
- Increased iron RGO output of "Bessemer Process" (60% up from 25%)
- Increase iron RGO output of "Open Hearth Furnace" (65% up from 40%)
- Increased iron RGO output from "Advanced Ore Grinding Processes" (40% up from 25%)
- Increased iron RGO output from "Advanced Ore Smelting Processes" (40% up from 25%)
- Increased oil RGO output from "Oil Pumping Machinery" (25% up from 10%)
- Increased the output bonus of the "Mechanized Mining" provincial modifier (75% up from 60%)
- Added provincial modifier for Brazilian and Malaysia rubber booms
- Added provincial modifier for high oil production provinces
- Added localizations for the "high_quality_rubber" and "high_quality_oil" provincial modifiers
- Added rubber boom modifier in four Brazilian provinces between 1880-1910
- Added rubber boom modifier in six Malaysian provinces between 1900-1936
- Added oil boom modifier in three Azerbaijani provinces between 1890-1936
- Limited the poor quality iron ore modifier to uncivilized countries only
- Added event names, descriptions, and option text for new RGO change events
- Added localizations for the "Haber Process" and "Carl Bosch" industrial inventions
- Increased output of synthetic sulfur factory (7.5 up from 2.5)
