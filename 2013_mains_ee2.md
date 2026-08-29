### [EE2-2013-Q1] Error Classification & Propagation in Parallel Current Measurement · Transmission-Line ABCD Constants, Microcomputer Architecture, Relay Terminology & Control-System Test Inputs

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements.
- **Directive:** Explain
- **Theme (primary):** Error Classification & Propagation in Parallel Current Measurement
- **Theme (secondary):** Transmission-Line ABCD Constants, Microcomputer Architecture, Relay Terminology & Control-System Test Inputs
- **Repeat cluster:** RC07 (Bridge Measurements & Error Analysis)
- **Has figure:** no

> (a) (i) Giving classification of errors in measurement, explain these errors giving suitable examples. Explain how systematic errors can be minimised. [5]
> 
> (ii) A circuit consists of two branches in parallel. The current in one branch is $I_{1}=10\pm 0.2\text{ A}$ and in other is $I_{2}=20\pm 0.5\text{ A}$. Determine the value of the total current $I=I_{1}+I_{2}$
> (i) considering the errors in $I_{1}$ and $I_{2}$ as limiting errors,
> (ii) considering the errors as standard deviations.
> Comment on the result. [5]
> 
> (b) A 3-phase 138-kV, transmission line is connected to a 49-MW load at a 0.85 lagging power factor. The line constants of the 80 km long line are $\overline{Z}=95\angle 78^{\circ}\ \Omega$ and $\overline{Y}=0.001\angle 90^{\circ}\text{ S}$. Using nominal-T circuit representation, compute:
> (i) The A, B, C and D constants of the line;
> (ii) Sending-end voltage;
> (iii) Sending-end current;
> (iv) Sending-end power factor; and
> (v) Efficiency of transmission. [10]
> 
> (c) (i) Draw the block diagram indicating the typical architecture of a microcomputer. Briefly discuss the salient features. [5]
> 
> (ii) How can square wave generation with a variable bit rate, be done using the microprocessor ? Output should be available on a chosen port, using bit '0'. [5]
> 
> (d) Define the terms given below:
> (i) Pick up value
> (ii) Reset time
> (iii) Operating time and
> (iv) Reset value
> for protective relays. [10]
> 
> (e) State and explain various test inputs in control systems. [10]

---

### [EE2-2013-Q2] Block-Diagram Reduction to Standard Feedback Form · IDMTL Overcurrent-Relay Timing & Newton–Raphson Load-Flow Formulation

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components.
- **Directive:** Reduce
- **Theme (primary):** Block-Diagram Reduction to Standard Feedback Form
- **Theme (secondary):** IDMTL Overcurrent-Relay Timing & Newton–Raphson Load-Flow Formulation
- **Repeat cluster:** RC12 (Control System Elements & Block-Diagram Modeling)
- **Has figure:** yes

> (a) Using the Block diagram simplification method reduce the block diagram of the following control system
> 
> **Figure ID:** FIG-EE2-2013-Q2a-1
> **Circuit description (netlist form):** Control system block diagram with input $R(s)$ entering a first summing junction with positive sign. The output of the first summing junction enters a second summing junction with positive sign. The output of the second summing junction passes to a gain block of $10$, which drives a block with transfer function $\frac{1}{s+1}$. The output of $\frac{1}{s+1}$ splits into three branches: (1) a feedback block with transfer function $s$ feeding back to the second summing junction with negative sign, (2) a forward path gain block of $10$ connecting to a third summing junction with positive sign, and (3) an integrator block $\frac{1}{s}$ connecting to the third summing junction with positive sign. The output of the third summing junction is $C(s)$, which is fed back with negative sign to the first summing junction.
> **Symbolic form:** not derivable from figure.
> 
> to a block diagram of the following type:
> 
> **Figure ID:** FIG-EE2-2013-Q2a-2
> **Circuit description (netlist form):** Single-loop feedback block diagram where reference input $R(s)$ enters a summing junction with positive sign. The error signal passes through forward transfer function block $G(s)$ to produce output $C(s)$. The output $C(s)$ feeds through feedback transfer function block $H(s)$ to the summing junction with negative sign.
> **Symbolic form:** $$\frac{C(s)}{R(s)} = \frac{G(s)}{1 + G(s)H(s)}$$
> 
> [20]
> 
> (b) Time-current characteristic of an induction-type overcurrent relay is:
> 
> | I (Multiples of pick-up) | 2 | 4 | 6 | 8 | 10 | 12 | 14 | 16 | 20 |
> |---|---|---|---|---|---|---|---|---|---|
> | T (Seconds) | 10 | 5.1 | 4 | 3.4 | 3 | 2.8 | 2.6 | 2.5 | 2.4 |
> 
> It is desired to determine the time of operation of 5-ampere relay having a current setting of 125% and TMS of 0.6 connected to a supply circuit through a C.T. ratio 400/5 ampere when the circuit carries a fault current of 4,000 amperes. [20]
> 
> (c) (i) Classify different types of buses for load flow study in power systems. [3]
> 
> (ii) Discuss formulation of Newton-Raphson method with mathematical details in polar co-ordinates. [7]

---

### [EE2-2013-Q3] Transfer-Function Determination from an Asymptotic Bode Plot · Power-Factor-Correction Capacitor Sizing & Restriking-Voltage (RRRV) Computation

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Transfer-Function Determination from an Asymptotic Bode Plot
- **Theme (secondary):** Power-Factor-Correction Capacitor Sizing & Restriking-Voltage (RRRV) Computation
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> (a) The asymptotic approximation of the variation of gain with frequency of a control system (Bode Plot) is shown below. Determine the transfer function of the system. [10]
> 
> **Figure ID:** FIG-EE2-2013-Q3a
> **Circuit description (netlist form):** Asymptotic Bode magnitude plot of gain in dB versus frequency $\omega$ on a logarithmic scale. The plot starts with a slope of $-6\text{ dB/octave}$ passing through $0\text{ dB}$ and reaching $-20\text{ dB}$ at $\omega = 1\text{ rad/s}$. From $\omega = 1$ to $\omega = 2$, the curve continues to a corner frequency at $\omega = 2$. Between $\omega = 2$ and $\omega = 10$, the slope is $0\text{ dB/octave}$ (horizontal segment). From $\omega = 10$ to $\omega = 50$, the slope is $-6\text{ dB/octave}$. From $\omega = 50$ to $\omega = 100$, the slope is $-12\text{ dB/octave}$. For frequencies above $\omega = 100$, the slope becomes $-6\text{ dB/octave}$.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) What are the main causes of low power factor and discuss measures by which low power factor can be avoided ? [10]
> 
> (ii) A consumer is taking a load of 20 kW at power factor 0.8 lagging. Find the rating of capacitor to raise the power factor to 0.95 lagging. [10]
> 
> (c) An 11-kV, 50-Hz generator was supplying power to a load when a three-phase fault occurred on the system. The inductive reactance and capacitance of the faulted section were 4.0 ohms and $0.01\ \mu\text{F}$ respectively, and the resistance was negligible. Compute (a) the active recovery voltage, (b) peak value of the restriking voltage, (c) the frequency of transient oscillatory voltage and (d) the average rate-of-rise of restriking voltage (RRRV) up to the first peak of oscillations. [20]

---

### [EE2-2013-Q4] Digital Frequency Meter & Wave-Analyser Operation · Memory Read/Write Timing Diagram & (7,4) Linear Block Code

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Draw
- **Theme (primary):** Digital Frequency Meter & Wave-Analyser Operation
- **Theme (secondary):** Memory Read/Write Timing Diagram & (7,4) Linear Block Code
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** no

> (a) (i) Draw a functional block diagram and explain the working of a digital frequency meter. [10]
> 
> (ii) Describe the circuit and working of a wave analyser for audio frequency and Megahertz frequency. [10]
> 
> (b) Draw the timing diagram for memory read cycle and memory write cycle and explain the significance of the time periods therein. [10]
> 
> (c) A systematic (7, 4) linear code has the parity matrix P given as:
> $$[P]=\begin{bmatrix} 1 & 1 & 1 \\ 1 & 1 & 0 \\ 1 & 0 & 1 \\ 0 & 1 & 1 \end{bmatrix}$$
> (i) Find the code vectors for message vectors 1000, 0001, 0010 and 0111. [8]
> 
> (ii) Draw the corresponding encoding diagram. [8]
> 
> (iii) If the received vector [0111110] has a single error, detect the error and correct it. [4]

---

### [EE2-2013-Q5] Root-Locus Break-In Point & Steady-State Error Gain · Distance-Relay Phase Comparator, FSK/PSK Signaling, Cable Insulation & Thermistor Characteristics

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Root-Locus Break-In Point & Steady-State Error Gain
- **Theme (secondary):** Distance-Relay Phase Comparator, FSK/PSK Signaling, Cable Insulation & Thermistor Characteristics
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> (a) (i) Determine the break-in point in the root locus of a control system with:
> $$G(s)H(s)=\frac{K(s+2)}{(s^{2}+s+10)}$$
> [5]
> 
> (ii) For the control system:
> 
> **Figure ID:** FIG-EE2-2013-Q5aii
> **Circuit description (netlist form):** Unity negative feedback control system. Reference input $R(s)$ enters a summing junction with positive sign. Forward path contains a block with transfer function $\frac{K}{s(sJ + f)}$. The plant output $C(s)$ feeds directly back to the summing junction with negative sign.
> **Symbolic form:** $$\frac{C(s)}{R(s)} = \frac{K}{s(sJ + f) + K}$$
> 
> $$f=10^{-1}\text{ Newton m per rad/sec}$$
> $$J=5\times 10^{-3}\text{ kg-m}^{2}$$
> the steady state error for unit ramp input is 0.01. Determine the value of K. [5]
> 
> (b) What is the need for a multi input comparator ? Show with diagrams how to obtain the quadrilateral characteristic in the R-X plane using 4-input phase comparator. [10]
> 
> (c) (i) What is the need for sending digital data over analog carriers? In this regard how is FSK better than PSK ? [5]
> 
> (ii) With reference to the 7 layer architecture of data networks, distinguish between Protocol Data Unit (PDU) and Service Data Unit (SDU). [5]
> 
> (d) State various insulating materials used for cables and comparatively discuss any two widely used materials. [10]
> 
> (e) What do you mean by Thermistor? Explain briefly resistance-temperature characteristic curve of Thermistor and compare the same with thermocouple. [10]

---

### [EE2-2013-Q6] Digital Voltmeter Types & Current-Measurement DVM · DAC-1200/8255 Interfacing & DPCM vs PCM with Convolutional Encoding

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Explain
- **Theme (primary):** Digital Voltmeter Types & Current-Measurement DVM
- **Theme (secondary):** DAC-1200/8255 Interfacing & DPCM vs PCM with Convolutional Encoding
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** yes

> (a) (i) What is a digital voltmeter ? [3]
> 
> (ii) What are its advantages as compared to analogue voltmeters ? [3]
> 
> (iii) Listing different types of DVMs explain any one type for the measurement of current. [4]
> 
> (b) (i) Show how DAC 1200 can be interfaced to the 8255. Write the schematic diagram. Use 'double buffering' to prevent glitches. [14]
> 
> (ii) Write 8085 subroutine to transfer 12 bits of data stored in two sequential memory locations to the DAC interface carried out in part (i). Assume that the address of the first byte is stored in the HL pair. [6]
> 
> (c) (i) How is DPCM better than PCM? With the help of illustrations, show how DPCM signals are generated and decoded. [10]
> 
> (ii) Consider the convolutional encoder shown in the figure below. The code is systematic:
> (a) Draw the state diagram using the State Transition Table
> (b) Draw the Code Tree.
> 
> **Figure ID:** FIG-EE2-2013-Q6cii
> **Circuit description (netlist form):** Rate $1/2$ systematic convolutional encoder. The input bit stream connects directly to the top terminal labeled $C^{(1)}$ of a commutator switch, to the input of a single flip-flop stage FF1, and to the first input of a modulo-2 adder. The output of flip-flop FF1 connects to the second input of the modulo-2 adder. The output of the modulo-2 adder connects to the bottom terminal labeled $C^{(2)}$ of the commutator switch. The switch commutates between $C^{(1)}$ and $C^{(2)}$ to produce the output bit stream.
> **Symbolic form:** $$C^{(1)} = \text{Input}, \quad C^{(2)} = \text{Input} \oplus \text{FF1}$$
> 
> [10]

---

### [EE2-2013-Q7] Charge Amplifier with a Piezoelectric Transducer · 8086 Segmented Memory & Addressing Modes; BPSK Formulation vs Baseband Transmission

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Transducers: thermocouple, thermistor, LVDT, strain-guage, piezo-electric crystal.
- **Directive:** Describe
- **Theme (primary):** Charge Amplifier with a Piezoelectric Transducer
- **Theme (secondary):** 8086 Segmented Memory & Addressing Modes; BPSK Formulation vs Baseband Transmission
- **Repeat cluster:** RC10 (Transducer Characteristics (LVDT/Strain Gauge/Capacitive/Piezo))
- **Has figure:** no

> (a) (i) Describe the functioning of a charge amplifier using an OPAMP with piezoelectric transducer used at the input for measurement of displacement. [10]
> 
> (ii) Derive the expression for the transfer function and draw its curve showing frequency response. [10]
> 
> (b) (i) List the features of 8086's segmented memory. [5]
> 
> (ii) What are the different addressing modes available in 8086? Indicate their features. Write the mnemonics for each of them taking 'MOV' as an example. Indicate the symbolic notation also for each of them. [15]
> 
> (c) What are the advantages of digital carrier systems over Baseband digital transmission ? Develop the mathematical formulation for a BPSK signal. [10]

---

### [EE2-2013-Q8] State-Transition Signal-Flow Graph & Characteristic Roots · HVDC Transmission-Link Classification & Digital Relay Block Diagram

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** State-variable representation and analysis of control systems.
- **Directive:** Draw
- **Theme (primary):** State-Transition Signal-Flow Graph & Characteristic Roots
- **Theme (secondary):** HVDC Transmission-Link Classification & Digital Relay Block Diagram
- **Repeat cluster:** RC11 (State-Variable/State-Space Analysis)
- **Has figure:** no

> (a) A control system is represented by the state space equations:
> $$\dot{x}_{1}=x_{2}$$
> $$\dot{x}_{2}=x_{3}-u_{1}$$
> $$\dot{x}_{3}=-2x_{2}-3x_{3}+u_{2}$$
> and the output equations are:
> $$y_{1}=x_{1}+3x_{2}+2u_{1}$$
> $$y_{2}=x_{2}$$
> Draw the state transition signal flow graph and find the characteristic roots of the system. [20]
> 
> (b) (i) With the help of single line diagrams, discuss the classification of HVDC transmission links. [14]
> 
> (ii) State their comparative advantages and disadvantages. [6]
> 
> (c) Draw the block diagram of a Digital Relay and name all the blocks of this relay. [10]

---
