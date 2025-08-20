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

### Resource Extraction and Conversion Recipes:
1. Rational Resources + CRP
   * Various resources can be mined with KC Mining Facility.[^1]
   * A large number of ISRU recipes added to KC IRSU. This is acquired by parsing RRCompanion omniconverter configurations with a Python script.
   * Bonus: If you have Real Fuel installed together with RR + CRP, KC ISRU can also use RF recipes added by RR.
2. Rational Resources EL Utilites (and its requirements)
   * Changes EL recipes in KC to use CRP resources (e.g. MetalOre -> MetallicOre)
3. Far Future Technologies
   * Mining LqdHe3 from KC Mining Facility.[^1]
   * Nuclear Salt Water, Fission Particle and Fission Pellet production in Nuclear Works
4. Near Future Technologies
   * Depleted fuel recycling into EnrichedUranium or XenonGas
   * EnrichedUranium from Ore. Efficiency is designed to be terrible.
   * Lithium from Ore. Efficiency is designed to be terrible.
5. Wild Blue Industries & Pathfinder[^2][^3]
   * With Pathfinder installed, all buildings and upgrades will now take Equipment (equal to RocketParts) and Konkrete (equal to 4 * Ore + 4 * RocketParts). This places the construction of permanent KC colonies behind considerable logistics and/or medium/big Pathfinder bases. This patch is applied at ```LAST[zzzzKCIP]```.
   * Production of Equipment, Konkrete and Coolant. Coolant is currently useless, as thermodynamics is not a thing in KC.
#### Planned addtitions and changes
6. MKS & USI (planned)
   * With MKS installed, all buildings and upgrades will now take Special Equipment (equal to RocketParts in original recipes) and required Rocketparts will be multiplied by 4. Additionally, KC Research Compound will require 100 Prototypes to be built and updated. This places the construction of permanent KC colonies behind considerable logistics and/or medium/big MKS bases. This patch is applied at ```LAST[zzzzKCIP]```. This recipe change will take precedence over all other similar changes as long as MKS is installed.
   * Entirety of MKS production chain is now available from ISRU facility.
[^1]: Limited to planetary resources only, as KC Mining Facility is hardcoded to only check for resources in the planetary crust, not ocean, atmosphere or exosphere.
[^2]: MKS patches (planned) will take precedence over all changes in this section.
[^3]: EC generation and life support will be added once publically available KC has been updated with the proper systems.
