# User Guide: Metamaterial Photonic Sensor

## 1. Installation
The sensor is supplied as a wafer-scale metasurface or a flexible "skin" (if transferred to a polymer substrate).

### Mounting
*   **Secure Attachment**: Use optical adhesive to bond the sensor surface to the target object (e.g., antenna, PCB, satellite chassis).
*   **Alignment**: Ensure the lattice axis is aligned with the expected polarization axis of the probe light if using linear polarization.

## 2. Operation
### Setup
1.  **Illumination Source**: Calibrated coherent light source (Laser, typically 1550nm for BIG-based sensors).
2.  **Beam Expansion**: Expand the beam to cover the area of interest on the sensor.
3.  **Polarizer**: Place a high-quality linear polarizer in the input path.
4.  **Analyzer**: Place a second polarizer (analyzer) or a Stokes polarimeter in the return path.

### Sensing Procedure
1.  **Baseline Calibration**: Illuminate the sensor in a zero-field environment to establish the optical baseline.
2.  **Field Exposure**: Activate the EM source (the object being measured).
3.  **Data Capture**: Record the intensity/polarization pattern of the reflected light.
    *   **Visualization**: The output pattern directly maps the magnetic field distribution.
    *   **Computation**: The interference fringes represent the processed analog signal (e.g., gradient or transform).

## 3. Data Interpretation
*   **Intensity Variations**: Indicate local magnetic field strength ($I \propto \sin^2(\theta)$, where $\theta \propto B$).
*   **Fringe Shifts**: Indicate phase changes due to field gradients.
*   **Vortex Patterns**: In GDZIM configurations, indicate topological field features.

## 4. Maintenance
*   **Cleaning**: Use standard optical cleaning protocols (dry air, optical wipes with methanol). Avoid abrasive contact.
*   **Environmental Limits**: Operate within the thermal limits of the substrate and adhesive. Garnet materials have a high Curie temperature but packaging may be limiting.
