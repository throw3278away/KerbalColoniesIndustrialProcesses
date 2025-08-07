# Kerbal Colonies Industrial Processes
Patches for Kerbal Colonies for a Number of Mods

### Currently covers:
1. Rational Resources + CRP
   * Various resources can be mined with KC Mining Facility.[^1]
   * A large number of ISRU recipes added to KC IRSU. This is acquired by parsing RRCompanion omniconverter configurations with a Python script.[^2]
   * Bonus: If you have Real Fuel installed together with RR + CRP, KC ISRU can also use RF recipes added by RR.
2. Rational Resources EL Utilites (and its requirements)
   * Changes EL recipes in KC to use CRP resources (e.g. MetalOre -> MetallicOre)
3. Far Future Technologies
   * Mining LqdHe3 from KC Mining Facility.[^1]

[^1]: Limited to planetary resources only, as KC Mining Facility is hardcoded to only check for resources in the planetary crust, not ocean, atmosphere or exosphere.
[^2]: All EC (or similar resources) in input or output are removed, as KC will have its own power system.
