# Chapter 6: Equipment Architecture & Hardware Moats

## 6.1 The High-Current, Medium-Current & High-Energy Triad
The ion implantation equipment market is structured into three specialized tool categories:
1. **High-Current Implanters:** Low energy ($0.2\text{–}20\text{ keV}$), massive beam currents ($10\text{–}60\text{ mA}$). Used for source/drain contacts, polysilicon gates, and amorphization. Dominates total tool unit volume.
2. **Medium-Current Implanters:** Medium energy ($10\text{–}300\text{ keV}$), currents ($0.1\text{–}5\text{ mA}$). Used for precision $V_{th}$ adjustment and halo implants requiring angular accuracy within $\pm 0.1^\circ$.
3. **High-Energy Implanters:** Energies from $300\text{ keV}$ to $>3\text{ MeV}$ utilizing linear RF accelerators (LINACs) or tandem accelerators. Used for deep retrograde wells and CMOS image sensor pinned photodiodes.

## 6.2 Cryogenic Wafer Chucking Moats
At room temperature, light ions like Boron experience significant dynamic self-annealing during beam bombardment, preventing full amorphization. Advanced implanters integrate closed-loop cryogenic electrostatic chucks (ESCs) chilled to $-100^\circ\text{C}$ to $-150^\circ\text{C}$ using gaseous or liquid nitrogen. Cryo-implantation freezes lattice damage in place, enabling complete amorphization at $10\times$ lower doses and creating ultra-abrupt junctions ($<1.5\text{nm/decade}$).

## 6.3 Beam Uniformity, Dose Control & Particle Moats
- **Ribbon Beam vs. Spot Beam:** Applied Materials VIISTA utilizes magnetically shaped ribbon beams; Axcelis Purion utilizes spot beams with fast mechanical electrostatic scanning.
- **Faraday Cup Dosimetry:** In-situ segmented Faraday cups measure beam current continuously to achieve dose uniformity across $300\text{mm}$ wafers of $<0.5\%\ (1\sigma)$.
