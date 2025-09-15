# Kerbal Colonies Industrial Processes
Chemistry, thermodynamics, nuclear. We do them all.

<img width="668" height="452" alt="pcf" src="https://github.com/user-attachments/assets/d28591f6-6e28-4e31-b9d8-cf6c65a80d4b" />

This mod all a few new facilities and a large number of resource extraction and conversion recipes from other mods to Kerbal Colonies.

### Requirements
Kerbal Colonies Core

KerbalColonies-ELPConfig

Both can be found on CKAN or https://forum.kerbalspaceprogram.com/topic/227961-kerbal-colonies-v1011-hotfix-112x/

Patch Manager: CKAN or https://forum.kerbalspaceprogram.com/topic/163072-112x-patchmanager/

And at least one of the mods listed in ```Resource Extraction and Conversion Recipes``` section. Otherwise, this mod will not do anything.

### New facilities:
#### Advanced ISRU
  For all your nuclear processing and advanced ISRU recipe needs needs. Currently using KC ISRU KK group but with double the cost. If Community Resource Pack is installed, Uraninite will be added to KC Mining Facility and EnrichedUranium from Uraninite will be added to this building.
#### Phase Conversion Facility
  Liquid to gas and gas to liquid. Does not require Kerbals to operate.
#### Greenhouse
  Greenhouse for growing food.
#### Agriculture Facility
  Agriculture facility for more advanced organic material manufacture.
#### Logistics Warehouse
  A large warehouse for solid nonvolatile resources. Recommended to be built first if you have MKS. A very large interaction range.
#### Cryo Tank Array
  A large half underground cryo tank for liquid and gas. Also has a very large interaction range. Requires EC to operate.
#### Secured Warehouse
  A medium warehouse for volatile resources (e.g. Uraninite, Antimatter). Also has a very large interaction range. Requires EC to operate.
#### Large Hanger
  A very large hanger facility. Can store only 1 craft, as long as the size is within the vanilla physics range. Perfect for those who wants to build and launch motherships from the surface of Mun or Minmus.
#### Flare Stack
  For automatic voiding of resources. Having options to void extra resources is simple a good design. Voiding recipe always has an input of 100.
#### EUP
  A starter fission reactor that acts more like a fuel cell, terrible efficiency and no production throttling. A very good choice for CRP players. Optional patch to swap out the Fuel Cell generator that comes with CAB with Patch Manager. Default active for CRP players.
#### Partitioned Storage 
  Deprecated. Will be removed in the next major update.
#### Cryogenic Distillation Tower
  Atmospheric extraction of resouces.
#### Accelerator Complex
  Anti-matter manufacture facility. Requires Far Future Technologies. Consumes 20k EC/s + LqdHydrogen/Fission Particle, and requires Level 3 CAB.

### Tech Tree support
#### Stock
Not much to say here. All new facilities have tech tree progression similar to the KC CAB.

#### Community Tech Tree
All new facilities and those that have tech tree placement in KC have been converted to support CTT. Note that they are relatively spread out, covering multiple branches (e.g. bottom branch for colonization and greenhouse, top branch for fission/fusion reactor).
If you are using ```Hide Empty Tech Tree Nodes``` mod, make sure that in the difficulty setting, enable ```Use RDNode Settings```. Otherwise, some of the nodes will be hidden and you might not be able to upgrade/construct the facilities. This is due to HETTN
do not consider KC facility tech tree nodes as parts.

### Resource Extraction and Conversion Recipes:
1. Rational Resources + CRP
   * Various resources can be mined with KC Mining Facility (planetary) and Cryogenic Distillation Tower (atomspheric).
   * A large number of ISRU recipes added to KC IRSU. This is acquired by parsing RRCompanion omniconverter configurations with a Python script.
   * Bonus: If you have Real Fuel installed together with RR + CRP, KC ISRU can also use RF recipes added by RR.
2. Rational Resources EL Utilites OR MKS
   * Changes EL recipes in KC to use CRP resources (e.g. MetalOre -> MetallicOre)
3. Far Future Technologies
   * Mining LqdHe3 from KC Mining Facility (planetary) and Cryogenic Distillation Tower (atomspheric).
   * Nuclear Salt Water, Fission Particle and Fission Pellet production in Advanced ISRU
   * Anti-matter from LqdHydrogen or Fission Pellets in Accelerator Complex
4. Near Future Technologies
   * Depleted fuel recycling into EnrichedUranium or XenonGas
   * EnrichedUranium from Ore
   * Lithium from Ore
5. Wild Blue Industries & Pathfinder[^1]
   * With Pathfinder installed, all buildings and upgrades will now take Equipment and Konkrete. This places the construction of permanent KC colonies behind considerable logistics and/or medium/big Pathfinder bases.
   * Production of Equipment, Konkrete and Coolant. Coolant is currently useless, as thermodynamics is not a thing in KC.
6. MKS & USI
   * With MKS installed, all buildings and upgrades will now take SpecializedParts, MaterialKits and Machinery. This places KC Colonies in mid-to-late game, as buildings can cost 100k+ MaterialKits per upgrade or construction.
   * Almost all recipes in MKS are now available in ISRU, Greenhouse, and Agriculture facilities. Recipes and production speed based on Atlas (aka skipping intermediate products).
   * Almost all recipes consume Machinery, similar to MKS itself. This also extends to any recipes added by other patches or mods. Recipes in PCF, Greenhouse and Agriculture facilities have reduced Machinery consumption speed.
   * Kerbals with MKS traits can be assigned to corresponding buildings, similar to MKS (e.g. Farmer and Scientist to Greenhouse).

#### Planned addtitions and changes
* Regolith sifter: He3 from moon rocks
* Singularity research facility: Lightyear distance communication station. Hope you have an extra fusion reactor ready.

[^1]: MKS patches will take precedence over all changes in this section.