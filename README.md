<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="img/aelos-logo-gradient-dark-800w.png">
    <img src="img/aelos-logo-gradient-800w.png" alt="AELOS" width="360">
  </picture>
</p>

<h3 align="center">AELOS: AeroElastic LOads Simulator</h3>
<p align="center"><i>Flight simulation with the structure in the loop</i></p>

---

## What is AELOS?

**AELOS** (*AeroElastic LOads Simulator*) is a complete aircraft flight simulator built
around one idea: **the airframe is not rigid, and the aeroelasticity matter.**

It covers everything a flight simulation needs: six-degree-of-freedom flight dynamics,
aerodynamics, propulsion, landing gear, atmosphere, flight control and a real-time cockpit
with a 3D view. At its centre are **structural loads and aeroelasticity**. The flexible
structure, the unsteady aerodynamics and the loads they produce are part of the simulation
from the first time step, not a post-processing step added afterwards.

With AELOS you can:

- **Fly the aircraft in real time** as a rigid or a flexible (elastic) airframe, and see
  how the structure responds to your inputs and to turbulence
- **Monitor internal loads** (shear, bending and torsion along the wing and fuselage)
  live during the flight
- **Study the coupling** between flight mechanics, aerodynamics and structural dynamics
  in one consistent model
- **Run loads analyses**: manoeuvres, discrete gusts, load envelopes and correlated-load
  "potato" plots *(full version)*
- **Investigate aeroelastic stability (flutter)** *(full version)*

AELOS is developed for **research** in aircraft loads, aeroelasticity and
flight dynamics.

---

## Demo version

This repository distributes the **AELOS Demo** for Windows.

| | Demo |
|---|---|
| Platform | Windows 10 / 11, 64-bit |
| Aircraft | Boeing 747-400 (generic model from public data) |
| Airframe | Rigid **or** Elastic |
| Mass case | MTOW |
| Flight condition | Cruise |
| Tools | Real-time cockpit |
| Validity | Each release expires on a fixed date, shown at start-up |

**On launch**, the AELOS splash screen appears, followed by the licence screen on first
start. Then choose **Rigid** or **Elastic** to open the cockpit.

---

## Download

1. Open the [**Releases**](../../releases/latest) page.
2. Download `AELOS-Demo-<version>.exe`.
3. Run it. No installation or Python required.

> Always download AELOS from this page. Every release is signed and carries its own expiry
> date. When a release expires, a new one will be available here.

---

## Licence

AELOS is distributed **as an executable only**, under the
[AELOS Academic & Research Licence](LICENSE.md):

- ✅ Free for **non-commercial research**
- ✅ Colleagues are welcome: each user downloads their own copy from this page
- ✅ You may **publish your results**, citing AELOS (see below)
- ❌ No commercial use, no redistribution, no reverse engineering
- ❌ The source code is **not** part of the licence

**No Commercial version are available**

---

## How to cite

If AELOS contributes to your work, please cite it:

> `D. Pezzella`, *AELOS: AeroElastic LOads Simulator*, version X.Y.Z, 2026.
> Available at: https://github.com/malbrum21/AELOS-releases

```bibtex
@software{aelos,
  author  = {D. Pezzella},
  title   = {{AELOS}: {AeroElastic LOads Simulator}},
  version = {X.Y.Z},
  year    = {2026},
  url     = {https://github.com/malbrum21/AELOS-releases}
}
```

---

## Acknowledgements

The B747-400 structural model is derived from the B747 model by gijsrooy
(https://github.com/gijsrooy/747-400), extended and substantially modified for AELOS.
The aircraft data are engineering estimates from public sources. They are not Boeing data
and do not represent the actual aircraft.

---

## Disclaimer

AELOS is a research tool. Its results are **not** intended for aircraft
certification, design sign-off or operational decisions.

---

## Contact

Questions, feedback or collaborations: `malbrum1986@gmail.com`

<p align="center"><sub>© 2026 &lt;Licensor&gt;. All rights reserved.</sub></p>
