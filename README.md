# Kerbal Colonies Industrial Processes
Chemistry, thermodynamics, nuclear. We do them all.

<img width="668" height="452" alt="pcf" src="https://github.com/user-attachments/assets/d28591f6-6e28-4e31-b9d8-cf6c65a80d4b" />

This mod all a few new facilities and a large number of resource extraction and conversion recipes from other mods to Kerbal Colonies.

### Requirements
Kerbal Colonies: https://forum.kerbalspaceprogram.com/topic/227961-kerbal-colonies-v1011-hotfix-112x/

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

[^1]: Limited to planetary resources only, as KC Mining Facility is hardcoded to only check for resources in the planetary crust, not ocean, atmosphere or exosphere.
