# 📘 Class 12 Physics — Chapter 14: Semiconductor Electronics: Materials, Devices and Simple Circuits
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Classification of Materials: Energy Bands](#2-classification-of-materials-energy-bands)
3. [Semiconductors — Intrinsic and Extrinsic](#3-semiconductors--intrinsic-and-extrinsic)
4. [p-n Junction Diode](#4-p-n-junction-diode)
5. [Diode as a Rectifier](#5-diode-as-a-rectifier)
6. [Special Purpose Diodes](#6-special-purpose-diodes)
7. [Junction Transistor](#7-junction-transistor)
8. [Transistor as an Amplifier (CE Configuration)](#8-transistor-as-an-amplifier-ce-configuration)
9. [Transistor as a Switch](#9-transistor-as-a-switch)
10. [Logic Gates](#10-logic-gates)
11. [Important Formulas Summary](#11-important-formulas-summary)
12. [Board Exam Questions with Answers](#12-board-exam-questions-with-answers)
13. [Objective / MCQ Questions](#13-objective--mcq-questions)
14. [Quick Revision Tips](#14-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is the **starting point of Modern Electronics** — the study of semiconductor materials and the devices built from them.

Think of it this way:
- Your smartphone has billions of tiny switches inside a chip. **How?** → Because of **transistors** made from semiconductors.
- A solar panel converts sunlight to electricity. **How?** → Because of **p-n junction** action.
- LED bulbs glow with very little power. **How?** → Because of **semiconductor diodes** that emit light.
- Your TV remote sends signals using infrared. **How?** → Because of **photodiodes** and **LEDs**.

This chapter answers all these questions scientifically.

**What you will learn:**
- How conductors, insulators and semiconductors differ (Energy Band Theory)
- Intrinsic and Extrinsic semiconductors (n-type and p-type)
- p-n Junction diode — forward and reverse bias
- Rectifiers (Half-wave and Full-wave)
- Special purpose diodes: Zener, LED, Photodiode, Solar Cell
- Transistor — action, amplifier, switch
- Logic Gates — AND, OR, NOT, NAND, NOR, XOR

---

## 2. Classification of Materials: Energy Bands

### 2.1 Energy Bands in Solids

When atoms combine to form a solid, their individual energy levels **split and broaden** into bands of allowed energies.

The two most important bands are:
- **Valence Band:** The highest energy band that is filled with electrons at 0 K. Electrons here are tightly bound.
- **Conduction Band:** The next higher energy band. Electrons here are free to move and conduct electricity.
- **Forbidden Gap (Energy Gap, Eg):** The gap between valence band and conduction band where no electron can exist.

### 2.2 Classification Based on Energy Bands ⭐ (Board Exam — 3 Mark)

| Property | Conductors (Metals) | Semiconductors | Insulators |
|---|---|---|---|
| Energy gap (Eg) | 0 (bands overlap) | 0 to 3 eV (small) | > 3 eV (very large) |
| Resistivity | 10⁻² to 10⁻⁸ Ω·m | 10⁻⁵ to 10⁶ Ω·m | > 10⁸ Ω·m |
| Conductivity | Very high | Intermediate | Very low |
| Examples | Cu, Ag, Al | Si, Ge, GaAs | Glass, Rubber, Diamond |
| At room temp | Many free electrons | Few free electrons | Almost no free electrons |

**For Semiconductors:**
- Silicon (Si): Eg = **1.1 eV**
- Germanium (Ge): Eg = **0.7 eV**
- Diamond (Insulator): Eg = **5.4 eV**

### 2.3 Energy Band Diagrams

```
CONDUCTOR:              SEMICONDUCTOR:          INSULATOR:
  CB overlaps VB          CB                      CB
  ___________           ---------               ---------
  ___________           Eg ~ 1 eV               Eg > 3 eV
 (overlap)              ---------               ---------
  ___________             VB                      VB

CB = Conduction Band,  VB = Valence Band
```

> 📝 **Board Exam Note:** Draw all three band diagrams. This is a very common 3-mark diagram question.

---

## 3. Semiconductors — Intrinsic and Extrinsic

### 3.1 Intrinsic Semiconductors ⭐ (Very Important)

**Definition:** *"A pure semiconductor, without any added impurity, is called an intrinsic semiconductor."*

- At absolute zero (0 K): Acts as a perfect insulator (no free electrons).
- At room temperature: Some electrons get enough thermal energy to jump to the conduction band.
- For every electron that moves to CB, a **hole** (vacancy) is created in VB.

**Key fact:**
```
Number of electrons (n) = Number of holes (p) = nᵢ
```
Where `nᵢ` = intrinsic carrier concentration.

**Mass Action Law:**
```
n × p = nᵢ²
```
This holds for both intrinsic and extrinsic semiconductors.

**Charge carriers in intrinsic semiconductor:**
- **Electrons** in the conduction band (negative charge carriers)
- **Holes** in the valence band (positive charge carriers, i.e., absence of electron)

> 💡 **Remember:** A "hole" is NOT a particle. It is the absence of an electron that behaves like a positive charge carrier.

### 3.2 Extrinsic Semiconductors (Doped Semiconductors) ⭐⭐

**Definition:** *"A semiconductor doped with a small quantity of suitable impurity to increase its conductivity is called an extrinsic semiconductor."*

The process of adding impurity is called **doping**.

#### 3.2.1 n-type Semiconductor ⭐⭐

- Formed by doping pure Si or Ge with **pentavalent (Group 15)** impurity atoms.
- **Dopants:** Phosphorus (P), Arsenic (As), Antimony (Sb) — also called **donor impurities**
- Each donor atom provides **one extra (free) electron** to the crystal.

```
Si — Si — Si
|    |    |
Si — P  — Si   → P has 5 valence electrons, 4 bond with Si, 1 is FREE
|    |    |
Si — Si — Si
```

**In n-type:**
- **Majority carriers = Electrons**
- **Minority carriers = Holes**
- The semiconductor is **electrically neutral** overall (despite extra electrons, the dopant atoms are neutral).

#### 3.2.2 p-type Semiconductor ⭐⭐

- Formed by doping pure Si or Ge with **trivalent (Group 13)** impurity atoms.
- **Dopants:** Boron (B), Aluminium (Al), Indium (In) — also called **acceptor impurities**
- Each acceptor atom creates a **hole** (one electron short).

```
Si — Si — Si
|    |    |
Si — B  — Si   → B has 3 valence electrons, all 3 bond with Si, 1 bond is INCOMPLETE = HOLE
|    |    |
Si — Si — Si
```

**In p-type:**
- **Majority carriers = Holes**
- **Minority carriers = Electrons**

### 3.3 Comparison: Intrinsic vs Extrinsic

| Property | Intrinsic | n-type | p-type |
|---|---|---|---|
| Purity | Pure | Doped with pentavalent | Doped with trivalent |
| Majority carriers | e⁻ = holes | Electrons | Holes |
| Minority carriers | — | Holes | Electrons |
| Conductivity | Low | Higher | Higher |
| Dopant name | — | Donor | Acceptor |

> 📝 **Board Exam Note:** "n-type semiconductor has more electrons but the material is electrically neutral." — This is a common MCQ trap. The answer is YES, it is neutral because the donor atoms (which have become ions) provide the balancing positive charge.

---

## 4. p-n Junction Diode

### 4.1 Formation of p-n Junction ⭐⭐ (Board Exam — 3-5 Marks)

When p-type and n-type semiconductors are joined together, a **p-n junction** is formed.

**What happens at the junction:**

1. Electrons from n-side **diffuse** across to p-side (high concentration → low concentration).
2. Holes from p-side **diffuse** across to n-side.
3. Near the junction, electrons and holes **recombine** and disappear.
4. This creates a **depletion region** — a thin region with no mobile charge carriers.
5. The depletion region has:
   - **Positive ions** on the n-side (donor atoms that lost their electron)
   - **Negative ions** on the p-side (acceptor atoms that gained an electron)
6. This creates a **built-in electric field** pointing from n to p.
7. The built-in field opposes further diffusion — **equilibrium** is reached.
8. This built-in potential difference is called **potential barrier (V₀)**.
   - For Si: V₀ ≈ 0.7 V
   - For Ge: V₀ ≈ 0.3 V

```
p-side      Depletion region      n-side
  [+ + + | − − | + + +]
  holes       ↑          electrons
         Built-in field
         ←←←←←←←←←←
         (n to p direction)
```

### 4.2 Forward Bias ⭐⭐

**Definition:** When the **positive terminal** of the battery is connected to the **p-side** and **negative terminal** to the **n-side**, the diode is said to be in **forward bias**.

**What happens:**
- The external field opposes the built-in field.
- Depletion layer **becomes thinner**.
- Potential barrier **decreases**.
- When applied voltage > threshold voltage (0.7 V for Si, 0.3 V for Ge), **current flows easily**.

**Result:** Low resistance, **large current** flows. Diode is **ON**.

### 4.3 Reverse Bias ⭐⭐

**Definition:** When the **negative terminal** of the battery is connected to the **p-side** and **positive terminal** to the **n-side**, the diode is said to be in **reverse bias**.

**What happens:**
- The external field adds to the built-in field.
- Depletion layer **becomes thicker**.
- Potential barrier **increases**.
- Only a very small **reverse saturation current** (due to minority carriers) flows.

**Result:** Very high resistance, **almost no current** flows. Diode is **OFF**.

> 💡 **Analogy:** A diode is like a one-way valve (check valve) for current. Current flows easily in one direction (forward), but is blocked in the other (reverse).

### 4.4 V-I Characteristics of a Diode ⭐⭐ (Important Diagram Question)

```
     I (mA)
     |         Forward bias
     |        /
     |       /
     |      /  ← Knee voltage (Si = 0.7V, Ge = 0.3V)
     |     /
 ----+----/--------→ V (Volts)
  ←  |  →
 Reverse|Forward
 bias  |
     |
   (very small)
   reverse
   saturation
   current (μA)
         ↓
    Zener/Breakdown
    voltage
```

**Key Points:**
- In forward bias: Current increases exponentially beyond knee voltage.
- In reverse bias: Very tiny reverse saturation current until **breakdown voltage** is reached.
- **Dynamic resistance** = ΔV / ΔI

---

## 5. Diode as a Rectifier

### 5.1 What is Rectification?

**Definition:** *"The process of converting alternating current (AC) into direct current (DC) is called rectification."*

A diode allows current in only one direction, so it can convert AC to DC.

### 5.2 Half-Wave Rectifier ⭐⭐ (Board Exam — 3-5 Marks)

**Circuit:** Single diode + load resistor (RL) in series.

**Working:**
- **Positive half cycle:** Diode is in forward bias → conducts → current flows through RL.
- **Negative half cycle:** Diode is in reverse bias → does not conduct → no current through RL.

**Output:** Pulsating DC — only positive half cycles appear.

```
Input AC:                    Output (Half-wave):
  /\    /\                     /\         /\
 /  \  /  \      Diode        /  \       /  \
/    \/    \   ------→       /    \     /    \
             (blocks -ve)        \_____/     \_____
```

**Output frequency = Input frequency**

If input frequency = 50 Hz → Output frequency = 50 Hz

**Efficiency of half-wave rectifier = 40.6%**

### 5.3 Full-Wave Rectifier ⭐⭐⭐ (Most Important — 5 Marks)

**Circuit:** Two diodes (D₁ and D₂) + centre-tapped transformer + load resistor (RL).

**Working:**
- **Positive half cycle:** D₁ conducts, D₂ blocked → current through RL in one direction.
- **Negative half cycle:** D₂ conducts, D₁ blocked → current through RL in **same direction**.

**Output:** Pulsating DC — both half cycles are used.

```
Input AC:                    Output (Full-wave):
  /\    /\                     /\    /\    /\
 /  \  /  \      Two Diodes   /  \  /  \  /  \
/    \/    \   ------→       /    \/    \/    \
```

**Output frequency = 2 × Input frequency**

If input frequency = 50 Hz → Output frequency = 100 Hz

**Efficiency of full-wave rectifier = 81.2%**

### 5.4 Comparison: Half-Wave vs Full-Wave Rectifier

| Property | Half-Wave | Full-Wave |
|---|---|---|
| Number of diodes | 1 | 2 |
| Output cycles | Only +ve half | Both halves |
| Output frequency | = Input freq | 2 × Input freq |
| Efficiency | 40.6% | 81.2% |
| Ripple factor | 1.21 | 0.48 |
| DC output | Lower | Higher |

> 📝 **Board Exam Tip:** Draw both circuits clearly with the transformer. Label D₁, D₂, RL, and the centre tap. The diagram is often asked for 3-5 marks.

---

## 6. Special Purpose Diodes

### 6.1 Zener Diode ⭐⭐⭐ (Very Important — Board Exam)

**Definition:** *"A Zener diode is a specially made p-n junction diode designed to operate in the reverse breakdown region without getting damaged."*

**Symbol:**
```
     ──|<|──    (like normal diode but with bent ends on the bar)
```

**Working:**
- Heavily doped diode → very thin depletion layer.
- In reverse bias, at a specific voltage called **Zener voltage (Vz)**, the current increases sharply.
- This Zener voltage remains **constant** even if current changes.

**Zener Breakdown Mechanisms:**
1. **Zener Effect:** In heavily doped diodes (low Vz < 4V) — due to tunnelling of electrons.
2. **Avalanche Effect:** In lightly doped diodes (high Vz > 6V) — due to collision ionisation.

**Zener Diode as Voltage Regulator:** ⭐⭐ (5-Mark Derivation)

The Zener maintains a **constant output voltage** across the load even when:
- Input voltage changes, OR
- Load resistance changes

**Circuit:**

```
        Rs (series resistor)
Vin ──┬──[Rs]──┬── Vout
      |         |
      |        [RL]   (Load)
      |     ───|<|───  (Zener diode in reverse bias)
      |         |
     GND       GND
```

**Key equations:**
```
Vin = VRs + Vz
VRs = Vin − Vz
Is  = (Vin − Vz) / Rs      (Total current through series resistor)
IL  = Vz / RL              (Load current)
Iz  = Is − IL              (Zener current)
```

**Condition for regulation:** Iz must remain between Iz(min) and Iz(max).

> 📝 **Note:** When Vin increases → Is increases → extra current is taken by Zener (Iz increases) → Vout remains Vz. This is how it regulates.

### 6.2 Light Emitting Diode (LED) ⭐⭐

**Definition:** *"An LED is a p-n junction diode that emits light when forward biased."*

**Working:**
- When forward biased, electrons from n-side recombine with holes in p-side.
- During recombination, energy is released in the form of **photons (light)**.
- The wavelength of light depends on the **energy gap** of the semiconductor.

**Materials and Colors:**

| Material | Color |
|---|---|
| GaAs | Infrared |
| GaAs₁₋ₓPₓ | Red / Yellow |
| GaP | Green |
| GaN | Blue |
| SiC | Yellow |

**Advantages of LEDs:**
1. Low power consumption
2. Long life (10,000+ hours)
3. Fast switching speed
4. No warm-up time
5. Available in various colors
6. Small size, rugged

**Disadvantages:**
1. Require precise voltage/current control
2. Sensitive to temperature
3. Initially expensive (though cost has dropped)

### 6.3 Photodiode ⭐⭐

**Definition:** *"A photodiode is a p-n junction diode used to detect light (optical signals). It is operated in reverse bias."*

**Working:**
- In reverse bias, normally very little current flows.
- When **light falls** on the junction, photons excite electrons, creating electron-hole pairs.
- These minority carriers increase the reverse current (called **photocurrent**).
- Photocurrent is proportional to the **intensity of incident light**.

**V-I Characteristics:**
```
     I
     |
     |   Increasing light intensity
     |   I₃ > I₂ > I₁
─────+──────────────────→ V (Reverse bias voltage)
  I₃ |
  I₂ |
  I₁ |
     | (Reverse saturation currents at different light intensities)
```

**Applications:** Optical communication, solar cells, light meters, burglar alarms.

### 6.4 Solar Cell ⭐

**Definition:** *"A solar cell is a p-n junction that converts solar energy (light energy) directly into electrical energy."*

**Working:**
- Similar to a photodiode, but designed to work without any external battery.
- When sunlight falls on the junction, electron-hole pairs are generated.
- The built-in electric field separates them: electrons to n-side, holes to p-side.
- This creates a **potential difference (emf)** across the junction.
- When a load is connected, **current flows** — this is the **photovoltaic effect**.

**Materials used:**
- Si (most common), GaAs (most efficient), CdS, InP

**I-V Characteristic of Solar Cell:**
```
     I (mA)
     |
     |_______________
     |               \
     |                \
─────+──────────────────→ V
     |            Voc (open circuit voltage)
    Isc
(short circuit current)
```

- **Open circuit voltage (Voc):** Voltage when no current is drawn.
- **Short circuit current (Isc):** Current when output is short-circuited.

> 📝 **Key Difference:** Photodiode is used in **reverse bias** to detect light. Solar cell uses **no external bias** and generates its own voltage.

---

## 7. Junction Transistor

### 7.1 Introduction ⭐⭐⭐ (Very Important — 5 Marks)

**Definition:** *"A transistor is a three-terminal semiconductor device formed by sandwiching one type of semiconductor between two layers of the other type."*

**Two types:**
- **n-p-n Transistor:** n-type | p-type | n-type
- **p-n-p Transistor:** p-type | n-type | p-type

**Three regions:**
1. **Emitter (E):** Heavily doped, medium size. Emits majority carriers.
2. **Base (B):** Very lightly doped, very thin. Controls current flow.
3. **Collector (C):** Moderately doped, largest size. Collects carriers from emitter.

**Symbols:**

```
n-p-n Transistor:          p-n-p Transistor:

    C                           C
    |                           |
B ──┤                       B ──┤
    |→ (arrow on emitter)        |← (arrow on emitter, pointing in)
    E                           E

Arrow on emitter always points from p to n.
For n-p-n: arrow points OUT from base to emitter.
For p-n-p: arrow points IN from emitter to base.
```

### 7.2 Biasing of Transistor ⭐⭐

For a transistor to work as an **amplifier**:
- **Emitter-Base (EB) junction:** Forward biased (small voltage)
- **Collector-Base (CB) junction:** Reverse biased (large voltage)

### 7.3 Transistor Action (Working of n-p-n Transistor) ⭐⭐

1. Emitter is forward biased → large number of electrons flow from emitter to base.
2. Base is very thin and lightly doped → very few electrons recombine with holes in base.
3. Typically **only 2-5% of electrons** recombine in base (form base current IB).
4. The remaining **95-98% of electrons** are swept across to the collector by reverse bias.
5. This forms the large **collector current IC**.

**Current relationship:**
```
IE = IB + IC
```

Where:
- IE = Emitter current (largest)
- IB = Base current (smallest, typically μA)
- IC = Collector current (nearly equal to IE, in mA)

### 7.4 Transistor Configurations

| Configuration | Input | Output | Application |
|---|---|---|---|
| Common Base (CB) | Emitter-Base | Collector-Base | High frequency |
| Common Emitter (CE) | Base-Emitter | Collector-Emitter | **Most used — Amplifier** |
| Common Collector (CC) | Base-Collector | Emitter-Collector | Impedance matching |

> 📝 **Common Emitter (CE) is the most important configuration for Bihar Board.**

### 7.5 Transistor Current Gains ⭐⭐⭐ (Formulas — Board Exam)

**DC Current Gain (α) — Common Base:**
```
α = IC / IE
```
Value of α: 0.95 to 0.99 (always less than 1)

**DC Current Gain (β) — Common Emitter:**
```
β = IC / IB
```
Value of β: 20 to 500 (always greater than 1 — this is why CE is used for amplification)

**Relationship between α and β:**
```
β = α / (1 − α)
α = β / (β + 1)
```

**Also:**
```
IB = IC / β
IE = IC + IB = IC(1 + 1/β) = IC(β+1)/β
```

**AC Current Gain:**
```
βac = ΔIC / ΔIB    (at constant VCE)
αac = ΔIC / ΔIE    (at constant VCB)
```

---

## 8. Transistor as an Amplifier (CE Configuration)

### 8.1 What is Amplification?

**Definition:** *"The process of increasing the amplitude (strength) of a weak signal using a transistor and an external power supply is called amplification."*

The transistor itself does NOT add energy — the extra energy comes from the **DC power supply (VCC)**.

### 8.2 CE Amplifier Circuit ⭐⭐⭐ (5-Mark Derivation — Must Learn!)

**Circuit components:**
- Input signal Vi (AC)
- Base resistor RB
- Collector resistor RC
- DC supply VCC
- Coupling capacitors C₁, C₂ (to block DC, allow AC)

```
           VCC (+)
            |
           [RC] ← Collector resistor
            |
   C₁       C──────────── Output (Vo)
Vi ──||──B──┤ n-p-n
            E
            |
           GND
```

### 8.3 Working of CE Amplifier

1. The DC bias sets the **operating point (Q-point)** — transistor is in active region.
2. The AC input signal (Vi) causes small changes in base current (ΔIB).
3. These cause large changes in collector current (ΔIC = β × ΔIB).
4. This large ΔIC flowing through RC produces large output voltage change (ΔVo = ΔIC × RC).
5. Output voltage is much **larger** than input → **amplification**.

### 8.4 Voltage Gain Derivation ⭐⭐ (Board Exam)

Change in output voltage:
```
ΔVo = −ΔIC × RC       (negative sign because when IC increases, Vo decreases)
```

Change in input voltage:
```
ΔVi = ΔIB × ri
```
Where ri = input resistance of transistor at base.

**Voltage Gain:**
```
        ΔVo     ΔIC × RC     β × RC
Av = − ——— = − ————————— = − ————————
        ΔVi     ΔIB × ri        ri
```

**Magnitude of voltage gain:**
```
|Av| = β × RC / ri
```

**Key formulae:**

| Quantity | Formula |
|---|---|
| Current gain (β) | β = ΔIC / ΔIB |
| Voltage gain | Av = −β(RC/ri) |
| Power gain | Ap = β² × (RC/ri) |

### 8.5 Phase Reversal in CE Amplifier ⭐

In CE amplifier, the output voltage is **180° out of phase** with the input voltage.

- When Vi increases → IB increases → IC increases → voltage drop across RC increases → VCE decreases → Vo decreases.
- So when input goes UP, output goes DOWN → **phase reversal**.

---

## 9. Transistor as a Switch

### 9.1 Working Principle ⭐ (2-3 Marks)

A transistor can be used as an **electronic switch** — either fully ON or fully OFF.

**Two states:**

| State | Base Condition | Transistor Region | Output |
|---|---|---|---|
| **OFF (Open switch)** | VB < 0.6 V (Si) | Cut-off | Vo ≈ VCC (HIGH) |
| **ON (Closed switch)** | VB large (saturated) | Saturation | Vo ≈ 0 V (LOW) |

**Cut-off Region:** IB = 0 → IC ≈ 0 → Transistor is OFF.

**Saturation Region:** IB is large → IC is maximum → Transistor is ON, VCE ≈ 0.

**Key fact:** In switching, the transistor is NOT in the active region (where amplification happens). It is either cut-off or saturated.

**Application:** Digital circuits, logic gates, computers, timers.

---

## 10. Logic Gates

### 10.1 Introduction to Digital Electronics ⭐

Digital electronics deals with signals that have only **two states**:
- **HIGH (1):** Typically +5V
- **LOW (0):** Typically 0V

This is called **binary logic**.

**Boolean Algebra:** The algebra of logic (0 and 1) used to design digital circuits.

### 10.2 Basic Logic Gates ⭐⭐⭐ (Most Important — Board Exam)

#### OR Gate ⭐⭐

**Definition:** Output is HIGH (1) if **ANY** one (or more) input is HIGH.

**Boolean expression:** `Y = A + B`  ('+' means OR)

**Symbol:**
```
A ──┐
    ├─ OR ─── Y
B ──┘
```

**Truth Table:**

| A | B | Y = A + B |
|---|---|---|
| 0 | 0 | **0** |
| 0 | 1 | **1** |
| 1 | 0 | **1** |
| 1 | 1 | **1** |

---

#### AND Gate ⭐⭐

**Definition:** Output is HIGH (1) only if **ALL** inputs are HIGH.

**Boolean expression:** `Y = A · B`  (or Y = AB)

**Symbol:**
```
A ──┐
    ├─ AND ─── Y
B ──┘
```

**Truth Table:**

| A | B | Y = A·B |
|---|---|---|
| 0 | 0 | **0** |
| 0 | 1 | **0** |
| 1 | 0 | **0** |
| 1 | 1 | **1** |

---

#### NOT Gate (Inverter) ⭐⭐

**Definition:** Output is the **complement** (opposite) of input.

**Boolean expression:** `Y = Ā`  (A-bar = NOT A)

**Symbol:**
```
A ── NOT ─○── Y
           (bubble = NOT/inversion)
```

**Truth Table:**

| A | Y = Ā |
|---|---|
| 0 | **1** |
| 1 | **0** |

---

#### NAND Gate ⭐⭐⭐ (Universal Gate — Very Important)

**Definition:** NAND = NOT + AND. Output is LOW only if **ALL** inputs are HIGH. (Opposite of AND)

**Boolean expression:** `Y = A·B̄ = (AB)' `  (A·B with bar on top)

**Symbol:** AND gate with a bubble (circle) at output.

**Truth Table:**

| A | B | A·B | Y = (A·B)' |
|---|---|---|---|
| 0 | 0 | 0 | **1** |
| 0 | 1 | 0 | **1** |
| 1 | 0 | 0 | **1** |
| 1 | 1 | 1 | **0** |

**NAND as a Universal Gate:** Any logic gate (OR, AND, NOT, NOR, etc.) can be built using only NAND gates.

```
NOT using NAND:   A ──┬── NAND ── Y = Ā    (both inputs of NAND tied together)
                      └──┘

AND using NAND:   NAND output → another NAND with both inputs tied = NOT of NAND = AND

OR using NAND:    Use 3 NAND gates
```

---

#### NOR Gate ⭐⭐⭐ (Universal Gate — Very Important)

**Definition:** NOR = NOT + OR. Output is HIGH only if **ALL** inputs are LOW. (Opposite of OR)

**Boolean expression:** `Y = (A + B)'`  (A+B with bar on top)

**Symbol:** OR gate with a bubble at output.

**Truth Table:**

| A | B | A+B | Y = (A+B)' |
|---|---|---|---|
| 0 | 0 | 0 | **1** |
| 0 | 1 | 1 | **0** |
| 1 | 0 | 1 | **0** |
| 1 | 1 | 1 | **0** |

**NOR is also a Universal Gate:** Any logic gate can be built using only NOR gates.

---

#### XOR Gate (Exclusive OR) ⭐

**Definition:** Output is HIGH if inputs are **different** from each other.

**Boolean expression:** `Y = A⊕B = A'B + AB'`

**Truth Table:**

| A | B | Y = A⊕B |
|---|---|---|
| 0 | 0 | **0** |
| 0 | 1 | **1** |
| 1 | 0 | **1** |
| 1 | 1 | **0** |

---

### 10.3 Summary of All Gates ⭐⭐⭐

| Gate | Symbol | Expression | Output HIGH when... |
|---|---|---|---|
| OR | `+` | Y = A + B | Any input is 1 |
| AND | `·` | Y = A·B | ALL inputs are 1 |
| NOT | `'` or bar | Y = A' | Input is 0 |
| NAND | `(·)'` | Y = (A·B)' | NOT all inputs are 1 |
| NOR | `(+)'` | Y = (A+B)' | ALL inputs are 0 |
| XOR | `⊕` | Y = A⊕B | Inputs are DIFFERENT |

---

## 11. Important Formulas Summary

| Formula | Quantity | Unit |
|---|---|---|
| n × p = nᵢ² | Mass action law | m⁻⁶ |
| IE = IB + IC | Current relation | A |
| α = IC / IE | Current gain (CB) | — (< 1) |
| β = IC / IB | Current gain (CE) | — (> 1) |
| β = α / (1−α) | α-β relation | — |
| α = β / (β+1) | β-α relation | — |
| Av = −β(RC/ri) | Voltage gain (CE) | — |
| Ap = β² (RC/ri) | Power gain | — |
| Iz = Is − IL | Zener current | A |
| Is = (Vin−Vz)/Rs | Series resistor current | A |
| Y = A + B | OR gate | — |
| Y = A·B | AND gate | — |
| Y = Ā | NOT gate | — |
| Y = (A·B)' | NAND gate | — |
| Y = (A+B)' | NOR gate | — |
| Y = A⊕B | XOR gate | — |

**Key values to memorise:**

```
Knee voltage (Si) = 0.7 V
Knee voltage (Ge) = 0.3 V
Energy gap Si     = 1.1 eV
Energy gap Ge     = 0.7 eV
Half-wave rectifier efficiency  = 40.6%
Full-wave rectifier efficiency  = 81.2%
Full-wave output frequency      = 2 × input frequency
β range (typical)               = 20 to 500
α range                         = 0.95 to 0.99
```

---

## 12. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What is a semiconductor?**
**Ans:** A material with electrical conductivity between conductors and insulators (resistivity 10⁻⁵ to 10⁶ Ω·m). Examples: Silicon, Germanium.

**Q2. What is doping?**
**Ans:** The process of deliberately adding small amounts of impurity atoms to a pure semiconductor to increase its conductivity is called doping.

**Q3. Name the majority carriers in n-type and p-type semiconductors.**
**Ans:** n-type → Electrons; p-type → Holes.

**Q4. What is a p-n junction?**
**Ans:** A p-n junction is formed when p-type and n-type semiconductors are joined together. A depletion region forms at the junction.

**Q5. What is the knee voltage of silicon diode?**
**Ans:** 0.7 V (for silicon), 0.3 V (for germanium).

**Q6. Name the process of converting AC to DC.**
**Ans:** Rectification.

**Q7. What is an LED?**
**Ans:** An LED (Light Emitting Diode) is a p-n junction diode that emits light when forward biased, due to electron-hole recombination.

**Q8. What is the output frequency of a full-wave rectifier if input frequency is 50 Hz?**
**Ans:** Output frequency = 2 × 50 = **100 Hz**

**Q9. Write the Boolean expression for NAND gate.**
**Ans:** Y = (A·B)'

**Q10. What is the current relation in a transistor?**
**Ans:** IE = IB + IC

**Q11. Why is the base of a transistor made thin and lightly doped?**
**Ans:** So that most of the charge carriers from the emitter pass through the base to the collector without recombining. This ensures large collector current and high current gain.

**Q12. What is a Zener diode used for?**
**Ans:** Zener diode is used as a **voltage regulator** — it maintains a constant output voltage even when input voltage or load changes.

**Q13. What is the direction of conventional current due to holes?**
**Ans:** Holes move from p-side to n-side (from high potential to low potential), so conventional current due to holes is from p to n.

**Q14. What is a universal gate?**
**Ans:** A gate from which any other logic gate can be constructed. NAND and NOR gates are universal gates.

**Q15. State the truth table of NOT gate.**
**Ans:**

| A | Y = A' |
|---|---|
| 0 | 1 |
| 1 | 0 |

---

### 📝 2-Mark Questions

**Q16. Differentiate between intrinsic and extrinsic semiconductors.**

**Ans:**

| Intrinsic | Extrinsic |
|---|---|
| Pure semiconductor | Doped semiconductor |
| n = p = nᵢ | n ≠ p |
| Low conductivity | Higher conductivity |
| Example: Pure Si, Ge | Example: Si doped with P or B |

---

**Q17. What is a depletion region? How does it form?**

**Ans:** Depletion region is the thin region at the p-n junction devoid of free charge carriers (electrons and holes). It forms due to diffusion of electrons from n-side to p-side and holes from p-side to n-side, which recombine near the junction, leaving behind fixed positive and negative ions. This creates a built-in electric field that stops further diffusion.

---

**Q18. Compare forward bias and reverse bias of a diode.**

**Ans:**

| Forward Bias | Reverse Bias |
|---|---|
| +ve terminal to p-side | +ve terminal to n-side |
| Depletion layer thin | Depletion layer wide |
| Low resistance | Very high resistance |
| Large current flows | Negligible current flows |
| Diode is ON | Diode is OFF |

---

**Q19. What is current amplification factor β? Give its typical value.**

**Ans:** β (beta) is the ratio of collector current to base current in common emitter configuration.
```
β = IC / IB
```
Typical value: β = 20 to 500. Since β > 1, a small change in base current produces a large change in collector current — this is the basis of amplification.

---

**Q20. Distinguish between n-type and p-type semiconductors.**

**Ans:**

| n-type | p-type |
|---|---|
| Doped with pentavalent impurity | Doped with trivalent impurity |
| Donor atoms (P, As, Sb) | Acceptor atoms (B, Al, In) |
| Majority carriers: electrons | Majority carriers: holes |
| Minority carriers: holes | Minority carriers: electrons |

---

### 📝 3-Mark Questions

**Q21. Explain Zener diode as a voltage regulator.**

**Ans:**

A Zener diode connected in reverse bias across the output maintains a **constant voltage Vz** across the load.

**Circuit:** Vin → Rs (series resistor) → Output with Zener diode (reverse biased) in parallel with RL.

**Working:**
- If Vin increases: The extra voltage appears across Rs as series drop. The Zener conducts more (Iz increases) but Vout = Vz remains constant.
- If load RL changes: The Zener adjusts its current Iz to keep total current Is = IL + Iz constant.

**Key equations:**
```
Vout = Vz (constant)
Is = (Vin − Vz)/Rs
IL = Vz/RL
Iz = Is − IL
```

---

**Q22. Draw the circuit diagram of a half-wave rectifier and explain its working.**

**Ans:**

**Circuit:**
```
AC Input ── Transformer ──┬──[D₁]──┬── Vout(+)
                          |         |
                          └────────[RL]──── Vout(−)/GND
```

**Working:**
- During **positive half cycle** of AC: Diode D₁ is forward biased → conducts → current through RL → output is +ve.
- During **negative half cycle:** Diode D₁ is reverse biased → does not conduct → no output.

**Result:** Only positive half cycles appear in output — pulsating DC.
**Output frequency = Input frequency (50 Hz)**

---

**Q23. Write the truth tables of AND, OR, and NOT gates.**

**Ans:**

**AND (Y = A·B):**

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

**OR (Y = A+B):**

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

**NOT (Y = A'):**

| A | Y |
|---|---|
| 0 | 1 |
| 1 | 0 |

---

**Q24. Explain why NAND gate is called a universal gate.**

**Ans:** NAND gate is called a universal gate because any other logic gate (AND, OR, NOT, NOR, XOR, etc.) can be built using only NAND gates.

**Realisation:**

- **NOT using NAND:** Connect both inputs of NAND together → Y = (A·A)' = A'
- **AND using NAND:** NOT of NAND → put NAND output into a NOT-NAND → Y = A·B
- **OR using NAND:** Invert each input using NAND, then NAND the results → Y = A + B (using De Morgan's theorem)

This versatility makes NAND the most commonly used gate in digital ICs.

---

### 📝 5-Mark Questions (Long Answer)

**Q25. Derive expressions for voltage gain and current gain of a transistor in CE configuration used as an amplifier.**

**Ans:**

**Circuit:** Input Vi applied between base and emitter through coupling capacitor. Output Vo taken between collector and emitter through coupling capacitor. RC is the load in collector circuit.

**Current Gain:**
```
βac = ΔIC / ΔIB
```

**Output voltage change:**
When ΔIB occurs, it causes:
```
ΔIC = βac × ΔIB
```

Output voltage change (across RC):
```
ΔVo = −ΔIC × RC = −βac × ΔIB × RC
(negative sign: when IC increases, VCE decreases)
```

**Input voltage change:**
```
ΔVi = ΔIB × ri
```
Where ri = input resistance.

**Voltage Gain:**
```
        ΔVo       βac × RC
Av = − ——— = − ————————————
        ΔVi           ri
```

**Power Gain:**
```
Ap = β² × RC / ri
```

**Key points:**
1. |Av| = β(RC/ri) — typically 100 to 1000.
2. Output is 180° out of phase with input (phase reversal).
3. Power gain is very large because Ap = β² × RC/ri.

---

**Q26. With a circuit diagram, explain the working of a full-wave rectifier. What is the output frequency?**

**Ans:**

**Circuit:**

```
        Centre-tap transformer
         A ──[D₁]──┐
         |          ├──[RL]── Output
         O (centre) ┘ (common ground/return)
         |          ┌──[RL]── (same RL, same output line)
         B ──[D₂]──┘
```

(Alternatively: Bridge rectifier uses 4 diodes without centre tap — also acceptable for Bihar Board.)

**Working:**

**Positive half cycle:** Terminal A is +ve → D₁ is forward biased and conducts. Current flows through RL in a specific direction. D₂ is reverse biased, does not conduct.

**Negative half cycle:** Terminal B is +ve (centre tap inverts it) → D₂ is forward biased and conducts. Current flows through RL in the **same direction** as before. D₁ is now reverse biased.

**Output:** Current flows through RL in the **same direction for BOTH half cycles** → pulsating DC with both half cycles.

**Output frequency:**
```
Output frequency = 2 × Input frequency = 2 × 50 = 100 Hz
```

**Efficiency = 81.2%** (compared to 40.6% for half-wave)

---

**Q27. Describe the formation of p-n junction. What is the depletion region and potential barrier?**

**Ans:**

When p-type and n-type semiconductors are brought together:

**Step 1 — Diffusion:** Electrons from n-side (high concentration) diffuse to p-side. Holes from p-side diffuse to n-side.

**Step 2 — Recombination:** Electrons and holes recombine near the junction. This leaves behind:
- Fixed **positive donor ions** on the n-side (near junction)
- Fixed **negative acceptor ions** on the p-side (near junction)

**Step 3 — Depletion region:** The region near the junction is depleted of free charge carriers. Width is typically a few μm.

**Step 4 — Built-in field:** The fixed ions create an electric field pointing from n-side to p-side (n→p). This is the built-in or internal electric field.

**Step 5 — Potential barrier:** The built-in field creates a potential difference (V₀) across the junction that opposes further diffusion.
- Si: V₀ ≈ 0.7 V
- Ge: V₀ ≈ 0.3 V

**Step 6 — Equilibrium:** Diffusion current (due to concentration gradient) = Drift current (due to built-in field). No net current flows — equilibrium is established.

---

**Q28. Write truth tables of NAND and NOR gates. Explain why they are called universal gates.**

**Ans:**

**NAND Gate [Y = (A·B)']:**

| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

**NOR Gate [Y = (A+B)']:**

| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

**Universal Gates:**
Both NAND and NOR are called universal gates because **any Boolean function** and **any logic gate** can be realised using only that one type of gate.

- NAND realises: NOT (1 NAND with tied inputs), AND (2 NANDs), OR (3 NANDs)
- NOR realises: NOT (1 NOR with tied inputs), OR (2 NORs), AND (3 NORs)

This is extremely useful in IC manufacturing — a chip factory needs to make only ONE type of gate!

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** In a transistor, IB = 50 μA and IC = 2 mA. Find (a) β and (b) α.

**Solution:**
```
(a) β = IC / IB = 2×10⁻³ / 50×10⁻⁶ = 40

(b) IE = IB + IC = 50×10⁻⁶ + 2×10⁻³ = 2.05 mA
    α = IC / IE = 2×10⁻³ / 2.05×10⁻³ = 0.976
```
**Answer: β = 40, α = 0.976**

---

**Num 2:** A CE amplifier has β = 100, input resistance ri = 1 kΩ, and RC = 2 kΩ. Find the voltage gain.

**Solution:**
```
Av = −β × RC / ri
   = −100 × 2000 / 1000
   = −200
```
**Answer: Voltage gain = −200 (magnitude 200, 180° phase reversal)**

---

**Num 3:** A Zener diode has Vz = 5 V. The input voltage is 12 V and series resistance Rs = 700 Ω. If load RL = 1 kΩ, find Iz.

**Solution:**
```
IL = Vz / RL = 5 / 1000 = 5 mA
Is = (Vin − Vz) / Rs = (12 − 5) / 700 = 7/700 = 10 mA
Iz = Is − IL = 10 − 5 = 5 mA
```
**Answer: Iz = 5 mA**

---

**Num 4:** The base current changes by 100 μA and collector current changes by 8 mA. Find βac.

**Solution:**
```
βac = ΔIC / ΔIB = 8×10⁻³ / 100×10⁻⁶ = 80
```
**Answer: βac = 80**

---

**Num 5:** In an n-p-n transistor, α = 0.98. If emitter current is 5 mA, find IC and IB.

**Solution:**
```
IC = α × IE = 0.98 × 5 = 4.9 mA
IB = IE − IC = 5 − 4.9 = 0.1 mA
```
**Answer: IC = 4.9 mA, IB = 0.1 mA**

---

**Num 6:** An LED has energy gap Eg = 2 eV. Find the wavelength of emitted light. (h = 6.63×10⁻³⁴ J·s, c = 3×10⁸ m/s)

**Solution:**
```
Eg = 2 eV = 2 × 1.6×10⁻¹⁹ = 3.2×10⁻¹⁹ J

E = hc/λ → λ = hc/E

λ = (6.63×10⁻³⁴ × 3×10⁸) / 3.2×10⁻¹⁹
  = 19.89×10⁻²⁶ / 3.2×10⁻¹⁹
  = 6.22×10⁻⁷ m
  = 622 nm (red light)
```
**Answer: λ ≈ 622 nm (visible red)**

---

## 13. Objective / MCQ Questions

**Q1.** The energy gap in silicon is:
- (a) 0.7 eV
- **(b) 1.1 eV** ✓
- (c) 5.4 eV
- (d) 0 eV

---

**Q2.** In p-type semiconductor, majority carriers are:
- (a) Electrons
- **(b) Holes** ✓
- (c) Protons
- (d) Neutrons

---

**Q3.** Pentavalent impurity added to silicon forms:
- **(a) n-type semiconductor** ✓
- (b) p-type semiconductor
- (c) Intrinsic semiconductor
- (d) Insulator

---

**Q4.** The potential barrier at p-n junction for silicon is approximately:
- (a) 0.3 V
- **(b) 0.7 V** ✓
- (c) 1.1 V
- (d) 5.4 V

---

**Q5.** A diode in forward bias has:
- **(a) Low resistance** ✓
- (b) High resistance
- (c) Zero resistance
- (d) Infinite resistance

---

**Q6.** Output frequency of a full-wave rectifier (input 50 Hz) is:
- (a) 25 Hz
- (b) 50 Hz
- **(c) 100 Hz** ✓
- (d) 200 Hz

---

**Q7.** Zener diode is used as:
- (a) Amplifier
- (b) Rectifier
- **(c) Voltage regulator** ✓
- (d) Oscillator

---

**Q8.** In an LED, light is emitted due to:
- (a) Photoelectric effect
- **(b) Recombination of electrons and holes** ✓
- (c) Thermal emission
- (d) Reverse breakdown

---

**Q9.** A photodiode is operated in:
- (a) Forward bias
- **(b) Reverse bias** ✓
- (c) No bias
- (d) Saturation region

---

**Q10.** If β = 99, then α =:
- (a) 0.90
- **(b) 0.99** ✓
- (c) 99
- (d) 0.1

*(Since α = β/(β+1) = 99/100 = 0.99)*

---

**Q11.** For transistor action, the emitter-base junction must be:
- **(a) Forward biased** ✓
- (b) Reverse biased
- (c) Unbiased
- (d) Both forward and reverse

---

**Q12.** In CE amplifier, the phase difference between input and output is:
- (a) 0°
- (b) 90°
- **(c) 180°** ✓
- (d) 360°

---

**Q13.** Which gate gives output 0 only when all inputs are 1?
- (a) AND
- (b) OR
- **(c) NAND** ✓
- (d) NOR

---

**Q14.** Boolean expression for NOR gate is:
- (a) A + B
- (b) A·B
- **(c) (A + B)'** ✓
- (d) (A·B)'

---

**Q15.** NAND gate is called universal gate because:
- (a) It is the fastest gate
- (b) It consumes least power
- **(c) Any logic gate can be made from it** ✓
- (d) It has most inputs

---

**Q16.** In the relationship n × p = nᵢ², this is called:
- **(a) Mass action law** ✓
- (b) Ohm's law
- (c) Kirchhoff's law
- (d) Gauss's law

---

**Q17.** The emitter of a transistor is:
- **(a) Heavily doped** ✓
- (b) Lightly doped
- (c) Moderately doped
- (d) Undoped

---

**Q18.** Which of the following is a trivalent impurity?
- (a) Phosphorus
- (b) Arsenic
- **(c) Boron** ✓
- (d) Antimony

---

**Q19.** For XOR gate, output is 1 when:
- (a) Both inputs are 1
- (b) Both inputs are 0
- **(c) Inputs are different** ✓
- (d) Any input is 1

---

**Q20.** Efficiency of full-wave rectifier is:
- (a) 40.6%
- **(b) 81.2%** ✓
- (c) 100%
- (d) 50%

---

## 14. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Full-wave rectifier (circuit + working) | 5 marks |
| ⭐⭐⭐ | CE Transistor Amplifier (gain derivation) | 5 marks |
| ⭐⭐⭐ | Zener diode as voltage regulator | 3-5 marks |
| ⭐⭐⭐ | Truth tables of all gates | 3 marks |
| ⭐⭐⭐ | p-n Junction formation + biasing | 3-5 marks |
| ⭐⭐ | Energy bands (diagram + classification) | 3 marks |
| ⭐⭐ | n-type and p-type semiconductors | 2-3 marks |
| ⭐⭐ | NAND/NOR as universal gates | 3 marks |
| ⭐⭐ | Transistor current relations (α, β) | 2-3 marks |
| ⭐ | LED, Photodiode, Solar Cell | 2 marks |
| ⭐ | Numericals (β, Av, Iz calculations) | 2-3 marks |
| ⭐ | MCQs (Objective) | 1 mark each |

---

### 📌 Things to Memorise (Flash Cards)

```
Energy gap:   Si = 1.1 eV,  Ge = 0.7 eV
Knee voltage: Si = 0.7 V,   Ge = 0.3 V

Mass action law:  n × p = nᵢ²
Transistor:       IE = IB + IC
Current gain CE:  β = IC / IB  (> 1)
Current gain CB:  α = IC / IE  (< 1)
Relation:         β = α/(1−α)  and  α = β/(β+1)

Voltage gain CE:  Av = −β(RC/ri)
Power gain:       Ap = β² (RC/ri)

Zener regulator:  Iz = Is − IL

OR gate:    Y = A + B
AND gate:   Y = A·B
NOT gate:   Y = A'
NAND gate:  Y = (A·B)'
NOR gate:   Y = (A+B)'
XOR gate:   Y = A⊕B
```

---

### 🔑 Key Differences to Remember

| | Forward Bias | Reverse Bias |
|---|---|---|
| +ve terminal connects to | p-side | n-side |
| Depletion layer | Thin | Thick |
| Resistance | Low | Very high |
| Current | Large | Negligible |
| Diode state | ON | OFF |

| | Half-Wave | Full-Wave |
|---|---|---|
| Diodes needed | 1 | 2 (or 4 for bridge) |
| Output frequency | f | 2f |
| Efficiency | 40.6% | 81.2% |

| | α (CB) | β (CE) |
|---|---|---|
| Formula | IC/IE | IC/IB |
| Value | < 1 (0.95–0.99) | > 1 (20–500) |
| Gain | Less than 1 | Greater than 1 |

| | n-type | p-type |
|---|---|---|
| Dopant | Pentavalent (P, As) | Trivalent (B, Al) |
| Majority carriers | Electrons | Holes |
| Impurity name | Donor | Acceptor |

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn energy band diagram for conductor, semiconductor, insulator
- [ ] Learn intrinsic vs extrinsic semiconductor (n-type and p-type)
- [ ] Learn p-n junction formation and depletion region
- [ ] Learn forward bias vs reverse bias (diagram + explanation)
- [ ] Practice full-wave rectifier circuit + working
- [ ] Practice Zener diode voltage regulator (circuit + equations)
- [ ] Learn LED, Photodiode, Solar Cell (2 lines each)
- [ ] Practice CE amplifier derivation — Av = −β(RC/ri)
- [ ] Learn transistor as switch (cut-off and saturation)
- [ ] Memorise truth tables of all 6 gates (AND, OR, NOT, NAND, NOR, XOR)
- [ ] Practise NAND as universal gate (realising NOT, AND, OR)
- [ ] Solve 5 numerical problems (β, α, Av, Iz)
- [ ] Revise all MCQs in Section 13
- [ ] Memorise all formulas in Section 11

---

### 💡 Common Mistakes to Avoid

1. **Don't confuse n-type and p-type.** n-type → pentavalent dopant → electrons are majority. p-type → trivalent dopant → holes are majority.
2. **Diode direction in forward bias:** +ve to p-side, −ve to n-side. Many students draw it reversed.
3. **Full-wave output frequency is 2f, NOT f.** Half-wave output frequency equals input frequency.
4. **Transistor current relation:** Always IE = IB + IC. Never write IC = IB + IE.
5. **β vs α:** β = IC/IB (greater than 1). α = IC/IE (less than 1). Don't mix them.
6. **Phase reversal in CE amplifier:** Output is 180° out of phase. Don't write "in phase."
7. **Zener diode is in REVERSE bias** for voltage regulation. Do not draw it in forward bias.
8. **NAND truth table:** Output is 0 ONLY when ALL inputs are 1. For any other input, output is 1. Students often confuse this with AND.
9. **NOR truth table:** Output is 1 ONLY when ALL inputs are 0. For any other input, output is 0.
10. **Photodiode works in reverse bias.** Solar cell works with NO external bias. These are different!

---

*Prepared for Bihar Board Class 12 Physics | Chapter 14: Semiconductor Electronics: Materials, Devices and Simple Circuits | Based on NCERT Textbook*