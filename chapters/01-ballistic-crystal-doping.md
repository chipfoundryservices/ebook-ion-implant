# Chapter 1: Ballistic Crystal Doping & Ion Beam Extraction

## 1.1 The Physical Imperative of Ion Implantation
Thermal diffusion cannot achieve the retrograde doping profiles, abrupt junctions, and low thermal budgets required for sub-micron and Angstrom-era microelectronics. Ion implantation bypasses equilibrium thermodynamic solubility limits by forcefully driving ionized atoms into a target lattice at kinetic energies ranging from $100\text{ eV}$ (ultra-shallow junctions) to $>3\text{ MeV}$ (deep retrograde wells and image sensor pinned photodiodes).

$$\text{Dose } \Phi = \frac{1}{q A} \int I(t) \, dt$$

Where:
- $\Phi$ = Ion dose in ions/cm$^2$ (typically $10^{11}$ to $10^{16}\text{ ions/cm}^2$)
- $q$ = Elementary charge ($1.602 \times 10^{-19}\text{ C}$)
- $A$ = Scanned wafer area (cm$^2$)
- $I(t)$ = Faraday cup beam current (Amperes)

## 1.2 Ion Source Physics: Freeman, Bernas & ECR
The implant tool begins with an ion source chamber operating at $10^{-5}\text{ to } 10^{-3}\text{ Torr}$. Precursor feed gases—such as $\text{BF}_3$ for Boron, $\text{PH}_3$ for Phosphorus, $\text{AsH}_3$ for Arsenic, and $\text{GeF}_4$ for Germanium—are ionized via thermionic discharge or microwave electron cyclotron resonance (ECR).
- **Filament Life & Halogen Cycle:** Fluorinated feed gases induce tungsten filament erosion via the halogen cycle, dictating source overhaul intervals (100–300 hours).
- **Extraction Optics:** Multi-electrode extraction assemblies extract positive ions at potentials between $10\text{ kV}$ and $80\text{ kV}$, forming a divergent, multi-species ion beam.

## 1.3 90-Degree Mass Analyzing Magnet
The extracted beam contains unwanted species: molecular fragments ($\text{BF}_2^+$, $\text{BF}^+$), isotopes ($^{10}\text{B}$, $^{11}\text{B}$), and metal contaminants ($\text{Fe}^+$, $\text{W}^+$). The beam traverses a dipole bending magnet where the Lorentz force bends ions along circular trajectories:

$$r = \frac{1}{B} \sqrt{\frac{2 m V_{\text{ext}}}{q}}$$

By tuning the magnetic field strength $B$ and setting resolving slit apertures ($R = m / \Delta m \approx 60\text{–}100$), only the selected isotope ($^{11}\text{B}^+$ or $^{75}\text{As}^+$) exits the mass analyzer.
