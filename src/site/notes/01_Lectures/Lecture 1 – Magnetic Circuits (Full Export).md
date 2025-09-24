---
{"dg-publish":true,"permalink":"/01-lectures/lecture-1-magnetic-circuits-full-export/","tags":["#Definition"]}
---


# Lecture 1 – Magnetic Circuits (Full Export)

---

## 1. Introduction to Machines & Transformers
- **Definition (Machine):** A machine is a device that converts energy from one form to another, usually electrical ↔ mechanical. #Definition
- **Definition (Transformer):** A transformer is a static electrical machine that transfers power from one circuit to another using electromagnetic induction, without a change in frequency. #Definition  
- **Key Point:** Machines are **dynamic** (rotating) → generators & motors. Transformers are **static**.

---

## 2. Electromagnetism Basics

### 2.1 Oersted’s Experiment
- **Definition:** A current-carrying conductor produces a magnetic field around it, discovered by Hans Christian Oersted. #Definition  
- **Formula (Qualitative):** $$B \propto I$$ (for fixed distance from conductor).  
- **Diagram Note:** Concentric circles around a conductor, direction given by right-hand rule.

### 2.2 Right-Hand Rule
- **Definition:** If the right hand grips a current-carrying conductor with the thumb pointing in the direction of current, the fingers curl in the direction of the magnetic field. #Definition  

### 2.3 Motor Action
- **Definition:** A current-carrying conductor placed in a magnetic field experiences a force. #Definition  
- **Formula:**  
  $$F = B \cdot I \cdot l \cdot \sin \theta$$  
- **Units:**  
  - \(F\): Newton (N)  
  - \(B\): Tesla (T = Wb/m²)  
  - \(I\): Ampere (A)  
  - \(l\): metre (m)  
- **Diagram Note:** Conductor in magnetic field, force shown by Fleming’s left-hand rule.  
- 🔗 Linked Concepts: [[06_Fundamentals/Force on a Conductor\|Force on a Conductor]], [[06_Fundamentals/Torque Basics\|Torque Basics]], [[06_Fundamentals/Electromagnetism\|Electromagnetism]]

### 2.4 Generator Action
- **Definition:** An emf is induced in a conductor when it moves through a magnetic field, cutting magnetic flux lines. #Definition  
- **Formula:**  
  $$e = B \cdot l \cdot v \cdot \sin \theta$$  
- **Units:** Volts (V).  
- **Diagram Note:** Conductor moving across field lines, induced emf polarity shown by Fleming’s right-hand rule.  
- 🔗 Linked Concepts: [[06_Fundamentals/Faraday’s Law\|Faraday’s Law]], [[06_Fundamentals/Energy Conversion\|Energy Conversion]]

### 2.5 Historical Notes
- First motor: **Barlow’s wheel**.  
- First DC generator: rotating wire in magnetic field.  
- **Exam Pitfall:** Don’t confuse motor vs generator action → they are duals.

---

## 3. Magnetic Circuits (Intro)

### 3.1 [[06_Fundamentals/Magnetic Flux\|Magnetic Flux]]
- **Definition:** The total magnetic field passing through a given area. #Definition  
- **Formula:**  
  $$\Phi = B \cdot A$$  
- **Units:** Weber (Wb).  

### 3.2 [[06_Fundamentals/Magnetomotive Force (MMF)\|Magnetomotive Force (MMF)]]
- **Definition:** The force that establishes magnetic flux in a magnetic circuit, equal to product of coil turns and current. #Definition  
- **Formula:**  
  $$F = N \cdot I$$  
- **Units:** Ampere-turns (At).  

### 3.3 [[06_Fundamentals/Reluctance\|Reluctance]]
- **Definition:** The opposition offered by a magnetic material to the establishment of magnetic flux. #Definition  
- **Formula:**  
  $$\mathcal{R} = \frac{l}{\mu \cdot A}$$  
- **Units:** At/Wb.  

### 3.4 Analogy with Electric Circuit
| Electrical Circuit | Magnetic Circuit |
|--------------------|------------------|
| Voltage (V)        | MMF (F)          |
| Current (I)        | Flux (Φ)         |
| Resistance (R)     | Reluctance (ℜ)   |

**Note:** Useful for problem solving, but only approximate (magnetic circuits are nonlinear).

---

## 4. [[06_Fundamentals/Hysteresis\|Hysteresis]] (Intro)
- **Definition:** The lag of magnetic flux density (B) behind magnetizing force (H) when a ferromagnetic material is magnetized through a cycle. #Definition  
- **Key Terms:**  
  - *Remanence (Br):* Residual flux density when H=0. #Definition  
  - *Coercivity (Hc):* Reverse magnetizing force needed to bring flux density to zero. #Definition  
- **Loss:** Energy lost in one cycle = area of hysteresis loop.  
- **Diagram Note:** Full B–H loop showing Br and Hc.  

---

## 5. Measurement & [[06_Fundamentals/SI Units in Magnetism\|SI Units in Magnetism]]
- **Flux (Φ):** Unit = Weber (Wb). #Definition  
- **Flux Density (B):** Unit = Tesla (T = Wb/m²). #Definition  
- **Magnetic Field Intensity (H):** Unit = Ampere per metre (A/m). #Definition  
- **Magnetomotive Force (F):** Unit = Ampere-turns (At). #Definition  
- **Reluctance (ℜ):** Unit = At/Wb. #Definition  

⚠️ **Exam Pitfall:** Don’t confuse Weber (Wb) with Tesla (T).  
- Example: *Gimli Glider* accident → fuel unit conversion error → included as real-world caution.

---

## 6. Magnetic Field Intensity (H)

- **Definition:** Magnetic field intensity (H) is the magnetizing force that sets up magnetic flux in a material. It represents the magnetizing ampere-turns per unit length. #Definition  
- **Formula:**  
  $$H = \frac{F}{l} = \frac{N \cdot I}{l}$$  
- **Units:** Ampere per metre (A/m).  
- 🔗 See: [[06_Fundamentals/Magnetomotive Force (MMF)\|Magnetomotive Force (MMF)]], [[06_Fundamentals/Reluctance\|Reluctance]]

---

## 7. Magnetic Flux Density (B)

- **Definition:** Magnetic flux density (B) is the amount of magnetic flux passing through a unit area placed normal to the flux. #Definition  
- **Formula:**  
  $$B = \frac{\Phi}{A}$$  
- **Units:** Tesla (T = Wb/m²).  
- 🔗 See: [[06_Fundamentals/Magnetic Flux\|Magnetic Flux]], [[06_Fundamentals/SI Units in Magnetism\|SI Units in Magnetism]]  

---

## 8. Relationship Between B and H

- **Definition:** In a magnetic material, the magnetic flux density (B) is proportional to the magnetic field intensity (H) until the material approaches saturation. #Definition  
- **Formula:**  
  $$B = \mu H$$  
- **Where:**  
  - \( \mu \): Permeability of the material (H/m).  
- **Units:** Tesla (T).  
- **Graph Note:** Straight line in linear region, then bends over as saturation is reached.  
- 🔗 See: [[06_Fundamentals/Electromagnetism\|Electromagnetism]], [[06_Fundamentals/Hysteresis\|Hysteresis]]  

---

## 9. Magnetisation Curve (B–H Curve)

- **Definition:** A magnetisation curve shows how magnetic flux density (B) in a material varies with applied magnetic field intensity (H). #Definition  
- **Key Regions:**  
  - Linear region (initial slope, B ∝ H).  
  - Knee of the curve (saturation begins).  
  - Saturation region (large H produces little increase in B).  
- **Diagram Note:** Plot of B vs H with three distinct regions.  
- 🔗 See: [[06_Fundamentals/Hysteresis\|Hysteresis]]  

---

## 10. Important Practical Notes on Magnetic Circuits

- **Flux confinement:** Most flux is assumed confined to the core.  
- **Air gaps:** Introduce high reluctance → cause fringing.  
- **Non-linear permeability:** μ is not constant in ferromagnetic materials.  
- **Accuracy:** Magnetic circuit analogy gives results within ~5% of actual.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Flux Leakage\|Flux Leakage]], [[06_Fundamentals/SI Units in Magnetism\|SI Units in Magnetism]]


---

## 11. Magnetic Materials

- **Definition:** Magnetic materials are substances that respond to an applied magnetic field and can be classified based on their magnetic properties. #Definition  
- **Types:**  
  - **Ferromagnetic:** Strongly attracted, high permeability (e.g., iron, cobalt, nickel).  
  - **Paramagnetic:** Weak attraction, μ slightly > μ₀ (e.g., aluminium).  
  - **Diamagnetic:** Weak repulsion, μ slightly < μ₀ (e.g., copper, bismuth).  
- **Diagram Note:** Table comparing properties of ferro/para/dia materials.  

---

## 12. Permeability (μ)

- **Definition:** Permeability is the measure of how easily a material allows the establishment of magnetic flux within it. #Definition  
- **Formula:**  
  $$\mu = \frac{B}{H}$$  
- **Units:** Henry per metre (H/m).  
- **Special Values:**  
  - μ₀ = 4π × 10⁻⁷ H/m (permeability of free space).  
  - μᵣ = μ / μ₀ (relative permeability).  
- 🔗 See: [[06_Fundamentals/SI Units in Magnetism\|SI Units in Magnetism]], [[06_Fundamentals/Electromagnetism\|Electromagnetism]]  

---

## 13. Magnetic Hysteresis (Extended)

- **Definition:** When a ferromagnetic material is taken through a cycle of magnetization, the flux density (B) lags behind the magnetizing force (H), forming a closed loop (hysteresis loop). #Definition  
- **Key Terms:**  
  - Remanence (Br): Flux density at H = 0.  
  - Coercivity (Hc): Reverse H needed to reduce B to 0.  
  - Saturation: Maximum B for a material.  
- **Loss:** Energy lost per cycle = area of hysteresis loop.  
- **Diagram Note:** Full B–H hysteresis loop with Br and Hc labelled.  
- 🔗 See: [[06_Fundamentals/Hysteresis\|Hysteresis]]  

---

## 14. Hysteresis Loss Formula

- **Formula:**  
  $$P_h = \eta \cdot B_{max}^{1.6} \cdot f \cdot V$$  
- **Where:**  
  - \(P_h\): Hysteresis power loss (W).  
  - \(\eta\): Steinmetz coefficient (material dependent).  
  - \(B_{max}\): Maximum flux density (T).  
  - \(f\): Frequency (Hz).  
  - \(V\): Volume of core (m³).  
- **Units:** Watts (W).  
- 🔗 See: [[06_Fundamentals/Core Losses\|Core Losses]]  

---

## 15. Eddy Current Loss

- **Definition:** Losses caused by induced circulating currents within the core when exposed to alternating flux. #Definition  
- **Formula:**  
  $$P_e = K_e \cdot B_{max}^2 \cdot f^2 \cdot t^2 \cdot V$$  
- **Where:**  
  - \(K_e\): Constant depending on material.  
  - \(t\): Thickness of lamination.  
- **Units:** Watts (W).  
- **Reduction:** Use laminated cores (increases resistance, reduces current).  
- 🔗 See: [[06_Fundamentals/Core Losses\|Core Losses]]  

---

## 16. Core Losses (Total Iron Loss)

- **Definition:** Total power loss in a magnetic core under alternating flux, consisting of hysteresis and eddy current losses. #Definition  
- **Formula:**  
  $$P_c = P_h + P_e$$  
- **Units:** Watts (W).  
- **Diagram Note:** Pie chart showing hysteresis vs eddy loss proportion.  
- 🔗 See: [[06_Fundamentals/Core Losses\|Core Losses]], [[06_Fundamentals/Hysteresis\|Hysteresis]], [[Eddy Current Loss\|Eddy Current Loss]]  

---

## 17. Example – Losses in Core

- **Problem Type:** Calculate total core loss given Bmax, frequency, lamination thickness, and core volume.  
- **Steps:**  
  1. Compute hysteresis loss using Steinmetz formula.  
  2. Compute eddy current loss using lamination formula.  
  3. Add to get Pc.  
- **Exam Pitfall:** Always use consistent SI units.  

---
---

## 18. Magnetic Circuit Calculations

- **Definition:** Magnetic circuit calculations are performed using the analogy of electrical circuits to determine flux, MMF, and reluctance. #Definition  
- **Formula (Ohm’s Law Analogy):**  
  $$\Phi = \frac{F}{\mathcal{R}}$$  
- **Where:**  
  - \( \Phi \): Flux (Wb)  
  - \( F \): MMF (At)  
  - \( \mathcal{R} \): Reluctance (At/Wb)  
- **Units:** Weber (Wb).  
- **Exam Pitfall:** Always convert lengths to metres and areas to m² before calculating reluctance.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Magnetomotive Force (MMF)\|Magnetomotive Force (MMF)]]

---

## 19. Series Magnetic Circuits

- **Definition:** In a series magnetic circuit, the same flux passes through all sections in series, while MMF drops across each section. #Definition  
- **Formula (Reluctances in series):**  
  $$\mathcal{R}_{eq} = \mathcal{R}_1 + \mathcal{R}_2 + \mathcal{R}_3 + \dots$$  
- **Flux Calculation:**  
  $$\Phi = \frac{F}{\mathcal{R}_{eq}}$$  
- **Diagram Note:** Magnetic circuit with three sections in series.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Magnetic Flux\|Magnetic Flux]]

---

## 20. Parallel Magnetic Circuits

- **Definition:** In a parallel magnetic circuit, flux divides between branches according to their reluctances. #Definition  
- **Formula (Reluctances in parallel):**  
  $$\frac{1}{\mathcal{R}_{eq}} = \frac{1}{\mathcal{R}_1} + \frac{1}{\mathcal{R}_2} + \dots$$  
- **Flux Distribution:**  
  $$\Phi_i = \frac{F}{\mathcal{R}_i}$$  
- **Diagram Note:** Core with two parallel paths carrying different flux.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Magnetic Flux\|Magnetic Flux]]

---

## 21. Composite Magnetic Circuits

- **Definition:** A composite circuit contains both series and parallel sections. #Definition  
- **Method:**  
  - Break into sections.  
  - Compute reluctance of each section.  
  - Combine using series + parallel rules.  
- **Diagram Note:** Stator core with multiple flux paths.  
- **Exam Pitfall:** Careful with air gaps → they dominate reluctance.  

---

## 22. Air Gap Effects

- **Definition:** An air gap is a discontinuity in a magnetic circuit that introduces very high reluctance compared to iron. #Definition  
- **Formula (Reluctance of air gap):**  
  $$\mathcal{R}_{gap} = \frac{l_g}{\mu_0 A_g}$$  
- **Where:**  
  - \( l_g \): length of gap (m)  
  - \( A_g \): area of gap (m²)  
  - \( \mu_0 = 4\pi \times 10^{-7} \) H/m  
- **Fringing Effect:** Flux spreads in air gap → effective area increases slightly.  
- **Diagram Note:** Core with exaggerated fringing at air gap.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Flux Leakage\|Flux Leakage]]  

---

## 23. Example – Magnetic Circuit with Air Gap

- **Problem Type:** Given core dimensions, μᵣ, air gap length, and coil current, calculate flux and flux density.  
- **Steps:**  
  1. Compute reluctance of iron and gap.  
  2. Find equivalent reluctance.  
  3. Apply flux law \( \Phi = F / \mathcal{R}_{eq} \).  
  4. Calculate flux density \( B = \Phi / A \).  
- **Exam Pitfall:** Don’t forget μ for iron vs μ₀ for air.  

---

## 24. Limitations of Magnetic Circuit Analogy

- **Definition:** The magnetic circuit analogy (with electrical circuits) is approximate, not exact. #Definition  
- **Key Limitations:**  
  - Flux does not always stay confined to the core → leakage flux.  
  - Permeability μ is nonlinear (depends on B).  
  - Air-gap fringing is difficult to model precisely.  
  - Results are usually within ~5% of measured values.  
- 🔗 See: [[06_Fundamentals/Flux Leakage\|Flux Leakage]], [[Magnetic Circuits\|Magnetic Circuits]]  

---
---

## 18. Magnetic Circuit Calculations

- **Definition:** Magnetic circuit calculations are performed using the analogy of electrical circuits to determine flux, MMF, and reluctance. #Definition  
- **Formula (Ohm’s Law Analogy):**    
$$
\Phi = \frac{F}{R}
$$
  
- **Where:**  
  - \( \Phi \): Flux (Wb)  
  - \( F \): MMF (At)  
  - \( \mathcal{R} \): Reluctance (At/Wb)  
- **Units:** Weber (Wb).  
- **Exam Pitfall:** Always convert lengths to metres and areas to m² before calculating reluctance.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Magnetomotive Force (MMF)\|Magnetomotive Force (MMF)]]

---

## 19. Series Magnetic Circuits

- **Definition:** In a series magnetic circuit, the same flux passes through all sections in series, while MMF drops across each section. #Definition  
- **Formula (Reluctances in series):**  
  $$\mathcal{R}_{eq} = \mathcal{R}_1 + \mathcal{R}_2 + \mathcal{R}_3 + \dots$$  
- **Flux Calculation:**  
  $$\Phi = \frac{F}{\mathcal{R}_{eq}}$$  
- **Diagram Note:** Magnetic circuit with three sections in series.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Magnetic Flux\|Magnetic Flux]]

---

## 20. Parallel Magnetic Circuits

- **Definition:** In a parallel magnetic circuit, flux divides between branches according to their reluctances. #Definition  
- **Formula (Reluctances in parallel):**  
  $$\frac{1}{\mathcal{R}_{eq}} = \frac{1}{\mathcal{R}_1} + \frac{1}{\mathcal{R}_2} + \dots$$  
- **Flux Distribution:**  
  $$\Phi_i = \frac{F}{\mathcal{R}_i}$$  
- **Diagram Note:** Core with two parallel paths carrying different flux.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Magnetic Flux\|Magnetic Flux]]

---

## 21. Composite Magnetic Circuits

- **Definition:** A composite circuit contains both series and parallel sections. #Definition  
- **Method:**  
  - Break into sections.  
  - Compute reluctance of each section.  
  - Combine using series + parallel rules.  
- **Diagram Note:** Stator core with multiple flux paths.  
- **Exam Pitfall:** Careful with air gaps → they dominate reluctance.  

---

## 22. Air Gap Effects

- **Definition:** An air gap is a discontinuity in a magnetic circuit that introduces very high reluctance compared to iron. #Definition  
- **Formula (Reluctance of air gap):**  
  $$\mathcal{R}_{gap} = \frac{l_g}{\mu_0 A_g}$$  
- **Where:**  
  - \( l_g \): length of gap (m)  
  - \( A_g \): area of gap (m²)  
  - \( \mu_0 = 4\pi \times 10^{-7} \) H/m  
- **Fringing Effect:** Flux spreads in air gap → effective area increases slightly.  
- **Diagram Note:** Core with exaggerated fringing at air gap.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Flux Leakage\|Flux Leakage]]  

---

## 23. Example – Magnetic Circuit with Air Gap

- **Problem Type:** Given core dimensions, μᵣ, air gap length, and coil current, calculate flux and flux density.  
- **Steps:**  
  1. Compute reluctance of iron and gap.  
  2. Find equivalent reluctance.  
  3. Apply flux law \( \Phi = F / \mathcal{R}_{eq} \).  
  4. Calculate flux density \( B = \Phi / A \).  
- **Exam Pitfall:** Don’t forget μ for iron vs μ₀ for air.  

---

## 24. Limitations of Magnetic Circuit Analogy

- **Definition:** The magnetic circuit analogy (with electrical circuits) is approximate, not exact. #Definition  
- **Key Limitations:**  
  - Flux does not always stay confined to the core → leakage flux.  
  - Permeability μ is nonlinear (depends on B).  
  - Air-gap fringing is difficult to model precisely.  
  - Results are usually within ~5% of measured values.  
- 🔗 See: [[06_Fundamentals/Flux Leakage\|Flux Leakage]], [[Magnetic Circuits\|Magnetic Circuits]]  


---

## 25. Energy in Magnetic Fields

- **Definition:** When current establishes magnetic flux in a magnetic field, energy is stored in the field. #Definition  
- **Formula:**  
  $$W = \frac{1}{2} L I^2$$  
- **Where:**  
  - \( W \): Stored energy (J)  
  - \( L \): Inductance (H)  
  - \( I \): Current (A)  
- **Alternative Expression:**  
  $$W = \frac{1}{2} B \cdot H \cdot V$$  
- **Units:** Joules (J).  
- **Diagram Note:** Field lines in coil core showing energy storage.  
- 🔗 See: [[06_Fundamentals/Energy Conversion\|Energy Conversion]], [[06_Fundamentals/Electromagnetism\|Electromagnetism]]

---

## 26. Inductance (L)

- **Definition:** Inductance is the property of a coil by which it opposes a change in current due to the production of self-induced emf. #Definition  
- **Formula:**  
  $$L = \frac{N \cdot \Phi}{I}$$  
- **Units:** Henry (H).  
- **Factors Affecting Inductance:**  
  - Number of turns (N).  
  - Core material (μ).  
  - Cross-sectional area (A).  
  - Length of magnetic path (l).  
- 🔗 See: [[06_Fundamentals/Faraday’s Law\|Faraday’s Law]], [[06_Fundamentals/Electromagnetism\|Electromagnetism]]

---

## 27. Self-Inductance

- **Definition:** Self-inductance is the property of a coil whereby a change in its own current induces an emf in it. #Definition  
- **Formula:**  
  $$e = -L \frac{dI}{dt}$$  
- **Units:** Volts (V).  
- **Diagram Note:** Coil with changing current producing emf opposing it.  

---

## 28. Mutual Inductance

- **Definition:** Mutual inductance is the property of two coils whereby a change of current in one coil induces an emf in the other. #Definition  
- **Formula:**  
  $$M = \frac{N_2 \Phi_{12}}{I_1}$$  
- **Where:**  
  - \(M\): Mutual inductance (H).  
  - \(\Phi_{12}\): Flux linking coil 2 due to current in coil 1.  
- **Units:** Henry (H).  
- **Diagram Note:** Two coils on same core, one inducing emf in the other.  
- 🔗 See: [[06_Fundamentals/Dot Convention\|Dot Convention]], [[06_Fundamentals/Faraday’s Law\|Faraday’s Law]]  

---

## 29. Dot Convention

- **Definition:** The dot convention is a method of marking transformer windings to indicate relative polarity of voltages. If current enters the dotted end of one winding, the induced voltage at the dotted end of the other winding is positive. #Definition  
- **Usage:** Essential for correct connection of multi-winding transformers.  
- **Diagram Note:** Transformer symbol with dotted ends.  
- 🔗 See: [[06_Fundamentals/Dot Convention\|Dot Convention]], [[06_Fundamentals/Turns Ratio\|Turns Ratio]]

---

## 30. Example – Inductance and Energy

- **Problem Type:** Calculate energy stored in a coil given N, I, core dimensions, and μ.  
- **Steps:**  
  1. Calculate flux: \( \Phi = B \cdot A \).  
  2. Find inductance: \( L = N \Phi / I \).  
  3. Energy: \( W = \tfrac{1}{2} L I^2 \).  
- **Exam Pitfall:** Always check SI units (H, A, Wb).  


---

## 31. Fringing of Flux at Air Gap

- **Definition:** Fringing occurs at an air gap where magnetic flux lines spread out, increasing the effective cross-sectional area of the gap. #Definition  
- **Effect:** Reduces flux density in the gap compared to the core.  
- **Correction Factor:** Effective area of air gap is taken slightly larger than its physical area to account for fringing.  
- **Diagram Note:** Core with flux spreading at gap edges.  
- 🔗 See: [[06_Fundamentals/Reluctance\|Reluctance]], [[06_Fundamentals/Flux Leakage\|Flux Leakage]]

---

## 32. Leakage Flux

- **Definition:** The portion of magnetic flux that does not link both windings (or intended parts of the magnetic circuit). #Definition  
- **Effect:** Causes leakage reactance in transformers and reduces efficiency.  
- **Diagram Note:** Transformer with some flux bypassing the secondary winding.  
- 🔗 See: [[06_Fundamentals/Flux Leakage\|Flux Leakage]], [[06_Fundamentals/Equivalent Circuit of Transformer\|Equivalent Circuit of Transformer]]

---

## 33. Magnetic Core Materials

- **Soft Iron / Silicon Steel:** High permeability, low hysteresis loss → used in transformers.  
- **Ferrites:** Non-metallic, high resistivity, reduce eddy currents → used in high-frequency applications.  
- **Permanent Magnet Materials:** High coercivity → used in DC motors/generators.  
- **Diagram Note:** Table comparing μ, losses, applications.  
- 🔗 See: [[06_Fundamentals/Core Losses\|Core Losses]], [[06_Fundamentals/Hysteresis\|Hysteresis]]

---

## 34. B–H Characteristics of Different Materials

- **Definition:** B–H characteristics show how different materials respond to magnetizing force. #Definition  
- **Soft Magnetic Materials:** Steep slope, low hysteresis.  
- **Hard Magnetic Materials:** Shallow slope, wide hysteresis loop.  
- **Diagram Note:** Overlay graph of soft vs hard material loops.  

---

## 35. Magnetic Saturation

- **Definition:** Saturation occurs when an increase in magnetizing force (H) produces little or no increase in flux density (B). #Definition  
- **Graph Note:** Knee point on B–H curve marks saturation.  
- **Practical Impact:** Limits maximum flux in machines/transformers.  
- 🔗 See: [[06_Fundamentals/Hysteresis\|Hysteresis]], [[Magnetisation Curve\|Magnetisation Curve]]

---

## 36. Example – Composite Core Calculation

- **Problem Type:** Given dimensions and μ values of different core sections, calculate total reluctance, flux, and flux density.  
- **Steps:**  
  1. Compute reluctance for each section.  
  2. Add series and parallel reluctances.  
  3. Apply \( \Phi = F / \mathcal{R}_{eq} \).  
- **Exam Pitfall:** Watch for units (mm² → m², cm → m).  

---

## 37. Practical Applications of Magnetic Circuits

- Transformers: Core design affects losses and efficiency.  
- DC Machines: Armature reaction and flux control.  
- Induction Motors: Air-gap flux controls torque.  
- Magnetic Relays: Rely on MMF and air-gap flux.  
- Magnetic Storage: Hysteresis used in memory devices.  

---

## 38. Summary of Key Formulas (Lecture 1)

- **Flux:**  
  $$\Phi = B \cdot A$$  
- **MMF:**  
  $$F = N \cdot I$$  
- **Reluctance:**  
  $$\mathcal{R} = \frac{l}{\mu \cdot A}$$  
- **Flux Law:**  
  $$\Phi = \frac{F}{\mathcal{R}}$$  
- **Magnetic Field Intensity:**  
  $$H = \frac{N I}{l}$$  
- **Flux Density:**  
  $$B = \mu H$$  
- **Hysteresis Loss:**  
  $$P_h = \eta \cdot B_{max}^{1.6} \cdot f \cdot V$$  
- **Eddy Current Loss:**  
  $$P_e = K_e \cdot B_{max}^2 \cdot f^2 \cdot t^2 \cdot V$$  
- **Core Loss:**  
  $$P_c = P_h + P_e$$  
- **Energy Stored:**  
  $$W = \tfrac{1}{2} L I^2 = \tfrac{1}{2} B H V$$  

---

## 39. Lecture 1 – Closing Notes

- Magnetic circuits behave like electrical circuits but with nonlinearities.  
- Air gaps dominate reluctance.  
- Hysteresis and eddy losses are critical for design efficiency.  
- Always check SI units in exam problems.  

---

### 🔎 Graphs & Diagrams (Slides 1–10)
- Oersted’s experiment sketch (field around conductor).  
- Fleming’s hand rules (motor vs generator).  
- Force on conductor diagram.  
- B–H loop.  
- Magnetic circuit analogy diagram.

### 🔎 Graphs & Diagrams (Slides 11–20)
- Graph of B vs H (straight line and saturation).  
- Full magnetisation curve (linear, knee, saturation).  
- Sketch showing fringing at an air gap.  

### 🔎 Graphs & Diagrams (Slides 21–30)
- Table: comparison of ferro, para, dia materials.  
- Graph: B–H hysteresis loop.  
- Diagram: laminated vs solid core (eddy current reduction).  
- Pie chart: hysteresis vs eddy loss.  

### 🔎 Graphs & Diagrams (Slides 31–40)
- Magnetic circuit with series reluctances.  
- Core with parallel flux paths.  
- Composite magnetic circuit example.  
- Air-gap diagram with fringing.  
- Worked example of flux calculation.

### 🔎 Graphs & Diagrams (Slides 31–40)
- Magnetic circuit with series reluctances.  
- Core with parallel flux paths.  
- Composite magnetic circuit example.  
- Air-gap diagram with fringing.  
- Worked example of flux calculation.

### 🔎 Graphs & Diagrams (Slides 41–50)
- Energy storage diagram in magnetic field.  
- Inductance formula with coil/core sketch.  
- Self-inductance emf diagram.  
- Mutual inductance with two coils.  
- Transformer symbol showing dot convention.

### 🔎 Graphs & Diagrams (Slides 51–59)
- Flux fringing at an air gap.  
- Leakage flux sketch in transformer.  
- B–H curves: soft vs hard material.  
- Composite core example.  
- Saturation knee point diagram.  