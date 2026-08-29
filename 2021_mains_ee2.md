# PAPER II

### [EE2-2021-Q1] State-Space Controllability Check · Per-Unit System Voltage, Programming Terminology, Instrument Readings & DPCM Processing Gain

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** State-variable representation and analysis of control systems.
- **Directive:** Check
- **Theme (primary):** State-Space Controllability Check
- **Theme (secondary):** Per-Unit System Voltage, Programming Terminology, Instrument Readings & DPCM Processing Gain
- **Repeat cluster:** RC11 (State-Variable/State-Space Analysis)
- **Has figure:** yes

> (a) A system is described by the following state equations : [10]
> $$\dot{x}_1=x_1+x_2+3x_3$$
> $$\dot{x}_2=2x_1+3x_2+u_1$$
> $$\dot{x}_3=2x_2+x_3+u_2$$
> Check the controllability of the system.
>
> (b) A single phase, single line diagram of a power system is shown in figure. Find the sending end voltage and the value of load resistance in p.u. referred to sending end if the voltage across load resistance is $9.8\text{ KV}$. [10]
>
> **Figure ID:** FIG-EE2-2021-Q1b
> **Circuit description (netlist form):** Single-phase single-line diagram. Sending-end voltage source terminal $V_S$ connected to primary of step-up transformer 1 ($11/33\text{ KV}$, $10\text{ MVA}$, $X=10\%$). Secondary of transformer 1 connects via transmission line to primary of step-down transformer 2 ($33/10\text{ KV}$, $10\text{ MVA}$, $X=12\%$). Secondary of transformer 2 is connected to receiving-end bus $V_R$, feeding a load resistance of $8\text{ }\Omega$ connected to ground.
> **Symbolic form:** not derivable from figure.
>
> (c) Explain the following related to computer programming: [10]
> (i) Machine Language
> (ii) Assembly Language
> (iii) Compiler
> (iv) Interpreter
> (v) ASCII
>
> (d) A current of $(0.5+0.3\sin\omega t-0.2\sin 2\omega t)\text{ amps}$ is passed through the circuit shown in figure. Determine the reading of each instrument if $\omega=10^6\text{ rad/sec}$. [10]
>
> **Figure ID:** FIG-EE2-2021-Q1d
> **Circuit description (netlist form):** Series-connected measurement network. Input current $i$ enters a parallel combination of inductor $1\text{ mH}$ and an electrostatic voltmeter, which is in series with a parallel combination of resistor $1000\text{ }\Omega$ and a second electrostatic voltmeter. This is followed in series by a Moving Coil (MC) ammeter and a Moving Iron (MI) ammeter to the return terminal.
> **Symbolic form:** not derivable from figure.
>
> (e) A DPCM system uses a linear predictor with a single tap. The normalized autocorrelation function of the input signal for a lag of one sampling interval is 0.75. The predictor is designed to minimize the prediction error variance. Determine the processing gain attained by the use of this predictor. [10]

---

### [EE2-2021-Q2] Sequence Networks and Load Sequence Impedance · Block-Diagram Reduction of an RC Ladder Network & Convolutional Code Free Distance

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** symmetrical components, analysis of symmetrical and unsymmetrical faults.
- **Directive:** Draw and calculate
- **Theme (primary):** Sequence Networks and Load Sequence Impedance
- **Theme (secondary):** Block-Diagram Reduction of an RC Ladder Network & Convolutional Code Free Distance
- **Repeat cluster:** RC29 (Power System Fault Analysis (Symmetrical Components))
- **Has figure:** yes

> (a) Draw the sequence networks and calculate the load sequence $Z_2$ of a load circuit as shown in figure. The load circuit is connected to a balanced three phase supply. The value of $z_1$, $z_2$ and $z_n$ are $(4+j6)\text{ }\Omega$, $-j45\text{ }\Omega$ and $j4\text{ }\Omega$. [20]
>
> **Figure ID:** FIG-EE2-2021-Q2a
> **Circuit description (netlist form):** Three-phase unbalanced/combined load connected to lines R, Y, B. A star-connected branch with identical phase impedance $z_1$ in lines R, Y, B meets at neutral point $N$, with neutral impedance $z_n$ connected between $N$ and ground. In parallel, a delta-connected branch with identical impedance $z_2$ is connected between phases R-Y, Y-B, and B-R.
> **Symbolic form:** not derivable from figure.
>
> (b) For the network shown in figure, draw a block diagram representing each circuit element by a block. Use block diagram reduction technique to obtain the transfer function of the network. The voltage $V_i(t)$ is the applied input and the voltage across the capacitor $V_o(t)$ is the output. [20]
>
> **Figure ID:** FIG-EE2-2021-Q2b
> **Circuit description (netlist form):** Two-stage RC ladder network. Input node $V_i(t)$ supplies current $I_1(t)$ through series resistor $R_1$ to intermediate node $V_1(t)$. Shunt capacitor $C_1$ is connected between node $V_1(t)$ and the common ground rail. Series resistor $R_2$ carries current $I_2(t)$ from node $V_1(t)$ to output node $V_o(t)$. Shunt capacitor $C_2$ is connected between output node $V_o(t)$ and the common ground rail.
> **Symbolic form:** $$\frac{V_o(s)}{V_i(s)} = \frac{1}{R_1 R_2 C_1 C_2 s^2 + (R_1 C_1 + R_1 C_2 + R_2 C_2)s + 1}$$
>
> (c) A convolutional code is described by [10]
> $$g_1=\begin{bmatrix}1 & 1 & 0\end{bmatrix},\quad g_2=\begin{bmatrix}1 & 0 & 1\end{bmatrix},\quad g_3=\begin{bmatrix}1 & 1 & 1\end{bmatrix}.$$
> Find the transfer function and the free distance for this code. Also verify whether or not this code is catastrophic.

---

### [EE2-2021-Q3] Busbar Differential Protection: Stability and Pickup Settings · Optimum Detector Error Probability (Laplacian Noise) & Moving-Iron Voltmeter DC Error

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers.
- **Directive:** Find
- **Theme (primary):** Busbar Differential Protection: Stability and Pickup Settings
- **Theme (secondary):** Optimum Detector Error Probability (Laplacian Noise) & Moving-Iron Voltmeter DC Error
- **Repeat cluster:** RC16 (Circuit-Breaker/Relay Protection Principles)
- **Has figure:** no

> (a) A solidly earthed $400\text{ KV}$, 3 phase busbar system is connected with two incoming and four outgoing lines (feeders). A differential protection is provided with switchgear of $4000\text{ MVA}$ capacity having the following parameters: [20]
> CT secondary resistance $=0.8\text{ }\Omega$
> Lead wire resistance $=1.2\text{ }\Omega$
> Relay load $=1.0\text{ }\Omega$
> CT magnetization current $=0.3\text{ mA/V}$
> Max. full load current in one feeder $=100\text{ A}$
> Voltage setting of over current $\text{relay}=100\text{ V}$
> If the O.C. relay in the spill path is set at $1\cdot 0\text{ A}$, find the following:
> (a) The maximum 'through fault' current up to which the protection scheme remains stable.
> (b) Whether the switchgear is capable to handle maximum through fault current.
> (c) The value of minimum internal fault current that can be detected by protection scheme.
> (d) The pick-up setting for detecting minimum internal fault current of $90\text{ Amp}$.
>
> (b) Consider a signal detector with an input [20]
> $$r=\pm A+n$$
> where $+A$ and $-A$ occur with equal probability and the noise variable $n$ is characterized by the Laplacian pdf shown.
>
> **Figure ID:** FIG-EE2-2021-Q3b
> **Circuit description (netlist form):** Symmetrical plot of the Laplacian probability density function $p(n) = \frac{1}{\sqrt{2}\sigma} e^{-|n|\frac{\sqrt{2}}{\sigma}}$ plotted against random variable $n$, centered symmetrically at $n=0$ with maximum value $\frac{1}{\sqrt{2}\sigma}$ and decaying exponentially for positive and negative values of $n$.
> **Symbolic form:** $$p(n)=\frac{1}{\sqrt{2}\sigma} e^{-|n|\frac{\sqrt{2}}{\sigma}}$$
>
> (i) Determine the probability of error as a function of the parameters A and $\sigma$.
> (ii) Determine the SNR required to achieve an error probability of $10^{-6}.$
>
> (c) A coil of $300\text{ V}$ moving iron voltmeter has a resistance of $500\text{ ohms}$ and an inductance of $0\cdot 8\text{ H}$. The instrument reads correctly at $50\text{ Hz}$ AC supply and takes $100\text{ mA}$ at full scale deflection. What is the percentage error in the instrument reading, when it is connected to $200\text{ V}$ DC supply. [10]

---

### [EE2-2021-Q4] Transmission-Line Charging MVAR and Cable Insulation Sizing · Anderson's Bridge Balance Condition & Non-Minimum-Phase Bode Phase Calculation

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation;
- **Directive:** Calculate
- **Theme (primary):** Transmission-Line Charging MVAR and Cable Insulation Sizing
- **Theme (secondary):** Anderson's Bridge Balance Condition & Non-Minimum-Phase Bode Phase Calculation
- **Repeat cluster:** RC32 (Transmission Line & Economic Power-System Operation)
- **Has figure:** yes

> (a) (i) The configuration of a $400\text{ KV}$ 3 phase line is shown in figure. The radius of each sub-conductor is $2\text{ cm}$. Calculate the charging mega volt-amperes if line is operating at $50\text{ Hz}$ and has a length of $300\text{ km}$. [10]
>
> **Figure ID:** FIG-EE2-2021-Q4ai
> **Circuit description (netlist form):** Horizontal spacing layout of a 3-phase bundled-conductor transmission line. Phase A consists of sub-conductors $a$ and $a'$ separated by $0.5\text{ m}$. Phase B consists of sub-conductors $b$ and $b'$ separated by $0.5\text{ m}$, located $10\text{ m}$ horizontally from the center of Phase A. Phase C consists of sub-conductors $c$ and $c'$ separated by $0.5\text{ m}$, located $10\text{ m}$ horizontally from the center of Phase B. Radius of each sub-conductor is $2\text{ cm}$.
> **Symbolic form:** not derivable from figure.
>
> (ii) Calculate the most economical overall diameter of insulation of a cable to be operated at $400\text{ KV}$, 3 phase power system if maximum stress is limited to $100\text{ KV/cm}$ [10]
>
> (b) Derive the conditions of balance of an Anderson's bridge and also draw the phasor diagram of the bridge under balanced condition. Determine the unknown quantities in terms of known parameters and comment on easy convergence of balance of the bridge. [20]
>
> (c) The approximate magnitude plot, obtained experimentally, of a nonminimum phase system is shown in figure. Calculate the phase in degrees at $\omega=3\text{ rad/sec}$ [10]
>
> **Figure ID:** FIG-EE2-2021-Q4c
> **Circuit description (netlist form):** Asymptotic Bode magnitude plot in $d_B$ versus frequency $\omega\text{ (rad/sec)}$ for a non-minimum phase system. Magnitude is flat at $0\text{ dB}$ from $\omega=0$ to corner frequency $\omega=2\text{ rad/sec}$, where the slope drops to $-20\text{ dB/decade}$. A second corner frequency is marked at $\omega=20\text{ rad/sec}$, beyond which the slope decreases further to $-40\text{ dB/decade}$.
> **Symbolic form:** not derivable from figure.

---

### [EE2-2021-Q5] Current Transformer Ratio and Phase-Angle Errors · Routh-Hurwitz Roots, Piezoelectric Transducer Time Constant, Shannon-Fano/Huffman Coding & 8085 Instructions

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Error analysis; measurement of current voltage, power, energy, power-factor, resistance, inductance, capacitance and frequency; bridge measurements.
- **Directive:** Explain
- **Theme (primary):** Current Transformer Ratio and Phase-Angle Errors
- **Theme (secondary):** Routh-Hurwitz Roots, Piezoelectric Transducer Time Constant, Shannon-Fano/Huffman Coding & 8085 Instructions
- **Repeat cluster:** RC07 (Bridge Measurements & Error Analysis)
- **Has figure:** no

> (a) Explain the ratio error and phase angle error of current transformer. [10]
>
> (b) The two top rows of a Routh table of a characteristic polynomial is given in the table. Determine the roots of the characteristic equation which lie in the left half s-plane. Complete the remaining rows of the table. [10]
>
> | $s^4$ | 1 | 10 | 24 |
> | :--- | :--- | :--- | :--- |
> | $s^3$ | 5 | 20 | |
>
> (c) A pulse is applied to a piezo-electric transducer for a time T. Prove that in order to keep the undershoot of the response to a value within 5%, the value of time constant should be approximately 207. [10]
>
> (d) A discrete memoryless source (DMS) has five symbols $x_1$, $x_2$, $x_3$, $x_4$ and $x_5$ with $P(x_1)=0\cdot 4,$ $P(x_2)=0.19$, $P(x_3)=0.16$, $P(x_4)=0.15$ and $P(x_5)=0\cdot 1$. [10]
> (i) Construct a Shannon Fano code for the source and calculate the efficiency of the code.
> (ii) Repeat for Huffman code. Compare the results of (i) and (ii).
>
> (e) List the functional classification of 8085 instruction set. Give one example for each class. [10]

---

### [EE2-2021-Q6] Synchronous Machine Swing Equation Derivation · Nyquist Stability Criterion & Spectrum Analyzer Applications

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Concepts of system stability: swing curves and equal area criterion.
- **Directive:** Determine
- **Theme (primary):** Synchronous Machine Swing Equation Derivation
- **Theme (secondary):** Nyquist Stability Criterion & Spectrum Analyzer Applications
- **Repeat cluster:** RC58 (Power System Transient Stability (Critical Clearing Angle))
- **Has figure:** yes

> (a) A synchronous machine is connected to an infinite bus through a transformer and a double circuit line as shown in figure. The infinite bus voltage is $V=1\cdot 0\angle 0^\circ\text{ p.u.}$ The direct axis transient reactance of the machine is $0\cdot 20\text{ p.u.}$, the transformer reactance is $0\cdot 10\text{ p.u.}$ and the reactance of each of the transmission lines is $0\cdot 4\text{ p.u.}$ all the values are to a base of the rating of the synchronous machine. Initially, the machine is delivering $0\cdot 8\text{ p.u.}$ power with a terminal voltage $|V_t|=1.05\text{ p.u.}$ The inertia constant $H=5\text{ MJ/MVA}$. All resistances are neglected. Determine the equation of motion of the machine rotor. [20]
>
> **Figure ID:** FIG-EE2-2021-Q6a
> **Circuit description (netlist form):** Single-line power system diagram. Synchronous generator with excitation voltage $E=|E|\angle\delta$ connected to generator bus. Step-up transformer $T$ connected between generator bus and transmission bus. Parallel double-circuit transmission system consisting of Line-1 (with circuit breakers $CB_1, CB_3$) and Line-2 (with circuit breakers $CB_2, CB_4$) connecting to an Infinite Bus-bar at voltage $V=1\cdot 0\angle 0^\circ\text{ p.u.}$
> **Symbolic form:** not derivable from figure.
>
> (b) State Nyquist stability criterion. Is the feedback system shown in figure in open loop stable? Determine the closed loop stability of the system using Nyquist stability criterion. Show all the required plots clearly. [20]
>
> **Figure ID:** FIG-EE2-2021-Q6b
> **Circuit description (netlist form):** Closed-loop block diagram. Input signal enters summing junction with positive sign and subtractive negative feedback. Forward path transfer function is $G(s)=\frac{1}{s(s+1)}$. Feedback path transfer function is $H(s)=2(s-2)$. Output branches to feedback block $H(s)$ and enters the inverting terminal of the summing junction.
> **Symbolic form:** $$T(s) = \frac{1}{s^2+3s-4}$$
>
> (c) Write advantages, disadvantages and application of spectrum analyzer. [10]

---

### [EE2-2021-Q7] Percentage Differential Relay with Harmonic Restraint · Phase-Lead Network Design & Minimum Spanning Tree Uniqueness Proof

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers.
- **Directive:** Discuss
- **Theme (primary):** Percentage Differential Relay with Harmonic Restraint
- **Theme (secondary):** Phase-Lead Network Design & Minimum Spanning Tree Uniqueness Proof
- **Repeat cluster:** RC16 (Circuit-Breaker/Relay Protection Principles)
- **Has figure:** yes

> (a) Discuss the percentage differential Relay with harmonic restraint with the help of diagram and also draw the conceptual representation of it. [20]
>
> (b) A sinusoidal voltage of $10\text{ V}$ amplitude at $100\text{ Hz}$ is applied to a lead network shown in figure. The phase difference between the input voltage $V_i(t)$ and output voltage $V_o(t)$ is $44\cdot 43^\circ$. If $C=0.1\mu\text{F}$ and $R_1=100\text{ k}\Omega$ determine the value of $R_2$ and the magnitude of steady state output voltage. [20]
>
> **Figure ID:** FIG-EE2-2021-Q7b
> **Circuit description (netlist form):** RC lead network circuit. Input AC voltage $V_i(t)$ is applied across the input terminals. Series branch comprises a parallel combination of resistor $R_1$ and capacitor $C$. Shunt branch comprises resistor $R_2$ connected across the output terminals where voltage $V_o(t)$ is measured.
> **Symbolic form:** $$\frac{V_o(s)}{V_i(s)} = \frac{R_2(1+s R_1 C)}{(R_1 + R_2) + s R_1 R_2 C}$$
>
> (c) Consider a connected graph $G=(N,A)$ with N nodes and A arcs, and a weight $\omega_{ij}$ for each arc $(i,j)\in A$ [10]
> (i) Define minimum weight spanning tree (MST).
> (ii) If all arc weights of G are distinct, prove that there exists a unique MST.

---

### [EE2-2021-Q8] Linear Block Code Minimum-Distance Bound and Hamming Code Proof · I/O Handshaking Interface Timing & 3-Bus Power Flow Loss Calculation

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Error control coding: error detection and correction, linear block codes, convolation codes.
- **Directive:** Prove
- **Theme (primary):** Linear Block Code Minimum-Distance Bound and Hamming Code Proof
- **Theme (secondary):** I/O Handshaking Interface Timing & 3-Bus Power Flow Loss Calculation
- **Repeat cluster:** RC31 (Error-Control Coding (Block Codes, CRC, Hamming))
- **Has figure:** no

> (a) (i) Prove that the minimum distance of any linear (n, k) block code satisfies [5]
> $$d_{min}\le 1+n-k$$
> (ii) Show that the minimum Hamming distance of a linear block code is equal to the minimum number of columns of its parity check matrix that are linearly dependent. From this conclude that the minimum Hamming distance of a Hamming code is always equal to 3. [15]
>
> (b) A commercial interface unit uses different names for the handshake lines associated with the transfer of data from the I/O device into the interface unit. The interface input handshake line is labelled STB (strobe), and the interface output handshake line is labelled IBF (input buffer full). A low-level signal on STB loads data from the I/O bus into the interface data register. A high-level signal on IBF indicates that the data item has been accepted by the interface. IBF goes low after an I/O read signal from the CPU when it reads the content of the data register. [20]
> (i) Draw the block diagram showing the CPU, the interface, and the I/O device together with the pertinent interconnections among the three units.
> (ii) Draw a timing diagram for the handshaking transfer.
> (iii) Obtain a sequence of events flowchart for the transfer from the device to the interface and from the interface to the CPU.
>
> (c) For a 3-bus power system, assume [10]
> Voltage at bus - 1 : $V_1=(1\cdot 05+j0)\text{ pu}$,
> Voltage at bus - 2 : $V_2=(0.9812-j0\cdot 0522)\text{ pu}$ and
> Voltage at bus - 3 : $V_3=(0\cdot 999-j0.0468)\text{ pu}$.
>
> The line impedances are shown below:
>
> | Bus code | Impedances (in p.u.) |
> | :--- | :--- |
> | 1-2 | $(0.02+j0\cdot 04)$ |
> | 1-3 | $(0\cdot 01+j0\cdot 03)$ |
> | 2-3 | $(0\cdot 0125+j0\cdot 025)$ |
>
> Compute Real and Reactive power loss in all the lines and also compute total system loss.

---
