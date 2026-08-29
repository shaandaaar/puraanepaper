[EE2-2024-Q1] Control Systems & Microprocessors · PID & 8085
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 1 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: What are, Explain, Determine, Calculate, Draw
Theme (primary): PID Controllers & 8085 Instructions
Theme (secondary): Ohmmeter Scale & Cable Loss
Repeat cluster: none
Has figure: yes
Q1. (a) What are the limitations of (i) Proportional (P), (ii) Integral (I), (iii) Derivative (D), and (iv) PID Controllers ?
What is the application of positive feedback control system? [10]

(b) Explain the operation performed by 8085 microprocessor when the following arithmetic instructions are executed :
(i) ADD M
(ii) ADC M
(iii) DAD rp
(iv) SBI d8
(v) DCR reg
[$5\times2=10$]

(c) The ohmmeter circuit has $V_{B}=1\cdot5\text{ V}$, $R_{1}=15\text{ k}\Omega$, $R_{m}=50\ \Omega$, $R_{2}=50\ \Omega$ and meter $\text{FSD}=50\ \mu\text{A}.$

**Figure ID:** FIG-EE2-2024-Q1c
**Circuit description (netlist form):** An ohmmeter circuit consisting of an internal DC voltage source $V_B = 1\cdot5\text{ V}$ connected between the return rail and terminal A. An unknown resistor $R_x$ is connected across external terminals A and B. Terminal B connects to a series resistor $R_1 = 15\text{ k}\Omega$ carrying current $I_b$, followed by a parallel combination of an adjustable shunt resistor $R_2 = 50\ \Omega$ (carrying current $I_2$) and a meter branch consisting of internal resistance $R_m = 50\ \Omega$ and meter movement M (carrying meter current $I_m$ with branch voltage $V_m$) connected to the return rail.
**Symbolic form:** not derivable from figure.

Determine the ohmmeter scale reading at 0.5 FSD. [10]

(d) Calculate the power loss in a cable insulation having capacitance $9\ \mu\text{F}$, loss angle $0\cdot05\text{ degree}$ and operating at $11\text{ kV}$, $50\text{ Hz}$. Draw the phasor diagram and equivalent circuit also. [10]

(e) Explain the concept of a constellation diagram. Draw the PSK signal constellations for the value of $M=2$, 4 and 8, if all have same transmitted signal energy $E_{s}$. [10]

[EE2-2024-Q2] Control Systems & Microprocessors · Dead-Time & Interfacing
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 2 | Marks: 50 | Words: N/A
Syllabus: PC organisation; CPU, instruction set, register settiming diagram, programming, interrupts, memory interfacing, I/O interfacing, programmable peripheral devices.
Directive: Show, Compare, What are, Explain, Determine, Comment
Theme (primary): Feedback Stability & Dead-Time
Theme (secondary): 8085 I/O Interfacing & Error Analysis
Repeat cluster: none
Has figure: no
Q2. (a) The open-loop transfer function of a feedback control system incorporating a dead time element is given by:
$$G(s)=\frac{Ke^{-Ts}}{s(s+1)}$$
where $K>0$ and $T>0$ are variable scalar parameters.
For a given value of T, show that the closed loop system for all values will be $K<K_{0}$
where $K_{0}=\omega_{0}\csc(\omega_{0}T),$ and $\omega_{0}$ is the smallest value of $\omega$ satisfying the equation $\omega=\cot(\omega T)$. [20]

(b) (i) Compare I/O mapped I/O and memory mapped I/O interfacing techniques used in 8085 microprocessor. [10]

(ii) What are the operating modes of Port-A of 8255? Explain handshake operation in I/O ports. [$4+3+3=10$]

(c) In a parallel circuit, in one branch the current, $I_{1}=(100\pm2)\text{ A}$ and in the other branch the current, $I_{2}=(200\pm5)\text{ A}$. Determine the total current considering the following errors:
(i) Limiting error
(ii) Probable error
Comment upon the results as well. [$2+6+2=10$]

[EE2-2024-Q3] Control Systems & Measurements · Frequency Response & CRT
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 3 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Compute, Calculate, Write
Theme (primary): Second Order Frequency Response
Theme (secondary): Cathode Ray Tube & 8085 Programming
Repeat cluster: none
Has figure: yes
Q3. (a) An underdamped second order system having a transfer function of the form
$$M(s)=\frac{K\omega_{n}^{2}}{s^{2}+2\xi\omega_{n}s+\omega_{n}^{2}}$$
has a frequency response plot as shown in the figure. Compute the system gain K and the damping factor ($\xi$).

**Figure ID:** FIG-EE2-2024-Q3a
**Circuit description (netlist form):** A frequency response plot of closed-loop magnitude $|M(j\omega)|$ versus angular frequency $\omega$ for an underdamped second-order system. The curve begins at $|M(j0)| = 1\cdot0$ at $\omega = 0$, rises to a peak value of $2\cdot5$ at $\omega = \omega_n$, and monotonically decays toward zero as frequency increases.
**Symbolic form:** $$|M(j\omega)| = \frac{K\omega_n^2}{\sqrt{(\omega_n^2-\omega^2)^2 + (2\xi\omega_n\omega)^2}}$$

[20]

(b) A CRT has an anode voltage of 3 kV and its parallel deflecting plates are 2.5 cm long and 5 mm apart. The screen is 30 cm from the centre of the plates. Assume the gain of the amplifier through which input voltage is applied to the deflecting plates as 100. Calculate the following:
(i) Beam speed
(ii) Deflection sensitivity of the CRT
(iii) Deflection factor of the CRT
(iv) Input voltage required to deflect the beam through 5 cm
[$5\times4=20$]

(c) Write an assembly language program to add two numbers of 8-bit data stored in memory locations 4200H and 4201H and store the result in 4202H and 4203H. [10]

[EE2-2024-Q4] Measurements & Microprocessors · Transducers & Addressing
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 4 | Marks: 50 | Words: N/A
Syllabus: Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements. Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter. Transducers: thermocouple, thermistor, LVDT, strain-guage, piezo-electric crystal.
Directive: Calculate, Identify and explain, Determine
Theme (primary): Piezoelectric Transducers
Theme (secondary): 8085 Addressing Modes & System Identification
Repeat cluster: none
Has figure: yes
Q4. (a) The capacitance of a piezoelectric transducer is 2000 pF and charge sensitivity is $30\times10^{-3}\text{ C/m}.$ Assume the capacitance of the connecting cable as 150 pF, when the oscilloscope used for readout has a readout input resistance of $1\text{ M}\Omega$ with parallel capacitance of 100 pF.
Calculate the following:
(i) Sensitivity of transducer alone
(ii) High frequency sensitivity of the entire measuring system
(iii) Lowest frequency that can be measured with 5% amplitude error by the entire system
(iv) Value of the external shunt capacitance that can be connected in order to extend the range of 5% error down to 20 Hz
[$5\times4=20$]

(b) Identify and explain briefly the addressing modes of 8085 microprocessor in the given instructions:
(i) ADD reg
(ii) MOV rd, M
(iii) CALL addr 16
(iv) LDA addr 16
(v) CMA
[$4\times5=20$]

(c) The first order system and its response to unit step input are shown in Figure I and II respectively. Determine the system parameters 'a' and 'K'.

**Figure ID:** FIG-EE2-2024-Q4c
**Circuit description (netlist form):** Two figures showing a first-order system and its step response. Figure I shows a block diagram with input $u(t)$, open-loop block $\frac{K}{s+a}$, and output $c(t)$. Figure II shows the unit step response curve $c(t)$ starting at the origin, with its initial slope tangent line intersecting the steady-state asymptote value of $2\cdot0$ at time $t = 0\cdot2\text{ s}$.
**Symbolic form:** $$C(s) = \frac{K}{s(s+a)}$$

[10]

[EE2-2024-Q5] Control Systems & Power Systems · Sensitivity & Admittance
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 5 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Determine, Calculate, Write, How does
Theme (primary): Closed-Loop Sensitivity
Theme (secondary): Energy Meter & Bus Admittance Matrix
Repeat cluster: none
Has figure: yes
Q5. (a) The block diagram of a position control system is shown in the figure. Determine the sensitivity of the closed loop transfer function T(s) with respect to $G(s)$ and $H(s)$ for $1\text{ rad/sec}$.

**Figure ID:** FIG-EE2-2024-Q5a
**Circuit description (netlist form):** A closed-loop feedback block diagram consisting of an input $R(s)$ entering a comparator with positive sign. The feedback signal from block $H(s) = 5$ is subtracted at the comparator. The resulting error signal is applied to forward transfer function $G(s) = \frac{10}{s(s+1)}$, which produces output $C(s)$. The output $C(s)$ feeds back into the input of $H(s)$.
**Symbolic form:** $$T(s) = \frac{C(s)}{R(s)} = \frac{G(s)}{1 + G(s)H(s)}$$

[10]

(b) The disc in a single-phase energy meter rotates 1320 times when monitoring a 110 V, 3 A load at unity power factor over a period of 8 hours. Calculate the meter constant. If the meter makes 750 revolutions when measuring the energy supplied to a 110 V, 5 A load for 3 hours, determine the load power factor. [$5+5=10$]

(c) Write the bus admittance matrix for the network shown in the figure.

**Figure ID:** FIG-EE2-2024-Q5c
**Circuit description (netlist form):** A 5-bus electrical network with numbered buses 0, 1, 2, 3, 4. Buses 0 and 4 are horizontal reference rails. Bus 2 is connected to bus 0 via parallel branches of branch admittance $-j0\cdot3$ and a current source, to bus 4 via branch admittance $-j6$, and to bus 3 via branch admittance $-j4$. Bus 3 is connected to bus 0 via parallel branches of branch admittance $-j0\cdot3$ and a current source, to bus 4 via branch admittance $-j12$, to bus 2 via branch admittance $-j4$, and to bus 1 via branch admittance $-j8$. Bus 1 is connected to bus 0 via parallel branches of branch admittance $-j0\cdot3$ and a current source, to bus 4 via branch admittance $-j6$, and to bus 3 via branch admittance $-j8$.
**Symbolic form:** not derivable from figure.

[10]

(d) A single core cable without grading operates at 14 kV. The conductor radius is $1\cdot12\text{ cm}$ and insulation radius is $2\cdot75\text{ cm}$. If cable is with inter-sheath grading at suitable radius, then calculate the maximum operating voltage of the cable. [10]

(e) How does information get passed from one layer to the next in the Internet model? How do the layers of the Internet model correlate to the layers of the OSI model? [$6+4=10$]

[EE2-2024-Q6] Power Systems & Communication · Dispatch & Delta Modulation
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 6 | Marks: 50 | Words: N/A
Syllabus: Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation; symmetrical components, analysis of symmetrical and unsymmetrical faults. Concepts of system stability: swing curves and equal area criterion. Static VAR system. Basic concepts of HVDC transmission.
Directive: Calculate, Determine
Theme (primary): Economic Load Dispatch
Theme (secondary): Transmission Loss & Slope Overload
Repeat cluster: none
Has figure: yes
Q6. (a) Calculate the power loss in the transmission system given in the following figure. The numerical values of transmission system are :
$$I_{1}=0\cdot75\angle 0^{\circ}\text{ PU},\ I_{2}=0\cdot8\angle 0^{\circ}\text{ PU},$$
$$V_{3}=1\cdot2\angle 0^{\circ}\text{ PU},\ Z_{1}=(0\cdot07+j0\cdot15)\text{ PU},$$
$$Z_{2}=(0\cdot06+j0\cdot20)\text{ PU},\ Z_{3}=(0\cdot05+j0\cdot06)\text{ PU}$$

**Figure ID:** FIG-EE2-2024-Q6a
**Circuit description (netlist form):** A power transmission single-line diagram with four buses. Generator $G_1$ feeds Bus 1 at voltage $V_1$, sending current $I_1$ through transmission line $L_1$ (impedance $Z_1$) to Bus 3. Generator $G_2$ feeds Bus 2 at voltage $V_2$, sending current $I_2$ through transmission line $L_2$ (impedance $Z_2$) to Bus 3. Bus 3 (at voltage $V_3$) delivers current $I_3$ through transmission line $L_3$ (impedance $Z_3$) to the Load at Bus 4.
**Symbolic form:** not derivable from figure.

[20]

(b) The fuel input equations of two power plant operations are given as:
$$F_{1}=0\cdot3\ P_{1}^{2}+35\ P_{1}+125,\text{ \textrupee/hr}$$
$$F_{2}=0\cdot2\ P_{2}^{2}+30\ P_{2}+140,\text{ \textrupee/hr}$$
If the maximum and minimum loading on each unit is 90 MW and 20 MW respectively and the total consumption demand is 200 MW, then calculate the economical operating schedule and corresponding cost of generation. If load is equally shared by both units, calculate the savings achieved by loading the units as per equal incremental production cost. Neglect the transmission losses. [20]

(c) A DM transmitter with a fixed step size of 0.25 V is given a sinusoidal message signal. Determine the maximum permissible amplitude of the message signal, if slope overload is to be avoided. Assume sampling frequency ten times the Nyquist rate. [10]

[EE2-2024-Q7] Power Systems & Communication · Transmission Lines & PCM
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 7 | Marks: 50 | Words: N/A
Syllabus: Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation; symmetrical components, analysis of symmetrical and unsymmetrical faults. Concepts of system stability: swing curves and equal area criterion. Static VAR system. Basic concepts of HVDC transmission.
Directive: Calculate, Determine, Mention, Write
Theme (primary): ABCD Parameters
Theme (secondary): PCM Quantization & HVDC Systems
Repeat cluster: none
Has figure: no
Q7. (a) Calculate the real and reactive power at sending end of a transmission line while delivering 10 MVA load at 0-85 lagging power factor at receiving end of line. The line parameters are $A=1$, $B=12\cdot12\angle 64\cdot64^{\circ}\ \Omega$, $D=1$ and receiving end voltage of line is 33 kV. [20]

(b) (i) A binary transmission system with a transmitted power of 300 mW uses a channel with zero-mean AWGN of two-sided PSD equal to $10^{-15}\text{ W/Hz}$ and a total transmission loss of 80 dB. If the probability of error, $P_{e}$ is not to exceed $10^{-4}$ calculate the maximum allowable bit rate using non-coherent ASK. [10]

(ii) A $2\text{ V}_{pp}$ audio frequency signal band-limited to 8 kHz is to be transmitted using a PCM system. If the quantization error of any sample is to be at the most $\pm 1\%$ of the dynamic range of the message signal, determine the minimum value of n, the minimum sampling rate and corresponding bit rate of transmission. [10]

(c) (i) Mention the techniques of increasing the voltage and current rating of converter station of HVDC transmission system. [5]

(ii) Write the requirements of valves used in HVDC transmission system. [5]

[EE2-2024-Q8] Communication & Protection · Entropy & Relays
Exam: UPSC Mains 2024 | Paper: EE2 | Q.No: 8 | Marks: 50 | Words: N/A
Syllabus: Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers. Computer aided protection introduction; line, bus, generator, transformer protection; numeric relays and application of DSP to protection.
Directive: Determine, Calculate
Theme (primary): Information Theory Entropy
Theme (secondary): Differential Relays & Circuit Breakers
Repeat cluster: none
Has figure: no
Q8. (a) Two sources $M_{1}$ and $M_{2}$ emit messages $x_{1}$, $x_{2}$, $x_{3}$ and $y_{1}$, $y_{2}$, $y_{3}$ with the joint probability $P(X,Y)$ as shown below in the matrix form.
$$P(X,Y) = \begin{bmatrix} \frac{3}{40} & \frac{1}{40} & \frac{1}{40} & \frac{1}{40} \\ \frac{1}{20} & \frac{3}{20} & \frac{1}{20} & \frac{1}{20} \\ \frac{1}{8} & \frac{1}{8} & \frac{3}{8} & \frac{1}{8} \end{bmatrix}$$
Determine $H(X)$, $H(Y)$, $H(X/Y)$ and $H(Y/X)$. [20]

(b) Calculate the current setting of a relay for fault that draws up to 400% of the rated current. The relay is used for differential protection of a delta-star, 50 MVA, 66/11 kV transformer. The CT ratio on secondary side is 3000 : 5 and primary side is 600 : 5. [20]

(c) Calculate the peak voltage which appears across the terminals of a circuit breaker when it suddenly interrupts 20 A current at 20% of its peak value in a circuit. The inductance and stray capacitance of circuit are 15 H and 3000 pF respectively. [10]