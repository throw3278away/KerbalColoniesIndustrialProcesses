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
  Storage facilities with 10x the capacity. Recommended to be built first if you have MKS. A very large interaction range.
#### Large Hanger
  A very large hanger facility. Can only store 1 vehicle, as long as the size is within the vanilla physics range. Perfect for those who wants to build and launch motherships from the surface of Mun or Minmus.
#### "Better than SE" Flare Stack
  For automatic voiding of resources. Having options to void extra resources is simple a good design, and practically required when there is a lack of production balancing system. Voiding recipe always has an input of 1000, and this would actually keep some resources available due to how KC processes the recipes. Please note that during high time warp, this threshold is also hugely inflated. Temporally lowering the time warp would get rid of a lot of the leftover resources.
#### EUP
  A starter fission reactor that acts more like a fuel cell, terrible efficiency and no production throttling. A very good choice for CRP players. Optional patch to swap out the Fuel Cell generator that comes with CAB with Patch Manager. Default active for CRP players.
#### Partitioned Storage
  Storage that is limited to only one resources. Since default KC storage does not have per-resource limit, overproduction will eventually flood your storage. If all of your storages are partioned to one resource only (aka lock any normal storage facilities), you can now have fully automated production line. Currently there is one caveat: upon construction of partitioned storage, any resource producers cannot put in the whitelisted resouces (and instead get voided) without first that resource existing in the facility (even if there is zero resouces). Two walk-arounds exist: save editing to add a small amount of the whitelisted resouce, or use a craft and transfer a small amount into it.  
#### Cryogenic Distillation Tower
  Atmospheric extraction of resouces.
#### Accelerator Complex
  Anti-matter manufacture facility. Requires Far Future Technologies. Consumes 20k EC/s + LqdHydrogen/Fission Particle, and requires Level 3 CAB.

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