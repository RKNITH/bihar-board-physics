# 📘 Class 12 Physics — Chapter 8: Electromagnetic Waves
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Maxwell's Equations — Overview](#2-maxwells-equations--overview)
3. [Displacement Current](#3-displacement-current)
4. [Electromagnetic Waves](#4-electromagnetic-waves)
5. [Sources of Electromagnetic Waves](#5-sources-of-electromagnetic-waves)
6. [Nature and Properties of Electromagnetic Waves](#6-nature-and-properties-of-electromagnetic-waves)
7. [Speed of Electromagnetic Waves](#7-speed-of-electromagnetic-waves)
8. [Electromagnetic Spectrum](#8-electromagnetic-spectrum)
9. [Radio Waves](#9-radio-waves)
10. [Microwaves](#10-microwaves)
11. [Infrared Waves](#11-infrared-waves)
12. [Visible Light](#12-visible-light)
13. [Ultraviolet Rays](#13-ultraviolet-rays)
14. [X-Rays](#14-x-rays)
15. [Gamma Rays](#15-gamma-rays)
16. [Important Formulas Summary](#16-important-formulas-summary)
17. [Board Exam Questions with Answers](#17-board-exam-questions-with-answers)
18. [Objective / MCQ Questions](#18-objective--mcq-questions)
19. [Quick Revision Tips](#19-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is about **Electromagnetic Waves** — one of the most important discoveries in the history of physics.

Think of it this way:
- How does light travel from the Sun to Earth through empty space (vacuum)?  → Through **electromagnetic waves**.
- How does your mobile phone communicate wirelessly? → **Radio/microwave electromagnetic waves**.
- How does a microwave oven heat your food? → **Microwaves** (a type of EM wave).
- How does an X-ray machine see inside your body? → **X-rays** (a type of EM wave).
- How does the remote control work for your TV? → **Infrared waves**.

All of these are examples of **electromagnetic waves**. This chapter explains what they are, how they are produced, and the complete spectrum of all EM waves.

**What you will learn:**
- What is displacement current and why Maxwell introduced it
- What electromagnetic waves are and their properties
- How EM waves travel and their speed
- The full Electromagnetic Spectrum (Radio → Gamma rays)
- Properties and uses of each type of EM wave

> 📝 **Bihar Board Note:** This chapter carries **3 marks** in the board exam (Unit 5: Electromagnetic Waves). It is a short but very scoring chapter. Every question has a predictable pattern — learn the spectrum table and displacement current derivation!

---

## 2. Maxwell's Equations — Overview

### 2.1 Background — The Problem with Ampere's Law

Before Maxwell, four fundamental laws of electromagnetism were known:

| Law | What it describes |
|---|---|
| Gauss's Law (Electric) | Electric flux through a closed surface = Q/ε₀ |
| Gauss's Law (Magnetic) | Net magnetic flux through any closed surface = 0 |
| Faraday's Law | Changing magnetic field produces electric field |
| Ampere's Law (original) | Magnetic field is produced by electric current |

**Ampere's Law (original):**
```
∮ B · dl = μ₀ I
```

Maxwell found an **inconsistency** in Ampere's Law. He discovered that Ampere's Law was incomplete — it only accounted for **conduction current** (actual flow of charges) but missed something crucial happening between capacitor plates.

### 2.2 Maxwell's Modification — Generalized Ampere's Law

Maxwell corrected Ampere's Law by adding a new term called **Displacement Current**:

```
∮ B · dl = μ₀ (I_c + I_d)
```

Where:
- `I_c` = Conduction current (real current due to flow of charges)
- `I_d` = Displacement current (Maxwell's new term — current due to changing electric flux)

**This is called Maxwell's Generalized Ampere's Circuital Law.**

### 2.3 Maxwell's Four Equations (Board Level)

| Equation | Based on | Meaning |
|---|---|---|
| ∮ E · dA = Q/ε₀ | Gauss's Law (Electric) | Electric field due to charges |
| ∮ B · dA = 0 | Gauss's Law (Magnetic) | No magnetic monopoles exist |
| ∮ E · dl = −dΦ_B/dt | Faraday's Law | Changing B produces E |
| ∮ B · dl = μ₀(I_c + ε₀ dΦ_E/dt) | Modified Ampere's Law | Current + changing E produces B |

> 📝 **Board Exam:** You don't need to solve Maxwell's equations. Just know their names and what they represent. 2-mark question often asks: "What was Maxwell's contribution to Ampere's Law?"

---

## 3. Displacement Current

### 3.1 Why is Displacement Current Needed? ⭐⭐ (Most Important — Board Exam)

**The Problem (Inconsistency in Ampere's Law):**

Consider a **capacitor** being charged by a battery. Current `I` flows in the wires outside the capacitor plates.

- If you draw an Amperian loop around the wire → B ≠ 0 (current passes through the loop's surface)
- If you draw a bulging surface between the capacitor plates → B = 0 by Ampere's original law (no current passes through the gap)

But both surfaces are bounded by the **same loop**! So Ampere's law gives **two different answers** for the same loop → **This is a contradiction!**

**Maxwell's Solution:**

Maxwell argued that between the capacitor plates, even though no real current flows, the **electric field is changing** as the capacitor charges. This changing electric field should produce a magnetic field — just like a changing magnetic field produces an electric field (Faraday's Law).

So Maxwell introduced **Displacement Current**:

```
        dΦ_E
I_d = ε₀ ————
         dt
```

Where:
- `I_d` = Displacement current (in Ampere, A)
- `ε₀` = Permittivity of free space = 8.85 × 10⁻¹² C² N⁻¹ m⁻²
- `dΦ_E/dt` = Rate of change of electric flux (V·m/s)

### 3.2 Derivation of Displacement Current ⭐⭐ (5-Mark Derivation)

**Setup:** A capacitor with plate area `A` is being charged. The conduction current in the wire is `I_c`.

**Step 1:** The charge on capacitor at time t is `q`.

Charge: q = C × V (but we'll use the field approach)

**Step 2:** The electric field between the plates:
```
E = q / (ε₀ A)       [from Gauss's law, σ = q/A, E = σ/ε₀]
```

**Step 3:** Electric flux between the plates:
```
Φ_E = E × A = q / ε₀
```

**Step 4:** Rate of change of electric flux:
```
dΦ_E/dt = (1/ε₀) × dq/dt = I_c / ε₀
```

So:
```
        dΦ_E
I_d = ε₀ ———— = ε₀ × (I_c / ε₀) = I_c
         dt
```

**This shows: Displacement current between the plates = Conduction current in the wires!**

The inconsistency is resolved. The **total current** (conduction + displacement) is always continuous.

### 3.3 Key Points about Displacement Current

1. Displacement current is **NOT a real current** — no actual charge is flowing.
2. It is produced due to **changing electric flux** (changing electric field).
3. It has the **same value** as the conduction current in the circuit.
4. It produces a **magnetic field** just like conduction current.
5. SI Unit: **Ampere (A)** — same as conduction current.

> 📝 **Board Exam Tip:** "What is displacement current?" is a very common 2-mark question. Answer: "Displacement current is the current that arises due to the rate of change of electric flux. It is given by I_d = ε₀ (dΦ_E/dt)."

---

## 4. Electromagnetic Waves

### 4.1 What is an Electromagnetic Wave? ⭐⭐

**Definition:** *"An electromagnetic wave is a wave consisting of oscillating electric and magnetic fields that are perpendicular to each other and to the direction of propagation."*

**How EM waves are produced:**

Maxwell's modified Ampere's Law says:
- A **changing electric field** produces a **magnetic field**.

And Faraday's Law says:
- A **changing magnetic field** produces an **electric field**.

So once you have a changing E field, it produces a changing B field, which produces a changing E field — and so on. This self-sustaining oscillating wave travels through space → **Electromagnetic Wave!**

```
          E field (vertical)
          ↑ ↑ ↑
          ↑ ↑ ↑
→ → → → → → → → → → →   Direction of propagation
          ↓ B field (horizontal, into/out of page)
```

### 4.2 Diagram of an Electromagnetic Wave

```
       E (Electric Field)
       ↑
       |   /\      /\
       |  /  \    /  \
   ————|—/————\——/————\————→   Direction of wave travel (z-axis)
       |/      \/      \
       |
       
       B (Magnetic Field) — oscillates perpendicular to E and to direction of travel
       ↑
       |   /\      /\
       |  /  \    /  \
   ————|—/————\——/————\————→
```

- E and B are **perpendicular to each other**.
- Both are **perpendicular to the direction of propagation**.
- They oscillate **in phase** (reach maximum and minimum at the same time).

---

## 5. Sources of Electromagnetic Waves

### 5.1 How EM Waves are Produced ⭐

**Statement:** *"An accelerating electric charge (or an oscillating electric charge) produces electromagnetic waves."*

**Examples:**
- An **oscillating charge** (like electrons oscillating in an antenna) produces EM waves of the same frequency as the oscillation.
- **Accelerating electrons** in X-ray tubes produce X-rays.
- **Nuclear transitions** produce gamma rays.
- **Hot bodies** emit infrared and visible light.

**Hertz's Experiment (1887):**
- Heinrich Hertz was the **first person** to produce and detect electromagnetic waves in the laboratory.
- He produced EM waves with a wavelength of a few metres (radio waves).
- This confirmed Maxwell's theoretical prediction.

> 📝 **Board Exam:** "Who first produced electromagnetic waves experimentally?" → **Hertz (1887)**

### 5.2 Mathematical Representation

The electric field of an EM wave travelling in the x-direction:
```
E_y = E₀ sin(kx − ωt)
```

The magnetic field:
```
B_z = B₀ sin(kx − ωt)
```

Where:
- `E₀` = Maximum value (amplitude) of electric field
- `B₀` = Maximum value (amplitude) of magnetic field
- `k` = wave number = 2π/λ
- `ω` = angular frequency = 2πν
- E and B are **in phase** (same kx − ωt term)

---

## 6. Nature and Properties of Electromagnetic Waves

### 6.1 Properties of EM Waves ⭐⭐ (3-Mark Question — Very Common)

1. **Transverse Nature:** EM waves are **transverse waves** — E and B fields oscillate perpendicular to the direction of propagation.

2. **No medium required:** EM waves can travel through **vacuum** (unlike sound waves, which need a medium). They travel at maximum speed in vacuum.

3. **Speed in vacuum:** All EM waves travel at the **same speed** in vacuum:
   ```
   c = 3 × 10⁸ m/s
   ```

4. **Speed in medium:** Speed is **reduced** in a medium:
   ```
   v = c / n     (where n = refractive index of medium)
   ```

5. **E and B are perpendicular:** Electric field E and magnetic field B are always perpendicular to each other.

6. **Both E and B are perpendicular to direction of travel:** This makes EM waves transverse.

7. **In phase:** E and B fields are **in phase** — they reach their maximum and minimum values at the same point and same time.

8. **Relationship between E and B amplitudes:**
   ```
   E₀ / B₀ = c     (in vacuum)
   ```
   i.e., E₀ = c × B₀

9. **Wave equation:** EM waves satisfy the wave equation:
   ```
   v = νλ    (frequency × wavelength = speed)
   c = νλ    (in vacuum)
   ```

10. **Energy:** EM waves carry **energy and momentum** as they propagate.

11. **Pressure:** EM waves exert **radiation pressure** on surfaces they fall on.

12. **Can be polarized:** Since they are transverse waves, EM waves can be **polarized** (unlike sound, which cannot be polarized).

### 6.2 Ratio of Electric to Magnetic Field

In an EM wave:
```
E₀/B₀ = c = 3 × 10⁸ m/s
```

Also:
```
E_rms / B_rms = c
```

> 📝 **Board Exam Note:** A very common numerical — "In an EM wave, E₀ = 6 V/m. Find B₀." Answer: B₀ = E₀/c = 6 / (3×10⁸) = 2×10⁻⁸ T

---

## 7. Speed of Electromagnetic Waves

### 7.1 Formula for Speed ⭐⭐

Maxwell derived the speed of EM waves from first principles:

```
         1
c = ————————————
     √(μ₀ ε₀)
```

Where:
- `c` = Speed of EM waves in vacuum = **3 × 10⁸ m/s**
- `μ₀` = Permeability of free space = 4π × 10⁻⁷ T·m/A
- `ε₀` = Permittivity of free space = 8.85 × 10⁻¹² C² N⁻¹ m⁻²

**This was one of Maxwell's greatest achievements** — he calculated this speed from electric and magnetic constants alone, and it matched the experimentally measured speed of light. This proved that **light is an electromagnetic wave!**

### 7.2 Speed in a Medium

In a medium with permittivity ε and permeability μ:
```
         1
v = ————————————
     √(με)
```

Since ε = ε₀εᵣ and μ = μ₀μᵣ:
```
         1                    c
v = ————————————————— = ——————————————
     √(μ₀εᵣ μ₀μᵣ)          √(εᵣμᵣ)
```

For non-magnetic materials (μᵣ ≈ 1):
```
v = c / √εᵣ = c / n
```
(where n = refractive index)

### 7.3 Important Values

| Constant | Value |
|---|---|
| Speed of light in vacuum (c) | 3 × 10⁸ m/s |
| μ₀ | 4π × 10⁻⁷ T·m/A ≈ 1.26 × 10⁻⁶ T·m/A |
| ε₀ | 8.85 × 10⁻¹² C² N⁻¹ m⁻² |
| μ₀ε₀ | 1/c² = 1/(9 × 10¹⁶) |

---

## 8. Electromagnetic Spectrum

### 8.1 What is the Electromagnetic Spectrum? ⭐⭐⭐ (Most Important — Always in Board Exam)

**Definition:** *"The orderly distribution of electromagnetic waves according to their frequency (or wavelength) is called the electromagnetic spectrum."*

All electromagnetic waves travel at the **same speed** (c = 3 × 10⁸ m/s) in vacuum but differ in their **frequency and wavelength**.

The relation: **c = νλ** applies to all.

### 8.2 Complete EM Spectrum Table ⭐⭐⭐ (Must Memorise!)

| Type of Wave | Frequency Range | Wavelength Range | Source | Uses |
|---|---|---|---|---|
| **Radio Waves** | 10⁵ – 10⁹ Hz | > 0.1 m (10 cm to km) | Oscillating circuits/antennas | Radio, TV, communication |
| **Microwaves** | 10⁹ – 10¹² Hz | 10⁻³ – 0.1 m (1 mm – 10 cm) | Klystron/Magnetron tubes | Radar, microwave oven, satellite |
| **Infrared** | 10¹¹ – 10¹⁴ Hz | 7×10⁻⁷ – 10⁻³ m | Hot bodies, molecules | TV remotes, night vision, heating |
| **Visible Light** | 4×10¹⁴ – 7×10¹⁴ Hz | 4×10⁻⁷ – 7×10⁻⁷ m (400–700 nm) | Excited atoms | Human vision, photography |
| **Ultraviolet** | 10¹⁵ – 10¹⁷ Hz | 10⁻⁸ – 4×10⁻⁷ m | Sun, electric arc, hot bodies | Sterilisation, vitamin D, LASIK |
| **X-Rays** | 10¹⁷ – 10¹⁹ Hz | 10⁻¹¹ – 10⁻⁸ m | X-ray tubes (bombarding metal) | Medical imaging, crystal structure |
| **Gamma Rays** | 10¹⁹ – 10²³ Hz | < 10⁻¹¹ m | Radioactive nuclei, cosmic rays | Cancer treatment, sterilisation |

### 8.3 Frequency and Wavelength Order (Memory Trick)

**Increasing frequency (decreasing wavelength):**

```
Radio → Microwaves → Infrared → Visible → Ultraviolet → X-Rays → Gamma Rays
```

**Memory Trick (English):** **"R**ather **M**any **I**ntelligent **V**illagers **U**se **X**ceptional **G**enius"

OR in reverse (increasing wavelength):
```
Gamma → X-ray → UV → Visible → IR → Microwave → Radio
```

**Visible Light — VIBGYOR (increasing wavelength):**
```
Violet → Indigo → Blue → Green → Yellow → Orange → Red
(highest frequency)                              (lowest frequency)
```

- Violet: λ ≈ 400 nm (shortest wavelength in visible)
- Red: λ ≈ 700 nm (longest wavelength in visible)

---

## 9. Radio Waves

### 9.1 Properties and Details ⭐

- **Frequency:** 10⁵ Hz to 10⁹ Hz (100 kHz to 1 GHz)
- **Wavelength:** A few metres to several kilometres
- **Produced by:** Oscillating circuits (LC circuits, antennas) — rapidly oscillating electrons in antennas

### 9.2 Uses of Radio Waves

1. **AM Radio (Amplitude Modulation):** Frequency range 540 kHz – 1600 kHz. Used for radio broadcasting.
2. **FM Radio (Frequency Modulation):** Frequency range 88 MHz – 108 MHz. Better quality audio.
3. **Television broadcasts:** VHF and UHF bands.
4. **Long-distance communication:** Short-wave radio (3–30 MHz) reflects from ionosphere — used for international broadcasts.
5. **Cellular/mobile communication**

> 📝 **Board Exam:** "Why are short-wave bands used for long-distance radio broadcasts?" → Because short-wave radio waves are reflected by the ionosphere and can travel around the curvature of the Earth. Long-wave signals get absorbed/not reflected.

---

## 10. Microwaves

### 10.1 Properties and Details ⭐

- **Frequency:** 1 GHz to 300 GHz (10⁹ – 10¹² Hz)
- **Wavelength:** 1 mm to 10 cm
- **Produced by:** Special vacuum tubes — **Klystron** and **Magnetron tubes**, or Gunn diodes

### 10.2 Uses of Microwaves ⭐ (Board Favourite)

1. **Radar (Radio Detection And Ranging):** Used in aircraft navigation, ships, and weather forecasting.
2. **Microwave Oven:** Microwaves (at 2.45 GHz) cause water molecules in food to vibrate, generating heat. The food is heated from inside.
3. **Satellite communication:** Microwave links connect ground stations to satellites.
4. **Mobile phone networks:** 4G/5G uses microwave frequencies.
5. **Speed guns:** Police use microwave guns (Doppler effect) to detect vehicle speed.

> 📝 **Board Exam:** "Why does a microwave oven heat food?" → Microwaves at 2.45 GHz match the resonant frequency of water molecules. The microwaves are absorbed by water molecules in the food, causing them to vibrate rapidly — generating heat throughout the food.

---

## 11. Infrared Waves

### 11.1 Properties and Details ⭐

- **Frequency:** 10¹¹ – 10¹⁴ Hz
- **Wavelength:** 700 nm – 1 mm (just below visible red light)
- **Produced by:** Hot bodies, molecules, the Sun (about 50% of solar radiation is IR)
- Also called **"heat waves"** because they are strongly felt as heat

### 11.2 Uses of Infrared Waves ⭐

1. **TV Remote Controls:** Use infrared LEDs to send signals.
2. **Night Vision Cameras:** Detect body heat in darkness — used in military and security.
3. **Medical Diagnosis:** Infrared thermometers, detecting inflammation.
4. **Greenhouses:** Glass transmits visible light but traps infrared → greenhouse effect.
5. **Drying and Curing:** Infrared lamps used in paint drying, food drying.
6. **Earth's Atmosphere:** IR radiation from Earth's surface is trapped by CO₂ and water vapour → **Global Warming / Greenhouse Effect**.
7. **Optical fibre communication:** Certain IR wavelengths used in fibre optics.

> 📝 **Board Exam:** "Why are infrared waves called heat waves?" → Because they are readily absorbed by most substances and produce a heating effect. They are the main form of heat radiation from warm/hot bodies.

---

## 12. Visible Light

### 12.1 Properties and Details ⭐

- **Frequency:** 4 × 10¹⁴ – 7 × 10¹⁴ Hz
- **Wavelength:** 400 nm – 700 nm (violet to red)
- **Produced by:** Electrons in excited atoms falling to lower energy levels; incandescent objects; LEDs
- This is the **only range of EM spectrum detectable by the human eye**

### 12.2 Colour and Wavelength

| Colour | Approximate Wavelength |
|---|---|
| Violet | 380 – 450 nm |
| Blue | 450 – 495 nm |
| Green | 495 – 570 nm |
| Yellow | 570 – 590 nm |
| Orange | 590 – 620 nm |
| Red | 620 – 700 nm |

### 12.3 Uses

1. Human vision and photography
2. Optical instruments (lenses, microscopes, telescopes)
3. Lasers (used in surgery, barcode scanners, optical communication)
4. Photosynthesis in plants

---

## 13. Ultraviolet Rays

### 13.1 Properties and Details ⭐

- **Frequency:** 10¹⁵ – 10¹⁷ Hz
- **Wavelength:** 10 nm – 400 nm (just above visible violet)
- **Produced by:** The Sun (main source), electric arcs, mercury vapour lamps, very hot bodies (stars)
- Most UV from the Sun is absorbed by the **ozone layer** in the atmosphere (very important fact!)

### 13.2 Uses of Ultraviolet Rays ⭐

1. **Sterilisation:** UV light kills bacteria and viruses — used to sterilise surgical equipment, water purifiers, and hospitals.
2. **Vitamin D production:** UV from sunlight causes skin to produce Vitamin D.
3. **LASIK Eye Surgery:** Uses UV laser to reshape the cornea.
4. **Fluorescence:** UV causes certain substances to fluoresce — used in detecting fake currency notes (under UV lamp).
5. **Tanning:** UV causes the skin to tan (melanin production).
6. **Photography:** UV photography used in forensics.

### 13.3 Harmful Effects

- Excessive UV causes **skin cancer**, **sunburn**, and **cataracts** in eyes.
- **Ozone layer depletion** (by CFCs/freons) increases UV reaching Earth's surface — a major environmental concern.

> 📝 **Board Exam:** "What is the role of the ozone layer?" → The ozone layer (O₃) in the stratosphere absorbs most of the harmful ultraviolet radiation coming from the Sun, protecting life on Earth.

---

## 14. X-Rays

### 14.1 Properties and Details ⭐

- **Frequency:** 10¹⁷ – 10¹⁹ Hz
- **Wavelength:** 0.01 nm – 10 nm (10⁻¹¹ – 10⁻⁸ m)
- **Produced by:** Bombarding a metal target with high-energy electrons in an **X-ray tube** (discovered by **Wilhelm Röntgen in 1895**)
- **Highly penetrating** — can pass through soft tissues but are absorbed by dense materials like bone and metals.

### 14.2 Uses of X-Rays ⭐

1. **Medical Diagnosis (Radiography):** X-rays pass through soft tissue but are blocked by bones → creates images of bones and internal organs.
2. **CT Scans:** Computerised X-ray imaging of internal organs.
3. **Cancer Treatment (Radiotherapy):** High-energy X-rays can destroy cancer cells.
4. **Industrial Use:** Detecting cracks and defects in metal structures (non-destructive testing).
5. **Security Screening:** Baggage scanners at airports.
6. **Crystal Structure Analysis:** X-ray crystallography — used to determine the structure of DNA, proteins.

### 14.3 Harmful Effects

- X-rays can **damage living cells** and cause **mutations**.
- Overexposure leads to **radiation sickness** and increased risk of cancer.
- Hence doctors and radiographers wear **lead aprons** for protection (lead absorbs X-rays).

> 📝 **Board Exam:** "Who discovered X-rays?" → **Wilhelm Röntgen** in **1895**. He also won the first Nobel Prize in Physics (1901) for this discovery.

---

## 15. Gamma Rays

### 15.1 Properties and Details ⭐

- **Frequency:** > 10¹⁹ Hz (highest frequency in EM spectrum)
- **Wavelength:** < 0.01 nm = 10⁻¹¹ m (shortest wavelength in EM spectrum)
- **Produced by:** **Radioactive nuclei** (nuclear transitions); cosmic ray interactions
- **Most penetrating** of all EM waves
- Carries the **highest energy** of all EM waves

### 15.2 Uses of Gamma Rays ⭐

1. **Cancer Treatment (Radiotherapy):** "Gamma knife" surgery destroys tumours.
2. **Sterilisation:** Sterilising medical equipment and food (gamma irradiation).
3. **Nuclear Reactions:** Emitted in nuclear fission and fusion.
4. **Astronomy:** Gamma-ray telescopes study neutron stars, pulsars, and black holes.
5. **Industrial Thickness Gauging:** Measure thickness of materials.

### 15.3 Harmful Effects

- Gamma rays are **extremely dangerous** to living tissue.
- Can cause **radiation burns**, **cancer**, **genetic mutations**, and **death** at high doses.
- Nuclear reactor workers and radiologists use **lead shielding** for protection.

---

## 16. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| I_d = ε₀ (dΦ_E/dt) | Displacement current | A (Ampere) |
| c = 1/√(μ₀ε₀) | Speed of EM wave in vacuum | m/s |
| c = 3 × 10⁸ m/s | Speed of light | m/s |
| c = νλ | Wave equation | — |
| E₀ = c B₀ | Relation between E and B amplitudes | — |
| E₀/B₀ = c | Ratio of field amplitudes | m/s |
| v = c/n | Speed in a medium | m/s |
| v = 1/√(με) = c/√(εᵣμᵣ) | Speed in medium | m/s |
| μ₀ = 4π × 10⁻⁷ T·m/A | Permeability of free space | T·m/A |
| ε₀ = 8.85 × 10⁻¹² C² N⁻¹ m⁻² | Permittivity of free space | C² N⁻¹ m⁻² |

---

## 17. Board Exam Questions with Answers

### Part A — 2-Mark Questions

---

**Q1. What is displacement current? Give its formula.**

**Answer:**
Displacement current is the current that arises in a region due to the rate of change of electric flux (or electric field). It is not due to actual movement of charges but is equivalent to a conduction current in its magnetic effect.

**Formula:**
```
I_d = ε₀ × (dΦ_E/dt)
```

Where ε₀ = 8.85 × 10⁻¹² C² N⁻¹ m⁻² and dΦ_E/dt is the rate of change of electric flux.

---

**Q2. What was the inconsistency in Ampere's Circuital Law and how did Maxwell remove it?**

**Answer:**
Ampere's original law ∮ B·dl = μ₀I was inconsistent for circuits with capacitors. Applying it to different surfaces bounded by the same loop gave contradictory results — a magnetic field through one surface but zero through another.

Maxwell resolved this by adding a new term called **displacement current** to Ampere's Law:
```
∮ B · dl = μ₀ (I_c + ε₀ dΦ_E/dt)
```

This made the law consistent for all cases.

---

**Q3. Write two properties of electromagnetic waves.**

**Answer:**
1. Electromagnetic waves are **transverse waves** — the electric and magnetic fields oscillate perpendicular to each other and to the direction of propagation.
2. EM waves do **not require a medium** — they can travel through vacuum at a speed of c = 3 × 10⁸ m/s.

---

**Q4. What is the relationship between electric field and magnetic field amplitudes in an EM wave?**

**Answer:**
In an electromagnetic wave, the amplitudes of the electric field (E₀) and magnetic field (B₀) are related by:
```
E₀ / B₀ = c = 3 × 10⁸ m/s
```

Where c is the speed of light in vacuum. The two fields are always in phase.

---

**Q5. Name the EM waves used in (a) TV remote controls (b) medical imaging of bones.**

**Answer:**
- (a) TV remote controls → **Infrared waves**
- (b) Medical imaging of bones → **X-rays**

---

### Part B — 3-Mark Questions

---

**Q6. Explain how Maxwell predicted the speed of electromagnetic waves. What was the significance of his result?**

**Answer:**
Maxwell derived the speed of EM waves purely from the fundamental constants of electromagnetism using his equations:

```
c = 1 / √(μ₀ε₀)
```

Substituting:
- μ₀ = 4π × 10⁻⁷ T·m/A
- ε₀ = 8.85 × 10⁻¹² C² N⁻¹ m⁻²

This gives: c = 3 × 10⁸ m/s

**Significance:** This was exactly equal to the experimentally measured speed of light! This proved that **light itself is an electromagnetic wave** — a revolutionary discovery that unified the theories of electricity, magnetism, and optics.

---

**Q7. Write the complete electromagnetic spectrum in order of increasing frequency. Give one use of each type.**

**Answer:**

| EM Wave | Increasing Frequency | One Use |
|---|---|---|
| Radio Waves | Lowest frequency | Radio broadcasting |
| Microwaves | ↑ | Radar, microwave ovens |
| Infrared Rays | ↑ | TV remote controls |
| Visible Light | ↑ | Human vision |
| Ultraviolet Rays | ↑ | Sterilisation |
| X-Rays | ↑ | Medical bone imaging |
| Gamma Rays | Highest frequency | Cancer treatment |

---

**Q8. Derive the expression for displacement current in a capacitor being charged.**

**Answer:**

Let a capacitor with plate area A be charged. Let q be the charge on the capacitor plates at any instant.

The electric field between the plates (by Gauss's Law):
```
E = q / (ε₀A)
```

Electric flux between the plates:
```
Φ_E = E × A = q / ε₀
```

Rate of change of electric flux:
```
dΦ_E/dt = (1/ε₀) × dq/dt = I_c / ε₀
```

Therefore, displacement current:
```
I_d = ε₀ × dΦ_E/dt = ε₀ × (I_c / ε₀) = I_c
```

**This proves that the displacement current between the capacitor plates equals the conduction current in the connecting wires**, maintaining continuity of current.

---

### Part C — 5-Mark Questions

---

**Q9. (a) What are electromagnetic waves? (b) Write their important properties. (c) Give the complete EM spectrum with sources and uses.**

**Answer:**

**(a) Definition:**
An electromagnetic wave is a wave consisting of oscillating, mutually perpendicular electric (E) and magnetic (B) fields, both perpendicular to the direction of propagation.

**(b) Important Properties:**
1. Transverse in nature — E ⊥ B ⊥ direction of propagation.
2. Travel through vacuum at c = 3 × 10⁸ m/s.
3. Do not require a medium.
4. E and B oscillate in phase; E₀/B₀ = c.
5. Carry energy and momentum.
6. Can be polarised.
7. Speed in vacuum is related to fundamental constants: c = 1/√(μ₀ε₀).

**(c) EM Spectrum:**

| Wave | Source | Use |
|---|---|---|
| Radio | Oscillating circuits | Broadcasting |
| Microwave | Magnetron tube | Radar, oven |
| Infrared | Hot bodies | Remote controls |
| Visible | Excited atoms | Vision |
| Ultraviolet | Sun, arc lamps | Sterilisation |
| X-Ray | X-ray tubes | Medical imaging |
| Gamma | Radioactive nuclei | Cancer therapy |

---

### Part D — Numericals

---

**Q10. In an EM wave, the electric field amplitude is E₀ = 120 N/C. Find the amplitude of the magnetic field.**

**Solution:**
```
B₀ = E₀ / c = 120 / (3 × 10⁸) = 4 × 10⁻⁷ T = 400 nT
```

**Answer: B₀ = 4 × 10⁻⁷ T**

---

**Q11. The magnetic field in an EM wave is B = 2 × 10⁻⁷ sin(0.5 × 10³ x + 1.5 × 10¹¹ t) T. Find (a) frequency (b) wavelength (c) electric field amplitude.**

**Solution:**

Comparing with B = B₀ sin(kx + ωt):

- k = 0.5 × 10³ m⁻¹ → λ = 2π/k = 2π / (0.5 × 10³) = 1.26 × 10⁻² m ≈ 1.26 cm
- ω = 1.5 × 10¹¹ rad/s → ν = ω/2π = 1.5 × 10¹¹ / (2π) ≈ 2.39 × 10¹⁰ Hz
- B₀ = 2 × 10⁻⁷ T → E₀ = c × B₀ = 3 × 10⁸ × 2 × 10⁻⁷ = 60 N/C

**Answers: (a) ν ≈ 2.39 × 10¹⁰ Hz (b) λ ≈ 1.26 cm (c) E₀ = 60 N/C**

---

**Q12. Calculate the displacement current between the plates of a capacitor if the electric flux between the plates is changing at the rate of 1.5 × 10¹³ V·m/s.**

**Solution:**
```
I_d = ε₀ × dΦ_E/dt = 8.85 × 10⁻¹² × 1.5 × 10¹³
    = 8.85 × 1.5 × 10 = 132.75 × 10⁻¹ ≈ 0.133 A
```

**Answer: I_d ≈ 0.133 A**

---

## 18. Objective / MCQ Questions

**Q1. Electromagnetic waves are produced by:**
- (a) A stationary charge
- (b) A uniformly moving charge
- **(c) An accelerating charge ✓**
- (d) A charge at rest in a magnetic field

---

**Q2. Which of the following EM waves has the highest frequency?**
- (a) Radio waves
- (b) X-rays
- **(c) Gamma rays ✓**
- (d) Ultraviolet

---

**Q3. In an EM wave, the electric field and magnetic field are:**
- (a) Parallel to each other
- (b) Anti-parallel to each other
- **(c) Perpendicular to each other ✓**
- (d) At 45° to each other

---

**Q4. Displacement current arises due to:**
- (a) Flow of electrons
- (b) Flow of protons
- **(c) Changing electric field ✓**
- (d) Constant magnetic field

---

**Q5. The speed of electromagnetic waves in vacuum is:**
- **(a) 3 × 10⁸ m/s ✓**
- (b) 3 × 10⁶ m/s
- (c) 3 × 10¹⁰ m/s
- (d) 3 × 10⁴ m/s

---

**Q6. The formula c = 1/√(μ₀ε₀) was given by:**
- (a) Hertz
- (b) Faraday
- **(c) Maxwell ✓**
- (d) Ampere

---

**Q7. Microwaves are used in radar because:**
- (a) They have large wavelength
- (b) They are visible to the eye
- **(c) They can be reflected by metallic objects ✓**
- (d) They travel slowly

---

**Q8. Ozone layer in the atmosphere absorbs:**
- (a) Infrared rays
- (b) X-rays
- **(c) Ultraviolet rays ✓**
- (d) Gamma rays

---

**Q9. Which of these EM waves is used in TV remotes?**
- (a) Radio waves
- (b) Microwaves
- **(c) Infrared waves ✓**
- (d) X-rays

---

**Q10. The ratio E₀/B₀ in an electromagnetic wave equals:**
- (a) ε₀
- (b) μ₀
- **(c) c (speed of light) ✓**
- (d) 1/c

---

**Q11. Electromagnetic waves discovered experimentally first by:**
- **(a) Hertz ✓**
- (b) Maxwell
- (c) Faraday
- (d) Einstein

---

**Q12. X-rays were discovered by:**
- (a) Maxwell
- (b) Hertz
- **(c) Röntgen ✓**
- (d) Becquerel

---

**Q13. The wavelength of visible light ranges from approximately:**
- (a) 10 nm to 100 nm
- **(b) 400 nm to 700 nm ✓**
- (c) 1 mm to 10 mm
- (d) 0.1 nm to 10 nm

---

**Q14. Which EM wave has wavelength just greater than visible red light?**
- (a) Ultraviolet
- (b) Gamma rays
- **(c) Infrared ✓**
- (d) X-rays

---

**Q15. In a region of space, if the electric flux is changing at dΦ/dt = 10⁶ V·m/s, the displacement current is approximately:**
- (a) 10⁶ A
- (b) 10⁻⁶ A
- **(c) 8.85 × 10⁻⁶ A ✓** [= ε₀ × dΦ/dt = 8.85×10⁻¹² × 10⁶]
- (d) Zero

---

## 19. Quick Revision Tips

### ⭐ Top 5 Most Important Topics for Bihar Board

| Rank | Topic | Expected Marks |
|---|---|---|
| 1 | Displacement Current — definition, formula, derivation | 2–3 marks |
| 2 | Electromagnetic Spectrum — table of all waves, uses | 3 marks |
| 3 | Properties of EM Waves | 2–3 marks |
| 4 | Speed of EM waves — c = 1/√(μ₀ε₀) | 1–2 marks |
| 5 | Uses of specific EM waves (IR, UV, X-ray, Gamma) | 2 marks |

---

### 📝 Key Formulas to Memorise

```
1.  I_d = ε₀ × dΦ_E/dt          [Displacement current]
2.  c = 1/√(μ₀ε₀) = 3 × 10⁸ m/s  [Speed of EM wave]
3.  c = νλ                         [Wave equation]
4.  E₀ / B₀ = c                    [E-B relation in EM wave]
5.  v = c/n = c/√(εᵣμᵣ)           [Speed in medium]
```

---

### 🧠 EM Spectrum Quick Memory Table

```
INCREASING FREQUENCY →
Radio | Micro | Infrared | Visible | UV | X-ray | Gamma

INCREASING WAVELENGTH →
Gamma | X-ray | UV | Visible | Infrared | Micro | Radio

VISIBLE LIGHT (VIBGYOR):
Violet → Indigo → Blue → Green → Yellow → Orange → Red
(↑ freq, ↓ λ)                              (↓ freq, ↑ λ)
```

---

### 🔑 One-Line Facts (For Last-Minute Revision)

- **Maxwell** predicted EM waves theoretically; **Hertz** verified them experimentally.
- **X-rays** discovered by **Röntgen** (1895).
- All EM waves travel at **c = 3 × 10⁸ m/s** in vacuum.
- EM waves are **transverse** — E ⊥ B ⊥ direction of travel.
- **Ozone layer** absorbs **UV** radiation from Sun.
- **Infrared** = heat waves; strongly absorbed by atmosphere.
- **Gamma rays** have highest frequency and energy; most penetrating.
- **Radio waves** have lowest frequency; largest wavelength.
- **Microwave oven** works at 2.45 GHz — resonates with water molecules.
- Displacement current = ε₀ × (rate of change of electric flux) — NOT a real current.
- Maxwell modified Ampere's Law by adding **displacement current** term.

---

### ✅ Chapter Summary Flowchart

```
PROBLEM: Ampere's Law was inconsistent
        ↓
MAXWELL added displacement current: I_d = ε₀ dΦ_E/dt
        ↓
New Ampere's Law: ∮ B·dl = μ₀(I_c + I_d)
        ↓
This means: Changing E produces B, Changing B produces E
        ↓
RESULT: Self-sustaining wave → ELECTROMAGNETIC WAVE
        ↓
Speed: c = 1/√(μ₀ε₀) = 3 × 10⁸ m/s = Speed of LIGHT
        ↓
CONCLUSION: Light is an electromagnetic wave!
        ↓
All EM waves form the ELECTROMAGNETIC SPECTRUM
(Radio → Microwave → IR → Visible → UV → X-ray → Gamma)
```

---

> 💡 **Final Board Exam Strategy for This Chapter:**
> 1. Learn the statement and formula of **displacement current** — 2 to 3 marks guaranteed.
> 2. Memorise the **complete EM spectrum table** (frequency, wavelength, source, uses) — 3 marks guaranteed.
> 3. Know the formula **c = 1/√(μ₀ε₀)** and what it signifies.
> 4. Practice at least 2–3 numericals on E₀/B₀ = c and displacement current calculations.
> 5. This chapter is small but very scoring — **never skip it!**

---
*📘 Bihar Board Class 12 Physics | Chapter 8 — Electromagnetic Waves | NCERT Based*
*Prepared for BSEB students targeting full marks in board examinations.*