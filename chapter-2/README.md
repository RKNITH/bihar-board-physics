# 📘 Class 12 Physics — Chapter 2: Electrostatic Potential and Capacitance
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Electric Potential Energy](#2-electric-potential-energy)
3. [Electric Potential](#3-electric-potential)
4. [Potential Due to a Point Charge](#4-potential-due-to-a-point-charge)
5. [Potential Due to a System of Charges](#5-potential-due-to-a-system-of-charges)
6. [Potential Due to an Electric Dipole](#6-potential-due-to-an-electric-dipole)
7. [Equipotential Surfaces](#7-equipotential-surfaces)
8. [Relation Between Electric Field and Potential](#8-relation-between-electric-field-and-potential)
9. [Potential Energy of a System of Charges](#9-potential-energy-of-a-system-of-charges)
10. [Potential Energy in an External Field](#10-potential-energy-in-an-external-field)
11. [Electrostatics of Conductors](#11-electrostatics-of-conductors)
12. [Dielectrics and Polarisation](#12-dielectrics-and-polarisation)
13. [Capacitor and Capacitance](#13-capacitor-and-capacitance)
14. [Parallel Plate Capacitor](#14-parallel-plate-capacitor)
15. [Effect of Dielectric on Capacitance](#15-effect-of-dielectric-on-capacitance)
16. [Combination of Capacitors](#16-combination-of-capacitors)
17. [Energy Stored in a Capacitor](#17-energy-stored-in-a-capacitor)
18. [Van de Graaff Generator](#18-van-de-graaff-generator)
19. [Important Formulas Summary](#19-important-formulas-summary)
20. [Board Exam Questions with Answers](#20-board-exam-questions-with-answers)
21. [Objective / MCQ Questions](#21-objective--mcq-questions)
22. [Quick Revision Tips](#22-quick-revision-tips)

---

## 1. What is This Chapter About?

In Chapter 1, you studied **electric forces and fields** — how charges push and pull each other.

Now in Chapter 2, we ask a deeper question:
- How much **energy** does it take to move a charge from one place to another?
- Why does current flow from one terminal of a battery to another?
- How do **capacitors** store energy in your phone, computer, and TV?

Real-world connections:
- Your phone battery stores energy using the concept of **electric potential**.
- Camera flash circuits use **capacitors** to release a burst of energy instantly.
- Lightning rods work on the principle of **sharp conductors** having high potential.

**What you will learn:**
- Electric potential and potential energy
- Equipotential surfaces
- Properties of conductors in electrostatics
- Dielectrics and their effect
- Capacitors — what they are, how they work, and how to combine them
- Energy stored in a capacitor
- Van de Graaff generator

---

## 2. Electric Potential Energy

### 2.1 What is Potential Energy?

Just like a stone held at a height has **gravitational potential energy**, a charge placed in an electric field has **electric potential energy**.

**Definition:** *"The electric potential energy of a charge at a point in an electric field is the work done by an external force in bringing the charge from infinity to that point, against the electric force, without acceleration."*

- Work done **against** the electric force → stored as potential energy.
- When the charge is released, this energy converts to kinetic energy.

### 2.2 Work Done by Electric Force

When a charge q₀ moves from point A to point B in an electric field:

```
Work done by electric force = W_AB = q₀(V_A − V_B)
```

Where V_A and V_B are potentials at A and B.

**Key Point:** Work done by the electric force depends only on the **initial and final positions**, NOT on the path taken.
→ This means the electric force is a **conservative force**.

---

## 3. Electric Potential

### 3.1 Definition ⭐⭐ (Most Important — Board Exam)

**Definition:** *"Electric potential at a point in an electric field is defined as the work done per unit positive charge in bringing a small test charge from infinity to that point, without acceleration."*

```
        W
V =  ———————
        q₀
```

Where:
- `V` = Electric potential (in Volt)
- `W` = Work done in bringing charge from infinity to the point
- `q₀` = Test charge (positive, infinitesimally small)

### 3.2 Unit and Dimension

- **SI Unit:** **Volt (V)** = Joule/Coulomb (J/C)
- **Dimension:** [M L² T⁻³ A⁻¹]
- 1 Volt = 1 J/C → If 1 Joule of work is done to bring 1 Coulomb of charge from infinity, the potential is 1 Volt.

### 3.3 Nature of Electric Potential

- Electric potential is a **scalar quantity** (it has no direction).
- It can be positive, negative, or zero.
- It is defined with respect to a reference point (usually infinity, where V = 0).
- **Potential difference** between two points A and B:

```
V_AB = V_A − V_B = W_AB / q₀
```

> 📝 **Board Exam Tip:** Potential is a **scalar**, while electric field is a **vector**. A very common 1-mark question.

---

## 4. Potential Due to a Point Charge

### 4.1 Derivation ⭐⭐ (Board Exam — 3 or 5 Mark)

**Setup:** Consider a point charge `+Q` at origin. Find the potential at point P at distance `r` from Q.

**Derivation:**

We bring a small test charge q₀ from infinity to point P. The work done against electric force is stored as potential energy.

Work done in moving q₀ from infinity to point P:

Consider the charge q₀ at distance `x` from Q. The electric force on it:
```
F = kQq₀/x²    (repulsive, pointing away from Q)
```

Small work done against this force for small displacement dx (toward Q):
```
dW = −F dx = −kQq₀/x² dx
```

Total work done bringing q₀ from ∞ to r:
```
W = ∫ dW = ∫(from ∞ to r) (−kQq₀/x²) dx

  = −kQq₀ [−1/x] from ∞ to r

  = −kQq₀ (−1/r + 0)

  = kQq₀/r
```

Electric potential:
```
V = W/q₀ = kQ/r
```

**Result:**
```
         1     Q        kQ
V =  ———————  ——   =   ————
       4πε₀   r          r
```

**Key Observations:**
- For **positive charge** (+Q): V > 0 (positive potential)
- For **negative charge** (−Q): V < 0 (negative potential)
- V ∝ 1/r (falls off as 1/r, unlike E which falls as 1/r²)
- At r = ∞: V = 0

---

## 5. Potential Due to a System of Charges

### 5.1 Superposition Principle for Potential ⭐

**Statement:** *"The potential at a point due to a system of charges is the algebraic sum of the potentials due to each individual charge."*

Since potential is a **scalar**, we simply add (algebraically, not vectorially):

```
V = V₁ + V₂ + V₃ + ... + Vₙ

     1     Q₁    Q₂    Q₃          Qₙ
V = ———— ( —— + —— + —— + ... + —— )
    4πε₀   r₁    r₂    r₃          rₙ
```

Where r₁, r₂, r₃ ... are distances of each charge from the point.

> 📝 **Important:** This is simpler than finding net E (which is vector addition). Potential addition is purely algebraic.

---

## 6. Potential Due to an Electric Dipole

### 6.1 At a General Point ⭐⭐ (Board Exam — Derivation)

**Setup:** A dipole has charges +q and −q separated by distance 2l. Point P is at distance r from the centre of the dipole, making angle θ with the dipole axis.

**Derivation:**

Let r₁ = distance from +q to P, r₂ = distance from −q to P.

Potential at P due to +q:
```
V₁ = kq/r₁
```

Potential at P due to −q:
```
V₂ = −kq/r₂
```

Total potential:
```
V = V₁ + V₂ = kq(1/r₁ − 1/r₂)
```

For a short dipole (r >> l), using geometry:
```
r₁ ≈ r − l cosθ
r₂ ≈ r + l cosθ
```

Substituting and simplifying:
```
          1      p cosθ
V =  ———————  ——————————
       4πε₀      r²
```

Where p = q × 2l is the dipole moment.

### 6.2 Special Cases

**At axial point (θ = 0°):**
```
        1      p
V =  ————————  ——
       4πε₀   r²
```
(Maximum positive potential for θ = 0°)

**At equatorial point (θ = 90°):**
```
V = 0
```
**The potential at equatorial point of a dipole is ZERO.**

> 📝 **Board Exam Note:** While E at equatorial point is NOT zero (it equals p/4πε₀r³), the **potential** at equatorial point IS zero. Don't confuse these!

---

## 7. Equipotential Surfaces

### 7.1 Definition ⭐⭐

**Definition:** *"An equipotential surface is a surface on which every point is at the same electric potential."*

**Key Property:** No work is done in moving a charge along an equipotential surface.

**Proof:** W = q₀(V_A − V_B). If both points are on the same equipotential, V_A = V_B, so W = 0.

### 7.2 Properties of Equipotential Surfaces ⭐⭐ (Board Exam Favourite — 3 Marks)

1. **No work done:** Work done to move a charge along an equipotential surface is **always zero**.
2. **Perpendicular to E:** The electric field is always **perpendicular** to the equipotential surface at every point.
3. **Never intersect:** Two equipotential surfaces can never intersect (just like field lines).
4. **Closer spacing → stronger field:** Equipotential surfaces are closer together where the electric field is stronger.
5. **Conductor surface is equipotential:** The entire surface of a charged conductor is an equipotential surface.
6. **Inside a conductor:** The entire interior of a conductor is at the same potential (equipotential volume).

### 7.3 Shape of Equipotential Surfaces

| Charge Configuration | Shape of Equipotential Surface |
|---|---|
| Isolated point charge | Concentric spheres around the charge |
| Uniform electric field | Planes perpendicular to E |
| Electric dipole | Distorted ovals around each charge |
| Two equal and same charges | Irregular closed curves around each |

```
POINT CHARGE:              UNIFORM FIELD:
   (concentric spheres)     (parallel planes ⊥ to E)

    ○ ○ ○                    |  |  |  |
   ○ ○+○ ○              E → |  |  |  |
    ○ ○ ○                    |  |  |  |
```

> 📝 **Why is E perpendicular to equipotential surface?** If E had a component along the surface, work would be done moving charge along it — but that contradicts the definition of equipotential. So E must be perpendicular.

---

## 8. Relation Between Electric Field and Potential

### 8.1 Formula ⭐⭐ (Very Important)

The electric field and potential are related by:

```
         dV
E = −  ————
         dr
```

**In words:** The electric field at any point is the **negative rate of change of potential** with distance (in the direction of field).

The negative sign means:
- E points in the direction of **decreasing potential**.
- Positive charges move from high potential to low potential.
- Negative charges move from low potential to high potential.

### 8.2 In Three Dimensions

```
       ∂V          ∂V          ∂V
Ex = − ——,    Ey = − ——,    Ez = − ——
       ∂x          ∂y          ∂z
```

### 8.3 Potential Gradient

The quantity dV/dr is called the **potential gradient**.

- **Unit:** V/m (same as E, which is N/C = V/m)
- **Relation:** E = −(potential gradient)

> 📝 **Board Exam Tip:** This explains why V/m and N/C are both units of electric field — they are equivalent.

---

## 9. Potential Energy of a System of Charges

### 9.1 Two-Charge System ⭐

**Potential energy of a system of two charges q₁ and q₂ separated by distance r:**

```
        1     q₁q₂
U =  ————————  ————
       4πε₀    r
```

**Physical meaning:** This is the work done to bring q₂ from infinity to distance r from q₁ (assuming q₁ is fixed).

- If q₁q₂ > 0 (like charges): U > 0 (you have to do work against repulsion)
- If q₁q₂ < 0 (unlike charges): U < 0 (the charges attract and release energy)

### 9.2 Three-Charge System

For three charges q₁, q₂, q₃ at distances r₁₂, r₂₃, r₁₃:

```
       1     q₁q₂    q₂q₃    q₁q₃
U =  ————— ( ———— + ———— + ———— )
      4πε₀   r₁₂     r₂₃     r₁₃
```

**Rule:** Add the potential energy for every **pair** of charges.

---

## 10. Potential Energy in an External Field

### 10.1 Potential Energy of a Charge in External Field

Work done to bring charge q from infinity to a point where potential is V:

```
U = qV
```

### 10.2 Potential Energy of a Dipole in External Field ⭐⭐

When a dipole of moment **p** is placed in a uniform electric field **E** at angle θ:

```
U = −pE cosθ = −p⃗ · E⃗
```

**Derivation:**

Work done in rotating dipole from θ₁ to θ₂:
```
W = pE(cosθ₁ − cosθ₂)
```

Taking reference position as θ₁ = 90° (where U = 0 by convention):
```
U = −pE cosθ
```

**Special Cases:**
- θ = 0°: U = −pE (minimum energy → **stable equilibrium**)
- θ = 90°: U = 0 (reference position)
- θ = 180°: U = +pE (maximum energy → **unstable equilibrium**)

> 📝 **Board Exam Note:** At stable equilibrium (θ = 0°), torque = 0 and U = −pE (minimum). At unstable equilibrium (θ = 180°), torque = 0 but U = +pE (maximum).

---

## 11. Electrostatics of Conductors

### 11.1 Key Properties of Conductors ⭐⭐⭐ (Most Important — Board Exam)

**Property 1: E = 0 inside a conductor**
- Inside a conductor in electrostatic equilibrium, E = 0.
- Reason: Free electrons redistribute until they cancel any internal field.

**Property 2: Net charge resides only on the surface**
- There is no net charge inside the conductor.
- All excess charge resides on the **outer surface**.

**Property 3: E is perpendicular to the surface**
- At the surface of a conductor, E is always **normal** (perpendicular) to the surface.
- If E had a tangential component, charges would flow → not equilibrium.

**Property 4: The surface is an equipotential surface**
- The entire surface of a conductor is at the same potential.

**Property 5: Interior has the same potential as surface**
- Since E = 0 inside, no work is done moving charges inside.
- So the entire interior is at the same potential as the surface.

**Property 6: Electric field just outside the surface**

```
        σ
E =  ————
       ε₀
```
Where σ is the surface charge density at that point.

**Property 7: Charge distribution depends on shape**
- On a non-spherical conductor, charge accumulates more at **sharp points** (high curvature → high σ → high E).
- This is why lightning rods have pointed tips.

### 11.2 Electrostatic Shielding ⭐

- The interior of a **hollow conductor** is completely shielded from external electric fields.
- E = 0 inside the hollow regardless of external field.
- **Application:** Sensitive instruments are enclosed in metal boxes (Faraday cage) to protect from external electric interference.

```
External Field ————→  [ METAL SHELL ]  ← E = 0 inside → [Instrument Safe]
```

---

## 12. Dielectrics and Polarisation

### 12.1 What is a Dielectric?

A **dielectric** is a non-conducting material (insulator) that can be polarised in an electric field.

**Examples:** Glass, mica, paper, wax, rubber, water.

Unlike conductors (where charges are free to move), in dielectrics all charges are tightly **bound** to their atoms.

### 12.2 Types of Dielectrics

**Polar Dielectrics:** Molecules that have a permanent dipole moment even without any external field.
- Example: Water (H₂O), HCl
- Molecules are asymmetric; positive and negative charge centres don't coincide.
- Normally randomly oriented → net dipole moment = 0.
- In external field: they align partially along the field.

**Non-Polar Dielectrics:** Molecules with NO permanent dipole moment.
- Example: O₂, N₂, CH₄
- In external field: electrons shift slightly → **induced dipole moment** is created.

### 12.3 Polarisation ⭐⭐

**Definition:** *"Polarisation is the development of a net dipole moment inside a dielectric in the presence of an external electric field."*

When an external field is applied:
- Bound charges are displaced slightly.
- The dielectric develops **surface charges** (bound charges) on its faces.
- This creates an internal field that **opposes** the external field.

**Polarisation vector P:**
```
P = χₑ × ε₀ × E
```
Where χₑ is the electric susceptibility of the dielectric.

**Net electric field inside dielectric:**
```
E_net = E₀ − E_induced = E₀/K
```
Where K is the dielectric constant (K > 1 always).

---

## 13. Capacitor and Capacitance

### 13.1 What is a Capacitor?

A **capacitor** is a device that stores electric charge (and electric energy).

It consists of two conductors (called **plates**) separated by an insulating material (dielectric) or vacuum.

**How it works:**
- Connect one plate to +ve terminal of battery → it gets +Q charge.
- Connect other plate to −ve terminal → it gets −Q charge.
- The electric field between the plates stores energy.

### 13.2 Capacitance ⭐⭐⭐

**Definition:** *"Capacitance of a capacitor is defined as the ratio of the charge stored on one plate to the potential difference between the two plates."*

```
      Q
C =  ———
      V
```

Where:
- `C` = Capacitance (in Farad)
- `Q` = Charge on one plate (in Coulomb)
- `V` = Potential difference between plates (in Volt)

### 13.3 Unit of Capacitance

- **SI Unit:** **Farad (F)** = Coulomb/Volt (C/V)
- 1 Farad is a VERY large unit. Practical units:
  - **microfarad (μF):** 1 μF = 10⁻⁶ F
  - **picofarad (pF):** 1 pF = 10⁻¹² F

> 📝 **Board Exam Note:** Capacitance depends on the **geometry** (size, shape, separation) of the capacitor and the **dielectric** between the plates — NOT on Q or V individually. If Q doubles, V also doubles, so C = Q/V stays constant.

---

## 14. Parallel Plate Capacitor

### 14.1 Description

A parallel plate capacitor consists of:
- Two large, flat, parallel metallic plates
- Each of area A
- Separated by distance d (small compared to plate dimensions)
- Vacuum (or air) between the plates

```
     +Q plate        −Q plate
     +  |                |  −
     +  |   E →→→→→     |  −
     +  |                |  −
     +  |←——— d ————→   |  −
```

### 14.2 Derivation of Capacitance ⭐⭐⭐ (5 Mark — Must Learn!)

**Step 1: Find the electric field between plates.**

Using Gauss's Law (from Chapter 1), E due to one plate:
```
E₁ = σ/2ε₀
```

For two plates with opposite charges, fields add between the plates:
```
E = E₁ + E₂ = σ/2ε₀ + σ/2ε₀ = σ/ε₀
```

Since surface charge density σ = Q/A:
```
E = Q/(ε₀A)
```

**Step 2: Find potential difference between plates.**

```
V = E × d = Qd/(ε₀A)
```

**Step 3: Calculate capacitance.**

```
       Q         Q           ε₀A
C =  ——— =  ——————————  =  ————
       V     Qd/(ε₀A)        d
```

**Result:**
```
       ε₀A
C =  ————————
        d
```

**Key observations:**
- C increases if **area A increases** (more plates → more charge storage)
- C decreases if **separation d increases** (plates farther apart → weaker attraction)
- C increases if **dielectric** is placed between plates (see Section 15)

---

## 15. Effect of Dielectric on Capacitance

### 15.1 Capacitance with Dielectric ⭐⭐

When a dielectric of **dielectric constant K** is completely filled between the plates:

```
        Kε₀A
C =  ————————
         d
```

Since K > 1 always, **capacitance increases** when dielectric is introduced.

The ratio:
```
C (with dielectric)      
———————————————————————  =  K
C (without dielectric)   
```

### 15.2 Why Does Capacitance Increase?

When a dielectric is placed between plates:
1. The dielectric gets polarised.
2. Bound charges appear on the surfaces of the dielectric.
3. These bound charges partially cancel the electric field inside (E decreases).
4. The potential difference V = Ed decreases (for the same Q).
5. Since C = Q/V, and V decreases, **C increases**.

### 15.3 Dielectric Constant K (εᵣ)

| Material | Dielectric Constant K |
|---|---|
| Vacuum / Air | 1 (by definition) |
| Paper | 3.7 |
| Mica | 5.4 |
| Glass | 5–10 |
| Water | 80 |
| Metal | ∞ (conductor) |

---

## 16. Combination of Capacitors

### 16.1 Capacitors in Series ⭐⭐⭐ (Board Exam — 3 to 5 Marks)

**Arrangement:** Capacitors connected end-to-end (in a chain).

```
     Q    C₁    C₂    C₃    Q
+|———||———||———||———|−
     V₁    V₂    V₃
     ←—————————V————————————→
```

**Properties of series combination:**
- **Charge** on each capacitor is the **same** (= Q)
- **Voltage** divides: V = V₁ + V₂ + V₃

**Formula for equivalent capacitance:**

Since V = Q/C:
```
V = V₁ + V₂ + V₃

Q/C_eq = Q/C₁ + Q/C₂ + Q/C₃

1/C_eq = 1/C₁ + 1/C₂ + 1/C₃
```

**For two capacitors in series:**
```
         C₁C₂
C_eq =  ————————
         C₁ + C₂
```

**Key fact:** Equivalent capacitance in series is **less than** the smallest individual capacitance.

### 16.2 Capacitors in Parallel ⭐⭐⭐ (Board Exam — 3 to 5 Marks)

**Arrangement:** All capacitors connected between the same two points.

```
     ———||——— C₁ ———
     |               |
+|——|———||——— C₂ ———|—|−
     |               |
     ———||——— C₃ ———
      ←——— V ———→
```

**Properties of parallel combination:**
- **Voltage** across each capacitor is the **same** (= V)
- **Charge** divides: Q = Q₁ + Q₂ + Q₃

**Formula for equivalent capacitance:**

```
Q = Q₁ + Q₂ + Q₃

C_eq × V = C₁V + C₂V + C₃V

C_eq = C₁ + C₂ + C₃
```

**Key fact:** Equivalent capacitance in parallel is **greater than** the largest individual capacitance.

### 16.3 Comparison: Series vs Parallel

| Property | Series | Parallel |
|---|---|---|
| Charge | Same (Q) | Different (Q₁, Q₂, Q₃) |
| Voltage | Different (V₁, V₂, V₃) | Same (V) |
| Formula | 1/C = 1/C₁ + 1/C₂ + 1/C₃ | C = C₁ + C₂ + C₃ |
| Net capacitance | Less than smallest C | Greater than largest C |
| Use | Voltage divider | Charge storage increase |

---

## 17. Energy Stored in a Capacitor

### 17.1 Derivation ⭐⭐⭐ (Board Exam — 3 or 5 Marks)

**Concept:** When a capacitor is charged, work is done to move charge from one plate to another. This work is stored as **electric potential energy** in the electric field between the plates.

**Derivation:**

Let the charge on the capacitor at some instant be q. The potential difference at that instant:
```
V = q/C
```

Small amount of work done in transferring an additional charge dq:
```
dW = V dq = (q/C) dq
```

Total work done to charge capacitor from 0 to Q:
```
W = ∫₀^Q (q/C) dq = (1/C) × Q²/2 = Q²/2C
```

This work is stored as energy:
```
        Q²      1          1
U =  ———————  =  ——CV²  =  ——QV
        2C      2          2
```

**Three equivalent forms:**
```
         Q²       1          1
U =  ——————— =  ——CV²  =  ——QV
         2C       2          2
```

### 17.2 Energy Density ⭐

The energy stored per unit volume in the electric field between the plates:

```
         1
u =  ————ε₀E²
         2
```

Where:
- `u` = energy density (J/m³)
- `E` = electric field between the plates

This result is very general — it applies to any electric field, not just capacitors.

---

## 18. Van de Graaff Generator

### 18.1 Principle ⭐⭐ (Board Exam — 3 Mark Theory)

A Van de Graaff generator is a device that produces very high voltages (millions of volts). It works on two principles:

**Principle 1:** Electric discharge occurs readily from **sharp points** (corona discharge).

**Principle 2:** If a charged conductor is placed inside another hollow conductor and connected to it, all charge transfers to the outer conductor regardless of how much charge is already on it.

### 18.2 Construction

```
                 [Large Spherical Shell]
                      ↑ ↑ ↑ ↑
      [Spray comb] → [Belt (insulating)] → [Collection comb]
           ↑                                       |
     [Motor/Pulley]                    [Inner surface of shell]
```

Main parts:
1. **Large hollow spherical shell** (S) mounted on insulating pillars.
2. **Long insulating belt** running between two pulleys.
3. **Lower spray comb (C₁):** Connected to +ve high voltage source → sprays +ve charge onto belt.
4. **Upper collection comb (C₂):** Picks up charge from belt and transfers to shell.

### 18.3 Working

1. Lower comb C₁ is given a high positive potential → due to corona discharge, it sprays positive charge on the belt.
2. The belt carries positive charge upward.
3. Upper comb C₂ is near the inner surface of the shell → due to induction, negative charge appears on C₂.
4. C₂ collects positive charge from belt and transfers it to the inner surface of shell.
5. The charge immediately moves to the **outer surface** of the shell (property of conductors).
6. This process keeps repeating → charge on shell keeps building up → potential rises to millions of volts.

### 18.4 Applications

- Used in **nuclear physics** to accelerate charged particles (protons, alpha particles) to high energies.
- Used in research to study nuclear reactions.
- Can create artificial lightning for study.

> 📝 **Board Exam Tip:** Draw the labeled diagram clearly. Explain the role of each comb. Learn the two principles clearly.

---

## 19. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| V = kQ/r | Potential due to point charge | Volt (V) |
| V = kp cosθ/r² | Potential due to dipole | V |
| V_equatorial = 0 | Potential at equatorial point | V |
| E = −dV/dr | E-V relation | N/C |
| U = kq₁q₂/r | Potential energy (two charges) | J |
| U = −pE cosθ | PE of dipole in external field | J |
| C = Q/V | Capacitance | Farad (F) |
| C = ε₀A/d | Parallel plate capacitor (vacuum) | F |
| C = Kε₀A/d | Parallel plate capacitor (dielectric) | F |
| 1/C = 1/C₁ + 1/C₂ + 1/C₃ | Capacitors in series | — |
| C = C₁ + C₂ + C₃ | Capacitors in parallel | — |
| U = Q²/2C = ½CV² = ½QV | Energy in capacitor | J |
| u = ½ε₀E² | Energy density | J/m³ |

---

## 20. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What is the SI unit of electric potential?**
**Ans:** Volt (V) = Joule/Coulomb (J/C)

**Q2. Define electric potential at a point.**
**Ans:** Electric potential at a point is the work done per unit positive charge in bringing a test charge from infinity to that point without acceleration. V = W/q₀

**Q3. What is the electric potential at the equatorial point of an electric dipole?**
**Ans:** Zero (V = 0), because the contributions from +q and −q cancel each other.

**Q4. Define capacitance of a capacitor.**
**Ans:** Capacitance is the ratio of charge stored on one plate to the potential difference between the plates. C = Q/V

**Q5. What is the SI unit of capacitance?**
**Ans:** Farad (F) = Coulomb/Volt (C/V)

**Q6. What is the energy density of an electric field E?**
**Ans:** u = ½ε₀E²

**Q7. What happens to the capacitance when a dielectric is introduced between the plates of a capacitor?**
**Ans:** Capacitance increases by a factor K (dielectric constant). C becomes KC.

**Q8. What is electrostatic shielding?**
**Ans:** The phenomenon by which the interior of a hollow conductor is completely shielded from external electric fields. E = 0 inside the hollow conductor.

**Q9. State the relation between electric field and electric potential.**
**Ans:** E = −dV/dr. Electric field is the negative gradient of electric potential.

**Q10. What is an equipotential surface?**
**Ans:** A surface on which every point is at the same electric potential. No work is done in moving a charge along an equipotential surface.

---

### 📝 2-Mark Questions

**Q11. Write any four properties of equipotential surfaces.**

**Ans:**
1. No work is done in moving a charge along an equipotential surface.
2. Electric field is always perpendicular to the equipotential surface.
3. Two equipotential surfaces never intersect each other.
4. Equipotential surfaces are closer together where the electric field is stronger.

---

**Q12. Derive the expression for equivalent capacitance when two capacitors C₁ and C₂ are connected in series.**

**Ans:**
In series, same charge Q on each capacitor:
```
V = V₁ + V₂ = Q/C₁ + Q/C₂
Q/C_eq = Q(1/C₁ + 1/C₂)
1/C_eq = 1/C₁ + 1/C₂
```
Equivalent capacitance = C₁C₂/(C₁+C₂)

---

**Q13. Write the expressions for the energy stored in a capacitor in three different forms.**

**Ans:**
```
        Q²      1          1
U =  ——————  =  ——CV²  =  ——QV
        2C      2          2
```
Where Q = charge, C = capacitance, V = potential difference.

---

**Q14. Why is the electric field inside a conductor zero?**

**Ans:**
Inside a conductor, free electrons redistribute themselves under the influence of any external field. They move and arrange themselves such that their own field exactly cancels the external field. This redistribution continues until E = 0 inside the conductor, which is the condition for electrostatic equilibrium.

---

### 📝 3-Mark Questions

**Q15. Derive the potential due to an electric dipole at an axial point.**

**Ans:**
At the axial point (on the axis of dipole), θ = 0°.

Using the general formula for dipole potential:
```
V = kp cosθ / r²
```

At θ = 0° (axial point):
```
V = kp / r² = p / 4πε₀r²
```

Full derivation: (Write derivation from Section 6 in your answer)

The potential at the axial point is: **V = p/4πε₀r²** (positive for +q end side)

---

**Q16. Explain the principle and working of a Van de Graaff generator with a diagram.**

**Ans:** *(See Section 18 — write principles, draw diagram, explain working)*

---

**Q17. Derive the capacitance of a parallel plate capacitor.**

**Ans:** *(See Section 14.2 — write full derivation)*

Final result: C = ε₀A/d

---

**Q18. Show that the energy stored per unit volume in an electric field E is u = ½ε₀E².**

**Ans:**

For a parallel plate capacitor with plate area A and separation d:
```
Energy stored: U = ½CV² = ½(ε₀A/d)(Ed)² = ½ε₀E² × Ad
```

Volume between plates = Ad

Energy per unit volume:
```
u = U/Volume = ½ε₀E² × Ad / Ad = ½ε₀E²
```

Hence: **u = ½ε₀E²** ✓

---

### 📝 5-Mark Questions (Long Answer)

**Q19. Derive the expression for electric potential at any point due to an electric dipole. What is the potential at the equatorial point?**

**Ans:** *(See Section 6 — write full derivation)*

General formula: V = kp cosθ / r²
At equatorial point (θ = 90°): V = 0

---

**Q20. Derive the expression for equivalent capacitance of capacitors connected:**
**(i) In series (ii) In parallel**

**Ans:** *(See Sections 16.1 and 16.2 — write both derivations fully)*

(i) Series: 1/C_eq = 1/C₁ + 1/C₂ + 1/C₃
(ii) Parallel: C_eq = C₁ + C₂ + C₃

---

**Q21. Derive an expression for the energy stored in a parallel plate capacitor. Also obtain the expression for energy density.**

**Ans:** *(See Sections 17.1 and 17.2)*

U = Q²/2C = ½CV² = ½QV
Energy density: u = ½ε₀E²

---

**Q22. State the properties of a conductor in electrostatics. Explain electrostatic shielding.**

**Ans:** *(See Section 11 — write all 7 properties + shielding with diagram)*

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** Find the potential at a distance of 0.2 m from a charge of +5μC.

**Solution:**
```
Given: Q = 5×10⁻⁶ C, r = 0.2 m, k = 9×10⁹ Nm²C⁻²

V = kQ/r
  = 9×10⁹ × 5×10⁻⁶ / 0.2
  = 45000 / 0.2
  = 2.25 × 10⁵ V
```
**Answer: V = 2.25 × 10⁵ V = 225 kV**

---

**Num 2:** A parallel plate capacitor has plate area 10⁻² m² and separation 1 mm. Find its capacitance.

**Solution:**
```
Given: A = 10⁻² m², d = 1×10⁻³ m, ε₀ = 8.85×10⁻¹² C²N⁻¹m⁻²

C = ε₀A/d
  = 8.85×10⁻¹² × 10⁻² / 10⁻³
  = 8.85×10⁻¹¹ F
  = 88.5 pF
```
**Answer: C = 88.5 pF**

---

**Num 3:** Two capacitors 4μF and 6μF are connected (a) in series and (b) in parallel across a 100V battery. Find the equivalent capacitance in each case.

**Solution:**

**(a) Series:**
```
1/C = 1/4 + 1/6 = 3/12 + 2/12 = 5/12
C = 12/5 = 2.4 μF
```

**(b) Parallel:**
```
C = 4 + 6 = 10 μF
```

**Answer: (a) 2.4 μF, (b) 10 μF**

---

**Num 4:** A capacitor of capacitance 10μF is charged to 200V. Find the energy stored in it.

**Solution:**
```
Given: C = 10×10⁻⁶ F, V = 200 V

U = ½CV²
  = ½ × 10×10⁻⁶ × (200)²
  = ½ × 10×10⁻⁶ × 40000
  = 0.2 J
```
**Answer: U = 0.2 J**

---

**Num 5:** Find the work done in moving a charge of 4C from a point at potential 100V to a point at potential 25V.

**Solution:**
```
Given: q = 4 C, V_A = 100 V, V_B = 25 V

W = q(V_A − V_B)
  = 4 × (100 − 25)
  = 4 × 75
  = 300 J
```
**Answer: W = 300 J**

---

**Num 6:** A parallel plate capacitor with air between the plates has capacitance 8 pF. What will be the capacitance if the separation is reduced to half and wax of K = 6 is introduced?

**Solution:**
```
Initial: C₀ = ε₀A/d = 8 pF

Final: d' = d/2, K = 6
C' = Kε₀A/d' = 6 × ε₀A/(d/2) = 12 × ε₀A/d = 12C₀

C' = 12 × 8 = 96 pF
```
**Answer: C' = 96 pF**

---

**Num 7:** Two charges 2μC and −4μC are placed at corners A and B of an equilateral triangle of side 20 cm. Find the potential at corner C.

**Solution:**
```
Given: q₁ = 2×10⁻⁶ C at A, q₂ = −4×10⁻⁶ C at B
Distance from each charge to C = r = 0.2 m

V_C = kq₁/r + kq₂/r = k(q₁ + q₂)/r
    = 9×10⁹ × (2×10⁻⁶ − 4×10⁻⁶) / 0.2
    = 9×10⁹ × (−2×10⁻⁶) / 0.2
    = −9×10⁴ V
```
**Answer: V_C = −9 × 10⁴ V = −90 kV**

---

## 21. Objective / MCQ Questions

**Q1.** Electric potential is:
- (a) A vector quantity
- **(b) A scalar quantity** ✓
- (c) Neither scalar nor vector
- (d) A tensor quantity

---

**Q2.** The unit of electric potential is:
- (a) N/C
- (b) N·m
- **(c) J/C** ✓
- (d) C/J

---

**Q3.** The potential at the equatorial point of an electric dipole is:
- (a) p/4πε₀r²
- (b) 2p/4πε₀r²
- **(c) Zero** ✓
- (d) −p/4πε₀r²

---

**Q4.** The work done in moving a charge along an equipotential surface is:
- **(a) Zero** ✓
- (b) Maximum
- (c) Negative
- (d) Depends on path

---

**Q5.** The electric field inside a conductor in electrostatic equilibrium is:
- **(a) Zero** ✓
- (b) Maximum
- (c) σ/ε₀
- (d) σ/2ε₀

---

**Q6.** Equipotential surfaces around a point charge are:
- (a) Parallel planes
- **(b) Concentric spheres** ✓
- (c) Cylinders
- (d) Ellipsoids

---

**Q7.** For capacitors in series, which quantity is the same?
- (a) Voltage
- (b) Energy
- **(c) Charge** ✓
- (d) Capacitance

---

**Q8.** For capacitors in parallel, which quantity is the same?
- (a) Charge
- **(b) Voltage** ✓
- (c) Energy
- (d) None

---

**Q9.** The capacitance of a parallel plate capacitor INCREASES when:
- (a) Plate area decreases
- (b) Plate separation increases
- **(c) Dielectric is introduced** ✓
- (d) Voltage is increased

---

**Q10.** The energy stored in a capacitor of capacitance C at voltage V is:
- (a) CV
- (b) CV²
- **(c) ½CV²** ✓
- (d) 2CV²

---

**Q11.** If distance between plates of a parallel plate capacitor is halved, the capacitance:
- (a) Becomes half
- **(b) Becomes double** ✓
- (c) Remains same
- (d) Becomes four times

---

**Q12.** The potential energy of an electric dipole in a uniform electric field is minimum when:
- **(a) θ = 0°** ✓
- (b) θ = 90°
- (c) θ = 180°
- (d) θ = 45°

---

**Q13.** Which of the following has the highest dielectric constant?
- (a) Air
- (b) Glass
- (c) Mica
- **(d) Water** ✓

---

**Q14.** The relation between E and V is:
- (a) E = dV/dr
- **(b) E = −dV/dr** ✓
- (c) E = V/r
- (d) E = V × r

---

**Q15.** A capacitor of 4μF is charged to 50V. The charge on the capacitor is:
- (a) 12.5 μC
- **(b) 200 μC** ✓
- (c) 0.08 μC
- (d) 54 μC

> *Solution: Q = CV = 4×10⁻⁶ × 50 = 200 μC*

---

**Q16.** The Van de Graaff generator works on the principle of:
- (a) Electromagnetic induction
- **(b) Electrostatic induction and charge transfer to outer shell** ✓
- (c) Mutual inductance
- (d) Thermoelectric effect

---

**Q17.** The energy density in a medium with electric field E and permittivity ε₀ is:
- (a) ε₀E
- (b) ε₀E²
- **(c) ½ε₀E²** ✓
- (d) 2ε₀E²

---

**Q18.** Two capacitors C₁ = 3μF and C₂ = 6μF are connected in series. The equivalent capacitance is:
- **(a) 2 μF** ✓
- (b) 9 μF
- (c) 18 μF
- (d) 0.5 μF

> *Solution: 1/C = 1/3 + 1/6 = 1/2 → C = 2μF*

---

## 22. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Parallel Plate Capacitor (derivation) | 5 marks |
| ⭐⭐⭐ | Energy Stored in Capacitor | 3–5 marks |
| ⭐⭐⭐ | Combination of Capacitors (S & P) | 3–5 marks |
| ⭐⭐⭐ | Properties of Conductors | 3 marks |
| ⭐⭐ | Equipotential Surfaces (properties) | 3 marks |
| ⭐⭐ | Potential Due to Dipole | 3–5 marks |
| ⭐⭐ | Van de Graaff Generator | 3 marks |
| ⭐⭐ | Dielectrics and Polarisation | 2–3 marks |
| ⭐ | Numericals | 2–3 marks |
| ⭐ | MCQs (Objective) | 1 mark each |

---

### 📌 Things to Memorize (Flash Cards)

```
Electric Potential:    V = kQ/r
Dipole Potential:      V = kp cosθ / r²
Equatorial Potential:  V = 0
E-V Relation:          E = −dV/dr
PE of Dipole:          U = −pE cosθ
Capacitance:           C = Q/V
Parallel Plate Cap:    C = ε₀A/d  (vacuum)
With Dielectric:       C = Kε₀A/d
Series:                1/C = 1/C₁ + 1/C₂ + 1/C₃
Parallel:              C = C₁ + C₂ + C₃
Energy in Capacitor:   U = Q²/2C = ½CV² = ½QV
Energy Density:        u = ½ε₀E²
```

---

### 🔑 Key Differences to Remember

| | Potential (V) | Electric Field (E) |
|---|---|---|
| Type | Scalar | Vector |
| Unit | Volt (V) | N/C or V/m |
| Due to point charge | kQ/r | kQ/r² |
| At equatorial (dipole) | **Zero** | **p/4πε₀r³** (non-zero) |

| Series | Parallel |
|---|---|
| Charge same | Voltage same |
| 1/C = Σ(1/Cᵢ) | C = ΣCᵢ |
| C decreases | C increases |

| Stable Equilibrium | Unstable Equilibrium |
|---|---|
| θ = 0° | θ = 180° |
| U = −pE (minimum) | U = +pE (maximum) |
| τ = 0 | τ = 0 |

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn definition and formula for Electric Potential
- [ ] Learn 4 Properties of Equipotential Surfaces
- [ ] Learn the derivation: Potential due to a point charge
- [ ] Learn the derivation: Potential due to a dipole (especially equatorial = 0)
- [ ] Learn E = −dV/dr and its meaning
- [ ] Learn 5 Properties of Conductors in Electrostatics
- [ ] Learn the derivation: Parallel Plate Capacitor (C = ε₀A/d)
- [ ] Learn effect of dielectric (C becomes KC)
- [ ] Practice series and parallel capacitor problems
- [ ] Learn Energy in Capacitor derivation and u = ½ε₀E²
- [ ] Learn Van de Graaff Generator (diagram + working)
- [ ] Solve 5 numerical problems
- [ ] Revise all MCQs in Section 21

---

### 💡 Common Mistakes to Avoid

1. **Potential vs Field at equatorial point of dipole:**
   - Potential V = **0** (zero)
   - Electric field E = p/4πε₀r³ (**not zero**)
   - This is the most common mistake in board exams!

2. **Potential is scalar — DON'T use vector addition.** Simply add algebraically (with signs).

3. **Capacitors in series:** Charge is same, voltage is different. Don't confuse with parallel.

4. **Energy formula:** U = ½CV² (NOT CV²). Always remember the factor of ½.

5. **Dielectric constant K ≥ 1 always.** Capacitance always increases (or stays same for vacuum/air).

6. **Direction of E:** E points from HIGH potential to LOW potential (negative gradient).

7. **Inside a conductor:** Both E = 0 AND V = constant (same as surface). Students often know E = 0 but forget V = constant.

8. **Van de Graaff:** Charge accumulates on the OUTER surface, not inner. Charge sprayed on belt goes to inner comb and then to outer shell.

---


---
*Prepared for Bihar Board Class 12 Physics | Chapter 2: Electrostatic Potential and Capacitance | Based on NCERT Textbook*