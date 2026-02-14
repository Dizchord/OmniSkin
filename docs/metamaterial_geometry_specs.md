# Metamaterial Geometry Specifications

## 1. Overview
This document defines the geometric parameters and fabrication requirements for the magneto-optic metasurface lattice. The precise nanostructure is critical for achieving the desired retroreflective and photonic computing capabilities.

## 2. Lattice Geometry
The structure is based on a **periodic triangular lattice** or **nanodisk array** designed to maximize light-matter interaction and enable retroreflection.

### Core Parameters
*   **Lattice Period ($P$)**: 1.0 $\mu$m (optimized for near-infrared operation, e.g., 1550 nm).
*   **Meta-Atom Element**: Nanodisks or triangular prisms.
*   **Element Height ($H$)**: 1.3 $\mu$m (aspect ratio > 1 for strong phase accumulation).
*   **Element Diameter ($D$)**: Variable, ranging from 50 nm to 900 nm depending on the desired phase gradient and local function.
    *   **Phase Gradient**: By varying D across the unit cell, a full 0 to 2$\pi$ phase shift can be achieved.

## 3. Retroreflective Features
*   **Topology**: Corner-cube-like micro-facets or diffractive gratings integrated into the lattice.
*   **Material Interface**: High-index contrast between the magneto-optic material (BIG/Ce:YIG) and the surrounding medium (Air/$\text{SiO}_2$ cladding).

## 4. Fabrication Process
Based on wafer-scale techniques (e.g., MetaLitho3D):
1.  **Substrate Preparation**: High-purity Fused Silica or Silicon wafer.
2.  **Material Deposition**: Sputtering or PLD of Bismuth-substituted Yttrium Iron Garnet (BIG) thin film.
3.  **Lithography**: High-resolution electron-beam or multi-photon lithography to define the nanodisk pattern.
4.  **Etching**: Reactive Ion Etching (RIE) to carve the pillars/disks.
5.  **Annealing**: High-temperature annealing (referenced for crystallization of garnet films) to active magneto-optic properties.

## 5. Topological Protection (Advanced)
For applications requiring robust signal transmission:
*   **Gyromagnetic Double-Zero-Index (GDZIM)** configuration.
*   **Zero Permittivity condition** ($\epsilon \approx 0$) achieved at specific frequencies.
