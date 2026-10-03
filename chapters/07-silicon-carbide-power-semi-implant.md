# Chapter 7: Wide-Bandgap Materials: Silicon Carbide & GaN Doping

## 7.1 The Physics of Silicon Carbide (SiC) Implantation
Silicon Carbide ($4\text{H-SiC}$) possesses a wide bandgap ($3.26\text{ eV}$) and immense silicon-carbon bond strength ($4.6\text{ eV}$ vs. $2.3\text{ eV}$ for $\text{Si-Si}$). 
- **Thermal Diffusion is Impossible:** Impurity diffusion coefficients in SiC are essentially zero below $1800^\circ\text{C}$. Ion implantation is the **only viable technique** to create p-n junctions, planar edge terminations, and guard rings in power MOSFETs.

## 7.2 High-Temperature Implantation ($500^\circ\text{C}$)
Implanting SiC at room temperature shatters the crystal lattice into an amorphous state that **cannot be recrystallized** without creating catastrophic polytype inclusions ($3\text{C-SiC}$) and stacking faults. 
- Fabs must implant SiC at chuck temperatures of **$450^\circ\text{C}$ to $600^\circ\text{C}$**.
- In-situ dynamic annealing during hot implantation maintains the $4\text{H}$ polytype crystallinity throughout the collision cascade.

## 7.3 Ultra-High Energy & Annealing ($1650^\circ\text{C}$)
Aluminum ($Al$) is the universal p-type dopant, and Nitrogen ($N$) is the n-type dopant. To form deep planar junction termination extensions (JTE) capable of blocking $1200\text{V to } 3300\text{V}$, implanters must deliver multi-MeV Aluminum ions.
Following implant, wafers are capped with carbon resist and annealed at **$1650^\circ\text{C}$ to $1750^\circ\text{C}$** in argon overpressure furnaces to activate Aluminum substitutionally.
