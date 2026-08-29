## SECTION A

### [EE1-2009-Q1] Network Transients & Coupled Circuits · BJT Bias Analysis, DC Machine Compounding & Random Variables

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Find
- **Theme (primary):** Network Transients & Coupled Circuits
- **Theme (secondary):** BJT Bias Analysis, DC Machine Compounding & Random Variables
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh))
- **Has figure:** yes

> 1. (a) (i) The current[cite: 1]
> $$i(t) = 2t \quad 0 \le t \le 1$$[cite: 1]
> $$= -2t + 4 \quad 1 \le t \le 2$$[cite: 1]
> $$= 0 \quad \text{otherwise}$$[cite: 1]
> is passed through a capacitor of 0.5 farad. Find the expression for the voltage across the capacitor in the time interval $1 \le t \le 2$. [5][cite: 1]
> 
> (ii) In the circuit given below, A and B are mutually coupled coils. Determine coefficient of coupling K between them so that the circuit is in resonance. [5][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q1a-ii
> **Circuit description (netlist form):** A single-loop AC series circuit containing an AC voltage source in series with a $10\ \Omega$ resistor, coupled inductor A with reactance $j8\ \Omega$, a capacitor with reactance $-j20\ \Omega$, and coupled inductor B with reactance $j10\ \Omega$. Mutual coupling exists between coil A and coil B with coupling coefficient $K$, with polarity dots placed on the left terminal of coil A and the right terminal of coil B.
> **Symbolic form:** not derivable from figure.
> 
> (iii) Three identical impedances of $5\angle-30^{\circ}$ ohms are connected in star to a 3-phase, 4-wire, 400 volts cba system. Express the current in phase 'a' in phasor form, assuming $V_{bc}$ as a reference phasor. [5][cite: 1]
> 
> (b) For the circuit shown in the figure, assume $\beta = h_{FE} = 100$.[cite: 1]
> 
> (i) Find if the silicon transistor is in cut-off, saturation or in the active region. [10][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q1b
> **Circuit description (netlist form):** NPN BJT transistor $Q$ has its base connected via a $7\text{ k}\Omega$ resistor to the negative terminal of a $3\text{ V}$ DC source whose positive terminal is connected to ground. The emitter is connected to ground via resistor $R_e = 500\ \Omega$. The collector is connected via a $3\text{ k}\Omega$ resistor to a $-10\text{ V}$ DC supply rail. The output node $v_o$ is connected directly to the collector.
> **Symbolic form:** not derivable from figure.
> 
> (ii) Find $v_{0}$. [5][cite: 1]
> 
> (c) (i) Explain differential compounding of a d.c. machine. [5][cite: 1]
> 
> (ii) Which type of compounding is not commonly used? Why? Explain with relevant characteristics for a motor and a generator. [10][cite: 1]
> 
> (d) (i) Explain the mathematical expressions for statistical average, mean, variance and correlation coefficient of a random variable. [4][cite: 1]
> 
> (ii) Explain, using analytical expressions, stationarity, time averages and ergodicity. [6][cite: 1]

---

### [EE1-2009-Q2] LTI System Analysis (Fourier & Z-Transform) · Digital Counter Design & DC Chopper Drives

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Representation of continuous-time and discrete-time signals and systems; LTI systems; convolution; impulse response; time-domain analysis of LTI systems based on convolution and differential/difference equations.
- **Directive:** Find
- **Theme (primary):** LTI System Analysis (Fourier & Z-Transform)
- **Theme (secondary):** Digital Counter Design & DC Chopper Drives
- **Repeat cluster:** none
- **Has figure:** yes

> 2. (a) (i) Using Fourier transforms, find the impulse response of the system described by the equation[cite: 1]
> $$\dot{y}(t) + 3y(t) = x(t) + 3\dot{x}(t)$$[cite: 1]
> where x is an input and y is an output. [10][cite: 1]
> 
> (ii) Using z transforms, obtain the convolution sum of two sequences, $y(n) = x_{1}(n) * x_{2}(n)$, where[cite: 1]
> $$x_{1}(n) = \{1 \quad 2 \quad -1 \quad 0 \quad 3\}$$[cite: 1]
> $$x_{2}(n) = u(n) - u(n-3)$$[cite: 1]
> $u(n)$ is a unit step sequence. [10][cite: 1]
> 
> (b) The figure below shows a divide-by-N counter.[cite: 1]
> 
> (i) Find N. Assume initial value of $Q_{0} = 1$, $Q_{1} = 0$ and $Q_{2} = 0$. [10][cite: 1]
> 
> (ii) Repeat Part (i), if initially $Q_{0} = 1$, $Q_{1} = 0$ and $Q_{2} = 1$. [10][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q2b
> **Circuit description (netlist form):** Synchronous counter comprising three JK flip-flops with outputs $(Q_2, \overline{Q}_2)$, $(Q_1, \overline{Q}_1)$, and $(Q_0, \overline{Q}_0)$ driven by a common Clock line to their Ck inputs. Flip-flop 2 inputs: $J_2$ is connected to $\overline{Q}_0$, $K_2$ is connected to $Q_1$. Flip-flop 1 inputs: $J_1$ is connected to $Q_2$, $K_1$ is connected to $\overline{Q}_0$. Flip-flop 0 inputs: $J_0$ is connected to $\overline{Q}_1$, $K_0$ is connected to $Q_1$.
> **Symbolic form:** not derivable from figure.
> 
> (c) (i) A d.c. series motor is powered by a d.c. chopper. The armature resistance is $R_{a} = 0.03\text{ ohm}$ and the field resistance $R_{f} = 0.05\text{ ohm}$. The back e.m.f. constant of the motor is $K_{v} = 15\cdot27\text{ mV/A-rad/s}$. The average armature current $I_{a} = 450\text{ A}$. The armature current is continuous and has negligible ripple. If the duty cycle of the chopper is 75%, determine-[cite: 1]
> 1. the input power from the source;[cite: 1]
> 2. the equivalent input resistance of chopper drive;[cite: 1]
> 3. the motor speed. [10][cite: 1]
> 
> (ii) Give the circuit of a single-phase half-bridge inverter. Draw the load current waveform for a highly inductive load. Explain the purpose of the feedback diodes. [10][cite: 1]

---

### [EE1-2009-Q3] Diode Wave-Shaping Circuits · Synchronous Machine Hunting & EM Wave Reflection

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Diode circuits Clipping, clamping, rectifier.
- **Directive:** Construct
- **Theme (primary):** Diode Wave-Shaping Circuits
- **Theme (secondary):** Synchronous Machine Hunting & EM Wave Reflection
- **Repeat cluster:** none
- **Has figure:** yes

> 3. (a) Construct circuits using diodes which exhibit terminal characteristics as shown in Part (i) and Part (ii) of the figure below. Assume diodes to be ideal. [20][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q3a
> **Circuit description (netlist form):** Two V-I characteristics. Part (i): Current $I = 0$ for $-V_1 \le V \le V_1$; for $V > V_1$, current increases linearly with a positive slope; for $V < -V_1$, current decreases linearly in the negative quadrant with positive slope. Part (ii): For $V > 0$, current starts at $I_1$ and increases linearly with positive slope; for $V < 0$, current starts at $-I_1$ and decreases linearly with positive slope; at $V = 0$, current transitions abruptly from $-I_1$ to $I_1$.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) Explain the phenomenon of hunting in a synchronous machine. [10][cite: 1]
> 
> (ii) A 3-phase, star-connected alternator is rated at 1600 KVA, 13.5 kV. The effective armature resistance and synchronous reactance are 1.5 ohms and 30 ohms per phase respectively. Find the regulation for a load of 1280 kW at rated voltage and 0.8 lagging power factor. [10][cite: 1]
> 
> (c) A plane wave in free space $(z \le 0)$ is incident normally on a large block of material with $\epsilon_{r} = 12$, $\mu_{r} = 3$ and $\sigma = 0$ which occupies $z \ge 0$. If the incident electric field is[cite: 1]
> $$E = 30\cos(\omega t - z)a_{y}\text{ V/m}$$[cite: 1]
> determine-[cite: 1]
> (i) the standing wave ratio;[cite: 1]
> (ii) the reflected magnetic field.[cite: 1]
> $[\mu_{0} = 4\pi \times 10^{-7}\text{ H/m}]$ [20][cite: 1]

---

### [EE1-2009-Q4] Nodal & Mesh Circuit Analysis · DC Choppers & AM/FM Detection

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Determine
- **Theme (primary):** Nodal & Mesh Circuit Analysis
- **Theme (secondary):** DC Choppers & AM/FM Detection
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh))
- **Has figure:** yes

> 4. (a) (i) For the circuit shown below, determine the numerical value of $i_{1}$, using nodal analysis. [12][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q4a-i
> **Circuit description (netlist form):** Planar DC circuit with a common ground reference at the bottom. A branch with a $2\text{ V}$ independent DC source (positive terminal at top) in series with a $0\cdot5\ \Omega$ resistor connects to an upper-left node. A $1\ \Omega$ resistor connects the upper-left node to a center top node, with current $i_1$ flowing from left to right. A $2\ \Omega$ bridging resistor connects the upper-left node directly to the upper-right node. From the center top node to ground, a $0\cdot5\ \Omega$ resistor is connected in parallel with an independent $1\text{ A}$ current source directed upwards. A $1\ \Omega$ resistor connects the center top node to the upper-right node. From the upper-right node, a $1\ \Omega$ resistor connects to ground, and an independent $2\text{ V}$ voltage source (positive terminal at top) connects to ground in parallel.
> **Symbolic form:** not derivable from figure.
> 
> (ii) For the network shown below, write mesh equations in vector-matrix form for the loop currents $i_{1}$ and $i_{2}$. Assume mutual inductances between coils $L_{1}$ & $L_{3}$ and coils $L_{2}$ & $L_{3}$ as $M_{13}$ and $M_{23}$ respectively. [8][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q4a-ii
> **Circuit description (netlist form):** Two-mesh AC circuit. Mesh 1 carries clockwise current $i_1$ and contains voltage source $v(t)$ (positive on top), resistor $R_1$, and inductor $L_1$ (dot at left terminal) connected to a common branch. The common branch consists of inductor $L_3$ (dot at top terminal) in series with resistor $R_2$. Mesh 2 carries clockwise current $i_2$ containing the common branch ($L_3$ and $R_2$), inductor $L_2$ (dot at right terminal), and resistor $R_3$. Mutual inductances are $M_{13}$ between $L_1, L_3$ and $M_{23}$ between $L_2, L_3$.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) How are choppers classified, based on direction of current and voltage? Indicate with $v_{L}-i_{L}$ diagrams. [8][cite: 1]
> 
> (ii) For a step-down chopper, derive an expression for peak-to-peak ripple current in terms of supply voltage $V_{s}$, output voltage $V_{0}$, frequency of operation and inductance. [12][cite: 1]
> 
> (c) (i) An AM wave[cite: 1]
> $$15[1+0\cdot4\cos 2\pi 10^{3}t]\cdot\cos 2\pi 10^{6}t$$[cite: 1]
> is to be detected by a linear diode detector.[cite: 1]
> 1. Find the time constant, $\tau$.[cite: 1]
> 2. Find the value of R, if the capacitor used is 100 pF. [8][cite: 1]
> 
> (ii) An FM signal defined as[cite: 1]
> $$x_{c}(t) = A_{c}\cos\left[\omega_{c}t + k_{f}\int_{-\infty}^{t}m(t)dt\right]$$[cite: 1]
> is applied to a high-pass RC filter, where $\text{RC} \ll \frac{1}{\omega}$ for $\omega$ representing the FM frequency band. Show if an envelope detector after the filter can demodulate the FM signal. [12][cite: 1]

---

## SECTION B

### [EE1-2009-Q5] Signal Transform Analysis (Laplace & Impulse Response) · Digital Logic Design, Controlled Rectifiers & EM Wave Parameters

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Sketch
- **Theme (primary):** Signal Transform Analysis (Laplace & Impulse Response)
- **Theme (secondary):** Digital Logic Design, Controlled Rectifiers & EM Wave Parameters
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** yes

> 5. (a) (i) Sketch the function[cite: 1]
> $$f(n) = u(n+4) - u(n)$$[cite: 1]
> and express it as a sum of shifted unit impulses. $u(n)$ is a unit step sequence. [5][cite: 1]
> 
> (ii) A series RC circuit with $R = 1\ \Omega$, $C = 1\text{ F}$ is excited by input $r(t) = e^{-2t}u(t)$. Obtain the expression for voltage across the capacitance in time domain, using the impulse response of the system. [5][cite: 1]
> 
> (iii) Determine Laplace transform of the function $f(t)$ shown below. [5][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q5a-iii
> **Circuit description (netlist form):** Plot of a triangular pulse $f(t)$ versus time $t$. The signal starts at $f(0) = 0$, rises linearly to a maximum amplitude of $2$ at $t = 1$, ramps linearly down to $0$ at $t = 2$, and remains $0$ for $t > 2$.
> **Symbolic form:** $f(t) = 2t\,[u(t)-u(t-1)] + (4-2t)\,[u(t-1)-u(t-2)]$
> 
> (b) Realize a half-adder circuit using only NOR gates. [15][cite: 1]
> 
> (c) With a neat circuit diagram, explain the operation of a $180^{\circ}$ variable half-wave rectifier along with its gate trigger circuit. [15][cite: 1]
> 
> (d) (i) Define the following:[cite: 1]
> Skin depth; Intrinsic impedance; Phase velocity; Group velocity; Surface impedance. [$2\times 5 = 10$][cite: 1]
> 
> (ii) In a medium[cite: 1]
> $$E = 16e^{-0\cdot05x}\sin(2\times 10^{8}t - 2x)a_{z}\text{ V/m}$$[cite: 1]
> Determine the skin depth. $[\epsilon_{0} = \frac{10^{-9}}{36\pi}\text{ F/m}]$ [5][cite: 1]

---

### [EE1-2009-Q6] Two-Port Network Parameters & Maximum Power Transfer · BJT Amplifier Biasing & DC Machine Excitation

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Two-port networks.
- **Directive:** Determine
- **Theme (primary):** Two-Port Network Parameters & Maximum Power Transfer
- **Theme (secondary):** BJT Amplifier Biasing & DC Machine Excitation
- **Repeat cluster:** none
- **Has figure:** yes

> 6. (a) (i) A Bridge-T network is made up of four capacitances, each having a value of 1 farad. Determine y parameters of this network, assuming that this Bridge-T network can be treated as parallel interconnection of two two-port networks. [12][cite: 1]
> 
> (ii) For the network shown below, determine $R_{L}$ which will receive maximum power. [8][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q6a-ii
> **Circuit description (netlist form):** A DC network with an independent $15\text{ V}$ voltage source in series with a $5\ \Omega$ resistor carrying current $I_1$ into an internal node. An independent $10\text{ A}$ current source is connected from ground to this node. Connected in series from this node to the output is a dependent voltage source $10I_1$ (positive terminal on the left) in series with variable load resistor $R_L$. The right terminal of $R_L$ is connected through a $1\ \Omega$ resistor and a series $10\text{ V}$ voltage source (positive terminal at the top) to ground.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) An n-p-n silicon transistor is used in a common-collector circuit as shown in the figure below. The circuit component values are $V_{CC} = 3\cdot0\text{ V}$, $R_{e} = 1\text{ K}$, $R_{1} = R_{2} = 5\text{ K}$. If $\beta = 44$, find the quiescent point. [12][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q6b-i
> **Circuit description (netlist form):** Common-collector NPN BJT amplifier. Supply rail $V_{CC} = 3\cdot0\text{ V}$ connects to the collector of the transistor and to bias resistor $R_1 = 5\text{ k}\Omega$. Resistor $R_2 = 5\text{ k}\Omega$ connects from base to ground. Emitter resistor $R_e = 1\text{ k}\Omega$ connects the emitter to ground.
> **Symbolic form:** not derivable from figure.
> 
> (ii) Three identical cascaded stages have an overall upper 3-dB frequency of 20 kHz and a lower 3-dB frequency of 20 Hz. What are $f_{L}$ and $f_{H}$ of each stage? Assume non-interacting stages. [8][cite: 1]
> 
> (c) (i) Explain how a separately excited d.c. generator and a d.c. shunt generator be operated below the knee of its magnetization curve. [10][cite: 1]
> 
> (ii) A series motor has an armature resistance of 0.7 ohm and field resistance of 0.3 ohm. It takes a current of 15 A from a 200 V supply and runs at 800 r.p.m. Find the speed at which it will run, when connected in series with a 5-ohm resistance and taking the same current at the same supply voltage. [10][cite: 1]

---

### [EE1-2009-Q7] Combinational & Sequential Digital Logic Design · Power Semiconductor Devices & Superheterodyne Receivers

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Combinational circuits arithmetic circuits, code converters, multiplexers and decoders.
- **Directive:** Design
- **Theme (primary):** Combinational & Sequential Digital Logic Design
- **Theme (secondary):** Power Semiconductor Devices & Superheterodyne Receivers
- **Repeat cluster:** RC03 (Digital Logic Design (Combinational))
- **Has figure:** yes

> 7. (a) (i) Design a combinational logic circuit which produces an output equal to '1' if the input variables have more 1's in the sequence than 0's. The output is zero otherwise. Design the circuit for three variable inputs. Draw the realization. [10][cite: 1]
> 
> (ii) The waveforms shown in the figure below are applied to-[cite: 1]
> 1. positive edge-triggered SR flip-flop;[cite: 1]
> 2. master-slave SR flip-flop.[cite: 1]
> Draw the output waveforms in each case. [10][cite: 1]
> 
> **Figure ID:** FIG-EE1-2009-Q7a-ii
> **Circuit description (netlist form):** Digital timing diagram displaying three aligned waveforms (Clock, S, and R) partitioned across ten consecutive time intervals labeled a through j. Clock provides regular periodic square pulses. Inputs S and R transition between logic HIGH and LOW states across the intervals.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) Distinguish between voltage-controlled power devices and current-controlled power devices with examples. [6][cite: 1]
> 
> (ii) What are the characteristic features of a GTO in relation to a thyristor? [8][cite: 1]
> 
> (iii) Distinguish between the minimum current required to turn-on a thyristor and the minimum current to keep the thyristor in conduction. Explain with reference to the static characteristics of a thyristor. [6][cite: 1]
> 
> (c) (i) Explain sensitivity, selectivity, fidelity and tracking in super-heterodyne receiver with relevant diagram. [6][cite: 1]
> 
> (ii) What is tracking error in super-heterodyne receiver? How is receiver aligned to achieve three-point tracking? [6][cite: 1]
> 
> (iii) Bring out the SSB spectrum with modulating signal[cite: 1]
> $$m(t) = \cos 2\pi 1500t + \cos 2\pi 3000t$$[cite: 1]
> and carrier is[cite: 1]
> $$c(t) = \cos 2\pi 15000t$$ [8][cite: 1]

---

### [EE1-2009-Q8] Sampling Theorem & Transform Techniques (Z & Fourier) · Transformer O.C. Test, Induction Motor Losses & Transmission Line Matching

- **Exam:** UPSC Mains 2009 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Determine
- **Theme (primary):** Sampling Theorem & Transform Techniques (Z & Fourier)
- **Theme (secondary):** Transformer O.C. Test, Induction Motor Losses & Transmission Line Matching
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** no

> 8. (a) (i) A signal $x(t) = 1 + \cos 100\pi t$ is sampled with sampling interval of 0.02 second. Can the original signal be recovered from these samples? [5][cite: 1]
> 
> (ii) Find z transform of the function[cite: 1]
> $$f(n) = a^{n}\cos\left(\frac{n\pi}{2}\right)u(n)$$[cite: 1]
> Sketch its RoC. [8][cite: 1]
> 
> (iii) Determine Fourier transform of the function $f(t) = e^{-a|t|}$. Sketch its magnitude spectrum. Assume $a > 0$. [7][cite: 1]
> 
> (b) (i) A single-phase, 50 Hz, 1200/120 V transformer gave the following results of open-circuit test with high-voltage winding open circuited-applied voltage 120 V, current 16 A, power input 400 W. Find magnetizing and core-loss components of no-load current. [8][cite: 1]
> 
> (ii) The power input to a 50 Hz, 4-pole induction motor running at 1442 r.p.m. is 60 kW. Find the total mechanical power developed and the rotor copper loss per phase, if the total stator loss is 1 kW. [12][cite: 1]
> 
> (c) (i) What is characteristic impedance of a transmission line? Write the expression of characteristic impedance of lossless line and distortionless line in terms of the primary constants R, L, G, C of the transmission line. What is the relation between characteristic impedance and input impedance of a matched line? [8][cite: 1]
> 
> (ii) Explain the use of quarter-wave transformer for transmission line matching. [6][cite: 1]
> 
> (iii) A lossless transmission line having characteristic impedance of 500 $\Omega$ is connected to a load $Z_{L}$. Determine the reflection coefficient and transmission coefficient. [6][cite: 1]

---
