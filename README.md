# Compact Star Modelling

An independent study project developing my theoretical and computational
understanding of compact stars and dense matter equations of state.

The project begins by working through the physical models presented in
Sagert et al., *Compact Stars for Undergraduates*. My aim is not simply
to reproduce the published results, but to understand the underlying
derivations, implement the models computationally, test the calculations,
and document the development of the project.

## Current objectives

- Develop the required mathematical and computational methods
- Model degenerate matter and its equation of state
- Reproduce selected results from Sagert et al.
- Progress towards numerical models of compact star structure
- Document assumptions, limitations and problems encountered

## Repository Structure

| File | Description |
| --- | --- |
| `Notebooks/white_dwarfs/sagert_white_dwarf_physics.ipynb` | Mathematical derivations and physical interpretation of the white dwarf equations presented in Sagert et al. |
| `Notebooks/white_dwarfs/sagert_white_dwarf_code.ipynb` | Python implementations, numerical stellar structure calculations and verification checks. |
| `Notebooks/neutron_stars/sagert_neutron_star_physics.ipynb` | Mathematical derivations and physical interpretation of neutron star matter and equations of state. |
| `Notebooks/neutron_stars/sagert_neutron_star_code.ipynb` | Python implementation of neutron star equations of state and stellar structure models. |
| `Notebooks/figures/` | Figures produced from the numerical calculations. |
| `eos_conceptual_overview.ipynb` | Reference notebook explaining the physical meaning of the equations. |
| `Glossary.ipynb` | Definitions of mathematical symbols, physical quantities and terminology. |

## Work Completed So Far

- Derived and implemented electron degeneracy pressure in the nonrelativistic and relativistic regimes.
- Explored polytropic equations of state and the Lane Emden equation.
- Implemented numerical integration of the Newtonian white dwarf structure equations.
- Calculated and compared white dwarf mass and radius relationships.
- Worked through the derivation and numerical investigation of the Chandrasekhar mass.
- Implemented the full electron equation of state, including numerical inversion from pressure to energy density.
- Studied the general relativistic corrections to hydrostatic equilibrium and implemented the Tolman Oppenheimer Volkoff equation.
- Investigated the effects of electron energy density and relativistic gravity on stellar structure.
- Produced numerical results corresponding to Figures 1 through 8 of Sagert et al.
- Explored radial oscillations, equilibrium sequences and the theoretical criteria for stellar stability.

## References and Further Reading

The primary framework for the current mathematical derivations and computational implementation is Sagert et al., *Compact Stars for Undergraduates*. provided by Charlie Perkins (Newcastle University) 

The additional texts listed below provide supporting theoretical background and further reading for deeper understanding in derivations, and fundamental understanding. This is a selected reading list rather than an exhaustive bibliography. 

### Primary Reference

Sagert, I. et al. (2006) 'Compact stars for undergraduates', *European Journal of Physics*, 27(3), pp. 577–610. 

### Supporting Literature

Glendenning, N.K. (2000) *Compact stars: Nuclear physics, particle physics, and general relativity*. 2nd edn.

Glendenning, N.K. (2007) *Special and general relativity: With applications to white dwarfs, neutron stars and black holes*. 

Haensel, P., Potekhin, A.Y. and Yakovlev, D.G. (2007) *Neutron stars 1: Equation of state and structure*. 

Schmitt, A. (2010) *Dense matter in compact stars: A pedagogical introduction*. 

Chandrasekhar, S. (1957) *An introduction to the study of stellar structure*. 

## Status

Work in progress.
