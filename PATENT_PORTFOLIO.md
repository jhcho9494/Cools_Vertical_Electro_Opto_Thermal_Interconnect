# Patent Portfolio — Vertical Electro-Opto-Thermal Interconnect

## 1. Portfolio thesis

The portfolio protects a semiconductor-package architecture in which a transparent single-crystal handler between upper and lower semiconductor devices simultaneously performs three vertical functions:

1. optical data transmission,
2. electrical power delivery, and
3. heat removal.

The central rights position is not limited to a particular transmitter, detector, wavelength, or device pair. It is the use of one crystalline handler as a shared **electrical–optical–thermal vertical infrastructure**.

---

## 2. Core structural claim axis

### Transparent single-crystal handler

The handler is positioned between two semiconductor devices and provides, in a single body:

- optical transparency at an operating wavelength,
- electrical insulation around conductive vias,
- useful through-thickness thermal conduction, and
- optional epitaxial-substrate compatibility for an integrated light source.

A principal material embodiment is single-crystal sapphire. Additional embodiments may use single-crystal AlN, SiC, Ga₂O₃, or another material satisfying the required optical, electrical, thermal, and process functions.

---

## 3. Vertical optical-transmission axis

Protected optical-path branches include:

- free-space propagation through the crystalline body,
- ion-implanted refractive-index-modulated cores,
- heterogeneous thin-film waveguides,
- micro-lens-assisted vertical coupling,
- spatially parallel channel arrays,
- wavelength-division multiplexing, and
- combinations of these structures.

The source and detector can be located on opposite faces of the handler or connected through intermediate optical structures.

---

## 4. Light-source integration axis

### Branch A — Monolithic epitaxial source

A III-V light-emitting structure, including a GaN/InGaN micro-LED array, is directly grown on a compatible crystalline handler surface.

**Strategic effect:** removal of separate source-die bonding and reduction of alignment error.

### Branch B — Modulator plus external continuous-wave source

An optical modulator on or adjacent to the handler modulates light supplied by an external CW source.

**Strategic effect:** high per-channel bandwidth and separation of laser thermal management from the stacked package.

### Branch C — Bonded laser diode

A separately fabricated laser diode is bonded to the package and aligned to the vertical optical path.

**Strategic effect:** wavelength and source-technology flexibility.

---

## 5. Vertical power-delivery axis

Conductive vias pass through the electrically insulating single-crystal body to provide short vertical power paths.

Protected functions include:

- power delivery between stacked devices,
- ground return,
- local bias supply,
- segmented power domains,
- optical-transmitter and detector biasing, and
- reduced reliance on planar power redistribution.

The insulating body can reduce or remove the need for a semiconductor-interposer-style dielectric liner around each via, depending on the selected material and implementation.

---

## 6. Vertical thermal-management axis

The handler provides a through-thickness thermal path by one or more of:

- solid conduction through the crystal,
- local heat-spreading regions,
- integrated microchannels,
- active coolant flow,
- thermal vias or conductive inserts,
- one-sided or two-sided heat rejection.

The thermal path is not merely an external heat sink attached to the package. It is integrated into the same intermediate body that carries the optical and electrical functions.

---

## 7. Planar region-separation axis

The handler plane is divided into functionally distinct regions:

- optical-input/output regions,
- power-via regions, and
- vertical cooling or heat-conduction regions.

Each region extends through the handler thickness, but their planar separation prevents mutual interference.

**Protected outcomes include:**

- optical paths not blocked by conductive vias,
- coolant flow not disturbing the optical channel,
- reduced electromagnetic interaction between power and optical paths,
- independent scaling of optical-channel density, current density, and cooling capacity.

---

## 8. Device-stack and application axis

Representative protected package configurations include:

- GPU or AI accelerator to HBM stack,
- logic-to-logic stack,
- processor-to-chiplet stack,
- memory-to-memory or memory-to-logic stack,
- sensor and optical-engine integration,
- NPU and accelerator fabrics,
- visible, near-infrared, and compatible mid-infrared links.

The architecture is orientation-independent: upper and lower devices may exchange positions, and the handler can be used in inverted or lateral package orientations.

---

## 9. Manufacturing axis

The manufacturing family can include:

1. preparation and double-side polishing of the transparent single-crystal handler,
2. definition of optical, via, and cooling regions,
3. formation of conductive through-vias,
4. formation of free-space, implanted-core, or thin-film optical paths,
5. formation or integration of the light source and detector,
6. formation of microchannels or thermal structures,
7. bonding of upper and lower semiconductor devices, and
8. optical, electrical, and thermal alignment and packaging.

---

## 10. Rights matrix

| Axis | Core embodiment | Major alternatives |
|---|---|---|
| Handler | Single-crystal sapphire | AlN, SiC, Ga₂O₃, other transparent insulating crystals |
| Optical path | Free-space vertical propagation | Implanted core, thin-film guide, micro-lens |
| Source | Monolithic micro-LED | External-CW modulator, bonded laser |
| Power | Conductive vertical via | Segmented via network, local bias/ground domains |
| Heat | Crystal-body conduction | Microchannel, coolant flow, thermal inserts |
| Multiplexing | Spatial parallel channels | WDM, spatial + WDM combination |
| Device pair | GPU–HBM | Logic–logic, chiplet, NPU, sensor, optical engine |

---

## 11. Combined system embodiment

```text
HBM stack or upper chiplet
        │
        ├── optical channel array
        ├── vertical power-via array
        └── vertical heat/cooling zones
        │
transparent single-crystal handler
        │
GPU / AI accelerator / lower logic die
```

The combined embodiment protects the simultaneous use of the handler for areal bandwidth, current delivery, and heat extraction rather than treating these as unrelated package subsystems.

---

## 12. Relationship to other Cools IP

- **Package-Substrate-Less SystemBoard:** system-level removal or absorption of package-substrate functions.
- **Thermally Active Photonic Substrate:** optical substrate in which buried insulation and thermal pathways are co-designed.
- **Thin-Film III-V on SiC:** active optical thin films transferred onto a thermal support.
- **Sapphire optical and quantum platforms:** use of sapphire as a single optical-domain and quantum-compatible integration medium.

The vertical electro-opto-thermal interconnect is the package-level bridge connecting these substrate and active-device platforms.

---

## 13. Disclosure scope

This document presents the public patent architecture only. Detailed claim sets, optical-alignment tolerances, via metallurgy, crystal-surface processing, microchannel design, coupling structures, reliability methods, and partner-specific manufacturing know-how may remain unpublished and confidential.
