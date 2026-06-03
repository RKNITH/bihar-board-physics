# 📘 Class 12 Physics — Chapter 3: Current Electricity
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Electric Current](#2-electric-current)
3. [Electric Current in Conductors](#3-electric-current-in-conductors)
4. [Ohm's Law](#4-ohms-law)
5. [Resistance and Resistivity](#5-resistance-and-resistivity)
6. [Temperature Dependence of Resistance](#6-temperature-dependence-of-resistance)
7. [Electrical Energy and Power](#7-electrical-energy-and-power)
8. [Combination of Resistors](#8-combination-of-resistors)
9. [Cells, EMF, and Internal Resistance](#9-cells-emf-and-internal-resistance)
10. [Combination of Cells](#10-combination-of-cells)
11. [Kirchhoff's Laws](#11-kirchhoffs-laws)
12. [Wheatstone Bridge](#12-wheatstone-bridge)
13. [Metre Bridge](#13-metre-bridge)
14. [Potentiometer](#14-potentiometer)
15. [Important Formulas Summary](#15-important-formulas-summary)
16. [Board Exam Questions with Answers](#16-board-exam-questions-with-answers)
17. [Objective / MCQ Questions](#17-objective--mcq-questions)
18. [Quick Revision Tips](#18-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is about **Current Electricity** — the study of charges **in motion**.

In Chapter 1, we studied charges at rest (electrostatics). Now we study what happens when charges **flow continuously** through a conductor.

Think of it this way:
- A **bulb glows** when connected to a battery. **Why?** → Because current flows through its filament.
- A **fan rotates** when switched on. **Why?** → Electric current drives a motor.
- Your **mobile phone charges**. **Why?** → Current flows from charger to battery.

This chapter answers all these questions scientifically.

**What you will learn:**
- What is electric current and how it flows
- Ohm's Law and resistance
- Resistivity and its temperature dependence
- Electric power and energy
- Series and parallel combinations
- Cells, EMF, and internal resistance
- Kirchhoff's Laws
- Wheatstone Bridge, Metre Bridge, and Potentiometer

---

## 2. Electric Current

### 2.1 Definition ⭐ (Very Important)

**Definition:** *"Electric current is defined as the rate of flow of electric charge through a cross-section of a conductor."*

```
I = Q / t
```

Where:
- `I` = Electric current (Ampere, A)
- `Q` = Charge flowing (Coulomb, C)
- `t` = Time (second, s)

**For instantaneous current:**
```
I = dQ / dt
```

### 2.2 Unit of Current

- **SI Unit:** Ampere (A)
- 1 Ampere = 1 Coulomb per second = 1 C/s
- Current is a **scalar quantity** (even though we say it "flows" in a direction, it does not follow vector laws)

### 2.3 Direction of Current

- Conventional current flows from **high potential (+ve) to low potential (−ve)** — i.e., opposite to the flow of electrons.
- Electrons actually flow from **−ve terminal to +ve terminal** (from low to high potential).
- This is the most common confusion — **conventional current ≠ electron flow direction**.

> 💡 **Memory Tip:** Conventional current → **C**urrent → **C**ations (positive charges) direction. Electrons flow the opposite way.

### 2.4 Current Density ⭐

**Definition:** *"Current density at a point is the current flowing per unit area perpendicular to the direction of flow."*

```
J = I / A
```

- **Vector form:** `J = nqv_d` (directed along the drift velocity of positive charges)
- **Unit:** A/m²
- Relation with electric field: `J = σE` where σ = conductivity

---

## 3. Electric Current in Conductors

### 3.1 Drift Velocity ⭐⭐ (Board Exam — 2 to 3 Mark)

**Why do electrons drift?**

In a metal conductor, electrons move randomly at high speeds (~10⁵ m/s). But in the absence of an electric field, their **net displacement is zero** — they collide repeatedly with positive ions (lattice).

When an electric field is applied:
- Electrons experience force opposite to E (since they are negative).
- They gain a **small net velocity** in the direction opposite to E.
- This net average velocity is called **drift velocity**.

**Formula:**
```
v_d = eEτ / m
```

Where:
- `v_d` = Drift velocity (m/s)
- `e` = Charge of electron = 1.6 × 10⁻¹⁹ C
- `E` = Electric field (N/C)
- `τ` = Relaxation time (average time between collisions) (s)
- `m` = Mass of electron = 9.1 × 10⁻³¹ kg

> 📝 **Board Exam Note:** Drift velocity is very small — typically ~10⁻⁴ m/s. Yet current flows almost instantly because the electric field propagates at speed of light.

### 3.2 Relation Between Current and Drift Velocity ⭐⭐

**Derivation:**

Consider a conductor of length `l`, cross-sectional area `A`, with `n` free electrons per unit volume.

- Volume of conductor = A × l
- Total number of electrons = nAl
- Total charge = nAle

Time to cross length `l` at drift velocity `v_d`:
```
t = l / v_d
```

Current = Charge / Time:
```
I = nAle / (l/v_d) = nAev_d
```

**Formula:**
```
I = nAev_d
```

Where:
- `n` = number density of free electrons (electrons/m³)
- `A` = cross-sectional area (m²)
- `e` = charge of electron (C)
- `v_d` = drift velocity (m/s)

### 3.3 Relaxation Time and Mobility

- **Relaxation time (τ):** Average time between two successive collisions of an electron.
- **Mobility (μ):** Drift velocity per unit electric field.

```
μ = v_d / E = eτ / m
```
- Unit of mobility: m²/V·s

---

## 4. Ohm's Law

### 4.1 Statement ⭐⭐⭐ (Most Important — Board Exam)

**Statement:** *"At constant temperature, the current flowing through a conductor is directly proportional to the potential difference across its ends."*

```
V ∝ I
V = IR
```

Where:
- `V` = Potential difference (Volt, V)
- `I` = Current (Ampere, A)
- `R` = Resistance (Ohm, Ω)

### 4.2 Ohm's Law Graph

The V-I graph for a conductor obeying Ohm's Law is a **straight line through the origin**.

```
V
|         /
|        /   slope = R
|       /
|      /
|     /
|    /
|   /
0_________ I
```

- Slope of V-I graph = Resistance R
- Steeper slope = Higher resistance
- Shallower slope = Lower resistance

### 4.3 Ohmic and Non-Ohmic Conductors

| Ohmic Conductors | Non-Ohmic Conductors |
|---|---|
| Obey Ohm's Law | Do not obey Ohm's Law |
| V-I graph is a straight line | V-I graph is curved |
| R is constant | R varies with V or I |
| Example: Metallic wire, resistors | Example: Diode, LED, transistor |

### 4.4 Microscopic Form of Ohm's Law

```
J = σE
```

Where:
- `J` = Current density (A/m²)
- `σ` = Electrical conductivity (S/m or Ω⁻¹m⁻¹)
- `E` = Electric field (N/C)

This is the **microscopic (vector) form** of Ohm's Law.

---

## 5. Resistance and Resistivity

### 5.1 Resistance ⭐

**Definition:** *"Resistance is the opposition offered by a conductor to the flow of electric current through it."*

```
R = V / I
```

**SI Unit:** Ohm (Ω)

**1 Ohm:** A conductor has resistance of 1 Ω if 1 Ampere of current flows through it when 1 Volt is applied across it.

### 5.2 Resistivity (Specific Resistance) ⭐⭐

**Definition:** *"Resistivity of a material is the resistance offered by a conductor of that material of unit length and unit cross-sectional area."*

**Formula:**
The resistance R of a conductor depends on:
```
R ∝ L        (longer wire → more resistance)
R ∝ 1/A      (thicker wire → less resistance)
Combining:
R = ρL / A
```

Where:
- `ρ` (rho) = Resistivity of the material (Ω·m)
- `L` = Length of the conductor (m)
- `A` = Cross-sectional area (m²)

**Rearranging:**
```
ρ = RA / L
```

**SI Unit of Resistivity:** Ohm·metre (Ω·m)

### 5.3 Conductance and Conductivity

- **Conductance (G):** Reciprocal of resistance. `G = 1/R`
  - Unit: Siemens (S) or mho (℧)
- **Conductivity (σ):** Reciprocal of resistivity. `σ = 1/ρ`
  - Unit: S/m or Ω⁻¹m⁻¹

### 5.4 Resistivity of Various Materials

| Material | Resistivity (Ω·m) |
|---|---|
| Silver | 1.6 × 10⁻⁸ |
| Copper | 1.7 × 10⁻⁸ |
| Aluminium | 2.7 × 10⁻⁸ |
| Tungsten | 5.6 × 10⁻⁸ |
| Nichrome | 1.0 × 10⁻⁶ |
| Silicon | ~640 |
| Glass | 10¹⁰ to 10¹⁴ |

> 📝 **Note:** Metals have very low resistivity → good conductors. Insulators (glass, rubber) have very high resistivity.

---

## 6. Temperature Dependence of Resistance

### 6.1 Effect of Temperature on Resistance ⭐⭐

For **metals** (conductors):
- As temperature increases, resistance **increases**.
- Reason: Increased thermal vibrations of lattice ions → more collisions → reduced relaxation time → reduced drift velocity → increased resistance.

**Formula:**
```
R_T = R₀ (1 + αΔT)
```

Where:
- `R_T` = Resistance at temperature T
- `R₀` = Resistance at reference temperature (usually 0°C)
- `α` = Temperature coefficient of resistance
- `ΔT` = Change in temperature (T − T₀)

**Similarly for resistivity:**
```
ρ_T = ρ₀ (1 + αΔT)
```

### 6.2 Temperature Coefficient of Resistance (α)

**Definition:** *"The fractional change in resistance per unit change in temperature."*

```
α = (R_T − R₀) / (R₀ × ΔT)
```

**Unit:** per °C or per K (K⁻¹)

| Material | α (per °C) |
|---|---|
| Copper | 3.9 × 10⁻³ |
| Tungsten | 4.5 × 10⁻³ |
| Nichrome | ~0.0004 (very small) |
| Carbon | Negative (resistance decreases with T) |

> 📝 **Board Exam Note:**
> - For **metals:** α is **positive** (R increases with T).
> - For **semiconductors and carbon:** α is **negative** (R decreases with T).
> - **Nichrome** has very low α → used in heating elements (stable resistance).
> - **Manganin, constantan** have almost zero α → used in standard resistors.

### 6.3 Superconductivity

- Some materials have **zero resistance** below a critical temperature.
- This phenomenon is called **superconductivity**.
- Example: Mercury below 4.2 K.
- Application: MRI machines, maglev trains.

---

## 7. Electrical Energy and Power

### 7.1 Electrical Energy ⭐

When a charge Q moves through a potential difference V:
```
Work done W = QV = VIt        [since Q = It]
```

This work is stored as **electrical energy**:
```
E = VIt = I²Rt = V²t/R
```

**SI Unit:** Joule (J)
**Commercial Unit:** Kilowatt-hour (kWh) = 1 Unit of electricity
```
1 kWh = 3.6 × 10⁶ J
```

### 7.2 Electrical Power ⭐⭐

**Definition:** *"Electrical power is the rate at which electrical energy is consumed or dissipated."*

```
P = W/t = VI = I²R = V²/R
```

**SI Unit:** Watt (W)

**1 Watt:** Power consumed when 1 Joule of energy is dissipated per second.

> 💡 **Memory Tip:** Three power formulas to remember:
> - `P = VI` (when both V and I are known)
> - `P = I²R` (when I and R are known — for series circuits)
> - `P = V²/R` (when V and R are known — for parallel circuits)

### 7.3 Joule's Law of Heating ⭐

**Statement:** *"The heat produced in a conductor is directly proportional to the square of the current, resistance, and time for which the current flows."*

```
H = I²Rt
```

Where:
- `H` = Heat produced (Joule, J)
- `I` = Current (A)
- `R` = Resistance (Ω)
- `t` = Time (s)

**Applications of Joule's Heating:**
- Electric iron, heater, toaster (heating effect used)
- Fuse wire (melts when excess current flows)
- Filament of electric bulb (produces light and heat)

---

## 8. Combination of Resistors

### 8.1 Series Combination ⭐⭐

**Setup:** Resistors are connected end-to-end — the same current flows through all.

```
──R₁──R₂──R₃──
```

**Properties:**
- Same current through each resistor: `I₁ = I₂ = I₃ = I`
- Total voltage = sum of individual voltages: `V = V₁ + V₂ + V₃`

**Equivalent Resistance:**
```
R_s = R₁ + R₂ + R₃ + ... + Rₙ
```

**Important:** The equivalent resistance in series is **greater** than the largest individual resistance.

**Derivation:**
```
V = V₁ + V₂ + V₃ = IR₁ + IR₂ + IR₃ = I(R₁+R₂+R₃)
Since V = IR_s → R_s = R₁ + R₂ + R₃
```

### 8.2 Parallel Combination ⭐⭐

**Setup:** Resistors are connected between the same two points — same voltage across all.

```
    ┌──R₁──┐
────┤──R₂──├────
    └──R₃──┘
```

**Properties:**
- Same voltage across each resistor: `V₁ = V₂ = V₃ = V`
- Total current = sum of individual currents: `I = I₁ + I₂ + I₃`

**Equivalent Resistance:**
```
1/R_p = 1/R₁ + 1/R₂ + 1/R₃ + ... + 1/Rₙ
```

**For two resistors in parallel:**
```
R_p = R₁R₂ / (R₁ + R₂)
```

**Important:** The equivalent resistance in parallel is **less** than the smallest individual resistance.

**Derivation:**
```
I = I₁ + I₂ + I₃ = V/R₁ + V/R₂ + V/R₃ = V(1/R₁ + 1/R₂ + 1/R₃)
Since I = V/R_p → 1/R_p = 1/R₁ + 1/R₂ + 1/R₃
```

### 8.3 Comparison: Series vs Parallel

| Property | Series | Parallel |
|---|---|---|
| Current | Same through all | Divides into branches |
| Voltage | Divides across resistors | Same across all |
| Equivalent R | R₁ + R₂ + R₃ (greater) | Less than smallest R |
| If one breaks | Circuit breaks (all off) | Others still work |
| Usage | String lights (old type) | Home wiring |

---

## 9. Cells, EMF, and Internal Resistance

### 9.1 EMF of a Cell ⭐⭐

**Definition:** *"The EMF (electromotive force) of a cell is the maximum potential difference between the terminals of the cell when no current is being drawn from it (open circuit)."*

- EMF is the work done by the cell in moving unit positive charge from one terminal to the other **through the cell** (internal path).
- **Symbol:** ε (epsilon)
- **Unit:** Volt (V)

> 📝 **Note:** EMF is NOT a force — it is a potential difference (energy per unit charge). The name is historical.

### 9.2 Internal Resistance ⭐⭐

**Definition:** *"The resistance offered by the electrolyte inside the cell to the flow of current is called internal resistance."*

- **Symbol:** `r`
- **Unit:** Ohm (Ω)

**Factors affecting internal resistance:**
1. Nature and concentration of electrolyte (more concentrated → less r)
2. Distance between electrodes (more distance → more r)
3. Area of electrodes (more area → less r)
4. Temperature (higher T → less r for electrolyte solutions)

### 9.3 Terminal Voltage ⭐⭐ (Board Exam Important)

When current `I` flows through the cell:

```
ε = V + Ir
V = ε − Ir        (when cell is discharging)
```

Where:
- `V` = Terminal voltage (actual voltage available)
- `ε` = EMF of cell
- `I` = Current
- `r` = Internal resistance

**Three cases:**

| Condition | Terminal Voltage |
|---|---|
| Open circuit (I = 0) | V = ε (terminal V = EMF) |
| Discharging (I flowing out) | V = ε − Ir (V < ε) |
| Charging (I flowing in) | V = ε + Ir (V > ε) |

> 📝 **Board Exam Tip:** Learn all three cases. It's a popular 2-mark question.

### 9.4 Current in a Simple Circuit

For a cell of EMF `ε` and internal resistance `r` connected to external resistance `R`:
```
I = ε / (R + r)
```

The current is maximum when R = 0 (short circuit):
```
I_max = ε / r       (short circuit current — dangerous!)
```

---

## 10. Combination of Cells

### 10.1 Cells in Series ⭐

**Setup:** Cells connected so that positive terminal of one connects to negative of next.

**Equivalent EMF and internal resistance:**
```
ε_eq = ε₁ + ε₂ + ε₃ + ... + εₙ
r_eq = r₁ + r₂ + r₃ + ... + rₙ
```

**Current in circuit:**
```
I = nε / (R + nr)        [for n identical cells each of EMF ε and internal resistance r]
```

**Best for:** High resistance external circuits (R >> r), where high EMF is needed.

### 10.2 Cells in Parallel ⭐

**Setup:** All positive terminals connected together, all negative terminals connected together.

**For n identical cells (each EMF ε, internal resistance r):**
```
ε_eq = ε
r_eq = r/n
```

**Current in circuit:**
```
I = ε / (R + r/n)        [for n identical cells in parallel]
```

**Best for:** Low resistance external circuits (R << r), where high current is needed.

### 10.3 Mixed Grouping ⭐⭐ (Board Exam — 3 Mark)

**Setup:** `m` rows in parallel, each row having `n` cells in series (total mn cells).

**Equivalent EMF and resistance:**
```
ε_eq = nε
r_eq = nr/m
```

**Current:**
```
I = mnε / (mR + nr)
```

**Condition for Maximum Current:**
```
mR = nr
i.e., R = nr/m = r_eq
```
**Maximum current is obtained when external resistance = equivalent internal resistance.**

---

## 11. Kirchhoff's Laws

### 11.1 Kirchhoff's First Law (KCL — Junction Rule) ⭐⭐⭐

**Statement:** *"The algebraic sum of all currents meeting at a junction (node) is zero."*

```
ΣI = 0   at any junction
```

**In simple words:** Sum of currents entering a junction = Sum of currents leaving it.

```
        I₁ →        ← I₃
              ●
        I₂ ↑
```
If I₁ and I₂ enter, I₃ leaves:
```
I₁ + I₂ = I₃
```

**Based on:** Law of conservation of **charge** (charge cannot accumulate at a junction).

### 11.2 Kirchhoff's Second Law (KVL — Loop Rule) ⭐⭐⭐

**Statement:** *"The algebraic sum of all potential differences (EMFs and voltage drops) around any closed loop in a circuit is zero."*

```
ΣV = 0   around any closed loop
ΣE = ΣIR   (sum of EMFs = sum of voltage drops)
```

**Based on:** Law of conservation of **energy** (energy cannot be created or destroyed in a loop).

**Sign Convention for KVL:**
- If you traverse a resistor in the direction of current → voltage drop = **−IR**
- If you traverse a resistor against current → voltage gain = **+IR**
- If you traverse a cell from − to + → EMF = **+ε** (gaining potential)
- If you traverse a cell from + to − → EMF = **−ε** (losing potential)

> 📝 **Board Exam Note:** Always draw the circuit, assign current directions, then apply KVL. This is very frequently asked for 3–5 marks.

### 11.3 Solved Example Using Kirchhoff's Laws

**Q:** In a circuit, two cells of EMF 10V and 20V (with internal resistance 1Ω each) are connected in a loop with a 5Ω resistor. Find the current.

**Solution using KVL:**
```
Assume current I flows in the loop.
Taking clockwise direction:
+20 − I(1) − I(5) − I(1) + 10 = ... 
Wait — if both cells oppose, let's apply:
ΣE = ΣIR
(20 − 10) = I(1 + 5 + 1) = 7I
I = 10/7 ≈ 1.43 A
```

---

## 12. Wheatstone Bridge

### 12.1 Principle ⭐⭐⭐ (Board Exam — 5 Mark)

**Definition:** *"Wheatstone Bridge is a circuit used to measure an unknown resistance by comparing it with known resistances."*

**Circuit Diagram:**
```
                A
               / \
              P   Q
             /     \
            B       C
             \     /
              R   S
               \ /
                D
         B: battery between A and D
         G: galvanometer between B and C
```

Four resistors P, Q, R, S are connected in a diamond (bridge) shape. A battery is connected across one diagonal (A-D), and a galvanometer across the other (B-C).

### 12.2 Balancing Condition ⭐⭐⭐

**The bridge is balanced when no current flows through the galvanometer (Ig = 0).**

**Condition:**
```
P/Q = R/S
```

Or equivalently:
```
PS = QR
```

**Derivation using KVL/KCL:**

At balance, Ig = 0, so B and C are at the same potential.

Current through P = Current through R = I₁
Current through Q = Current through S = I₂

Voltage across P = Voltage across Q:
```
I₁P = I₂Q     → I₁/I₂ = Q/P    ...(1)
```

Voltage across R = Voltage across S:
```
I₁R = I₂S     → I₁/I₂ = S/R    ...(2)
```

From (1) and (2):
```
Q/P = S/R
→ P/Q = R/S  (Balancing condition)
```

### 12.3 Finding Unknown Resistance

If S is unknown:
```
S = QR / P
```

---

## 13. Metre Bridge

### 13.1 Construction and Principle ⭐⭐

**Metre Bridge** is a practical device based on the **Wheatstone Bridge principle**, used to determine an unknown resistance.

**Construction:**
- A **1-metre long resistance wire** (manganin or nichrome, uniform cross-section) is stretched on a wooden board with a metre scale below it.
- Two metallic strips form the bridge gaps at each end, connected to known resistance R (in left gap) and unknown resistance S (in right gap).
- A **jockey** (sliding contact) touches the wire at any point.

### 13.2 Working and Formula ⭐⭐

Let the jockey be at position `l` cm from the left end where the galvanometer shows no deflection (null point).

Then:
- Resistance of wire from 0 to l = **P** ∝ l
- Resistance of wire from l to 100 = **Q** ∝ (100 − l)

By Wheatstone balance:
```
P/Q = R/S
l/(100−l) = R/S
```

**Unknown resistance:**
```
S = R × (100 − l) / l
```

**Specific resistance (resistivity) of wire:**
```
ρ = S × A / L       where A = πd²/4 (cross-section area), L = length of wire
```

> 📝 **Board Exam Tip:** Draw a labelled diagram of the metre bridge. It is asked almost every year. Know the formula for S.

---

## 14. Potentiometer

### 14.1 Principle ⭐⭐

**Principle:** *"When a constant current flows through a wire of uniform cross-section and material, the potential difference across any segment is directly proportional to its length."*

```
V ∝ l
V = φl          where φ = potential gradient (V/m)
```

**Potential gradient (φ):**
```
φ = V/L = IR/L    (V/m)
```

Where V is total potential difference, L is total length of wire.

### 14.2 Application 1: Comparison of EMF of Two Cells ⭐⭐⭐

**Procedure:**
1. Balance the first cell (EMF ε₁) — note null point at length `l₁`.
2. Balance the second cell (EMF ε₂) — note null point at length `l₂`.

At balance: EMF = potential gradient × balancing length

```
ε₁ = φ × l₁
ε₂ = φ × l₂
```

**Dividing:**
```
ε₁/ε₂ = l₁/l₂
```

### 14.3 Application 2: Measurement of Internal Resistance ⭐⭐

**Procedure:**
1. Find balancing length `l₁` when the cell circuit is open → `ε = φl₁`
2. Connect external resistance R across cell. Find new balancing length `l₂` → `V = φl₂`

Since `V = ε − Ir` and `I = ε/(R+r)`:
```
V/ε = R/(R+r) = l₂/l₁
```

**Solving for internal resistance:**
```
r = R(l₁ − l₂) / l₂
```

### 14.4 Advantages of Potentiometer Over Voltmeter ⭐

| Potentiometer | Voltmeter |
|---|---|
| No current drawn at balance (null method) | Draws some current always |
| Measures EMF accurately | Measures terminal voltage (slightly less) |
| More accurate | Less accurate |
| Can measure internal resistance | Cannot measure internal resistance |

> 📝 **Board Exam Note:** "Why is potentiometer preferred over voltmeter for measuring EMF?" — this is a popular 2-mark question. The answer is: **potentiometer draws no current at null point, so it measures true EMF**.

---

## 15. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| I = Q/t | Electric current | A |
| I = nAev_d | Current and drift velocity | A |
| v_d = eEτ/m | Drift velocity | m/s |
| V = IR | Ohm's Law | V |
| R = ρL/A | Resistance | Ω |
| R_T = R₀(1 + αΔT) | Temperature dependence | Ω |
| P = VI = I²R = V²/R | Electrical power | W |
| H = I²Rt | Joule's heating | J |
| R_s = R₁+R₂+R₃ | Series combination | Ω |
| 1/R_p = 1/R₁+1/R₂+1/R₃ | Parallel combination | Ω |
| V = ε − Ir | Terminal voltage | V |
| I = ε/(R+r) | Current in circuit | A |
| P/Q = R/S | Wheatstone balance | — |
| S = R(100−l)/l | Metre bridge | Ω |
| ε₁/ε₂ = l₁/l₂ | Potentiometer (EMF comparison) | — |
| r = R(l₁−l₂)/l₂ | Internal resistance (potentiometer) | Ω |

---

## 16. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What is the SI unit of electric current?**
**Ans:** Ampere (A)

**Q2. Define drift velocity.**
**Ans:** Drift velocity is the average velocity acquired by free electrons in a conductor in the direction opposite to the applied electric field.

**Q3. State Ohm's Law.**
**Ans:** At constant temperature, the current through a conductor is directly proportional to the potential difference across its ends: V = IR.

**Q4. What is resistivity?**
**Ans:** Resistivity is the resistance of a conductor of unit length and unit cross-sectional area. ρ = RA/L. Unit: Ω·m.

**Q5. Define EMF of a cell.**
**Ans:** EMF is the maximum potential difference between the terminals of a cell when no current flows (open circuit). It equals work done per unit charge inside the cell.

**Q6. What is internal resistance?**
**Ans:** It is the resistance offered by the electrolyte inside the cell to the current flowing through it.

**Q7. State Kirchhoff's Current Law (KCL).**
**Ans:** The algebraic sum of all currents at a junction is zero: ΣI = 0.

**Q8. On what principle does a Wheatstone Bridge work?**
**Ans:** Wheatstone Bridge works on the principle that when the bridge is balanced, no current flows through the galvanometer and P/Q = R/S.

**Q9. What is the condition for null deflection in a metre bridge?**
**Ans:** P/Q = R/S, i.e., l/(100−l) = R/S, where l is the balancing length.

**Q10. Why is potentiometer preferred over voltmeter to measure EMF?**
**Ans:** Because at balance, potentiometer draws no current from the cell, so it measures true EMF without any drop due to internal resistance.

---

### 📝 2-Mark Questions

**Q11. Derive the relation between current and drift velocity.**

**Ans:**
Let `n` = number density of electrons, `A` = cross-section area, `v_d` = drift velocity.

In time `t`, electrons in a length `v_d × t` cross the area A.
Volume = A × v_d × t
Number of electrons = nAv_d t
Charge = nAv_d te
Current I = Charge/time = nAev_d

∴ **I = nAev_d**

---

**Q12. Write three differences between series and parallel combination of resistors.**

**Ans:**

| Series | Parallel |
|---|---|
| Same current through all | Same voltage across all |
| R_eq = R₁+R₂+... (greater) | 1/R_eq = 1/R₁+1/R₂+... (less) |
| All go off if one breaks | Others still work if one breaks |

---

**Q13. What is Joule's Law of Heating? Write its formula.**

**Ans:** When current flows through a conductor, heat is generated. The heat produced is:
```
H = I²Rt
```
It is directly proportional to I², R, and t. This is Joule's Law of Heating.

---

**Q14. Explain the effect of temperature on resistance of metals.**

**Ans:** For metals, resistance increases with temperature.
Formula: `R_T = R₀(1 + αΔT)`
Reason: At higher temperatures, lattice ions vibrate more vigorously, causing more collisions with free electrons. This reduces relaxation time τ, reducing drift velocity, increasing resistance.
α is positive for metals.

---

**Q15. A cell of EMF 3V and internal resistance 0.5Ω is connected to a 2.5Ω resistor. Find the current and terminal voltage.**

**Ans:**
```
I = ε/(R+r) = 3/(2.5+0.5) = 3/3 = 1 A
Terminal voltage V = ε − Ir = 3 − 1×0.5 = 2.5 V
```
**Answer: I = 1 A, V = 2.5 V**

---

### 📝 3-Mark Questions

**Q16. State and explain Kirchhoff's two laws.**

**Ans:**

**KCL (Junction Rule):** The algebraic sum of currents at any junction is zero. ΣI = 0.
Currents entering = Currents leaving.
Based on conservation of charge.

**KVL (Loop Rule):** The algebraic sum of all potential differences around any closed loop is zero. ΣV = 0 or ΣE = ΣIR.
Based on conservation of energy.

---

**Q17. Derive the balancing condition for Wheatstone Bridge.**

**Ans:**
*(See Section 12.2 — write full derivation)*

At balance, Ig = 0.
Using KCL and KVL:
```
I₁P = I₂Q     →  I₁/I₂ = Q/P
I₁R = I₂S     →  I₁/I₂ = S/R
∴ Q/P = S/R → P/Q = R/S
```

---

**Q18. Describe the principle and working of a potentiometer to compare EMFs of two cells.**

**Ans:** *(See Section 14.2)*

Principle: V ∝ l (at constant current).
Balance cell 1 at length l₁, cell 2 at length l₂.
```
ε₁/ε₂ = l₁/l₂
```

---

### 📝 5-Mark Questions (Long Answer)

**Q19. What is Wheatstone Bridge? Derive the condition for its balance. How is it used to find unknown resistance?**

**Ans:** *(See Sections 12.1, 12.2, and 12.3 — write full derivation with diagram)*

Final balancing condition: P/Q = R/S
Unknown resistance: S = QR/P

---

**Q20. Describe the construction and working of a metre bridge. Derive the formula for unknown resistance. List two precautions.**

**Ans:** *(See Section 13 — write with labelled diagram)*

Formula: S = R(100 − l)/l

Precautions:
1. The wire should be of uniform cross-section.
2. Connect the jockey gently and take reading accurately.
3. The null point should be near the middle (around 50 cm) for best accuracy.

---

**Q21. Derive expressions for equivalent resistance when resistors are connected in:**
**(i) Series**
**(ii) Parallel**

**Ans:** *(See Sections 8.1 and 8.2 — write both derivations with circuit diagrams)*

(i) Series: R_s = R₁ + R₂ + R₃
(ii) Parallel: 1/R_p = 1/R₁ + 1/R₂ + 1/R₃

---

**Q22. Define EMF and internal resistance of a cell. Derive the expression for current in a circuit and terminal voltage. What happens when the cell is (i) open circuited (ii) short circuited?**

**Ans:** *(See Sections 9.1, 9.2, 9.3, and 9.4)*

Key results:
- General: I = ε/(R+r), V = ε − Ir
- Open circuit (I=0): V = ε
- Short circuit (R=0): I = ε/r (maximum, dangerous)

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** Find the resistance of a wire of length 2m, area of cross-section 2×10⁻⁶ m², and resistivity 1.7×10⁻⁸ Ω·m.

**Solution:**
```
R = ρL/A = (1.7×10⁻⁸ × 2) / (2×10⁻⁶)
  = 3.4×10⁻⁸ / 2×10⁻⁶
  = 0.017 Ω
```
**Answer: R = 0.017 Ω**

---

**Num 2:** Three resistors of 2Ω, 3Ω, and 6Ω are connected in parallel. Find the equivalent resistance.

**Solution:**
```
1/R_p = 1/2 + 1/3 + 1/6 = 3/6 + 2/6 + 1/6 = 6/6 = 1
R_p = 1 Ω
```
**Answer: R_p = 1 Ω**

---

**Num 3:** A bulb rated 60W, 220V is connected to 220V supply. Find (a) its resistance, (b) current through it.

**Solution:**
```
(a) P = V²/R → R = V²/P = (220)²/60 = 48400/60 ≈ 806.7 Ω
(b) I = P/V = 60/220 ≈ 0.27 A
```
**Answer: R ≈ 807 Ω, I ≈ 0.27 A**

---

**Num 4:** A cell of EMF 1.5V and internal resistance 0.3Ω is connected to an external resistance of 2.7Ω. Find the terminal voltage.

**Solution:**
```
I = ε/(R+r) = 1.5/(2.7+0.3) = 1.5/3 = 0.5 A
V = ε − Ir = 1.5 − 0.5×0.3 = 1.5 − 0.15 = 1.35 V
```
**Answer: Terminal Voltage = 1.35 V**

---

**Num 5:** In a Wheatstone Bridge, P = 10Ω, Q = 15Ω, R = 20Ω. Find the value of S for balance.

**Solution:**
```
P/Q = R/S
10/15 = 20/S
S = 20×15/10 = 30 Ω
```
**Answer: S = 30 Ω**

---

**Num 6:** In a metre bridge experiment, a wire of unknown resistance S gives a null point at 40 cm when R = 30Ω. Find S.

**Solution:**
```
S = R(100 − l)/l = 30×(100−40)/40 = 30×60/40 = 1800/40 = 45 Ω
```
**Answer: S = 45 Ω**

---

**Num 7:** A potentiometer wire is 4m long. The EMF of the driver cell is 2V and the wire has resistance 8Ω. Find the potential gradient.

**Solution:**
```
Current through potentiometer wire (assuming only wire resistance):
φ = V/L = 2/4 = 0.5 V/m
```
**Answer: Potential gradient = 0.5 V/m**

---

**Num 8:** The resistance of a wire at 0°C is 20Ω. It increases to 25Ω at 100°C. Find the temperature coefficient of resistance.

**Solution:**
```
R_T = R₀(1 + αΔT)
25 = 20(1 + α×100)
25/20 = 1 + 100α
1.25 = 1 + 100α
100α = 0.25
α = 0.0025 per °C = 2.5 × 10⁻³ per °C
```
**Answer: α = 2.5 × 10⁻³ /°C**

---

## 17. Objective / MCQ Questions

**Q1.** The SI unit of resistivity is:
- (a) Ω/m
- **(b) Ω·m** ✓
- (c) Ω/m²
- (d) S/m

---

**Q2.** Drift velocity of electrons is of the order of:
- (a) 10⁵ m/s
- **(b) 10⁻⁴ m/s** ✓
- (c) 10² m/s
- (d) 1 m/s

---

**Q3.** When temperature increases, resistance of a semiconductor:
- **(a) Decreases** ✓
- (b) Increases
- (c) Remains same
- (d) Becomes zero

---

**Q4.** Three resistors of 1Ω, 2Ω, 3Ω are in series. Equivalent resistance is:
- (a) 6/11 Ω
- (b) 1 Ω
- **(c) 6 Ω** ✓
- (d) 3 Ω

---

**Q5.** Kirchhoff's Current Law is based on conservation of:
- (a) Energy
- **(b) Charge** ✓
- (c) Momentum
- (d) Mass

---

**Q6.** Kirchhoff's Voltage Law is based on conservation of:
- **(a) Energy** ✓
- (b) Charge
- (c) Momentum
- (d) Current

---

**Q7.** A cell of EMF 5V and internal resistance 1Ω is short-circuited. The short-circuit current is:
- (a) 0 A
- (b) 2.5 A
- **(c) 5 A** ✓
- (d) 10 A

---

**Q8.** For a Wheatstone Bridge to be balanced, the condition is:
- (a) P + Q = R + S
- **(b) P/Q = R/S** ✓
- (c) P × Q = R × S
- (d) P − Q = R − S

---

**Q9.** The commercial unit of electrical energy is:
- (a) Joule
- **(b) kWh** ✓
- (c) Watt
- (d) Coulomb

---

**Q10.** A potentiometer can be used to measure:
- (a) Resistance only
- (b) Current only
- (c) EMF only
- **(d) EMF and internal resistance both** ✓

---

**Q11.** In a metre bridge, the null point is at 60 cm. If R = 30Ω, the unknown resistance S is:
- (a) 18 Ω
- **(b) 20 Ω** ✓
- (c) 45 Ω
- (d) 50 Ω

*(Solution: S = R(100−l)/l = 30×40/60 = 20 Ω)*

---

**Q12.** When cells are connected in parallel, the equivalent EMF:
- **(a) Remains equal to EMF of one cell** ✓
- (b) Doubles
- (c) Halves
- (d) Becomes zero

---

**Q13.** The power dissipated in a resistor R when voltage V is applied is:
- (a) V²R
- **(b) V²/R** ✓
- (c) VR
- (d) V/R

---

**Q14.** The terminal voltage of a cell is less than its EMF when:
- (a) Cell is on open circuit
- **(b) Cell is being discharged** ✓
- (c) Cell is being charged
- (d) No current flows

---

**Q15.** A wire of resistance R is stretched to double its length. New resistance will be:
- (a) R/2
- (b) R
- (c) 2R
- **(d) 4R** ✓

*(Length doubles → L becomes 2L; area halves → A becomes A/2; R = ρL/A becomes ρ(2L)/(A/2) = 4R)*

---

## 18. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Wheatstone Bridge + Metre Bridge | 5 marks |
| ⭐⭐⭐ | Potentiometer (both applications) | 5 marks |
| ⭐⭐⭐ | Kirchhoff's Laws | 3–5 marks |
| ⭐⭐⭐ | EMF, Internal Resistance, Terminal Voltage | 3 marks |
| ⭐⭐ | Series & Parallel Resistors (derivation) | 3 marks |
| ⭐⭐ | Ohm's Law + Resistivity | 2–3 marks |
| ⭐⭐ | Drift Velocity derivation | 3 marks |
| ⭐ | Joule's Heating Law | 2 marks |
| ⭐ | Numericals | 2–3 marks each |
| ⭐ | MCQs | 1 mark each |

---

### 📌 Things to Memorize (Flash Cards)

```
Current:          I = Q/t = nAev_d
Ohm's Law:        V = IR
Resistivity:      R = ρL/A
Temp. dependence: R_T = R₀(1 + αΔT)
Power (3 forms):  P = VI = I²R = V²/R
Joule's Heating:  H = I²Rt
Series:           R_s = R₁ + R₂ + R₃
Parallel:         1/R_p = 1/R₁ + 1/R₂ + 1/R₃
Terminal voltage: V = ε − Ir
Circuit current:  I = ε/(R+r)
KCL:              ΣI = 0
KVL:              ΣV = 0 (or ΣE = ΣIR)
Wheatstone:       P/Q = R/S
Metre Bridge:     S = R(100−l)/l
Potentiometer:    ε₁/ε₂ = l₁/l₂
Internal r:       r = R(l₁−l₂)/l₂
1 kWh:            3.6 × 10⁶ J
```

---

### 🔑 Key Differences to Remember

| | Ohmic Conductors | Non-Ohmic Conductors |
|---|---|---|
| V-I graph | Straight line | Curved |
| Resistance | Constant | Variable |
| Example | Resistors, metallic wire | Diode, LED |

| | Series | Parallel |
|---|---|---|
| Current | Same | Divides |
| Voltage | Divides | Same |
| R_eq | Increases | Decreases |

| | Potentiometer | Voltmeter |
|---|---|---|
| Current drawn | Zero (at balance) | Always some |
| Accuracy | Very high | Lower |
| Can measure | EMF + internal r | Terminal voltage only |

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn Ohm's Law — statement, formula, V-I graph
- [ ] Learn resistivity formula and unit
- [ ] Learn R = R₀(1+αΔT) and what α means for metals vs semiconductors
- [ ] Learn all three power formulas: P = VI, I²R, V²/R
- [ ] Practice Series and Parallel resistance derivations
- [ ] Learn terminal voltage formula for all three cases (open, discharge, charge)
- [ ] Practice Kirchhoff's Law application on circuits
- [ ] Learn Wheatstone Bridge balancing condition derivation
- [ ] Learn Metre Bridge formula: S = R(100−l)/l
- [ ] Learn Potentiometer — both applications: ε₁/ε₂ = l₁/l₂ and r = R(l₁−l₂)/l₂
- [ ] Memorize all formulas in Section 15
- [ ] Solve 6–8 numerical problems
- [ ] Revise all MCQs in Section 17

---

### 💡 Common Mistakes to Avoid

1. **Conventional current vs electron flow:** Conventional current is from + to −; electrons flow from − to +.
2. **Terminal voltage formula:** V = ε − Ir (NOT V = ε + Ir) during discharge.
3. **Parallel formula:** Always use 1/R_p = 1/R₁ + 1/R₂. Don't add resistances in parallel.
4. **Metre bridge formula:** S = R(100−l)/l — it's (100−l) not l in numerator for S.
5. **Wheatstone balance:** Condition is P/Q = R/S, not P/R = Q/S (don't swap).
6. **Power in series vs parallel:** For same resistors, series has less power, parallel has more.
7. **Wire stretched problem:** If length doubled, area is halved → R becomes 4 times (not 2 times!).
8. **EMF vs Terminal Voltage:** EMF is measured only in open circuit. In closed circuit, terminal voltage < EMF.

---

*Prepared for Bihar Board Class 12 Physics | Chapter 3: Current Electricity | Based on NCERT Textbook*