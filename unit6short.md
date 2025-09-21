# **Operational Amplifier – Quick Revision Notes**

---

## **1. Ideal vs Practical Op-Amp**

**Ideal:**

* Infinite gain
* Infinite input resistance
* Zero output resistance
* Infinite bandwidth
* Zero offset voltage
* Infinite CMRR

**Practical:**

* Gain = $10^5 – 10^6$
* Input resistance = $10^6\ \Omega$
* Output resistance ≈ $100\ \Omega$
* Bandwidth = limited (Hz–MHz)
* Offset ≠ 0
* CMRR = 70–100 dB

---

## **2. Inverting Amplifier**

* Input → (−) terminal, (+) grounded
* Output = **inverted (180° phase shift)**
* Gain:

$$
A_v = -\frac{R_f}{R_{in}}
$$

---

## **3. Non-Inverting Amplifier**

* Input → (+) terminal
* Output = **same phase**
* Gain:

$$
A_v = 1 + \frac{R_f}{R_1}
$$

---

## **4. Differential Amplifier**

* Amplifies **difference** between two inputs.

$$
V_{out} = \left(\frac{R_2}{R_1}\right)(V_2 - V_1)
$$

* Cancels common signals (noise).

---

## **5. Offset Errors**

* **Input Offset Voltage (Vos):** Small voltage needed at inputs to make output = 0.
* **Input Bias Current (Ib):** Avg current at input terminals.

$$
I_b = \frac{I_+ + I_-}{2}
$$

* **Input Offset Current (Ios):** Difference between input currents.

$$
I_{os} = |I_+ - I_-|
$$

---

## **6. CMRR (Common Mode Rejection Ratio)**

* Ability to reject common signals.

$$
CMRR = \frac{A_d}{A_{cm}}, \quad CMRR(dB) = 20\log_{10}\left(\frac{A_d}{A_{cm}}\right)
$$

* Higher CMRR → better noise rejection.

---

# **Combined Comparison Chart**

| Topic                 | Formula / Key Point               | Phase   | Notes                   |   |          |
| --------------------- | --------------------------------- | ------- | ----------------------- | - | -------- |
| **Ideal Op-Amp**      | A → ∞, Rin → ∞, Rout → 0, Vos = 0 | –       | Perfect model           |   |          |
| **Practical Op-Amp**  | A = $10^5$, Rin = MΩ, Rout ≈ 100Ω | –       | Realistic               |   |          |
| **Inverting Amp**     | $A_v = -Rf/Rin$                   | 180°    | Controlled by resistors |   |          |
| **Non-Inverting Amp** | $A_v = 1 + Rf/R1$                 | 0°      | Gain ≥ 1                |   |          |
| **Differential Amp**  | $V_{out} = (R2/R1)(V2 - V1)$      | –       | Rejects noise           |   |          |
| **Offset Voltage**    | Vos (mV)                          | –       | Needed for zero output  |   |          |
| **Bias Current**      | $Ib = (I+ + I-)/2$                | –       | nA–µA                   |   |          |
| **Offset Current**    | (Ios =                            | I+ - I- | )                       | – | mismatch |
| **CMRR**              | $CMRR = Ad/Acm$, 70–100 dB        | –       | Noise rejection         |   |          |

---
