# Kerbal Colonies Industrial Processes
Patches for Kerbal Colonies for a Number of Mods

### New facilities:
* Nuclear Works: For all your nuclear processing needs. Currently reusing ISRU KK group but with double the cost. If Community Resource Pack is installed, Uraninite will be added to KC Mining Facility and EnrichedUranium from Uraninite will be added to this building.

### Currently covers:
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

[^1]: Limited to planetary resources only, as KC Mining Facility is hardcoded to only check for resources in the planetary crust, not ocean, atmosphere or exosphere.
