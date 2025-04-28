# Izod Impact Tester Project

## Project Files

- **Izod Impact Tester SolidWorks Files**  
  This folder contains the SolidWorks part files (`.SLDPRT`) for all 3D-printed components of the Izod Impact Tester.

- **Izod Impact Tester STL Files**  
  This folder contains the STL files (`.stl`) for each 3D-printed component, ready for slicing and printing.

---

# Impact Tester Operation Instructions

## Setup for Windage Measurement

1. Lift the hammer to the upright (90°) position.
2. Pull and hold the release button until the pawl engages the gear and secures the hammer.
3. Reset the read-out needle, if needed:
   - Adjust the white needle to the lowest position on the read-out plate.
4. Firmly press the release button and record the windage measurement.

## Testing Samples

1. Load the sample into the tester:
   - Place the sample in the vise with the notch facing the hammer.
   - Tighten the vise just enough to hold the sample; **do not overtighten**.
2. Lift the hammer back to the upright (90°) position.
3. Pull and hold the release button until the pawl secures the hammer.
4. Reset the read-out needle, if needed:
   - Adjust the white needle to the lowest position.
5. Firmly press the release button and record the energy drop caused by the sample.

Repeat steps 1–5 for each additional sample.

## After Testing

- Leave the hammer in the lowered position.
- Reset the read-out needle.

---

# General Equation for Impact Energy Calculation

The potential energy (PE) of the hammer at an angle \(\theta\) is:

\[
PE = mgL(1 - \cos\theta)
\]

where:
- \( m \) = mass of the hammer (kg)
- \( g \) = acceleration due to gravity (9.81 m/s²)
- \( L \) = distance from pivot to hammer center of mass (m)
- \( \theta \) = hammer angle from vertical (in radians)

---

The impact energy absorbed by the sample is:

\[
E_{\text{impact}} = mgL(\cos\theta_{\text{after}} - \cos\theta_{\text{before}})
\]

where:
- \( \theta_{\text{before}} \) = initial hammer angle (typically 90°)
- \( \theta_{\text{after}} \) = hammer angle after striking the sample

---
