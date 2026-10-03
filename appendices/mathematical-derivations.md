# Appendix B: Mathematical Derivations

## B.1 Lorentz Force in Mass Analysis
When an ion of mass $m$ and charge $q$ is accelerated through potential $V_{\text{ext}}$, its kinetic energy is:

$$E_k = \frac{1}{2} m v^2 = q V_{\text{ext}} \implies v = \sqrt{\frac{2 q V_{\text{ext}}}{m}}$$

In the magnetic mass analyzer, the centripetal force is supplied entirely by the magnetic Lorentz force ($B \perp v$):

$$F_c = \frac{m v^2}{r} = q v B \implies r = \frac{m v}{q B}$$

Substituting velocity $v$:

$$r = \frac{m}{q B} \sqrt{\frac{2 q V_{\text{ext}}}{m}} = \frac{1}{B} \sqrt{\frac{2 m V_{\text{ext}}}{q}}$$

Solving for mass $m$:

$$m = \frac{q B^2 r^2}{2 V_{\text{ext}}}$$

This shows that for fixed orbit radius $r$ (defined by the analyzer geometry) and extraction voltage $V_{\text{ext}}$, the selected mass is strictly proportional to $B^2$.

## B.2 Projected Range Gaussian Distribution
For an ideal amorphous medium, the 1D spatial distribution of implanted ions follows:

$$C(x) = C_{\text{peak}} \exp\left( -\frac{(x - R_p)^2}{2 \Delta R_p^2} \right)$$

To relate peak concentration $C_{\text{peak}}$ to total implant dose $\Phi$, integrate over space:

$$\Phi = \int_{-\infty}^{\infty} C(x) \, dx = C_{\text{peak}} \int_{-\infty}^{\infty} \exp\left( -\frac{(x - R_p)^2}{2 \Delta R_p^2} \right) \, dx$$

Using the standard Gaussian integral $\int_{-\infty}^{\infty} e^{-u^2} du = \sqrt{\pi}$:

$$\Phi = C_{\text{peak}} \sqrt{2\pi} \Delta R_p \implies C_{\text{peak}} = \frac{\Phi}{\sqrt{2\pi} \Delta R_p} \approx \frac{0.3989 \, \Phi}{\Delta R_p}$$

## B.3 Solid-Phase Epitaxial Regrowth Arrhenius Law
The regrowth velocity $v$ of amorphous silicon is thermally activated:

$$v(T) = v_0 \exp\left( -\frac{E_a}{k_B T} \right)$$

For (100) silicon:
- $v_0 \approx 3.1 \times 10^8\text{ cm/s}$
- $E_a \approx 2.70\text{ eV}$
- $k_B \approx 8.617 \times 10^{-5}\text{ eV/K}$

At $T = 600^\circ\text{C} = 873.15\text{ K}$:

$$\frac{E_a}{k_B T} = \frac{2.70}{8.617 \times 10^{-5} \times 873.15} = \frac{2.70}{0.07524} \approx 35.885$$

$$v(600^\circ\text{C}) = 3.1 \times 10^8 \times e^{-35.885} \approx 3.1 \times 10^8 \times 2.60 \times 10^{-16} \approx 8.06 \times 10^{-8}\text{ cm/s} = 0.81\text{ nm/s} \approx 48\text{ nm/min}$$
