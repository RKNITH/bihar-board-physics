# 📘 Class 12 Physics — Chapter 1: Electric Charges and Fields
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
> 
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Electric Charge](#2-electric-charge)
3. [Properties of Electric Charge](#3-properties-of-electric-charge)
4. [Methods of Charging](#4-methods-of-charging)
5. [Coulomb's Law](#5-coulombs-law)
6. [Superposition Principle](#6-superposition-principle)
7. [Electric Field](#7-electric-field)
8. [Electric Field Lines](#8-electric-field-lines)
9. [Electric Dipole](#9-electric-dipole)
10. [Electric Field Due to a Dipole](#10-electric-field-due-to-a-dipole)
11. [Torque on a Dipole in Uniform Electric Field](#11-torque-on-a-dipole-in-uniform-electric-field)
12. [Electric Flux](#12-electric-flux)
13. [Gauss's Law](#13-gausss-law)
14. [Applications of Gauss's Law](#14-applications-of-gausss-law)
15. [Important Formulas Summary](#15-important-formulas-summary)
16. [Board Exam Questions with Answers](#16-board-exam-questions-with-answers)
17. [Objective / MCQ Questions](#17-objective--mcq-questions)
18. [Quick Revision Tips](#18-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is the **starting point of Electrostatics** — the study of charges at rest.

Think of it this way:
- You rub a comb on your hair → it attracts small bits of paper. **Why?** → Because of **electric charge**.
- Lightning strikes during storms. **Why?** → Because of **charge accumulation** in clouds.
- Your phone screen reacts to your finger touch. **Why?** → Electric forces between charges.

This chapter answers all these questions scientifically.

**What you will learn:**
- What is charge and its properties
- Force between charges (Coulomb's Law)
- Electric Field and Field Lines
- Electric Dipole
- Electric Flux and Gauss's Law

---

## 2. Electric Charge

### 2.1 What is Charge?

Electric charge is a **fundamental property** of matter that causes it to experience a force when placed in an electric field.

- There are **two types** of charges:
  - **Positive Charge (+)** → Protons carry positive charge
  - **Negative Charge (−)** → Electrons carry negative charge

- **Like charges repel** each other. (+ repels +, − repels −)
- **Unlike charges attract** each other. (+ attracts −)

### 2.2 Unit of Charge

- SI Unit = **Coulomb (C)**
- Charge of 1 electron = **−1.6 × 10⁻¹⁹ C**
- Charge of 1 proton = **+1.6 × 10⁻¹⁹ C**
- This value `e = 1.6 × 10⁻¹⁹ C` is called the **elementary charge**

> 💡 **Memory Tip:** 1 Coulomb = charge of about **6.25 × 10¹⁸ electrons**

### 2.3 Conductors and Insulators

| Conductors | Insulators |
|---|---|
| Allow charge to flow freely | Do not allow charge to flow |
| Example: Copper, Silver, Iron | Example: Glass, Rubber, Plastic |
| Have free electrons | Electrons are tightly bound |

---

## 3. Properties of Electric Charge

### 3.1 Additivity of Charge

Charge is a **scalar quantity**. Total charge of a system = algebraic sum of all charges.

**Example:**
If a system has charges +3C, −2C, +1C:
```
Total charge = +3 + (−2) + (+1) = +2 C
```

### 3.2 Conservation of Charge ⭐ (Very Important for Board)

**Statement:** *"Electric charge can neither be created nor destroyed. It can only be transferred from one body to another."*

**Total charge of an isolated system always remains constant.**

**Examples:**
- When glass rod is rubbed with silk: glass becomes +ve and silk becomes −ve. Net charge = 0 (same as before rubbing).
- In nuclear reactions: charge is always conserved.
- Pair production: γ → e⁺ + e⁻ (total charge = 0 before and after)

> 📝 **Board Exam Note:** This is a 2-mark theory question. Learn the statement + one example.

### 3.3 Quantization of Charge ⭐ (Very Important)

**Statement:** *"Electric charge always exists as an integral multiple of the elementary charge e."*

```
q = ne
```
Where:
- `q` = total charge
- `n` = any integer (n = ±1, ±2, ±3, ...)
- `e` = 1.6 × 10⁻¹⁹ C (charge of one electron)

**Meaning:** You cannot have half a charge of an electron. Charge comes in **packets** of `e`.

**Examples:**
- 1 electron: q = −1e = −1.6 × 10⁻¹⁹ C
- 3 electrons: q = −3e = −4.8 × 10⁻¹⁹ C
- 2 protons: q = +2e = +3.2 × 10⁻¹⁹ C

> 📝 **Why do we ignore quantization at large scale?**
> When charges are in coulombs (very large), the number of electrons is ~10¹⁸. Adding or removing one electron makes no practical difference. So we treat charge as **continuous** at large scale.

---

## 4. Methods of Charging

### 4.1 Charging by Friction (Rubbing)
- When two objects are rubbed together, electrons transfer from one to another.
- **Example:** Glass rod + Silk cloth → Glass becomes +ve (loses electrons), Silk becomes −ve (gains electrons)

### 4.2 Charging by Conduction (Contact)
- A charged body is brought in **direct contact** with a neutral body.
- Charge transfers until both reach same potential.
- Both bodies end up with the **same sign** of charge.

### 4.3 Charging by Induction ⭐ (Board Exam Favourite)
- Charged body is brought **near** (NOT touching) a neutral conductor.
- Free electrons in the neutral conductor redistribute.
- **Near side** gets opposite charge, **far side** gets same charge as inducing body.
- If the far side is grounded → opposite charge remains permanently.

**Steps of Induction:**
1. Bring +ve charged rod near a neutral metal ball.
2. Electrons in the ball are attracted toward the rod side (left side becomes −ve, right becomes +ve).
3. Ground the right side → +ve charge flows to earth.
4. Remove the ground connection.
5. Remove the rod.
6. Ball is left with net −ve charge.

> 📝 **Key difference:** In conduction, both bodies get SAME sign charge. In induction, the body gets OPPOSITE sign charge.

---

## 5. Coulomb's Law

### 5.1 Statement ⭐⭐ (Most Important — 3 or 5 Mark Question)

**Statement:** *"The force of attraction or repulsion between two stationary point charges is directly proportional to the product of the magnitudes of the charges and inversely proportional to the square of the distance between them. This force acts along the line joining the two charges."*

### 5.2 Mathematical Form

```
        1     q₁ × q₂
F =  ———————  ————————
       4πε₀      r²
```

Where:
- `F` = Electrostatic force (in Newton, N)
- `q₁`, `q₂` = magnitudes of the two charges (in Coulomb, C)
- `r` = distance between the two charges (in meter, m)
- `ε₀` = Permittivity of free space = **8.85 × 10⁻¹² C² N⁻¹ m⁻²**
- `1/4πε₀` = k = **9 × 10⁹ N m² C⁻²**

**Simple form:**
```
F = k × q₁q₂ / r²        where k = 9 × 10⁹ N m² C⁻²
```

### 5.3 Vector Form of Coulomb's Law

Force on charge q₂ due to q₁:
```
→         1    q₁q₂  ^
F₁₂ =  ————————  ——— r₁₂
         4πε₀   r²
```
Where `r̂₁₂` is the unit vector pointing from q₁ to q₂.

### 5.4 In a Medium (Dielectric)

When charges are placed in a medium with dielectric constant K (relative permittivity εᵣ):
```
         1     q₁ × q₂
F =  —————————  ————————
       4πε₀K      r²
```
Where `K` = εᵣ = dielectric constant of the medium.

- For air/vacuum: K = 1
- For water: K ≈ 80 (force becomes 80 times weaker)

### 5.5 Relationship between ε₀, εᵣ, and ε
```
ε = ε₀ × εᵣ
```

### 5.6 Properties / Characteristics of Coulomb's Force
1. It is a **central force** (acts along the line joining two charges).
2. It follows **inverse square law**.
3. It can be **attractive or repulsive**.
4. It is a **conservative force**.
5. It **does not depend** on the medium between charges... wait, it DOES depend on the medium. (Force is reduced in a medium compared to vacuum)
6. It **obeys Newton's Third Law**: F₁₂ = −F₂₁ (equal and opposite).
7. It is much **stronger than gravitational force** (about 10³⁶ times stronger).

### 5.7 Similarities and Differences: Coulomb's Force vs Gravitational Force

| Property | Coulomb's Force | Gravitational Force |
|---|---|---|
| Depends on | Charge | Mass |
| Nature | Attractive or Repulsive | Always Attractive |
| Medium effect | Yes (depends on K) | No medium effect |
| Range | Long range | Long range |
| Obeys inverse sq. law | Yes | Yes |
| Conservative force | Yes | Yes |

---

## 6. Superposition Principle

### 6.1 Statement ⭐ (Board Exam Important)

**Statement:** *"The total force on any charge due to a number of other charges is the vector sum of the forces that each of those charges would exert on it individually."*

### 6.2 Mathematical Form

If charge q is at position, and charges q₁, q₂, q₃ ... qₙ exert forces F₁, F₂, F₃ ... Fₙ on it:

```
→    →    →    →         →
F = F₁ + F₂ + F₃ + ... + Fₙ
```

**Key Point:** The presence of other charges does **NOT** affect the force between any two charges. Each force is calculated independently and then added vectorially.

### 6.3 Solved Example

**Q:** Three charges q₁ = +4μC, q₂ = −2μC, q₃ = +3μC are placed in a straight line at distances 0.1m, 0.2m. Find force on q₂.

**Step 1:** Calculate F₂₁ (force on q₂ due to q₁)
```
F₂₁ = k|q₁||q₂|/r₁² = 9×10⁹ × 4×10⁻⁶ × 2×10⁻⁶ / (0.1)²
     = 9×10⁹ × 8×10⁻¹² / 0.01 = 7.2 N (attractive, toward q₁)
```

**Step 2:** Calculate F₂₃ (force on q₂ due to q₃)  
Similarly calculate, then find vector sum.

---

## 7. Electric Field

### 7.1 What is Electric Field?

**Definition:** *"The electric field at a point in space is defined as the force experienced by a unit positive test charge placed at that point."*

```
→    →
E =  F / q₀
```

- `E` = Electric field (N/C or V/m)
- `F` = Force on test charge
- `q₀` = Test charge (very small, so it doesn't disturb the field)

### 7.2 Electric Field Due to a Point Charge ⭐ (Derivation — Board Exam)

**Proof/Derivation:**

Consider a charge `+Q` at origin. We want to find E at point P at distance `r`.

Place a small test charge `q₀` at P.

By Coulomb's law, force on q₀:
```
F = (1/4πε₀) × Q×q₀ / r²
```

Electric field E = F/q₀:
```
E = (1/4πε₀) × Q / r²
```

**In vector form:**
```
→        1      Q   ^
E =  ————————  ——— r
       4πε₀    r²
```
Where `r̂` is the unit vector pointing away from Q (for positive charge).

**Important conclusions:**
- For **positive charge**: E points **away** from the charge.
- For **negative charge**: E points **toward** the charge.
- E is inversely proportional to r² (as distance increases, E decreases).

### 7.3 Unit and Dimensions of Electric Field

- **SI Unit:** N/C (Newton per Coulomb) = V/m (Volt per meter)
- **Dimension:** [M L T⁻³ A⁻¹]

---

## 8. Electric Field Lines

### 8.1 Definition

Electric field lines are **imaginary lines** drawn in an electric field such that the **tangent at any point** on the line gives the direction of the electric field at that point.

### 8.2 Properties of Electric Field Lines ⭐⭐ (Most Asked — 3 Mark Question)

1. **Direction:** Field lines start from positive charge and end at negative charge.
2. **Tangent property:** Tangent at any point gives direction of E at that point.
3. **Never cross each other:** Because at any point, E can have only ONE direction.
4. **Density represents magnitude:** More lines per unit area → Stronger field. Fewer lines → Weaker field.
5. **Normal to conductor surface:** Field lines are always perpendicular to the surface of a conductor.
6. **No closed loops:** Electrostatic field lines never form closed loops. (Magnetic field lines DO form closed loops — this is the difference.)
7. **Start and end perpendicular:** They emerge/enter perpendicular to the surface of charged conductors.

### 8.3 Diagrams of Field Lines

```
POSITIVE CHARGE:          NEGATIVE CHARGE:
                               
    ← ←                        → →
  ←   ←                      →   →
← ← + → →              → → - ← ←
  ←   ←                      →   →
    ← ←                        → →
(arrows point AWAY)       (arrows point TOWARD)


TWO EQUAL AND OPPOSITE CHARGES (+Q and -Q):
        +Q ————————————→ -Q
Lines go from + to -

TWO EQUAL AND SAME CHARGES (+Q and +Q):
        +Q ←    → +Q
Lines repel each other, neutral point in middle
```

### 8.4 Uniform Electric Field

A uniform electric field has **equally spaced parallel lines**, all pointing in the same direction. The field between two large parallel plates (one +ve, one −ve) is uniform.

---

## 9. Electric Dipole

### 9.1 Definition ⭐ (Very Important)

**Definition:** *"An electric dipole is a system of two equal and opposite charges (+q and −q) separated by a small distance 2l."*

```
   -q ←——— 2l ———→ +q
       [DIPOLE]
```

### 9.2 Electric Dipole Moment ⭐ (Board Exam — 2 Mark)

**Definition:** *"The electric dipole moment is defined as the product of either charge and the distance between them."*

```
p = q × 2l
```

Where:
- `p` = dipole moment
- `q` = magnitude of either charge
- `2l` = distance between two charges

**Direction:** From negative charge (−q) to positive charge (+q)

**SI Unit:** C·m (Coulomb·meter)

**Vector form:**
```
→      →
p = q(2l)  (direction from −q to +q)
```

> 📝 **Board Exam Tip:** Always remember: dipole moment direction = from −q to +q (negative to positive). Students often get confused.

---

## 10. Electric Field Due to a Dipole

### 10.1 Electric Field at Axial Point (End-on Position) ⭐⭐

**Setup:** The point P is on the **axis** of the dipole (the line passing through both charges) at distance `r` from the centre of the dipole.

**Derivation:**

Let the dipole have charges +q and −q, separated by distance 2l. Centre is at O. Point P is at distance r from O on the axis.

- Distance from +q to P = (r − l)
- Distance from −q to P = (r + l)

Electric field at P due to +q (pointing away from +q, i.e., toward P):
```
E₊ = kq / (r−l)²       [in the direction of p]
```

Electric field at P due to −q (pointing toward −q, i.e., away from P):
```
E₋ = kq / (r+l)²       [opposite to direction of p]
```

Net field at P (since E₊ > E₋):
```
E = E₊ − E₋
  = kq/(r−l)² − kq/(r+l)²
  = kq [(r+l)² − (r−l)²] / [(r−l)(r+l)]²
  = kq [4rl] / (r²−l²)²
  = 4kqrl / (r²−l²)²
```

Since p = q × 2l, so qrl = p×r/2:
```
      1       2pr
E = ———————  ————————
     4πε₀   (r²−l²)²
```

**For short dipole (l << r), r² >> l²:**
```
      1       2p
E = ———————  ————        [direction along p]
     4πε₀    r³
```

### 10.2 Electric Field at Equatorial Point (Broad-side On Position) ⭐⭐

**Setup:** Point P is on the **perpendicular bisector** of the dipole axis (equatorial line) at distance `r` from centre.

**Derivation:**

Distance from each charge to P:
```
d = √(r² + l²)
```

Field at P due to +q: E₊ = kq/(r²+l²) [pointing from +q toward P]
Field at P due to −q: E₋ = kq/(r²+l²) [pointing from P toward −q]

The vertical components (perpendicular to axis) cancel out.
The horizontal components (along axis) add up.

```
E = E₊cosθ + E₋cosθ = 2E₊cosθ
```

Where cosθ = l/√(r²+l²)

```
E = 2 × kq/(r²+l²) × l/√(r²+l²)
  = 2kql / (r²+l²)^(3/2)
  = kp / (r²+l²)^(3/2)        [since p = 2ql]
```

**For short dipole (l << r):**
```
      1       p
E = ———————  ————        [direction OPPOSITE to p]
     4πε₀    r³
```

### 10.3 Comparison: Axial vs Equatorial Field

| Property | Axial Point | Equatorial Point |
|---|---|---|
| Formula (short dipole) | E = 2p/4πε₀r³ | E = p/4πε₀r³ |
| Direction | Along p (same as dipole) | Opposite to p |
| Ratio | Eaxial = 2 × Eequatorial | — |

> 📝 **Key Fact:** Axial field is **twice** the equatorial field at the same distance.

---

## 11. Torque on a Dipole in Uniform Electric Field

### 11.1 Derivation ⭐⭐ (5 Mark Question — Must Learn!)

**Setup:**
- Electric dipole with dipole moment `p` is placed in a uniform electric field `E`.
- The dipole makes an angle `θ` with the direction of field.

**Forces on the dipole:**
- Force on +q charge: F = qE (in the direction of E)
- Force on −q charge: F = qE (opposite to the direction of E)

These two forces are **equal and opposite** → they form a **couple**.
The net translational force = 0 (dipole does not move in uniform field).
But there is a **net torque** that tends to rotate the dipole.

**Calculation of Torque:**

Torque = Force × Perpendicular distance between the forces
```
τ = F × BC
  = qE × 2l sinθ       [since BC = 2l sinθ]
  = (q × 2l) × E × sinθ
  = pE sinθ
```

**In vector form:**
```
→    →   →
τ =  p × E
```

**Magnitude:**
```
τ = pE sinθ
```

Where:
- `τ` = Torque (N·m)
- `p` = Dipole moment (C·m)
- `E` = Electric field (N/C)
- `θ` = Angle between p and E

**Special Cases:**
- θ = 0°: τ = 0 (dipole is along E — **stable equilibrium**)
- θ = 90°: τ = pE (maximum torque)
- θ = 180°: τ = 0 (dipole is opposite to E — **unstable equilibrium**)

> 📝 **Board Exam Note:** This derivation comes for 3-5 marks. Draw the diagram clearly. Show forces on each charge, the angle, and the perpendicular distance.

### 11.2 Work Done in Rotating a Dipole

Work done in rotating the dipole from angle θ₁ to θ₂:
```
W = pE(cosθ₁ − cosθ₂)
```

**Potential Energy of Dipole:**
```
U = −pE cosθ = −p·E (vector form)
```

---

## 12. Electric Flux

### 12.1 Definition ⭐

**Definition:** *"Electric flux through a surface is defined as the total number of electric field lines passing through that surface normally."*

**Mathematically:**
```
φ = E × A × cosθ
```

Where:
- `φ` (phi) = Electric flux
- `E` = Magnitude of electric field
- `A` = Area of the surface
- `θ` = Angle between E and the normal to the surface (area vector)

**In vector form:**
```
→  →
φ = E · A = EA cosθ
```

### 12.2 Unit and Dimension

- **SI Unit:** N·m²/C or V·m
- **Dimension:** [M L³ T⁻³ A⁻¹]

### 12.3 Special Cases

- θ = 0° (E perpendicular to surface): φ = EA (Maximum flux)
- θ = 90° (E parallel to surface): φ = 0 (No flux)
- θ = 180°: φ = −EA (flux is negative, outward defined as positive)

### 12.4 Flux through a Closed Surface

For a closed surface:
```
φ = ∮ E · dA
```

The circle on the integral sign means integration over a **closed surface**.

---

## 13. Gauss's Law

### 13.1 Statement ⭐⭐⭐ (Most Important — Board Exam Must!)

**Statement:** *"The total electric flux through any closed surface is equal to 1/ε₀ times the total charge enclosed within that surface."*

```
        Q_enclosed
φ = ————————————————
           ε₀
```

**In integral form:**
```
∮ E · dA = Q_enclosed / ε₀
```

Where:
- `φ` = Total electric flux through the closed surface (Gaussian surface)
- `Q_enclosed` = Total charge inside the closed surface
- `ε₀` = Permittivity of free space

### 13.2 Proof of Gauss's Law (from Coulomb's Law) ⭐⭐

**Proof for a point charge:**

Consider a point charge `+Q` at the centre of a sphere of radius `r`.

By symmetry, electric field E is directed radially outward and has the same magnitude at every point on the sphere.

Total flux through the sphere:
```
φ = E × 4πr²          [since area of sphere = 4πr²]
```

From Coulomb's law, E at the surface:
```
E = (1/4πε₀) × Q/r²
```

Substituting:
```
φ = (1/4πε₀) × Q/r² × 4πr²
φ = Q/ε₀
```

**This proves Gauss's Law: φ = Q/ε₀** ✓

### 13.3 Important Points about Gauss's Law

1. Gauss's Law is valid for **any closed surface** (called Gaussian surface).
2. Gaussian surface is a **mathematical surface** — not a physical surface.
3. The flux depends only on the **charge enclosed**, NOT on the shape of the surface.
4. Charges **outside** the Gaussian surface contribute **zero net flux**.
5. Gauss's Law is equivalent to Coulomb's law (both give same results).

> 📝 **Board Exam Tip:** Learn the statement word by word. Then learn the mathematical formula. 3-mark question often just asks statement + formula.

---

## 14. Applications of Gauss's Law

### 14.1 Electric Field Due to Infinitely Long Straight Charged Wire ⭐⭐

**Setup:** An infinitely long wire has linear charge density `λ` (charge per unit length). Find E at distance `r`.

**Derivation:**

Choose Gaussian surface as a **cylinder** of radius `r` and length `l` coaxial with the wire.

The cylinder has 3 surfaces:
- **Curved surface** (side): E is parallel to area vector. Flux = E × 2πrl
- **Two flat ends** (top and bottom): E is perpendicular to area vector. Flux = 0 (E and area vector are perpendicular)

Total flux:
```
φ = E × 2πrl
```

Charge enclosed in the cylinder:
```
Q = λl
```

By Gauss's Law:
```
φ = Q/ε₀
E × 2πrl = λl/ε₀
```

**Solving:**
```
         λ
E =  ————————
      2πε₀r
```

**Direction:** Radially outward (for positive λ), radially inward (for negative λ).

**Key fact:** E ∝ 1/r (for infinite wire — NOT 1/r², unlike point charge!)

### 14.2 Electric Field Due to Uniformly Charged Infinite Plane Sheet ⭐⭐

**Setup:** An infinite plane sheet has surface charge density `σ` (charge per unit area). Find E on either side.

**Derivation:**

Choose Gaussian surface as a **cylinder (pillbox)** with its axis perpendicular to the sheet.
- Let the area of each flat end = A
- The sheet passes through the middle of the cylinder.

Flux through the two flat ends:
```
φ = 2 × EA = 2EA
```
(By symmetry, E is same on both sides and perpendicular to the sheet)

Flux through the curved side = 0 (E is parallel to it)

Charge enclosed:
```
Q = σA
```

By Gauss's Law:
```
2EA = σA/ε₀
```

**Solving:**
```
       σ
E = ————————
      2ε₀
```

**Key observations:**
- E is **independent of distance** from the sheet!
- E is same everywhere on either side of the sheet.
- Direction: Away from sheet (for +ve σ), toward sheet (for −ve σ)

### 14.3 Electric Field Due to Uniformly Charged Thin Spherical Shell ⭐⭐⭐

**Setup:** A thin spherical shell of radius `R` has total charge `Q`. Find E at a point at distance `r` from centre.

#### Case 1: Outside the shell (r > R)

Choose Gaussian surface as a sphere of radius r (> R) centered at the shell centre.

By symmetry, E is radially outward and uniform on this Gaussian surface.

Total flux:
```
φ = E × 4πr²
```

Charge enclosed = Q (total charge of shell)

By Gauss's Law:
```
E × 4πr² = Q/ε₀
```

**Solving:**
```
        1      Q
E =  ————————  ——
       4πε₀   r²
```

**This is exactly like a point charge!** The shell behaves as if ALL charge is concentrated at its centre.

#### Case 2: Inside the shell (r < R)

Choose Gaussian surface as a sphere of radius r (< R) inside the shell.

Charge enclosed = **0** (no charge inside the hollow shell)

By Gauss's Law:
```
E × 4πr² = 0/ε₀ = 0
E = 0
```

**Electric field INSIDE a spherical shell = ZERO**

#### Summary: Spherical Shell

| Region | Electric Field |
|---|---|
| Inside (r < R) | **E = 0** |
| On surface (r = R) | E = Q/4πε₀R² |
| Outside (r > R) | E = Q/4πε₀r² (like a point charge) |

> 📝 **Board Exam:** Draw the graph of E vs r. This shows up as a diagram question!

```
  E
  |
  |    (E=0 inside)     (E decreases as 1/r² outside)
  |________________________
  |                       |\
  |                       | \
  |                       |  \
  |                       |   \________
  0    R (surface)              r
```

---

## 15. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| q = ne | Quantization of charge | C |
| F = kq₁q₂/r² | Coulomb's force | N |
| k = 9×10⁹ Nm²C⁻² | Coulomb's constant | Nm²C⁻² |
| E = F/q₀ = kQ/r² | Electric field | N/C |
| p = q × 2l | Dipole moment | C·m |
| Eaxial = 2p/4πε₀r³ | Field at axial point (short dipole) | N/C |
| Eequatorial = p/4πε₀r³ | Field at equatorial point (short dipole) | N/C |
| τ = pE sinθ | Torque on dipole | N·m |
| φ = EA cosθ | Electric flux | N·m²/C |
| φ = Q/ε₀ | Gauss's Law | N·m²/C |
| E = λ/2πε₀r | Field due to infinite wire | N/C |
| E = σ/2ε₀ | Field due to infinite sheet | N/C |
| E = Q/4πε₀r² | Field outside spherical shell | N/C |
| E = 0 | Field inside spherical shell | — |

---

## 16. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What is the SI unit of electric charge?**  
**Ans:** Coulomb (C)

**Q2. What is the charge of an electron?**  
**Ans:** −1.6 × 10⁻¹⁹ C

**Q3. State the principle of conservation of charge.**  
**Ans:** Electric charge can neither be created nor destroyed. The total charge of an isolated system always remains constant.

**Q4. Define electric field intensity.**  
**Ans:** Electric field intensity at a point is the force experienced per unit positive test charge placed at that point. E = F/q₀

**Q5. What is an electric dipole?**  
**Ans:** A system of two equal and opposite charges (+q and −q) separated by a small distance 2l.

**Q6. Define electric flux.**  
**Ans:** Electric flux through a surface is the total number of electric field lines passing normally through that surface. φ = EA cosθ

**Q7. What is the electric field inside a spherical shell?**  
**Ans:** Zero (E = 0) inside a uniformly charged spherical shell.

**Q8. What is the direction of electric dipole moment?**  
**Ans:** From negative charge (−q) to positive charge (+q).

**Q9. Name the method of charging in which the charged body does not touch the neutral body.**  
**Ans:** Charging by Induction.

**Q10. What is quantization of charge?**  
**Ans:** Charge always exists as integral multiples of elementary charge e. q = ne, where n is an integer.

---

### 📝 2-Mark Questions

**Q11. State and explain Coulomb's Law.**

**Ans:** The force between two point charges is:
```
F = kq₁q₂/r²
```
- Directly proportional to product of charges
- Inversely proportional to square of distance between them
- Acts along the line joining the charges
- k = 9 × 10⁹ Nm²C⁻²

---

**Q12. What are the properties of electric field lines? (List any 4)**

**Ans:**
1. They start from positive charge and end at negative charge.
2. Tangent to the field line at any point gives the direction of E.
3. Two field lines never intersect each other.
4. The number of field lines per unit area is proportional to the magnitude of E.

---

**Q13. Write the expression for torque on an electric dipole in a uniform electric field.**

**Ans:** 
```
τ = pE sinθ
```
Where:
- τ = torque, p = dipole moment
- E = electric field, θ = angle between p and E

Direction: τ tends to align the dipole along E.

Special cases:
- θ = 0°: τ = 0 (stable equilibrium)
- θ = 90°: τ = pE (maximum)

---

**Q14. What do you understand by linear charge density, surface charge density, and volume charge density?**

**Ans:**
- **Linear charge density (λ):** Charge per unit length. λ = q/l. Unit: C/m
- **Surface charge density (σ):** Charge per unit area. σ = q/A. Unit: C/m²
- **Volume charge density (ρ):** Charge per unit volume. ρ = q/V. Unit: C/m³

---

### 📝 3-Mark Questions

**Q15. Prove Gauss's Law from Coulomb's Law.**

**Ans:** *(See Section 13.2 above — write the full proof with steps)*

Step 1: Consider point charge Q at centre of sphere of radius r.
Step 2: E = kQ/r² at surface of sphere.
Step 3: Total flux = E × 4πr².
Step 4: Substitute E: φ = (kQ/r²) × 4πr² = 4πkQ = Q/ε₀.
Hence φ = Q/ε₀ — **Gauss's Law proved.**

---

**Q16. Using Gauss's Law, derive the expression for electric field due to an infinitely long straight wire.**

**Ans:** *(See Section 14.1 — write the full derivation)*
Final answer: E = λ/2πε₀r

---

**Q17. State and explain the superposition principle.**

**Ans:** *(See Section 6.1 and 6.2 — write in 3-4 lines with formula)*

---

### 📝 5-Mark Questions (Long Answer)

**Q18. Derive the expression for electric field at an axial point of an electric dipole.**

**Ans:** *(See Section 10.1 — write full derivation)*

Final Answer: E = 2p / 4πε₀r³ (for short dipole)

---

**Q19. Derive the expression for electric field at an equatorial point of an electric dipole.**

**Ans:** *(See Section 10.2 — write full derivation)*

Final Answer: E = p / 4πε₀r³ (for short dipole, direction opposite to p)

---

**Q20. Using Gauss's Law, find the electric field due to a uniformly charged spherical shell at:**
**(i) A point outside the shell**
**(ii) A point inside the shell**

**Ans:** *(See Section 14.3 — write both cases with diagram)*

(i) Outside: E = Q/4πε₀r²
(ii) Inside: E = 0

---

**Q21. Derive the expression for torque on an electric dipole placed in a uniform electric field. Find the work done in rotating the dipole from angle θ₁ to θ₂.**

**Ans:**

**Part 1 — Torque:**
*(See Section 11.1 — write full derivation)*
Result: τ = pE sinθ

**Part 2 — Work Done:**
```
dW = τ dθ = pE sinθ dθ

W = ∫ pE sinθ dθ  (from θ₁ to θ₂)
  = pE [−cosθ] from θ₁ to θ₂
  = pE (cosθ₁ − cosθ₂)
```

---

**Q22. Using Gauss's Law, derive the expression for electric field due to:**
**(i) Infinite plane sheet of charge**
**(ii) Infinite long straight wire**

**Ans:** *(See Sections 14.2 and 14.1)*

(i) Plane sheet: E = σ/2ε₀
(ii) Infinite wire: E = λ/2πε₀r

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** Two charges 4μC and 2μC are placed 0.2 m apart in air. Find the force between them.

**Solution:**
```
Given: q₁ = 4×10⁻⁶ C, q₂ = 2×10⁻⁶ C, r = 0.2 m

F = kq₁q₂/r²
  = 9×10⁹ × 4×10⁻⁶ × 2×10⁻⁶ / (0.2)²
  = 9×10⁹ × 8×10⁻¹² / 0.04
  = 72×10⁻³ / 0.04
  = 1.8 N
```
**Answer: F = 1.8 N (repulsive, since both are positive)**

---

**Num 2:** How many electrons must be removed from a body to give it a charge of +3.2 μC?

**Solution:**
```
Given: q = +3.2×10⁻⁶ C, e = 1.6×10⁻¹⁹ C

Number of electrons = q/e
= 3.2×10⁻⁶ / 1.6×10⁻¹⁹
= 2×10¹³ electrons
```
**Answer: 2 × 10¹³ electrons**

---

**Num 3:** An electric dipole has a moment of 4×10⁻⁹ C·m. It is placed in a uniform electric field of 5×10⁴ N/C at an angle of 30° with the field. Find the torque.

**Solution:**
```
Given: p = 4×10⁻⁹ C·m, E = 5×10⁴ N/C, θ = 30°

τ = pE sinθ
  = 4×10⁻⁹ × 5×10⁴ × sin 30°
  = 4×10⁻⁹ × 5×10⁴ × 0.5
  = 10⁻⁴ N·m
```
**Answer: τ = 10⁻⁴ N·m = 0.1 mN·m**

---

**Num 4:** A charge of 5μC is placed at the centre of a sphere of radius 0.5 m. Find the total flux through the sphere.

**Solution:**
```
Given: Q = 5×10⁻⁶ C, ε₀ = 8.85×10⁻¹² C²N⁻¹m⁻²

By Gauss's Law: φ = Q/ε₀
= 5×10⁻⁶ / 8.85×10⁻¹²
= 5.65×10⁵ N·m²/C
```
**Answer: φ ≈ 5.65 × 10⁵ N·m²/C**

---

**Num 5:** A long wire has a linear charge density λ = 2×10⁻⁸ C/m. Find E at 0.1 m from the wire.

**Solution:**
```
Given: λ = 2×10⁻⁸ C/m, r = 0.1 m

E = λ/2πε₀r = λ × 2k/r
  = 2×10⁻⁸ × 2×9×10⁹ / 0.1
  = 2×10⁻⁸ × 18×10¹⁰
  = 3600 N/C = 3.6×10³ N/C
```
**Answer: E = 3600 N/C**

---

**Num 6:** A point charge +10μC is at the centre of a spherical shell of radius 5 cm. Find E at (a) 3 cm from centre (b) 10 cm from centre, if the shell has charge −10μC.

**Solution:**

**(a) At r = 3 cm (inside the shell):**
Only the inner charge matters (shell charge doesn't contribute inside it):
```
E = kQ/r² = 9×10⁹ × 10×10⁻⁶ / (0.03)²
  = 9×10⁴ / 9×10⁻⁴ = 10⁸ N/C
```

**(b) At r = 10 cm (outside):**
Total enclosed charge = +10μC + (−10μC) = 0
```
E = k×0/r² = 0
```
**Answer: (a) E = 10⁸ N/C, (b) E = 0**

---

## 17. Objective / MCQ Questions

**Q1.** The charge on an electron is:
- (a) +1.6×10⁻¹⁹ C
- **(b) −1.6×10⁻¹⁹ C** ✓
- (c) 1.6×10⁻²⁰ C
- (d) −1.6×10⁻²⁰ C

---

**Q2.** Coulomb's constant k in SI units is:
- (a) 9×10⁶ Nm²C⁻²
- **(b) 9×10⁹ Nm²C⁻²** ✓
- (c) 9×10¹² Nm²C⁻²
- (d) 9×10³ Nm²C⁻²

---

**Q3.** If the distance between two charges is doubled, the force becomes:
- **(a) 1/4 times** ✓
- (b) 1/2 times
- (c) 2 times
- (d) 4 times

---

**Q4.** The number of electrons in 1 Coulomb of charge is:
- (a) 1.6×10¹⁹
- **(b) 6.25×10¹⁸** ✓
- (c) 1.6×10¹⁸
- (d) 6.25×10¹⁹

---

**Q5.** Electric field lines never intersect because:
- (a) They repel each other
- **(b) E can have only one direction at a point** ✓
- (c) They are parallel
- (d) They are curves

---

**Q6.** Torque on a dipole in a uniform electric field is MAXIMUM when θ =:
- (a) 0°
- **(b) 90°** ✓
- (c) 180°
- (d) 45°

---

**Q7.** The SI unit of dipole moment is:
- (a) C/m
- **(b) C·m** ✓
- (c) N/C
- (d) C²/m

---

**Q8.** Electric field inside a uniformly charged spherical shell is:
- (a) Maximum
- (b) σ/ε₀
- **(c) Zero** ✓
- (d) Infinite

---

**Q9.** Gauss's law is valid for:
- (a) Only spherical surfaces
- (b) Only cylindrical surfaces
- **(c) Any closed surface** ✓
- (d) Only plane surfaces

---

**Q10.** Electric field due to infinite plane sheet of charge (surface charge density σ) is:
- (a) σ/ε₀
- **(b) σ/2ε₀** ✓
- (c) 2σ/ε₀
- (d) σ/4ε₀

---

**Q11.** The electric field due to a long straight wire varies as:
- (a) 1/r²
- **(b) 1/r** ✓
- (c) r
- (d) r²

---

**Q12.** If the charge on an object is doubled, electric field:
- (a) Remains same
- **(b) Doubles** ✓
- (c) Halves
- (d) Becomes zero

---

**Q13.** The force between two charges is F in air. If a medium of dielectric constant K = 4 is introduced between them, the force becomes:
- (a) 4F
- **(b) F/4** ✓
- (c) 2F
- (d) F/2

---

**Q14.** The direction of electric dipole moment is:
- (a) From +q to −q
- **(b) From −q to +q** ✓
- (c) Perpendicular to dipole
- (d) Along the equatorial line

---

**Q15.** At stable equilibrium, the angle between dipole moment and electric field is:
- **(a) 0°** ✓
- (b) 90°
- (c) 180°
- (d) 45°

---

## 18. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Gauss's Law + Applications | 5 marks |
| ⭐⭐⭐ | Torque on Dipole (derivation) | 5 marks |
| ⭐⭐⭐ | Coulomb's Law | 3 marks |
| ⭐⭐⭐ | Properties of Field Lines | 3 marks |
| ⭐⭐ | Dipole field at axial/equatorial | 5 marks |
| ⭐⭐ | Conservation + Quantization | 2 marks |
| ⭐ | Numericals | 2-3 marks |
| ⭐ | MCQs (Objective) | 1 mark each |

---

### 📌 Things to Memorize (Flash Cards)

```
k = 9 × 10⁹ Nm²C⁻²
ε₀ = 8.85 × 10⁻¹² C²N⁻¹m⁻²
e = 1.6 × 10⁻¹⁹ C

Coulomb's Law:   F = kq₁q₂/r²
Electric Field:   E = kQ/r²
Dipole Moment:  p = q × 2l
Torque:           τ = pE sinθ
Gauss's Law:     φ = Q/ε₀
Infinite wire:    E = λ/2πε₀r
Infinite sheet:   E = σ/2ε₀
```

---

### 🔑 Key Differences to Remember

| | Axial Point | Equatorial Point |
|---|---|---|
| E (short dipole) | 2p/4πε₀r³ | p/4πε₀r³ |
| Direction | Along p | Opposite to p |
| Ratio | 2:1 | 1 |

| Conductor | Insulator |
|---|---|
| Free electrons present | No free electrons |
| Charge resides on surface | Charge stays where placed |

| Conduction | Induction |
|---|---|
| Contact needed | No contact needed |
| Same sign charge | Opposite sign charge |

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn Coulomb's Law statement + formula
- [ ] Learn Conservation of charge + Quantization
- [ ] Learn 6 Properties of field lines
- [ ] Practice Torque derivation (write it 2 times)
- [ ] Practice Gauss's Law proof
- [ ] Practice all 3 applications of Gauss's Law
- [ ] Memorize all formulas in Section 15
- [ ] Solve 5 numerical problems
- [ ] Revise all MCQs in Section 17

---

### 💡 Common Mistakes to Avoid

1. **Don't confuse axial and equatorial field directions.** Axial: along p. Equatorial: opposite to p.
2. **Torque formula:** τ = pE sinθ — NOT pE cosθ. Remember: sin of the angle between p and E.
3. **Dipole moment direction:** From NEGATIVE to POSITIVE (many students get this wrong).
4. **Gauss's Law:** Only charge ENCLOSED matters, not charges outside.
5. **Inside spherical shell:** E = 0. Don't use formula E = kQ/r² here.
6. **Coulomb's Law works for POINT CHARGES only.** For extended charge distributions, use Gauss's Law.
7. **Electric flux through closed surface:** Can be positive, negative, or zero depending on charge inside.

---

> **🎯 Final Advice:** Read this README once carefully. Then write all derivations on paper without looking. Solve 10 numericals. Revise MCQs. You are ready for your Bihar Board Exam!
>
> **All the best! आपको परीक्षा में बहुत सफलता मिले! 🙏**

---
*Prepared for Bihar Board Class 12 Physics | Chapter 1: Electric Charges and Fields | Based on NCERT Textbook*