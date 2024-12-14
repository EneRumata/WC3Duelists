"Duelists_2_0_0.w3x" is the map file for 1.26a version of TFT. Unprotected, can be opened in JNGP World Editor.

"map_code_with_standard_innites.j" file was created using JNPG and contains all the standard and non-standard map code.

"tablitsa_very_old.xlsx" is an outdated version of "tablitsa".

"tablitsa.xlsx" excel file is used to help me in development.
 List 1 counts units strength and cost and memorise it. It also has an info about some unit AI target priorities.
   Left red side is DPS, middle green side in health, right gray side in spell custom gold cost and total unit cost, last blue side in an AI info.
 List 4 calculates the value of players armies at every attack wave, which is equal to desired AI attack waves values. It also contains some code info, mainly unit-type-ids for warriors triggering an event and having some unique action with it.
   "Attack" group memorizes warrior-IDs for "Unit has been attacked" event.
   "DMG" group memorizes warrior-IDs for "Unit takes damage" event.
   "Cast" group memorizes spell-IDs for "Unit cast spell" event.
   "Spell id" group memorizes ingame orders of some spells, which shouldnt duplicate.
   Next part calculates bonuses of one unique modifier.
   Then there is some calculations I cannot remember.
   The last part memorizes interchangeable spell-IDs and other type of non-recurring ingame spell orders.
 List 2 is outdated and doesn't do anything.
 List 3 is outdated and doesn't do anything.
