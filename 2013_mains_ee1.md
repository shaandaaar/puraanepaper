### [EE1-2013-Q1] Δ–Y Transformation for Equivalent Resistance · Fourier Series of a Square Wave, Electrostatic Charge Transfer, Op-Amp Design & Maxwell's Equations

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Determine
- **Theme (primary):** Δ–Y Transformation for Equivalent Resistance
- **Theme (secondary):** Fourier Series of a Square Wave, Electrostatic Charge Transfer, Op-Amp Design & Maxwell's Equations
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> (a) Using $\Delta\text{-}Y$ substitution, determine the resistance between a and d, in Fig. 1. [10]
> 
> **Figure ID:** FIG-EE1-2013-Q1a
> **Circuit description (netlist form):** Bridge resistor network configured as a diamond with four outer nodes a, b, c, d and a central horizontal branch between b and c. Resistor $R_{ab} = 2\ \Omega$ connects node a to node b. Resistor $R_{ac} = 2\ \Omega$ connects node a to node c. Resistor $R_{bc} = 1\ \Omega$ connects node b to node c. Resistor $R_{bd} = 2\ \Omega$ connects node b to node d. Resistor $R_{cd} = 1\ \Omega$ connects node c to node d. Terminal nodes for equivalent resistance measurement are node a and node d.
> **Symbolic form:** not derivable from figure.
> 
> (b) Figure 2 shows a square wave that is described through the range from 0 to $\pi$ by $f(t)=2$ and through the range from $\pi$ to $2\pi$ by $f(t)=0$. Find its Fourier components in the exponential series. [10]
> 
> **Figure ID:** FIG-EE1-2013-Q1b
> **Circuit description (netlist form):** Plot of a periodic square waveform $f(t)$ against $\omega_1 t$. The waveform has a constant amplitude of $+2$ over the intervals $[-\pi, -\pi/2\text{ or }0]$, $[0, \pi]$, and $[2\pi, 3\pi]$, and zero amplitude over the interval $[\pi, 2\pi]$, with a fundamental period of $T = 2\pi/\omega_1$.
> **Symbolic form:** $$f(t) = \begin{cases} 2, & 0 \le \omega_1 t < \pi \\ 0, & \pi \le \omega_1 t < 2\pi \end{cases}$$
> 
> (c) A conductor is charged by repeated contacts with a metal plate which, after each contact, is recharged to a quantity of charge Q by connecting it to a constant voltage source. If q is the charge of the conductor after the first operation, show that the ultimate charge on the conductor is $\frac{Q\cdot q}{Q-q}$. [10]
> 
> (d) Design an amplifier with a gain of +5 using one OP-AMP. Choose $R_{i}=10\text{ k}\Omega$. [10]
> 
> (e) (i) Write the Maxwell's equations including the continuity equation in vector form for time-varying fields in general medium naming each of them. [5]
> 
> (ii) Define the following parameters for an OP-AMP:
> Input offset voltage; Bias current; Slew rate; Output impedance; CMRR. [5]

---

### [EE1-2013-Q2] Unbalanced Wheatstone Bridge via Thevenin's Theorem · Ladder-Network Analysis & Multi-Capacitor RC Transient

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Determine
- **Theme (primary):** Unbalanced Wheatstone Bridge via Thevenin's Theorem
- **Theme (secondary):** Ladder-Network Analysis & Multi-Capacitor RC Transient
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> (a) Consider the unbalanced Wheatstone bridge shown in Fig. 3:
> 
> **Figure ID:** FIG-EE1-2013-Q2a
> **Circuit description (netlist form):** Unbalanced Wheatstone bridge powered by an ideal DC voltage source $E = 10\text{ V}$ connected across node c (positive) and node d (negative). Resistor $R_{ca} = 100\ \Omega$ connects node c to node a. Resistor $R_{cb} = 110\ \Omega$ connects node c to node b. Resistor $R_{ad} = 100\ \Omega$ connects node a to node d. Resistor $R_{bd} = 90\ \Omega$ connects node b to node d. A galvanometer G with an internal resistance of $1\ \Omega$ is connected across the bridge between node a and node b.
> **Symbolic form:** not derivable from figure.
> 
> The internal resistance of the galvanometer is 1 ohm. Using Thevenin's theorem, determine the galvanometer current. [20]
> 
> (b) Determine the current I in Fig. 4 using the ladder method. [20]
> 
> **Figure ID:** FIG-EE1-2013-Q2b
> **Circuit description (netlist form):** Resistive ladder network driven by a DC voltage source $V_g = 10\text{ V}$ connected in series with a $2\ \Omega$ resistor to top node a and bottom node a'. Shunt resistor of $200\ \Omega$ is connected between node a and node a'. Series resistor of $1\ \Omega$ connects top node a to node b, and series resistor of $1\ \Omega$ connects bottom node a' to node b'. Shunt resistor of $50\ \Omega$ is connected between node b and node b'. Series resistor of $2\ \Omega$ connects node b to node c, while bottom node b' is shorted directly to node c'. Shunt resistor of $100\ \Omega$ is connected between node c and node c'. A series branch consisting of a $1\ \Omega$ resistor in series with a $10\ \Omega$ load resistor is connected between node c and node c', with current $I$ flowing downward through the $10\ \Omega$ resistor.
> **Symbolic form:** not derivable from figure.
> 
> (c) In Fig. 5, capacitor $C_{1}$ is initially charged at 100 V and the other two capacitors are initially uncharged. The switch S is closed at time $t=0$. Find the current flowing through the resistor as a function of time. [10]
> 
> **Figure ID:** FIG-EE1-2013-Q2c
> **Circuit description (netlist form):** Circuit with a continuous bottom reference rail. Capacitor $C_1 = 1\ \mu\text{F}$ is connected between the left terminal of switch S and the bottom rail. Switch S connects the top of $C_1$ to a node common to the top terminal of capacitor $C_2 = 1\ \mu\text{F}$ and the left terminal of resistor $R = 500\ \Omega$. Bottom terminal of $C_2$ is connected to the bottom rail. The right terminal of resistor $R$ is connected to the top terminal of capacitor $C_3 = 2\ \mu\text{F}$, whose bottom terminal is connected to the bottom rail.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2013-Q3] Plane-Wave Radiation Intensity & Energy Division (E–H Fields) · Transmission-Line Wavelength & Phase Constant

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves.
- **Directive:** Calculate
- **Theme (primary):** Plane-Wave Radiation Intensity & Energy Division (E–H Fields)
- **Theme (secondary):** Transmission-Line Wavelength & Phase Constant
- **Repeat cluster:** none
- **Has figure:** no

> (a) Plane monochromatic waves are propagated parallel to the z-axis in both positive and negative directions. At the origin, the field strengths are given by
> $$E_{x}=A\cos(\omega t\pm kz)$$
> $$H_{x}=0$$
> $$E_{y}=0$$
> $$H_{y}=B\cos(\omega t\pm kz)$$
> Calculate the mean intensity of the radiation in each of the two directions in terms of A, B and the constants of the medium. [20]
> 
> (b) Show that the energy stored in a plane electromagnetic wave is equally divided between the electric and magnetic fields. [20]
> 
> (c) A lossless transmission line with air dielectric is 12 m long. What is the line length in wavelengths and what is the value of the phase constant $\beta$ at 15 MHz? [10]

---

### [EE1-2013-Q4] Op-Amp Lossy Integrator Design · 7805 Linear Voltage Regulator & Second-Order Butterworth Filter Design

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Filters; sinusoidal oscillators: criterion for oscillation; single-transistor and OPAMP configurations. Function generators and wave-shaping circuits.
- **Directive:** Design
- **Theme (primary):** Op-Amp Lossy Integrator Design
- **Theme (secondary):** 7805 Linear Voltage Regulator & Second-Order Butterworth Filter Design
- **Repeat cluster:** RC05 (Op-Amp Oscillator/Filter Design)
- **Has figure:** no

> (a) Using an OP-AMP, design a lossy integrator whose peak gain is 20 dB and the gain is 3 dB down from its peak when $\omega=10000\text{ rad/sec}$. Use a capacitance of $0.01\ \mu\text{F}$. [20]
> 
> (b) Design a voltage regulator using 7805 IC to get a voltage output of 8 V. [10]
> 
> (c) Design a second-order low-pass Butterworth filter having a cutoff frequency of 1 kHz. Choose $C=0.1\ \mu\text{F}$. The damping factor $\alpha$ is given to be 1.414. Choose $R_{i}$ as $10\text{ k}\Omega$. [20]

---

### [EE1-2013-Q5] TTL Logic-Level Specifications · DC Universal Motors, DC-DC Converter Cores, Receiver Selectivity & Multiplexer Logic

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS).
- **Directive:** Specify
- **Theme (primary):** TTL Logic-Level Specifications
- **Theme (secondary):** DC Universal Motors, DC-DC Converter Cores, Receiver Selectivity & Multiplexer Logic
- **Repeat cluster:** RC17 (Digital IC Families & Number Systems)
- **Has figure:** no

> (a) Specify power supply voltage range, output logic 1 level voltage and output logic 0 level voltage for standard TTL gates. [10]
> 
> (b) Why are 'high power to size ratio machines' like mixer, hand drill, vacuum cleaner, etc., using DC universal motor? [10]
> 
> (c) Specify the type of core used in DC-DC converter and explain why iron core is not used in it. [10]
> 
> (d) How is good selectivity achieved in a superheterodyne receiver? [10]
> 
> (e) Draw a block diagram to implement logic $F=A\cdot B$ using a $4\times 1$ multiplexer. [10]

---

### [EE1-2013-Q6] Six-Variable Karnaugh Map Minimization · Sequential Machine State-Table Reduction & Universal Logic Gates

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS).
- **Directive:** Determine
- **Theme (primary):** Six-Variable Karnaugh Map Minimization
- **Theme (secondary):** Sequential Machine State-Table Reduction & Universal Logic Gates
- **Repeat cluster:** RC17 (Digital IC Families & Number Systems)
- **Has figure:** no

> (a) Determine the MSP form of the switching function
> $$F(u, v, w, x, y, z) = \Sigma(0, 1, 4\text{--}6, 11, 14\text{--}17, 20\text{--}22, 30, 32, 33, 36, 37, 48, 49, 52, 53, 59, 63)$$
> using 6-variable Karnaugh map. [20]
> 
> (b) A sequential machine produces an output of 1 only when exactly two 0's are followed by a 1 or exactly two 1's are followed by a 0. Determine the reduced state table of the machine. [20]
> 
> (c) Assuming that logic 0 is available, show that the INCLUSION gate is a universal building block. [10]

---

### [EE1-2013-Q7] Transformer No-Load Power Factor from Test Data · SCR-Based DC Motor Speed Control & MOSFET Gate-Capacitance Effects

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers.
- **Directive:** Determine
- **Theme (primary):** Transformer No-Load Power Factor from Test Data
- **Theme (secondary):** SCR-Based DC Motor Speed Control & MOSFET Gate-Capacitance Effects
- **Repeat cluster:** none
- **Has figure:** no

> (a) A single-phase transformer of turns ratio 3:1 is connected to 110 V AC mains. It draws a primary current of 1 A at unity p.f. when delivering power to a load with an efficiency of 85%. If the no-load current of the transformer is 0.43 A, determine the p.f. at no load. [20]
> 
> (b) Draw the circuit diagram of SCR-based control circuit for full-range speed control of a shunt DC motor using two SCRs to run from single-phase AC mains. [20]
> 
> (c) What is the effect of gate capacitance of MOSFET in driving circuit when it is used in high-frequency power switching applications like sine wave inverter or DC-DC converter? [10]

---

### [EE1-2013-Q8] FM Signal Parameter Extraction · Wiener-Hopf Optimum Filtering & FM-vs-AM Noise Performance

- **Exam:** UPSC Mains 2013 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Phase and Frequency modulation: PM & FM signals; narrows band FM; generation & detection of FM and PM, Deemphasis, Preemphasis.
- **Directive:** Find
- **Theme (primary):** FM Signal Parameter Extraction
- **Theme (secondary):** Wiener-Hopf Optimum Filtering & FM-vs-AM Noise Performance
- **Repeat cluster:** none
- **Has figure:** no

> (a) A certain FM signal is represented by $V(t)=10\sin(10^{8}t+15\sin 2000t)\text{ volts}$, where t is in seconds. Find the parameters of the FM wave. [20]
> 
> (b) Show that the Wiener-Hopf filter is practical only when the input SNR is small. [20]
> 
> (c) Explain why signal to noise ratio is better in FM receiver as compared to AM. Draw suitable diagrams in support of your explanation. [10]

---
