

# 📒 Op-Amp Applications – Notes

---

## 1. **Subtractor (Difference Amplifier)**

👉 **Job:** Output = difference of two input voltages.

$$
V_{out} = (R_2/R_1)(V_2 - V_1)
$$

* **Circuit:** Uses both inverting & non-inverting input.
* **Use:** Removes common signals (noise cancellation).

🔹 **Hinglish:** Ye dono input voltages ka **difference** nikalta hai.

---

## 2. **Integrator**

👉 **Job:** Output = integration of input (acts like mathematical ∫).

$$
V_{out}(t) = -\frac{1}{RC}\int V_{in}(t) dt
$$

* **Circuit:** Capacitor in feedback.
* **Use:** Signal waveform generation, ADC.

🔹 **Hinglish:** Input ko **add karke jama** karta rehta hai → output slope form.

---

## 3. **Differentiator**

👉 **Job:** Output = derivative of input (acts like d/dt).

$$
V_{out}(t) = -RC \frac{dV_{in}(t)}{dt}
$$

* **Circuit:** Capacitor in series at input.
* **Use:** Edge detection, sharp signal detection.

🔹 **Hinglish:** Input ke change/variation ko highlight karta hai.

---

## 4. **Comparator**

👉 **Job:** Compares 2 voltages → outputs HIGH/LOW.

* **If** $V_{in} > V_{ref}$ → output HIGH.

* **Else** → output LOW.

* **Use:** ADC, decision-making circuits.

🔹 **Hinglish:** Jaise ek judge → konsa voltage bada hai decide karta hai.

---

## 5. **Schmitt Trigger**

👉 **Job:** Comparator with **hysteresis** (upper & lower threshold).

* Removes noise, gives **clean square wave** from noisy input.

* **Use:** Digital pulse generation.

🔹 **Hinglish:** Noisy input ko **saaf aur stable square wave** banata hai.

---

## 6. **Zero Crossing Detector (ZCD)**

👉 **Job:** Detects when input crosses **0V axis**.

* Output changes sign at every crossing.
* **Use:** Phase detection, frequency measurement.

🔹 **Hinglish:** Jab bhi input zero line cross kare → output switch ho jata hai.

---

## 7. **Active Filters (Op-Amp + R + C)**

👉 Types:

* **Low Pass:** Passes low freq, blocks high freq.

* **High Pass:** Passes high freq, blocks low.

* **Band Pass:** Passes only a range.

* **Band Stop/Notch:** Rejects a range.

* **Use:** Audio processing, communication.

🔹 **Hinglish:** Normal filter jaisa hi, but op-amp use karte → **zyada gain + accuracy** milti hai.

---

## 8. **Precision Rectifier (Super Diode)**

👉 **Job:** Rectifies (converts AC → DC) even for very small voltages.

* Normal diode drop (0.7V) ko remove karta hai.
* **Use:** Signal detectors, AC voltmeter.

🔹 **Hinglish:** Chhote se chhota signal bhi rectifier karega, normal diode se better.

---

# ⭐ Quick Table (One Shot Revision)

| Application         | Formula / Feature                     | Use Case                |
| ------------------- | ------------------------------------- | ----------------------- |
| Subtractor          | $V_{out} ∝ (V_2 - V_1)$               | Noise removal           |
| Integrator          | $V_{out} = -\frac{1}{RC} ∫ V_{in} dt$ | Waveform gen, ADC       |
| Differentiator      | $V_{out} = -RC \frac{dV_{in}}{dt}$    | Edge detection          |
| Comparator          | HIGH/LOW decision                     | ADC, logic              |
| Schmitt Trigger     | Hysteresis                            | Clean square wave       |
| ZCD                 | Output flips at 0 crossing            | Frequency, phase detect |
| Active Filters      | LPF, HPF, BPF, Notch                  | Audio, comms            |
| Precision Rectifier | No diode drop issue                   | Small signal rectifier  |

---
