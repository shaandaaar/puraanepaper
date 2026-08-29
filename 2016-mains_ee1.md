# PAPER I

## SECTION-A

### [EE1-2016-Q1] Graph-Theoretic Network Analysis (Incidence Matrix, Trees, Tie-Sets) · Cascaded LTI Impulse Response, Maxwell's Equation, Diode Circuit & AC Resonance

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Determine
- **Theme (primary):** Graph-Theoretic Network Analysis (Incidence Matrix, Trees, Tie-Sets)
- **Theme (secondary):** Cascaded LTI Impulse Response, Maxwell's Equation, Diode Circuit & AC Resonance
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> (a) The reduced incidence matrix of an oriented graph is given as
> $$\begin{bmatrix}0 & -1 & 1 & 0 & 0\\ 0 & 0 & -1 & -1 & -1\\ -1 & 0 & 0 & 0 & 1\end{bmatrix}$$
> (i) Draw the graph.
> (ii) How many trees are possible for this graph?
> (iii) Write the tie-set matrix. [10]
> 
> (b) Determine the overall impulse response, $h(n)$, of the system shown in Fig. 1(b) below. Given that
> $$h_{1}(n)=\delta(n)-\left(\frac{1}{5}\right)\delta(n-1)$$
> $$h_{2}(n)=\delta(n)-\delta(n-1)$$
> $$h_{3}(n)=\left(\frac{1}{5}\right)^{n}u(n)$$
> $$h_{4}(n)=(n-1)u(n)$$
> $$h_{5}(n)=\delta(n)+nu(n-1)+\delta(n-2)$$
> where $\delta(n)$ and $u(n)$ denote, respectively, the unit impulse and unit step signals: [10]
> 
> **Figure ID:** FIG-EE1-2016-Q1b
> **Circuit description (netlist form):** Block diagram consisting of input signal passing sequentially through a cascade of three discrete-time LTI blocks with impulse responses $h_1(n)$, $h_2(n)$, and $h_3(n)$. The output from $h_3(n)$ branches into two parallel paths: the upper path contains block $h_4(n)$ connected to the inverting input ($-$) of a summer, and the lower path contains block $h_5(n)$ connected to the non-inverting input ($+$) of the summer to yield the overall system output.
> **Symbolic form:** $H(z) = H_1(z)H_2(z)H_3(z)[H_5(z) - H_4(z)]$
> 
> (c) Derive an expression for Maxwell's equation in integral form from Ampere's law. [10]
> 
> (d) Two ideal and identical junction diodes are connected as shown in Fig. 1(d). If the current through the reverse-biased diode is $I_{0}$ and is constant, explain the circuit operation when both the diodes are connected in forward-biased condition. Assume $V_{T}=25\text{ mV}$, $V_{\gamma}=0.7\text{ V}$ and $\eta=1$ for the diodes. [10]
> 
> **Figure ID:** FIG-EE1-2016-Q1d
> **Circuit description (netlist form):** Closed-loop circuit containing a DC voltage source $V = 50\text{ mV}$ in series with two diodes $D_1$ and $D_2$. The positive terminal of source $V$ is on the left and the negative terminal is on the right. Diode $D_1$ is connected with its cathode to the positive terminal of the source and its anode to the anode of diode $D_2$ at the top node (forming a back-to-back connection). The cathode of $D_2$ connects to the negative terminal of the source. The voltage drop across $D_1$ is labeled $V_1$ and across $D_2$ is labeled $V_2$.
> **Symbolic form:** not derivable from figure.
> 
> (e) Two impedances $Z_{1}=5\ \Omega$ and $Z_{2}=(5-jX_{C})\ \Omega$ are connected in parallel and this combination is connected in series with $Z_{3}=(6\cdot25+j1\cdot25)\ \Omega$. Determine the value of capacitance of $X_{C}$ to achieve resonance if the supply is 100 V, 50 Hz. [10]

---

### [EE1-2016-Q2] Dependent-Source Network Analysis for Specified Power Dissipation · LTI Impulse Response Cases & BJT Emitter-Follower Output Resistance

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Find
- **Theme (primary):** Dependent-Source Network Analysis for Specified Power Dissipation
- **Theme (secondary):** LTI Impulse Response Cases & BJT Emitter-Follower Output Resistance
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> (a) For the circuit shown in Fig. 2(a), find the value of V, if the power dissipation in the load resistance $R_{L}$ is 36 watts: [20]
> 
> **Figure ID:** FIG-EE1-2016-Q2a
> **Circuit description (netlist form):** Two interconnected subcircuits sharing a common bottom reference wire. Subcircuit 1 (left): Independent DC voltage source $V$ connected in series with a $5\ \Omega$ resistor (having voltage drop $+ V_1 -$ with positive terminal on the left) to an intermediate node; from this node, a $2\ \Omega$ resistor and a $4\ \Omega$ resistor are connected in parallel to the bottom reference rail. Subcircuit 2 (right): Dependent current source of value $2V_1$ directed upward, connected from the bottom rail to a top node; from this top node, a $10\ \Omega$ resistor connects to a node which connects to the bottom rail via a $2\ \Omega$ resistor, and via a $5\ \Omega$ resistor to the load resistor $R_L = 4\ \Omega$ connected to the bottom reference rail.
> **Symbolic form:** not derivable from figure.
> 
> (b) Consider a continuous-time LTI system for which the input $x(t)$ and output $y(t)$ are related by the following differential equation:
> $$\frac{d^{2}y(t)}{dt^{2}}-\frac{dy(t)}{dt}-2y(t)=x(t)$$
> Determine the impulse response, $h(t)$, of the system for the following cases by plotting pole-zero pattern:
> (i) The system is causal.
> (ii) The system is stable.
> (iii) The system is neither stable nor causal. [20]
> 
> (c) For the circuit shown in Fig. 2(c), calculate the resistance $R_{o}$ as seen by the output terminals. Ignore the effect of $R_{1}$ and $R_{2}$. Assume $\beta=99$ and $h_{ie}=1\text{ k}\Omega$. Comment on the value of $R_{o}$ of the circuit : [10]
> 
> **Figure ID:** FIG-EE1-2016-Q2c
> **Circuit description (netlist form):** BJT emitter follower circuit. NPN transistor with collector tied directly to positive DC rail $+V_{CC}$. Base is biased through potential divider resistors $R_1$ (connected to $+V_{CC}$) and $R_2$ (connected to ground). AC source $V_s$ is connected in series with an inductive element labeled $1\text{ k}\Omega$ to the base. Emitter is connected to ground via a $1\text{ k}\Omega$ resistor and provides output terminal $V_o$, with output resistance looking into the emitter terminal indicated as $R_o$.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2016-Q3] Coupled-Circuit Dotted Equivalent and Capacitor Voltage · Transmission-Line VSWR/Smith Chart & Op-Amp RLC Frequency Response

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Obtain
- **Theme (primary):** Coupled-Circuit Dotted Equivalent and Capacitor Voltage
- **Theme (secondary):** Transmission-Line VSWR/Smith Chart & Op-Amp RLC Frequency Response
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> (a) Obtain the dotted equivalent circuit for the coupled circuit shown in Fig. 3(a) and hence find the voltage across the capacitor: [20]
> 
> **Figure ID:** FIG-EE1-2016-Q3a
> **Circuit description (netlist form):** Transformer-coupled circuit with an iron core having two winding coils with mutual reactance $j2\ \Omega$. The left coil has self-reactance $j5\ \Omega$ and is connected in series with a $5\ \Omega$ resistor and an AC source of $10\angle 0^\circ\text{ V}$. The right coil has self-reactance $j5\ \Omega$ and is connected in series with a $5\ \Omega$ resistor and an AC source of $10\angle 90^\circ\text{ V}$. The bottom terminals of both coils are tied together and connected to a common capacitor of impedance $-j10\ \Omega$, which returns to the negative terminals of both AC sources.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) A transmission line has the following parameters:
> $$Z_{L}=(200-j200)\ \Omega,\ Z_{0}=200\ \Omega$$
> Determine the voltage standing wave ratio and reflection coefficient of the line.
> (ii) (1) Write the significance of Smith chart.
> (2) Find the length of x of the $100\ \Omega$ transmission line which converts a load impedance $Z_{L}=(100+j100)\ \Omega$ to a pure resistance. Also find the value of the resistance $R_{x}$. Assume $\text{VSWR}=2\cdot6$. [20]
> 
> (c) For the circuit shown in Fig. 3(c), get the expression for $V_{o}$. Also sketch the output waveform. Assume that the op-amp is ideal. $R=\sqrt{\frac{L}{C}},$ $\omega=\frac{1}{\sqrt{LC}}$ and $V_{i}=10\sin\omega t$: [10]
> 
> **Figure ID:** FIG-EE1-2016-Q3c
> **Circuit description (netlist form):** Ideal operational amplifier circuit with non-inverting terminal ($+$) connected to ground. Input voltage $V_i$ is connected to the inverting input ($-$) via a series connection of resistor $R$ and capacitor $C$. Negative feedback from the output terminal $V_o$ to the inverting terminal ($-$) consists of a series combination of inductor $L$ and resistor $R$.
> **Symbolic form:** $\frac{V_o(s)}{V_i(s)} = -\frac{R + sL}{R + \frac{1}{sC}} = -\frac{s(sL + R)}{sRC + 1}$

---

### [EE1-2016-Q4] Causal Signal from Its Z-Transform · EM Wave Propagation Constant/Skin Depth, Differential Op-Amp & Wave Parameters

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Determine
- **Theme (primary):** Causal Signal from Its Z-Transform
- **Theme (secondary):** EM Wave Propagation Constant/Skin Depth, Differential Op-Amp & Wave Parameters
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** no

> (a) Determine the causal signal, $x(n)$ having its z-transform
> $$X(z)=\frac{1}{(1+z^{-1})(1-z^{-1})^{2}}$$ [10]
> 
> (b) (i) Determine the propagation constant $\gamma$ for a material having $\mu_{r}=1$, $\epsilon_{r}=8$ and $\sigma=0.25\text{ pS/m}$, if the wave frequency is 1.6 MHz.
> (ii) Find the skin depth $\delta$ at a frequency of 1.6 MHz in aluminium, where $\sigma=38\cdot2\text{ MS/m}$ and $\mu_{r}=1$. Also find $\gamma$ and the wave velocity u. [20]
> 
> (c) For the op-amp circuit shown in Fig. 4(c), deduce the output voltage expression. Calculate $V_{o}$, when $R_{1}=1\text{ k}\Omega=R_{2}$, $R_{3}=1\text{ K}$ and $R_{4}=2\text{ K}$ and $V_{in}=1\text{ V}$: [10]
> 
> **Figure ID:** FIG-EE1-2016-Q4c
> **Circuit description (netlist form):** Operational amplifier circuit with single input $V_{in}$ splitting into two parallel branches: one branch connects through resistor $R_1$ to the inverting input ($-$), and the second branch connects through resistor $R_2$ to the non-inverting input ($+$). A feedback resistor $R_4$ is connected between the output terminal $V_o$ and the inverting input ($-$). Resistor $R_3$ connects from the non-inverting input ($+$) to ground.
> **Symbolic form:** $V_o = V_{in}\left[\left(\frac{R_3}{R_2+R_3}\right)\left(1+\frac{R_4}{R_1}\right) - \frac{R_4}{R_1}\right]$
> 
> (d) If a propagating wave in free space has a potential gradient at any point (x, y, z) as
> $$\overline{E}=(-\overline{i}-2\sqrt{3}\overline{j}+3\overline{k})e^{-j0\cdot04\pi(\sqrt{3}x-2y-3z)}\text{ V/m}$$
> then determine—
> (i) the vertical direction of propagation;
> (ii) the wavelength of the propagating wave;
> (iii) the frequency of the propagating wave;
> (iv) the phase velocity and phase velocity vector.
> What are the apparent velocities and wavelengths along x, y and z directions? [10]

---

## SECTION-B

### [EE1-2016-Q5] Boolean SOP Minimization and NAND-Only Realization · Synchronous Motor V-Curves, SCR di/dt Protection, AM/FM Comparison & DC Motor Torque

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS).
- **Directive:** Minimize
- **Theme (primary):** Boolean SOP Minimization and NAND-Only Realization
- **Theme (secondary):** Synchronous Motor V-Curves, SCR di/dt Protection, AM/FM Comparison & DC Motor Torque
- **Repeat cluster:** RC17 (Digital IC Families & Number Systems)
- **Has figure:** yes

> (a) Minimize the SOP terms given for a Boolean function
> $$f(A,B,C,D)=\Sigma m(2,3,8,10,11,12,14,15)$$
> Implement the minimized function using NAND gates alone. [10]
> 
> (b) What do you mean by V-curves of a synchronous motor? Draw them showing the leading power factor and lagging power factor regions. [10]
> 
> (c) The SCR shown in Fig. 5(c) has a $\frac{di}{dt}$ limit of 10 A/$\mu$s. It is to be operated from a 100 V d.c. supply with load resistance $R=50\ \Omega$.
> (i) What is the minimum value of load inductance L that will protect the SCR?
> (ii) If an $R_{s}C_{s}$ snubber is connected across the SCR with $R_{s}=500\ \Omega$, what will be the new value of load inductance L to protect the SCR against $\frac{di}{dt}$? [10]
> 
> **Figure ID:** FIG-EE1-2016-Q5c
> **Circuit description (netlist form):** DC switching circuit comprising a DC source $V_s = 100\text{ V}$ connected in series with an inductor $L$, a load resistor $R = 50\ \Omega$, and an SCR. The anode of the SCR is connected to $R$, the cathode is connected to the negative terminal of $V_s$, and a gate current $i_g$ is applied at the gate terminal.
> **Symbolic form:** not derivable from figure.
> 
> (d) Compare Amplitude Modulation (AM) and Frequency Modulation (FM). [10]
> 
> (e) A 20 hp, 230 V, 1150 r.p.m. d.c. shunt motor has four poles, four parallel armature paths and 882 armature conductors. The armature circuit resistance is $0\cdot188\ \Omega$. At rated speed and rated output, the armature current is 73 A and the field current is 1.6 A. Calculate the electromagnetic torque. [10]

---

### [EE1-2016-Q6] R-2R Ladder DAC Identification and Output Calculation · Distribution Transformer Voltage Regulation & PLL FM Demodulation

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Comparators, timers, multivibrators. Sample and hold circuits, ADCs and DACs.
- **Directive:** Identify
- **Theme (primary):** R-2R Ladder DAC Identification and Output Calculation
- **Theme (secondary):** Distribution Transformer Voltage Regulation & PLL FM Demodulation
- **Repeat cluster:** none
- **Has figure:** yes

> (a) Identify the circuit shown in Fig. 6(a). Briefly explain the same. Calculate the current i and $V_{o}$, if $V_{R}=5\text{ V}$ and $R=5\text{ k}\Omega=R_{F}$: [20]
> 
> **Figure ID:** FIG-EE1-2016-Q6a
> **Circuit description (netlist form):** 4-bit R-2R ladder DAC connected to an operational amplifier. Reference voltage $V_R$ is applied to an input shunt resistor of value $2R$ to ground, and feeds a ladder of series resistors of value $R$ and shunt branches of value $2R$. The second and fourth shunt arms (from left) are connected to the inverting input ($-$) of the op-amp. The first and third shunt arms are connected to ground. The terminating rightmost branch has a series resistance of $2R$ carrying current $i$ to ground. Feedback resistor $R_F$ connects from output $V_o$ to the inverting input ($-$). Non-inverting input ($+$) is grounded.
> **Symbolic form:** not derivable from figure.
> 
> (b) The resistances and leakage reactances of a 10 kVA, 50 Hz, 2300/230 V distribution transformer are
> $$r_{1}=3.96\ \Omega\quad\text{and}\quad r_{2}=0.0396\ \Omega\qquad x_{1}=15\cdot8\ \Omega\quad\text{and}\quad x_{2}=0.158\ \Omega$$
> Subscript 1 refers to HV and 2 refers to LV winding
> The transformer delivers rated kVA at 0.8 p.f. lagging to a load on the LV side. Find the HV side voltage necessary to maintain 230 V across load terminals. Also find the percentage voltage regulation. [20]
> 
> (c) Explain the operations of phase-locked loop used as FM demodulator with neat sketch. [10]

---

### [EE1-2016-Q7] PLA-Based Realization of Boolean Functions · Controlled-Rectifier DC Motor Drive, White Noise & Square-Wave Inverter

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Semiconductor memories. Logic implementation using programmable devices (ROM, PLA, FPGA).
- **Directive:** Realize
- **Theme (primary):** PLA-Based Realization of Boolean Functions
- **Theme (secondary):** Controlled-Rectifier DC Motor Drive, White Noise & Square-Wave Inverter
- **Repeat cluster:** none
- **Has figure:** no

> (a) What is a PLA? Realize the following functions using an appropriate PLA: [10]
> $$f_{1}=AB+CD$$
> $$f_{2}=\overline{A}B+A\overline{B}$$
> $$f_{3}=AD+BC+\overline{B}D$$
> 
> (b) A 200 V, 875 r.p.m., 150 A, separately excited d.c. motor has an armature resistance of $0\cdot06\ \Omega$. The motor armature terminals are fed from a single-phase fully controlled bridge rectifier. The input a.c. supply to bridge rectifier is 240 V, 50 Hz. Assuming continuous and ripple-free armature current, determine the following:
> (i) Firing angle of SCRs for rated torque and 750 r.p.m.
> (ii) Firing angle for rated torque and -500 r.p.m.
> Assume that field winding of the motor is connected to a constant d.c. voltage source. [20]
> 
> (c) Write a short note on white noise. [10]
> 
> (d) A single-phase full-bridge square-wave inverter is supplying power to a purely resistive load of $20\ \Omega$. The d.c. source voltage is 600 V. If the inverter is to operate at 500 Hz with an r.m.s. load voltage 500 V, find—
> (i) average power absorbed by the load;
> (ii) average source current (assume no losses in switching);
> (iii) average current of each switch. [10]

---

### [EE1-2016-Q8] Induction Motor Line Current and Power Factor at Given Slip · Class-A Chopper Load Current & FM Pre-Emphasis/De-Emphasis

- **Exam:** UPSC Mains 2016 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
- **Directive:** Find
- **Theme (primary):** Induction Motor Line Current and Power Factor at Given Slip
- **Theme (secondary):** Class-A Chopper Load Current & FM Pre-Emphasis/De-Emphasis
- **Repeat cluster:** RC26 (AC Machine Performance (Induction & Synchronous))
- **Has figure:** no

> (a) A 3-phase, 4-pole, 50 hp, 440 V, 60 Hz, Y-connected induction motor has the following parameters per phase:
> $$r_{1}=0.10\ \Omega,\quad r_{2}'=0.12\ \Omega,\quad x_{1}=0.35\ \Omega,\quad x_{2}'=0.40\ \Omega$$
> It is known that the stator core loss amounts to 1200 W and the rotational losses equal 950 W. Moreover, at no-load the motor draws a line current of 18 A at a power factor of 0.089 lagging. When the motor operates at a slip of 2.5%, find the input line current and power factor. [20]
> 
> (b) A class-A chopper circuit is supplied from a d.c. source voltage 100 V. The chopper supplies power to a series R-L load with $R=0\cdot5\ \Omega$ and $L=1\text{ mH}$. The chopper switch is ON for 1 ms in an overall period of 3 ms. Calculate average load voltage, maximum and minimum value of load current and average load current. Assume continuous current operation of the chopper. [20]
> 
> (c) Explain in detail about pre-emphasis and de-emphasis in Frequency Modulation (FM). [10]

---
