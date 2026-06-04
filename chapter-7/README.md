# 📘 Class 12 Physics — Chapter 7: Alternating Current
### Bihar Board (BSEB) | NCERT Based | Complete Study Guide
> **For students starting from scratch → Board Exam Ready**
>
> _Covers every topic, subtopic, formula, theory, derivation, proof, and board-exam questions._

---

## 📋 Table of Contents

1. [What is This Chapter About?](#1-what-is-this-chapter-about)
2. [AC vs DC — Basic Difference](#2-ac-vs-dc--basic-difference)
3. [AC Voltage and Current — Representation](#3-ac-voltage-and-current--representation)
4. [Peak Value, RMS Value, and Average Value](#4-peak-value-rms-value-and-average-value)
5. [AC Voltage Applied to a Resistor](#5-ac-voltage-applied-to-a-resistor)
6. [AC Voltage Applied to an Inductor](#6-ac-voltage-applied-to-an-inductor)
7. [AC Voltage Applied to a Capacitor](#7-ac-voltage-applied-to-a-capacitor)
8. [AC Voltage Applied to Series LCR Circuit](#8-ac-voltage-applied-to-series-lcr-circuit)
9. [Resonance in LCR Circuit](#9-resonance-in-lcr-circuit)
10. [Power in AC Circuit](#10-power-in-ac-circuit)
11. [LC Oscillations](#11-lc-oscillations)
12. [Transformers](#12-transformers)
13. [Important Formulas Summary](#13-important-formulas-summary)
14. [Board Exam Questions with Answers](#14-board-exam-questions-with-answers)
15. [Objective / MCQ Questions](#15-objective--mcq-questions)
16. [Quick Revision Tips](#16-quick-revision-tips)

---

## 1. What is This Chapter About?

This chapter is about **Alternating Current (AC)** — the type of electricity that powers your home, school, and every building around you.

Think of it this way:
- You plug in your phone charger. The power socket gives **AC current**. Why not DC? → Because AC is **easy to transmit** over long distances without much energy loss.
- Your fan runs at different speeds when you turn the regulator. Why? → Because **AC frequency and voltage** can be controlled.
- Radio stations broadcast at specific frequencies. Why? → **Resonance** in LC circuits selects a particular frequency.
- A transformer steps up voltage for long distance transmission and steps it down for home use. How? → **Electromagnetic induction** using AC.

This chapter answers all these questions scientifically.

**What you will learn:**
- What is AC and how it differs from DC
- RMS and Peak values of AC
- Behaviour of Resistor, Inductor, and Capacitor in AC circuits
- LCR Series Circuit and Resonance
- Power in AC circuits and Power Factor
- LC Oscillations
- Working of a Transformer

---

## 2. AC vs DC — Basic Difference

### 2.1 Direct Current (DC)
- Current flows in **one direction only**.
- Magnitude is **constant** with time.
- **Example:** Battery, Torch, Mobile phone.

### 2.2 Alternating Current (AC)
- Current **periodically reverses** direction.
- Magnitude **varies sinusoidally** with time.
- **Example:** Power supply from socket (220V, 50 Hz in India).

### 2.3 Comparison Table

| Property | DC | AC |
|---|---|---|
| Direction | Unidirectional | Bidirectional (reverses) |
| Magnitude | Constant | Varies sinusoidally |
| Frequency | Zero | 50 Hz (in India) |
| Generation | Battery / Cell | AC Generator |
| Transmission | Difficult over long distance | Easy over long distance |
| Use | Electronics, batteries | Home appliances, motors |
| Transformer works? | No | Yes |

> 📝 **Why India uses 50 Hz AC?** India follows the international standard of 50 Hz (50 cycles per second). USA uses 60 Hz. Bihar Board may ask this as 1-mark question.

---

## 3. AC Voltage and Current — Representation

### 3.1 Mathematical Representation

An AC voltage source produces a **sinusoidally varying voltage**:

```
v = Vm sin(ωt)
```

Where:
- `v` = Instantaneous voltage at time t
- `Vm` = Peak voltage (maximum value of voltage)
- `ω` = Angular frequency = 2πf (rad/s)
- `f` = Frequency (Hz)
- `t` = Time (seconds)

Similarly, AC current:
```
i = Im sin(ωt + φ)
```
Where:
- `Im` = Peak current
- `φ` = Phase difference between voltage and current

### 3.2 Important Terms

| Term | Symbol | Formula | Meaning |
|---|---|---|---|
| Time Period | T | T = 1/f | Time for one complete cycle |
| Frequency | f | f = 1/T | Number of cycles per second |
| Angular Frequency | ω | ω = 2πf | Rate of change of phase angle |
| Phase | φ | — | Position in a cycle |

**Relationship between T, f, and ω:**
```
ω = 2πf = 2π/T
```

For India's power supply:
- f = 50 Hz
- T = 1/50 = 0.02 s
- ω = 2π × 50 = 100π rad/s

---

## 4. Peak Value, RMS Value, and Average Value

### 4.1 Peak Value (Vm or Im)

The **maximum value** of voltage or current in one cycle.
- Also called **amplitude**.
- The AC voltage from socket is given as 220V — this is the **RMS value**, NOT peak.

### 4.2 RMS Value (Root Mean Square) ⭐⭐ (Very Important — Board Exam)

**Definition:** *"The RMS value of AC is that value of steady DC which would produce the same heating effect in a given resistance in the same time."*

```
Vrms = Vm / √2 = 0.707 × Vm

Irms = Im / √2 = 0.707 × Im
```

**Derivation of RMS value:**

For v = Vm sinωt:
```
Mean of v² over one full cycle:
<v²> = Vm²/2        [since mean of sin²ωt = 1/2]

Vrms = √<v²> = Vm/√2
```

**Important:**
- Household supply 220V means **Vrms = 220V**
- Peak voltage: Vm = 220 × √2 ≈ 311 V

### 4.3 Average Value

**Definition:** Mean of AC over one **half cycle** (over full cycle, average = 0 because positive and negative halves cancel).

```
Vavg = (2/π) × Vm ≈ 0.637 × Vm

Iavg = (2/π) × Im ≈ 0.637 × Im
```

> 📝 **Note:** For full cycle, average of sinusoidal AC = 0. So average is always taken over half cycle.

### 4.4 Summary Table

| Quantity | Formula | Approximate Value |
|---|---|---|
| Peak Value | Vm | — |
| RMS Value | Vm/√2 | 0.707 Vm |
| Average Value (half cycle) | 2Vm/π | 0.637 Vm |

> 💡 **Memory Trick:** RMS = **R**eal **M**easured **S**ize. It's the one that matters for power calculations and is the value written on every appliance.

---

## 5. AC Voltage Applied to a Resistor

### 5.1 Circuit and Analysis ⭐

**Setup:** A resistor R is connected to an AC voltage source v = Vm sinωt.

By Ohm's Law:
```
i = v/R = (Vm sinωt)/R = Im sinωt
```
Where Im = Vm/R (peak current)

### 5.2 Phase Relationship

- In a purely resistive circuit, **voltage and current are IN PHASE** (φ = 0).
- Both v and i reach their maximum, minimum, and zero values at the same instant.

```
v = Vm sinωt
i = Im sinωt      [φ = 0, in phase]
```

### 5.3 Phasor Diagram

In a **phasor diagram**, voltage and current phasors point in the **same direction** (for pure resistor).

```
      ↑ Vm
      |
      |  (V and I overlap — in phase)
      |
      ↑ Im
```

### 5.4 Power Consumed

```
P = Vrms × Irms = (Vm/√2)(Im/√2) = VmIm/2
```
Or:
```
P = Irms² × R
```

**Power factor** = cos φ = cos 0° = **1** (maximum power is consumed in pure resistor)

---

## 6. AC Voltage Applied to an Inductor

### 6.1 Inductive Reactance ⭐⭐ (Board Exam Important)

**Definition:** *"The opposition offered by an inductor to the flow of AC is called Inductive Reactance."*

```
XL = ωL = 2πfL
```

Where:
- `XL` = Inductive Reactance (measured in Ohm, Ω)
- `ω` = Angular frequency (rad/s)
- `L` = Inductance (Henry, H)
- `f` = Frequency (Hz)

**Key Points:**
- XL increases as frequency increases. **High frequency → High XL → Less current.**
- For DC (f = 0): XL = 0. Inductor offers **NO opposition to DC**.
- Unit of XL = Ohm (Ω)

### 6.2 Phase Relationship ⭐

For a pure inductor with v = Vm sinωt:
```
i = Im sin(ωt − π/2)
```

**Current LAGS voltage by 90° (π/2).**

> 💡 **Memory Trick:** "**ELI** the **ICE** man" — In **L** (inductor), **E** leads **I** (i.e., voltage leads current). In **C** (capacitor), **I** leads **E** (current leads voltage).

### 6.3 Peak Current

```
Im = Vm / XL = Vm / ωL
```

### 6.4 Power Consumed

For pure inductor, φ = 90°:
```
P = Vrms × Irms × cos90° = 0
```
**No power is consumed in a pure inductor!** The inductor stores energy in the magnetic field during one half cycle and returns it in the next half cycle.

---

## 7. AC Voltage Applied to a Capacitor

### 7.1 Capacitive Reactance ⭐⭐ (Board Exam Important)

**Definition:** *"The opposition offered by a capacitor to the flow of AC is called Capacitive Reactance."*

```
XC = 1/ωC = 1/(2πfC)
```

Where:
- `XC` = Capacitive Reactance (Ohm, Ω)
- `ω` = Angular frequency (rad/s)
- `C` = Capacitance (Farad, F)
- `f` = Frequency (Hz)

**Key Points:**
- XC decreases as frequency increases. **High frequency → Low XC → More current.**
- For DC (f = 0): XC = ∞. Capacitor **blocks DC completely**.
- For high frequency AC: XC → 0. Capacitor easily allows high frequency AC.
- Unit of XC = Ohm (Ω)

### 7.2 Phase Relationship ⭐

For a pure capacitor with v = Vm sinωt:
```
i = Im sin(ωt + π/2)
```

**Current LEADS voltage by 90° (π/2).**

### 7.3 Peak Current

```
Im = Vm / XC = Vm × ωC
```

### 7.4 Power Consumed

For pure capacitor, φ = 90°:
```
P = Vrms × Irms × cos90° = 0
```
**No power is consumed in a pure capacitor!** Capacitor stores energy in the electric field during one half cycle and returns it in the next half cycle.

### 7.5 Quick Comparison: R, L, C in AC

| Property | Resistor (R) | Inductor (L) | Capacitor (C) |
|---|---|---|---|
| Opposition | R | XL = ωL | XC = 1/ωC |
| Phase (I vs V) | In phase (φ=0) | I lags V by 90° | I leads V by 90° |
| Power consumed | P = Irms²R | Zero | Zero |
| Effect of ↑ frequency | No change | XL increases | XC decreases |
| DC behavior | Allows DC | Allows DC | Blocks DC |

---

## 8. AC Voltage Applied to Series LCR Circuit

### 8.1 Setup

An inductor L, capacitor C, and resistor R are connected in **series** with an AC source v = Vm sinωt.

### 8.2 Impedance ⭐⭐⭐ (Most Important — 5 Mark Derivation)

**Definition:** *"Impedance is the total effective opposition offered by a series LCR circuit to the flow of AC."*

```
Z = √[R² + (XL − XC)²]
```

Where:
- `Z` = Impedance (Ohm, Ω)
- `R` = Resistance
- `XL` = Inductive Reactance = ωL
- `XC` = Capacitive Reactance = 1/ωC

**Think of it as:** Z is like the "total resistance" of the LCR circuit.

### 8.3 Derivation of Impedance (Phasor Method) ⭐⭐⭐

**Given:** v = Vm sinωt applied to series R, L, C.

**Step 1 — Voltage across each element:**
- Voltage across R: VR = IR (in phase with I)
- Voltage across L: VL = IXL (leads I by 90°)
- Voltage across C: VC = IXC (lags I by 90°)

**Step 2 — Phasor Addition:**
Since VL and VC are opposite (one leads by 90°, other lags by 90°), they partially cancel.

```
Net reactive voltage = VL − VC = I(XL − XC)
```

**Step 3 — Total Voltage:**
The total voltage V and resistive voltage VR are not in the same direction. They add by Pythagoras:

```
V² = VR² + (VL − VC)²
   = (IR)² + (IXL − IXC)²
   = I²[R² + (XL − XC)²]
```

Therefore:
```
V = I × √[R² + (XL − XC)²] = I × Z
```

So:
```
Z = √[R² + (XL − XC)²]
```

**Step 4 — Phase Angle:**
```
tan φ = (XL − XC) / R
```

Where φ = phase difference between applied voltage and current.

### 8.4 Three Cases

| Condition | Nature | Phase |
|---|---|---|
| XL > XC | Inductive (circuit behaves like L) | V leads I (I lags V) |
| XL < XC | Capacitive (circuit behaves like C) | I leads V |
| XL = XC | Purely Resistive (Resonance!) | V and I in phase, Z = R (minimum) |

### 8.5 Peak Current

```
Im = Vm / Z = Vm / √[R² + (XL − XC)²]
```

---

## 9. Resonance in LCR Circuit

### 9.1 Definition ⭐⭐ (Board Exam Favourite)

**Definition:** *"Resonance in a series LCR circuit occurs when the inductive reactance equals the capacitive reactance, i.e., XL = XC. At resonance, impedance is minimum and current is maximum."*

### 9.2 Resonant Frequency ⭐⭐

At resonance: XL = XC
```
ωL = 1/ωC
ω² = 1/LC
ω₀ = 1/√(LC)
```

**Resonant frequency:**
```
f₀ = 1 / (2π√LC)
```

Where:
- `f₀` = Resonant frequency (Hz)
- `L` = Inductance (H)
- `C` = Capacitance (F)

### 9.3 At Resonance

- XL = XC
- Z = R (minimum impedance — only resistance remains)
- Current I = Vm/R (**maximum current**)
- Phase angle φ = 0 (voltage and current are in phase)
- Power factor = 1 (maximum power delivered)

### 9.4 Sharpness of Resonance — Quality Factor (Q Factor) ⭐

**Definition:** *"The Q factor (Quality Factor) is a measure of sharpness of resonance. It tells how sharp or flat the resonance peak is."*

```
Q = ω₀L / R = 1/(ω₀CR) = (1/R)√(L/C)
```

**Key Points:**
- **High Q** → Sharp resonance peak → Narrow bandwidth → Highly selective circuit.
- **Low Q** → Flat resonance peak → Wide bandwidth → Less selective.
- Q factor is important in **radio tuning circuits** (selects one station out of many).

### 9.5 Bandwidth

```
Bandwidth = Δω = R/L = ω₀/Q
```

The frequency range over which current is at least 1/√2 times its maximum value.

> 📝 **Real Life Application:** When you tune a radio to a specific station, you are adjusting C in an LC circuit to achieve **resonance** at the frequency of that station!

---

## 10. Power in AC Circuit

### 10.1 Instantaneous Power

For v = Vm sinωt and i = Im sin(ωt − φ):
```
p = vi = VmIm sinωt × sin(ωt − φ)
```

### 10.2 Average Power ⭐⭐ (Board Exam — Very Important)

```
P = Vrms × Irms × cosφ
```

Where:
- `P` = Average (true) power (Watt, W)
- `Vrms` = RMS voltage
- `Irms` = RMS current
- `cosφ` = **Power Factor**

### 10.3 Power Factor ⭐⭐

**Definition:** *"Power factor is the cosine of the phase angle between voltage and current in an AC circuit."*

```
Power Factor = cosφ = R/Z
```

| Circuit | φ | cosφ | Power |
|---|---|---|---|
| Pure Resistor | 0° | 1 | Maximum (P = VrmsIrms) |
| Pure Inductor | 90° | 0 | Zero |
| Pure Capacitor | 90° | 0 | Zero |
| Series LCR | 0° to 90° | 0 to 1 | Partial |
| LCR at Resonance | 0° | 1 | Maximum |

### 10.4 Wattless Current

- The component of current that does **NOT** contribute to power is called **wattless current** or **idle current**.
- Wattless current = Irms sinφ
- It exists in pure L and pure C circuits where φ = 90°.

### 10.5 Apparent Power, True Power, Reactive Power

| Type | Formula | Unit | Meaning |
|---|---|---|---|
| True (Active) Power | P = VrmsIrms cosφ | Watt (W) | Actual power consumed |
| Apparent Power | S = VrmsIrms | Volt-Ampere (VA) | Total power supplied |
| Reactive Power | Q = VrmsIrms sinφ | VAR | Power stored/returned by L or C |

Relationship:
```
S² = P² + Q²
```

---

## 11. LC Oscillations

### 11.1 What are LC Oscillations? ⭐

When a charged capacitor is connected to an inductor, the energy oscillates back and forth between the electric field of the capacitor and the magnetic field of the inductor.

These are called **LC oscillations** (or electromagnetic oscillations).

### 11.2 Analogy with Spring-Mass System

| LC Circuit | Spring-Mass System |
|---|---|
| Charge q | Displacement x |
| Current i | Velocity v |
| Inductance L | Mass m |
| 1/C | Spring constant k |
| Electrical energy | Kinetic energy |
| Magnetic energy | Potential energy |

### 11.3 Frequency of LC Oscillations

```
ω = 1/√(LC)

f = 1 / (2π√LC)
```

This is the **same as the resonant frequency** of LCR circuit.

### 11.4 Energy in LC Oscillations

Total energy is conserved (assuming no resistance):
```
U = q²/2C + Li²/2 = constant
```

- When capacitor is fully charged: All energy = q²/2C (electrical), i = 0
- When capacitor is fully discharged: All energy = Li²/2 (magnetic), q = 0

> 📝 **Board Exam Note:** LC oscillations are like a pendulum — energy keeps converting from one form to another without loss (in ideal case).

---

## 12. Transformers

### 12.1 Definition ⭐⭐⭐ (Must Know — 5 Mark Question)

**Definition:** *"A transformer is a device that converts high voltage low current AC into low voltage high current AC or vice versa, based on the principle of mutual electromagnetic induction."*

### 12.2 Principle

A transformer works on **Faraday's Law of Electromagnetic Induction**.

When AC flows in the primary coil, it creates a changing magnetic flux. This changing flux links with the secondary coil and induces an EMF in it.

### 12.3 Construction

A transformer consists of:
1. **Primary Coil (Np turns):** Connected to the AC input.
2. **Secondary Coil (Ns turns):** From which output is taken.
3. **Soft Iron Core:** Links the magnetic flux between the two coils.

```
   Primary (Np)         Secondary (Ns)
   ||||||||||||   CORE   ||||||||||||
   ||||||||||||   ~~~~   ||||||||||||
      ↑ Input                ↑ Output
      Vp, Ip                 Vs, Is
```

### 12.4 Transformer Equation ⭐⭐⭐ (Board Exam Most Important)

**Voltage Ratio:**
```
Vs / Vp = Ns / Np
```

**Current Ratio (for ideal transformer):**
```
Is / Ip = Np / Ns
```

**Power (ideal transformer):**
```
Vp × Ip = Vs × Is         [Input power = Output power]
```

Where:
- `Vp` = Primary voltage, `Vs` = Secondary voltage
- `Ip` = Primary current, `Is` = Secondary current
- `Np` = Primary turns, `Ns` = Secondary turns

### 12.5 Turns Ratio (Transformation Ratio)

```
n = Ns / Np = Vs / Vp = Ip / Is
```

### 12.6 Types of Transformers ⭐

| Type | Condition | Effect |
|---|---|---|
| **Step-Up Transformer** | Ns > Np | Vs > Vp (voltage increases, current decreases) |
| **Step-Down Transformer** | Ns < Np | Vs < Vp (voltage decreases, current increases) |

**Real-life example:**
- **Step-Up:** Power station generates at ~11kV → stepped up to 220kV for long-distance transmission.
- **Step-Down:** At your locality, 220kV → stepped down to 220V for home use.

### 12.7 Efficiency of Transformer

```
η = (Output Power / Input Power) × 100%
η = (Vs × Is) / (Vp × Ip) × 100%
```

For an **ideal transformer**, η = 100%. Real transformers have η = 95% to 99%.

### 12.8 Energy Losses in a Transformer ⭐ (Board Exam — 3 Mark)

| Loss | Cause | How to Reduce |
|---|---|---|
| **Copper Loss (I²R loss)** | Current flowing in resistance of coils generates heat | Use thick copper wire (low resistance) |
| **Iron/Eddy Current Loss** | Changing flux induces currents in the iron core, generating heat | Use laminated core (thin sheets insulated from each other) |
| **Hysteresis Loss** | Energy lost in magnetizing and demagnetizing the iron core repeatedly | Use soft iron core (low hysteresis) |
| **Flux Leakage** | Not all flux from primary links with secondary | Use tightly wound coils on same limb |

> 📝 **Board Exam Note:** Laminated core reduces **eddy current losses**. This is a very commonly asked 1-mark question.

### 12.9 Uses of Transformer

- Long-distance power transmission (step-up at power station, step-down at destination).
- Mobile phone chargers (step-down).
- Welding machines (step-down, high current).
- Radio, television circuits.
- Inverters and UPS.

---

## 13. Important Formulas Summary

| Formula | Quantity | SI Unit |
|---|---|---|
| v = Vm sinωt | Instantaneous AC voltage | Volt (V) |
| Vrms = Vm/√2 | RMS voltage | V |
| Vavg = 2Vm/π | Average voltage (half cycle) | V |
| XL = ωL = 2πfL | Inductive reactance | Ohm (Ω) |
| XC = 1/ωC = 1/2πfC | Capacitive reactance | Ω |
| Z = √[R² + (XL−XC)²] | Impedance | Ω |
| tan φ = (XL−XC)/R | Phase angle | — |
| f₀ = 1/2π√(LC) | Resonant frequency | Hz |
| P = VrmsIrms cosφ | Average power | Watt (W) |
| cosφ = R/Z | Power factor | — |
| Q = ω₀L/R | Quality factor | — |
| Vs/Vp = Ns/Np | Transformer equation | — |
| η = (VsIs/VpIp)×100 | Transformer efficiency | % |

---

## 14. Board Exam Questions with Answers

### 📝 1-Mark / Very Short Answer Questions

**Q1. What is the frequency of AC supply in India?**
**Ans:** 50 Hz

**Q2. What is the RMS value of AC voltage if peak voltage is 311 V?**
**Ans:** Vrms = Vm/√2 = 311/1.414 ≈ 220 V

**Q3. Define inductive reactance.**
**Ans:** Inductive reactance is the opposition offered by an inductor to the flow of AC. XL = ωL = 2πfL. Its unit is Ohm.

**Q4. What is the power factor of a pure inductor?**
**Ans:** Zero (cosφ = cos90° = 0)

**Q5. At what frequency does a capacitor offer infinite resistance?**
**Ans:** At zero frequency (DC), XC = 1/ωC → ∞. So capacitor blocks DC completely.

**Q6. State the condition for resonance in LCR series circuit.**
**Ans:** XL = XC, i.e., ωL = 1/ωC. At this condition, impedance Z is minimum and equal to R.

**Q7. What is the power factor of a circuit at resonance?**
**Ans:** Power factor = cosφ = cos0° = 1 (unity)

**Q8. Why is the core of a transformer laminated?**
**Ans:** To reduce eddy current losses (iron losses) in the core.

**Q9. State the principle of a transformer.**
**Ans:** A transformer works on the principle of mutual electromagnetic induction (Faraday's Law).

**Q10. What is wattless current?**
**Ans:** The component of AC current that does not contribute to the power consumption is called wattless current. It equals Irms sinφ.

**Q11. Define Quality factor (Q factor) of LCR circuit.**
**Ans:** Q factor measures the sharpness of resonance. Q = ω₀L/R. Higher Q means sharper resonance.

**Q12. A step-up transformer has Np = 200 and Ns = 1000. What is the turns ratio?**
**Ans:** n = Ns/Np = 1000/200 = 5. It is a step-up transformer.

---

### 📝 2-Mark Questions

**Q13. Derive the expression for RMS value of AC.**

**Ans:**
For v = Vm sinωt, instantaneous power in R:
```
p = v²/R = Vm² sin²ωt / R
```
Mean value of v²:
```
<v²> = Vm² × <sin²ωt> = Vm²/2        [since <sin²ωt> = 1/2]
```
RMS value:
```
Vrms = √<v²> = Vm/√2 ≈ 0.707 Vm
```

---

**Q14. What is capacitive reactance? How does it vary with frequency?**

**Ans:**
The opposition offered by a capacitor to AC is called capacitive reactance.
```
XC = 1/ωC = 1/2πfC
```
- As frequency (f) increases, XC decreases. (Inversely proportional to f)
- For DC (f = 0): XC → ∞ (blocks DC)
- For very high frequency: XC → 0 (passes easily)

---

**Q15. Write two differences between a step-up and step-down transformer.**

**Ans:**

| Step-Up Transformer | Step-Down Transformer |
|---|---|
| Ns > Np | Ns < Np |
| Output voltage > Input voltage | Output voltage < Input voltage |
| Output current < Input current | Output current > Input current |
| Used at power stations | Used at distribution points |

---

**Q16. What is power factor? Write its value for purely inductive and purely capacitive circuit.**

**Ans:**
Power factor = cosφ = R/Z

It is the cosine of phase angle between voltage and current.

- Pure inductor: φ = 90°, cosφ = cos90° = **0**
- Pure capacitor: φ = 90°, cosφ = cos90° = **0**
- Pure resistor: φ = 0°, cosφ = cos0° = **1**

---

**Q17. What are eddy currents? How are they minimized in a transformer?**

**Ans:**
When a conductor is placed in a changing magnetic field, currents are induced in the body of the conductor itself. These are called **eddy currents** (or Foucault currents). They cause energy loss as heat.

In a transformer, eddy currents are minimized by using a **laminated iron core** — the core is made of thin sheets of iron, each insulated from the other. This breaks the path of eddy currents and reduces them greatly.

---

### 📝 3-Mark Questions

**Q18. Derive the expression for impedance of a series LCR circuit.**

**Ans:** *(See Section 8.3 — write full derivation with phasor diagram)*

Final Answer:
```
Z = √[R² + (XL − XC)²]
tan φ = (XL − XC)/R
```

---

**Q19. What is resonance in LCR circuit? Derive the expression for resonant frequency.**

**Ans:**

**Resonance** is the condition when XL = XC in an LCR series circuit, making impedance minimum and current maximum.

**Derivation:**
At resonance, XL = XC:
```
ωL = 1/ωC
ω² = 1/LC
ω₀ = 1/√(LC)
```

Resonant frequency:
```
f₀ = ω₀/2π = 1/(2π√LC)
```

At resonance:
- Z = R (minimum)
- I = Vm/R (maximum)
- Phase angle φ = 0°
- Power factor = 1

---

**Q20. Explain the energy losses in a transformer.**

**Ans:** *(See Section 12.8 — write all 4 losses with causes and remedies)*

---

**Q21. A series LCR circuit has R = 10Ω, L = 0.5 H, C = 100 μF. Find (i) resonant frequency (ii) impedance at resonance (iii) Q factor.**

**Ans:**
```
Given: R = 10Ω, L = 0.5H, C = 100×10⁻⁶ F

(i) f₀ = 1/(2π√LC)
       = 1/(2π√(0.5 × 100×10⁻⁶))
       = 1/(2π√(5×10⁻⁵))
       = 1/(2π × 7.07×10⁻³)
       = 1/0.04443 ≈ 22.5 Hz

(ii) At resonance: Z = R = 10 Ω

(iii) ω₀ = 2πf₀ = 2π × 22.5 = 141.4 rad/s
     Q = ω₀L/R = 141.4 × 0.5 / 10 = 7.07
```

---

### 📝 5-Mark Questions (Long Answer)

**Q22. With the help of a phasor diagram, derive the expression for impedance of a series LCR circuit. Also find the condition for resonance.**

**Ans:** *(See Sections 8.3 and 9.2 — write full derivation with phasor diagram)*

---

**Q23. What is a transformer? Describe its principle, construction, and working. Derive the transformer equation.**

**Ans:** *(See Section 12 — write complete theory, transformer equation derivation, types, and losses)*

---

**Q24. (a) In a series LCR circuit, find the expression for average power consumed.**
**(b) What do you mean by power factor? When is it zero and when is it one?**

**Ans:**

**(a) Average Power:**

For v = Vm sinωt and i = Im sin(ωt − φ):
```
P = <vi> = <Vm sinωt × Im sin(ωt − φ)>
  = VmIm/2 × cosφ
  = (Vm/√2)(Im/√2) cosφ
  = Vrms × Irms × cosφ
```

**(b) Power Factor:**
```
cosφ = R/Z
```
- cosφ = 0 when φ = 90° → Pure inductor or pure capacitor (no power consumed)
- cosφ = 1 when φ = 0° → Pure resistor or LCR at resonance (maximum power consumed)

---

### 📝 Numerical Problems (Board Pattern)

**Num 1:** Calculate the impedance of a series LCR circuit with R = 5Ω, XL = 10Ω, XC = 6Ω.

**Solution:**
```
Z = √[R² + (XL − XC)²]
  = √[5² + (10 − 6)²]
  = √[25 + 16]
  = √41 ≈ 6.4 Ω

Phase angle: tan φ = (XL − XC)/R = 4/5 = 0.8
φ = tan⁻¹(0.8) ≈ 38.7°
```
**Answer: Z ≈ 6.4 Ω**

---

**Num 2:** An AC voltage V = 200 sin(314t) is applied to a 10Ω resistor. Find (i) peak current (ii) RMS current.

**Solution:**
```
From v = Vm sinωt: Vm = 200V, ω = 314 rad/s

(i) Im = Vm/R = 200/10 = 20 A

(ii) Irms = Im/√2 = 20/√2 = 14.14 A
```
**Answer: Im = 20 A, Irms = 14.14 A**

---

**Num 3:** A capacitor of 100 μF is connected to AC source of frequency 50 Hz. Find capacitive reactance.

**Solution:**
```
XC = 1/(2πfC)
   = 1/(2π × 50 × 100×10⁻⁶)
   = 1/(2π × 50 × 10⁻⁴)
   = 1/(0.03141)
   = 31.85 Ω ≈ 31.9 Ω
```
**Answer: XC ≈ 31.9 Ω**

---

**Num 4:** An inductor of 0.5 H is connected to AC of frequency 50 Hz. Find inductive reactance.

**Solution:**
```
XL = 2πfL
   = 2π × 50 × 0.5
   = 2π × 25
   = 157 Ω
```
**Answer: XL = 157 Ω**

---

**Num 5:** A transformer has 500 primary turns and 2500 secondary turns. If primary voltage is 220V, find secondary voltage. (Assume ideal transformer)

**Solution:**
```
Vs/Vp = Ns/Np
Vs/220 = 2500/500 = 5
Vs = 220 × 5 = 1100 V
```
**Answer: Vs = 1100 V (Step-Up Transformer)**

---

**Num 6:** The primary coil of a transformer has 200 turns and secondary has 50 turns. If primary voltage is 400V and primary current is 0.5A, find (i) secondary voltage (ii) secondary current (iii) power.

**Solution:**
```
(i) Vs = Vp × (Ns/Np) = 400 × (50/200) = 400 × 0.25 = 100 V

(ii) Is = Ip × (Np/Ns) = 0.5 × (200/50) = 0.5 × 4 = 2 A

(iii) Power = Vp × Ip = 400 × 0.5 = 200 W
     (Also: Vs × Is = 100 × 2 = 200 W ✓)
```
**Answer: Vs = 100 V, Is = 2 A, P = 200 W (Step-Down Transformer)**

---

**Num 7:** Find the resonant frequency of an LCR circuit with L = 1 mH and C = 0.1 μF.

**Solution:**
```
L = 1×10⁻³ H, C = 0.1×10⁻⁶ F

f₀ = 1/(2π√LC)
   = 1/(2π√(10⁻³ × 10⁻⁷))
   = 1/(2π√(10⁻¹⁰))
   = 1/(2π × 10⁻⁵)
   = 10⁵/(2π)
   ≈ 15.9 kHz
```
**Answer: f₀ ≈ 15.9 kHz**

---

**Num 8:** An AC circuit has R = 6Ω, XL = 10Ω, XC = 2Ω. Find power factor.

**Solution:**
```
Z = √[R² + (XL − XC)²]
  = √[36 + (10−2)²]
  = √[36 + 64]
  = √100 = 10 Ω

Power factor = cosφ = R/Z = 6/10 = 0.6
```
**Answer: Power factor = 0.6**

---

## 15. Objective / MCQ Questions

**Q1.** The RMS value of AC voltage is related to peak voltage by:
- (a) Vrms = 2Vm
- **(b) Vrms = Vm/√2** ✓
- (c) Vrms = Vm/2
- (d) Vrms = √2 Vm

---

**Q2.** Inductive reactance XL depends on frequency as:
- **(a) XL ∝ f** ✓
- (b) XL ∝ 1/f
- (c) XL ∝ f²
- (d) XL is independent of f

---

**Q3.** In a purely capacitive circuit, current:
- (a) Lags voltage by 90°
- **(b) Leads voltage by 90°** ✓
- (c) Is in phase with voltage
- (d) Lags voltage by 45°

---

**Q4.** At resonance in a series LCR circuit, the impedance is:
- (a) Maximum
- (b) Zero
- **(c) Equal to R** ✓
- (d) Equal to XL

---

**Q5.** The resonant frequency of an LCR circuit is:
- (a) f₀ = 2π√(LC)
- (b) f₀ = 1/2π(LC)
- **(c) f₀ = 1/2π√(LC)** ✓
- (d) f₀ = 2π/√(LC)

---

**Q6.** The power factor of a pure inductor is:
- (a) 1
- (b) 0.5
- **(c) 0** ✓
- (d) ∞

---

**Q7.** In a step-up transformer, the secondary coil has:
- **(a) More turns than primary** ✓
- (b) Fewer turns than primary
- (c) Same turns as primary
- (d) No turns

---

**Q8.** Eddy current losses in a transformer are reduced by:
- (a) Using thick iron core
- **(b) Using laminated iron core** ✓
- (c) Using copper core
- (d) Increasing the number of turns

---

**Q9.** The unit of impedance is:
- (a) Henry
- (b) Farad
- **(c) Ohm** ✓
- (d) Volt

---

**Q10.** Power consumed by a pure capacitor is:
- **(a) Zero** ✓
- (b) Maximum
- (c) VrmsIrms
- (d) VrmsIrms/2

---

**Q11.** The peak value of household AC supply (220V RMS) is approximately:
- (a) 220 V
- (b) 200 V
- **(c) 311 V** ✓
- (d) 440 V

---

**Q12.** A transformer is used to change:
- (a) DC to AC
- (b) AC to DC
- **(c) Voltage level of AC** ✓
- (d) Frequency of AC

---

**Q13.** In a series LCR circuit at resonance, the voltage across L and C are:
- (a) Both zero
- (b) Both equal to supply voltage
- **(c) Equal in magnitude but opposite in phase** ✓
- (d) Equal in magnitude and same phase

---

**Q14.** The Q factor of a resonant circuit is a measure of:
- (a) Power consumed
- **(b) Sharpness of resonance** ✓
- (c) Impedance at resonance
- (d) Current at resonance

---

**Q15.** If frequency of AC is doubled, inductive reactance becomes:
- **(a) Double** ✓
- (b) Half
- (c) Four times
- (d) Unchanged

---

**Q16.** In the ELI the ICE man rule, in a capacitor (C):
- **(a) I leads E** ✓
- (b) E leads I
- (c) I and E are in phase
- (d) None of the above

---

**Q17.** Average power in an AC circuit depends on:
- (a) Only Vrms
- (b) Only Irms
- **(c) Both Vrms, Irms and cosφ** ✓
- (d) Only phase angle

---

**Q18.** For a transformer with η = 80%, Vp = 200V, Ip = 4A, Vs = 400V. Find Is.
- (a) 2 A
- (b) 1.6 A
- **(c) 1.6 A** ✓
- (d) 4 A

*(Solution: Output power = η × Input power = 0.8 × 200 × 4 = 640 W; Is = 640/400 = 1.6 A)*

---

## 16. Quick Revision Tips

### ⭐ Most Important Topics for Bihar Board Exam

| Priority | Topic | Marks (Expected) |
|---|---|---|
| ⭐⭐⭐ | Transformer (working + equation + losses) | 5 marks |
| ⭐⭐⭐ | LCR Series Circuit + Impedance derivation | 5 marks |
| ⭐⭐⭐ | Resonance in LCR (resonant frequency) | 3-5 marks |
| ⭐⭐⭐ | Power in AC + Power Factor | 3 marks |
| ⭐⭐ | RMS and Peak Values | 2 marks |
| ⭐⭐ | Inductive and Capacitive Reactance | 2 marks |
| ⭐⭐ | Phase relationships (R, L, C circuits) | 2 marks |
| ⭐ | LC Oscillations | 2 marks |
| ⭐ | Numericals | 2-3 marks |
| ⭐ | MCQs | 1 mark each |

---

### 📌 Things to Memorize (Flash Cards)

```
Vrms = Vm/√2 ≈ 0.707 Vm
Irms = Im/√2 ≈ 0.707 Im
Vavg = 2Vm/π ≈ 0.637 Vm

XL = ωL = 2πfL          [increases with f]
XC = 1/ωC = 1/2πfC      [decreases with f]

Impedance:      Z = √[R² + (XL−XC)²]
Phase angle:    tan φ = (XL−XC)/R
Power factor:   cosφ = R/Z

Resonant freq:  f₀ = 1/2π√(LC)
Q factor:       Q = ω₀L/R

Average Power:  P = VrmsIrms cosφ

Transformer:    Vs/Vp = Ns/Np = Ip/Is
Efficiency:     η = (VsIs/VpIp) × 100%
```

---

### 🔑 Key Differences to Remember

| | Pure R | Pure L | Pure C |
|---|---|---|---|
| Opposition | R | XL = ωL | XC = 1/ωC |
| Phase | In phase | V leads I by 90° | I leads V by 90° |
| Power | VrmsIrms | Zero | Zero |
| Power Factor | 1 | 0 | 0 |

| | Step-Up | Step-Down |
|---|---|---|
| Ns vs Np | Ns > Np | Ns < Np |
| Voltage | Vs > Vp | Vs < Vp |
| Current | Is < Ip | Is > Ip |
| Where used | Power station output | Near homes |

---

### 📅 Day-Before Exam Quick Revision Checklist

- [ ] Learn AC representation: v = Vm sinωt
- [ ] Memorize: Vrms = Vm/√2, Vavg = 2Vm/π
- [ ] Learn XL = ωL (increases with f) and XC = 1/ωC (decreases with f)
- [ ] Practice Impedance derivation (write it 2 times)
- [ ] Learn resonant frequency formula: f₀ = 1/2π√(LC)
- [ ] Learn average power formula: P = VrmsIrms cosφ
- [ ] Learn transformer equation: Vs/Vp = Ns/Np
- [ ] Memorize 4 energy losses in transformer
- [ ] Solve all 8 numerical problems
- [ ] Revise all MCQs in Section 15
- [ ] Remember ELI the ICE man rule

---

### 💡 Common Mistakes to Avoid

1. **Don't confuse Vrms with Vm.** Household 220V is RMS, NOT peak. Peak = 220√2 ≈ 311V.
2. **XL and XC are NOT the same as R.** They are frequency-dependent. R is constant.
3. **Phase rule:** In inductor, V leads I (or I lags V) by 90°. In capacitor, I leads V by 90°. Many students get this reversed.
4. **Transformer doesn't work on DC.** It needs changing current (AC) to produce changing flux.
5. **Power in pure L or C = 0.** Don't write P = VrmsIrms for inductors or capacitors.
6. **Resonance condition:** XL = XC, NOT XL = R or XC = R.
7. **Transformer equation:** Vs/Vp = Ns/Np, but Is/Ip = Np/Ns (note: current ratio is INVERTED compared to voltage ratio).
8. **Laminated core reduces eddy current losses,** NOT hysteresis losses. (Common confusion!)

---

### 🔗 Connection to Previous Chapters

- This chapter directly uses concepts from **Chapter 6 (Electromagnetic Induction)** — Faraday's Law for transformer, mutual inductance.
- Capacitance from **Chapter 2 (Electrostatic Potential and Capacitance)**.
- Inductance introduced in **Chapter 6**.

---

*Prepared for Bihar Board Class 12 Physics | Chapter 7: Alternating Current | Based on NCERT Textbook*