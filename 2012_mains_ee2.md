### [EE2-2012-Q1] Root-Locus & Second-Order Stability Concepts (True/False Analysis) · 8085 Bus Multiplexing, Thermocouple Dynamics, HVAC Line Loading, Relay Features & PCM/Huffman Coding

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Identify
- **Theme (primary):** Root-Locus & Second-Order Stability Concepts (True/False Analysis)
- **Theme (secondary):** 8085 Bus Multiplexing, Thermocouple Dynamics, HVAC Line Loading, Relay Features & PCM/Huffman Coding
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> **Section-A**
> 
> 1. (a) Identify the correctness of the following statements. Justify your answers :
> (i) The root locus gives idea about system's transient behaviour. [3]
> (ii) For an inherently stable second-order system, all the coefficients of characteristic equation are of the same sign. [4]
> (iii) A critically damped system has sustained oscillations. [3]
> 
> (b) (i) In 8085 microprocessor, what is the advantage of multiplexing the address bus with a data bus? [5]
> (ii) Write an assembly level program of 8085 microprocessor to exchange the contents of DE register pair with that of HL register pair, using only PUSH-POP instructions. [5]
> 
> (c) (i) The transfer function of a thermocouple relating output voltage to temperature is given by
> $$\frac{0\cdot625\times10^{-4}}{s+0\cdot125}\frac{\text{V}}{^\circ\text{C}}$$
> Put the transfer function in standard format and find the values of characterising parameters of the thermocouple. Determine the thermocouple output voltage at $t=8\text{ s}$, when the thermocouple kept at ambient temperature of $20^\circ\text{C}$ at $t=0\text{ s}$ is taken to a water bath kept at $80^\circ\text{C}$. [$3+4=7$]
> (ii) Comment upon 'linearity' and 'sensitivity' of thermistors in comparison to thermocouples. [2]
> (iii) Why is 'lead wire compensation' not required for thermistors? [1]
> 
> (d) (i) What is the impedance of the ideal load connected to an HVAC transmission line? [2]
> (ii) What is the nature of the load of an HVAC transmission line by itself, capacitive or inductive? [2]
> (iii) Which electrical quantity measures the magnitude of electrical load in a system? What is generally the nature of the load current, capacitive or inductive, in the power system? [2]
> (iv) Under which condition is the receiving-end voltage higher than the sending-end voltage in a transmission line? Explain with the help of a phasor diagram. [4]
> 
> (e) Describe the essential features of a protective relay. [10]
> 
> (f) (i) A binary PCM system uses a uniform quantizer and an 8-bit binary encoder. If the bit rate is $100\text{ Mb/s}$, what is the maximum bandwidth for which the system operates satisfactorily? Determine the output signal to quantization ratio when full-load sinusoidal modulating wave of frequency 1 MHz is applied to the input. [5]
> (ii) A discrete memoryless source is described by the alphabet $X=\{x_{1},x_{2},\cdots,x_{8}\}$ and the corresponding probability vector
> $$P = \{0\cdot2, 0\cdot12, 0\cdot06, 0\cdot15, 0\cdot07, 0\cdot1, 0\cdot13, 0\cdot17\}$$
> Design a Huffman code for this source; find $\overline{L}$, the average codeword length for the Huffman code; and determine the efficiency of the code. [5]

---

### [EE2-2012-Q2] Steady-State Error with Minor-Loop Feedback · Merz-Price Transformer Differential Protection & 8085 CALL Instruction

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** LTI systems: time-domain and transform-domain analysis.
- **Directive:** Determine
- **Theme (primary):** Steady-State Error with Minor-Loop Feedback
- **Theme (secondary):** Merz-Price Transformer Differential Protection & 8085 CALL Instruction
- **Repeat cluster:** RC06 (Control System Time-Domain Response)
- **Has figure:** yes

> 2. (a) For the control system, shown in the following figure, determine the steady-state error for a unit step input in terms of K and $K_1$, where $E(s)=R(s)-C(s)$. Determine the value of $K_1$, when steady-state error is zero : [20]
> 
> **Figure ID:** FIG-EE2-2012-Q2a
> **Circuit description (netlist form):** Closed-loop control system block diagram. Reference input $R(s)$ enters a primary summing junction with negative feedback from output $C(s)$ to generate error $E(s)$. Error $E(s)$ passes through gain block $K$ to a secondary summing junction. Secondary summing junction subtracts minor-loop feedback signal $K_1 s C(s)$ and drives forward path plant block $\frac{10}{s(s+10)(s+12)}$. The plant output is $C(s)$, which feeds both minor feedback block $K_1 s$ and primary unity feedback path.
> **Symbolic form:** $\frac{C(s)}{R(s)} = \frac{10K}{s(s+10)(s+12) + 10K_1 s + 10K}$
> 
> (b) A three-phase, 66 kV/11 kV transformer is connected in star/delta. The transformer is protected by Merz-Price circulating current system. Protecting current transformers on the low-voltage side have a ratio of $250/5$. Find the ratio of the current transformer on the high-voltage side. [20]
> 
> (c) For 8085 microprocessor, explain the CALL instruction, showing the details of main memory and stack. [20]

---

### [EE2-2012-Q3] AC Power-Triangle Analysis & Power-Factor Calculation · Piezoelectric Transducer Transfer Function & Digital Modulation/Block Codes

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements.
- **Directive:** Draw
- **Theme (primary):** AC Power-Triangle Analysis & Power-Factor Calculation
- **Theme (secondary):** Piezoelectric Transducer Transfer Function & Digital Modulation/Block Codes
- **Repeat cluster:** RC07 (Bridge Measurements & Error Analysis)
- **Has figure:** yes

> 3. (a) (i) Draw power triangles showing the three types of power and their units for-
> (1) inductive loads;
> (2) capacitive loads. [10]
> (ii) A single-phase, 240 V a.c. voltage is applied to a series circuit whose impedance is $10\angle60^\circ\ \Omega$. Find R, X, P and Q, and also the power factor of the circuit. [10]
> 
> (b) The equivalent model of a piezoelectrical crystal is shown below :
> 
> **Figure ID:** FIG-EE2-2012-Q3b
> **Circuit description (netlist form):** Piezoelectric crystal equivalent circuit. Current source $i_{cr}$ is connected in parallel with equivalent resistance $R_{eq}$ and equivalent capacitance $C_{eq}$ across a pair of open-circuit output terminals with voltage $V_o$.
> **Symbolic form:** $\frac{V_o(s)}{I_{cr}(s)} = \frac{R_{eq}}{1 + s R_{eq} C_{eq}}$
> 
> (i) Derive the transfer function relating output voltage $(V_o)$ to input displacement $(x_i)$. Arrange it in standard form and identify the expression for characterising parameters. The charge developed in piezoelectric crystal is related to $x_i$ by a constant $k_q$. [10]
> (ii) "Piezoelectric transducers cannot be used to measure static displacement." Comment upon the statement. State the reason based on the transfer function derived in Part (i). [2]
> (iii) If the lower range of frequency for displacement measurement is 5 kHz with 5% inaccuracy, what is the lower range of frequency for 2% inaccuracy? [8]
> 
> (c) (i) Explain ASK, FSK and PSK modulation schemes used for transmitting the data. Draw clearly the block diagram for coherent detection and non-coherent detection of FSK modulation scheme. [10]
> (ii) A (6,3) systematic linear block code encodes the information sequence $X=(x_1,x_2,x_3)$ into code word $C = (c_1, c_2, c_3, c_4, c_5, c_6)$ such that $c_4$ is a parity check on $c_1$ and $c_2$, to make the overall parity even, i.e., $c_1\oplus c_2\oplus c_4=0$. Similarly $c_5$ is a parity check on $c_2$ and $c_3$, and $c_6$ is a parity check on $c_1$ and $c_3$.
> (1) Determine the generator matrix of this code.
> (2) Find the parity check matrix for this code.
> (3) Using the parity check matrix, determine the minimum distance of this code.
> (4) How many errors of this code are capable of correcting? [10]

---

### [EE2-2012-Q4] Synchronous Generator Loss of Synchronism & Swing-Equation Derivation · 8085 Stack-Pointer I/O Program & Multi-Input Block-Diagram Algebra

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Concepts of system stability: swing curves and equal area criterion.
- **Directive:** Explain
- **Theme (primary):** Synchronous Generator Loss of Synchronism & Swing-Equation Derivation
- **Theme (secondary):** 8085 Stack-Pointer I/O Program & Multi-Input Block-Diagram Algebra
- **Repeat cluster:** none
- **Has figure:** yes

> 4. (a) (i) Under which different conditions a generator or a number of generators together may lose synchronism or fall out of step in an interconnected power system? Explain in brief. [10]
> (ii) Relating the torque angle and the rotor angular displacement (electrical) of a synchronous generator, derive the 'swing equation' taking into consideration the inertia constant of the machine. Make suitable assumptions. [10]
> 
> (b) For an 8085 microprocessor, write an assembly level program to transfer the contents of the stack pointer register to the output ports $A_0$ and $A_1$. Write comments with selected instructions. [20]
> 
> (c) (i) Some control systems have more than one inputs applied at different points in the system. How do we find the response of such systems, using block diagram algebra? Illustrate your answer with the help of a simple example. [10]
> (ii) For the block diagram representation of the figure shown below, determine the system characteristic equation. Is the system represented by this block diagram stable? [10]
> 
> **Figure ID:** FIG-EE2-2012-Q4cii
> **Circuit description (netlist form):** Feedback control system block diagram. Reference input $R(s)$ enters a summing junction with positive polarity (+). Forward path transfer block $(s+1)(s+3)$ receives the summing junction output and produces output $C(s)$. Feedback block $\frac{1}{(s+2)(s+4)}$ takes output $C(s)$ and feeds back to the summing junction with negative polarity (-).
> **Symbolic form:** $\frac{C(s)}{R(s)} = \frac{(s+1)(s+3)}{1 + \frac{(s+1)(s+3)}{(s+2)(s+4)}}$

---

### [EE2-2012-Q5] Routh/Hurwitz/Nyquist Stability-Criteria Limitations · 8085 Interrupt Nesting, Analog Ohmmeter, Power-Grid Concepts, CB Ratings & Convolutional Codes

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Explain
- **Theme (primary):** Routh/Hurwitz/Nyquist Stability-Criteria Limitations
- **Theme (secondary):** 8085 Interrupt Nesting, Analog Ohmmeter, Power-Grid Concepts, CB Ratings & Convolutional Codes
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> **Section-B**
> 
> 5. (a) (i) What are the limitations of Routh, Hurwitz and continued fraction stability criteria when used for determining system stability? What is Nyquist analysis? Where is this technique used? [6]
> (ii) Why are integral and derivative controllers not used in practice? [4]
> 
> (b) Can the 8085 microprocessor be interrupted before completion of existing Interrupt Service Subroutine (ISS)? Justify your answer. [10]
> 
> (c) (i) Draw the basic circuit of an analog series ohmmeter to measure an unknown resistance $R_x$. [3]
> (ii) If the standard resistance and meter resistance add up to 20 k$\Omega$, and the battery is of 2.0 V, determine the instrument indication, when $R_x=0\ \Omega$. [2]
> (iii) What would be the resistance value marked for 0.5 FSD (full-scale deflection)? [2]
> (iv) What component should be connected and in which way to take care of falling battery voltage? [1]
> (v) When each time ohmmeter is used, what adjustment is recommended for accurate measurement? [2]
> 
> (d) (i) Define an electrical power grid in one sentence. How is it achieved? [2]
> (ii) Write four main advantages of the electrical power grid system. [2]
> (iii) What is the purpose of installing a 'reactor' at a suitable location on a long high-voltage a.c. transmission line? [2]
> (iv) Write the full form of FACTS. [2]
> (v) What are the advantages of 'reactive power control' installed on the transmission lines? [2]
> 
> (e) What is circuit breaker rating? Explain the rated making capacity of a circuit breaker. [$5+5=10$]
> 
> (f) (i) A convolutional encoder is given in the figure below :
> 
> **Figure ID:** FIG-EE2-2012-Q5fi
> **Circuit description (netlist form):** Convolutional encoder block diagram consisting of a 3-stage shift register with flip-flop stages $S_1$, $S_2$, and $S_3$ connected in series receiving the Input sequence. Top modulo-2 adder ($\oplus$) sums outputs from stage $S_1$ and stage $S_2$. Bottom modulo-2 adder ($\oplus$) sums outputs from stage $S_1$ and stage $S_3$. A commutator switch alternates between the top adder output and bottom adder output to produce the Output stream.
> **Symbolic form:** not derivable from figure.
> 
> (1) Find the impulse response of the encoder.
> (2) Find the output code word if the input sequence is all 1's (111111...). [5]
> 
> (ii) Determine the channel capacity of band-limited waveform AWGN channel with an input power constraint. [5]

---

### [EE2-2012-Q6] Static-Relay Elements & Advantages over Electromagnetic Relays · 8255 PPI Block Schematic & Multi-Loop Transfer Function (Block Diagram vs SFG)

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers.
- **Directive:** Describe
- **Theme (primary):** Static-Relay Elements & Advantages over Electromagnetic Relays
- **Theme (secondary):** 8255 PPI Block Schematic & Multi-Loop Transfer Function (Block Diagram vs SFG)
- **Repeat cluster:** RC16 (Circuit-Breaker/Relay Protection Principles)
- **Has figure:** yes

> 6. (a) (i) What are the basic elements of a static relay? Describe the function of each element. [12]
> (ii) What are the advantages of static overcurrent relays over the electromagnetic form? [8]
> 
> (b) Draw a block schematic of an 8255-programmable parallel I/O device, showing all elements and control word format. For mode 0 (simple input and output), determine the addresses of its ports and of the control register. Write a control word in the control register, when port $A = \text{output}$, port $C_U = \text{output}$, port $B = \text{input}$ and port $C_L = \text{input}$. [20]
> 
> (c) For the block diagram shown in the figure below, find the overall transfer function of the system. Verify the same, using signal-flow graph analysis: [20]
> 
> **Figure ID:** FIG-EE2-2012-Q6c
> **Circuit description (netlist form):** Multiple-loop control system block diagram. Reference input $R(s)$ enters summing junction 1 (+). Output of summing junction 1 passes through block $G_1$ to summing junction 2 (+). Output of summing junction 2 passes through block $G_2$ to node 3. From node 3, forward signal passes through block $G_3$ to node 4 (output $C(s)$) and feedback signal passes through block $H_1$ to summing junction 1 (-). From node 4 ($C(s)$), feedback signal passes through block $H_2$ to summing junction 2 (-).
> **Symbolic form:** $\frac{C(s)}{R(s)} = \frac{G_1 G_2 G_3}{1 + G_2 H_2 G_3 + G_1 G_2 H_1}$

---

### [EE2-2012-Q7] Line-to-Ground Fault Analysis on an Unloaded Generator · OSI Model, CRC-4 Computation & AC Bridge Measurement

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** symmetrical components, analysis of symmetrical and unsymmetrical faults.
- **Directive:** Draw
- **Theme (primary):** Line-to-Ground Fault Analysis on an Unloaded Generator
- **Theme (secondary):** OSI Model, CRC-4 Computation & AC Bridge Measurement
- **Repeat cluster:** none
- **Has figure:** yes

> 7. (a) (i) Draw the circuit diagram for a single line to ground fault on an unloaded Y-connected generator with its neutral grounded through reactance. Also draw the connection for three symmetrical component sequence networks for this case showing the currents and voltages. [10]
> (ii) A synchronous generator rated at 100 MVA, 20 kV has $X'' = X_2 = 20\%$ and $X_0 = 5\%$. Its neutral is grounded through a reactor of $0\cdot32\ \Omega$. The generator is operating at rated voltage without load and is disconnected from the system when a single phase to ground fault occurs at its terminals. Find the sub-transient current in the faulted phase. [10]
> 
> (b) (i) Draw the neat sketch of OSI model. What is the significance of data link layer? Explain the flow-control and error-control mechanism. [10]
> (ii) Compute the CRC-4 character for the following message, using a modified divisor constant of 10011:
> 1100 0110 1011 01 [10]
> 
> (c) The a.c. bridge circuit shown below is used to measure the excitation frequency of the source and the resistance $R_x$ connected in arm CD of the bridge. Arm AB is parallel combination of $R_1$ and $C_1$, arm BC is fixed resistor $R_2$, arm AD is serial combination of $R_4$ and $C_4$ :
> 
> **Figure ID:** FIG-EE2-2012-Q7c
> **Circuit description (netlist form):** Four-arm AC bridge circuit with four junction nodes A, B, C, and D. AC source $V_s$ is connected across nodes B and D. Detector galvanometer G is connected across nodes A and C. Arm AB consists of a parallel combination of resistor $R_1$ and capacitor $C_1$. Arm BC consists of fixed resistor $R_2$. Arm AD consists of a series combination of resistor $R_4$ and capacitor $C_4$. Arm CD contains unknown resistance $R_x$.
> **Symbolic form:** not derivable from figure.
> 
> (i) Find the expression for the unknown resistance $R_x$ at balance. [5]
> (ii) Find the expression for unknown excitation frequency ($\omega$) at balance. [5]
> (iii) If $R_1=200\ \Omega$, $C_1=1\ \mu\text{F}$, $R_2=400\ \Omega$, $\frac{C_1}{C_4} = 0\cdot5$ and $\frac{R_4}{R_1}=2$, find the value of $R_x$ in $\text{k}\Omega$ and frequency of excitation in kHz. [10]

---

### [EE2-2012-Q8] Circuit-Breaker Testing & Rated Making Capacity · DM/DPCM Relation, AWGN Channel Capacity & Three-Op-Amp Instrumentation Amplifier

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers.
- **Directive:** Explain
- **Theme (primary):** Circuit-Breaker Testing & Rated Making Capacity
- **Theme (secondary):** DM/DPCM Relation, AWGN Channel Capacity & Three-Op-Amp Instrumentation Amplifier
- **Repeat cluster:** RC16 (Circuit-Breaker/Relay Protection Principles)
- **Has figure:** yes

> 8. (a) What is the importance of testing of a circuit breaker? Explain different tests carried out to prove the ability of a circuit breaker. [$8+12=20$]
> 
> (b) (i) Bring out the salient points of relation between DM and DPCM. Draw the block diagram of delta modulator and demodulator. [8]
> (ii) Find the capacity of an additive white Gaussian noise channel with a bandwidth 1 MHz, power 10 W and noise power spectral density $\frac{N_0}{2}=10^{-9}\text{ W/Hz}$. [6]
> (iii) Explain cyclic codes. [6]
> 
> (c) The circuit given below is made by three ideal operational amplifiers (op-amp):
> 
> **Figure ID:** FIG-EE2-2012-Q8c
> **Circuit description (netlist form):** Three-op-amp instrumentation amplifier. First stage: Non-inverting input (+) of top op-amp receives input voltage $V_1$; its inverting input (-) is connected to node (a); feedback resistor $R$ is connected between output node (c) and node (a). Non-inverting input (+) of bottom op-amp receives input voltage $V_2$; its inverting input (-) is connected to node (b); feedback resistor $R$ is connected between output node (d) and node (b). Gain resistor $R_g$ is connected between node (a) and node (b). Second stage: Difference amplifier with inverting input (-) of output op-amp connected via resistor $R_1$ to node (c) and via feedback resistor $R_2$ to output node (e); non-inverting input (+) connected via resistor $R_1$ to node (d) and via resistor $R_2$ to ground reference.
> **Symbolic form:** $V_e = \frac{R_2}{R_1}\left(1 + \frac{2R}{R_g}\right)(V_2 - V_1)$
> 
> (i) Identify the name of the circuit. Comment upon its CMRR in comparison to op-amp. [2]
> (ii) Find the expressions for voltages at points a, b, c, d and e. [10]
> (iii) If $V_1=5\text{ V}$ and $V_2=5\cdot05\text{ V}$ and $V_e$ (voltage at point e) is 5 V, find the ratio of $\frac{R}{R_g}$ and $\frac{R_2}{R_1}$, when overall gain is divided in the ratio of $10 : 1$ between first and second stage of the circuit. [8]

---
