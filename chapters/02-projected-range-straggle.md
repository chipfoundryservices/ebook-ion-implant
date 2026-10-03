# Chapter 2: Range Theory & Spatial Straggle Physics

## 2.1 The Lindhard-Scharff-Schiøtt (LSS) Stopping Theory
As high-energy ions penetrate silicon, they lose energy via two independent mechanisms:
1. **Nuclear Stopping Power ($S_n(E)$):** Elastic collisions between the incoming ion and silicon nuclei. Dominates at low ion velocities; causes lattice displacements, vacancies, and interstitial defects.
2. **Electronic Stopping Power ($S_e(E)$):** Inelastic collisions with bound and valence electrons. Dominates at high ion velocities; produces ionization and excitation without direct atomic displacement.

$$-\frac{dE}{dx} = N [S_n(E) + S_e(E)]$$

Where $N$ is the atomic density of silicon ($5.0 \times 10^{22}\text{ atoms/cm}^3$).

## 2.2 Projected Range ($R_p$) and Straggle ($\Delta R_p$)
The total integrated path length along the ion trajectory is the range $R$. Its projection along the surface normal is the **Projected Range** ($R_p$), with standard deviation **Longitudinal Straggle** ($\Delta R_p$) and lateral dispersion **Transverse Straggle** ($\Delta R_\perp$).

For an ideal amorphous substrate, the dopant profile follows a Gaussian distribution:

$$C(x) = \frac{\Phi}{\sqrt{2\pi} \Delta R_p} \exp\left( -\frac{(x - R_p)^2}{2 \Delta R_p^2} \right)$$

## 2.3 Pearson IV & Skewness in Real Crystals
Real-world implants deviate from simple Gaussians due to backscattering and nuclear mass mismatches. Fabs utilize 4-moment **Pearson IV distributions** incorporating:
- Mean ($R_p$)
- Variance ($\Delta R_p^2$)
- Skewness ($\gamma$) — quantifying forward or backward asymmetry
- Kurtosis ($\beta$) — quantifying tail weight

## 2.4 Ion Channeling & Screen Oxides
In single-crystal silicon, open crystallographic axes (such as $\langle 110 \rangle$ and $\langle 100 \rangle$) offer low nuclear stopping power. Ions entering within the critical angle $\psi_c$ can travel 5–10x deeper than expected. Fabs mitigate channeling by:
1. Tilting the wafer $7^\circ$ and twisting $22^\circ\text{–}27^\circ$.
2. Depositing a thin ($2\text{–}5\text{nm}$) sacrificial screen oxide.
3. Performing a pre-amorphization implant (PAI) using neutral $\text{Si}^+$ or $\text{Ge}^+$ ions.
