# 📘 Class 12 Physics — Chapter 4: Moving Charges and Magnetism
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Magnetic Force on a Moving Charge](#2-magnetic-force-on-a-moving-charge)
3. [Motion of a Charged Particle in a Magnetic Field](#3-motion-of-a-charged-particle-in-a-magnetic-field)
4. [Cyclotron](#4-cyclotron)
5. [Magnetic Force on a Current-Carrying Conductor](#5-magnetic-force-on-a-current-carrying-conductor)
6. [Force Between Two Parallel Current-Carrying Conductors](#6-force-between-two-parallel-current-carrying-conductors)
7. [Torque on a Current Loop in a Magnetic Field](#7-torque-on-a-current-loop-in-a-magnetic-field)
8. [Moving Coil Galvanometer](#8-moving-coil-galvanometer)
9. [Biot-Savart Law](#9-biot-savart-law)
10. [Magnetic Field on the Axis of a Circular Current Loop](#10-magnetic-field-on-the-axis-of-a-circular-current-loop)
11. [Ampere's Circuital Law](#11-amperes-circuital-law)
12. [Applications of Ampere's Law](#12-applications-of-amperes-law)
13. [Solenoid and Toroid](#13-solenoid-and-toroid)
14. [Important Formulas Summary](#14-important-formulas-summary)
15. [Board Exam Questions with Answers](#15-board-exam-questions-with-answers)
16. [Objective / MCQ Questions](#16-objective--mcq-questions)
17. [Quick Revision Tips](#17-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is the **starting point of Magnetism** caused by moving charges (electric currents).

Think of it this way:
- An MRI machine uses powerful magnets. **How?** → Magnetic fields created by large coils of current-carrying wire.
- A compass needle deflects near a current-carrying wire. **Why?** → Current produces a magnetic field.
- Electric motors run fans and pumps. **How?** → A current-carrying coil experiences a torque in a magnetic field.

This chapter answers all these questions scientifically.

**What you will learn:**
- Force on a moving charge in a magnetic field (Lorentz Force)
- Circular motion of charged particles — and the Cyclotron
- Force on current-carrying conductors
- Biot-Savart Law and Ampere's Circuital Law
- Magnetic field due to solenoid and toroid
- Moving Coil Galvanometer

---

## 2. Magnetic Force on a Moving Charge

### 2.1 Lorentz Force ⭐⭐ (Very Important)

When a charged particle moves in both electric and magnetic fields, it experiences a combined force called the **Lorentz Force**.

**Magnetic force on a moving charge:**
```
→    →   →
F = q(v × B)
```

**Magnitude:**
```
F = qvB sinθ
```

Where:
- `F` = Magnetic force (in Newton, N)
- `q` = Charge of the particle (in Coulomb, C)
- `v` = Speed of the particle (in m/s)
- `B` = Magnetic field (in Tesla, T)
- `θ` = Angle between velocity vector and magnetic field

**Complete Lorentz Force (Electric + Magnetic):**
```
→        →      →   →
F = q(E + v × B)
```

### 2.2 Important Points

1. **If θ = 0° or 180°:** F = 0. A charge moving parallel (or anti-parallel) to B experiences **no** magnetic force.
2. **If θ = 90°:** F = qvB (Maximum force — charge moves perpendicular to B).
3. The magnetic force is **always perpendicular** to the velocity → it does **no work** on the particle → **kinetic energy (speed) doesn't change**.
4. Magnetic force **cannot** change the speed of a particle, only its direction.

### 2.3 SI Unit of Magnetic Field

- SI Unit of B = **Tesla (T)**
- 1 T = 1 N A⁻¹ m⁻¹ = 1 Wb/m²
- CGS Unit = **Gauss (G)**
- 1 T = 10⁴ G

### 2.4 Direction of Magnetic Force — Right Hand Rule / Fleming's Left Hand Rule

**Fleming's Left Hand Rule:**  
Stretch the thumb, index finger, and middle finger of the LEFT hand mutually perpendicular to each other:
- **Index finger** → Direction of magnetic field (B)
- **Middle finger** → Direction of current / velocity of positive charge (v)
- **Thumb** → Direction of force (F)

> 📝 **Board Exam Note:** Always draw a diagram when using Fleming's Left Hand Rule. It's easy marks.

---

## 3. Motion of a Charged Particle in a Magnetic Field

### 3.1 Circular Motion ⭐⭐ (Very Important — Derivation)

When a charged particle enters a magnetic field **perpendicular** to B (θ = 90°):

- Magnetic force acts as **centripetal force**.
- The particle moves in a **circular path**.

**Derivation:**

Magnetic force provides centripetal force:
```
qvB = mv²/r
```

Solving for radius r:
```
     mv
r = ————
     qB
```

Where:
- `r` = Radius of circular path
- `m` = Mass of particle
- `v` = Speed of particle
- `q` = Charge of particle
- `B` = Magnetic field strength

### 3.2 Time Period and Frequency ⭐

**Time Period:**
```
      2πr   2πm
T = ——— = ————
       v     qB
```

**Frequency:**
```
       1      qB
f = ——— = ————
       T    2πm
```

**Angular Frequency:**
```
       qB
ω = ————
        m
```

> 📝 **Key Observation:** The time period T does NOT depend on velocity or radius. It depends only on mass, charge, and magnetic field. This principle is used in the **Cyclotron**.

### 3.3 Cases of Particle Motion

| Angle θ (v with B) | Path of particle |
|---|---|
| 0° or 180° | Straight line (no force) |
| 90° | Perfect circle |
| Between 0° and 90° | **Helix (spiral)** |

> 📝 **Board Exam Tip:** "Helical motion" — this is a common 1-2 mark question. The component of v along B causes straight motion; the component perpendicular to B causes circular motion. Combined = helix.

---

## 4. Cyclotron

### 4.1 What is a Cyclotron? ⭐⭐ (5-Mark Long Answer)

A **cyclotron** is a device used to **accelerate charged particles** (like protons, alpha particles) to very high energies (MeV range) for use in nuclear physics experiments, cancer therapy (radiation), etc.

**Inventor:** Ernest O. Lawrence (1930)

### 4.2 Principle

A charged particle can be accelerated repeatedly using a high-frequency alternating electric field. The magnetic field keeps the particle moving in a circular path, and the radius increases with each acceleration.

**Principle is based on:** The time period of revolution of a charged particle in a magnetic field is **independent of its speed** (as derived above).

### 4.3 Construction

The cyclotron consists of:
1. **Two D-shaped hollow metallic chambers** called **"Dees"** (D₁ and D₂).
2. A **strong magnetic field** perpendicular to the plane of the Dees (provided by an electromagnet).
3. A **high-frequency oscillating voltage** (alternating voltage) applied between the two Dees.
4. A **vacuum chamber** (to prevent air resistance).
5. A **deflecting plate** to extract the accelerated beam.

```
        N (North Pole)
        |
   _____|_____
  |     |     |
  |  [D₁] [D₂]|   ← Dees (D-shaped hollow chambers)
  |     |     |
  |_____|_____|
        |
        S (South Pole)

Particle source at centre.
Alternating voltage applied between D₁ and D₂.
```

### 4.4 Working ⭐⭐

1. A positive ion (e.g., proton) is placed at the centre (source).
2. When D₁ is negative, the positive ion accelerates toward D₁ and enters it.
3. Inside D₁, no electric field → ion moves in a semicircle due to magnetic force.
4. When the ion comes out of D₁, the polarity of the voltage reverses → D₂ becomes negative.
5. Ion accelerates again and enters D₂, moving in a larger semicircle (because its speed has increased → r = mv/qB increases).
6. This continues repeatedly — each time the ion gains energy at the gap between Dees.
7. The ion spirals outward. When it reaches the outer edge, it is deflected by a deflecting plate and hits the target.

### 4.5 Key Formulas

**Cyclotron frequency (resonance condition):**
```
         qB
f_c = ————
        2πm
```

**Maximum kinetic energy:**
```
        q²B²R²
K_max = ————————
           2m
```

Where R = maximum radius (radius of the Dees).

**Maximum velocity:**
```
        qBR
v_max = ————
           m
```

### 4.6 Limitations of Cyclotron ⭐

1. **Cannot accelerate electrons:** Electrons gain speed very quickly and their mass increases (relativistic effect) — cyclotron condition breaks down.
2. **Cannot accelerate neutrons:** Neutrons are uncharged — no electric force acts on them.
3. **Relativistic limitation:** At very high speeds, mass increases → time period increases → particle goes out of resonance with the applied frequency.

> 📝 **Board Exam Note:** Cyclotron comes for 5 marks. Draw the diagram clearly. Write principle, construction, working, and one limitation.

---

## 5. Magnetic Force on a Current-Carrying Conductor

### 5.1 Expression for Force ⭐⭐ (Derivation)

**Derivation:**

Consider a straight conductor of length `L` carrying current `I` placed in a uniform magnetic field `B` at angle `θ` with B.

Let `n` = number of free electrons per unit volume, `A` = cross-sectional area, `v_d` = drift velocity.

Current: I = nqAv_d

Force on one electron: f = qv_dB sinθ

Total number of electrons: N = nAL

Total force:
```
F = Nf = nAL × qv_dB sinθ
       = (nqAv_d) × LB sinθ
       = ILB sinθ
```

**Formula:**
```
F = BIL sinθ
```

**In vector form:**
```
→    →   →
F = I(L × B)
```

Where:
- `F` = Force on conductor (N)
- `B` = Magnetic field (T)
- `I` = Current (A)
- `L` = Length of conductor (m)
- `θ` = Angle between current direction and B

### 5.2 Special Cases

- **θ = 0° (conductor parallel to B):** F = 0
- **θ = 90° (conductor perpendicular to B):** F = BIL (Maximum)

> 📝 This formula is the foundation for understanding electric motors and galvanometers.

---

## 6. Force Between Two Parallel Current-Carrying Conductors

### 6.1 Derivation ⭐⭐ (Board Exam — 3 or 5 Marks)

**Setup:** Two long parallel conductors AB and CD, separated by distance `d`, carry currents I₁ and I₂ respectively.

**Step 1:** Magnetic field due to conductor AB at the location of CD:
```
        μ₀ I₁
B₁ = ————————
        2πd
```

**Step 2:** Force on conductor CD (length L) due to field B₁:
```
F = B₁ I₂ L = (μ₀ I₁ / 2πd) × I₂ × L
```

**Force per unit length:**
```
F      μ₀ I₁ I₂
— = ——————————
L        2πd
```

Where:
- `μ₀` = Permeability of free space = **4π × 10⁻⁷ T·m/A**

### 6.2 Nature of Force ⭐

| Currents | Force |
|---|---|
| Same direction (→ →) | **Attractive** |
| Opposite direction (→ ←) | **Repulsive** |

> 💡 **Memory Tip:** "Like currents attract, unlike currents repel" (opposite of charges!)

### 6.3 Definition of 1 Ampere ⭐ (Very Important — Board Exam)

**Definition:** *"One ampere is defined as that steady current which, when flowing in each of two infinitely long, straight, parallel conductors placed 1 metre apart in vacuum, produces a force of 2 × 10⁻⁷ N per metre length between them."*

Verify: Put I₁ = I₂ = 1A, d = 1m:
```
F/L = μ₀I₁I₂/2πd = 4π×10⁻⁷ × 1 × 1 / (2π × 1) = 2×10⁻⁷ N/m ✓
```

---

## 7. Torque on a Current Loop in a Magnetic Field

### 7.1 Derivation ⭐⭐⭐ (5-Mark Question — Must Learn!)

**Setup:**
- A rectangular current loop of dimensions `a × b` (sides of length a and b) carrying current `I`.
- Placed in a uniform magnetic field `B`.
- The plane of the loop makes angle `α` with B (or the normal to the loop makes angle `θ` with B, where θ + α = 90°).

**Forces on each side:**

- **Side of length b (parallel to B):** F = BIb sin0° = 0 or BIb (depending on orientation). For the standard setup where sides of length `a` are perpendicular to B:
  - Force on side AD: F₁ = BIa (upward)
  - Force on side BC: F₂ = BIa (downward)
  - These two forces form a **couple**.
- **Sides of length b (parallel to B):** F = 0 (no force)

**Torque = Force × Perpendicular distance:**
```
τ = F₁ × b cosα     (where α = angle between plane of loop and B)
  = BIa × b cosα
  = BI(ab) cosα
  = BIA cosα        [since A = ab = area of loop]
```

Since `θ = 90° - α` (θ = angle between normal to loop and B):
```
τ = BIA sinθ
```

**For N turns:**
```
τ = NBIA sinθ
```

**In vector form:**
```
→    →   →
τ = m × B
```

Where `m = NIA` is the **magnetic dipole moment** of the loop.

### 7.2 Magnetic Dipole Moment ⭐

```
m = NIA
```

- **Direction:** Perpendicular to the plane of the loop, given by the **right-hand rule**.
- **SI Unit:** A·m² (Ampere × metre²)

---

## 8. Moving Coil Galvanometer

### 8.1 Principle ⭐⭐

**Principle:** *"When a current-carrying coil is placed in a magnetic field, it experiences a torque. This torque deflects the coil."*

### 8.2 Construction

1. **Coil:** A rectangular coil of N turns of insulated wire wound over a non-conducting frame.
2. **Permanent Magnet:** Provides a strong uniform radial magnetic field (concave pole pieces ensure the field is always perpendicular to the plane of the coil — for linear scale).
3. **Soft Iron Core:** Placed inside the coil to strengthen the magnetic field and make it radial.
4. **Spring (Hair spring):** Provides restoring torque — brings the pointer back to zero.
5. **Scale and Pointer:** For reading deflection.

### 8.3 Working / Theory ⭐⭐

When current I flows through the coil:

**Deflecting torque:**
```
τ_deflecting = NIAB
```

(Field is always radial, so sinθ = 1 always)

**Restoring torque from spring:**
```
τ_restoring = kφ
```

Where `k` = spring constant, `φ` = angle of deflection.

**At equilibrium:**
```
NIAB = kφ

        NIAB
φ = ————————
          k
```

**Current sensitivity:**
```
φ      NAB
— = ————————
I         k
```

**Voltage sensitivity:**
```
φ      NAB
— = ————————
V       kR
```

Where R = resistance of coil.

### 8.4 Conversion to Ammeter and Voltmeter ⭐⭐ (Board Exam Important)

#### Converting Galvanometer to Ammeter:

Connect a **low resistance (shunt S) in parallel** with the galvanometer.

**Formula:**
```
       I_g × G
S = ——————————
      I − I_g
```

Where:
- `S` = Shunt resistance
- `I_g` = Full-scale deflection current of galvanometer
- `G` = Resistance of galvanometer
- `I` = Maximum current to be measured

**Key point:** Ammeter has **very low resistance**. It is connected in **series** in a circuit.

#### Converting Galvanometer to Voltmeter:

Connect a **high resistance R in series** with the galvanometer.

**Formula:**
```
        V
R = ——— − G
       I_g
```

Where:
- `R` = Series resistance to be added
- `V` = Maximum voltage to be measured
- `I_g` = Full-scale deflection current
- `G` = Galvanometer resistance

**Key point:** Voltmeter has **very high resistance**. It is connected in **parallel** in a circuit.

### 8.5 Comparison: Ammeter vs Voltmeter

| Property | Ammeter | Voltmeter |
|---|---|---|
| Purpose | Measures current | Measures voltage |
| Connected | In series | In parallel |
| Resistance | Very low (ideally 0) | Very high (ideally ∞) |
| Conversion | Low shunt in parallel | High resistance in series |

---

## 9. Biot-Savart Law

### 9.1 Statement ⭐⭐⭐ (Most Important — Board Exam Must!)

**Statement:** *"The magnetic field dB at a point P due to a small current element Idl is directly proportional to the current I, the length of the element dl, the sine of the angle θ between the element and the line joining the element to P, and inversely proportional to the square of the distance r between the element and the point."*

### 9.2 Mathematical Form ⭐⭐

```
         μ₀   Idl sinθ
dB =  ——— × ——————————
          4π       r²
```

**In vector form:**
```
→       μ₀  I(dl × r̂)
dB = ——— × ————————
         4π       r²
```

Where:
- `dB` = Magnetic field due to small current element
- `μ₀` = Permeability of free space = 4π × 10⁻⁷ T·m/A
- `I` = Current in the conductor
- `dl` = Small length element of the conductor
- `r` = Distance from the element to point P
- `θ` = Angle between dl and r̂

**Direction:** Given by the **right-hand thumb rule** or the **cross product dl × r̂**.

### 9.3 Comparison: Biot-Savart Law vs Coulomb's Law

| Property | Biot-Savart (Magnetic) | Coulomb's (Electric) |
|---|---|---|
| Source | Moving charge / current | Static charge |
| Field | Magnetic field B | Electric field E |
| Dependence | 1/r² | 1/r² |
| Direction | Perpendicular to dl and r | Along line joining charges |
| Superposition | Applicable | Applicable |

---

## 10. Magnetic Field on the Axis of a Circular Current Loop

### 10.1 Derivation ⭐⭐ (5-Mark Question)

**Setup:** A circular loop of radius `R` carrying current `I`. Point P is on the axis at distance `x` from the centre.

**Using Biot-Savart Law:**

Consider a small element `dl` of the loop. Its distance from P:
```
r = √(R² + x²)
```

The magnetic field `dB` due to element `dl` makes an angle with the axis.

By symmetry, when we sum over all elements of the loop, the **perpendicular components cancel** and only the **axial components add up**.

```
dB_axial = dB × cosφ = (μ₀I dl)/(4π(R²+x²)) × R/√(R²+x²)
```

Total field at P (integrating dl over full circle = 2πR):
```
         μ₀IR²
B = ———————————————
      2(R² + x²)^(3/2)
```

### 10.2 Special Cases ⭐

**At the centre of the loop (x = 0):**
```
      μ₀I
B = ————
      2R
```

**At a far axial point (x >> R):**
```
      μ₀IR²        μ₀ 2m
B ≈ ————————  = ————————
       2x³           4π x³
```

Where m = IA is the magnetic dipole moment.

> 📝 **Board Exam Note:** "Magnetic field at the centre of a circular loop" = μ₀I/2R is a very common 1-mark or formula-based question.

---

## 11. Ampere's Circuital Law

### 11.1 Statement ⭐⭐⭐ (Board Exam Must!)

**Statement:** *"The line integral of the magnetic field B around any closed loop (Amperian loop) is equal to μ₀ times the total current passing through the surface enclosed by that loop."*

**Mathematical Form:**
```
∮ B · dl = μ₀ I_enclosed
```

Where:
- The circle on the integral means integration over a **closed path**.
- `I_enclosed` = net current enclosed by the Amperian loop.

> 📝 **Analogy:** Ampere's Circuital Law for magnetism is analogous to Gauss's Law for electrostatics.

### 11.2 Proof for a Long Straight Wire ⭐

Consider a long straight wire carrying current I. Choose an Amperian loop as a circle of radius r centred on the wire.

By symmetry, B has the same magnitude at every point on the circle and is tangent to it:
```
∮ B · dl = B × 2πr

By Ampere's Law:
B × 2πr = μ₀I

           μ₀I
B = ————
        2πr
```

This is the same result as from Biot-Savart Law — confirming Ampere's Law.

---

## 12. Applications of Ampere's Law

### 12.1 Magnetic Field Due to Long Straight Wire ⭐

(Already derived above)
```
       μ₀I
B = ————————
       2πr
```

**Direction:** Circles around the wire — direction given by the **Right-Hand Thumb Rule**:
> Curl the right hand around the wire with the thumb pointing in the direction of current → fingers curl in the direction of magnetic field.

**Key fact:** B ∝ 1/r (similar to electric field of an infinite wire)

---

## 13. Solenoid and Toroid

### 13.1 Magnetic Field Due to a Solenoid ⭐⭐⭐ (Most Important Derivation)

**What is a Solenoid?**  
A solenoid is a long coil of wire with many closely spaced turns. When current flows through it, it behaves like a **bar magnet** and produces a strong, nearly uniform magnetic field inside.

**Let:**
- `n` = number of turns per unit length (n = N/L)
- `I` = current through the solenoid
- `L` = total length of solenoid

**Derivation using Ampere's Law:**

Choose a rectangular Amperian loop ABCD where:
- AB is inside the solenoid (length = l)
- BC and DA are perpendicular to the solenoid axis
- CD is outside the solenoid (B ≈ 0 outside)

Applying Ampere's Law:
```
∮ B · dl = μ₀ I_enclosed
```

Contributions:
- Along AB (inside, B parallel to dl): B × l
- Along BC and DA (B perpendicular to dl): 0
- Along CD (outside, B ≈ 0): 0

Total: B × l = μ₀ × (n × l) × I

**Magnetic field inside solenoid:**
```
B = μ₀nI
```

Or in terms of total turns N and length L:
```
         μ₀NI
B = ————————
            L
```

**Key observations:**
- B is **uniform** inside an ideal (long) solenoid.
- B is **zero** outside a solenoid.
- B depends on **n (turns per unit length)** and **I (current)**, NOT on the radius of the solenoid.

### 13.2 Magnetic Field Due to a Toroid ⭐⭐ (Board Exam Important)

**What is a Toroid?**  
A toroid is a solenoid bent into a circle (doughnut shape). It has no open ends. The magnetic field is entirely confined within the toroid.

**Derivation using Ampere's Law:**

**Case 1: Inside the toroid (r = mean radius of toroid)**

Choose circular Amperian loop of radius r inside:
```
B × 2πr = μ₀ × N × I

           μ₀NI
B = ————————
          2πr
```

Or if n = N/2πr (turns per unit length):
```
B = μ₀nI
```

**Case 2: Outside the toroid (r > outer radius or r < inner radius)**

No current is enclosed (currents in adjacent turns cancel for any outside loop):
```
B = 0
```

### 13.3 Comparison: Solenoid vs Toroid

| Property | Solenoid | Toroid |
|---|---|---|
| Shape | Straight cylinder | Circular (doughnut) |
| Field inside | B = μ₀nI (uniform) | B = μ₀NI/2πr |
| Field outside | ≈ 0 (for ideal long solenoid) | B = 0 (exactly) |
| Open ends | Yes | No (closed) |

---

## 14. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| F = qvB sinθ | Magnetic force on charge | N |
| r = mv/qB | Radius of circular path | m |
| T = 2πm/qB | Time period in magnetic field | s |
| f = qB/2πm | Cyclotron frequency | Hz |
| F = BIL sinθ | Force on current-carrying wire | N |
| F/L = μ₀I₁I₂/2πd | Force per unit length between wires | N/m |
| τ = NBIA sinθ | Torque on current loop | N·m |
| m = NIA | Magnetic dipole moment | A·m² |
| dB = μ₀Idl sinθ/4πr² | Biot-Savart Law | T |
| B = μ₀I/2πr | Field due to long wire | T |
| B = μ₀IR²/2(R²+x²)^(3/2) | Field on axis of circular loop | T |
| B = μ₀I/2R | Field at centre of circular loop | T |
| ∮B·dl = μ₀I | Ampere's Circuital Law | T·m |
| B = μ₀nI | Field inside solenoid | T |
| B = μ₀NI/2πr | Field inside toroid | T |
| μ₀ = 4π × 10⁻⁷ T·m/A | Permeability of free space | T·m/A |

---

## 15. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What is the SI unit of magnetic field?**  
**Ans:** Tesla (T)

**Q2. Write the expression for the force on a moving charge in a magnetic field.**  
**Ans:** F = qvB sinθ (or in vector form: F = q(v × B))

**Q3. When does a moving charge experience no magnetic force?**  
**Ans:** When the charge moves parallel or anti-parallel to the magnetic field (θ = 0° or 180°).

**Q4. What is the value of permeability of free space (μ₀)?**  
**Ans:** μ₀ = 4π × 10⁻⁷ T·m/A

**Q5. State the principle of a cyclotron.**  
**Ans:** The time period of revolution of a charged particle in a magnetic field is independent of its velocity. Hence the particle can be accelerated repeatedly using a resonant alternating electric field.

**Q6. What is the magnetic field at the centre of a circular loop of radius R carrying current I?**  
**Ans:** B = μ₀I / 2R

**Q7. Define magnetic dipole moment of a current loop.**  
**Ans:** Magnetic dipole moment m = NIA, where N = number of turns, I = current, A = area of loop. Its SI unit is A·m².

**Q8. State Ampere's Circuital Law.**  
**Ans:** The line integral of magnetic field B around any closed path equals μ₀ times the total current enclosed: ∮B·dl = μ₀I

**Q9. Why is the magnetic field inside a toroid zero outside it?**  
**Ans:** Because there is no net current enclosed by any Amperian loop outside the toroid — currents in adjacent loops cancel each other.

**Q10. Why cannot a cyclotron accelerate electrons?**  
**Ans:** Electrons gain very high speeds quickly, causing relativistic mass increase. The time period then changes, breaking the resonance condition with the oscillating electric field.

---

### 📝 2-Mark Questions

**Q11. State and explain Biot-Savart Law.**

**Ans:**  
The magnetic field dB at a point P due to a small current element Idl at distance r is:
```
dB = (μ₀/4π) × Idl sinθ / r²
```
- dB is proportional to I, dl, and sinθ
- dB is inversely proportional to r²
- Direction is given by right-hand rule (dl × r̂)

---

**Q12. Explain why a galvanometer cannot be used directly as an ammeter.**

**Ans:**  
A galvanometer has a **high resistance** and can tolerate only a **very small current** (microampere range). If used directly as an ammeter, most of the current would pass through the galvanometer, damaging it. Also, ammeter must have **very low resistance** to avoid disturbing the circuit. To convert a galvanometer to an ammeter, a **low resistance shunt is connected in parallel**.

---

**Q13. Two parallel wires carry currents in the same direction. What is the nature of the force between them? Explain.**

**Ans:**  
The wires will **attract** each other.

Wire 1 creates a magnetic field at wire 2. By Fleming's Left Hand Rule (or right-hand rule), the force on wire 2 due to this field acts toward wire 1. Similarly, wire 1 is attracted toward wire 2. The force per unit length is:
```
F/L = μ₀I₁I₂ / 2πd
```

---

**Q14. Write the differences between an ammeter and a voltmeter.**

**Ans:**

| Property | Ammeter | Voltmeter |
|---|---|---|
| Measures | Current | Voltage |
| Connected | In series | In parallel |
| Resistance | Very low | Very high |
| Conversion | Shunt in parallel | High R in series |

---

### 📝 3-Mark Questions

**Q15. Derive the expression for force per unit length between two parallel current-carrying conductors and state the definition of 1 Ampere.**

**Ans:** *(See Section 6 — write derivation)*

Result: F/L = μ₀I₁I₂ / 2πd

**Definition of 1 Ampere:** 1 A is that steady current which, flowing in each of two infinitely long parallel conductors 1 metre apart in vacuum, produces a force of 2 × 10⁻⁷ N/m between them.

---

**Q16. Derive the expression for torque on a current-carrying rectangular loop in a uniform magnetic field.**

**Ans:** *(See Section 7.1 — write derivation)*  
Result: τ = NBIA sinθ

---

**Q17. Explain the principle, construction, and working of a Moving Coil Galvanometer.**

**Ans:** *(See Section 8 — write all three parts)*  
Key formula: φ = NIAB/k (current sensitivity)

---

### 📝 5-Mark Questions (Long Answer)

**Q18. Describe the construction and working of a Cyclotron. Derive the expression for cyclotron frequency. What are its limitations?**

**Ans:** *(See Section 4 — write construction, working, formula, and limitations)*

Cyclotron frequency: f_c = qB / 2πm  
Max KE: K_max = q²B²R² / 2m

---

**Q19. Using Biot-Savart Law, derive the expression for magnetic field on the axis of a circular current loop.**

**Ans:** *(See Section 10 — write full derivation)*

Result: B = μ₀IR² / 2(R² + x²)^(3/2)  
At centre (x=0): B = μ₀I / 2R

---

**Q20. Using Ampere's Circuital Law, derive the magnetic field inside a solenoid.**

**Ans:** *(See Section 13.1 — write full derivation with diagram)*

Result: B = μ₀nI (inside solenoid)  
B = 0 (outside solenoid)

---

**Q21. Explain the conversion of a galvanometer into (i) an ammeter and (ii) a voltmeter. Derive the relevant expressions.**

**Ans:**  

**(i) Ammeter:** Connect shunt S in parallel:
```
S = I_g × G / (I − I_g)
```

**(ii) Voltmeter:** Connect high resistance R in series:
```
R = V/I_g − G
```

Draw diagrams for both conversions.

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** A proton moves with velocity 2×10⁶ m/s perpendicular to a magnetic field of 0.5 T. Find the radius of its circular path. (Mass of proton = 1.67×10⁻²⁷ kg, charge = 1.6×10⁻¹⁹ C)

**Solution:**
```
r = mv/qB
  = (1.67×10⁻²⁷ × 2×10⁶) / (1.6×10⁻¹⁹ × 0.5)
  = 3.34×10⁻²¹ / 8×10⁻²⁰
  = 0.04175 m ≈ 4.2 cm
```
**Answer: r ≈ 4.2 cm**

---

**Num 2:** Two parallel wires 0.05 m apart carry currents 3 A and 5 A in the same direction. Find the force per unit length between them.

**Solution:**
```
F/L = μ₀I₁I₂ / 2πd
    = (4π×10⁻⁷ × 3 × 5) / (2π × 0.05)
    = (4π×10⁻⁷ × 15) / (0.1π)
    = (60π×10⁻⁷) / (0.1π)
    = 6×10⁻⁵ N/m
```
**Answer: F/L = 6 × 10⁻⁵ N/m (attractive)**

---

**Num 3:** A galvanometer has resistance G = 50 Ω and full-scale deflection current I_g = 1 mA. Find the shunt resistance to convert it into an ammeter for measuring up to 5 A.

**Solution:**
```
S = I_g × G / (I − I_g)
  = (1×10⁻³ × 50) / (5 − 1×10⁻³)
  = 0.05 / 4.999
  ≈ 0.01 Ω
```
**Answer: S ≈ 0.01 Ω**

---

**Num 4:** A galvanometer (G = 50 Ω, I_g = 1 mA) is to be converted into a voltmeter of range 0–10 V. Find the series resistance required.

**Solution:**
```
R = V/I_g − G
  = 10 / (1×10⁻³) − 50
  = 10000 − 50
  = 9950 Ω
```
**Answer: R = 9950 Ω ≈ 9.95 kΩ**

---

**Num 5:** A solenoid of length 0.5 m has 500 turns and carries a current of 2 A. Find the magnetic field inside the solenoid.

**Solution:**
```
n = N/L = 500/0.5 = 1000 turns/m

B = μ₀nI = 4π×10⁻⁷ × 1000 × 2
  = 4π×10⁻⁷ × 2000
  = 8π×10⁻⁴
  ≈ 2.51×10⁻³ T
```
**Answer: B ≈ 2.51 × 10⁻³ T = 2.51 mT**

---

**Num 6:** A circular loop of radius 0.1 m carries a current of 5 A. Find the magnetic field at the centre.

**Solution:**
```
B = μ₀I / 2R
  = (4π×10⁻⁷ × 5) / (2 × 0.1)
  = 20π×10⁻⁷ / 0.2
  = 100π×10⁻⁷
  = π × 10⁻⁵
  ≈ 3.14×10⁻⁵ T
```
**Answer: B ≈ 3.14 × 10⁻⁵ T**

---

**Num 7:** A rectangular coil of 200 turns, area 0.02 m², carries current 0.5 A. It is placed in a uniform field of B = 0.3 T with its plane parallel to B. Find the torque on the coil.

**Solution:**
```
When plane is parallel to B → θ = 90° (angle between normal and B)

τ = NBIA sin90°
  = 200 × 0.3 × 0.5 × 0.02 × 1
  = 0.6 N·m
```
**Answer: τ = 0.6 N·m**

---

## 16. Objective / MCQ Questions

**Q1.** The SI unit of magnetic field intensity B is:
- (a) Weber
- **(b) Tesla** ✓
- (c) Gauss
- (d) Oersted

---

**Q2.** A charged particle moves in a magnetic field. The work done by the magnetic force on the particle is:
- (a) Positive
- (b) Negative
- **(c) Zero** ✓
- (d) Depends on velocity

---

**Q3.** The radius of the circular path of a charged particle in a magnetic field is:
- (a) r = qB/mv
- **(b) r = mv/qB** ✓
- (c) r = mv/qB²
- (d) r = m/qvB

---

**Q4.** The cyclotron frequency is independent of:
- (a) Charge of particle
- (b) Mass of particle
- (c) Magnetic field
- **(d) Velocity of particle** ✓

---

**Q5.** Two long parallel conductors carrying currents in opposite directions will:
- (a) Attract each other
- **(b) Repel each other** ✓
- (c) Have no force between them
- (d) Rotate each other

---

**Q6.** The torque on a current loop in a magnetic field is maximum when the angle between the magnetic moment and B is:
- (a) 0°
- **(b) 90°** ✓
- (c) 180°
- (d) 45°

---

**Q7.** A galvanometer is converted into a voltmeter by connecting:
- (a) A low resistance in parallel
- (b) A low resistance in series
- (c) A high resistance in parallel
- **(d) A high resistance in series** ✓

---

**Q8.** The magnetic field at the centre of a circular loop of radius R carrying current I is:
- (a) μ₀I/4πR
- (b) μ₀I/4R
- **(c) μ₀I/2R** ✓
- (d) 2μ₀I/R

---

**Q9.** Which of the following cannot be accelerated by a cyclotron?
- (a) Proton
- (b) Alpha particle
- (c) Deuteron
- **(d) Neutron** ✓

---

**Q10.** The magnetic field inside an ideal solenoid is:
- (a) Zero
- (b) Maximum at the ends
- **(c) Uniform and equal to μ₀nI** ✓
- (d) Depends on the radius of solenoid

---

**Q11.** Ampere's circuital law is analogous to:
- **(a) Gauss's Law in electrostatics** ✓
- (b) Coulomb's Law
- (c) Faraday's Law
- (d) Biot-Savart Law

---

**Q12.** A charge q moves with velocity v parallel to a magnetic field B. The magnetic force on the charge is:
- (a) qvB
- **(b) Zero** ✓
- (c) qvB/2
- (d) 2qvB

---

**Q13.** The magnetic field outside a toroid is:
- (a) μ₀nI
- (b) μ₀NI/2πr
- **(c) Zero** ✓
- (d) Infinite

---

**Q14.** 1 Ampere is defined using the force between two parallel wires carrying equal currents placed 1 m apart in vacuum, which produces a force per unit length of:
- (a) 1 N/m
- (b) 10⁻⁷ N/m
- **(c) 2 × 10⁻⁷ N/m** ✓
- (d) 4π × 10⁻⁷ N/m

---

**Q15.** The direction of the magnetic field around a long straight wire carrying current is given by:
- (a) Fleming's left hand rule
- (b) Lenz's law
- **(c) Right-hand thumb rule** ✓
- (d) Maxwell's screw rule (also correct — both c and d are equivalent)

---

## 17. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Cyclotron (construction, working, formula) | 5 marks |
| ⭐⭐⭐ | Solenoid field derivation (Ampere's Law) | 5 marks |
| ⭐⭐⭐ | Torque on current loop (derivation) | 5 marks |
| ⭐⭐⭐ | Moving Coil Galvanometer | 3–5 marks |
| ⭐⭐⭐ | Biot-Savart Law + Circular loop field | 5 marks |
| ⭐⭐ | Force between parallel wires + 1 A definition | 3 marks |
| ⭐⭐ | Ammeter/Voltmeter conversion formulas | 2–3 marks |
| ⭐⭐ | Circular motion of charge (radius, T, f) | 2–3 marks |
| ⭐ | Numericals | 2–3 marks |
| ⭐ | MCQs (Objective) | 1 mark each |

---

### 📌 Things to Memorize (Flash Cards)

```
μ₀ = 4π × 10⁻⁷ T·m/A
μ₀/4π = 10⁻⁷ T·m/A

Lorentz Force:         F = qvB sinθ
Radius (circular):     r = mv/qB
Time period:           T = 2πm/qB
Cyclotron freq:        f = qB/2πm
Force on wire:         F = BIL sinθ
Force/length (wires):  F/L = μ₀I₁I₂/2πd
Torque on loop:        τ = NBIA sinθ
Dipole moment:         m = NIA
Biot-Savart:           dB = μ₀Idl sinθ / 4πr²
Field (long wire):     B = μ₀I/2πr
Field (centre loop):   B = μ₀I/2R
Ampere's Law:          ∮B·dl = μ₀I
Field (solenoid):      B = μ₀nI
Field (toroid):        B = μ₀NI/2πr
Shunt (ammeter):       S = I_g G/(I−I_g)
Series R (voltmeter):  R = V/I_g − G
```

---

### 🔑 Key Differences to Remember

| | Biot-Savart Law | Ampere's Circuital Law |
|---|---|---|
| Best used for | Any current distribution | Highly symmetric situations |
| Form | Differential (dB) | Integral (∮B·dl) |
| Analogy | Coulomb's Law | Gauss's Law |

| | Solenoid | Toroid |
|---|---|---|
| Shape | Straight | Ring (closed) |
| Field inside | μ₀nI | μ₀NI/2πr |
| Field outside | ≈ 0 | Exactly 0 |

| | Ammeter | Voltmeter |
|---|---|---|
| Connection | Series | Parallel |
| Resistance | Low | High |
| Conversion | Low shunt ∥ | High R in series |

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn Lorentz Force formula + direction rule
- [ ] Practice radius, time period, frequency of circular motion
- [ ] Learn Cyclotron: principle, diagram, working, limitations
- [ ] Memorize force between parallel wires formula + definition of 1 A
- [ ] Practice Torque on current loop derivation (write 2 times)
- [ ] Learn Biot-Savart Law statement + formula
- [ ] Practice circular loop axis field derivation
- [ ] Learn Ampere's Law statement + solenoid derivation
- [ ] Practice galvanometer → ammeter and voltmeter conversion
- [ ] Memorize all formulas in Section 14
- [ ] Solve all 7 numerical problems
- [ ] Revise all MCQs in Section 16

---

### 💡 Common Mistakes to Avoid

1. **Magnetic force does NO work** → kinetic energy (speed) doesn't change — only direction changes.
2. **Cyclotron frequency** = qB/2πm — does NOT depend on speed or radius.
3. **Like currents attract, unlike currents repel** — opposite of electric charges!
4. **Torque formula:** τ = NBIA sinθ — NOT cosθ. θ = angle between magnetic moment (m) and B.
5. **For converting to ammeter:** shunt in PARALLEL. For voltmeter: resistance in SERIES.
6. **Inside solenoid:** B = μ₀nI (n = turns per unit length, NOT total turns N).
7. **Inside toroid:** B = μ₀NI/2πr. **Outside toroid:** B = 0 (exactly, not approximately).
8. **Biot-Savart vs Ampere:** Biot-Savart gives dB for an element; Ampere gives total B for symmetric configurations.
9. **Right-hand thumb rule** (field direction) vs **Fleming's Left Hand Rule** (force on conductor) — don't mix them up.
10. **Galvanometer pointer at 0° = stable equilibrium**, not at 90°. Torque is zero at θ = 0.

---

*Prepared for Bihar Board Class 12 Physics | Chapter 4: Moving Charges and Magnetism | Based on NCERT Textbook*