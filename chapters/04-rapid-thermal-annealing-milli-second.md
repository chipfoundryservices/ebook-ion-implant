# Chapter 4: Annealing Kinetics & Solid-Phase Epitaxy

## 4.1 Solid-Phase Epitaxial Regrowth (SPER)
To activate dopants electrically and eliminate leakage, the damaged lattice must be repaired. Amorphized silicon regrows epitaxially from the underlying crystalline template via **Solid-Phase Epitaxial Regrowth (SPER)**:

$$v_{\text{SPER}}(T) = v_0 \exp\left(-\frac{E_a}{k_B T}\right)$$

Where $E_a \approx 2.7\text{ eV}$ for intrinsic silicon along the (100) plane. At $600^\circ\text{C}$, SPER achieves recrystallization velocities of $\sim 1\text{–}10\text{ nm/min}$, successfully incorporating dopants onto substitutional lattice sites well above solid equilibrium solubility.

## 4.2 Transient Enhanced Diffusion (TED)
When wafers are heated in conventional quartz furnaces ($800\text{–}1000^\circ\text{C}$ for minutes), $\{311\}$ interstitial clusters dissolve, releasing free interstitials. These interstitials bind with dopants like Boron, causing diffusion rates to surge by $10,000\times$ over normal thermal diffusion until interstitials recombine.

$$D_{\text{eff}} = D_{\text{thermal}} + D_{\text{TED}}(t)$$

TED causes shallow source/drain extensions to spread deeply into the channel, destroying sub-5nm transistor geometry.

## 4.3 Millisecond Annealing: Laser Spike & Flash Lamp (LSA / FLA)
To defeat TED, the semiconductor industry abandoned furnace soak anneals in favor of sub-millisecond thermal processing:
1. **Laser Spike Annealing (LSA):** Continuous-wave $\text{CO}_2$ or diode laser beams raster across the wafer, heating the top surface to $1100\text{–}1350^\circ\text{C}$ for $0.2\text{–}1.0\text{ ms}$.
2. **Flash Lamp Annealing (FLA):** High-power xenon flashlamps deliver pulses of $1\text{–}5\text{ ms}$.

Because heating time is shorter than the $\{311\}$ cluster dissolution time constant, dopants activate substitutionally with near-zero diffusion ($<0.5\text{nm}$ spatial movement).
