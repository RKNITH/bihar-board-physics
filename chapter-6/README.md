# 📘 Class 12 Physics — Chapter 6: Electromagnetic Induction
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Experiments of Faraday and Henry](#2-experiments-of-faraday-and-henry)
3. [Magnetic Flux](#3-magnetic-flux)
4. [Faraday's Laws of Electromagnetic Induction](#4-faradays-laws-of-electromagnetic-induction)
5. [Lenz's Law and Conservation of Energy](#5-lenzs-law-and-conservation-of-energy)
6. [Motional EMF](#6-motional-emf)
7. [Energy Consideration — A Quantitative Study](#7-energy-consideration--a-quantitative-study)
8. [Eddy Currents](#8-eddy-currents)
9. [Inductance](#9-inductance)
   - [9.1 Mutual Inductance](#91-mutual-inductance)
   - [9.2 Self-Inductance](#92-self-inductance)
10. [AC Generator](#10-ac-generator)
11. [Important Formulas Summary](#11-important-formulas-summary)
12. [Board Exam Questions with Answers](#12-board-exam-questions-with-answers)
13. [Objective / MCQ Questions](#13-objective--mcq-questions)
14. [Quick Revision Tips](#14-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter explores one of the most **revolutionary discoveries in Physics** — that a **changing magnetic field can produce electric current**.

Think of it this way:
- A dynamo generates electricity in your bicycle. **How?** → Electromagnetic Induction.
- Power reaches your home from far-away power stations. **How?** → Transformers use EMI.
- An induction cooktop heats your food without flame. **How?** → Eddy currents from EMI.
- Electric guitar pickups convert string vibrations to sound. **How?** → EMI!

**What you will learn:**
- Faraday's and Lenz's Laws — the foundation of electricity generation
- Magnetic Flux and induced EMF
- Motional EMF — electricity from motion
- Eddy currents and their uses
- Self-inductance and Mutual inductance
- How an AC Generator works

> 💡 **Why it matters for Board Exam:** This chapter carries **significant weight** in Bihar Board exams. Derivations (motional EMF, mutual inductance, AC generator) come directly for 3–5 marks each. Do NOT skip this chapter!

---

## 2. Experiments of Faraday and Henry

### 2.1 Background

**Michael Faraday** (England) and **Joseph Henry** (USA) independently discovered electromagnetic induction around **1830–1831**.

Their key observation: **A changing magnetic field induces an electric current.**

### 2.2 Faraday's Key Experiments

#### Experiment 1 — Magnet and Coil

**Setup:** A galvanometer (current detector) is connected to a coil. A bar magnet is moved toward or away from the coil.

**Observations:**
| Action | Galvanometer | Conclusion |
|---|---|---|
| Magnet moved **toward** coil | Deflects (current flows) | Changing B induces current |
| Magnet **stationary** near coil | No deflection | Constant B → no current |
| Magnet moved **away** from coil | Deflects in **opposite** direction | Decreasing B → opposite current |
| Magnet moved **faster** | Larger deflection | Faster change → more EMF |

#### Experiment 2 — Two Coils (Coil-Galvanometer Setup)

**Setup:** Coil-1 is connected to a battery and switch. Coil-2 is placed nearby, connected to a galvanometer.

**Observations:**
- When **switch is closed** (current starts in Coil-1): Galvanometer deflects momentarily
- When **current is steady** in Coil-1: No deflection
- When **switch is opened** (current stops in Coil-1): Galvanometer deflects in opposite direction

**Conclusion:** It is not the current itself, but the **change in current (and hence change in magnetic field)** that induces EMF in the second coil.

### 2.3 Key Conclusion

> *"Whenever there is a change in the magnetic flux linked with a circuit, an EMF (and hence a current) is induced in the circuit. The induced EMF lasts only as long as the flux is changing."*

---

## 3. Magnetic Flux

### 3.1 Definition ⭐ (Board Exam — 2 Mark)

**Definition:** *"Magnetic flux through a surface is defined as the total number of magnetic field lines passing normally through that surface."*

```
φ_B = B × A × cosθ
```

Where:
- `φ_B` = Magnetic flux (Weber, Wb)
- `B` = Magnetic field (Tesla, T)
- `A` = Area of the surface (m²)
- `θ` = Angle between **B** and the **normal to the surface** (area vector)

**In vector form:**
```
→  →
φ_B = B · A = BA cosθ
```

### 3.2 Unit and Dimension

- **SI Unit:** Weber (Wb) = Tesla × m² = V·s
- **CGS Unit:** Maxwell (Mx)
- **Dimension:** [M L² T⁻² A⁻¹]

### 3.3 Special Cases

| Angle θ | Flux φ_B | Situation |
|---|---|---|
| 0° (B ⊥ to surface plane) | φ = BA (Maximum) | B normal to surface |
| 90° (B ∥ to surface) | φ = 0 | B parallel to surface |
| 180° | φ = −BA | B opposite to normal |

> 📝 **Board Exam Tip:** Magnetic flux is a **scalar quantity**. Its SI unit is Weber (Wb). 1 Wb = 1 T·m².

---

## 4. Faraday's Laws of Electromagnetic Induction

### 4.1 First Law ⭐⭐ (Statement — Board Exam Must)

**Statement:** *"Whenever the magnetic flux linked with a circuit changes, an EMF is induced in the circuit. The induced EMF exists only as long as the change in flux continues."*

### 4.2 Second Law ⭐⭐ (Statement + Formula — Board Exam Must)

**Statement:** *"The magnitude of the induced EMF in a circuit is directly proportional to the rate of change of magnetic flux linked with the circuit."*

```
        dφ_B
|ε| =  ——————
         dt
```

**With the negative sign (Lenz's Law included):**
```
        dφ_B
ε =  − ——————
          dt
```

Where:
- `ε` = Induced EMF (Volt, V)
- `dφ_B` = Change in magnetic flux (Weber, Wb)
- `dt` = Time interval (second, s)
- The **negative sign** indicates that the induced EMF opposes the change in flux (Lenz's Law)

### 4.3 For a Coil with N Turns

If the coil has `N` turns, the total flux linkage = Nφ_B

```
        d(Nφ_B)       dφ_B
ε =  − ————————— = −N ——————
           dt           dt
```

> 📝 **Board Exam Note:** This formula is extremely important. Learn both the 1-turn version and the N-turn version.

### 4.4 Induced Current and Charge

Induced current in a circuit of resistance R:
```
     ε       1   dφ_B
I = ——— = − ———  ——————
     R       R    dt
```

Induced charge (independent of time!):
```
      Nφ_B       N × ΔΦ
q = ——————— = ————————————
       R              R
```

> 💡 **Key Insight:** Induced charge depends on the **change in flux** and resistance — NOT on how fast the change happens!

---

## 5. Lenz's Law and Conservation of Energy

### 5.1 Statement ⭐⭐ (Most Important — Board Exam Favourite)

**Statement:** *"The induced EMF (or induced current) in a circuit is always in such a direction as to oppose the cause that produces it."*

OR in simpler words:

*"The induced current always flows in such a direction that the magnetic field it creates opposes the change in magnetic flux that produced it."*

### 5.2 Explanation with Example

**Case 1 — Magnet approaching the coil:**
- The north pole of a magnet is brought toward the face of a coil.
- Flux through the coil **increases**.
- By Lenz's Law, the induced current must **oppose** this increase.
- So the induced current creates a **north pole** on the face facing the magnet (to repel it).
- By the right-hand rule, the induced current flows **anticlockwise** (when viewed from the magnet side).

**Case 2 — Magnet moving away from the coil:**
- The north pole is moved **away** from the coil.
- Flux through the coil **decreases**.
- Induced current must **oppose** this decrease.
- So the induced current creates a **south pole** on the face facing the magnet (to attract it and maintain flux).
- Induced current flows **clockwise** (when viewed from magnet side).

### 5.3 Lenz's Law and Conservation of Energy ⭐ (Conceptual — 3 Mark)

Lenz's Law is a consequence of **Conservation of Energy**. Here's why:

- When you push a magnet toward the coil, the coil **repels** the magnet (opposing motion).
- You have to do **work** against this opposition.
- This **mechanical work** gets converted into **electrical energy** (the induced current).

If the induced current instead **attracted** the magnet, the magnet would accelerate without any energy input — this would violate the law of conservation of energy. Hence, the induced current MUST oppose the cause.

> 📝 **Board Exam Note:** This is a 3-mark conceptual question. Write: Statement → Example → Connection to Energy Conservation.

### 5.4 Lenz's Law — The Negative Sign

The negative sign in Faraday's Law (`ε = −dφ/dt`) mathematically represents Lenz's Law.

---

## 6. Motional EMF

### 6.1 Concept

When a **conductor moves** through a magnetic field, free electrons in the conductor experience a magnetic force, which causes them to drift — producing an EMF. This is called **Motional EMF**.

### 6.2 Derivation ⭐⭐ (5 Mark Derivation — Bihar Board)

**Setup:**
- A conducting rod PQ of length `l` is placed on two parallel rails separated by distance `l`.
- The rails are in a plane perpendicular to a uniform magnetic field **B** (directed into the page).
- The rod moves to the right with velocity **v**.

**Step 1:** As the rod moves right by `dx` in time `dt`:

Area swept by the rod:
```
dA = l × dx
```

Change in magnetic flux:
```
dφ_B = B × dA = B × l × dx
```

**Step 2:** By Faraday's Law, induced EMF:
```
         dφ_B     B × l × dx
|ε| =  ——————— = ————————————
           dt          dt
```

Since `dx/dt = v` (velocity of the rod):
```
|ε| = Blv
```

**Motional EMF formula:**
```
ε = Blv
```

Where:
- `ε` = Induced EMF (V)
- `B` = Magnetic field (T)
- `l` = Length of the conductor (m)
- `v` = Velocity of the conductor (m/s)

### 6.3 Force on the Free Charges (Alternate Derivation)

Consider a free electron in the rod moving with velocity v to the right.

Magnetic force on the electron:
```
F = qvB = evB       (using F = qv × B)
```

This force acts from Q to P (i.e., upward if B is into the page and v is rightward).

The work done per unit charge in moving from Q to P = EMF:
```
ε = F/e × l = (evB/e) × l = Bvl
```

Same result: **ε = Blv** ✓

### 6.4 Induced Current (if circuit is closed)

If the rod slides on rails connected by an external resistance R:
```
     ε      Blv
I = ——— = ———————
     R        R
```

### 6.5 Direction of Induced Current

Use the **right-hand thumb rule** or **Fleming's right-hand rule** (for generators):
- Point fingers in the direction of **B** (field)
- Curl in the direction of **v** (motion)
- **Thumb** gives direction of induced current in the rod

---

## 7. Energy Consideration — A Quantitative Study

### 7.1 Power Required to Move the Rod

When the rod carries induced current `I` in magnetic field `B`, it experiences a retarding force:
```
F_retard = BIl = B × (Blv/R) × l = B²l²v / R
```

Power required to move the rod at constant velocity v:
```
P_input = F × v = (B²l²v/R) × v = B²l²v² / R
```

### 7.2 Power Dissipated in Resistance

```
             ε²       (Blv)²     B²l²v²
P_dissipated = ——— = ————————— = ————————
               R         R           R
```

**P_input = P_dissipated** ✓

This confirms **Conservation of Energy** — all the mechanical energy input is converted into electrical (heat) energy in the circuit.

> 📝 **Board Exam Note:** This section is a 3-mark numerical + conceptual section. Always verify input power = output power.

---

## 8. Eddy Currents

### 8.1 Definition ⭐ (Very Important — 2 Mark)

**Definition:** *"When a bulk piece of conductor (metal) is placed in a changing magnetic field, induced currents are set up throughout the volume of the conductor. These are called Eddy Currents or Foucault Currents."*

These currents flow in **closed loops** within the conductor, like swirling eddies in water — hence the name.

### 8.2 Cause

Changing magnetic flux → induces EMF (Faraday's Law) → since the conductor is a bulk material with many paths, currents flow in loops within the metal body.

### 8.3 Effects of Eddy Currents

- They produce **heat** in the conductor (energy loss).
- They create a **retarding force** opposing the motion (Lenz's Law).
- They can cause significant **energy loss** in transformer cores, motors, etc.

### 8.4 How to Reduce Eddy Currents ⭐ (Board Exam)

To reduce eddy currents (and the energy loss they cause), the metal core is made of **thin laminated sheets** insulated from each other.

- Each thin lamination has high resistance to eddy current path.
- The overall eddy current (and energy loss) is greatly reduced.
- This is why **transformer cores are laminated**.

> 📝 **Board Exam Tip:** Question often asked: "Why are transformer cores laminated?" Answer: To reduce eddy current losses.

### 8.5 Applications of Eddy Currents ⭐ (3 Mark)

| Application | How Eddy Currents Help |
|---|---|
| **Magnetic Braking** | Retarding force on moving conductor used in trains and roller coasters |
| **Induction Furnace** | Eddy currents heat and melt metals (used in metallurgy) |
| **Electromagnetic Damping** | Galvanometers use eddy currents to damp needle oscillations quickly |
| **Induction Cooktop** | Eddy currents in the vessel bottom produce heat for cooking |
| **Electric Meters / Speedometers** | Eddy currents cause deflection proportional to speed |

---

## 9. Inductance

**Inductance** is the property of a conductor by which it **opposes any change in the current flowing through it** by inducing an EMF.

There are two types:
1. **Mutual Inductance (M)** — between two coils
2. **Self-Inductance (L)** — within the same coil

---

### 9.1 Mutual Inductance

#### Definition ⭐ (Board Exam — 2 Mark)

**Definition:** *"Mutual inductance is the property of a pair of coils by virtue of which an EMF is induced in one coil when the current in the neighbouring coil changes."*

#### Mathematical Expression

When current `I₁` flows in Coil-1, the flux through Coil-2 is:
```
φ₂₁ = M × I₁
```

For N₂ turns in Coil-2:
```
N₂φ₂₁ = M × I₁
```

Induced EMF in Coil-2:
```
          d(N₂φ₂₁)        dI₁
ε₂ =  − —————————— = −M ——————
              dt              dt
```

Where `M` = Mutual Inductance (Henry, H)

#### Formula for Mutual Inductance of Two Coaxial Solenoids ⭐⭐ (Derivation — Board Exam)

**Setup:**
- Solenoid-1 (primary): N₁ turns, length l, area A
- Solenoid-2 (secondary): N₂ turns, wound over Solenoid-1

**Derivation:**

Magnetic field inside Solenoid-1 when current I₁ flows:
```
B₁ = μ₀n₁I₁ = μ₀(N₁/l)I₁
```

Flux through each turn of Solenoid-2 (same area A):
```
φ = B₁ × A = μ₀(N₁/l)I₁ × A
```

Total flux linkage with Solenoid-2:
```
N₂φ = N₂ × μ₀(N₁/l)I₁A = μ₀N₁N₂A I₁ / l
```

By definition, N₂φ = M × I₁:
```
        μ₀N₁N₂A
M =  ————————————
           l
```

Where:
- `μ₀` = 4π × 10⁻⁷ H/m (Permeability of free space)
- `N₁`, `N₂` = Number of turns in each solenoid
- `A` = Cross-sectional area (m²)
- `l` = Length of the solenoid (m)

#### Unit and Dimension of Mutual Inductance

- **SI Unit:** Henry (H) = Wb/A = V·s/A = Ω·s
- **Dimension:** [M L² T⁻² A⁻²]

#### Definition of 1 Henry

*"The mutual inductance between two coils is said to be 1 Henry if a current changing at the rate of 1 A/s in one coil induces an EMF of 1 Volt in the neighbouring coil."*

> 📝 **Board Exam Note:** Derivation of M for two coaxial solenoids comes for 3 marks. Learn each step clearly.

---

### 9.2 Self-Inductance

#### Definition ⭐⭐ (Very Important — Board Exam)

**Definition:** *"Self-inductance is the property of a coil by virtue of which it opposes any change in the magnitude of current flowing through it, by inducing an EMF in itself."*

This induced EMF is called **back EMF** or **self-induced EMF**.

#### Mathematical Expression

The magnetic flux linked with the coil is proportional to the current:
```
Nφ = L × I
```

Induced EMF:
```
         d(Nφ)        dI
ε = − ——————— = −L ——————
           dt            dt
```

Where `L` = Self-Inductance (Henry, H)

#### Self-Inductance of a Solenoid ⭐⭐ (Derivation — Board Exam)

**Setup:** A solenoid of N turns, length l, cross-sectional area A, carrying current I.

**Derivation:**

Magnetic field inside the solenoid:
```
B = μ₀nI = μ₀(N/l)I
```

Flux through each turn:
```
φ = B × A = μ₀(N/l)IA
```

Total flux linkage:
```
Nφ = N × μ₀(N/l)IA = μ₀N²A/l × I
```

By definition, Nφ = LI:
```
        μ₀N²A
L =  ————————————
           l
```

Can also be written as:
```
L = μ₀n²Al       where n = N/l (turns per unit length)
```

#### Definition of 1 Henry (for Self-Inductance)

*"The self-inductance of a coil is 1 Henry if a current changing at the rate of 1 A/s induces a back EMF of 1 Volt in the coil itself."*

#### Energy Stored in an Inductor ⭐ (Board Exam — 2 Mark)

When a current I flows through an inductor of self-inductance L, the energy stored in its magnetic field is:

```
U = ½ LI²
```

**Derivation (brief):**

Work done against the back EMF to build current from 0 to I:
```
dW = ε × I × dt = L(dI/dt) × I × dt = LI dI
```

Integrating from 0 to I:
```
W = ∫₀ᴵ LI dI = ½LI²
```

This energy is stored in the **magnetic field** of the inductor.

#### Energy Density in Magnetic Field

Energy per unit volume stored in the magnetic field:
```
u = B² / 2μ₀
```

> 📝 **Board Exam Note:** U = ½LI² is analogous to the energy stored in a capacitor: U = ½CV². Learn both for comparison questions.

---

## 10. AC Generator

### 10.1 Principle ⭐ (Board Exam — 1 Mark)

**Principle:** *"An AC generator works on the principle of electromagnetic induction. When a coil rotates in a magnetic field, the magnetic flux through it changes continuously, thereby inducing an alternating EMF."*

### 10.2 Construction ⭐⭐ (Board Exam — 3 Mark with Diagram)

**Main Parts:**

| Part | Function |
|---|---|
| **Field Magnet** (permanent or electromagnet) | Provides the magnetic field |
| **Armature Coil** (ABCD) | Rectangular coil that rotates in the field; made of insulated copper wire wound on a soft iron core |
| **Slip Rings** | Two circular rings attached to the ends of the armature; rotate with it |
| **Carbon Brushes** | Stationary conductors that press against the slip rings; connect to external circuit |
| **External Resistance** | Load connected between the two brushes |

```
Diagram (Side View):

        N   |  S
            |
      ──────────────
      |      ABCD  |
      |  [Coil]    |
      ──────────────
           ↕  ↕
       Slip Rings
           ↕  ↕
       Carbon Brushes
           ↕  ↕
         External
         Circuit
```

### 10.3 Working ⭐⭐ (Board Exam — 3 Mark)

1. The armature coil **ABCD** is rotated at uniform angular velocity ω in the magnetic field **B**.
2. As the coil rotates, the angle between **B** and the normal to the coil changes.
3. The magnetic flux changes continuously → induced EMF is produced (Faraday's Law).
4. This EMF is alternating — it reverses direction every half rotation.

### 10.4 Derivation of EMF — Expression ⭐⭐⭐ (5 Mark Derivation — Must Learn!)

**Setup:**
- Rectangular coil of N turns, area A, rotating with angular velocity ω
- Uniform magnetic field B perpendicular to the axis of rotation

**Step 1:** At time t, the coil has rotated by angle `θ = ωt` from its initial position (where it was perpendicular to B).

**Step 2:** Magnetic flux through the coil at time t:
```
φ = NBA cosθ = NBA cos(ωt)
```

**Step 3:** By Faraday's Law, induced EMF:
```
         dφ              d
ε = − ——————— = − NBA ——— [cos(ωt)]
          dt               dt

ε = − NBA × (−ω sin(ωt))

ε = NBAω sin(ωt)
```

**Writing as:** `ε₀ = NBAω` (maximum EMF)

```
ε = ε₀ sin(ωt)
```

Where:
- `ε` = Instantaneous EMF
- `ε₀` = Peak (maximum) EMF = NBAω
- `ω` = Angular velocity of rotation (rad/s)
- `t` = Time (s)

**This is an alternating EMF — varies sinusoidally with time.**

### 10.5 Special Positions of the Coil

| Position of Coil | Angle θ | Flux φ | EMF ε |
|---|---|---|---|
| Coil ⊥ to B (plane parallel to B) | 90° | φ = 0 | ε = ε₀ (Maximum) |
| Coil ∥ to B (plane perpendicular to B) | 0° | φ = NBA (Max) | ε = 0 (Minimum) |
| After half rotation | 270° | φ = 0 | ε = −ε₀ (Max in opposite direction) |

> 📝 **Board Exam Tip:** The coil produces **maximum EMF** when it is **parallel** to the magnetic field (flux is changing fastest). It produces **zero EMF** when perpendicular to B (flux is at maximum, rate of change = 0).

### 10.6 Graph of EMF vs Time

```
  ε
  |
ε₀|     *         *
  |   *   *     *   *
  |  *     *   *     *
  | *       * *       *
  |*         *         *
──────────────────────────→ t
  |0    T/2   T    3T/2  
  |          * *
  |         *   *
  |        *     *
−ε₀|               *
  |
```
The EMF varies as ε = ε₀ sin(ωt).

### 10.7 AC vs DC Generator (Dynamo)

| Feature | AC Generator | DC Generator |
|---|---|---|
| Output | Alternating current | Direct current |
| Uses | Slip rings + brushes | Split-ring commutator + brushes |
| Rectification | Not needed | Built-in (commutator reverses connection) |
| Used in | Power stations, alternators | Vehicles, portable devices |

---

## 11. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| `φ_B = BA cosθ` | Magnetic Flux | Weber (Wb) |
| `ε = −dφ_B/dt` | Faraday's Law (1 turn) | Volt (V) |
| `ε = −N dφ_B/dt` | Faraday's Law (N turns) | Volt (V) |
| `ε = Blv` | Motional EMF | Volt (V) |
| `I = Blv/R` | Induced Current | Ampere (A) |
| `F = B²l²v/R` | Retarding Force on rod | Newton (N) |
| `M = μ₀N₁N₂A/l` | Mutual Inductance (solenoid) | Henry (H) |
| `ε₂ = −M(dI₁/dt)` | EMF due to mutual induction | Volt (V) |
| `L = μ₀N²A/l` | Self-Inductance (solenoid) | Henry (H) |
| `ε = −L(dI/dt)` | Back EMF (self-induction) | Volt (V) |
| `U = ½LI²` | Energy stored in inductor | Joule (J) |
| `u = B²/2μ₀` | Energy density in magnetic field | J/m³ |
| `ε₀ = NBAω` | Peak EMF of AC Generator | Volt (V) |
| `ε = ε₀ sin(ωt)` | Instantaneous EMF | Volt (V) |

---

## 12. Board Exam Questions with Answers

### Q1. State Faraday's laws of electromagnetic induction. (2 Marks)

**Answer:**

**First Law:** Whenever the magnetic flux linked with a circuit changes, an EMF is induced in the circuit. The induced EMF persists only as long as the change in flux continues.

**Second Law:** The magnitude of the induced EMF is directly proportional to the rate of change of magnetic flux linked with the circuit.

Mathematically: `ε = −N dφ_B/dt`

The negative sign indicates Lenz's Law — the induced EMF opposes the change causing it.

---

### Q2. State and explain Lenz's Law. How is it consistent with Conservation of Energy? (3 Marks)

**Answer:**

**Statement:** The induced EMF (or current) is always in such a direction as to oppose the cause that produces it.

**Explanation:** When a north pole approaches a coil, flux increases. The induced current creates a north pole on the near face of the coil (opposing the approach). When the north pole moves away, the induced current creates a south pole (opposing the withdrawal).

**Energy Conservation:** To push the magnet against the opposing magnetic force, we do mechanical work. This work is converted into electrical energy of the induced current. If the induced current aided the motion, energy would be created from nothing — violating conservation of energy. Hence Lenz's Law is a consequence of energy conservation.

---

### Q3. Derive an expression for Motional EMF. (3 Marks)

**Answer:**

When a conductor of length `l` moves with velocity `v` perpendicular to a magnetic field `B`:

In time dt, area swept = l × dx = l × v dt

Change in flux: `dφ = B × l × v × dt`

By Faraday's Law:
```
|ε| = dφ/dt = Blv
```

∴ **Motional EMF: ε = Blv**

Direction is determined by Lenz's Law (or Fleming's right-hand rule).

---

### Q4. What are eddy currents? Give two applications. (3 Marks)

**Answer:**

**Eddy Currents:** When a bulk conductor is placed in a changing magnetic field, circulating currents are induced throughout its volume. These are called eddy currents or Foucault currents.

**Two Applications:**
1. **Magnetic Braking in Trains:** Eddy currents in the metal disc produce a retarding force that slows the train smoothly without mechanical friction.
2. **Induction Furnace:** Eddy currents generated in metals by a high-frequency alternating field heat and melt the metal — used in steel manufacturing.

---

### Q5. Define self-inductance. Derive the expression for self-inductance of a solenoid. (5 Marks)

**Answer:**

**Definition:** Self-inductance is the property of a coil by virtue of which it opposes any change in current through it, by inducing a back EMF in itself.
```
ε = −L dI/dt
```
1 Henry = the self-inductance when a rate of change of current of 1 A/s induces a back EMF of 1 V.

**Derivation for Solenoid:**

For a solenoid of N turns, length l, area A, carrying current I:
- Magnetic field: `B = μ₀(N/l)I`
- Flux per turn: `φ = BA = μ₀(N/l)IA`
- Total flux linkage: `Nφ = μ₀N²IA/l`
- Since `Nφ = LI`:

```
      μ₀N²A
L = ———————————
          l
```

Or in terms of n (turns per unit length):
```
L = μ₀n²Al
```

---

### Q6. Derive the expression for EMF generated by an AC Generator. (5 Marks)

**Answer:**

**Principle:** Electromagnetic induction — rotating coil in a magnetic field experiences changing flux.

**Let:**
- N = number of turns
- A = area of coil
- B = magnetic field
- ω = angular velocity

**At time t**, angle rotated = ωt

Magnetic flux: `φ = NBA cos(ωt)`

By Faraday's Law:
```
ε = −dφ/dt = −NBA × d[cos(ωt)]/dt = NBAω sin(ωt)
```

Let `ε₀ = NBAω` (peak EMF):

```
ε = ε₀ sin(ωt)
```

This is the required expression. The output is a sinusoidal alternating EMF.
- ε = 0 when coil is perpendicular to B (θ = 0°)
- ε = ε₀ (maximum) when coil is parallel to B (θ = 90°)

---

### Q7. Numerical — Motional EMF (3 Marks)

**Q:** A conducting rod of length 1 m is moved with a velocity of 5 m/s perpendicular to a magnetic field of 0.8 T. Find (a) the induced EMF, (b) the induced current if the circuit resistance is 2 Ω.

**Solution:**

Given: l = 1 m, v = 5 m/s, B = 0.8 T, R = 2 Ω

(a) `ε = Blv = 0.8 × 1 × 5 = **4 V**`

(b) `I = ε/R = 4/2 = **2 A**`

---

### Q8. Numerical — Mutual Inductance (2 Marks)

**Q:** The mutual inductance between two coils is 5 H. If the current in one coil changes at the rate of 3 A/s, find the induced EMF in the other coil.

**Solution:**

`ε = M × dI/dt = 5 × 3 = **15 V**`

---

### Q9. Numerical — Energy in Inductor (2 Marks)

**Q:** A solenoid has self-inductance 2 H. Calculate the energy stored when a current of 3 A flows through it.

**Solution:**

`U = ½LI² = ½ × 2 × (3)² = ½ × 2 × 9 = **9 J**`

---

## 13. Objective / MCQ Questions

**Q1.** The SI unit of magnetic flux is:
- (a) Tesla
- (b) Henry
- **(c) Weber** ✓
- (d) Volt

---

**Q2.** Lenz's Law is a consequence of the law of conservation of:
- (a) Charge
- **(b) Energy** ✓
- (c) Momentum
- (d) Mass

---

**Q3.** The induced EMF in a coil does NOT depend on:
- **(a) The resistance of the coil** ✓
- (b) Rate of change of flux
- (c) Number of turns
- (d) Magnitude of flux change

---

**Q4.** Eddy currents are reduced in transformer cores by:
- (a) Using copper cores
- **(b) Using laminated cores** ✓
- (c) Increasing the area of the core
- (d) Using thick iron plates

---

**Q5.** The self-inductance of a solenoid is doubled if:
- (a) Its length is doubled (keeping N, A same)
- **(b) The number of turns per unit length is doubled** ✓
- (c) Its area is halved
- (d) The current is doubled

---

**Q6.** When the current in a coil changes from 2 A to 4 A in 0.5 s, an EMF of 8 V is induced. The self-inductance of the coil is:
- (a) 1 H
- **(b) 2 H** ✓
- (c) 4 H
- (d) 0.5 H

> _Hint: ε = L × ΔI/Δt → 8 = L × (4−2)/0.5 → L = 8×0.5/2 = 2 H_

---

**Q7.** In an AC generator, the EMF is maximum when the plane of the coil is:
- **(a) Parallel to the magnetic field** ✓
- (b) Perpendicular to the magnetic field
- (c) At 45° to the magnetic field
- (d) None of the above

---

**Q8.** Which of the following devices works on the principle of mutual induction?
- (a) AC Generator
- (b) Electric motor
- **(c) Transformer** ✓
- (d) Induction cooktop

---

**Q9.** The peak EMF of an AC Generator with N = 100 turns, A = 0.01 m², B = 1 T, ω = 100 rad/s is:
- **(a) 100 V** ✓
- (b) 1000 V
- (c) 10 V
- (d) 50 V

> _Hint: ε₀ = NBAω = 100 × 1 × 0.01 × 100 = 100 V_

---

**Q10.** The energy stored in an inductor of inductance L carrying current I is:
- (a) LI
- (b) LI²
- **(c) ½LI²** ✓
- (d) 2LI²

---

## 14. Quick Revision Tips

### ⚡ Most Important Topics for Bihar Board

| Topic | Marks Likely | Priority |
|---|---|---|
| Faraday's Laws — Statement + Formula | 2 | ⭐⭐⭐ |
| Lenz's Law + Energy Conservation | 3 | ⭐⭐⭐ |
| Motional EMF Derivation | 3–5 | ⭐⭐⭐ |
| Self-Inductance of Solenoid Derivation | 3–5 | ⭐⭐⭐ |
| Mutual Inductance of Solenoids Derivation | 3–5 | ⭐⭐⭐ |
| AC Generator — Construction, Working, Derivation | 5 | ⭐⭐⭐ |
| Eddy Currents — Definition + Applications | 2–3 | ⭐⭐ |
| Energy in Inductor: U = ½LI² | 2 | ⭐⭐ |
| Numericals (Motional EMF, Inductance) | 2–3 | ⭐⭐ |

---

### 🧠 Memory Tricks

| Concept | Trick |
|---|---|
| **Lenz's Law direction** | "The coil is LAZY — it resists change!" |
| **Motional EMF = Blv** | **B**ig **L**ong **V**ehicle (Big Long Vehicle produces EMF) |
| **Self-Inductance formula** | L = μ₀N²A/l → "**MAN**uel drives a **L**ong car" |
| **Peak EMF of Generator** | ε₀ = NBAω → **N**ever **B**uy **A**ny **ω**atches |
| **EMF max when coil || B** | When parallel to field, flux is changing FASTEST |
| **U = ½LI²** | Just like capacitor: U = ½CV² → same formula structure |

---

### 📌 Key Differences to Remember

**Lenz's Law vs Faraday's Law:**
- Faraday's Law tells the **magnitude** of induced EMF
- Lenz's Law tells the **direction** of induced EMF
- Lenz's Law is already included as the **negative sign** in Faraday's equation

**Self-Inductance vs Mutual Inductance:**
- Self-inductance: coil opposes change in its **own** current
- Mutual inductance: one coil induces EMF in **another** coil
- Transformer works on mutual inductance; choke coils work on self-inductance

**Slip rings (AC Generator) vs Commutator (DC Generator):**
- Slip rings allow continuous contact → output alternates → **AC**
- Commutator reverses connection every half turn → output is always one direction → **DC**

---

### 📝 Board Exam Answer Format Tips

1. **For theory questions:** Write Statement → Formula → Diagram (if needed) → Special Cases
2. **For derivation questions:** Write Principle → Setup → Step-by-step math → Final formula → Unit
3. **For numericals:** Write Given → Formula → Substitution → Answer with unit
4. **For diagram questions:** Label ALL parts clearly — coil, magnets, slip rings, brushes, galvanometer/voltmeter
5. **Negative sign in Faraday's Law:** Always write it and explain it = Lenz's Law (examiners check this!)

---

### 🔁 Last-Day Revision Checklist

- [ ] Faraday's First and Second Laws — statements memorized
- [ ] Lenz's Law — statement + example + energy connection
- [ ] Motional EMF derivation (ε = Blv) — every step clear
- [ ] Self-Inductance derivation for solenoid (L = μ₀N²A/l)
- [ ] Mutual Inductance derivation for two coaxial solenoids (M = μ₀N₁N₂A/l)
- [ ] Energy in inductor (U = ½LI²) — can derive it
- [ ] AC Generator — all parts, working, EMF derivation (ε = ε₀ sinωt)
- [ ] Eddy currents — definition, why lamination reduces them, 2–3 applications
- [ ] All formulas in summary table memorized
- [ ] 2–3 numericals practiced from each topic

---

> 💬 **Final Words:** Electromagnetic Induction is one of the most application-rich chapters in Class 12 Physics. Every electrical device around you — from your phone charger to the power grid — works because of what you learned here. Understand the concepts deeply, not just the formulas, and the board exam becomes easy. Best of luck! 🌟

---

*📘 Bihar Board (BSEB) | Class 12 Physics | Chapter 6: Electromagnetic Induction*
*Based on NCERT Textbook | For Board Exam Preparation*