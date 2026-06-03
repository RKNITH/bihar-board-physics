# 📘 Class 12 Physics — Chapter 5: Magnetism and Matter
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [Bar Magnet](#2-bar-magnet)
3. [Properties of Magnetic Field Lines](#3-properties-of-magnetic-field-lines)
4. [Bar Magnet as an Equivalent Solenoid](#4-bar-magnet-as-an-equivalent-solenoid)
5. [Magnetic Dipole Moment](#5-magnetic-dipole-moment)
6. [Torque on a Magnetic Dipole in Uniform Field](#6-torque-on-a-magnetic-dipole-in-uniform-field)
7. [Bar Magnet in Earth's Magnetic Field](#7-bar-magnet-in-earths-magnetic-field)
8. [Earth's Magnetism](#8-earths-magnetism)
9. [Magnetic Properties of Materials](#9-magnetic-properties-of-materials)
10. [Dia, Para, and Ferromagnetic Materials](#10-dia-para-and-ferromagnetic-materials)
11. [Hysteresis Loop](#11-hysteresis-loop)
12. [Permanent Magnets and Electromagnets](#12-permanent-magnets-and-electromagnets)
13. [Important Formulas Summary](#13-important-formulas-summary)
14. [Board Exam Questions with Answers](#14-board-exam-questions-with-answers)
15. [Objective / MCQ Questions](#15-objective--mcq-questions)
16. [Quick Revision Tips](#16-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is the study of **Magnetism** — a fundamental force of nature closely related to electricity.

Think of everyday examples:
- A compass needle always points North. **Why?** → Earth behaves like a giant magnet.
- A fridge magnet sticks to the door. **Why?** → Magnetic force between atoms.
- MRI machines in hospitals use powerful magnets. **Why?** → Ferromagnetism.
- Some materials (like wood, copper) are not attracted to magnets at all. **Why?** → Diamagnetism.

This chapter answers all of these scientifically.

**What you will learn:**
- Properties of bar magnets and magnetic field lines
- Magnetic dipole moment and torque
- Earth's magnetism — declination, inclination, horizontal component
- Types of magnetic materials: Dia, Para, Ferro
- Hysteresis, permanent magnets, and electromagnets

---

## 2. Bar Magnet

### 2.1 What is a Bar Magnet?

A **bar magnet** is a permanent magnet in the shape of a rectangular bar that has two poles — **North Pole (N)** and **South Pole (S)**.

- **Like poles repel** each other (N–N, S–S).
- **Unlike poles attract** each other (N–S).
- If a bar magnet is freely suspended, its **North pole points toward geographic North**.

### 2.2 Magnetic Poles

- **Magnetic poles always exist in pairs** — you cannot separate a North pole from a South pole.
- If you cut a magnet in half, each piece becomes a separate magnet with its own N and S poles.
- This is a fundamental difference from electric charges (which can be isolated).

> 💡 **Key Concept:** Magnetic monopoles (isolated N or S pole) do NOT exist in nature.

### 2.3 Axial Line and Equatorial Line

```
        S ←——— 2l ———→ N
               [BAR MAGNET]

Axial Line: Line passing through both poles (extended on both sides)
Equatorial Line: Perpendicular bisector of the magnet through its centre
```

### 2.4 Magnetic Field at Axial Point ⭐⭐ (5-Mark Derivation)

**Setup:** Point P is on the axis of the bar magnet at distance `r` from the centre. The magnet has pole strength `m` and magnetic length `2l`.

**Derivation:**

Let the bar magnet have poles +m (N) and −m (S) separated by 2l.

Field at P due to North pole (at distance r − l):
```
B_N = (μ₀/4π) × m/(r−l)²      [directed away from N, i.e., toward P]
```

Field at P due to South pole (at distance r + l):
```
B_S = (μ₀/4π) × m/(r+l)²      [directed toward S, i.e., away from P]
```

Net field (B_N > B_S, resultant is along N to P direction):
```
B = B_N − B_S
  = (μ₀/4π) × m × [(r+l)² − (r−l)²] / (r²−l²)²
  = (μ₀/4π) × m × 4rl / (r²−l²)²
  = (μ₀/4π) × 2Mr / (r²−l²)²
```
Where M = m × 2l = magnetic dipole moment.

**For short magnet (l << r):**
```
        μ₀    2M
B =  ———————  ————
       4π     r³
```
**Direction:** Along the direction of magnetic moment M (from S to N inside the magnet, i.e., from S to N extended outward).

---

### 2.5 Magnetic Field at Equatorial Point ⭐⭐ (5-Mark Derivation)

**Setup:** Point P is on the equatorial line at distance `r` from the centre.

Distance from each pole to P:
```
d = √(r² + l²)
```

Field at P due to N pole:
```
B_N = (μ₀/4π) × m/(r²+l²)     [directed from N toward P]
```

Field at P due to S pole:
```
B_S = (μ₀/4π) × m/(r²+l²)     [directed from P toward S]
```

The components along the equatorial line cancel. Components along the axis (parallel to magnet) add up:
```
B = 2 × B_N × cosθ
  = 2 × (μ₀/4π) × m/(r²+l²) × l/√(r²+l²)
  = (μ₀/4π) × M/(r²+l²)^(3/2)
```

**For short magnet (l << r):**
```
        μ₀    M
B =  ———————  ————
       4π     r³
```
**Direction:** Opposite to the direction of magnetic moment M (i.e., from N to S direction).

---

### 2.6 Comparison: Axial vs Equatorial Field

| Property | Axial Point | Equatorial Point |
|---|---|---|
| Formula (short magnet) | B = μ₀×2M/4πr³ | B = μ₀×M/4πr³ |
| Direction | Along M (S→N direction) | Opposite to M (N→S direction) |
| Ratio | B_axial = 2 × B_equatorial | — |

> 📝 **Key Fact:** Axial field is **twice** the equatorial field at the same distance. (Same as electric dipole — but now it's a magnetic dipole!)

---

## 3. Properties of Magnetic Field Lines

### 3.1 What are Magnetic Field Lines?

Magnetic field lines are **imaginary lines** drawn in a magnetic field such that the **tangent at any point** gives the direction of the magnetic field at that point.

### 3.2 Properties ⭐⭐ (3-Mark Question — Very Commonly Asked)

1. **Direction:** Field lines emerge from the **North pole** and enter the **South pole** outside the magnet. Inside the magnet, they travel from S to N.
2. **Closed loops:** Magnetic field lines are **always closed loops** (unlike electric field lines which start/end at charges). They have no starting or ending point.
3. **Never intersect:** Two field lines never cross each other. At any point, the field has only one direction.
4. **Density = Magnitude:** Closer (denser) field lines represent a **stronger** magnetic field; spread out lines represent a weaker field.
5. **Perpendicular at surface:** Field lines are perpendicular to the surface of a magnetic material.
6. **Tangent gives direction:** The tangent drawn at any point on a field line gives the direction of B at that point.

### 3.3 KEY Difference from Electric Field Lines

| Electric Field Lines | Magnetic Field Lines |
|---|---|
| Start at + charge, end at − charge | Always form **closed loops** |
| Do NOT form closed loops | Are always closed |
| Can begin or end at a charge | Have no beginning or end |

> 📝 **Board Exam Tip:** "Magnetic field lines form closed loops" is a 1-mark question answer that many students forget!

---

## 4. Bar Magnet as an Equivalent Solenoid

### 4.1 Concept ⭐ (2-3 Marks)

A solenoid carrying current produces a magnetic field very similar to a bar magnet. This is why we say:

**"A bar magnet is equivalent to a current-carrying solenoid."**

**Why?**
- The end of a solenoid from which field lines emerge acts as the **North Pole**.
- The end from which field lines enter acts as the **South Pole**.
- If we look at the North end of a solenoid, current flows **anticlockwise**.
- If we look at the South end, current flows **clockwise**.

### 4.2 Magnetic Moment of Solenoid

For a solenoid of n turns, length 2l, area A, carrying current I:
```
M = nIA × (2l) ... for full solenoid
```

For a solenoid equivalent to bar magnet:
```
M = NIA
```
Where N = total number of turns, I = current, A = cross-sectional area.

The magnetic field at the axial point of a solenoid (far away) is:
```
B = (μ₀/4π) × 2M/r³
```
This is **identical** to the field of a bar magnet at its axial point!

---

## 5. Magnetic Dipole Moment

### 5.1 Definition ⭐

**Definition:** *"The magnetic dipole moment of a bar magnet is defined as the product of its pole strength and the magnetic length (distance between two poles)."*

```
M = m × 2l
```

Where:
- `M` = Magnetic dipole moment
- `m` = Pole strength (in A·m)
- `2l` = Magnetic length (distance between N and S pole)

**SI Unit:** A·m² (Ampere metre squared) or J/T (Joule per Tesla)

**Direction:** From **South pole to North pole** (inside the magnet) — this is the direction of M.

> 📝 **Comparison with Electric Dipole:**
> Electric dipole moment: p = q × 2l (from −q to +q)
> Magnetic dipole moment: M = m × 2l (from S to N)
> Both follow the same pattern — from "negative" type to "positive" type.

---

## 6. Torque on a Magnetic Dipole in Uniform Field

### 6.1 Derivation ⭐⭐ (5-Mark Question — Must Learn!)

**Setup:**
- A bar magnet (magnetic dipole) with moment M is placed in a uniform magnetic field B.
- The dipole makes an angle `θ` with the direction of field.

**Forces on the dipole:**
- Force on N pole: F = mB (in the direction of B)
- Force on S pole: F = mB (opposite to direction of B)

These two forces are **equal and opposite** → they form a **couple**.
Net translational force = 0 (dipole does not translate in uniform field).
But there is a **net torque** that tends to align the dipole with the field.

**Calculation of Torque:**
```
τ = Force × Perpendicular distance between forces
  = mB × 2l sinθ       [perpendicular distance = 2l sinθ]
  = (m × 2l) × B × sinθ
  = MB sinθ
```

**In vector form:**
```
→    →   →
τ =  M × B
```

**Magnitude:**
```
τ = MB sinθ
```

Where:
- `τ` = Torque (N·m)
- `M` = Magnetic dipole moment (A·m²)
- `B` = Magnetic field (Tesla, T)
- `θ` = Angle between M and B

**Special Cases:**

| Angle θ | Torque | Condition |
|---|---|---|
| 0° | τ = 0 | **Stable Equilibrium** (M along B) |
| 90° | τ = MB (Maximum) | Dipole perpendicular to B |
| 180° | τ = 0 | **Unstable Equilibrium** (M antiparallel to B) |

### 6.2 Work Done in Rotating a Magnetic Dipole

Work done in rotating the dipole from angle θ₁ to θ₂:
```
W = MB(cosθ₁ − cosθ₂)
```

**Potential Energy of Magnetic Dipole:**
```
U = −MB cosθ = −M·B (vector form)
```

**Special values:**
- At θ = 0°: U = −MB (minimum — stable equilibrium)
- At θ = 90°: U = 0
- At θ = 180°: U = +MB (maximum — unstable equilibrium)

> 📝 **Note:** The formula for torque and work done is **identical** to the electric dipole case — just replace p→M and E→B.

---

## 7. Bar Magnet in Earth's Magnetic Field

### 7.1 Equilibrium of a Bar Magnet

A freely suspended bar magnet in Earth's magnetic field (B_H = horizontal component of Earth's field) will align itself along the field direction (geographic North).

When deflected by angle θ and released, the restoring torque is:
```
τ = MB_H sinθ
```

For small angles (sinθ ≈ θ):
```
τ = MB_H θ
```

### 7.2 Time Period of Oscillation ⭐ (2-Mark Formula)

When a bar magnet is freely suspended and given a small angular displacement, it oscillates with time period:

```
        ___
T = 2π √ I/(MB_H)
```

Where:
- `T` = Time period of oscillation (seconds)
- `I` = Moment of inertia of the magnet about the axis of oscillation
- `M` = Magnetic dipole moment
- `B_H` = Horizontal component of Earth's magnetic field

**For a rectangular bar magnet:**
```
I = M_mass(l² + b²)/12
```
Where M_mass = mass of the magnet, l = length, b = breadth.

---

## 8. Earth's Magnetism

### 8.1 Earth as a Magnet

Earth behaves like a **giant bar magnet** with:
- Its **magnetic South pole** near the **geographic North pole** (that's why the N pole of compass points toward geographic North).
- Its **magnetic North pole** near the **geographic South pole**.

> 💡 **Memory Tip:** The geographic North pole of Earth is actually near the magnetic South pole. Opposite poles attract — so the North pole of a compass needle is attracted toward it.

### 8.2 Elements of Earth's Magnetic Field ⭐⭐⭐ (Very Important — Board Exam)

There are **three elements** (also called magnetic elements) that completely describe Earth's magnetic field at any point:

#### (i) Magnetic Declination (α) ⭐

**Definition:** *"The angle between the geographic meridian (true North-South) and the magnetic meridian (direction of Earth's total magnetic field) at a given place is called magnetic declination."*

```
Geographic North
       |
       |  α
       |/
  Magnetic North
```

- Declination varies from place to place.
- It is used in navigation to correct compass readings.
- At most places in India, declination is small.

#### (ii) Magnetic Inclination / Dip (δ) ⭐⭐

**Definition:** *"The angle between the total magnetic field of Earth (B) and the horizontal plane at a given place is called the angle of dip or magnetic inclination."*

```
Horizontal plane ————————————
                       \  δ
                        \
                         B (total field, pointing into Earth in N. hemisphere)
```

- At the **magnetic equator**: δ = 0° (field is horizontal)
- At the **magnetic poles**: δ = 90° (field is vertical)
- In India: δ is approximately 11° to 30° (varies by location)

**Instrument used:** A **dip needle** or **inclinometer** measures the angle of dip.

#### (iii) Horizontal Component of Earth's Field (B_H) ⭐⭐

**Definition:** *"The component of Earth's total magnetic field in the horizontal direction is called the horizontal component of Earth's magnetic field."*

If B = total intensity of Earth's field, δ = angle of dip:

```
B_H = B cosδ       (Horizontal component)
B_V = B sinδ       (Vertical component)
```

**Relation between B, B_H, B_V:**
```
B² = B_H² + B_V²

tanδ = B_V / B_H
```

**At magnetic equator:** B_V = 0, B_H = B (maximum horizontal component)
**At magnetic poles:** B_H = 0, B_V = B (entire field is vertical)

> 📝 **Board Exam Tip:** Drawing the right-angle triangle with B, B_H, B_V and angle δ is essential for derivation. Practice this diagram!

```
        B_H
        ————————
        |      /
        |     /
   B_V  |    /  B (total)
        |   /
        |  /
        | / δ
        |/
```

---

## 9. Magnetic Properties of Materials

### 9.1 Basic Definitions ⭐⭐ (2-3 Marks)

When a material is placed in an external magnetic field, its response is described by these quantities:

#### (i) Intensity of Magnetisation (I or M)

**Definition:** *"The magnetic moment developed per unit volume of a material when placed in a magnetic field."*

```
I = M/V = Total magnetic moment / Volume
```
**Unit:** A/m

#### (ii) Magnetic Intensity / Magnetising Field (H)

**Definition:** *"The magnetic intensity H represents the ability of an external agency to magnetise a material."*

```
B = μ₀(H + I)
```
Or equivalently: B = μ₀μᵣH = μH

**Unit:** A/m

#### (iii) Magnetic Susceptibility (χ_m) ⭐

**Definition:** *"Magnetic susceptibility is the ratio of intensity of magnetisation to the magnetic intensity."*

```
χ_m = I/H
```

- **No unit** (dimensionless quantity)
- Positive χ_m → material gets magnetised in the direction of H (paramagnetic, ferromagnetic)
- Negative χ_m → material gets magnetised opposite to H (diamagnetic)
- Large χ_m → material magnetises strongly (ferromagnetic)

#### (iv) Magnetic Permeability (μ) ⭐

**Definition:** *"Magnetic permeability is the ratio of magnetic flux density B to the magnetic intensity H."*

```
μ = B/H
```

**Unit:** T·m/A = Henry/m (H/m)

**Relative Permeability:**
```
μᵣ = μ/μ₀
```

**Relationship between μᵣ and χ_m:**
```
μᵣ = 1 + χ_m
```

---

## 10. Dia, Para, and Ferromagnetic Materials

### 10.1 Diamagnetic Materials ⭐⭐

**Definition:** Materials that are **weakly repelled** by magnets and get magnetised **opposite** to the applied field.

**Examples:** Bismuth (Bi), Copper (Cu), Silver (Ag), Gold (Au), Water, Mercury, Nitrogen gas, Lead

**Properties:**

| Property | Value/Behaviour |
|---|---|
| Susceptibility (χ_m) | Small, **negative** (−1 ≤ χ_m < 0) |
| Relative permeability (μᵣ) | Slightly less than 1 |
| Behaviour in external field | Moves from stronger to weaker field region |
| Effect of temperature | Practically **independent** of temperature |
| Internal magnetic field | B inside < B₀ (external field) |

**Explanation at atomic level:**
- Orbital motion of electrons produces tiny magnetic moments.
- In diamagnetic materials, these moments are paired and cancel out — **net magnetic moment of atom = 0**.
- When an external field is applied, Lenz's law effect induces a small moment **opposing** the field.
- Hence diamagnetism is a **universal** property (all materials have it, but it's very weak and masked by para/ferromagnetism).

**Example Diagram:**
```
External field B₀ →→→→→
                ___
  N → [  Cu  ] → S    (Slightly repelled from strong field region)
                ---
```

### 10.2 Paramagnetic Materials ⭐⭐

**Definition:** Materials that are **weakly attracted** by magnets and get magnetised **in the direction** of the applied field.

**Examples:** Aluminium (Al), Platinum (Pt), Chromium (Cr), Manganese (Mn), Sodium (Na), Oxygen gas, Liquid oxygen

**Properties:**

| Property | Value/Behaviour |
|---|---|
| Susceptibility (χ_m) | Small, **positive** (0 < χ_m < 0.1) |
| Relative permeability (μᵣ) | Slightly more than 1 |
| Behaviour in external field | Moves from weaker to stronger field region |
| Effect of temperature | **Inversely proportional** to temperature (Curie's Law) |
| Internal magnetic field | B inside slightly > B₀ |

**Curie's Law:** ⭐
```
χ_m ∝ 1/T      or      χ_m = C/T
```
Where C = Curie constant, T = absolute temperature (in Kelvin)

**Explanation at atomic level:**
- Each atom has a **permanent magnetic dipole moment** (due to unpaired electrons).
- Without external field: moments are randomly oriented → no net magnetisation.
- With external field: moments try to align with the field → weak magnetisation in field direction.
- At higher temperature, thermal agitation randomizes alignment → susceptibility decreases.

### 10.3 Ferromagnetic Materials ⭐⭐⭐ (Most Important)

**Definition:** Materials that are **strongly attracted** by magnets and get magnetised **very strongly** in the direction of the applied field.

**Examples:** Iron (Fe), Nickel (Ni), Cobalt (Co), Gadolinium, Dysprosium

**Properties:**

| Property | Value/Behaviour |
|---|---|
| Susceptibility (χ_m) | Very large, **positive** (χ_m >> 1, can be thousands) |
| Relative permeability (μᵣ) | Much greater than 1 (μᵣ >> 1) |
| Behaviour in external field | Strongly attracted toward strong field region |
| Effect of temperature | Decreases with temperature; above **Curie temperature (T_C)**, becomes paramagnetic |
| Retains magnetism? | Yes, even after field is removed (residual magnetism) |

**Concept of Magnetic Domains:** ⭐⭐
- In ferromagnetic materials, atoms are grouped into small regions called **magnetic domains**.
- Within each domain, all atomic magnetic moments are **aligned parallel** — very strong magnetisation.
- In unmagnetised material: domains point in **random directions** → no net magnetisation.
- In external field: domains aligned with field **grow** at the expense of others → strong net magnetisation.
- On removing field: most alignment remains → **residual magnetism** (the material stays magnetised).

**Curie Temperature (T_C):** ⭐
- Above this temperature, ferromagnetic material becomes **paramagnetic**.
- For Iron: T_C ≈ 1043 K (770°C)
- For Nickel: T_C ≈ 631 K (358°C)
- For Cobalt: T_C ≈ 1388 K (1115°C)

---

### 10.4 Comparison Table — Dia, Para, Ferro ⭐⭐⭐

| Property | Diamagnetic | Paramagnetic | Ferromagnetic |
|---|---|---|---|
| Examples | Cu, Bi, Ag, water | Al, Pt, Na, O₂ | Fe, Ni, Co |
| χ_m | Small, negative | Small, positive | Very large, positive |
| μᵣ | Slightly < 1 | Slightly > 1 | >> 1 (thousands) |
| Attracted/repelled | Weakly repelled | Weakly attracted | Strongly attracted |
| Effect of temperature | Independent | χ ∝ 1/T (Curie's Law) | Becomes paramagnetic above T_C |
| Domains | No | No | **Yes** |
| Retains magnetism | No | No | Yes (Permanent magnet possible) |

---

## 11. Hysteresis Loop

### 11.1 What is Hysteresis? ⭐⭐ (3-5 Marks — Board Exam Favourite)

**Definition:** *"The lagging of magnetisation (B) behind the magnetising field (H) when the magnetising field is varied cyclically is called hysteresis."*

When a ferromagnetic material is subjected to a cycle of magnetisation (H varied from 0 → max → 0 → negative max → 0), the B-H curve forms a loop. This loop is called the **Hysteresis Loop** or **B-H curve**.

### 11.2 Key Terms in Hysteresis Loop ⭐⭐

**Draw and label the loop:**

```
        B
        |        C (Saturation)
        |      /|
        |    /  |
  B_r --D----|--|---------
        |    |  |        \  A
        |    |  |         |
   ——————————|——|————————————— H
        |    |  |
     -H_c    |  |    H
        |    |  |
        F    |  E (Saturation in opposite direction)
        |  /
        G
```

| Term | Symbol | Definition |
|---|---|---|
| **Retentivity / Remanence** | B_r | Value of B when H = 0 after saturation. Ability to retain magnetism. |
| **Coercivity / Coercive force** | H_c | Value of H needed to reduce B to zero. |
| **Saturation magnetisation** | B_s | Maximum value of B achieved in the material. |

**Retentivity** = OD (in the diagram) — the residual magnetism remaining when H is returned to zero.

**Coercivity** = OG (the reverse H needed to demagnetise the material).

### 11.3 Significance of the Hysteresis Loop ⭐

- **Area of the loop** = Energy dissipated as **heat** per unit volume per cycle of magnetisation.
- **Narrow loop** → less energy loss → good for **transformer cores, electromagnet cores** (soft iron).
- **Wide loop** → high retentivity and coercivity → good for **permanent magnets** (steel, alnico).

### 11.4 Properties: Soft Iron vs Steel ⭐⭐

| Property | Soft Iron | Steel / Hard Iron |
|---|---|---|
| Retentivity | Low | High |
| Coercivity | Low | High |
| Hysteresis loss | Small (narrow loop) | Large (wide loop) |
| Suitable for | Electromagnets, transformer cores, relay cores | Permanent magnets |
| Magnetised easily? | Yes | Relatively harder |
| Demagnetised easily? | Yes | No (retains magnetism) |

> 📝 **Board Exam:** The reason soft iron is used in transformers and steel for permanent magnets comes directly from hysteresis loop properties. Learn this comparison.

---

## 12. Permanent Magnets and Electromagnets

### 12.1 Permanent Magnets ⭐

**Definition:** Substances that retain their ferromagnetic properties for a long time are called permanent magnets.

**Properties needed for permanent magnets:**
- High retentivity (to remain strongly magnetised)
- High coercivity (to resist demagnetisation)
- High saturation magnetisation

**Materials used:** Steel, Alnico (Al-Ni-Co alloy), Lodestone (Fe₃O₄), Ferrites, Rare earth magnets (Neodymium: Nd₂Fe₁₄B)

**Making a permanent magnet:**
- Pass a hard ferromagnetic material through a strong magnetic field.
- Or stroke a steel bar repeatedly with a permanent magnet.
- By placing the material inside a solenoid and passing a strong current.

### 12.2 Electromagnets ⭐

**Definition:** Magnets made using electric current (current-carrying solenoid with an iron core) are called electromagnets.

**Properties needed for electromagnet core:**
- High permeability (to produce strong B for small H)
- Low retentivity (field should disappear when current is switched off)
- Low coercivity (easy to demagnetise)
- Low hysteresis loss

**Material used:** Soft iron (best for electromagnet core)

**Advantages of electromagnets:**
- Magnetic field can be switched on and off by controlling current.
- Field strength can be varied by varying current.
- Used in: cranes (to lift heavy iron objects), electric bells, relays, MRI machines, particle accelerators.

### 12.3 Comparison: Permanent Magnet vs Electromagnet

| Property | Permanent Magnet | Electromagnet |
|---|---|---|
| Material | Steel, Alnico | Soft iron core + solenoid |
| Strength | Fixed | Can be varied |
| Retentivity | High | Low |
| Coercivity | High | Low |
| Switched on/off | No | Yes |
| Energy needed | No (once made) | Yes (electricity) |
| Used in | Speakers, compass | Cranes, MRI, relays |

---

## 13. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| M = m × 2l | Magnetic dipole moment | A·m² |
| B_axial = μ₀×2M/4πr³ | Field at axial point (short magnet) | T |
| B_equatorial = μ₀×M/4πr³ | Field at equatorial point (short magnet) | T |
| τ = MB sinθ | Torque on magnetic dipole | N·m |
| W = MB(cosθ₁ − cosθ₂) | Work done in rotating dipole | J |
| U = −MB cosθ | Potential energy of dipole | J |
| T = 2π√(I/MB_H) | Time period of oscillation | s |
| B_H = B cosδ | Horizontal component of Earth's field | T |
| B_V = B sinδ | Vertical component of Earth's field | T |
| tanδ = B_V/B_H | Relation involving angle of dip | — |
| χ_m = I/H | Magnetic susceptibility | Dimensionless |
| μᵣ = 1 + χ_m | Relative permeability and susceptibility | Dimensionless |
| χ_m = C/T | Curie's Law (paramagnetic) | — |
| B = μ₀(H + I) | Relation between B, H, and magnetisation | T |

**Constants:**
```
μ₀ = 4π × 10⁻⁷ T·m/A (permeability of free space)
μ₀/4π = 10⁻⁷ T·m/A
```

---

## 14. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What are the SI units of magnetic dipole moment?**
**Ans:** A·m² (Ampere metre squared) or J/T (Joule per Tesla)

**Q2. What is the angle of dip at the magnetic equator?**
**Ans:** Zero (0°). At the magnetic equator, the Earth's field is horizontal and there is no vertical component.

**Q3. What is the angle of dip at the magnetic poles?**
**Ans:** 90°. At the poles, the Earth's field is entirely vertical.

**Q4. Can a magnetic monopole exist?**
**Ans:** No. Magnetic monopoles do not exist. Magnetic poles always exist in pairs (North and South).

**Q5. Name a diamagnetic material.**
**Ans:** Bismuth (Bi) or Copper (Cu) or Water.

**Q6. Name a paramagnetic material.**
**Ans:** Aluminium (Al) or Platinum (Pt).

**Q7. Name a ferromagnetic material.**
**Ans:** Iron (Fe), Nickel (Ni), or Cobalt (Co).

**Q8. What is magnetic susceptibility?**
**Ans:** Magnetic susceptibility (χ_m) is the ratio of intensity of magnetisation (I) to the magnetising field intensity (H). χ_m = I/H. It is dimensionless.

**Q9. What is retentivity?**
**Ans:** Retentivity is the value of magnetic flux density (B) remaining in a ferromagnetic material when the magnetising field H is reduced to zero after saturation. It represents the ability to retain magnetism.

**Q10. What is coercivity?**
**Ans:** Coercivity is the magnitude of the reverse magnetising field required to completely demagnetise a ferromagnetic material (reduce B to zero).

**Q11. Why is soft iron used as the core of a transformer?**
**Ans:** Soft iron has high permeability (magnetises easily), low coercivity, and narrow hysteresis loop (low energy loss per cycle). This makes it ideal for transformer cores.

**Q12. What is the direction of the magnetic dipole moment of a bar magnet?**
**Ans:** From the South pole to the North pole (inside the magnet).

---

### 📝 2-Mark Questions

**Q13. State Curie's Law for paramagnetic materials.**

**Ans:** Curie's Law states that the magnetic susceptibility of a paramagnetic material is inversely proportional to the absolute temperature.
```
χ_m = C/T
```
Where C is the Curie constant and T is the temperature in Kelvin.

**Explanation:** At higher temperatures, thermal agitation randomises the alignment of magnetic dipoles, reducing magnetisation. Therefore, susceptibility decreases with increasing temperature.

---

**Q14. What is magnetic declination and magnetic inclination?**

**Ans:**

**Magnetic Declination (α):** The angle between the geographic meridian (direction of geographic North) and the magnetic meridian (direction of Earth's horizontal field) at a given place.

**Magnetic Inclination / Dip (δ):** The angle between the direction of Earth's total magnetic field (B) and the horizontal plane at a given place.

---

**Q15. Define horizontal component of Earth's magnetic field. Derive its relation with total field.**

**Ans:** The component of Earth's total magnetic field in the horizontal direction is the horizontal component (B_H).

If B = total field, δ = angle of dip:
```
B_H = B cosδ
B_V = B sinδ
tanδ = B_V/B_H
B² = B_H² + B_V²
```

---

**Q16. Write two differences between diamagnetic and paramagnetic materials.**

**Ans:**

| Property | Diamagnetic | Paramagnetic |
|---|---|---|
| Susceptibility | Small, negative | Small, positive |
| Behaviour in external field | Weakly repelled | Weakly attracted |
| Temperature dependence | Independent | χ ∝ 1/T |

---

**Q17. What are magnetic domains? How do they explain ferromagnetism?**

**Ans:** Magnetic domains are small regions inside a ferromagnetic material where all atomic magnetic dipole moments are aligned in the same direction, forming a region of strong local magnetisation.

In an unmagnetised ferromagnet, domains are randomly oriented, so net magnetisation is zero. When placed in an external field, domains aligned with the field grow at the expense of others, producing a very strong net magnetisation. This explains why ferromagnets can be strongly magnetised.

---

### 📝 3-Mark Questions

**Q18. State and explain the hysteresis loop. Define retentivity and coercivity.**

**Ans:**

**Hysteresis:** The lagging of magnetisation B behind the applied field H, during cyclic magnetisation of a ferromagnetic material, is called hysteresis. The closed curve traced by B vs H is the hysteresis loop.

**Retentivity:** The value of B remaining when H is brought back to zero (after saturation). It measures the ability of the material to retain magnetism.

**Coercivity:** The reverse field H required to make B = 0. It measures the resistance of the material to demagnetisation.

**Significance of loop area:** Area enclosed by the hysteresis loop = energy dissipated as heat per unit volume per cycle.

---

**Q19. Using Gauss's Law for Magnetism, show that isolated magnetic poles cannot exist.**

**Ans:**

Gauss's Law for Magnetism states:
```
∮ B · dA = 0
```
The total magnetic flux through any closed surface is always **zero**.

This means the number of field lines entering any closed surface equals the number leaving it. Magnetic field lines always form closed loops — they don't start or end anywhere. This is fundamentally different from electric field lines which start at positive charges and end at negative charges.

If a magnetic monopole (isolated N or S pole) existed, the flux through a closed surface surrounding it would be non-zero (just like Gauss's law for electricity gives non-zero flux for an enclosed charge). Since the law demands ∮ B · dA = 0 always, isolated magnetic poles cannot exist. Poles always come in pairs.

---

### 📝 5-Mark Questions (Long Answer)

**Q20. Derive the expression for the magnetic field due to a bar magnet at an axial point. Compare it with the equatorial field.**

**Ans:** *(See Sections 2.4 and 2.5 — write full derivations)*

Axial: B = μ₀ × 2M / (4πr³)
Equatorial: B = μ₀ × M / (4πr³)

Ratio: B_axial : B_equatorial = 2 : 1 at the same distance.

---

**Q21. Derive the expression for torque on a bar magnet in a uniform magnetic field. State conditions for stable and unstable equilibrium.**

**Ans:** *(See Section 6.1 — write full derivation)*

Result: τ = MB sinθ

- θ = 0°: τ = 0, Stable Equilibrium
- θ = 90°: τ = MB (Maximum)
- θ = 180°: τ = 0, Unstable Equilibrium

---

**Q22. Discuss the magnetic properties of diamagnetic, paramagnetic, and ferromagnetic materials. Give two examples of each.**

**Ans:** *(See Section 10 and comparison table — write with examples and properties in detail)*

---

**Q23. What is hysteresis? Draw the B-H curve (hysteresis loop) for a ferromagnetic material and explain retentivity, coercivity, and the area of the loop. Why is soft iron preferred over steel for transformer cores?**

**Ans:** *(See Section 11 — write full explanation with labeled diagram and comparison table)*

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** A bar magnet of moment M = 5 A·m² is placed in a magnetic field B = 0.4 T at angle 30°. Find the torque on it.

**Solution:**
```
Given: M = 5 A·m², B = 0.4 T, θ = 30°

τ = MB sinθ
  = 5 × 0.4 × sin 30°
  = 5 × 0.4 × 0.5
  = 1.0 N·m
```
**Answer: τ = 1.0 N·m**

---

**Num 2:** The angle of dip at a place is 45° and the horizontal component of Earth's field is 0.4 × 10⁻⁴ T. Find the total magnetic field and the vertical component.

**Solution:**
```
Given: δ = 45°, B_H = 0.4 × 10⁻⁴ T

B_H = B cosδ
B = B_H / cosδ = 0.4×10⁻⁴ / cos 45°
  = 0.4×10⁻⁴ / (1/√2)
  = 0.4√2 × 10⁻⁴
  ≈ 0.566 × 10⁻⁴ T

B_V = B sinδ = 0.566×10⁻⁴ × sin 45°
    = 0.566×10⁻⁴ × (1/√2)
    = 0.4 × 10⁻⁴ T
```
**Answer: B = 5.66 × 10⁻⁵ T, B_V = 4 × 10⁻⁵ T**

---

**Num 3:** A short bar magnet has a magnetic moment of 0.48 J/T. Find the magnitude of the magnetic field due to it at a distance of 10 cm from the magnet on (a) its axial line, (b) its equatorial line.

**Solution:**
```
Given: M = 0.48 J/T, r = 10 cm = 0.1 m

(a) Axial:
B_axial = (μ₀/4π) × 2M/r³
        = 10⁻⁷ × 2 × 0.48 / (0.1)³
        = 10⁻⁷ × 0.96 / 10⁻³
        = 10⁻⁷ × 960
        = 9.6 × 10⁻⁵ T = 0.96 G

(b) Equatorial:
B_equatorial = (μ₀/4π) × M/r³
             = 10⁻⁷ × 0.48 / (0.1)³
             = 10⁻⁷ × 480
             = 4.8 × 10⁻⁵ T = 0.48 G
```
**Answer: (a) 0.96 G, (b) 0.48 G** *(Note: 1 G = 10⁻⁴ T)*

---

**Num 4:** A bar magnet has a time period of 3 s when suspended freely. If it is placed in a uniform field that doubles the horizontal component, what will be its new time period?

**Solution:**
```
T = 2π√(I/MB_H)

Original: T₁ = 3 s with B_H
New: B_H' = 2B_H

T₁/T₂ = √(B_H'/B_H) = √2

T₂ = T₁/√2 = 3/√2 ≈ 3/1.414 ≈ 2.12 s
```
**Answer: T₂ ≈ 2.12 s**

---

**Num 5:** A solenoid with 500 turns, length 0.4 m, radius 0.01 m carries current 5 A. Find its magnetic dipole moment.

**Solution:**
```
Given: N = 500, I = 5 A, r = 0.01 m

A = πr² = π × (0.01)² = 3.14 × 10⁻⁴ m²

M = NIA = 500 × 5 × 3.14 × 10⁻⁴
  = 500 × 5 × 3.14 × 10⁻⁴
  = 0.785 A·m²
```
**Answer: M ≈ 0.785 A·m²**

---

## 15. Objective / MCQ Questions

**Q1.** At the magnetic equator of the Earth, the angle of dip is:
- (a) 90°
- **(b) 0°** ✓
- (c) 45°
- (d) 180°

---

**Q2.** A bar magnet cannot be separated into individual poles because:
- (a) Poles are too heavy
- **(b) Magnetic monopoles do not exist** ✓
- (c) Magnets are fragile
- (d) Poles have equal strength

---

**Q3.** The SI unit of magnetic pole strength is:
- **(a) A·m** ✓
- (b) A·m²
- (c) T
- (d) Wb

---

**Q4.** Magnetic susceptibility of a diamagnetic material is:
- (a) Large positive
- (b) Small positive
- **(c) Small negative** ✓
- (d) Zero

---

**Q5.** The time period of oscillation of a bar magnet in Earth's field is T. If the moment of the magnet is doubled, the new time period will be:
- (a) 2T
- **(b) T/√2** ✓
- (c) T√2
- (d) T/2

---

**Q6.** Which of the following is a ferromagnetic material?
- (a) Aluminium
- (b) Copper
- **(c) Nickel** ✓
- (d) Platinum

---

**Q7.** The area enclosed by the hysteresis loop represents:
- (a) Retentivity of the material
- **(b) Energy dissipated per unit volume per cycle** ✓
- (c) Coercivity of the material
- (d) Susceptibility

---

**Q8.** Soft iron is used in transformer cores because it has:
- (a) High retentivity and high coercivity
- **(b) Low retentivity and low coercivity** ✓
- (c) High retentivity and low coercivity
- (d) Low retentivity and high coercivity

---

**Q9.** At a place, the angle of dip is 30° and the total intensity of Earth's field is B. The horizontal component is:
- (a) B/2
- **(b) B√3/2** ✓
- (c) B/√3
- (d) B√2

---

**Q10.** The B-H curve (hysteresis loop) for a permanent magnet material should have:
- **(a) Wide loop with high retentivity and high coercivity** ✓
- (b) Narrow loop with low coercivity
- (c) High permeability and low retentivity
- (d) Zero coercivity

---

**Q11.** Curie's Law states that susceptibility of a paramagnetic material:
- (a) Increases with temperature
- **(b) Decreases with temperature** ✓
- (c) Is independent of temperature
- (d) First increases, then decreases

---

**Q12.** The magnetic field at an equatorial point of a bar magnet is directed:
- **(a) Opposite to the magnetic moment** ✓
- (b) Along the magnetic moment
- (c) Perpendicular to the magnetic moment
- (d) At 45° to the magnetic moment

---

**Q13.** If angle of dip at a place is δ, then:
- (a) tanδ = B_H/B_V
- **(b) tanδ = B_V/B_H** ✓
- (c) tanδ = B/B_H
- (d) tanδ = B_H/B

---

**Q14.** A magnetic dipole is in stable equilibrium when the angle between M and B is:
- **(a) 0°** ✓
- (b) 90°
- (c) 180°
- (d) 45°

---

**Q15.** Above the Curie temperature, a ferromagnetic material becomes:
- (a) Diamagnetic
- **(b) Paramagnetic** ✓
- (c) Non-magnetic
- (d) Superconducting

---

## 16. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Torque on magnetic dipole (derivation) | 5 marks |
| ⭐⭐⭐ | Elements of Earth's Magnetism | 3-5 marks |
| ⭐⭐⭐ | Dia, Para, Ferro comparison | 3-5 marks |
| ⭐⭐⭐ | Hysteresis Loop | 3-5 marks |
| ⭐⭐ | Field at Axial/Equatorial points | 5 marks |
| ⭐⭐ | Bar Magnet as Solenoid | 3 marks |
| ⭐⭐ | Permanent Magnets vs Electromagnets | 2-3 marks |
| ⭐ | Curie's Law | 2 marks |
| ⭐ | Numericals | 2-3 marks |
| ⭐ | MCQs (Objective) | 1 mark each |

---

### 📌 Things to Memorize (Flash Cards)

```
μ₀ = 4π × 10⁻⁷ T·m/A
μ₀/4π = 10⁻⁷ T·m/A

Magnetic moment:      M = m × 2l
Axial field:          B = μ₀×2M / 4πr³
Equatorial field:     B = μ₀×M / 4πr³
Torque:               τ = MB sinθ
Work done:            W = MB(cosθ₁ − cosθ₂)
Time period:          T = 2π√(I/MB_H)
Susceptibility:       χ_m = I/H
Permeability rel.:    μᵣ = 1 + χ_m
Curie's Law:          χ_m = C/T
Horizontal comp.:     B_H = B cosδ
Vertical comp.:       B_V = B sinδ
```

---

### 🔑 Key Differences to Remember

| | Axial Point | Equatorial Point |
|---|---|---|
| B (short magnet) | μ₀×2M/4πr³ | μ₀×M/4πr³ |
| Direction | Along M (S→N direction outward) | Opposite to M |
| Ratio | 2:1 | 1 |

| | Soft Iron | Steel |
|---|---|---|
| Retentivity | Low | High |
| Coercivity | Low | High |
| Used for | Electromagnets, transformers | Permanent magnets |

| | Diamagnetic | Paramagnetic | Ferromagnetic |
|---|---|---|---|
| χ_m | Negative (small) | Positive (small) | Positive (very large) |
| μᵣ | Slightly < 1 | Slightly > 1 | >> 1 |

---

### 🔗 Key Analogies: Electric Dipole vs Magnetic Dipole

| Quantity | Electric Dipole | Magnetic Dipole |
|---|---|---|
| Dipole moment | p = q × 2l | M = m × 2l |
| Axial field | E = 2p/4πε₀r³ | B = μ₀×2M/4πr³ |
| Equatorial field | E = p/4πε₀r³ | B = μ₀×M/4πr³ |
| Torque | τ = pE sinθ | τ = MB sinθ |
| Work done | W = pE(cosθ₁−cosθ₂) | W = MB(cosθ₁−cosθ₂) |
| Potential energy | U = −pE cosθ | U = −MB cosθ |

> 📝 The formulas are **identical** in structure! If you know the electric dipole formulas, you already know the magnetic dipole formulas — just swap p → M and E → B.

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn and practice torque derivation (write it 2 times)
- [ ] Learn all three elements of Earth's magnetism with definitions
- [ ] Memorize the Dia, Para, Ferro comparison table
- [ ] Understand hysteresis loop — draw and label it
- [ ] Learn why soft iron → transformer, steel → permanent magnet
- [ ] Learn the axial and equatorial field formulas (short dipole)
- [ ] Memorize all formulas in Section 13
- [ ] Practice the 5 numerical problems
- [ ] Revise all MCQs in Section 15
- [ ] Revise Curie's Law and Curie temperature concept

---

### 💡 Common Mistakes to Avoid

1. **Direction of M:** Always from S pole to N pole inside the magnet. Students often confuse this.
2. **Axial vs Equatorial direction:** Axial — along M. Equatorial — OPPOSITE to M. Remember this!
3. **Gauss's law for magnetism:** ∮ B·dA = 0 (NOT Q/ε₀). There are no magnetic monopoles.
4. **Dip at equator is 0°, not 90°.** At poles it is 90°.
5. **Soft iron for electromagnets, NOT permanent magnets.** Steel is for permanent magnets.
6. **Curie's Law:** Susceptibility DECREASES with temperature for paramagnetics (χ ∝ 1/T).
7. **Ferromagnetic above Curie temp:** Becomes PARAMAGNETIC, not diamagnetic.
8. **Magnetic field lines form CLOSED LOOPS** — unlike electric field lines.
9. **Torque formula:** τ = MB sinθ (not cosθ). Maximum at 90°.
10. **Retentivity and coercivity for permanent magnets must both be HIGH.**

---

*Prepared for Bihar Board Class 12 Physics | Chapter 5: Magnetism and Matter | Based on NCERT Textbook*