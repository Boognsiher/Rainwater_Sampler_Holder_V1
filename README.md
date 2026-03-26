# Rainwater_Sampler_Holder_V1

A 3D-printable holder for automatic rainwater collection. The mount clamps a standard funnel at the top and holds a laboratory vial underneath to collect the water. An integrated millimetre scale (10–60 mm) is visible through a viewing window on the side.

![Rainwater Funnel Holder](./preview.png)
<!-- Replace preview.png with your own screenshot -->

---

## Repository Contents

| File | Description |
|---|---|
| `Rainwater_Sampler_Holder_V1.f3d` | Fusion 360 source file (full parameter history) |
| `Rainwater_Sampler_Holder_V1.step` | STEP export for all other CAD programs |
| `README.md` | This file (English) |
| `README_DE.md` | German version |

---

## Components (38 Bodies)

### Right side
| Body | Group | Description |
|---|---|---|
| Body21 | – | Right half of the holder |
| Body3–20 | TextR (18 bodies) | Scale markings right side – one character per body |

### Left side
| Body | Group | Description |
|---|---|---|
| Body2 | – | Left half of the holder |
| Body22–39 | TextL (18 bodies) | Scale markings left side – one character per body |

### Cap
| Body | Description |
|---|---|
| Body1 | Cap for the sample vial |

> **Note on scale markings:** The scale characters (TextR / TextL) are modelled as individual bodies – each body represents a single character (e.g. "0", "1", "2", "-" etc.). Printing them in a contrast colour requires an **AMS, MMU, or similar multi-material system**. Manual filament swaps per character are technically possible but very tedious.

---

## Bill of Materials

### Sample vial
- **VWR Screw-Thread Vial ND18**
- 🔗 [vwr.com – EU7061890](https://www.vwr.com/ch/de/product/EU7061890/vwr-gewindeflschchennd18)

### Funnel
- Standard funnel with a neck diameter of **16–18 mm**

### Screws & Nuts

| Qty | Part | Note |
|---|---|---|
| 5× | M3 or M4 × 25 mm + nut | M4 recommended – tighter fit |
| 2× | M3 or M4 × 15 mm + nut | M4 recommended – tighter fit |
| 1× | M5 × 35 mm + nut | – |

### Other Hardware

| Qty | Part | Description |
|---|---|---|
| 1× | Elastic band | 3–5 mm diameter |
| 2× | Hose clamp or cable tie | For mounting the holder |

---

## 3D Print Files

Print-ready files (STL / 3MF) with print settings are available on MakerWorld:

> 🔗 **MakerWorld:** [Rainwater_Sampler_Holder_V1](https://makerworld.com/de/models/2576738-rainwater_sampler_holder_v1#profileId-2841437)

---

## Technical Details

| Parameter | Value |
|---|---|
| Units | mm |
| Scale range | 10–60 mm |
| Designed in | Autodesk Fusion 360 |
| CAD formats | `.f3d` (native), `.step` (universal) |
| Coordinate origin | Bottom face of holder base |

---

## Using the CAD Files

### With Fusion 360
Open the `.f3d` file directly – the full parameter tree and model history are preserved.

### With other CAD programs
*(SolidWorks, FreeCAD, Rhino, CATIA, Creo etc.)*
Import the `.step` file. Geometry and assembly structure are fully intact. Model history and parameters are not transferred.

---

## License

This project is licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

- ✅ Free to use, modify and share
- ✅ Credit to the original creator required
- ❌ Commercial use not permitted

🔗 [License details](https://creativecommons.org/licenses/by-nc/4.0/)

---

## Contact & Contributing

**Created by:** Roman Thurnherr  
**Questions & suggestions:** feel free to open a GitHub Issue or Pull Request

---

*Last updated: March 2026*
