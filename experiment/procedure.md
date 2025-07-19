### Procedure

### Apparatus 

 Transistors, resistors, capacitors, inductance coil, dc power supply, C.R.O.

 
<h2>1. Designing</h2>

<p>
  <strong>Selection of Transistor:</strong> Use a high-frequency NPN transistor such as BF195.
</p>

<p>
  <strong>Component Values:</strong><br>
  L = 10&nbsp;μH<br>
  V<sub>CE</sub> = 0.5 × V<sub>CC</sub><br>
  V<sub>RE</sub> = V<sub>E</sub> = 0.1 × V<sub>CC</sub><br>
  V<sub>RC</sub> = V<sub>C</sub> = 0.4 × V<sub>CC</sub>
</p>

<h3>Applying KVL for the Output Loop</h3>

<p>
  V<sub>CC</sub> = I<sub>C</sub> R<sub>C</sub> + V<sub>CE</sub> + I<sub>E</sub> R<sub>E</sub><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;= I<sub>C</sub> R<sub>C</sub> + V<sub>CE</sub> + V<sub>E</sub>
</p>

<p>
  <strong>Therefore:</strong><br>
</p>

$$R_C=\frac{V_{CC}-V_{CE}-V_{E}}{I_C}$$


$V_E=I_ER_E \approx I_CR_E$

There for 

$$R_E=\frac{V_E}{I_E}$$

<p><strong>Let</strong> V<sub>CC</sub> = 12V, β = 60 and I<sub>C</sub> = 1mA</p>

<h3>Applying KVL for the Output Loop</h3>

<p>
  V<sub>CC</sub> = I<sub>C</sub>R<sub>C</sub> + V<sub>CE</sub> + I<sub>E</sub>R<sub>E</sub> =
  I<sub>C</sub>R<sub>C</sub> + V<sub>CE</sub> + V<sub>E</sub>
</p>

<p><strong>Therefore</strong>:</p>

$$R_E = \frac{V_{CC} - V_{CE} - V_E}{I_C} \approx 4.7k\,\Omega$$

$$V_E = I_E R_E \approx I_C R_E$$

$$R_E = \frac{V_E}{I_C} = 1.2\,k\,\Omega$$

$$I_{R1} \approx 21 I_B \quad \text{and} \quad I_{R2} = 20 I_B$$

$$\text{i.e.} \quad R_2 \leq \frac{1}{10} \beta R_E \approx 7.5\,k\Omega$$

$$V_{BB} = \frac{R_2}{R_1 + R_2} V_{CC} = V_{BE} + V_E = 0.7 + 1.2 = 1.9\,V$$

$$R_1 \approx 39\,k\Omega$$

<h3>Design of Feedback Network</h3>

<p><strong>Selection of capacitors:</strong> All capacitor values may be taken as 1μF.</p>

<p><strong>Required frequency of oscillation:</strong> f = 1000 KHz</p>
<p><strong>Let</strong> L = 10μH</p>

<p>
  <strong>Frequency formula:</strong><br>
$$f = \frac{1}{2\pi\sqrt{\frac{L C_{1} C_{2}}{C_{1} + C_{2}}}}$$
</p>

<p>Effective capacitor C<sub>eq</sub> = 2.5 nF</p>

<p><strong>Therefore,</strong> C = 5 nF</p>

<h2>Result</h2>

<p>
  Amplitude and frequency of sine wave from Colpitts Oscillator = ……….. V, ……….. Hz.
</p>



