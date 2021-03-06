
# Type: nuclide


an atomic species characterized by the specific constitution of its nucleus

URI: [chemont:Nuclide](http://w3id.org/chemontNuclide)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[Radionuclide],[Nuclide&#124;energy_level:string%20%3F;atomic_number(i):count%20%3F;symbol(i):string%20%3F;name(i):string%20%3F]^-[Radionuclide],[Atom]^-[Nuclide],[Atom])

## Parents

 *  is_a: [Atom](Atom.md) - A material entity consisting of exactly one atomic nucleus and the electron(s) orbiting it.

## Children

 * [Radionuclide](Radionuclide.md) - an atom that has excess nuclear energy, making it unstable

## Referenced by class


## Attributes


### Own

 * [energy level](energy_level.md)  <sub>OPT</sub>
    * Description: e.g. ground, stable
    * range: [String](types/String.md)

### Inherited from atom:

 * [atomic number](atomic_number.md)  <sub>OPT</sub>
    * Description: number of proteins in an atom
    * range: [Count](types/Count.md)
 * [name](name.md)  <sub>OPT</sub>
    * Description: name of chemical entity. E.g. nickel, carbon-16
    * range: [String](types/String.md)
 * [symbol](symbol.md)  <sub>OPT</sub>
    * Description: short symbol for chemical entity, e.g. K, C-16
    * range: [String](types/String.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Aliases:** | | nucleide |
|  | | nuclear species |
| **Examples:** | | Example(value='https://en.wikipedia.org/wiki/Isotopes_of_tantalum#Tantalum-180m', description=None) |

