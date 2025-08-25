# Kerbal Colonies Industrial Processes
Chemistry, thermodynamics, nuclear. We do them all.

<img width="668" height="452" alt="pcf" src="https://github.com/user-attachments/assets/d28591f6-6e28-4e31-b9d8-cf6c65a80d4b" />

This mod all a few new facilities and a large number of resource extraction and conversion recipes from other mods to Kerbal Colonies.

### Requirements
Kerbal Colonies Core

KerbalColonies-ExtraplanetaryLaunchpadsConfig

Both can be found on CKAN or https://forum.kerbalspaceprogram.com/topic/227961-kerbal-colonies-v1011-hotfix-112x/

And at least one of the mods listed in ```Resource Extraction and Conversion Recipes``` section. Otherwise, this mod will not do anything.

### New facilities:
#### Nuclear Works
  For all your nuclear processing needs. Currently using KC ISRU KK group but with double the cost. If Community Resource Pack is installed, Uraninite will be added to KC Mining Facility and EnrichedUranium from Uraninite will be added to this building.
#### Phase Conversion Facility
  Liquid to gas and gas to liquid. Does not require Kerbals to operate.
#### Greenhouse
  Greenhouse for growing food.
#### Agriculture Facility
  Agriculture facility for more advanced organic material manufacture.
#### Logistics Warehouse
  Storage facilities with 10x the capacity. Recommended to be built first if you have MKS.
#### Large Hanger
  A very large hanger facility. Can only store 1 vehicle, as long as the size is within the vanilla physics range. Perfect for those who wants to build and launch motherships on Mun or Minmus.
#### "Better than SE" Flare Stack
  For automatic voiding of resources. Having options to void extra resources is simple a good design, and practically required when there is a lack of production balancing system. Voiding recipe always has an input of 1000, and this would actually keep some resources available due to how KC processes the recipes. Please note that during high time warp, this threshold is also hugely inflated. Temporally lowering the time warp would get rid of a lot of the leftover resources.

### Resource Extraction and Conversion Recipes:
1. Rational Resources + CRP
   * Various resources can be mined with KC Mining Facility.[^1]
   * A large number of ISRU recipes added to KC IRSU. This is acquired by parsing RRCompanion omniconverter configurations with a Python script.
   * Bonus: If you have Real Fuel installed together with RR + CRP, KC ISRU can also use RF recipes added by RR.
2. Rational Resources EL Utilites OR MKS
   * Changes EL recipes in KC to use CRP resources (e.g. MetalOre -> MetallicOre)
3. Far Future Technologies
   * Mining LqdHe3 from KC Mining Facility.[^1]
   * Nuclear Salt Water, Fission Particle and Fission Pellet production in Nuclear Works
4. Near Future Technologies
   * Depleted fuel recycling into EnrichedUranium or XenonGas
   * EnrichedUranium from Ore. Efficiency is designed to be terrible.
   * Lithium from Ore. Efficiency is designed to be terrible.
5. Wild Blue Industries & Pathfinder[^2][^3]
   * With Pathfinder installed, all buildings and upgrades will now take Equipment and Konkrete. This places the construction of permanent KC colonies behind considerable logistics and/or medium/big Pathfinder bases. This patch is applied at ```LAST[zzzzKCIP]```.
   * Production of Equipment, Konkrete and Coolant. Coolant is currently useless, as thermodynamics is not a thing in KC.
6. MKS & USI[^3]
   * With MKS installed, all buildings and upgrades will now take SpecializedParts, MaterialKits and Machinery. This places KC Colonies in mid-to-late game, as buildings can cost 100k+ MaterialKits per upgrade or construction. Cost of CAB is reduced, for otherwise it would require almost 1 million MaterialKits.
   * Almost all recipes in MKS are now available in ISRU, Greenhouse, and Agriculture facilities. Recipes and production speed based on Atlas (aka skipping intermediate products).
   * Almost all recipes consume Machinery, similar to MKS itself. This also extends to any recipes added by other patches or mods. Recipes in PCF, Greenhouse and Agriculture facilities have reduced Machinery consumption speed.
   * Kerbals with MKS traits can be assigned to corresponding buildings, similar to MKS (e.g. Farmer and Scientist to Greenhouse).
#### Planned addtitions and changes

[^1]: Limited to planetary resources only, as KC Mining Facility is hardcoded to only check for resources in the planetary crust, not ocean, atmosphere or exosphere.
[^2]: MKS patches will take precedence over all changes in this section.
[^3]: EC generation will be added once publically available KC has been updated with the proper systems.
