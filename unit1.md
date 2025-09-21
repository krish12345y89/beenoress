# **1. P–N Junction Diode**

---

## **English Explanation (Easy Language)**

* A **diode** is a two-terminal electronic device.
* It is made by **joining P-type semiconductor** and **N-type semiconductor** together.
* The junction formed between P and N region is called **P–N junction**.
* It allows **current in one direction only** (Forward bias) and **blocks current in the opposite direction** (Reverse bias).
* So, diode works like a **one-way valve** for electric current.

---

## **Hindi (Hinglish, Simple Language)**

* **Diode ek 2 terminal device hai.**
* Ye banta hai jab hum **P-type semiconductor (jahaan holes zyada hote h)** aur **N-type semiconductor (jahaan electrons zyada hote h)** ko jod dete h.
* Dono ke beech banne wali line ko bolte h **P-N Junction**.
* Diode ka kaam hai current ko **ek hi side flow hone dena** (Forward Bias), aur dusri side **roak dena** (Reverse Bias).
* Matlab diode ek **ek-tarfa current gate** ki tarah kaam karta h.

---

## **Symbol of Diode**

```
   Anode (P) →|← Cathode (N)
```

* Arrow = Current ka direction (forward)
* Line = Blocking side

---

## **Construction Diagram (Simple)**

```
 P-type (holes +)      N-type (electrons -)
 ----------------|------------------------
                  Junction
```

---

## **Key Features of P–N Junction Diode**

1. **Unidirectional Device** → Current only flows in forward direction.
2. **Forward Bias Condition** → When P is connected to +ve, diode conducts.
3. **Reverse Bias Condition** → When P is connected to –ve, diode does not conduct (except very small leakage).
4. **Threshold Voltage** → Minimum voltage required to start conduction.

   * For Silicon diode ≈ 0.7 V
   * For Germanium diode ≈ 0.3 V
5. **Applications** → Rectifiers, Clipping circuits, Voltage multipliers, etc.

---

## **Characteristics (VI Curve)**

* **Forward Bias Region**: Current starts after threshold voltage (0.7V for Si).
* **Reverse Bias Region**: Very small current (leakage).
* **Breakdown Region**: If reverse voltage exceeds a limit → diode gets damaged (except Zener diode).

---

### **Diagram of V–I Characteristics**

```
 Current (I)
   |
   |        / (Forward current after 0.7V)
   |       /
   |------/
   |     .
   |     . (Small leakage in reverse bias)
   |________________________ Voltage (V)
             -      0     +
```

---

Samajh gya bhai 🙌
Ab mai **Topic 2 (V–I Characteristics of Diode)** ko **bohot detail me, saari characteristics** ke saath explain karta hu.
Simple English + Hinglish dono, diagram + points + graphs bhi.

---

# **2. V–I Characteristics of a Diode (Detailed)**

---

## **Introduction**

**English:**

* The **V–I characteristic** is a graph between **Voltage across the diode (V)** and **Current through the diode (I)**.
* It explains how the diode behaves in **Forward Bias** and **Reverse Bias** conditions.

**Hinglish:**

* V–I characteristic ek graph hota h jo batata h ki diode pe voltage lagane par usme kitna current flow karta h.
* Ye graph hume diode ka behaviour forward aur reverse dono condition me samjhata h.

---

## **Biasing of Diode**

### **1. Forward Bias**

* **English:** P connected to +ve, N to –ve → junction barrier decreases → conduction starts after threshold.
* **Hinglish:** P ko + aur N ko – se jodo → barrier potential kam ho jata h → current tabhi start hota h jab threshold voltage cross ho jaye.

### **2. Reverse Bias**

* **English:** P connected to –ve, N to +ve → junction barrier increases → only small leakage current flows.
* **Hinglish:** P ko – aur N ko + se jodo → barrier potential aur bada ho jata h → sirf thoda leakage current bachta h.

---

## **Complete V–I Characteristics Curve**

```
 Current (I)
   |
   |                   Forward Region
   |                     /
   |                    /
   |-------------------/---------------------> Voltage (V)
   |        .         /
   |        .        /
   |        .       /
   | Reverse Leakage .
   |        .  (Breakdown here)
   |
```

---

## **Characteristics / Features (Detailed)**

### **1. Threshold Voltage (Cut-in Voltage, Vγ)**

* **English:** Minimum forward voltage at which diode starts conducting.

  * For Silicon: 0.7 V
  * For Germanium: 0.3 V
* **Hinglish:** Diode ko current chalane ke liye minimum forward voltage chahiye.

  * Silicon = 0.7 V
  * Germanium = 0.3 V

---

### **2. Forward Resistance (Dynamic Resistance)**

* **English:** The resistance offered by diode in forward conducting state.
* It is very small (few ohms).
* **Hinglish:** Jab diode forward bias me chal raha ho to uska resistance bohot kam hota h (kuch ohms).

---

### **3. Reverse Resistance**

* **English:** Resistance of diode in reverse bias.
* Very high (Mega-ohms).
* **Hinglish:** Reverse me diode ka resistance bohot zyada hota h (lakho ohms).

---

### **4. Reverse Saturation Current (Io)**

* **English:** Small constant current that flows in reverse bias due to minority carriers.
* In microampere (μA).
* **Hinglish:** Reverse bias me thoda sa leakage current chalta h (minority carriers ki wajah se). Ye microampere range me hota h.

---

### **5. Breakdown Voltage (Vbr)**

* **English:** Reverse voltage at which diode suddenly conducts a very large current.
* In normal diode → diode gets damaged.
* In **Zener diode** → it works safely in breakdown.
* **Hinglish:** Agar reverse voltage bohot zyada kar do to diode achanak se bohot current chalane lagta h.

  * Normal diode → jal jata h.
  * Zener diode → safe rahkar kaam karta h.

---

### **6. Knee Voltage**

* **English:** Another name of Threshold Voltage where conduction starts.
* **Hinglish:** Ye wahi point h jaha se diode current chalana start karta h (cut-in voltage).

---

### **7. Static Resistance**

* **English:** Ratio of applied voltage to current at a point on VI curve.
  $Rs = V / I$
* **Hinglish:** Kisi ek point par diode ka resistance nikalne ka formula h V/I.

---

### **8. Dynamic (AC) Resistance**

* **English:** Ratio of change in voltage to change in current in forward bias.
  $rd = ΔV / ΔI$
* **Hinglish:** Forward conduction region me agar voltage aur current thoda change karo to unke ratio se dynamic resistance milta h.

---

### **9. Cut-off Region**

* **English:** In reverse bias, very small current flows → this region is called cut-off region.
* **Hinglish:** Reverse bias me jab sirf chhota sa leakage current flow hota h uss part ko cut-off region bolte h.

---

### **10. Breakdown Region**

* **English:** Reverse voltage > Breakdown → sudden increase in current.
* **Hinglish:** Reverse bias me jab voltage limit se upar chala jata h to diode breakdown me chala jata h aur current bohot zyada badh jata h.

---

## **Final Graph Labels (Detailed)**

Forward Side (Right Side):

* Cut-in Voltage → Current starts after this.
* Forward conduction → Current rises exponentially.

Reverse Side (Left Side):

* Leakage Current → Very small.
* Breakdown Voltage → Sudden rise.

---

## **Summary of Characteristics (One-Word Table)**

| Feature / Characteristic | Silicon  | Germanium |
| ------------------------ | -------- | --------- |
| Threshold Voltage (Vγ)   | 0.7 V    | 0.3 V     |
| Forward Resistance       | Low      | Low       |
| Reverse Resistance       | High     | High      |
| Leakage Current          | Very Low | Higher    |
| Breakdown Voltage        | High     | Low       |

---
Samajh gya bhai 🙌
Ab mai **Topic 2 (V–I Characteristics of Diode)** ko **bohot detail me, saari characteristics** ke saath explain karta hu.
Simple English + Hinglish dono, diagram + points + graphs bhi.

---

# **2. V–I Characteristics of a Diode (Detailed)**

---

## **Introduction**

**English:**

* The **V–I characteristic** is a graph between **Voltage across the diode (V)** and **Current through the diode (I)**.
* It explains how the diode behaves in **Forward Bias** and **Reverse Bias** conditions.

**Hinglish:**

* V–I characteristic ek graph hota h jo batata h ki diode pe voltage lagane par usme kitna current flow karta h.
* Ye graph hume diode ka behaviour forward aur reverse dono condition me samjhata h.

---

## **Biasing of Diode**

### **1. Forward Bias**

* **English:** P connected to +ve, N to –ve → junction barrier decreases → conduction starts after threshold.
* **Hinglish:** P ko + aur N ko – se jodo → barrier potential kam ho jata h → current tabhi start hota h jab threshold voltage cross ho jaye.

### **2. Reverse Bias**

* **English:** P connected to –ve, N to +ve → junction barrier increases → only small leakage current flows.
* **Hinglish:** P ko – aur N ko + se jodo → barrier potential aur bada ho jata h → sirf thoda leakage current bachta h.

---

## **Complete V–I Characteristics Curve**

```
 Current (I)
   |
   |                   Forward Region
   |                     /
   |                    /
   |-------------------/---------------------> Voltage (V)
   |        .         /
   |        .        /
   |        .       /
   | Reverse Leakage .
   |        .  (Breakdown here)
   |
```

---

## **Characteristics / Features (Detailed)**

### **1. Threshold Voltage (Cut-in Voltage, Vγ)**

* **English:** Minimum forward voltage at which diode starts conducting.

  * For Silicon: 0.7 V
  * For Germanium: 0.3 V
* **Hinglish:** Diode ko current chalane ke liye minimum forward voltage chahiye.

  * Silicon = 0.7 V
  * Germanium = 0.3 V

---

### **2. Forward Resistance (Dynamic Resistance)**

* **English:** The resistance offered by diode in forward conducting state.
* It is very small (few ohms).
* **Hinglish:** Jab diode forward bias me chal raha ho to uska resistance bohot kam hota h (kuch ohms).

---

### **3. Reverse Resistance**

* **English:** Resistance of diode in reverse bias.
* Very high (Mega-ohms).
* **Hinglish:** Reverse me diode ka resistance bohot zyada hota h (lakho ohms).

---

### **4. Reverse Saturation Current (Io)**

* **English:** Small constant current that flows in reverse bias due to minority carriers.
* In microampere (μA).
* **Hinglish:** Reverse bias me thoda sa leakage current chalta h (minority carriers ki wajah se). Ye microampere range me hota h.

---

### **5. Breakdown Voltage (Vbr)**

* **English:** Reverse voltage at which diode suddenly conducts a very large current.
* In normal diode → diode gets damaged.
* In **Zener diode** → it works safely in breakdown.
* **Hinglish:** Agar reverse voltage bohot zyada kar do to diode achanak se bohot current chalane lagta h.

  * Normal diode → jal jata h.
  * Zener diode → safe rahkar kaam karta h.

---

### **6. Knee Voltage**

* **English:** Another name of Threshold Voltage where conduction starts.
* **Hinglish:** Ye wahi point h jaha se diode current chalana start karta h (cut-in voltage).

---

### **7. Static Resistance**

* **English:** Ratio of applied voltage to current at a point on VI curve.
  $Rs = V / I$
* **Hinglish:** Kisi ek point par diode ka resistance nikalne ka formula h V/I.

---

### **8. Dynamic (AC) Resistance**

* **English:** Ratio of change in voltage to change in current in forward bias.
  $rd = ΔV / ΔI$
* **Hinglish:** Forward conduction region me agar voltage aur current thoda change karo to unke ratio se dynamic resistance milta h.

---

### **9. Cut-off Region**

* **English:** In reverse bias, very small current flows → this region is called cut-off region.
* **Hinglish:** Reverse bias me jab sirf chhota sa leakage current flow hota h uss part ko cut-off region bolte h.

---

### **10. Breakdown Region**

* **English:** Reverse voltage > Breakdown → sudden increase in current.
* **Hinglish:** Reverse bias me jab voltage limit se upar chala jata h to diode breakdown me chala jata h aur current bohot zyada badh jata h.

---

## **Final Graph Labels (Detailed)**

Forward Side (Right Side):

* Cut-in Voltage → Current starts after this.
* Forward conduction → Current rises exponentially.

Reverse Side (Left Side):

* Leakage Current → Very small.
* Breakdown Voltage → Sudden rise.

---

## **Summary of Characteristics (One-Word Table)**

| Feature / Characteristic | Silicon  | Germanium |
| ------------------------ | -------- | --------- |
| Threshold Voltage (Vγ)   | 0.7 V    | 0.3 V     |
| Forward Resistance       | Low      | Low       |
| Reverse Resistance       | High     | High      |
| Leakage Current          | Very Low | Higher    |
| Breakdown Voltage        | High     | Low       |

---

Bhai ab chalte h **Topic 4: Full-Wave Rectifier (Review)** 👇
Ye thoda bada h kyunki isme **2 types** hote h – (1) Center-Tap Rectifier, (2) Bridge Rectifier.

---

# **4. Full-Wave Rectifier (Review)**

---

## **Introduction**

**English:**

* A **Full-Wave Rectifier** converts **both half cycles of AC** into **DC output**.
* Unlike half-wave rectifier (which wastes half cycle), this uses **both positive and negative half cycles**.
* It gives **higher efficiency** and **less ripple**.

**Hinglish:**

* Full-wave rectifier AC ke **dono half cycles** (positive + negative) ko **DC me badal deta h**.
* Half-wave rectifier sirf ek half use karta tha, par full-wave dono half ka use karta h.
* Iski **efficiency zyada hoti h** aur ripple kam hote h.

---

## **Types of Full-Wave Rectifier**

1. **Center-Tap Full-Wave Rectifier**
2. **Bridge Full-Wave Rectifier**

---

## **1. Center-Tap Full-Wave Rectifier**

### Circuit Diagram

```
           AC
         ~~~~~~~
           |    
       ----| |---- Center Tap
       |        |
      D1        D2
       |        |
       +---/\/\/\---+
           Load RL
            |
           GND
```

* Transformer with center-tap secondary.
* Two diodes (D1, D2).

---

### Working

* **Positive Half Cycle:**

  * D1 conducts (forward bias), D2 blocks.
  * Current flows through load in one direction.

* **Negative Half Cycle:**

  * D2 conducts, D1 blocks.
  * Current again flows through load in same direction.

👉 Both halves give output → continuous pulsating DC.

---

## **2. Bridge Full-Wave Rectifier**

### Circuit Diagram

```
       AC Input
        ~    ~
        |    |
       D1   D2
        |\ /|
        | V |
       D3   D4
        |    |
        +---/\/\/\---+
             RL
             |
            GND
```

* Uses **4 diodes in bridge connection**.
* No center tap transformer required.

---

### Working

* **Positive Half Cycle:**

  * D1 and D3 conduct → current flows through RL.
* **Negative Half Cycle:**

  * D2 and D4 conduct → current again flows through RL (same direction).

👉 Both halves utilized.

---

## **Waveforms**

### Input (AC)

```
   ~ ~ ~ ~ ~ ~
```

### Output (Full-Wave DC)

```
   /¯\ /¯\ /¯\ /¯\ /¯\
  /   \   /   \   /   \
```

(Every half cycle converted into positive output.)

---

## **Important Characteristics / Parameters**

1. **DC Output Voltage (Average Value):**

   $$
   V_{dc} = \frac{2 V_m}{\pi}
   $$

2. **RMS Value of Output:**

   $$
   V_{rms} = \frac{V_m}{\sqrt{2}}
   $$

3. **Peak Inverse Voltage (PIV):**

   * Center-Tap: $PIV = 2V_m$ per diode.
   * Bridge: $PIV = V_m$ per diode.

4. **Rectification Efficiency (η):**

   * Maximum = 81.2%

5. **Ripple Factor (r):**

   * 0.48 (much lower than half-wave).

---

## **Advantages**

* Higher efficiency (81.2%).
* Utilizes both halves of input.
* Output DC smoother (less ripple).
* Bridge type doesn’t need center-tap transformer.

---

## **Disadvantages**

* Center-tap requires special transformer (costly).
* Bridge requires 4 diodes (voltage drop increases).

---

## **Applications**

* DC power supplies.
* Battery chargers.
* Radio, TV, and electronic devices.
* Any place where efficient AC → DC conversion is required.

---

## **Comparison: Half-Wave vs Full-Wave**

| Feature                 | Half-Wave Rectifier | Full-Wave Rectifier                 |
| ----------------------- | ------------------- | ----------------------------------- |
| No. of Diodes           | 1                   | 2 (center-tap) / 4 (bridge)         |
| Efficiency (η)          | 40.6%               | 81.2%                               |
| Ripple Factor (r)       | 1.21 (high)         | 0.48 (low)                          |
| Transformer Requirement | Not needed          | Needed in center-tap, not in bridge |
| DC Output Voltage       | Vm/π                | 2Vm/π                               |

---

Bhai ab chalte h **Topic 5: Zener Diode** 👇

---

# **5. Zener Diode**

---

## **Introduction**

**English:**

* A **Zener diode** is a special type of diode designed to operate safely in the **reverse breakdown region**.
* It is mainly used for **voltage regulation** (keeping voltage constant).

**Hinglish:**

* Zener diode ek special diode hota h jo **reverse breakdown region me bhi safe chalta h**.
* Iska main kaam h **voltage ko stable/constant rakhna** (Voltage Regulator).

---

## **Symbol**

```
   Anode (P) →|← Cathode (N)
                ─┐
                ┘  (bent line for zener)
```

---

## **Construction**

* Made from **heavily doped P and N materials** → thin depletion layer.
* Due to heavy doping → breakdown voltage is very sharp and well-defined.

---

## **V–I Characteristics of Zener Diode**

### **1. Forward Bias**

* Works like a normal diode.
* Conducts after threshold (0.7 V for Si).

### **2. Reverse Bias**

* Initially only small leakage current flows.
* When reverse voltage reaches **Zener Breakdown Voltage (Vz)** → large current flows, but voltage across diode remains **constant at Vz**.

---

### **Graph (Simple Representation)**

```
 Current (I)
   |
   |           Forward Bias
   |             /
   |            /
   |-----------/-------------------------
   |          .
   |          . Leakage
   |          .
   |          .___________
   |                    | (Voltage stays constant at Vz)
   |________________________ Voltage (V)
            -Vz     0    +V
```

---

## **Key Characteristics**

1. **Zener Voltage (Vz):**

   * Reverse voltage at which zener conducts heavily but keeps voltage constant.

2. **Knee Voltage:**

   * Same as threshold voltage in forward bias (\~0.7 V for Si).

3. **Breakdown Region:**

   * Zener diode specially designed to operate here **without damage**.

4. **Voltage Regulation Property:**

   * Keeps output voltage constant even if input voltage or load current changes.

---

## **Applications of Zener Diode**

1. **Voltage Regulator**

   * Keeps voltage constant for circuits.

2. **Overvoltage Protection**

   * Protects devices from high voltage spikes.

3. **Reference Voltage Generator**

   * Used in power supplies as fixed voltage reference.

4. **Wave Shaping**

   * Used in clipping circuits.

---

## **Zener Diode as Voltage Regulator (Circuit)**

```
          AC
         ~~~~
          |
        Rectifier
          |
         ----
          |----->|----/\/\/\----+---- Vout
               Zener    R        |
                                GND
```

* **R (Series Resistor):** Limits current.
* **Zener Diode:** Maintains constant output voltage Vout = Vz.

---

## **Advantages**

* Simple and cheap voltage regulation.
* Works well for low-power applications.
* Fast response.

---

## **Disadvantages**

* Not suitable for high current/voltage regulation.
* Less efficient compared to IC regulators.

---

Bhai ab chalte h **Topic 5: Zener Diode** 👇

---

# **5. Zener Diode**

---

## **Introduction**

**English:**

* A **Zener diode** is a special type of diode designed to operate safely in the **reverse breakdown region**.
* It is mainly used for **voltage regulation** (keeping voltage constant).

**Hinglish:**

* Zener diode ek special diode hota h jo **reverse breakdown region me bhi safe chalta h**.
* Iska main kaam h **voltage ko stable/constant rakhna** (Voltage Regulator).

---

## **Symbol**

```
   Anode (P) →|← Cathode (N)
                ─┐
                ┘  (bent line for zener)
```

---

## **Construction**

* Made from **heavily doped P and N materials** → thin depletion layer.
* Due to heavy doping → breakdown voltage is very sharp and well-defined.

---

## **V–I Characteristics of Zener Diode**

### **1. Forward Bias**

* Works like a normal diode.
* Conducts after threshold (0.7 V for Si).

### **2. Reverse Bias**

* Initially only small leakage current flows.
* When reverse voltage reaches **Zener Breakdown Voltage (Vz)** → large current flows, but voltage across diode remains **constant at Vz**.

---

### **Graph (Simple Representation)**

```
 Current (I)
   |
   |           Forward Bias
   |             /
   |            /
   |-----------/-------------------------
   |          .
   |          . Leakage
   |          .
   |          .___________
   |                    | (Voltage stays constant at Vz)
   |________________________ Voltage (V)
            -Vz     0    +V
```

---

## **Key Characteristics**

1. **Zener Voltage (Vz):**

   * Reverse voltage at which zener conducts heavily but keeps voltage constant.

2. **Knee Voltage:**

   * Same as threshold voltage in forward bias (\~0.7 V for Si).

3. **Breakdown Region:**

   * Zener diode specially designed to operate here **without damage**.

4. **Voltage Regulation Property:**

   * Keeps output voltage constant even if input voltage or load current changes.

---

## **Applications of Zener Diode**

1. **Voltage Regulator**

   * Keeps voltage constant for circuits.

2. **Overvoltage Protection**

   * Protects devices from high voltage spikes.

3. **Reference Voltage Generator**

   * Used in power supplies as fixed voltage reference.

4. **Wave Shaping**

   * Used in clipping circuits.

---

## **Zener Diode as Voltage Regulator (Circuit)**

```
          AC
         ~~~~
          |
        Rectifier
          |
         ----
          |----->|----/\/\/\----+---- Vout
               Zener    R        |
                                GND
```

* **R (Series Resistor):** Limits current.
* **Zener Diode:** Maintains constant output voltage Vout = Vz.

---

## **Advantages**

* Simple and cheap voltage regulation.
* Works well for low-power applications.
* Fast response.

---

## **Disadvantages**

* Not suitable for high current/voltage regulation.
* Less efficient compared to IC regulators.

---

Bhai ab chalte h **Topic 7: Voltage Multiplier Circuits** pe. Ye important aur exam me favourite question hota h. Step by step English + Hinglish me samjhata hu, saath me features aur diagram bhi.

---

# **7. Voltage Multiplier Circuits**

### **English (Simple)**

A **voltage multiplier circuit** is an electronic circuit that multiplies the input AC voltage (using diodes + capacitors) to get a higher DC voltage at the output.

* They are **used when high DC voltage is required but transformer with high secondary voltage is not available**.
* Instead of increasing transformer turns, these circuits use **diodes + capacitors in special arrangement**.

---

## **Types of Voltage Multipliers**

1. **Voltage Doubler** → Output ≈ 2 × peak input voltage.
2. **Voltage Tripler** → Output ≈ 3 × peak input voltage.
3. **Voltage Quadrupler** → Output ≈ 4 × peak input voltage.
4. **General Multiplier** → Any multiple (n × V).

---

## **Basic Working Principle**

* **Capacitors** → store charge.
* **Diodes** → allow charging in only one direction.
* In each half cycle of AC, capacitors are charged and stacked in series, producing higher DC output.

---

## **A. Half-Wave Voltage Doubler**

* Consists of 2 diodes (D1, D2) and 2 capacitors (C1, C2).
* During **positive half cycle** → D1 conducts, charges C1.
* During **negative half cycle** → D2 conducts, charges C2.
* Output voltage across both capacitors = **2 × Vpeak (DC)**.

**Diagram (Simple Sketch):**

```
         D1
 AC ~---->|----+-----> Vout (+)
          |    |
         C1    C2
          |    |
 AC ~-----+---|<|-----> Vout (–)
               D2
```

---

## **B. Voltage Tripler**

* Adds one more diode + capacitor to the doubler circuit.
* Output ≈ **3 × Vpeak**.

## **C. Voltage Quadrupler**

* Adds another diode + capacitor.
* Output ≈ **4 × Vpeak**.

---

## **Applications**

1. **CRT TV & Oscilloscopes** → High voltage for electron beam.
2. **X-ray machines** → Need kV range DC voltage.
3. **Microwave ovens** → Use doubler for magnetron power.
4. **Laser printers / Photocopiers** → High voltage supply.

---

## **Features**

* **Advantages:**

  * No need of high-voltage transformer.
  * Cheap and simple design.
  * Easy to scale (doubler, tripler, quadrupler, etc.).

* **Disadvantages:**

  * Not suitable for high current (best for low current, high voltage).
  * Output voltage decreases under heavy load.
  * Ripple voltage may be high.

---

# **Hinglish (Simple Hindi)**

**Voltage Multiplier** matlab ek aisa circuit jo input AC voltage ko **multiply karke bahut bada DC output deta hai**.

* Yaha **diode aur capacitor** use hote h.
* Transformer ko high voltage banane ki zarurat nahi hoti, bas normal transformer + multiplier circuit se bada DC nikal lete h.

---

### **Types**

1. **Voltage Doubler** → Output = 2 × input peak.
2. **Voltage Tripler** → Output = 3 × input peak.
3. **Voltage Quadrupler** → Output = 4 × input peak.

---

### **Kaise Kaam Karta h?**

* **Capacitor** charge store karta h.
* **Diode** ek hi direction me charge allow karta h.
* Har half cycle me capacitor charge hote h aur ek dusre ke upar stack hoke bada voltage banate h.

---

### **Example: Voltage Doubler**

* Positive half cycle me → D1 conduct karega, C1 charge hoga.
* Negative half cycle me → D2 conduct karega, C2 charge hoga.
* Dono capacitor ka voltage add hoke **2 × Vpeak** output milta h.

---

### **Use Kaha Hota H?**

* **TV, Oscilloscope, X-ray machine, Microwave oven, Laser printer** me.

---

### **Features**

* **Fayde:** Transformer ka size chhota, simple, cheap.
* **Nuksan:** Zyada current nahi de sakta, load badhne pe voltage drop ho jata h.

---

# **1. Half-Wave Voltage Doubler**

**Circuit:**

```
         D1
 AC ~---->|----+-----> Vout (+)
          |    |
         C1    C2
          |    |
 AC ~-----+---|<|-----> Vout (–)
               D2
```

* **Positive half cycle:** D1 conducts → C1 charges.
* **Negative half cycle:** D2 conducts → C2 charges.
* **Output = 2 × Vpeak (DC).**

---

# **2. Voltage Tripler**

**Circuit:**

```
         D1
 AC ~---->|----+---------+-----> Vout (+)
          |    |         |
         C1   D3        C3
          |    ^         |
 AC ~-----+---| |--C2----+-----> Vout (–)
               D2
```

* C1 charges first, then C2 + C3 add up.
* **Output = 3 × Vpeak (DC).**

---

# **3. Voltage Quadrupler**

**Circuit:**

```
         D1
 AC ~---->|----+---------+-------------+-----> Vout (+)
          |    |         |             |
         C1   D3        C3            D4
          |    ^         |             ^
 AC ~-----+---| |--C2----+----C4-------+-----> Vout (–)
               D2
```

* More diodes + capacitors stacked.
* **Output = 4 × Vpeak (DC).**

---

# **Key Notes for Exam (Direct Lines likhne ke liye)**

* Each stage = 1 diode + 1 capacitor.
* **Doubler = 2 × Vpeak**
* **Tripler = 3 × Vpeak**
* **Quadrupler = 4 × Vpeak**
* Output DC is **pulsating with ripple**, so not pure DC.
* Used in **X-ray, CRT, TV, Microwave** where high voltage but low current is needed.

---
