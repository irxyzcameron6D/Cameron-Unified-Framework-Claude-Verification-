# Section IV — The Four Forces as PMV Phase States

*Cameron Unified Framework — Paper Draft*  
*Status: In preparation. Not yet peer reviewed.*

---

## IV.1 One Force Law, Four Projections

From Section III, the unified force law is:

```
F  =  Q₁ · Q₂ / r²     where Q = q + im√G               (IV.1)
```

The four fundamental forces are four projections of this single
equation onto different sectors of the pseudo-Euclidean metric
at different scales.

No new equations are needed. No new postulates. The four forces
differ only in:
1. Which sector dominates (real, imaginary, or boundary)
2. The scale at which the force operates
3. Whether the metric is standard or inverted

---

## IV.2 Electromagnetism — Real Sector, φ ≈ 0

**Phase angle:** φ = atan(m√G/q) ≈ 0 for electrons and protons  
**Sector:** Real (α·(Δx_re)² dominates)  
**Origin in Q₁Q₂:** Re(Q₁)·Re(Q₂) = q₁q₂  
**Scale:** Bohr radius (10⁻¹⁰ m) to macroscopic

The electromagnetic force is the real×real term in the complex
charge product. For charged particles where q >> m√G
(electrons: |Im/Re| = 4.6×10⁻¹⁷), the imaginary component
is negligible and:

```
F_EM  ≈  q₁q₂ / r²                                        (IV.2)
```

This is standard Coulomb's law. The entire apparatus of QED —
Feynman diagrams, renormalization, the hydrogen spectrum, the
anomalous magnetic moment — operates in this sector unchanged.

**Maxwell's equations in the real sector:**

```
div_re E_re  =  ρ_q / ε₀       [Gauss — electric]
curl_re E_re  =  −∂B_re/∂t     [Faraday]
div_re B_re  =  0               [no monopoles]
curl_re B_re  =  μ₀J + ...     [Ampere-Maxwell]
```

These are the standard Maxwell equations. The Cameron framework
does not alter them.

**Magnetism** is the velocity-dependent part of the real sector
force — the Lorentz-boosted electric field. In PMV language:
when the source charge has θ > 0 (moving), the retarded field
is asymmetric (stronger forward, weaker backward). The
transverse component of this asymmetry is the magnetic force.

---

## IV.3 Gravity — Imaginary Sector, φ = π/2

**Phase angle:** φ = π/2 for neutral matter  
**Sector:** Imaginary (β·(Δx_im)² dominates)  
**Origin in Q₁Q₂:** −Im(Q₁)·Im(Q₂) = −Gm₁m₂  
**Scale:** Macroscopic to cosmological  
**Range:** Infinite (1/r²)

For charge-neutral matter (q = 0), Q = pure imaginary:

```
F_grav  =  −G·m₁·m₂ / r²      [Newton — exact]           (IV.3)
```

The attractive sign comes from i² = −1. No separate postulate.

**Why gravity cannot be shielded:**  
The electron shells of atoms screen the real sector (electric
charge) completely — the outer world sees Q_re = 0 for neutral
matter. But the electron shells cannot screen the imaginary
sector (gravitational charge). The imaginary component of Q
passes through matter exactly as neutrinos pass through matter.
This is why there is no gravitational Faraday cage.

**Maxwell's equations in the imaginary sector:**

```
div_im E_im  =  ρ_m · √G       [gravitational Gauss = Newton]
curl_im E_im  =  −∂B_im/∂t    [gravitomagnetic Faraday = frame dragging]
```

Frame dragging (Lense-Thirring effect) is the gravitomagnetic
analogue of the magnetic force — the velocity-dependent part of
the imaginary sector force, confirmed by Gravity Probe B (2011).

**The neutron is pure imaginary charge:**  
Q_neutron = 0 + i·m_n·√G, phase φ = π/2 exactly.  
The neutron carries full gravitational charge with zero electric
charge. It is the clearest experimental demonstration that the
imaginary sector is real and physical.

---

## IV.4 The Strong Force — Inverted Imaginary Sector, r < r_proton

**Phase angle:** φ ≈ π/2 (quarks are nearly pure imaginary inside nucleon)  
**Sector:** Imaginary, metric inverted  
**Origin:** Im(Q_quark)² with sign flipped by metric inversion  
**Scale:** 0.9–1.5 fm (nuclear scale)

Inside the proton, at r < r_proton = 8.41×10⁻¹⁶ m, the metric
inverts at the null geodesic surface. Real and imaginary sectors
swap roles.

**Outside the proton** (standard metric, real sector dominant):  
- u quark charge (2/3)e is real — like charges repel
- Quarks would repel each other if free

**Inside the proton** (inverted metric, imaginary sector dominant):  
- The (2/3)e electric charge of the u quark, which was real
  outside, is now imaginary inside the inverted metric
- Imaginary × imaginary = real negative = **attractive**
- Same charge magnitude, same 1/r² law, **opposite sign**

The strong force is the electric force with inverted metric.

### Asymptotic freedom from the metric boundary

Quarks very close together (near the proton center) are deep
in the inverted metric region, where the coupling is weaker
because the imaginary charges partially cancel. As quarks
separate toward the proton surface, they approach the null
geodesic where the inversion is strongest — coupling grows.
At the surface (null geodesic, d² = 0), escaping requires
crossing into the standard metric where the force sign flips
again — infinite energy cost.

**Asymptotic freedom is the gradient of the metric inversion.**  
Confinement is the sign flip at the null geodesic surface.

### The quark Monte Carlo result

Cameron (2015) computed the p-n inter-nucleon force using
Monte Carlo sampling of quark positions in the anchor model
(minority quark at center, majority quarks at surface).

Result: **attraction at 0.9–1.5 fm at 8–14σ significance**
with naive charge sum = 0 (p-n pure van der Waals). ✓

The potential well depth from the Monte Carlo: ~0.09–1.20 MeV.  
Empirical nuclear binding: ~2.22 MeV (deuteron), ~8 MeV/nucleon.  
Gap: relativistic γ factor not yet included (see Gap 3 in disputes/).

### Complexified Maxwell in the inverted metric

```
div_im E_im_inside  =  ρ_color · √(G_strong)
```

where G_strong = 1/α_s replaces G in the strong sector.
The metric inversion swaps which sector is dominant — the
imaginary sector Maxwell equation IS the strong force equation
inside the nucleon.

---

## IV.5 The Weak Force — Sector Boundary, φ = π/4

**Phase angle:** φ = π/4 (equal real and imaginary components)  
**Sector:** The null geodesic boundary itself  
**Origin:** PMV rotation at the exact real-imaginary sector crossing  
**Scale:** ~2×10⁻¹⁸ m (W boson Compton wavelength)

The weak force operates at the boundary between the real and
imaginary sectors — exactly where d² = 0. The W and Z bosons
are **gauge fields of the sector-rotation symmetry** — they
mediate the process of a particle crossing from one sector to
the other.

**Why W and Z bosons are massive:**  
In standard physics, gauge bosons must be massless by gauge
invariance (as the photon is massless). The W and Z acquire
mass through the Higgs mechanism — spontaneous symmetry
breaking of the electroweak gauge group.

In the Cameron framework: the W and Z are massive because the
null geodesic boundary has **finite width** determined by the
sector mixing parameter. The Higgs field is the order parameter
of this mixing — it measures how sharply the transition from
real-dominated to imaginary-dominated metric occurs. A sharp
transition gives massless mediators (like the photon on the
EM null geodesic). A gradual transition gives massive mediators.
The width of the transition IS the W/Z mass.

**Parity violation:**  
The weak force violates parity (left-right symmetry). In the
Cameron framework: the null geodesic boundary has a preferred
orientation inherited from the angular momentum of the PMV
pair (P_re × P_im = ℏn̂). This preferred orientation breaks
left-right symmetry at the boundary. Parity violation is the
statement that the sector boundary is oriented, not isotropic.

---

## IV.6 The Complete Force Unification Table

| Force | Scale | Sector | Metric | Phase φ | Shielded? |
|---|---|---|---|---|---|
| EM | 10⁻¹⁰ m → ∞ | Real | Standard | ≈ 0 | Yes (by opposite charges) |
| Gravity | 1 m → ∞ | Imaginary | Standard | π/2 | No |
| Strong | 10⁻¹⁵ m | Imaginary | **Inverted** | ≈ π/2 | Yes (confinement) |
| Weak | 10⁻¹⁸ m | Boundary | Transitional | π/4 | N/A (decays) |

---

## IV.7 The Complexified Maxwell Equations in 6D

All four forces follow from one field equation extended to
the 6D complex metric:

```
Real sector:
  div_re F_re  =  ρ_q / ε₀              [electric Gauss]
  curl_re F_re  =  −∂F_re/∂t            [Faraday / EM propagation]

Imaginary sector:
  div_im F_im  =  ρ_m · √G             [gravitational Gauss = Newton]
  curl_im F_im  =  −∂F_im/∂t           [gravitomagnetic / frame dragging]

Cross sector (van der Waals coupling):
  div_re F_im + div_im F_re  =  J_cross [Cameron 2015 mechanism]
  curl_re F_im + curl_im F_re  =  0     [sector boundary condition]
```

The **strong force** appears when the inverted metric is applied
to the imaginary sector equations inside the nucleon.

The **weak force** appears as the boundary condition between
real and imaginary sector equations at the null geodesic.

**This is one field equation — four forces.**

---

## IV.8 Gravitomagnetic Predictions

The imaginary sector has its own magnetic analogue —
**gravitomagnetism** — predicted by General Relativity as
frame-dragging and confirmed by Gravity Probe B (2011).

In the Cameron framework, gravitomagnetism is the velocity-
dependent part of the imaginary sector force, in exact analogy
with magnetism in the real sector:

| Real sector | Imaginary sector |
|---|---|
| Electric field E | Gravitoelectric field g |
| Magnetic field B | Gravitomagnetic field B_g |
| Moving charge → B | Rotating mass → B_g |
| Lorentz force F = q(E + v×B) | Geodetic + frame-dragging force |
| Faraday induction | Gravitational wave emission |

The gravitational wave — discovered by LIGO (2015) — is the
electromagnetic wave of the imaginary sector. It propagates
at speed c (confirmed by GW170817, 2017) because both real
and imaginary sectors share the same null geodesic structure.

---

*Next: [Section V — Black Holes and the Metric Boundary](section_V_black_holes.md)*  
*Previous: [Section III — Complex Charge and Force Unification](section_III_complex_charge.md)*

---

*This draft has not been submitted for peer review.*  
*Open questions documented in [disputes/what_doesnt_work.md](../disputes/what_doesnt_work.md)*
