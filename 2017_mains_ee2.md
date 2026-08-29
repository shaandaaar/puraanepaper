## SECTION 'A'

### [EE2-2017-Q1] Root-Locus Break-Away and Break-In Points · Delta-Modulation Step Size, 8085 Interrupt/Memory Sizing, Four-Terminal Resistance & Biased Differential Relay

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Find
- **Theme (primary):** Root-Locus Break-Away and Break-In Points
- **Theme (secondary):** Delta-Modulation Step Size, 8085 Interrupt/Memory Sizing, Four-Terminal Resistance & Biased Differential Relay
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> 1. (a) For the open-loop transfer function
> $$G(s)H(s)=\frac{K(s-3)(s-5)}{(s+1)(s+2)}$$
> find out the break-away and break-in points, if any, for the root locus. Also specify whether the gain is maximum or minimum at these points. [10]
>
> (b) A delta modulation system is designed to accommodate a bandlimited analog signal with maximum frequency of 5000 Hz. The sampling rate is five times the Nyquist rate. A signal $x(t)=\sin(2000\pi t)$ is applied to this system.
> Determine:
> (i) the minimum step size required to process the signal without slope overload distortion and
> (ii) maximum signal-to-quantization noise ratio of the system. [10]
>
> (c) (i) Describe the two ways in which the interrupt RST 7.5 in 8085 micro-processor can be disabled: [5]
> (ii) Calculate the number of memory chips needed to design 8k-bytes memory for an 8085 microprocessor. The memory chip size is $1024\times1$. [5]
>
> (d) (i) Why low resistances are usually constructed as four-terminal resistances? [5]
> (ii) How can surface resistivity of insulating material be measured using direct deflection method? [5]
>
> (e) Explain the principle of percentage biased differential relay with harmonic restraint. [10]

---

### [EE2-2017-Q2] Nyquist Plot for an Unstable Open-Loop System · 8085 DMA Types & Per-Unit System Voltage Calculation

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Sketch
- **Theme (primary):** Nyquist Plot for an Unstable Open-Loop System
- **Theme (secondary):** 8085 DMA Types & Per-Unit System Voltage Calculation
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> 2. (a) For a given unstable open-loop system whose transfer function is
> $$G(s)H(s)=\frac{s+3}{s(s-1)}$$
> sketch the Nyquist Contour and Nyquist Plot. Comment on the stability of the closed-loop system. [20]
>
> (b) What is the difference between cycle stealing DMA and interleaved DMA in 8085 microprocessor? What is meant by block transfer DMA? [15]
>
> (c)
> **Figure ID:** FIG-EE2-2017-Q2c
> **Circuit description (netlist form):** Single-phase power system divided into three sections: Part A, Part B, and Part C. Part A contains an AC source $V_S$ feeding the primary of single-phase Transformer 1 ($10\text{ kVA}$, $100 : 400\text{ V}$, reactance $X = 0\cdot1\text{ p.u.}$). Part B is a two-wire transmission link connecting the secondary of Transformer 1 to the primary of single-phase Transformer 2 ($10\text{ kVA}$, $400 : 200\text{ V}$, reactance $X = 0\cdot15\text{ p.u.}$), with an observation node D on the upper conductor. Part C connects the secondary of Transformer 2 across a $10\text{ kVA}$ resistive load operating at $200\text{ V}$.
> **Symbolic form:** not derivable from figure.
>
> In a system shown in the above figure, two single phase transformers supply a 10 kVA resistance load at 200 V. Show that the p.u. load is the same for each part of the circuit (like part A, B and C) and calculate the voltage at point D. [15]

---

### [EE2-2017-Q3] Iterative Load-Flow Computation for a Two-Bus System · Huffman Coding for Source Extension & Energy-Meter Calibration Error

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation;
- **Directive:** Compute
- **Theme (primary):** Iterative Load-Flow Computation for a Two-Bus System
- **Theme (secondary):** Huffman Coding for Source Extension & Energy-Meter Calibration Error
- **Repeat cluster:** RC32 (Transmission Line & Economic Power-System Operation)
- **Has figure:** yes

> 3. (a)
> **Figure ID:** FIG-EE2-2017-Q3a
> **Circuit description (netlist form):** Single-line diagram of a two-bus power system. Bus 1 has bus voltage $V_1$ with net injected power $P_1 \& Q_1$. Bus 2 has bus voltage $V_2$ supplying load demand $P_2 \& Q_2$. A transmission line with series per-unit impedance $Z_l$ connects Bus 1 to Bus 2 and carries current $I$ flowing from Bus 1 to Bus 2.
> **Symbolic form:** $I = \frac{V_1 - V_2}{Z_l}$, $P_2 - jQ_2 = V_2^* I$
>
> In the above figure, $V_{1}=1\angle0^{\circ}$, $Z_{l}=(0\cdot05+j\,0\cdot02)\text{ pu}$ and $P_{2}+jQ_{2}=(1\cdot0+j\,0\cdot6)\text{ pu}$. Using load flow study iteratively compute $V_{2}$ and $P_{1}+jQ_{1}$. Also determine the reactive power that must be injected to bus 2 to maintain $|V_{1}|=|V_{2}|=1\cdot0\text{ pu}$. [20]
>
> (b) A discrete memoryless source is emitting the symbols $x_{1}$, $x_{2}$ and $x_{3}$ with probabilities, respectively, 0.2, 0.45 and 0.35. Construct optimal binary Huffman code for the second extension of the source and calculate the coding efficiency. [15]
>
> (c) A single phase, 240 V, 20 A, induction type watt-hour meter is working correctly. When tested at half load, rated voltage, and unity power factor, the disc rotates at 32 rpm. Determine the meter constant of the meter.
> Then, due to the alteration of the lag adjustment of the meter, the meter reads with $-6\cdot7\%$ error at 0.8 p.f. lagging. What is the new phase angle between the supply voltage and the pressure coil flux because of this incorrect lag adjustment? [15]

---

### [EE2-2017-Q4] Critical Clearing Angle for a Single-Machine-Infinite-Bus System · Steady-State Error Coefficients & Schering Bridge Specimen Measurement

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Concepts of system stability: swing curves and equal area criterion.
- **Directive:** Derive
- **Theme (primary):** Critical Clearing Angle for a Single-Machine-Infinite-Bus System
- **Theme (secondary):** Steady-State Error Coefficients & Schering Bridge Specimen Measurement
- **Repeat cluster:** RC58 (Power System Transient Stability (Critical Clearing Angle))
- **Has figure:** no

> 4. (a) Derive an expression for the critical clearing angle for a power system consisting of a single machine supplying to an infinite bus, for a sudden load increment. [20]
>
> (b) Consider a unity feedback system having transfer function
> $$\frac{C(s)}{R(s)}=\frac{a}{s^{2}+bs+a}$$
> Determine the open-loop transfer function and steady state error coefficients. [15]
>
> (c) A Schering bridge, used to test a specimen, has the following bridge arms: arm ab contains the unknown capacitance $(C_{1})$ whose loss part is represented by a series resistance $(r_{1})$, arm bc contains a non-inductive resistance $(R_{3})$ of $315\ \Omega$, arm cd contains a variable capacitor $(C_{4})$ in parallel with a variable non-inductive resistance $(R_{4})$ and arm da contains a standard capacitor $(C_{2})$ of 150 pF. The supply is connected between a and c and the detector is connected between b and d. The specimen is tested at a frequency of 50 Hz, it is having a thickness of 6.3 mm and it is tested between electrodes each having a dimension of $0\cdot15\text{ m}\times0\cdot18\text{ m}$. At balance, $C_{4}=0\cdot375\ \mu\text{F}$ and $R_{4}=423\ \Omega$. Find the capacitance, dissipation factor and relative permittivity of the specimen. Given Permittivity of free space $=8\cdot854\times10^{-12}\text{ F/m}$. [15]

---

## SECTION 'B'

### [EE2-2017-Q5] Generator Short-Circuit Currents (Sustained and Initial Symmetrical) · 8085 INTR Timing, Wattmeter Compensating Coil, Information Rate & Proportional Controller Gain

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** symmetrical components, analysis of symmetrical and unsymmetrical faults.
- **Directive:** Find
- **Theme (primary):** Generator Short-Circuit Currents (Sustained and Initial Symmetrical)
- **Theme (secondary):** 8085 INTR Timing, Wattmeter Compensating Coil, Information Rate & Proportional Controller Gain
- **Repeat cluster:** RC29 (Power System Fault Analysis (Symmetrical Components))
- **Has figure:** no

> 5. (a) A 20 MVA, 6.6 kV generator, with $X_{d}^{\prime\prime}=10\%$, $X_{d}^{\prime}=20\%$ and $X_{d}=100\%$ is connected through a circuit breaker to a transformer. It is operating on no load when a short circuit occurs between breaker and transformer.
> Find (i) sustained short circuit current through breaker.
> (ii) initial symmetrical rms short circuit current. [10]
>
> (b) (i) How long can the INTR pulse stay high in 8085 microprocessor? [5]
> (ii) What is a jump-on-reset circuit in a processor? [5]
>
> (c) How a compensating coil can be utilized in reducing connection errors in an electro-dynamometer type wattmeter? [10]
>
> (d) An information source is modelled as a bandlimited process with a bandwidth of 6000 Hz. This process is sampled at a rate higher than the Nyquist rate to provide a guard band of 2000 Hz. The resulting samples takes one of the value in the set $\{-4, -3, -1, 2, 4, 7\}$ with corresponding probabilities $\{0\cdot2, 0\cdot1, 0\cdot15, 0\cdot05, 0\cdot3, 0\cdot2\}$. Determine the rate of information of the source. [10]
>
> (e)
> **Figure ID:** FIG-EE2-2017-Q5e
> **Circuit description (netlist form):** Closed-loop control block diagram. Reference input $R(s)$ enters a summing junction with negative feedback. The error signal is multiplied by proportional controller gain $K$, which drives a forward plant with transfer function $\frac{1}{s(s+2)}$ to yield output $C(s)$. The output $C(s)$ is fed back directly via unity negative feedback to the summing junction.
> **Symbolic form:** $\frac{C(s)}{R(s)}=\frac{K}{s^{2}+2s+K}$
>
> For $r(t)=0\cdot9t$, it is required that the steady state error should be less than 0.05. Determine the value of gain (K) of proportional controller for the system shown above. [10]

---

### [EE2-2017-Q6] Convolutional Encoder Construction (State and Trellis Diagrams) · P/I Controller Response to a Step Error & Transmission-Line Maximum-Power X/R Ratio

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Error control coding: error detection and correction, linear block codes, convolation codes.
- **Directive:** Construct
- **Theme (primary):** Convolutional Encoder Construction (State and Trellis Diagrams)
- **Theme (secondary):** P/I Controller Response to a Step Error & Transmission-Line Maximum-Power X/R Ratio
- **Repeat cluster:** RC31 (Error-Control Coding (Block Codes, CRC, Hamming))
- **Has figure:** yes

> 6. (a) A convolutional code is described by the following generator sequences:
> $$g_{1}=[\begin{matrix}1&0&0\end{matrix}]$$
> $$g_{2}=[\begin{matrix}1&0&1\end{matrix}]$$
> $$g_{3}=[\begin{matrix}1&1&1\end{matrix}]$$
> (i) Construct the encoder circuit corresponding to this code.
> (ii) Draw the state diagram for this code.
> (iii) Draw the trellis diagram for a message sequence length of 5 bits.
> (iv) Determine the encoded sequence for the message sequence 10111. [20]
>
> (b)
> **Figure ID:** FIG-EE2-2017-Q6b
> **Circuit description (netlist form):** Plot of error signal in Volts versus time in seconds. The error voltage is $0\text{ V}$ from $t = 0\text{ s}$ to $t = 2\text{ s}$. At $t = 2\text{ s}$, it step-transitions to a constant level of $5\text{ V}$ until $t = 10\text{ s}$. At $t = 10\text{ s}$, it steps down to $0\text{ V}$.
> **Symbolic form:** $e(t) = 5[u(t-2) - u(t-10)]$
>
> The error signal as shown above is given to the controller. The initial controller output is zero. Draw the output of the controller if it is a
> (i) P controller with proportional gain $(K_{p})=10$
> (ii) I controller with integral gain $(K_{I})=2$ [15]
>
> (c) For a certain lagging power factor load, the sending end and receiving end voltages of a short transmission line of impedance $R+jX$ are equal. Prove that $\frac{X}{R}$ ratio is $\sqrt{3}$ for maximum power transmitted over the line under steady state condition. [15]

---

### [EE2-2017-Q7] Subtransient Fault Currents in Generator, Motor and Fault Branch · 8085 Stack Pointer/Nested Interrupts & Spectrum Analyzer Sensitivity

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** symmetrical components, analysis of symmetrical and unsymmetrical faults.
- **Directive:** Find
- **Theme (primary):** Subtransient Fault Currents in Generator, Motor and Fault Branch
- **Theme (secondary):** 8085 Stack Pointer/Nested Interrupts & Spectrum Analyzer Sensitivity
- **Repeat cluster:** RC29 (Power System Fault Analysis (Symmetrical Components))
- **Has figure:** no

> 7. (a) A synchronous generator and motor are rated 30,000 kVA, 13.2 kV, and both have subtransient reactances of 20%. The line connecting them has a reactance of 10% on the base of the machine ratings. The motor is drawing 20,000 kW at 0.8 power factor leading and a terminal voltage of 12.8 kV when a symmetrical three phase fault occurs at the motor terminal. Find the subtransient currents (i) in the generator, (ii) in the motor and (iii) in the fault by using the internal voltages of the machines. [20]
>
> (b) (i) In an 8085 microprocessor, what is the value of stack pointer after the following program is run?
>
> | | |
> |---|---|
> | MOV | SP, 07FFH |
> | PUSH | B |
> | CALL | Subroutine |
> | POP | B |
> | ADD | B |
> | PUSH | B |
> | HLT | |
>
> [5]
> (ii) Suppose that an 8085 microprocessor has received three interrupt requests in the following order: RST 7.5, RST 6.5 and RST 5.5. If these three interrupts are nested, to what depth does the stack penetrate if all registers within the CPU must be saved? Assume that the stack pointer initially points to location FFFFH. [10]
>
> (c) Explain in detail different types of frequency instabilities that cause difficulties in spectrum analyzers for display of narrow frequency ranges. A spectrum analyzer is designed using a 10-kHz, 3 dB filter and with a noise figure of 25 dB. What is the minimum detectable signal of this spectrum analyzer? What will be the power-level of the third-order intercept point, if this spectrum analyzer possesses a dynamic range of 86 dB? [15]

---

### [EE2-2017-Q8] State Model and State-Feedback Gain for Pole Placement · QPSK Signal-Space Diagram & Strain-Gauge Temperature Compensation

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** State-variable representation and analysis of control systems.
- **Directive:** Find
- **Theme (primary):** State Model and State-Feedback Gain for Pole Placement
- **Theme (secondary):** QPSK Signal-Space Diagram & Strain-Gauge Temperature Compensation
- **Repeat cluster:** RC11 (State-Variable/State-Space Analysis)
- **Has figure:** no

> 8. (a) A continuous system has transfer function
> $$\frac{C(s)}{R(s)}=\frac{3}{(s-2)(s+3)(s+4)}$$
> Find out the state model of the system. Find out the state feedback gain $K=[\begin{matrix}K_{1}&K_{2}&K_{3}\end{matrix}]$ such that the closed loop poles will be at -4, -3 and -2. [20]
>
> (b) Write down expression for the signal set and draw signal space diagram for coherent quadri-phase shift keying system. For the input binary sequence 11001001, sketch inphase and quadrature components of the modulated quadri-phase shift keying signal. [15]
>
> (c) (i) Why temperature compensation is needed in strain gauges? A four arm DC Wheatstone bridge is designed using a single active gauge. How can a dummy gauge be employed here to achieve temperature compensation? [10]
> (ii) A resistance wire strain gauge with nominal resistance $350\ \Omega$ and gauge factor 2 is fastened to a steel bar. The modulus of elasticity of steel is $2\cdot1\times10^{6}\text{ kg/cm}^{2}$. What is the stress applied to the steel bar if strain gauge resistance becomes $350\cdot52\ \Omega$? [5]

---
