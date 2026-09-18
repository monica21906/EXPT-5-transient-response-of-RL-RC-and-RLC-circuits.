# EXPT-5-transient-response-of-RL-RC-and-RLC-circuits.
# TRANSIENT ANALYSIS OF SERIES RC CIRCUIT
# AIM:
To determine transient response of a series RC circuit using MultisimSimulator. 
# APPARATUS REQUIRED:
1. CRO
2. DCB
3. Resistors
4. Bread board
5. Connecting wires
6. PC with Multisim
7. Simulator
# THEORY:
When an increasing DC voltage is applied to a discharged Capacitor, the capacitor
draws a charging current and “charges up”, and when the voltage is reduced, thecapacitor discharges in the opposite direction. Because capacitors are able to storeelectrical energy they act like small batteries and can store or release the energyas
required.The charge on the plates of the capacitor is given as: Q = CV. This charging(storage) and discharging (release) of a capacitors energy is never instant but takes acertain amount of time to occur with the time taken for the capacitor to charge or
discharge to within a certain percentage of its maximum supply value being knownas
its Time Constant ( τ ).If a resistor is connected in series with the capacitor formingan RC circuit, the capacitor will charge up gradually through the resistor until thevoltage across the capacitor reaches that of the supply voltage. RC Charging Curve :
As the capacitor charges up, the potential difference across its plates slowly increases
with the actual time taken for the charge on the capacitor to reach 63%of its maximumpossible voltage, in our curve 0.63Vs being known as one Time Constant, ( τ ).This 0.63Vs voltage point is given the abbreviation of 1τ, (one time constant).Thecapacitor continues charging up and the voltage difference between Vs and Vc reduces, so to does the circuit current, i. Then at its final condition greater than five time constants ( 5τ ) when the capacitor is said to be fully charged, t = ∞, i = 0, q = Q=CV. Then at infinity the current diminishes to zero, the capacitor acts like an open circuit condition therefore, the voltage drop is entirely across the capacitor.So mathematicallywe can say that the time required for a capacitor to charge up to one time constant, ( 1τ ) is given as RC. After a period equivalent to 4 time constants, ( 4T ) the capacitor inthis RC charging circuit is virtually fully charged and the voltage across the capacitor is now approx 98% of its maximum value, 0.98Vs. The time period taken for the capacitor to reach this 4T point is known as the Transient Period. After a time of 5T the capacitor is now fully charged and the voltage across the capacitor, ( Vc ) is equal to the supply voltage, ( Vs ). As the capacitor is fully charged no more current flows in the circuit. The time period after this 5T point is known as the Steady State Period.

<img width="582" height="290" alt="image" src="https://github.com/user-attachments/assets/0882b83d-7018-43da-b309-e29f6e1e1bb1" />

RC Discharging Curve :
During the negative cycle, the capacitor starts to discharge . The rate of decay of the
RC discharging curve is steeper at the beginning because the discharging rate is fastest
at the start, but then tapers off exponentially as the capacitor looses charge at a slower
rate. As the discharge continues, VC reduces resulting in less discharging current. For a RC discharging circuit, the voltage across the capacitor ( VC ) as a function of
time during the discharge period is defined as:

<img width="526" height="277" alt="image" src="https://github.com/user-attachments/assets/4ac560be-f980-4307-af18-02aa2f35f311" />

After five time constants the capacitor is considered to be fully discharged. So an RC
circuit’s time constant is a measure of how quickly it either charges or discharges. 
# PROCEDURE:
1. Make connection as per the circuit diagram .
2. Calculate the values of Vc(t)and write in table .
3. Compare the calculated values and measured values of voltage in both the cases.

# CIRCUIT DIAGRAM
Choose R = 10kΩ and C=0.1µF ( Values of R and C can be changed)
<img width="615" height="202" alt="image" src="https://github.com/user-attachments/assets/7d525931-7369-45c3-b9da-7932f2716ab2" />

Formula :
During charging, Voltage across capacitor is given by
During Discharge, Voltage across capacitor is given by
# TABLE
<img width="1280" height="1244" alt="image" src="https://github.com/user-attachments/assets/a282ab90-dc22-4a1c-bbdc-e922506f801e" />

# RESULT:
Thus the transient analysis of series RC circuit is done practically and verified
with theoretical values using Multisim Simulator.

# TRANSIENT ANALYSIS OF SERIES RL CIRCUIT
# AIM:
To determine transient response of a series RL circuit using Multisim Simulator. 

# APPARATUS REQUIRED:
1. CRO
2. DIB
3. Resistors
4. Bread board
5. Connecting wires
6. PC with Multisim
7. Simulator

# THEORY:
The LR series circuit is connected across a voltage source, (the square wave) and a switch. Assume that the switch, S is open until it is closed at a time t = 0, and then remains permanently closed producing a “step response” type voltage input. The current, i begins to flow through the circuit but does not rise rapidly to its maximum value of Imax as determined by the ratio of V / R (Ohms Law). This limiting factor is due to the presence of the self induced emf within the inductor as a result of the growth of magnetic flux, (Lenz’s Law). After a time the voltage source neutralizes the effect of the self induced emf, the current flow becomes constant and the induced current and field are reduced to zero. the voltage drop across the resistor depends upon the current, i, while the voltage drop across the inductor depends upon
the rate of change of the current, di/dt. The expression for current across the inductor is given as
The expression for voltage across the inductor is given as The time required for the current flowing in the LR series circuit to reach its maximum steady state value is equivalent to about 5 time constants or 5τ. This time constant τ, is measured by τ = L/R, in seconds, where R is the value of the resistor in ohms and L is the value of the inductor in Henries. This then forms the basis of an RL charging circuit
were 5τ can also be thought of as “5*(L/R)” or the transient time of the circuit.The transient time of any inductive circuit is determined by the relationship between the inductance and the resistance. For example, for a fixed value resistance the larger the inductance the slower will be the transient time and therefore a longer time constant for the LR series circuit. Likewise, for a fixed value inductance the smaller the
resistance value the longer the transient time. However, for a fixed value inductance, by increasing the resistance value the transient time and therefore the time constant of the circuit becomes shorter. This is because as the resistance increases the circuit becomes more and more resistive as the value of the
inductance becomes negligible compared to the resistance. If the value of the resistance is increased sufficiently large compared to the inductance the transient time would effectively be reduced to almost zero

   <img width="532" height="260" alt="image" src="https://github.com/user-attachments/assets/646d1b57-c12b-46eb-8f1d-c62a5ea27f29" />

# Formula :
Voltage across inductor is
# PROCEDURE:
1. Make connection as per the circuit diagram .
2. Calculate the values of VL(t)and write in table . Compare the calculated values and measured values of voltage in both the cases.

# CIRCUIT DIAGRAM
<img width="596" height="197" alt="image" src="https://github.com/user-attachments/assets/97a98b6f-a20b-4f98-83d2-91745a2eb2dc" />

# TABLE
<img width="1280" height="1244" alt="image" src="https://github.com/user-attachments/assets/24973a45-63c0-4441-9da9-ee736458a387" />

# RESULT:
Thus the transient analysis of series RL circuit is done practically and verified with theoretical values using Multisim Simulator.

# TRANSIENT ANALYSIS OF SERIES RLC CIRCUIT
# AIM:
To determine transient response of a series RLC circuit using Multisim Simulator.
# APPARATUS REQUIRED:
1. CRO
2. DCB
3. Resistors
4. Bread board
5. Connecting wires
6. PC with Multisim
7. Simulator
# THEORY:
Series RLC circuits consist of a resistance, a capacitance and an inductance connected in series across an alternating supply. In a series RLC circuit containing a resistor, an inductor and a capacitor the source voltage Vin is the phasor sum made up of three components, VR, VL and VC with the current common to all three. Since the current is common to all three components it is used as the horizontal reference when constructing a voltage triangle. The impedance of the circuit is the total opposition to the flow of current. For a series RLC circuit, and impedance triangle can be drawn by dividing each side of the voltage
triangle by its current, I. The voltage drop across the resistive element is equal to I*R, the voltage across the two reactive elements is I*X = I*XL – I*XC while the source voltage is equal to I*Z. The angle between VS and I will be the phase angle, θ.
# CIRCUIT DIAGRAM
Choose R = 10kΩ , L = 10mH and C=0.1µF ( Values of R, L and C can be changed
<img width="531" height="230" alt="image" src="https://github.com/user-attachments/assets/7702b25e-b773-483c-a0b7-b528ddd77548" />

# PROCEDURE:
1. Make connection as per the circuit diagram .
2. Calculate the values of Vc(t), VR(t)VL(t)and write in table .
3. Compare the calculated values and measured values of voltage in both the cases.

<img width="1280" height="1244" alt="image" src="https://github.com/user-attachments/assets/d530e500-8f82-43e5-98cc-56177f8a7452" />

# RESULT:
Thus the transient analysis of series RLC circuit is done practically using Multisim Simulator.
