# Section VIII — Relativistic Beam Deflection

*Cameron Unified Framework — Paper Draft*  
*Status: Theoretical prediction. Not yet experimentally tested.*  
*This section presents a falsifiable prediction that distinguishes*  
*the Cameron framework from General Relativity.*

---

## VIII.1 The Experiment

**Setup:** A beam of neutral atoms or neutrons at velocity v = βc
is directed past the Sun with impact parameter b (the distance of
closest approach). The deflection of the beam trajectory from a
straight line is measured. Source and receiver are on opposite sides
of the Sun.

**Why neutral particles:** charged particles are deflected by the
solar magnetic field, solar wind, and radiation pressure — all
confounding effects. Neutral atoms and neutrons have no net electric
charge. Only the gravitational (imaginary sector) coupling acts on
them at long range. This isolates the Cameron velocity-dependent
mass coupling from all other effects.

**The measurement:** compare the observed deflection to the
Newtonian prediction 2GM/(bv²) as a function of β.

---

## VIII.2 The Cameron Deflection Formula

Using the impulse approximation with M_eff = M(1+β²):

The transverse impulse on a particle of mass m at speed v = βc
passing the Sun with impact parameter b:

```
Δp_⊥  =  ∫ F_⊥ dt  =  2G·M_eff·m / (bv)
        =  2GM·m·(1+β²) / (bβc)
```

The deflection angle α = Δp_⊥ / p where p = γmv = γmβc:

```
α_Cameron  =  2GM(1+β²)√(1−β²) / (bc²β²)               (VIII.1)
```

For comparison, General Relativity (PPN with γ_PPN = 1):

```
α_GR  =  (2GM/bc²) · (1+β²)/β²                          (VIII.2)
```

The difference is the factor √(1−β²) = 1/γ in the Cameron formula.
This factor arises because the Cameron framework divides by the full
relativistic momentum p = γmβc, while the GR formula does not have
the same momentum suppression for massive particles.

---

## VIII.3 Predicted Deflection — Grazing the Sun (b = R_sun)

| β = v/c | Newton (arcsec) | GR (arcsec) | Cameron (arcsec) | Cameron/GR |
|---|---|---|---|---|
| 0.10 | 87.59 | 88.46 | 88.02 | 0.995 |
| 0.20 | 21.90 | 22.77 | 21.95 | 0.964 |
| 0.30 | 9.73 | 10.61 | 10.12 | 0.954 |
| 0.50 | 3.50 | 4.38 | 3.79 | 0.866 |
| 0.70 | 1.79 | 2.66 | 1.90 | 0.714 |
| **0.786** | **1.42** | **2.29** | **1.42** | **0.618** |
| 0.90 | 1.08 | 1.96 | 0.85 | 0.436 |
| 0.95 | 0.97 | 1.85 | 0.58 | 0.313 |
| 0.99 | 0.89 | 1.77 | **0.25** | 0.141 |
| 0.999 | 0.88 | 1.75 | 0.08 | 0.045 |
| 1.000 (massive→c) | ∞ | **1.752** | **0.000** | 0 |
| **photon** | ∞ | **1.752** | **1.752** | **1.000** |

Eddington value (photon, grazing Sun): **1.752 arcseconds**

---

## VIII.4 Three Distinguishing Features

### Feature 1 — The Crossover at β = 0.786

At β ≈ 0.786 the Cameron deflection equals the Newtonian deflection.
The crossover occurs when:

```
(1+β²)√(1−β²)  =  1                                      (VIII.3)
```

which has the numerical solution β ≈ 0.7862.

At this velocity:
- Cameron: 1.42 arcseconds
- GR: 2.29 arcseconds
- Newton: 1.42 arcseconds

GR predicts 61% more deflection than the Cameron framework at this
specific velocity. This is detectable without requiring precision
near the speed of light.

Above β = 0.786: **Cameron predicts less deflection than even Newton.**

### Feature 2 — Decreasing Deflection at High Velocity

For β > 0.786, increasing the particle velocity *decreases* the
Cameron deflection. The factor √(1−β²) = 1/γ in the numerator
of equation (VIII.1) falls faster than the coupling (1+β²) rises.

At β = 0.99: Cameron gives 0.25 arcseconds vs GR's 1.77 arcseconds
— a factor of **seven** difference.

**Physical reason:** the relativistic momentum p = γmβc grows
without bound as β → 1. The transverse impulse Δp_⊥ is finite
(the particle passes the Sun in finite time). So α = Δp_⊥/p → 0.
The particle has too much inertia to be deflected — the infinite
forward pressure of the cosmic boundary asymmetry manifests as
infinite resistance to transverse acceleration.

### Feature 3 — The Hard Discontinuity at v = c

For massive particles as β → 1: α_Cameron → 0.
For massless photons (β = 1): α_Cameron = 1.752 arcseconds (Eddington).

This is a hard discontinuity in the Cameron framework.

For massive particles: p = γmv → ∞ as β → 1. Deflection → 0.
For photons: p = E/c (finite). Full Eddington deflection.

**GR predicts no such discontinuity.** In GR the deflection of
massive particles approaches the Eddington value smoothly as β → 1.

The physical origin of the discontinuity in the Cameron framework:
massive particles always have P_im = mc ≠ 0 — a nonzero imaginary
tether that keeps them off the null geodesic. A photon exists exactly
on the null geodesic (d² = 0) where both sectors have equal weight.
These are categorically different situations. As a massive particle
approaches v = c it gets arbitrarily close to the null geodesic but
never reaches it. Its coupling to the imaginary sector approaches 2M
(the photon value) but its momentum simultaneously approaches infinity.
The deflection angle — the ratio of transverse impulse to total
momentum — goes to zero.

A photon, having no rest mass, sits permanently on the null geodesic.
It couples to both sectors simultaneously by geometry, not velocity.
The deflection is the full Eddington value.

**This is the sharpest quantitative distinction between the Cameron
framework and General Relativity.**

---

## VIII.5 The Connection to the Perihelion Advance

The M_eff coupling M(1+β²) appears in both the perihelion advance
(Section VII) and the beam deflection (this section). They are the
same physical mechanism in two different dynamical regimes:

**Perihelion advance (slow orbital motion, β ~ 10⁻⁴):**
The coupling integrates over many orbits. The effect accumulates
to 14.33 arcsec/century despite the tiny v²/c² per orbit.

**Beam deflection (single pass, β from 0.1 to 0.99):**
The coupling acts once. But the momentum denominator grows as γ
and cancels the coupling for massive particles near β = 1.

The same equation (VII.1) gives:
- A tiny but measurable effect for slowly orbiting planets
- A qualitatively different behaviour for relativistic beams
- The exact Eddington factor for photons

One equation. Three regimes. All three are consequences of the
geometry of the PMV rotation angle θ and the null geodesic.

---

## VIII.6 Experimental Feasibility

**Current status:** relativistic neutral beams at the required
intensities and precisions are not currently available. This is a
theoretical prediction, not a confirmed result.

**What would be needed:**

At β = 0.5, Cameron and GR differ by 13% (3.79 vs 4.38 arcsec
grazing the Sun). This is in principle detectable with precision
astrometry if a sufficiently intense neutral beam could be produced.

At β = 0.9, the difference is a factor of 2.3 (0.85 vs 1.96 arcsec).
This is qualitative — Cameron predicts less than half the GR value.

At β = 0.99, the difference is a factor of 7 (0.25 vs 1.77 arcsec).
This does not require exquisite precision — it only requires
determining whether the deflection is closer to 0.25 or to 1.77.

**The practical limit:** relativistic heavy ion beams at CERN reach
β ≈ 0.9999 but these are charged nuclei, not neutral particles.
Neutral atom beams at relativistic speeds require new technology.
A more practical near-term test might use a very massive gravitating
body (neutron star) at known distance with a long-baseline detector.

**What makes the experiment worth pursuing:** at β = 0.9 the
Cameron and GR predictions differ by a factor of two. Either
deflection increases toward the Eddington limit as β increases (GR)
or deflection decreases toward zero (Cameron). An experiment capable
of measuring at β = 0.9 with 20% precision would distinguish the
two frameworks definitively. This is not a percent-level precision
measurement — it is a qualitative test.

---

## VIII.7 The Cosmic Boundary Asymmetry

The decreasing deflection at high velocity is related to a broader
physical effect — the asymmetry of the cosmic boundary conditions
as seen by a rapidly moving particle.

As β → 1, the forward hemisphere of the universe appears blueshifted
and increasingly dense in the particle's frame. The backward
hemisphere appears redshifted and increasingly sparse.

```
T_forward  =  T₀ · √((1+β)/(1-β))
T_backward =  T₀ · √((1-β)/(1+β))
```

At β = 0.99: T_forward = 38 K (CMB at rest: 2.725 K)
At β = 0.9999: T_forward = 385 K (above water boiling point)

This growing asymmetry of the cosmic boundary conditions IS the
physical mechanism behind the infinite resistance to further
acceleration as β → 1. The universe is literally pressing back.

The deflection going to zero for massive particles near β = 1 is
the same mechanism expressed in the transverse direction — the
particle cannot be deflected because the forward momentum has grown
to the point where any transverse impulse is negligible relative to
the total momentum.

This has implications for interstellar travel: the practical
engineering limit for neutral beam propagation through the solar
gravitational field is not a precision issue but a fundamental one.
Above β ≈ 0.786 the beam deflects LESS than Newton predicts — an
initially counterintuitive result that follows directly from the
Cameron momentum suppression.

---

## VIII.8 Summary

| Quantity | GR prediction | Cameron prediction |
|---|---|---|
| Deflection at β = 0.1 | 88.46 arcsec | 88.02 arcsec |
| Deflection at β = 0.5 | 4.38 arcsec | 3.79 arcsec |
| Crossover with Newton | does not occur | β = 0.786 |
| Deflection at β = 0.9 | 1.96 arcsec | 0.85 arcsec |
| Deflection at β = 0.99 | 1.77 arcsec | **0.25 arcsec** |
| Transition at v → c | smooth → Eddington | → **0** then jumps |
| Photon deflection | 1.752 arcsec | 1.752 arcsec ✓ |

The Cameron framework agrees with GR at low velocities (β < 0.3)
where the precision of current gravitational measurements is
concentrated. The frameworks diverge dramatically at high velocities
where no precision measurements currently exist.

**The beam deflection experiment is the cleanest available test
that distinguishes the Cameron framework from General Relativity.**

---

*Previous: [Section VII — Perihelion Advance of Mercury](section_VII_perihelion_advance.md)*  
*Next: [Section IX — Things to Contemplate and Refine](section_IX_contemplate.md)*  
*Return to: [README](../README.md)*  
*Figure: [relativistic_beam_deflection.png](../figures/relativistic_beam_deflection.png)*

---

*This section presents a theoretical prediction derived in 2025.*  
*The prediction has not yet been experimentally tested.*  
*It is falsifiable by relativistic neutral beam experiments.*  
*Open questions in [disputes/what_doesnt_work.md](../disputes/what_doesnt_work.md)*
