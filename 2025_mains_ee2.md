[EE2-2025-Q1] Control Systems & Processors · Block Diagram & 8085
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 1 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Evaluate, Explain, Give, Determine, Obtain
Theme (primary): Transfer Function Reduction
Theme (secondary): 8085 Instructions & Measurement Uncertainty
Repeat cluster: none
Has figure: yes
(a) The block diagram of a system is as shown below:

**Figure ID:** FIG-EE2-2025-Q1a
**Circuit description (netlist form):** Control system block diagram with input $R(s)$ and output $Y(s)$. From $R(s)$, the path branches directly to forward block $G_3$ (summing with $+$ at the output summing junction) and to a main comparator (summing with $+$ for input and $-$ for feedback from block $H_2$). Output of first comparator passes through block $G_1$ to a second comparator (summing $+$ from $G_1$ and $-$ from feedback block $H_1$). The output of the second comparator branches into forward block $G_2$ and feedback block $H_2$. The output of $G_2$ sums with the output of $G_3$ at the third summing junction to produce output $Y(s)$. Output $Y(s)$ is fed back through block $H_1$ to the second comparator.
**Symbolic form:** $$\frac{Y(s)}{R(s)} = \frac{G_1 G_2 + G_3(1 + G_1 H_2 + G_2 H_1)}{1 + G_1 H_2 + G_2 H_1}$$

Evaluate the overall transfer function $\frac{Y(s)}{R(s)}$ using block diagram reduction technique.
[10]

(b) Explain the operation performed by 8085 microprocessor when the following instructions are executed :
(i) JMP unconditionally
(ii) POP
(iii) PUSH
(iv) RET
(v) STC
[$2\times5=10$]

(c) For the circuit shown in the figure below

**Figure ID:** FIG-EE2-2025-Q1c
**Circuit description (netlist form):** Resistor circuit showing equivalent resistance $R$ formed by resistor $R_1$ connected in series with the parallel combination of resistors $R_2$ and $R_3$.
**Symbolic form:** $$R = R_1 + \frac{R_2 R_3}{R_2 + R_3}$$

give expression for the overall uncertainty in the value of combined resistance R. Further, evaluate the overall uncertainty in the value of combined resistance R, when individual values of the resistors are as
$R_1=50\pm0.1\ \Omega$
$R_2=100\pm0\cdot2\ \Omega$
$R_3=100\pm0.2\ \Omega$
[10]

(d) A factory has a fixed load of 860 kW and is operating at 0.85 power factor. The electric utility company offers to supply energy at the following two alternate rates:
(i) LV supply at ₹30/kVA max demand/annum + 12 paise/kWh
(ii) HV supply at ₹25/kVA max demand/annum + 10 paise/kWh
The HV switchgear costs ₹50/kVA and switchgear losses at full load amount to 4%. Interest and depreciation charges for switchgear are 10% of the capital cost. If the factory is to work 48 hours/week, then determine the more economical tariff option.
[10]

(e) If the generator polynomial is $(x^4+x+1)$ and the message bits are 1101101, then obtain the CRC code.
[10]

[EE2-2025-Q2] Control Systems & Processors · State-Space & 8085 Programming
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 2 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Design, Realize, Write, Calculate
Theme (primary): Lead Compensator Design
Theme (secondary): 8085 Assembly & PMMC Temp Error
Repeat cluster: none
Has figure: no
(a) An LTI system with the following state-space representation is given:
$$\dot{x}=\begin{bmatrix}0&1\\ 0&-0\cdot5\end{bmatrix}x+\begin{bmatrix}0\\ k\end{bmatrix}u$$
$$y=\begin{bmatrix}1&0\end{bmatrix}x$$
Design a phase lead compensator so that the system achieves a settling time of 2 seconds for a 2% tolerance band and has a damped natural frequency of $2\text{ rad/s}.$ Also realize the designed compensator using passive components.
[20]

(b) For 8085 microprocessor, write the instructions to perform the following:
(i) Set the zero flag when a register pair is used as a down counter
(ii) Load the accumulator with the contents of location 2050H, if memory location 2050H contains byte F8H
(iii) Load 3AH in memory location 2050H, if registers H and L contain 20H and 50H
(iv) Subtract 25H with borrow from accumulator, if the accumulator contains 37H and the borrow flag is set
(v) Complement the accumulator, which has data byte 89H
[$4\times5=20$]

(c) A moving-coil instrument with a resistance of 10 $\Omega$ gives full-scale deflection for a current of 1 mA. A manganin shunt is used to extend its range to 1 A. Calculate the error caused by a $5^\circ\text{C}$ fall in temperature, when-
(i) the manganin shunt is directly connected across the moving coil;
(ii) a 90 $\Omega$ manganin resistance is used in series with the moving coil, before applying manganin shunt.
Assume temperature coefficient of copper as $0\cdot004/^\circ\text{C}$ and that of manganin as $0.00015/^\circ\text{C}$.
[10]

[EE2-2025-Q3] Control Systems & Measurements · Root Locus & AC Bridge
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 3 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Sketch, Compute, Verify, Determine, Evaluate, Calculate, Explain, Draw, List
Theme (primary): Root Locus & Signal Flow Graph
Theme (secondary): AC Bridge Balance & 8085 Interrupts
Repeat cluster: none
Has figure: yes
(a) (i) Sketch the approximate root locus plot for a time-delay system approximated by the transfer function
$$G(s)=\frac{K(1-\frac{s}{2})}{s(s+1)(1+\frac{s}{2})}$$
Also compute the largest value of K for which the system is stable under unity feedback. Verify this value from the root locus plot.
[10]
(ii) The signal flow graph of a system is as shown below :

**Figure ID:** FIG-EE2-2025-Q3aii
**Circuit description (netlist form):** Signal flow graph with input node $R(s)$ and output node $Y(s)$. Main forward path consists of directed branches from node 1 to 2 (gain 1), node 2 to 3 (gain 2), node 3 to 4 (gain $K_1$), node 4 to 5 (gain $\frac{1}{s(s+2)}$), node 5 to 6 (gain $\frac{1}{s}$), and node 6 to $Y(s)$ (gain 1). Feedback and self loops: self-loop at node 6 with gain 1; feedback branch from node 6 to node 4 with gain $-2$; feedback branch from node 4 to node 2 with gain $-1$; feedback branch from node 6 to node 2 with gain $-1$.
**Symbolic form:** not derivable from figure.

Determine the overall transmission $\frac{R(s)}{Y(s)},$ and evaluate the sensitivity of the output to variations in $K_1$ at $s=10$ What would be the value of sensitivity obtained under DC condition, i.e., $s=0$?
[10]

(b) A bridge consists of the following configurations :
Arm AB: A choke coil of unknown resistance $R_1$ and unknown inductance $L_1$
Arm BC: A non-inductive resistance $R_3$
Arm DA: A non-inductive resistance $R_2$
Arm CD: A mica condenser with capacitance $C_4$ in series with a non-inductive resistance $R_4$
Bridge balance is obtained at 400 Hz with the following component values:
$R_2=2000\ \Omega$, $R_3=500\ \Omega$, $C_4=0.2\ \mu\text{F}$, $R_4=70.9\ \Omega$
Assume that capacitor has a series resistance of 0.1 $\Omega$. Calculate the resistance and inductance of the choke coil. Also sketch the phasor diagram for the bridge under balanced conditions, and evaluate Q factor of the choke coil.
[20]

(c) Explain maskable interrupt. Draw the timing diagram for the maskable interrupt acknowledgement cycle. List the activities in each clock cycle.
[10]

[EE2-2025-Q4] Control Systems & Processors · Freq Response & 8085
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 4 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Compute, Obtain, Write, Specify, Give, Explain, Find
Theme (primary): Second-Order Responses & State-Space
Theme (secondary): 8085 Accumulator logic & Piezoelectric Transducer
Repeat cluster: none
Has figure: yes
(a) (i) Consider a second-order type-1 system with no zeros. The system under unity feedback admits a resonant peak of 1.36 at resonant frequency $8\cdot2\text{ rad/s}$. Compute the transfer function $G(s)$, and its steady-state error due to input signal $x(t)=2u(t)+3t\cdot u(t)$ under unity feedback.
[10]
(ii) For the system shown in the figure below

**Figure ID:** FIG-EE2-2025-Q4aii
**Circuit description (netlist form):** Unity negative feedback control system with forward transfer function block $G(s) = \frac{K}{s(s+a)}$ receiving error signal from input $R$ and feedback $Y$, producing output $Y$.
**Symbolic form:** $$\frac{Y(s)}{R(s)} = \frac{K}{s^2 + as + K}$$

the unit step response is given by
$$y(t)=1-1\cdot15e^{-2t}\sin(3\cdot464t+\frac{\pi}{3})$$
Obtain the state-space representation of the system in observable canonical form.
[10]

(b) (i) For 8085 microprocessor, write a program to do the following:
1. Clear the accumulator
2. Add 47H (using ADI instruction)
3. Subtract 92H
4. Add 64H
5. Display the results after subtracting 92H and after adding 64H
Specify the answer you would expect at the output port. Also give the reason for clearing the accumulator before adding the number 47H directly to the accumulator.
[10]
(ii) Write the instruction to clear the CY flag to load FFH in register B and increment (B). If the CY flag is set, display 1 at the output port; otherwise, display the contents of register B. Explain your result.
[10]

(c) A quartz piezoelectric transducer having a capacitance of 3000 pF and voltage sensitivity of 0.06 V-m/N has a resistance of $10^7\text{ M}\Omega$. The impedance of the measuring system has a capacitance of 300 pF in parallel with a $1\text{ M}\Omega$ resistance. A force as shown in the figure is applied across the transducer:

**Figure ID:** FIG-EE2-2025-Q4c
**Circuit description (netlist form):** Rectangular force pulse waveform $F(N)$ versus time $t$. Pulse has constant amplitude $0.2\text{ N}$ starting at $t=0$ and ending at $t=4\times 10^{-3}\text{ s}$ ($4\text{ ms}$), with value 0 for $t > 4\times 10^{-3}\text{ s}$.
**Symbolic form:** $$F(t) = 0.2[u(t) - u(t - 4\times 10^{-3})]\text{ N}$$

Find the voltages just before and after $t=4\text{ ms}$. [Permittivity of quartz is $40.6\times10^{-12}\text{ F/m}$]
[10]

[EE2-2025-Q5] Control & Power Systems · Stability Delay & Protection
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 5 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Calculate, What is, Determine
Theme (primary): Delay Instability
Theme (secondary): Frequency Counter Error & CB Recovery Voltage
Repeat cluster: none
Has figure: no
(a) Given a second-order linear time-invariant system $G(s)$ with a relative degree of 2. $G(s)$ admits a zero steady-state error for unit step input and steady-state error of 0.1 for unit ramp input under unity feedback configuration. Further, it admits a settling time of 4 seconds for 2% tolerance band in its unit step response under unity feedback. A delay of T seconds is now placed in cascade with $G(s)$. Calculate the value of T in seconds that will make the delayed system oscillate under unity feedback configuration.
[10]

(b) A frequency counter with an accuracy of $\pm1\text{ LSD}\pm(1\times10^{-6})$ is employed to measure frequencies of 100 Hz, 1 MHz and 100 MHz. Calculate the percentage measurement error in each case. What is the effect of time base on error?
[10]

(c) An 11 kV, 50 Hz alternator is connected to a system which has inductance and capacitance per phase of 10 mH and $0.01\ \mu\text{F}$ respectively. Determine (i) the maximum voltage across circuit breaker contacts, (ii) the frequency of transient oscillation, (iii) the average RRRV and (iv) the maximum RRRV.
[10]

(d) Four 50 MVA alternators of 15% reactance each are connected via four 35 MVA reactors each of 10% reactance to a common bus bar. The feeders are connected to the junction of each alternator and its reactor. Determine the rating of each feeder circuit breaker.
[10]

(e) A code is made up of 'dots' and 'dashes'. Assuming that a dash is three times as long as a dot with one-third the probability of occurrence of a dot, calculate-
(i) the information in a dot and a dash;
(ii) the entropy of the dot-dash code;
(iii) the average rate of information, if a dot lasts for 10 ms and this time is allowed between symbols.
[10]

[EE2-2025-Q6] Power Systems & Comm · Line Models & TDM
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 6 | Marks: 50 | Words: N/A
Syllabus: Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation; symmetrical components, analysis of symmetrical and unsymmetrical faults. Concepts of system stability: swing curves and equal area criterion. Static VAR system. Basic concepts of HVDC transmission.
Directive: Determine, Draw, Find, Repeat
Theme (primary): Nominal-Pi Transmission Line
Theme (secondary): TDM Sampling Rates & Alternator Protection
Repeat cluster: none
Has figure: no
(a) Determine the sending-end voltage, current, power factor of a single-phase, 50 Hz, 76.2 kV transmission line delivering a load of 12 MW at 0.8 p.f. lagging. The line constants are $R=25\ \Omega$, inductance 200 mH and capacitance between lines is $2.5\ \mu\text{F}$. Also determine the regulation and efficiency of the transmission. Use nominal-$\pi$ method. Draw the phasor diagram.
[20]

(b) 24 voice signals are sampled uniformly and then time-division multiplexed. Flat-top sampling is used with one microsecond duration. Multiplexing operation provides for synchronization by adding an extra pulse of sufficient amplitude and also one microsecond duration. The highest frequency component of each voice signal is 3.4 kHz.
(i) Assuming a sampling rate of 8 kHz, find the spacing between successive pulses of the multiplexed signal.
(ii) Repeat your calculations by assuming the use of Nyquist rate sampling.
[20]

(c) A 3-phase, 33 kV, star-connected alternator is to be protected using circulating current protection. The pilot wires are connected to the secondary windings of $100/5$ ratio current transformer. The protective relay is adjusted to operate with an out of balance current of 1 A in the pilot wires. Determine (i) the earthing resistance which will protect 90% of the winding and (ii) the percent of the winding which would be protected, if the earthing resistance is 15 $\Omega$.
[10]

[EE2-2025-Q7] Power Systems & Comm · Fault Analysis & Line Coding
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 7 | Marks: 50 | Words: N/A
Syllabus: Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation; symmetrical components, analysis of symmetrical and unsymmetrical faults. Concepts of system stability: swing curves and equal area criterion. Static VAR system. Basic concepts of HVDC transmission.
Directive: Find, What is, Draw, Describe
Theme (primary): Transformer 3-Phase Fault
Theme (secondary): Line Coding PCM SNR & Static Differential Relay
Repeat cluster: none
Has figure: yes
(a) Two generators are connected in parallel to the low-voltage side of a 3-phase, $\Delta$-Y transformer as shown below:
Generator 1 is rated 60 MVA, 13.8 kV
Generator 2 is rated 30 MVA, 13.8 kV
Each generator has a subtransient reactance of 20%. The transformer is rated 90 MVA, $13.8\ \Delta/69\text{ Y kV}$ with a reactance of 10%. Before the fault occurs, the voltage on the high-tension side of the transformer is 66 kV. The transformer is unloaded, and there is no circulating current between the generators. Find the subtransient current in each generator, when a 3-phase short circuit occurs on the high-tension side of the transformer:

**Figure ID:** FIG-EE2-2025-Q7a
**Circuit description (netlist form):** Single-line diagram showing two generators G1 and G2 connected in parallel to the low-voltage delta-connected primary side of a 3-phase $\Delta\text{-Y}$ step-up transformer. A symmetrical three-phase short-circuit fault designated as F occurs on the high-voltage star-connected secondary side of the transformer.
**Symbolic form:** not derivable from figure.

[20]

(b) (i) What is line coding? For the data sequence 10101110, draw the waveforms for the following line coding schemes:
1. Polar NRZ scheme
2. Bipolar NRZ scheme
3. Differential Manchester scheme
4. RZ polar scheme
[10]
(ii) A PCM system uses 4096 quantization levels to handle telephone signals with a volume range of 40 dB.
1. What is the SNR for maximum sinusoidal signal level?
2. What is the SNR level for the smallest sinusoidal signal level?
3. With a 10 dB compression provided, what will be the new SNR?
[10]

(c) With the help of schematic and circuit diagrams, describe the operation of a static differential protection relay, using the rectifier bridge amplitude comparator.
[10]

[EE2-2025-Q8] Power Systems & Comm · Stability & Coding
Exam: UPSC Mains 2025 | Paper: EE2 | Q.No: 8 | Marks: 50 | Words: N/A
Syllabus: Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation; symmetrical components, analysis of symmetrical and unsymmetrical faults. Concepts of system stability: swing curves and equal area criterion. Static VAR system. Basic concepts of HVDC transmission.
Directive: Determine, Develop, Draw, Write, Calculate
Theme (primary): Generator Power-Angle Swing Equation
Theme (secondary): Convolutional Encoder & Belted Cable Capacitance
Repeat cluster: none
Has figure: yes
(a) The figure below shows the single-line diagram of a generator connected through parallel transmission lines to an infinite bus. The machine is delivering 1 pu power, and both the terminal voltage and the infinite bus voltage are 1 pu. The numbers on the diagram indicate the values of the reactances on a common system base. The transient reactance of the generator is 0.20 pu as indicated. Determine the power-angle equation for the system applicable to the operating conditions. Also develop the swing equation of the machine:

**Figure ID:** FIG-EE2-2025-Q8a
**Circuit description (netlist form):** Single-line diagram of a synchronous generator connected to an infinite bus. The generator has internal transient excitation voltage $E'$ with transient reactance $X_d' = 0.20\text{ pu}$, followed by a step-up transformer with reactance $j0.15\text{ pu}$. The transformer connects to a sending bus that splits into two parallel transmission lines, each having a series reactance of $j0.3\text{ pu}$, both terminating at an infinite bus with voltage $V = 1.0\text{ pu}$.
**Symbolic form:** not derivable from figure.

Given $H=4\text{ MJ/MVA}.$
[20]

(b) Draw the diagram of a $1/3$ rate convolution encoder. Write the corresponding code tree for the $1/3$ rate convolution encoder.
[20]

(c) The capacitances of a 3-core cable of belted type are measured and found to be as follows:
(i) Between 3 cores bunched together and the sheath, $8\ \mu\text{F}$
(ii) Between one conductor and the other two connected together to the sheath, $5\ \mu\text{F}$
Calculate the capacitance to the neutral and the total charging kVA, when the cable is connected to an 11 kV, 50 Hz, 3-phase supply.
[10]