# PAPER II

## SECTION A

### [EE2-2016-Q1] Measurement Uncertainty in a Resistive Power Calculation · Transformer Tap-Changer Reactive Power, 8085 I/O Comparison, Sampling & Bode-Based Oscillation Condition

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements.
- **Directive:** Compute
- **Theme (primary):** Measurement Uncertainty in a Resistive Power Calculation
- **Theme (secondary):** Transformer Tap-Changer Reactive Power, 8085 I/O Comparison, Sampling & Bode-Based Oscillation Condition
- **Repeat cluster:** RC07 (Bridge Measurements & Error Analysis)
- **Has figure:** no

> Answer all of the following:
> 
> (a) An $820\ \Omega$ resistance with an accuracy of $\pm 10\%$ carries a current of 10 mA. The current was measured by an analog meter of 25 mA range with an accuracy of $\pm 2\%$ of full scale. Compute the power dissipated in the resistor and determine the accuracy of the result. [10]
> 
> (b) Two sub-stations are connected by two lines in parallel with negligible impedance, but each containing a tap-changing transformer of reactance 0.18 p.u. on the basis of its rating of 200 MVA. Find the net absorption of reactive power when the transformer taps are set to $1:1\cdot1$ and $1:0\cdot9$ respectively. Assume p.u. voltages to be equal at the two ends and also at the sub-stations. [10]
> 
> (c) Compare memory mapped I/O (Input/Output) with peripheral mapped I/O for 8085 microprocessor. [10]
> 
> (d) What do you mean by aliasing? How can aliasing be removed ? State and explain Shannon's sampling theorem. [10]
> 
> (e) (i) The open loop transfer function of a unity negative feedback control system is given by
> $$G(s)=\frac{K}{(s+2)(s+4)(s^{2}+6s+25)}.$$
> For what value of K, will the system work as an oscillator in its closed loop form? [5]
> 
> (ii) Identify the relevant layers of the ISO/OSI model to which the following protocols belong :
> SQL, HTTPS, ISDN, PPP, NFS, IP, RPC, TELNET, HDLC, X Windows [5]

---

### [EE2-2016-Q2] Second-Order Feedback System Transient Response Analysis · Economic Load Dispatch with Transmission Loss & Numerical Protection Principles

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** LTI systems: time-domain and transform-domain analysis.
- **Directive:** Find
- **Theme (primary):** Second-Order Feedback System Transient Response Analysis
- **Theme (secondary):** Economic Load Dispatch with Transmission Loss & Numerical Protection Principles
- **Repeat cluster:** none
- **Has figure:** yes

> (a) (i) Figure 2(a) shows the block diagram of a control system. Find its characteristic equation.
> (ii) Calculate its damping factor and undamped natural frequency for $K=10$.
> (iii) What should be the value of K for critical damping?
> (iv) For $K=10$, find the expression for $c(t)$ and obtain the time at which the first overshoot occurs. Also calculate the peak overshoot magnitude. [20]
> 
> **Figure ID:** FIG-EE2-2016-Q2a
> **Circuit description (netlist form):** Closed-loop control system block diagram with reference input $R(s)$ entering a primary summing junction with negative feedback from output $C(s)$. The error signal is fed into a secondary summing junction with a negative minor feedback loop of transfer function $0.25s$ tapped from output $C(s)$. The combined signal drives the forward path transfer function block $\frac{K}{s(s+2)}$ to produce output $C(s)$.
> **Symbolic form:** $\frac{C(s)}{R(s)} = \frac{K}{s^2 + (2 + 0.25K)s + K}$
> 
> (b) A system consists of two plants connected by a transmission line and a load at power plant 2 as shown in Figure 2(b). Data for the loss equation consists of the information that 200 MW transmitted from plant 1 to the load results in a transmission loss of 20 MW. Find the optimum generation schedule considering transmission losses to supply a load of 204.41 MW. Also evaluate the amount of financial loss that may be incurred if at the time of scheduling transmission losses are not co-ordinated. Assume that the incremental fuel cost characteristics of plant 1 and plant 2 are given by
> $$\frac{dF_{1}}{dP_{G_{1}}}=0.025P_{G_{1}}+14\text{ Rs./MWh}$$
> $$\frac{dF_{2}}{dP_{G_{2}}}=0.05P_{G_{2}}+16\text{ Rs./MWh}$$ [20]
> 
> **Figure ID:** FIG-EE2-2016-Q2b
> **Circuit description (netlist form):** Power system schematic with Plant 1 (generator G1 at bus 1) transmitting power over a transmission line to Plant 2 (generator G2 at bus 2), where a total electrical load is connected at bus 2.
> **Symbolic form:** not derivable from figure.
> 
> (c) Describe the principle of numerical protection. How is this method of protection different from conventional methods? [10]

---

### [EE2-2016-Q3] Root-Locus Construction for a Fourth-Order Characteristic Equation · Generator Neutral Grounding Reactance/Resistance & Circuit-Breaker Testing Methods

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Draw
- **Theme (primary):** Root-Locus Construction for a Fourth-Order Characteristic Equation
- **Theme (secondary):** Generator Neutral Grounding Reactance/Resistance & Circuit-Breaker Testing Methods
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> (a) Consider a control system with characteristic equation
> $$s(s+4)(s^{2}+2s+2)+K(s+1)=0.$$
> Draw complete root loci labelling all important values. Find the angles of asymptotes and the intercept of asymptotes. [20]
> 
> (b) A three-phase generator rated 11 kV, 20 MVA has a solidly grounded neutral. Its positive, negative and zero sequence reactances are 60%, 25% and 15% respectively.
> (i) Calculate the value of reactance that should be placed in the generator neutral such that the current for single line-to-ground fault does not exceed the rated current.
> (ii) What value of the resistance in the neutral will serve the same purpose? [20]
> 
> (c) What are the different methods of testing of circuit breakers ? Discuss their merits and demerits. Which method is more suitable for testing the circuit breakers of large capacity? [10]

---

### [EE2-2016-Q4] Linear Potentiometer Loading Non-Linearity Derivation · 8085 SIM Instruction, Hamming Distance & Delta Modulation vs DPCM

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements.
- **Directive:** Show
- **Theme (primary):** Linear Potentiometer Loading Non-Linearity Derivation
- **Theme (secondary):** 8085 SIM Instruction, Hamming Distance & Delta Modulation vs DPCM
- **Repeat cluster:** RC07 (Bridge Measurements & Error Analysis)
- **Has figure:** no

> (a) Show that the maximum non-linearity on account of loading of a linear potentiometer can be expressed as
> $$\frac{400}{27}\frac{R_{p}}{R_{m}}\%$$
> of f.s.d. for
> $$\frac{R_{p}}{R_{m}}\ll1.$$ [20]
> 
> (b) Write down the purpose of each bit in SIM (Set Interrupt Mark) instruction. Give three different functions of SIM instruction. [10]
> 
> (c) (i) Discuss the concept of 'Hamming distance'. How is the minimum Hamming distance between a set of code words related to the error detection and error correction properties of the code?
> Find the correct 4-bit messages from the following two Hamming codes, assuming at most a single error has occurred :
> $$C_{1}=0110101$$
> $$C_{2}=1011001$$ [10]
> 
> (ii) Explain Delta Modulation, comparing it with Differential Pulse Code Modulation. Discuss how the choice of step size in Delta modulator affects slope overload distortion and granular noise. [10]

---

## SECTION B

### [EE2-2016-Q5] PID Controller Design for Specified Closed-Loop Pole Locations · Fast Decoupled Load Flow Matrices, 8085 Assembly, Ferroresonant Breaker Transient & Accelerometer Transducer Range

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Proportional, PI, PID controllers.
- **Directive:** Find
- **Theme (primary):** PID Controller Design for Specified Closed-Loop Pole Locations
- **Theme (secondary):** Fast Decoupled Load Flow Matrices, 8085 Assembly, Ferroresonant Breaker Transient & Accelerometer Transducer Range
- **Repeat cluster:** RC21 (PID/Compensator Controller Design)
- **Has figure:** yes

> Answer all of the following:
> 
> (a) (i) Explain with proper transfer function a standard PID controller. Explain why derivative term is not employed alone. [5]
> 
> (ii) The open loop transfer function of a system is given by
> $$G(s)=\frac{5}{s(s+2)}.$$
> It is desired to locate the poles of this transfer function at -8 and $-3\pm4j$ by using a suitable PID controller. Find the suitable gains needed by the PID controller to achieve this task. [5]
> 
> (b) Form $[B']$ and $[B'']$ matrices used in Fast Decoupled Load Flow (FDLF) for the power system shown in Figure 5(b) and line data given in Table I. [10]
> 
> **Figure ID:** FIG-EE2-2016-Q5b
> **Circuit description (netlist form):** 5-bus interconnected power system network. Bus 1 is connected to a generator. Bus 2 is connected to a generator and a local load. Bus 3, Bus 4, and Bus 5 are load buses with outgoing arrows. Transmission line branches interconnect buses (1-2), (2-3), (3-4), (4-5), (1-5), and an internal tie line between (3-5).
> **Symbolic form:** not derivable from figure.
> 
> | Bus Code $(i\text{-}j)$ | Impedance $(z_{ij})$ (in p.u.) | Half-line Charging Admittance (in p.u.) |
> | :--- | :--- | :--- |
> | 1-2 | $(0\cdot02+j\ 0\cdot04)$ | $j\ 0\cdot020$ |
> | 2-3 | $(0\cdot04+j\ 0\cdot20)$ | $j\ 0\cdot020$ |
> | 3-5 | $(0\cdot15+j\ 0\cdot40)$ | $j\ 0\cdot025$ |
> | 3-4 | $(0\cdot02+j\ 0\cdot06)$ | $j\ 0\cdot010$ |
> | 4-5 | $(0\cdot02+j\ 0\cdot04)$ | $j\ 0\cdot010$ |
> | 1-5 | $(0\cdot08+j\ 0\cdot20)$ | $j\ 0\cdot020$ |
> 
> Table I: Line data
> 
> (c) Write down the ALP (Assembly Language Program) to exchange 10H data bytes stored from memory location 2450H with data bytes stored from memory locations 2480H onwards. [10]
> 
> (d) A circuit breaker interrupts the magnetising current of a 100 MVA transformer at 220 kV. The magnetising current of the transformer is 5% of the full load current. Determine the maximum voltage which may appear across the gap of the breaker when the magnetising current is interrupted at 53% of its peak value. The stray capacitance is $2500\ \mu\text{F}$ and the inductance is 30 H. [10]
> 
> (e) (i) An accelerometer has an input range of $0-100\text{ m/s}^{2}$. It has a mass of 10 g and works on a frequency of 10 Hz. Find the range for the displacement transducer used to measure the displacement of the accelerometer. [5]
> 
> (ii) 1. State and explain Nyquist criterion.
> 2. An information signal $x(t)=5\cos(2000\pi t)\cos(5000\pi t)$ is sampled. Calculate the minimum sampling rate that will be needed to recover the signal back from its samples. [5]

---

### [EE2-2016-Q6] Ramp-Type ADC Operation and Clock-Pulse Count Calculation · LVDT Characteristics & Sensitivity, Cyclic Code Equivalence & OSI vs TCP/IP

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Explain
- **Theme (primary):** Ramp-Type ADC Operation and Clock-Pulse Count Calculation
- **Theme (secondary):** LVDT Characteristics & Sensitivity, Cyclic Code Equivalence & OSI vs TCP/IP
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** no

> (a) With the help of a neat diagram, explain the functioning of a Ramp type Analog-to-Digital Converter. A Ramp type ADC makes use of a 1 MHz clock generator and a ramp voltage that increases from $0-1\cdot25\text{ V}$ in 125 ms. Find the number of clock pulses counted into the register for an input of 0.75 V. [20]
> 
> (b) (i) With the help of a neat diagram, explain the working of an LVDT. Give its characteristics, advantages and applications. Explain the role of phase sensitive detector used for signal conditioning of LVDT. [15]
> 
> (ii) An LVDT is connected to a 10 V voltmeter through an amplifier of gain 100. An output of 2 mV appears across the terminals of the LVDT when the core crosses a distance of 0.5 mm. Find the sensitivity of the LVDT and that of the whole set-up. The used voltmeter has 100 divisions and $\frac{1}{5}\text{th}$ of a division can be read accurately. Find the resolution of the instrument in mm. [5]
> 
> (c) (i) Show that the (7, 4) cyclic codes generated by the two polynomials
> $$g_{1}(P)=P^{3}+P^{2}+1\quad\text{and}\quad g_{2}(P)=P^{3}+P+1$$
> are equivalent. Find the codes for the four messages :
> (0011), (0101), (1010), (1101) [10]
> 
> (ii) Discuss and differentiate between ISO/OSI and TCP/IP. Explain how the functions of each of the seven layers of ISO/OSI are carried out by TCP/IP. [10]

---

### [EE2-2016-Q7] CRO Dual-Axis Waveform Display from Triangular and Sawtooth Inputs · 8085 Instruction Decoding/Execution & Huffman Source Coding

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Sketch
- **Theme (primary):** CRO Dual-Axis Waveform Display from Triangular and Sawtooth Inputs
- **Theme (secondary):** 8085 Instruction Decoding/Execution & Huffman Source Coding
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** no

> (a) A 500 Hz triangular wave with a peak amplitude of 40 V is applied to the vertical deflecting plates of a CRO having a vertical deflection sensitivity of $0\cdot1\text{ cm/V}.$ Another 250 Hz sawtooth wave of 50 V is applied to the horizontal plates having a horizontal deflection sensitivity of $0\cdot08\text{ cm/V}.$ Assuming the two inputs are synchronized, sketch the waveform displayed on the CRO. [10]
> 
> (b) (i) Assume that the accumulator contains data byte 82H and the instruction MOV C, A (4FH) is fetched. List the steps in decoding and executing the instruction. [10]
> 
> (ii) Describe the function of each of the following mnemonics. How many cycles do each of them require for execution and which are the flags affected? Explain.
> 1. DAD (Double Add)
> 2. CMC (Complement Carry)
> 3. LHLD (Load H-L Register Pair Direct)
> 4. ORI (OR Immediate) [10]
> 
> (c) Eight messages are generated by a source with the following probabilities:
> 
> | Message $m_{i}$ | $m_{0}$ | $m_{1}$ | $m_{2}$ | $m_{3}$ | $m_{4}$ | $m_{5}$ | $m_{6}$ | $m_{7}$ |
> | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> | Probability $p_{i}$ | $0\cdot02$ | $0\cdot04$ | $0\cdot07$ | $0\cdot10$ | $0\cdot13$ | $0\cdot18$ | $0\cdot22$ | $0\cdot24$ |
> 
> (i) Use Huffman scheme to code these messages.
> (ii) Explain and illustrate the prefix property of the code.
> (iii) Determine the average number of bits per message (1) with the Huffman coding, and (2) with uniform coding assuming the messages to be equiprobable. Also find the information content (entropy) in the message and hence efficiency of the Huffman coding. [20]

---

### [EE2-2016-Q8] Control System Performance Indices (Rise Time, ISE, ITSE, IAE, ITAE) · State-Space to Transfer Function Conversion, SF6 Circuit Breaker & Load-Flow Solution Types

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** LTI systems: time-domain and transform-domain analysis.
- **Directive:** Explain
- **Theme (primary):** Control System Performance Indices (Rise Time, ISE, ITSE, IAE, ITAE)
- **Theme (secondary):** State-Space to Transfer Function Conversion, SF6 Circuit Breaker & Load-Flow Solution Types
- **Repeat cluster:** none
- **Has figure:** no

> (a) (i) Explain the following terms in reference to performance indices in a control system:
> 1. Rise time
> 2. Integral square error
> 3. Integral of time multiplied square error
> 4. Integral absolute error
> 5. Integral of time multiplied absolute error [10]
> 
> (ii) Consider the system described by
> $$\begin{bmatrix}\dot{x}_{1}\\ \dot{x}_{2}\end{bmatrix}=\begin{bmatrix}-4 & -1\\ 3 & -1\end{bmatrix}\begin{bmatrix}x_{1}\\ x_{2}\end{bmatrix}+\begin{bmatrix}1\\ 1\end{bmatrix}u,$$
> $$y=\begin{bmatrix}1 & 0\end{bmatrix}\begin{bmatrix}x_{1}\\ x_{2}\end{bmatrix}.$$
> Obtain the transfer function of the system. [10]
> 
> (b) Discuss the operating principle of $\text{SF}_{6}$ circuit breaker. What are its advantages over other types of circuit breakers? In practice, for what voltage range is it recommended ? [20]
> 
> (c) What is Load Flow solution? What do you understand by (i) Adjustable Load Flow, and (ii) Unadjustable Load Flow? Which method will provide the accurate solution? [10]

---
