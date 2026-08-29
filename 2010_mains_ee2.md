## Section 'A'

### [EE2-2010-Q1] LVDT Excitation & Strain Gauge Bridge Circuits · Static VAR Systems & 8085 Vending-Machine Controller Program

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Transducers: thermocouple, thermistor, LVDT, strain-guage, piezo-electric crystal.
- **Directive:** Derive
- **Theme (primary):** LVDT Excitation & Strain Gauge Bridge Circuits
- **Theme (secondary):** Static VAR Systems & 8085 Vending-Machine Controller Program
- **Repeat cluster:** RC10 (Transducer Characteristics (LVDT/Strain Gauge))
- **Has figure:** no

> 1.
> (a) Why is a LVDT excited by high frequency and low voltage? Derive the LVDT output, $e_{0}$, in terms of excitation voltage, winding resistance and inductances. A bridge ABCD has resistors in its four arms. $R_{1}$ in arm AB, $R_{2}$ in arm BC, dummy gauge in arm AD, and active gauge in arm CD. If a strain of $1250\ \mu\text{m/m}$ is applied, find the bridge offset voltage across AC if the bridge is supplied with a voltage of 12 V across BD. Assume, $R_{1}=R_{2}=R_{\text{dummy gauge}}=350\text{ ohm}$ and $R_{\text{active strain gauge}}=350\text{ ohm}$ has gauge factor $(GF=2\cdot0)$. [$2+10+8=20$]
> 
> (b) (i) Explain the functions of static VAR systems in EHV AC transmission.
> (ii) Discuss different types of static VAR systems (SVS) with the aid of neat figures.
> [$8+12=20$]
> 
> (c) Write an 8085 assembly level program for designing the following system:
> When a coin is inserted and when it is valid, port 1 gives code FFH. If it is valid, check whether the request is for tea or coffee at port 2. 04H code at port 2 is the request for tea and 40H code at port 2 is the request for coffee. Open the valve for liquid to come out with 04H code for tea and 40H code for coffee at port 3. These codes at port 3 are to be used for valve operation. When port 4 gives code 00H, valve is to be closed with code FFH. Repeat process can start with a new coin. If coin is invalid, 00 indication at port 5 is to be given and the instruction for inserting a new coin can be given.
> Write comments in the selected lines of the program. [20]

---

### [EE2-2010-Q2] Routh-Hurwitz Stability & Imaginary-Axis Roots · Circuit-Breaker Restriking Voltage & Economic Load Dispatch

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Find
- **Theme (primary):** Routh-Hurwitz Stability & Imaginary-Axis Roots
- **Theme (secondary):** Circuit-Breaker Restriking Voltage & Economic Load Dispatch
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> 2.
> (a) The loop Transfer function of a system is given by
> $$G(s)H(s)=\frac{7s+4}{s^{2}(s^{3}+4s^{2}+8s+8)}$$
> Find the number of roots located on the imaginary axis and also their values using the Routh table.
> Is there any root on the right hand side of the s-plane? [$5+10+5=20$]
> 
> (b) (i) Differentiate between "Restriking Phenomenon" and "Reclosing Phenomenon" in a circuit breaker. Which one is harmful and which one is useful and why?
> 
> (ii) A simple power system is shown operating on NO LOAD.
> 
> **Figure ID:** FIG-EE2-2010-Q2b(ii)
> **Circuit description (netlist form):** A single-phase equivalent circuit of an unloaded power system. An ideal AC generator source is connected in series with an inductance $L$. A capacitance $C$ is connected in shunt across the line to the return path. Connected after the shunt capacitance is a closed circuit breaker (CB closed) leading to open-circuited receiving end terminals.
> **Symbolic form:** not derivable from figure.
> 
> A fault occurs at the far end of the system and the breaker contacts separate. Derive an expression for the voltage across the breaker contacts. Find the frequency of oscillation of the recovery voltage. What is the highest value of the Restriking Voltage and when does it occur.
> [$6+14=20$]
> 
> (c) (i) A two bus system is shown in the figure below:
> 
> **Figure ID:** FIG-EE2-2010-Q2c(i)
> **Circuit description (netlist form):** A two-bus single-line diagram. Generator 1 with active power generation $P_{G_1}$ is connected to Bus 1. A transmission line connects Bus 1 to Bus 2. Generator 2 with active power generation $P_{G_2}$ is connected to Bus 2. A load is tapped off directly from Bus 2.
> **Symbolic form:** not derivable from figure.
> 
> If 100 MW power is transferred from plant 1 to load, a loss of 12 MW is incurred. System incremental cost is $\lambda = \text{Rs. } 30/\text{MWh}$. The incremental costs of the two plants are given by:
> $$\frac{dC_{1}}{dP_{G_{1}}}=0.02\,P_{G_{1}}+16\cdot0\text{ Rs./MWh}$$
> $$\frac{dC_{2}}{dP_{G_{2}}}=0.04\,P_{G_{2}}+20\cdot0\text{ Rs./MWh}$$
> Determine $P_{G_{1}}$, $P_{G_{2}}$ and power received by load.
> 
> (ii) Derive the economic dispatch criterion for a power system consisting of thermal plants with transmission losses.
> [$12+8=20$]

---

### [EE2-2010-Q3] Nyquist Stability Criterion · Power System Stability Classification & Ring-Feeder Relay Coordination

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Explain
- **Theme (primary):** Nyquist Stability Criterion
- **Theme (secondary):** Power System Stability Classification & Ring-Feeder Relay Coordination
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> 3.
> (a) (i) Explain the 'principle of the argument' of the complex-variable theory.
> (ii) Explain how this is adopted to determine the stability of control systems.
> (iii) The critical point in using the Nyquist criterion is $(-1, j0)$ in $G(s)H(s)$ plane and not the origin $(0, j0)$. Why?
> (iv) For minimum phase transfer function, $G(s)H(s)$, the polar plot is sufficient to determine the stability of the system. Explain.
> [$5+5+5+5=20$]
> 
> (b) (i) Explain comparatively steady state, dynamic and transient stability of a power system.
> (ii) Explain point-by-point method of solving swing-equation stating clearly the assumptions made.
> [$8+12=20$]
> 
> (c) A certain ring feeder has 6 sections. It is fed at one point only. Using non directional and directional overcurrent relays with suitable line lag, explain the method of protecting this feeder. Assume a minimum operating time of 60 ms for the relays.
> In the diagram to be drawn, the location of all the relays and whether they are directional or non directional are to be shown. Also the time of operation of all the relays is to be shown by the side of the relay. [20]

---

### [EE2-2010-Q4] Electrodynamometer Power-Factor Meter · 8085 Instruction Comparisons & Delta Modulation vs DPCM

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Explain
- **Theme (primary):** Electrodynamometer Power-Factor Meter
- **Theme (secondary):** 8085 Instruction Comparisons & Delta Modulation vs DPCM
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** no

> 4.
> (a) Explain, why the pointer of a single phase dynamometer type power factor meter remain in the same position even after the excitation source is switched off, that is, it does not come back to zero position. Explain the principle of operation of the power factor meter. How would the accuracy of such an instrument be affected by frequency and wave form variations. [$5+10+5=20$]
> 
> (b) Explain the similarities and differences between:
> (i) JUMP and CALL instructions
> (ii) STA and STAX instructions
> [20]
> 
> (c) Mention the salient points of relation between the delta modulation (DM) and differential pulse code modulation (DPCM). Draw the block diagram of delta modulator and demodulator. Explain threshold and overloading effects in delta modulation. How can a slope overload noise, which occurs due to threshold and overloading, be reduced ? [20]

---

## Section 'B'

### [EE2-2010-Q5] Inverted Pendulum Mathematical Modeling · Circuit-Breaker Resistance Switching, Distance Relay & PCM Companding

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components.
- **Directive:** Obtain
- **Theme (primary):** Inverted Pendulum Mathematical Modeling
- **Theme (secondary):** Circuit-Breaker Resistance Switching, Distance Relay & PCM Companding
- **Repeat cluster:** none
- **Has figure:** yes

> 5.
> (a) 
> 
> **Figure ID:** FIG-EE2-2010-Q5a
> **Circuit description (netlist form):** Schematic of an inverted pendulum system in the $xy$-plane. A motorized cart of mass $M$ moves horizontally with displacement $x$ under an applied horizontal control force $u$. An inverted pendulum of mass $m$, total length $2l$, and moment of inertia $I$ is hinged to the cart top. The pendulum rod is inclined at an angle $\theta$ to the vertical, and downward gravitational force $mg$ acts at the centre of gravity located at distance $l$ from the pivot (at vertical height $l\cos\theta$ above the cart).
> **Symbolic form:** not derivable from figure.
> 
> A model of the attitude control of a space booster on take off is represented by an inverted pendulum mounted on a motor driven cart shown in the above figure. The objective of the attitude control problem is to keep the pendulum in a vertical position. The pendulum can be assumed to move only in one plane (say the xy plane). The control force 'u' is applied to the cart. The centre of gravity of the pendulum is at its centre. The moment of inertia of the pendulum is 'I'. The mass of the pendulum is 'm' and the cart is 'M'. Obtain a mathematical model. [20]
> 
> (b) (i) What is "resistance switching" as applied to circuit breaker operation? Why is it resorted to ? Derive an expression for the value of the resistance to be used in terms of system parameters. [10]
> 
> (ii) A transmission line is protected by a three zone plain Impedance. Draw the characteristics of this relay in the R-X diagram. If this relay is provided with a directional feature, what modification is to be made in the characteristics drawn on the R-X diagram. Also draw the contact diagram of the arrangement assuming directional feature. [10]
> 
> (c) Pulse code modulation (PCM) is the most useful and widely used of all pulse modulations. How does an analog signal get converted to digital signal by the PCM? By which process non-uniform quantization is practically achieved? Draw a diagram of a model, which does this process. Explain its working. [20]

---

### [EE2-2010-Q6] Harmonic Distortion Meter & Multimeter Resistance Measurement · 8085 Interrupt Masking & Block vs Convolutional Codes

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Explain
- **Theme (primary):** Harmonic Distortion Meter & Multimeter Resistance Measurement
- **Theme (secondary):** 8085 Interrupt Masking & Block vs Convolutional Codes
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** no

> 6.
> (a) Explain the working principle of a "Harmonic Distortion Meter". State some of its typical technical specifications.
> Also describe, how is the resistance measured with an electronic multimeter. [$10+2+8=20$]
> 
> (b) The interrupt is a process of data transfer whereby a peripheral can inform the processor that it is ready for communication. How can interrupt be masked or unmasked using a program control? List the instructions used for control of interrupts. Explain any one by taking a suitable example. [20]
> 
> (c) Two important types of error-correcting codes are: (i) block codes and (ii) convolutional codes. Write the main difference between the block codes and convolutional codes. Explain the codes, which are a subclass of linear block codes. [20]

---

### [EE2-2010-Q7] High-Voltage Schering & Wien Bridge Measurements · DMA Controller Operation & OSI Network-Layer Functions

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements.
- **Directive:** Explain
- **Theme (primary):** High-Voltage Schering & Wien Bridge Measurements
- **Theme (secondary):** DMA Controller Operation & OSI Network-Layer Functions
- **Repeat cluster:** RC07 (Bridge Measurements & Error Analysis)
- **Has figure:** no

> 7.
> (a) Why is a Schering bridge particularly suitable for measurement at high voltage ? Draw high voltage Schering bridge line diagram, showing the high voltage transformer.
> The Wien bridge is used to measure the frequency of excitation voltage. Derive the frequency relation in terms of bridge elements. [$4+8+8=20$]
> 
> (b) What are the functions of DMA (Direct Memory Access)? How are HOLD and HLDA lines used in DMA operation? List the data transfer modes of DMA controller. Describe each mode in brief. [20]
> 
> (c) The network layer of OSI (Open Systems Interconnection) has two major functions, namely (i) routing of packets through the network and (ii) a flow control. Explain each of these two functions taking suitable examples. Prove that the network layer is the most sophisticated of the layered architecture. [20]

---

### [EE2-2010-Q8] State-Space Controllability Analysis · HVDC Converter Stations & Transformer Differential Protection

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** State-variable representation and analysis of control systems.
- **Directive:** Find
- **Theme (primary):** State-Space Controllability Analysis
- **Theme (secondary):** HVDC Converter Stations & Transformer Differential Protection
- **Repeat cluster:** RC11 (State-Variable/State-Space Analysis)
- **Has figure:** no

> 8.
> (a) A system is described by the following state variable equation
> $$\begin{bmatrix}\dot{x}_{1}\\ \dot{x}_{2}\\ \dot{x}_{3}\end{bmatrix}=\begin{bmatrix}1&2&4\\ 0&1&3\\ 1&1&1\end{bmatrix}\begin{bmatrix}\dot{x}_{1}\\ x_{2}\\ x_{3}\end{bmatrix}+\begin{bmatrix}1\\ 0\\ 1\end{bmatrix}u$$
> (i) Find its characteristic equation.
> (ii) Determine the controllability matrix.
> (iii) Is the system controllable ?
> [$8+7+5=20$]
> 
> (b) (i) With the aid of a neat figure, state the main components of a converter station of HVDC transmission system and explain the function of each component.
> (ii) Differentiate between two-terminal point to point dc transmission link and back to back dc link with an example of these links existing in India.
> [$12+8=20$]
> 
> (c) (i) Why do you need the harmonic restraint in the application of differential protection to power transformers? With the help of relevant circuit diagram, explain how this harmonic restraint scheme operates ?
> (ii) "Relays are comparators". Justify this statement. Show that an inherent two input amplitude comparator can work as a phase comparator and vice-versa.
> [$10+10=20$]

---
