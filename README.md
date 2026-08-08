# TPMS Metamaterial Lattices CAD Models

An open‑source collection of high‑resolution Triply Periodic Minimal Surface (TPMS) metamaterial lattices designed for additive manufacturing, mechanical testing, and thermal/fluid transport research.

These CAD models support advanced studies in architected materials, lightweight structures, and multi‑physics simulation.

## 📁 Repository Structure

All CAD files (`.stl`, `.3mf`) are stored in the root directory and organized by topology, relative density, and unit‑cell configuration.

```text
tpms-metamaterial-lattices/
│
├── gyroid30_448x56x56_U28.stl         # Gyroid lattice
├── primitive30_448x56x56_U28.stl      # Schwarz Primitive lattice
├── ...                                # Additional TPMS lattice models
├── .gitignore                         # Excluded macOS & temp system files
└── README.md                          # Repository documentation
```

## 🔤 File Naming Convention

All CAD files follow a standardized parameter schema:

```text
<Topology><Relative Density>_<Bounding Dimensions>_<Unit Cells>.<ext>
```

**Example:** `gyroid30_448x56x56_U28.stl`

- **Topology:** `gyroid` (Gyroid), `primitive` (Schwarz Primitive), `diamond` (Schwarz Diamond)
- **Relative Density:** `30` → 30% volume fraction
- **Bounding Dimensions:** `448 × 56 × 56` mm
- **Unit Cells:** `U28` → 28 unit cells along the longitudinal axis

## 🔬 TPMS Architectures Overview

| Surface Type | Abbreviation | Key Features | Applications |
| :--- | :--- | :--- | :--- |
| **Gyroid** | `gyroid` | High shear strength, continuous fluid channels | Heat exchangers, bone scaffolds, energy absorbers |
| **Schwarz Primitive** | `primitive` | High axial stiffness | Compression testing, lightweight structural cores |
| **Schwarz Diamond** | `diamond` | Isotropic mechanical response | Multi‑axial structural components |

## 🛠️ Usage & Compatibility

### 1. Visualization & Simulation
These models can be directly imported into:
- **CAD & FEA Tools:** FreeCAD, nTop, ANSYS, Abaqus, SolidWorks, Autodesk Fusion 360
- **3D Printing Slicers:** PrusaSlicer, Bambu Studio, Cura, OrcaSlicer

### 2. Downloading Files
Click any `.stl` or `.3mf` file in the repository and select **Download raw file**.

## 🌐 Author & Website

For publications, projects, and collaboration:
- **Website:** [shahadathussain.com](https://shahadathussain.com)
- **GitHub:** [@drshahadathussain](https://github.com/drshahadathussain)

## 📜 License

This repository is released under the MIT License.
You may use, modify, and distribute these models for academic or commercial purposes with attribution.

## 📚 Citation

If you use these CAD models in your research, please cite:

```bibtex
@misc{Hussain_TPMS_Lattices_2026,
  author       = {Shahadat Hussain},
  title        = {TPMS Metamaterial Lattices CAD Models Repository},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub Repository},
  howpublished = {\url{https://github.com/drshahadathussain/tpms-metamaterial-lattices}}
}
```

*Maintained by Dr. Shahadat Hussain ([@drshahadathussain](https://github.com/drshahadathussain)).*
