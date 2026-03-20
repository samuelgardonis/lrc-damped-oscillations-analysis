# Analytical Characterisation of Damped Oscillations and Parasitic Resistance in a Series LRC Circuit

## Objective
To investigate the transient response of a series L–R–C circuit and determine the damping constant as a function of resistance, along with estimating the inductance and parasitic resistance of the inductor.

---

## Background & Theory

A series L–R–C circuit exhibits oscillatory behavior analogous to a damped mechanical oscillator. Energy alternates between:
- Electric field (capacitor)
- Magnetic field (inductor)

In the presence of resistance, energy dissipates via Joule heating, leading to damped oscillations.

The governing differential equation:

d²q/dt² + (R/L)(dq/dt) + q/LC = 0

For an underdamped system:

α = R / 2L

Logarithmic decrement:

δ = ln(A₁ / A₂)

Damping constant:

α = δ / T

---

## Experimental Setup

- Inductor (L)
- Capacitor (C)
- Variable resistor (R)
- Function generator (square wave input)
- Digital Storage Oscilloscope (DSO)

The voltage across the capacitor was monitored to observe oscillations.

---

## Methodology

1. Construct a series LCR circuit  
2. Apply a square-wave signal  
3. Observe damped oscillations on the oscilloscope  
4. Record successive peak amplitudes (A₁, A₂) and time period (T)  
5. Calculate logarithmic decrement (δ) and damping constant (α)  
6. Repeat for different resistance values  

---

## Observations

| R (Ω) | A₁ (V) | A₂ (V) | T (μs) | δ | α (s⁻¹) | Q |
|------|--------|--------|--------|----|---------|----|
| 0    | 7.84   | 7.36   | 280    | 0.063 | 225.0 | ∞ |
| 50   | 12.70  | 7.52   | 540    | 0.524 | 970.4 | 6.0 |
| 100  | 9.84   | 5.52   | 536    | 0.578 | 1078.5 | 5.43 |
| 400  | 12.20  | 2.20   | 544    | 1.713 | 3148.9 | 1.83 |
| 500  | 10.40  | 1.30   | 545    | 2.079 | 3814.7 | 1.51 |
| 600  | 9.60   | 0.85   | 548    | 2.424 | 4423.4 | 1.30 |

---

## Graph Analysis

A plot of damping constant (α) vs resistance (R) shows a linear relationship:

α = (R_ext + R_L) / (2L)

Slope (m): 6.46 × 10⁻³  
Intercept (c): 548.2  

---

## Results

Inductance:
L ≈ 77.4 mH  

Parasitic Resistance:
R_L ≈ 84.9 Ω  

---

## Key Inferences

- Damping increases linearly with resistance  
- Non-zero intercept confirms internal resistance in the inductor  
- Quality factor decreases as resistance increases  

---

## Applications

- RF filter design  
- Automotive ignition systems  
- Sensor calibration  

---

## Error Analysis

- Capacitor tolerance (±10%)  
- Skin effect in inductor  
- Oscilloscope measurement uncertainty (~1–2%)  

---

## Author

Samuel Gardonis  
B.Sc. Physics, St. Xavier’s College, Mumbai
