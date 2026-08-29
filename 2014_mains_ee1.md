# SECTION-A

### [EE1-2014-Q1] DC Network Analysis (Nodal/Mesh Circuit Values) · Maxwell's Divergence Equations, Z-Transform Inversion, Op-Amp Limiter & 3-Phase Wattmeter Method

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Find
- **Theme (primary):** DC Network Analysis (Nodal/Mesh Circuit Values)
- **Theme (secondary):** Maxwell's Divergence Equations, Z-Transform Inversion, Op-Amp Limiter & 3-Phase Wattmeter Method
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> (a) Find the values of $E$ and $I$ in the circuit shown in Fig. 1. [10]
> 
> **Figure ID:** FIG-EE1-2014-Q1a
> **Circuit description (netlist form):** DC voltage source $E$ connected between reference node 0 and node 1 (positive at node 1); resistor $2\ \Omega$ connected between node 1 and node 2 carrying branch current $I$ from node 1 to node 2; resistor $6\ \Omega$ connected between node 2 and node 0; resistor $2\ \Omega$ connected between node 2 and node 3; resistor $4\ \Omega$ connected between node 3 and node 0 carrying a downward branch current of $2\text{ A}$; resistor $2\ \Omega$ connected between node 3 and node 0.
> **Symbolic form:** not derivable from figure.
> 
> (b) Starting from Maxwell's equations
> $$\nabla\times\vec{E}=-\frac{\partial\vec{B}}{\partial t}\quad\text{and}\quad\nabla\times\vec{H}=\vec{J}+\frac{\partial\vec{D}}{\partial t}$$
> show that $\nabla\cdot\vec{B}=0$ and $\nabla\cdot\vec{D}=\rho$. [10]
> 
> (c) Determine the inverse z-transform of
> $$X(z)=\frac{1}{1-1\cdot5z^{-1}+0\cdot5z^{-2}}\quad\text{for ROC } |z|>1$$ [10]
> 
> (d) A comparator and limiter circuit is shown in Fig. 2. Develop transfer characteristics $v_{0}$ vs. $V_{I}$ and explain. [10]
> 
> **Figure ID:** FIG-EE1-2014-Q1d
> **Circuit description (netlist form):** Inverting op-amp configuration with non-inverting terminal (+) connected to ground (node 0). Input voltage $V_I$ connected to inverting terminal (-) through resistor $R_1$. Feedback network connected between output terminal $v_O$ and inverting terminal (-) consists of resistor $R_2$ in parallel with two series back-to-back Zener diodes (Zener diode $V_{Z2}$ with anode towards inverting terminal and cathode connected to cathode of Zener diode $V_{Z1}$ whose anode connects to output terminal $v_O$).
> **Symbolic form:** not derivable from figure.
> 
> (e) A three-phase balanced delta-connected load gives wattmeter readings of $1050\text{ W}$ and $550\text{ W}$, when the two-wattmeter method is applied. Calculate the impedance in each arm of the load. Given, line voltage $= 200\text{ V}$. [10]

---

### [EE1-2014-Q2] Poynting Theorem: Power Flow and Energy Dissipation in a Volume · Delta-Star Load Conversion & Discrete-Time System Properties

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves.
- **Directive:** Derive
- **Theme (primary):** Poynting Theorem: Power Flow and Energy Dissipation in a Volume
- **Theme (secondary):** Delta-Star Load Conversion & Discrete-Time System Properties
- **Repeat cluster:** RC18 (Electromagnetic Field Theory (Maxwell's Equations & Poynting Theorem))
- **Has figure:** no

> (a) The net power flowing out of a given volume $v$ is equal to the time rate of decrease in the energy stored within $v$ minus the conduction losses. Derive equations to explain. [20]
> 
> (b) A delta-connected balanced three-phase load is supplied from a three-phase, $400\text{ V}$ supply. The line current is $20\text{ A}$ and power taken by the load is $10000\text{ W}$. Find (i) impedance in each branch and (ii) the line current, power factor and power consumed if the same load is connected in star. [20]
> 
> (c) Determine whether the following system is linear, time invariant, stable or dynamic:
> $$y(n)=5~x(2n)$$ [10]

---

### [EE1-2014-Q3] Laplace Transform and Region of Convergence · Helmholtz Equation Derivation & Two-Port Parameter Conversion

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Find
- **Theme (primary):** Laplace Transform and Region of Convergence
- **Theme (secondary):** Helmholtz Equation Derivation & Two-Port Parameter Conversion
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** no

> (a) Find the Laplace transform of the signal $x(t)=e^{-3t}u(t)+e^{-2t}u(t)$ and find ROC. [20]
> 
> (b) Derive Helmholtz equation in terms of magnetic field. [20]
> 
> (c) The z-parameters of a two-port network are $z_{11}=20~\Omega$, $z_{22}=30~\Omega$, $z_{12}=z_{21}=10~\Omega$. Find y and ABCD parameters of the network. [10]

---

### [EE1-2014-Q4] Op-Amp Slew Rate: Derivation and Frequency-Distortion Calculation · Norton Equivalent Circuit & Discrete Signal Periodicity

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits.
- **Directive:** Develop
- **Theme (primary):** Op-Amp Slew Rate: Derivation and Frequency-Distortion Calculation
- **Theme (secondary):** Norton Equivalent Circuit & Discrete Signal Periodicity
- **Repeat cluster:** RC19 (Op-Amp/Transistor Amplifier Characteristics)
- **Has figure:** yes

> (a) (i) Why the output voltage of an Op-Amp does not respond immediately to the fast-changing input?
> (ii) Develop the expression for the slew rate of Op-Amp.
> (iii) An open-loop configuration of Op-Amp 741C changes its output from $+14\text{ V}$ to $-14\text{ V}$ each time its input crosses zero volt. If 741C has a typical slew rate of $0.5\text{ V}/\mu\text{s}$, calculate the time between the zero crossings and the maximum frequency at which the output will be distorted. [20]
> 
> (b) Obtain the Norton's equivalent circuit at the terminals A and B for the network shown in Fig. 3. [20]
> 
> **Figure ID:** FIG-EE1-2014-Q4b
> **Circuit description (netlist form):** Independent DC voltage source $100\text{ V}$ (negative terminal at ground/node 0, positive terminal at bottom of $1\ \Omega$ resistor) in series with $1\ \Omega$ resistor connected between node 0 and node 1; resistor $10\ \Omega$ connected between node 1 and node 0; independent DC voltage source $20\text{ V}$ (negative at node 1, positive at node 2) in series with resistor $2\ \Omega$ connected between node 1 and node 3 (terminal A); resistor $10\ \Omega$ connected between terminal A (node 3) and terminal B (node 0).
> **Symbolic form:** not derivable from figure.
> 
> (c) Determine whether the following signal is periodic or aperiodic. Find the fundamental period, if it is periodic:
> $$x(n)=\sin\left(\frac{3\pi}{7}n+\frac{\pi}{4}\right)+\cos\frac{\pi}{3}n$$ [10]

---

# SECTION-B

### [EE1-2014-Q5] Single-Phase Fully-Controlled Bridge Converter: Performance Parameters · DC Motor Torque Laws, Thyristor Gate Pulse Width, Random-Variable PDFs & Sequential Logic Design

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** phase control rectifiers; bridge converters: fully-controlled and half-controlled;
- **Directive:** Determine
- **Theme (primary):** Single-Phase Fully-Controlled Bridge Converter: Performance Parameters
- **Theme (secondary):** DC Motor Torque Laws, Thyristor Gate Pulse Width, Random-Variable PDFs & Sequential Logic Design
- **Repeat cluster:** none
- **Has figure:** yes

> (a) A single-phase fully controlled bridge converter supplies an inductive load. Assuming that the output current is virtually constant and is equal to $20\text{ A}$, determine the following performance measures, if the supply voltage is $230\text{ V}$ and the firing angle is maintained at $30^{\circ}$:
> (i) Average output voltage
> (ii) Supply r.m.s. current
> (iii) Supply fundamental r.m.s. current
> (iv) Fundamental power factor
> (v) Supply power factor
> (vi) Supply harmonic factor
> (vii) Voltage ripple factor
> (viii) Reactive power input [10]
> 
> (b) Prove that the torque produced in a shunt motor is proportional to armature current $I_{a}$ and in case of series motor, it is proportional to $I_{a}^{2}$. [10]
> 
> (c) A single-phase converter feeds an R-L load having a resistance of $10\text{ ohms}$ in series with an inductance of $20\text{ mH}$. The converter operates such that the d.c. voltage across the load is $250\text{ V}$. The thyristor used in the converter has holding current of $300\text{ mA}$ and a delay time of $5\ \mu\text{s}$. Determine the pulse width of gate current. [10]
> 
> (d) A random variable has an exponential probability function given by $f(x)=ae^{-b|x|}$, where $a$ and $b$ are constants. Find (i) the relationship between $a$ and $b$, and (ii) the distribution function of $x$. [10]
> 
> (e) Design a circuit that gives the input-output relationship shown in Fig. 4. [10]
> 
> **Figure ID:** FIG-EE1-2014-Q5e
> **Circuit description (netlist form):** Digital timing waveform with Input and Output signals. Input is a sequence of periodic rectangular clock pulses labeled 1, 2, 3, 4, 5. The Output remains low during pulses 1, 2, and 3, transitions to high at the rising edge of pulse 4, remains high through pulse 4 and pulse 5, and transitions low at the trailing edge of pulse 5.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2014-Q6] Chopper-Controlled Speed Range of a DC Shunt Motor · 2's Complement, POS Logic Design & Alternator Synchronous Reactance

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** principles of thyristor choppers and inverters; DC-DC converters; Switch mode inverter;
- **Directive:** Determine
- **Theme (primary):** Chopper-Controlled Speed Range of a DC Shunt Motor
- **Theme (secondary):** 2's Complement, POS Logic Design & Alternator Synchronous Reactance
- **Repeat cluster:** none
- **Has figure:** no

> (a) A d.c. shunt motor takes a current of $80\text{ A}$ on a $480\text{ V}$ supply and runs at $960\text{ r.p.m.}$ The armature resistance is $0\cdot25\text{ ohm}$ and the field resistance is $120\text{ ohms}$. A chopper is used to control the speed of the motor in the range of $400\text{--}750\text{ r.p.m.}$ having constant torque. The on-period of the chopper is $3\text{ ms}$. The field is supplied directly from $480\text{ V}$ supply. Determine the range of frequencies of the chopper. [20]
> 
> (b) (i) Find 2's complement of the following numbers:
> (1) 10010010
> (2) 11011000
> (ii) Convert the logical equation $Y=(A+BC)(B+\overline{C}A)$ into product-of-sums (POS) form and design circuits using (1) OR and AND gates and (2) NOR gates.
> (iii) Explain the function of Schottky diode connected between the collector and base of transistors of TTL gate. [20]
> 
> (c) A $550\text{ V}$, $55\text{ kVA}$, single-phase alternator has effective resistance of $0\cdot2\ \Omega$. A field current of $10\text{ A}$ produces an armature current of $200\text{ A}$ on short circuit and an e.m.f. of $450\text{ V}$ on open circuit. Calculate (i) the synchronous reactance and (ii) the full-load regulation with power factor $0\cdot8$ lagging. [10]

---

### [EE1-2014-Q7] All-Day Efficiency of a Transformer · Joint Gaussian Random Variables in Polar Form & Voltage-Commutated Chopper

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers.
- **Directive:** Describe
- **Theme (primary):** All-Day Efficiency of a Transformer
- **Theme (secondary):** Joint Gaussian Random Variables in Polar Form & Voltage-Commutated Chopper
- **Repeat cluster:** RC20 (Transformer Performance & Testing)
- **Has figure:** no

> (a) Describe all-day efficiency of a transformer. [10]
> 
> (b) The two random variables X and Y are independent and identically distributed each with a Gaussian density function with mean equal to zero and variance equal to $\sigma^{2}$. If these two random variables denote the coordinates of a point in the plane, find the probability density function of the magnitude and the phase of that in polar coordinates. [20]
> 
> (c) Describe the voltage-commutated chopper controlling the speed of a d.c. series motor with relevant schematic diagram and associated voltage and current waveforms as a function of time. [20]

---

### [EE1-2014-Q8] Synchronous Motor Excitation Effects & Comparison with Induction Motor · PLL Frequency Demodulation & Chopper-Controlled Rotor-Resistance Speed Control

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
- **Directive:** Discuss
- **Theme (primary):** Synchronous Motor Excitation Effects & Comparison with Induction Motor
- **Theme (secondary):** PLL Frequency Demodulation & Chopper-Controlled Rotor-Resistance Speed Control
- **Repeat cluster:** none
- **Has figure:** no

> (a) Discuss the effect of excitation on armature current for a synchronous motor and compare the performance of $3\phi$ synchronous motor with $3\phi$ induction motor. [20]
> 
> (b) Explain the method of frequency demodulation using PLL. [15]
> 
> (c) A three-phase, four-pole, $50\text{ Hz}$ induction motor has a chopper-controlled resistance in the rotor circuit for speed control. Load torque is $\omega^{2}$. When the thyristor is ON, the torque is $30\text{ N-m}$ at a slip of average $0\cdot03$. If $\frac{T_{\text{ON}}}{T_{\text{OFF}}}=1$, compute the average torque and speed. The motor develops a torque of $80\text{ percent}$ of ON torque when the thyristor is OFF. The speed variation ranges down to $1200\text{ r.p.m.}$ from synchronous speed. Determine the ratio $\frac{T_{\text{ON}}}{T_{\text{OFF}}}$ to give an average torque of $25\text{ N-m}$. [15]

---
