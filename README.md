# Cools Vertical Electro-Opto-Thermal Interconnect

[한국어](README_KR.md) | [中文](README_ZH.md) | [Patent Portfolio](PATENT_PORTFOLIO.md) | [Public Notice](PUBLIC_NOTICE.md)

## Data, power, and heat no longer compete for planar area.

Cools proposes a semiconductor-package architecture in which a transparent single-crystal handler is positioned between upper and lower semiconductor devices and used simultaneously for:

1. **vertical optical data transmission,**
2. **vertical electrical power delivery,** and
3. **vertical heat extraction.**

The same crystalline handler becomes the optical medium, the electrical insulation body around power vias, the thermal conduction body, and—where appropriate—the epitaxial growth substrate for a monolithically integrated III-V light source.

---

## 1. The planar-resource bottleneck

Conventional packages route data, power, and heat mainly through planar wiring or a single backside direction.

```text
Data  → Cu/RDL/interposer routing in the package plane
Power → TSV + planar power distribution
Heat  → one-sided backside TIM and heat sink
```

As bandwidth and power density increase, these three functions compete for the same package area.

The Cools architecture rotates all three functions into the thickness direction.

```text
Upper device
     │
     │  optical path
     │  power via
     │  thermal path / cooling channel
     ▼
Transparent single-crystal handler
     ▼
Lower device
```

---

## 2. One crystalline handler, four material functions

The handler is selected to combine four properties in one body:

- optical transparency at the operating wavelength,
- high electrical resistivity,
- substantially higher thermal conductivity than conventional package dielectrics, and
- compatibility with epitaxial growth of a III-V light-emitting structure.

Single-crystal sapphire is a principal embodiment because it combines broad optical transparency, electrical insulation, useful thermal conduction, mechanical strength, and established GaN epitaxy.

Other candidate single-crystal materials may include aluminum nitride, silicon carbide, or gallium oxide where their optical, electrical, thermal, and process properties match the application.

---

## 3. Vertical optical path

An optical transmitter and detector are placed on opposite sides of the handler.

The optical signal can propagate through the handler by:

- free-space transmission through the transparent crystal,
- an ion-implanted refractive-index-modulated core,
- a heterogeneous thin-film waveguide,
- a micro-lens-assisted path, or
- combinations of these structures.

The architecture is compatible with spatial parallelism and wavelength-division multiplexing.

### Light-source branches

1. **Monolithic GaN/InGaN micro-LED array** grown directly on a sapphire handler.
2. **Optical modulator** driven by an external continuous-wave source.
3. **Bonded laser diode** for high-speed or wavelength-specific operation.

The source, path, and detector architecture can be selected independently for the bandwidth, power, wavelength, and alignment requirements of the package.

---

## 4. Vertical power delivery

Because the handler body is electrically insulating, a conductive via can pass through the crystal without requiring the same via-liner architecture used in a semiconductor interposer.

The power-via region is spatially separated from the optical-input/output region. This enables high vertical current density without blocking the optical path.

The via network may provide:

- power delivery between stacked logic and memory,
- ground return,
- bias supply for optical transmitters and detectors,
- local power-domain segmentation, and
- short vertical paths with reduced planar routing demand.

---

## 5. Vertical thermal path

The handler body itself conducts heat between the stacked devices and the external cooling boundary.

Thermal extraction can be strengthened through:

- direct solid conduction through the crystal,
- local thermal-spreading regions,
- microchannels formed in the handler,
- active coolant flow,
- thermal vias or conductive inserts located outside the optical region, and
- two-sided cooling configurations.

The optical, electrical, and cooling regions are divided in the handler plane while all extend in the thickness direction.

---

## 6. Region-separated 3-in-1 architecture

```text
Handler plane
┌───────────────────────────────────────────────┐
│ Optical I/O │ Power-via region │ Cooling zone │
└───────────────────────────────────────────────┘
       │               │               │
       ▼               ▼               ▼
 vertical light   vertical current   vertical heat
```

This spatial separation prevents:

- optical blockage by conductive vias,
- optical scattering from coolant or bubbles,
- unwanted electromagnetic interaction between current and optical paths, and
- thermal-channel placement from consuming optical-channel area.

---

## 7. Representative package applications

### GPU–HBM vertical optical interconnect

A logic accelerator or GPU can be connected to an HBM stack through massively parallel vertical optical channels, while the same handler supplies vertical power and removes heat.

### Logic-to-logic and chiplet stacks

The platform can connect logic dies, neural-processing dies, chiplets, sensors, and optical engines across a stacked architecture.

### Optical memory and accelerator fabrics

Spatially parallel optical channels can raise areal bandwidth without requiring a proportional increase in micro-bump count or planar copper routing.

### Multi-wavelength package links

The transparent single-crystal body supports wavelength selection across visible, near-infrared, and—in suitable materials and designs—mid-infrared bands.

---

## 8. Why the handler is not an ordinary interposer

| Function | Conventional interposer | Cools transparent single-crystal handler |
|---|---|---|
| Data routing | Primarily planar electrical routing | Vertical optical transmission |
| Power delivery | TSV plus planar redistribution | Vertical conductive vias in insulating body |
| Heat extraction | Separate backside thermal stack | Handler body and embedded cooling path |
| Light-source integration | Typically separately bonded | Monolithic epitaxial source possible |
| Shared planar-area demand | High | Reduced through thickness-direction separation |

---

## 9. Patent architecture

The protected platform includes:

- transparent single-crystal handler between semiconductor devices,
- vertical optical signal transmission through the handler,
- vertical power vias through the electrically insulating body,
- vertical solid or fluidic heat-removal paths,
- planar region separation among optical, electrical, and thermal zones,
- monolithic, modulated, or bonded light-source variants,
- free-space, implanted-core, and thin-film-waveguide variants,
- spatial and wavelength multiplexing, and
- manufacturing sequences for forming the integrated package.

See [PATENT_PORTFOLIO.md](PATENT_PORTFOLIO.md) for the detailed rights structure.

---

## 10. Related Cools platforms

- [Cools Package-Substrate-Less SystemBoard](https://github.com/jhcho9494/Cools_Package_Substrate_Less_SystemBoard)
- [Cools Thermally Active Photonic Substrate](https://github.com/jhcho9494/Cools_Thermally_Active_Photonic_Substrate)
- [Cools Thin-Film III-V on SiC Platform](https://github.com/jhcho9494/Cools_ThinFilm_III-V_on_SiC_Platform)
- [Cools Sapphire Quantum Optical Interconnect](https://github.com/jhcho9494/Cools_Sapphire_Quantum_Optical_Interconnect)

---

## Collaboration

Cools is open to evaluation and joint-development discussions with AI-accelerator companies, memory companies, photonics companies, package manufacturers, substrate suppliers, optical-component companies, and research institutions.

**Cools — Jinhyun Cho**
