# PAPER II

## SECTION A

### [EE2-2020-Q1] Root-Locus Break-In Point Gain · 8085 Control Instructions, Strain-Gauge Resistance Change, Steady-State Power Limit & GF(3) Block Code

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Root-Locus Break-In Point Gain
- **Theme (secondary):** 8085 Control Instructions, Strain-Gauge Resistance Change, Steady-State Power Limit & GF(3) Block Code
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> (a) The open-loop transfer function of a feedback system is given by
> $G(s)H(s)=\frac{K(s+3)}{(s-1)(s-2)}.$ Determine the gain K at the break-in point of the root locus of the system. [10]
> 
> (b) Explain briefly the following control instructions of 8085 microprocessor:
> (i) HLT
> (ii) EI
> (iii) DI
> (iv) RIM [10]
> 
> (c) Why are strain gauges made with high value of gauge factor $(G_{f})$? Write the expression for gauge factor in terms of change in resistance and strain. If a strain gauge with a gauge factor of 2 is bonded on a steel structure which is subjected to a stress of $100\text{ MN/m}^{2}$ and the modulus of elasticity of steel is $200\text{ GN/m}^{2}$, then what is the percentage change in the value of the strain gauge resistance due to this applied stress? [10]
> 
> (d) Find the steady-state power limit of a system consisting of a generator with equivalent reactance 0.50 p.u. connected to an infinite bus through a series reactance of 1.0 p.u. The terminal voltage of the generator is held at 1.20 p.u. and the voltage of the infinite bus is 1.0 p.u. [10]
> 
> (e) For a linear block code $C_{b}(4,2)$ over $GF(3)$, the generator matrix (G) is given by
> $G=\begin{bmatrix}1&0&2&1\\ 1&2&0&2\end{bmatrix}$
> (i) Determine all right code words for this code.
> (ii) How many errors can this code correct? [10]

---

### [EE2-2020-Q2] Sustained Oscillation in a Unity-Feedback Step Response · Two-Wattmeter Power-Factor Derivation & 8085 Register/Addressing Modes

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Sustained Oscillation in a Unity-Feedback Step Response
- **Theme (secondary):** Two-Wattmeter Power-Factor Derivation & 8085 Register/Addressing Modes
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> (a) The unit step response of a unity feedback system exhibits sustained oscillations as shown in the figure below. The open-loop transfer function of the system is
> $G(s)=\frac{K}{(s+1)(s+4)(s+a)}.$
> The time x in the figure is 1.0471 second. Determine the values of K and a. [20]
> 
> **Figure ID:** FIG-EE2-2020-Q2a
> **Circuit description (netlist form):** Waveform plot illustrating sustained sinusoidal oscillations of the step response over time $t$ from 0 to 6 seconds. The duration of one half-cycle between two consecutive zero-slope/crossing points is marked as $x = 1.0471\text{ second}$.
> **Symbolic form:** not derivable from figure.
> 
> (b) Draw the circuit arrangement for power measurement in a 3-phase, 3-wire balanced supply and load using two-wattmeter method, and show that the power factor of the load is given by
> $\cos\phi=\frac{1}{\sqrt{1+3\left(\frac{P_{1}-P_{2}}{P_{1}+P_{2}}\right)^{2}}}$
> where $P_{1}$ and $P_{2}$ are powers indicated by Wattmeter 1 and Wattmeter 2, respectively. [20]
> 
> (c) (i) Name various registers in 8085 microprocessor. Which of these registers are of 16-bit length?
> (ii) Explain indirect addressing modes in 8085 microprocessor with suitable example. [10]

---

### [EE2-2020-Q3] Thermistor and RTD Resistance-Temperature Characteristics · Generator/Motor Subtransient Fault Currents & 8085 Subtraction Program

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Transducers: thermocouple, thermistor, LVDT, strain-guage, piezo-electric crystal.
- **Directive:** Find
- **Theme (primary):** Thermistor and RTD Resistance-Temperature Characteristics
- **Theme (secondary):** Generator/Motor Subtransient Fault Currents & 8085 Subtraction Program
- **Repeat cluster:** RC10 (Transducer Characteristics (LVDT/Strain Gauge/Capacitive/Piezo))
- **Has figure:** yes

> (a) The resistance-temperature characteristic of a thermistor is given by
> $R_{T}=R_{0}e^{\beta\left(\frac{1}{T}-\frac{1}{T_{0}}\right)}$
> where $R_{0}$ is the resistance of the thermistor at reference temperature, $T_{0}$ and $R_{T}$ is the resistance at the measured temperature, T. If the value of $\beta$ is 4000 K and the resistance of the thermistor is $200\text{ k}\Omega$ at $-100^{\circ}\text{C}$, find the value of resistance at $400^{\circ}\text{C}$. Also find the ratio of two resistances. If platinum resistance temperature detector (RTD) is used over the same temperature range, then what will be the ratio of RTD resistances on the above-referred two temperatures? [20]
> 
> (b) A synchronous generator and a synchronous motor each rated 25 MVA, 11 kV having 15% subtransient reactance are connected through transformers and a line as shown in the figure below. The transformers are rated 25 MVA, 11/66 kV and 25 MVA, 66/11 kV with leakage reactance of 10% each. The line has a leakage reactance of 10% on a base of 25 MVA, 66 kV. The motor is drawing 15 MW at 0.8 power factor leading and a terminal voltage of 10.6 kV when a symmetrical 3-phase fault occurs at the motor terminals. Find the subtransient current in the generator, motor and fault. [20]
> 
> **Figure ID:** FIG-EE2-2020-Q3b
> **Circuit description (netlist form):** Single-line diagram of a power system. A Generator rated 25 MVA, 11 kV is connected to bus 1. Step-up transformer $T_1$ (25 MVA, 11/66 kV) connects bus 1 to a 66 kV transmission line. Step-down transformer $T_2$ (25 MVA, 66/11 kV) connects the line to bus 2. A synchronous Motor rated 25 MVA, 11 kV is connected to bus 2.
> **Symbolic form:** not derivable from figure.
> 
> (c) (i) For 8085 microprocessor, write a program to do the following:
> (1) Load the number 30H in register B and 39H in register C
> (2) Subtract 39H from 30H
> (3) Display the answer at Port 1
> (ii) Find the output displayed at Port 1. [10]

---

### [EE2-2020-Q4] Buchholz Relay and Circuit-Breaker Magnetizing-Current Transient · Digital Modulation Power/Bandwidth Efficiency Tradeoffs & Natural Oscillation Frequency

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers.
- **Directive:** Discuss
- **Theme (primary):** Buchholz Relay and Circuit-Breaker Magnetizing-Current Transient
- **Theme (secondary):** Digital Modulation Power/Bandwidth Efficiency Tradeoffs & Natural Oscillation Frequency
- **Repeat cluster:** RC16 (Circuit-Breaker/Relay Protection Principles)
- **Has figure:** no

> (a) (i) What is Buchholz relay? Which equipment is protected by it? Discuss its working principle.
> (ii) A circuit breaker interrupts the magnetizing current of a 100 MVA transformer at 220 kV. The magnetizing current of the transformer is 5% of the full-load current. Determine the maximum voltage which may appear across the gap of the breaker when the magnetizing current is interrupted at 53% of its peak value. The stray capacitance is $2500\,\mu\text{F}$ and the inductance is 30 H. [20]
> 
> (b) (i) Explain the power efficiency and bandwidth efficiency of a digital modulation scheme.
> (ii) Comment on the power efficiency for a given bandwidth efficiency for a good modulation scheme.
> (iii) Comment on the bandwidth efficiency for a given power efficiency for a good modulation scheme.
> (iv) Compare the bandwidth efficiency of ASK and QAM modulation techniques.
> (v) Comment on the bandwidth efficiency of M-ary orthogonal signalling scheme for large M.
> (vi) Write the fundamental tradeoff equation between power and bandwidth efficiency under which reliable communication is possible. [20]
> 
> (c) A synchronous generator of reactance 1.20 p.u. is connected to an infinite bus bar $(|V|=1\cdot0\text{ p.u.})$ through transformers and a line of total reactance of 0.60 p.u. The generator no-load voltage is 1.20 p.u. and its inertia constant is $H=4\text{ MW s/MVA}$. The resistance and machine damping may be assumed negligible. The system frequency is 50 Hz. Calculate the frequency of natural oscillations if the generator is loaded to 80% of its maximum power limit. [10]

---

## SECTION B

### [EE2-2020-Q5] LTI System Output for an Exponential Input · Schering Bridge Balance, LG-Fault Current Comparison, CB Restriking Transient & Hamming-Bound Perfect Codes

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** LTI systems: time-domain and transform-domain analysis.
- **Directive:** Determine
- **Theme (primary):** LTI System Output for an Exponential Input
- **Theme (secondary):** Schering Bridge Balance, LG-Fault Current Comparison, CB Restriking Transient & Hamming-Bound Perfect Codes
- **Repeat cluster:** RC06 (Control System Time-Domain Response)
- **Has figure:** no

> (a) The unit impulse response of a linear system is given by $c(t)=e^{t}u(t)+e^{-t}u(t)$. When the same system is subjected to an input of $e^{-3t}u(t)$, determine the output of the system. Assume that the system is initially relaxed. [10]
> 
> (b) An insulating material specimen is connected to arm AB of a Schering bridge. The arm BC has a non-inductive resistance $R_{2}$ of $140\,\Omega$ and arm CD has a non-inductive resistance $R_{4}$ of $208\,\Omega$ in parallel with a capacitor $C_{4}$ of $0\cdot5\,\mu\text{F}$ (loss-free). The arm DA has a loss-free capacitor $C_{3}$ of $150\times10^{-6}\,\mu\text{F}$. If the bridge is supplied with 50 Hz a.c. voltage connected between terminals A and C, then draw a neat circuit diagram of the bridge and derive the balance condition of the bridge, and calculate the parameters $C_{1}$, $r_{1}$ of the specimen and its loss angle $(\delta)$. [10]
> 
> (c) Show that the fault current for a single line to ground fault at the terminals of an alternator with solidly grounded neutral is more than that for symmetrical three-phase short circuit. The alternator has sequence reactances $X_{1}$, $X_{2}$ and $X_{0}$ such that $X_{1}=X_{2}\gg X_{0}$. [10]
> 
> (d) In a 220 kV system, the reactance and capacitance up to the location of circuit breaker is $8\,\Omega$ and $0\cdot025\,\mu\text{F}$ respectively. A resistance of $600\,\Omega$ is connected across the contacts of the circuit breaker. Determine the following:
> (i) Natural frequency of oscillation
> (ii) Frequency of damped oscillation
> (iii) Critical value of resistance which will give no transient oscillation
> (iv) The value of resistance which will give frequency of damped oscillation, one-fourth of the natural frequency of oscillation [10]
> 
> (e) (i) Write down Hamming bound condition for code $C(n,k)$ of size M in $GF(q)$, which can correct t errors.
> (ii) Explain perfect code using Hamming bound condition in GF(2).
> (iii) Check whether n-repetition code (for odd value of n) is perfect code or not. [10]

---

### [EE2-2020-Q6] Cascaded System State-Space Representation, Controllability and Observability · Per-Unit Representation & Transmission-Line Sending-End Voltage, 8085 Program Analysis

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** State-variable representation and analysis of control systems.
- **Directive:** Obtain
- **Theme (primary):** Cascaded System State-Space Representation, Controllability and Observability
- **Theme (secondary):** Per-Unit Representation & Transmission-Line Sending-End Voltage, 8085 Program Analysis
- **Repeat cluster:** RC11 (State-Variable/State-Space Analysis)
- **Has figure:** yes

> (a) Two first-order systems are connected in cascade as shown in the figure below. Obtain the state-space representation of the system. Also check the controllability and observability of the system. u is the input to the system and y is the output. [20]
> 
> **Figure ID:** FIG-EE2-2020-Q6a
> **Circuit description (netlist form):** Cascaded block diagram where input signal $u$ feeds into a first block with transfer function $\frac{s-1}{s+1}$, whose output enters a second cascaded block with transfer function $\frac{1}{s+2}$, producing the final system output $y$.
> **Symbolic form:** $Y(s) = \frac{s-1}{(s+1)(s+2)} U(s)$
> 
> (b) (i) What are the advantages of per unit representation?
> (ii) Using the nominal method, find the sending-end voltage and voltage regulation of a 250 km, 3-phase, 50 Hz transmission line delivering 25 MVA at 0.8 lagging power factor to a balanced load at 132 kV. The line conductors are spaced equilaterally 3 m apart. The conductor resistance is $0\cdot11\,\Omega/\text{km}$ and its effective diameter is 1.6 cm. Neglect leakance. [20]
> 
> (c) (i) For an 8085 microprocessor program, the instructions are as follows:
> 
> | Opcode | Operand |
> | :--- | :--- |
> | MVI | B, 91H |
> | MVI | C, A8H |
> | MOV | A, B |
> | ORA | C |
> | OUT | Port 1 |
> | HLT | |
> 
> Determine the output at Port 1, with the explanation of each statement.
> 
> (ii) For an 8085 microprocessor program given below
> 
> | Label | Opcode | Operand |
> | :--- | :--- | :--- |
> | Loop: | MVI | B, 64H |
> | | NOP | |
> | | DCR | B |
> | | JNZ | Loop |
> 
> find the number of times the loop will be executed. [10]

---

### [EE2-2020-Q7] LVDT Working Principle and Characteristics · Load-Flow Analysis, Ybus Advantages, Economic-Dispatch Penalty Factor & Lag-Network Input Determination

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Transducers: thermocouple, thermistor, LVDT, strain-guage, piezo-electric crystal.
- **Directive:** Explain
- **Theme (primary):** LVDT Working Principle and Characteristics
- **Theme (secondary):** Load-Flow Analysis, Ybus Advantages, Economic-Dispatch Penalty Factor & Lag-Network Input Determination
- **Repeat cluster:** RC10 (Transducer Characteristics (LVDT/Strain Gauge/Capacitive/Piezo))
- **Has figure:** no

> (a) With the help of a neat diagram, explain the working principle and characteristics of a linear variable differential transformer (LVDT). Why is the frequency of excitation in primary winding kept very high as compared to frequency of the signal detected? Write three advantages and disadvantages of LVDT also. [20]
> 
> (b) (i) What informations are obtained from load flow analysis? Explain the necessity of load flow studies.
> (ii) Explain the advantages of using bus admittance matrix, $Y_{bus}$ in load flow analysis.
> (iii) A power system has two generating plants and the power is being dispatched economically with $P_{1}=150\text{ MW}$ and $P_{2}=275\text{ MW}$. The loss coefficients are
> $B_{11}=0\cdot10\times10^{-2}\text{ MW}^{-1}$
> $B_{12}=-0\cdot10\times10^{-3}\text{ MW}^{-1}$
> $B_{22}=0\cdot13\times10^{-2}\text{ MW}^{-1}$
> To raise the total load on the system by 1 MW will cost an additional 200 per hour. Find the penalty factor for Plant 1 and the additional cost per hour to increase the output of Plant 1 by 1 MW. [20]
> 
> (c) A sinusoidal voltage $v_{i}(t)$ is applied to the lag network shown in the figure below. $v_{i}(t)$ is adjusted to produce a sinusoidal steady-state output voltage $v_{o}(t)=2\sin(\omega t+45^{\circ})\text{ volts}$. If $\omega=1\text{ rad/sec}$, determine the input voltage $v_{i}(t)$. [10]
> 
> **Figure ID:** FIG-EE2-2020-Q7c
> **Circuit description (netlist form):** A lag network with input voltage $v_i(t)$ connected between input terminal node 1 and reference ground node 0. A $4\,\Omega$ resistor connects node 1 to node 2. Connected in series between node 2 and node 0 are a $2\,\Omega$ resistor and a $0.5\text{ F}$ capacitor. The output voltage $v_o(t)$ is taken across node 2 and node 0.
> **Symbolic form:** $\frac{V_o(s)}{V_i(s)} = \frac{s+1}{3s+1}$

---

### [EE2-2020-Q8] Bode Plot Analysis with Transportation Lag (Time Delay) · GF(8) Field Construction, BCH Code Design & Cable Grading Methods

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Bode Plot Analysis with Transportation Lag (Time Delay)
- **Theme (secondary):** GF(8) Field Construction, BCH Code Design & Cable Grading Methods
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> (a) The open-loop transfer function of a unity feedback system is given by $G(s)H(s)=e^{-Ts}G_{1}(s)$, where $G_{1}(s)$ is a minimum phase system. The approximate Bode magnitude plot of the open-loop transfer function, which is shown in the figure below, crosses the 0 dB line at $\omega=2\cdot8\text{ rad/sec}$. If the phase margin of the system is $-12\cdot17^{\circ}$, determine the transportation lag T. [20]
> 
> **Figure ID:** FIG-EE2-2020-Q8a
> **Circuit description (netlist form):** Asymptotic Bode magnitude plot displaying magnitude in dB versus angular frequency in rad/sec. At $\omega = 0.05\text{ rad/sec}$, the magnitude is $40\text{ dB}$ with an initial slope of $-20\text{ dB/decade}$. Corner frequencies occur at $\omega = 2\text{ rad/sec}$ (where slope changes to $-40\text{ dB/decade}$) and at $\omega = 10\text{ rad/sec}$ (where slope changes to $-60\text{ dB/decade}$).
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) Consider the primitive polynomial $p(x)=x^{3}+x+1$ over GF(2). Construct GF(8) field using the given primitive polynomial.
> (ii) Find the minimal polynomial for the primitive element $\alpha$.
> (iii) Find the BCH code of length $n=15$ which can correct at least one error. [20]
> 
> (c) What is grading of cables? What are the different methods of grading? What are its limitations? [10]

---
