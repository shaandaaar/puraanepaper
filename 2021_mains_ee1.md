# PAPER I

### [EE1-2021-Q1] Two-Port Y-Parameter Load Voltage Calculation · Signal Energy/Scaling, DC Motor Efficiency, BJT Saturation Current & 3-Gate Logic Implementation

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Two-port networks.
- **Directive:** Find
- **Theme (primary):** Two-Port Y-Parameter Load Voltage Calculation
- **Theme (secondary):** Signal Energy/Scaling, DC Motor Efficiency, BJT Saturation Current & 3-Gate Logic Implementation
- **Repeat cluster:** RC13 (Two-Port Network Parameters)
- **Has figure:** yes

> (a) In Figure 1(a) shown below, the two-port network is characterized in terms of y-parameters with $y_{11}=3\cdot3\times10^{-3}\text{ S}$, $y_{22}=5\times10^{-3}\text{ S}$ and $y_{12}=y_{21}=0$. Find the voltage across $200\text{ }\Omega$ load. [10]
>
> **Figure ID:** FIG-EE1-2021-Q1a
> **Circuit description (netlist form):** AC voltage source $100\sin(2t)\text{ V}$ connected in series with inductor $2\text{ H}$ to port 1 terminal (1) of a two-port network. Port 1 terminal ($1'$) and port 2 terminal ($2'$) are connected together to the top terminal of capacitor $0.01\text{ F}$, whose bottom terminal is connected to the common return/ground rail. Port 2 terminal (2) is connected through load resistor $200\text{ }\Omega$ to the common return/ground rail. Current entering terminal 1 is $I_1$ and current entering terminal 2 is $I_2$.
> **Symbolic form:** not derivable from figure.
>
> (b) For the signal shown in Figure 1(b), calculate the total energy of the signal $X(t)$. Also sketch $y(t)=X(10t-5)$. [10]
>
> **Figure ID:** FIG-EE1-2021-Q1b
> **Circuit description (netlist form):** Graph of continuous-time signal $X(t)$ plotted against time $t$. Symmetrical piecewise linear waveform: $X(t)=0$ for $t < -3$; linear ramp from $0$ to $1$ for $-3 \le t < -2$; constant amplitude $1$ for $-2 \le t < -1$; step up to constant amplitude $2$ for $-1 \le t \le 1$; step down to constant amplitude $1$ for $1 < t \le 2$; linear ramp from $1$ to $0$ for $2 < t \le 3$; $X(t)=0$ for $t > 3$.
> **Symbolic form:** $$X(t) = (t+3)[u(t+3)-u(t+2)] + [u(t+2)-u(t+1)] + 2[u(t+1)-u(t-1)] + [u(t-1)-u(t-2)] + (3-t)[u(t-2)-u(t-3)]$$
>
> (c) A $220\text{ V}$ dc shunt motor has armature resistance $R_a=0.13\text{ }\Omega$, field resistance $R_f=250\text{ }\Omega$ and rotational loss $230\text{ W}$. On full-load, the line current is $9.5\text{ A}$ with the motor running at $1440\text{ rpm}$. Determine the following: [10]
> (i) The mechanical power developed
> (ii) The power output
> (iii) The load torque
> (iv) The full-load efficiency
>
> (d) For the transistor circuit shown in Figure 1(d), determine the value of reverse saturation current, $I_S$, that would give a collector current of $1\text{ mA}$, if $\beta=80$, $V_A=\infty$ and $V_T=26\text{ mV}$ at $T=300\text{ K}$. [10]
>
> **Figure ID:** FIG-EE1-2021-Q1d
> **Circuit description (netlist form):** PNP BJT transistor $Q_1$ with emitter connected to positive DC supply rail $V_{CC}=2.5\text{ V}$. Collector of $Q_1$ is connected to an intermediate node. Resistor $20\text{ k}\Omega$ is connected between the base of $Q_1$ and the intermediate node. Resistor $1.6\text{ k}\Omega$ is connected between the intermediate node and ground.
> **Symbolic form:** not derivable from figure.
>
> (e) Consider the four variables logic function defined as follows: [10]
> $$F(A,B,C,D)=\overline{A}C+\overline{A}D+\overline{B}C+\overline{B}D+AB\overline{C}\overline{D}$$
> Assuming input variables as A, B, C and D, propose a logic circuit using only three logic gates to implement the function.

---

### [EE1-2021-Q2] Thevenin's Theorem with Mutually Coupled Inductors · Discrete Convolution, Signal Representation & JK/D Flip-Flop Sequence Detector

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Find
- **Theme (primary):** Thevenin's Theorem with Mutually Coupled Inductors
- **Theme (secondary):** Discrete Convolution, Signal Representation & JK/D Flip-Flop Sequence Detector
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> (a) Find the Thevenin's equivalent of the circuit shown in Figure 2(a) below as seen from the load impedance $Z_L$. Also find the value of $Z_L$ for maximum power transfer. [20]
>
> **Figure ID:** FIG-EE1-2021-Q2a
> **Circuit description (netlist form):** AC voltage source $100\angle 0^\circ\text{ V}$ connected in series with capacitor $-j2\text{ }\Omega$ to the top terminal (dotted) of coupled inductor $j4\text{ }\Omega$. Dotted coupled inductor $j9\text{ }\Omega$ (dot at top) is in series with inductor $j2\text{ }\Omega$ and connected to top terminal of load impedance $Z_L$. Coupling coefficient between $j4\text{ }\Omega$ and $j9\text{ }\Omega$ is $k=0.5$. Bottom terminals of $j4\text{ }\Omega$ and $j9\text{ }\Omega$ inductors meet at a common node connected through series combination of resistor $2\text{ }\Omega$ and inductor $j3\text{ }\Omega$ to the ground reference rail. Bottom terminal of load $Z_L$ and return of source $100\angle 0^\circ\text{ V}$ are connected to the ground reference rail.
> **Symbolic form:** not derivable from figure.
>
> (b) (i) Compute the convolution $X[n]*h[n]$, where [20]
> $$X[n]=\left(\frac{1}{2}\right)^{-n}u[-n-2]$$
> $$h[n]=u[n-2]$$
> (ii) Consider the signal $X(t)$ shown in Figure 2(b)(ii) below. Represent the signal $X(t)$ in terms of rectangular pulse signal $V(t)$ shown in the same figure.
>
> **Figure ID:** FIG-EE1-2021-Q2bii
> **Circuit description (netlist form):** Plot of continuous-time staircase signal $X(t)$ vs $t$: amplitude is $1$ for $0 \le t < 1$, $2$ for $1 \le t < 2$, $3$ for $2 \le t < 3$, $2$ for $3 \le t < 4$, and $0$ elsewhere. Plot of unit rectangular pulse $V(t)$ vs $t$: amplitude is $1$ for $-1 \le t \le 1$ and $0$ elsewhere.
> **Symbolic form:** not derivable from figure.
>
> (c) Consider the circuit shown in Figure 2(c) below. Let inputs A, B and C be all initially LOW. Output Y is supposed to go HIGH only when A, B and C go HIGH in a certain sequence. Determine the sequence that will make Y go HIGH. Modify this circuit to use D-Flip-flops. [10]
>
> **Figure ID:** FIG-EE1-2021-Q2c
> **Circuit description (netlist form):** Two cascaded JK flip-flops. First JK flip-flop: input $A$ connected to $J$, input $B$ connected to $\text{CLK}$, terminal $K$ connected to ground, active-low $\overline{\text{CLR}}$ connected to $\overline{\text{Start}}$ line, output $X$ connected to $J$ input of second flip-flop. Second JK flip-flop: input $C$ connected to $\text{CLK}$, terminal $K$ connected to ground, active-low $\overline{\text{CLR}}$ connected to $\overline{\text{Start}}$ line, output terminal is $Y$.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2021-Q3] Logarithmic Amplifier Circuit Analysis (Two Topologies) · Multi-Source AC/DC Network Voltage & Analog-Multiplier Fourier Transform

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits.
- **Directive:** Explain
- **Theme (primary):** Logarithmic Amplifier Circuit Analysis (Two Topologies)
- **Theme (secondary):** Multi-Source AC/DC Network Voltage & Analog-Multiplier Fourier Transform
- **Repeat cluster:** RC19 (Op-Amp/Transistor Amplifier Characteristics)
- **Has figure:** yes

> (a) (i) Explain what happens when a circuit shown in Figure 3(a)(i) below is constructed using logarithmic amplifier. [10]
>
> **Figure ID:** FIG-EE1-2021-Q3ai
> **Circuit description (netlist form):** Operational amplifier with non-inverting terminal $(+)$ grounded. Input DC voltage source $V_{\text{REF}}$ connected via resistor $R_1$ to inverting terminal $(-)$. NPN BJT $Q_1$ connected in feedback path: collector connected to inverting terminal $(-)$, base connected to ground, emitter connected to op-amp output node $V_1$. NPN BJT $Q_2$: base connected to node $V_1$, emitter connected to negative terminal of fixed DC voltage source (positive terminal grounded), collector provides output current $I_X$.
> **Symbolic form:** not derivable from figure.
>
> (ii) Explain what happens if the topology is modified as shown in Figure 3(a)(ii) below. [10]
>
> **Figure ID:** FIG-EE1-2021-Q3aii
> **Circuit description (netlist form):** Operational amplifier with non-inverting terminal $(+)$ grounded. Input DC voltage source $V_{\text{REF}}$ connected via resistor $R_1$ to inverting terminal $(-)$. NPN BJT $Q_1$ connected in feedback path: collector connected to inverting terminal $(-)$, base connected to ground, emitter connected to op-amp output node $V_1$. NPN BJT $Q_2$: base connected to ground, emitter connected to op-amp output node $V_1$, collector provides output current $I_X$.
> **Symbolic form:** not derivable from figure.
>
> (b) For the circuit shown in Figure 3(b), calculate the voltage $V_0(t)$ as function of time, [20]
>
> **Figure ID:** FIG-EE1-2021-Q3b
> **Circuit description (netlist form):** Multi-source parallel network. Branch 1: AC voltage source $V(t)$ in series with resistor $10\text{ }\Omega$ connected to top node. Branch 2: capacitor $0.1\text{ F}$ connected across top node and ground rail with voltage $V_0$ (+ at top). Branch 3: independent AC current source $I(t)$ directed upward from ground rail to top node. Branch 4: series combination of inductor $4\text{ H}$ and DC voltage source $20\text{ V}$ (+ at top, - at ground rail).
> **Symbolic form:** not derivable from figure.
>
> where $V(t)=10\sin(6t+60^\circ)\text{ V}$ and $I(t)=5\cos(4t+30^\circ)\text{ A}$
>
> (c) A mixer (analog multiplier) is used as a process in some analog communication systems. Two signals $X_1(t)$ and $X_2(t)$ are mixed to produce the output $y(t)=X_1(t)X_2(t)$. [20]
> If $X_1(t)=10\text{ sinc}(10t)$ and $X_2(t)=2\cos(1000\pi t)$, then calculate and plot the magnitude of the Fourier transform of output signal. Further, specify and prove the property of Fourier transform used in calculations.

---

### [EE1-2021-Q4] Discrete-Time System Impulse and Step Response (With Initial Conditions) · Multiplexer Tree Logic Verification & Op-Amp T-Network Gain

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Calculate
- **Theme (primary):** Discrete-Time System Impulse and Step Response (With Initial Conditions)
- **Theme (secondary):** Multiplexer Tree Logic Verification & Op-Amp T-Network Gain
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** yes

> (a) Consider a discrete time system with transfer function given by [20]
> $$H(z)=\frac{Y(z)}{R(z)}=\frac{z^{-1}-\frac{1}{2}z^{-2}}{\left(1-z^{-1}+\frac{2}{9}z^{-2}\right)}$$
> Calculate the following:
> (i) The impulse response of the system
> (ii) The step response of the system with zero initial conditions
> (iii) The step response of the system with initial conditions $y[-1]=1$ and $y[-2]=2$
>
> (b) (i) Verify by determining the logic equation for the output and by constructing the truth table for the logic circuit shown in Figure 4(b). [20]
>
> **Figure ID:** FIG-EE1-2021-Q4b
> **Circuit description (netlist form):** Multiplexer tree circuit with four 2-to-1 multiplexers feeding into one 4-to-1 multiplexer. Select line $S_0$ is common to all four 2:1 MUXes. MUX 0 has inputs $D_0$ (at 0) and $D_1$ (at 1), output to input '00' of 4:1 MUX. MUX 1 has inputs $D_2$ (at 0) and $D_3$ (at 1), output to input '01' of 4:1 MUX. MUX 2 has inputs $D_4$ (at 0) and $D_5$ (at 1), output to input '10' of 4:1 MUX. MUX 3 has inputs $D_6$ (at 0) and $D_7$ (at 1), output to input '11' of 4:1 MUX. 4-to-1 MUX has select lines $S_2$ and $S_1$, and output line $Y$.
> **Symbolic form:** not derivable from figure.
>
> (ii) Use an 8 to 1 multiplexer and logic gates to implement the following function:
> $$F(A,B,C,D,E)=\sum m(0,1,2,4,5,6,7,13,14,20,21,\dots,28,29,30,31)$$
>
> (c) Determine the closed loop gain of the inverting amplifier shown in Figure 4(c) below. Explain the result if $R_1\rightarrow 0$ or $R_3\rightarrow 0$. [10]
>
> **Figure ID:** FIG-EE1-2021-Q4c
> **Circuit description (netlist form):** Inverting operational amplifier circuit with ideal gain $A_0=\infty$ and non-inverting terminal $(+)$ grounded. Input voltage source $V_{in}$ connected via resistor $R_2$ to inverting terminal $(-)$. Feedback loop consists of a T-network: resistor $R_3$ connected between inverting terminal $(-)$ and intermediate node $V_x$; resistor $R_4$ connected between node $V_x$ and ground; resistor $R_1$ connected between node $V_x$ and output terminal $V_{out}$.
> **Symbolic form:** $$\frac{V_{out}}{V_{in}} = -\frac{R_1 R_3 + R_1 R_4 + R_3 R_4}{R_2 R_4}$$

---

### [EE1-2021-Q5] Step-Down DC Chopper Ripple Current · Displacement Current, Scott-Connected Transformer, AM Modulation Index & RC Transient

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** principles of thyristor choppers and inverters; DC-DC converters; Switch mode inverter;
- **Directive:** Determine
- **Theme (primary):** Step-Down DC Chopper Ripple Current
- **Theme (secondary):** Displacement Current, Scott-Connected Transformer, AM Modulation Index & RC Transient
- **Repeat cluster:** RC25 (DC Choppers & Switch-Mode Converters)
- **Has figure:** no

> (a) A step down dc chopper is feeding a load of $R=10\text{ }\Omega$ and $L=20\text{ mH}$. The dc supply voltage is $100\text{ V}$. The chopper is switching at a frequency of $2\text{ kHz}$ with a duty cycle of 50%. Determine the load current and the peak-to-peak ripple current as an absolute value and as percentage of dc value. [10]
>
> (b) In a certain material with $\sigma=0$, $\epsilon=\epsilon_0\epsilon_r$ and $\mu=\mu_0\mu_r$, the magnetic field intensity component is given by [10]
> $$H=10\sin(10^8 t-2x)a_z\text{ A/m}.$$
> Find the following:
> (i) Displacement current density
> (ii) Electric field intensity
>
> (c) A Scott connected transformer shown in Figure 5(c) is supplied from $11\text{ kV}$, 3-phase, $50\text{ Hz}$ mains. Secondaries are series connected and supply $1100\text{ A}$ at a voltage of $100\sqrt{2}\text{ V}$ to a resistive load. The phase sequence of the 3-phase supply is ABC. [10]
> (i) Calculate the turns ratio of the teaser transformer.
> (ii) Calculate the line current $I_B$ and its phase angle with respect to the voltage of phase A to neutral on the 3-phase side.
>
> **Figure ID:** FIG-EE1-2021-Q5c
> **Circuit description (netlist form):** Scott-connected transformer schematic. 3-phase supply lines A, B, C at $11\text{ kV}$. Main transformer primary winding of $N_1$ turns is connected between lines B and C, center-tapped at node M with $N_1/2$ turns on each side. Teaser transformer primary winding with $\frac{\sqrt{3}}{2}N_1$ turns connected between line A and center tap M. Teaser secondary winding with $N_2$ turns and Main secondary winding with $N_2$ turns are connected in series aiding across a resistive load, supplying $1100\text{ A}$ at $100\sqrt{2}\text{ V}$.
> **Symbolic form:** not derivable from figure.
>
> (d) A transmitter with a $10\text{ kW}$ carrier transmits $11.2\text{ kW}$ when modulated with a single sine wave. Calculate the modulation index. If the carrier is simultaneously modulated with two other sine waves also at 50% modulation, calculate the total power transmitted. [10]
>
> (e) For the circuit shown in Figure 5(e), $v_C(0+)=2\text{ V}$ and $i(0+)=\frac{2}{3}\text{ A}$. Calculate the value of $v_C(t)$ for $t>0$. [10]
>
> **Figure ID:** FIG-EE1-2021-Q5e
> **Circuit description (netlist form):** Single-pair parallel network between upper node and lower reference node. Branch 1: capacitor $C_1=0.5\text{ F}$ with voltage $v_C$ (+ at top). Branch 2: dependent current source $i/2$ directed upward. Branch 3: series combination of resistor $3\text{ }\Omega$ and capacitor $C_2=\frac{1}{3}\text{ F}$, with upward current $i$ flowing into the resistor.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2021-Q6] Uniform Plane Wave Attenuation in Lossy Sea Water · 3-Phase Bridge Inverter RMS Current/Power & Continuous Random Variable PDF

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves.
- **Directive:** Determine
- **Theme (primary):** Uniform Plane Wave Attenuation in Lossy Sea Water
- **Theme (secondary):** 3-Phase Bridge Inverter RMS Current/Power & Continuous Random Variable PDF
- **Repeat cluster:** RC18 (Electromagnetic Field Theory (Maxwell's Equations & Poynting Theorem))
- **Has figure:** yes

> (a) The magnetic field intensity of a linearly polarized uniform plane wave propagating in the +Y-direction in sea water $(\epsilon_r=80, \mu_r=1, \sigma=4\text{ S/m})$ is [20]
> $$H=0\cdot1\sin\left(10^{10}\pi t-\frac{\pi}{3}\right)a_x\text{ A/m}.$$
> At $Y=0$, determine the following:
> (i) The attenuation constant, intrinsic impedance, the wavelength and skin depth.
> (ii) The location at which the amplitude of H is $0\cdot01\text{ A/m}$.
> (iii) The expression for $E(y,t)$ and $H(y,t)$ at $Y=0\cdot5\text{ (m)}$ as functions of t.
>
> (b) A three-phase bridge inverter shown in Figure 6(b) is used to feed a Y-connected resistive load with $R=10\text{ }\Omega$ per phase. The dc input to the inverter $V_S=400\text{ V}$ and the output frequency is $50\text{ Hz}$. If the inverter is operating with $180^\circ$ conduction mode, [20]
> (i) compute the rms value of the load current,
> (ii) compute the rms value of the current in each switching device,
> (iii) calculate the output power, and
> (iv) draw the waveforms of phase and line voltages.
>
> **Figure ID:** FIG-EE1-2021-Q6b
> **Circuit description (netlist form):** Three-phase voltage source bridge inverter fed from DC voltage source $V_S$. Leg 1 has upper transistor $Q_1$ with antiparallel diode $D_1$ and lower transistor $Q_4$ with antiparallel diode $D_4$, with midpoint terminal $a$. Leg 2 has upper transistor $Q_3$ with antiparallel diode $D_3$ and lower transistor $Q_6$ with antiparallel diode $D_6$, with midpoint terminal $b$. Leg 3 has upper transistor $Q_5$ with antiparallel diode $D_5$ and lower transistor $Q_2$ with antiparallel diode $D_2$, with midpoint terminal $c$. Terminals $a, b, c$ connect to a star-connected balanced 3-phase resistive load of resistance $R$ per phase with star neutral point $n$.
> **Symbolic form:** not derivable from figure.
>
> (c) Let the measurement error of a physical quantity be defined by a random variable X and its density function as follows: [10]
> $$f(x)=\begin{cases}K(3-x^2) & -1\le x\le 1\\ 0 & \text{elsewhere}\end{cases}$$
> Determine the value of 'K' and find the probability that a random error in measurement is less than $1/2$.

---

### [EE1-2021-Q7] Synchronous Machine Reactance from OCC/SCC Test Data · 3-Phase Thyristor Bridge Converter Performance & Lossless Line Reflection/SWR

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
- **Directive:** Determine
- **Theme (primary):** Synchronous Machine Reactance from OCC/SCC Test Data
- **Theme (secondary):** 3-Phase Thyristor Bridge Converter Performance & Lossless Line Reflection/SWR
- **Repeat cluster:** RC26 (AC Machine Performance (Induction & Synchronous))
- **Has figure:** no

> (a) The following test data are obtained for a three-phase, $195\text{ MVA}$, $15\text{ kV}$, $50\text{ Hz}$ star connected synchronous machine. [20]
>
> Open circuit test:
>
> | $I_f\text{ (A)}$ | 150 | 300 | 450 | 600 | 750 | 900 | 1200 |
> | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> | $V_{LL}\text{ (kV)}$ | 3.75 | 7.5 | 11.2 | 13.6 | 15 | 15.8 | 16.5 |
>
> Short circuit test:
> $I_f=750\text{ A}$, $I_a=7000\text{ A}$
> The armature resistance is small.
> (i) Draw the open circuit characteristic, the short circuit characteristic, the airgap line and the modified airgap line.
> (ii) Determine the unsaturated and saturated values of the synchronous reactance in pu.
> (iii) Find the field current required, if the synchronous machine is to deliver $100\text{ MVA}$ at rated voltage, at 0.8 leading power factor.
>
> (b) A three-phase, full-wave thyristor bridge converter is operated from a three-phase, Y-connected $220\text{ V}$, $50\text{ Hz}$ supply and the load resistance is $20\text{ }\Omega$. [20]
> It is required to obtain an average output voltage of 50% of the maximum possible output voltage. Determine the following:
> (i) The delay angle $\alpha$
> (ii) The rms and average output currents
> (iii) The rms and average thyristor currents
> (iv) The rectification efficiency
> (v) The input PF
>
> (c) A lossless transmission line has characteristic impedance $Z_0=50\text{ }\Omega$. Its length is $30\text{ m}$ and operates at $5\text{ MHz}$. The line is terminated with a load $Z_L=60+j50\text{ }\Omega$. If the phase velocity $u=0\cdot6c$ on the line, find the following: [10]
> (i) The reflection coefficient '$\Gamma$'
> (ii) The standing wave ratio 'S'
> (iii) The input impedance '$Z_{in}$'

---

### [EE1-2021-Q8] FM System Output SNR and Noise Power · Induction Motor Starting Torque with Rotor Resistance & Controlled-Rectifier DC Motor Drive

- **Exam:** UPSC Mains 2021 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Phase and Frequency modulation: PM & FM signals; narrows band FM; generation & detection of FM and PM, Deemphasis, Preemphasis.
- **Directive:** Determine
- **Theme (primary):** FM System Output SNR and Noise Power
- **Theme (secondary):** Induction Motor Starting Torque with Rotor Resistance & Controlled-Rectifier DC Motor Drive
- **Repeat cluster:** RC24 (Frequency & Phase Modulation)
- **Has figure:** no

> (a) For an FM communication system with $\beta=2$ and white channel noise with PSD $S_n(\omega)=10^{-10}$, the output SNR is found to be $28\text{ dB}$. The base band signal $m(t)$ is Gaussian, band-limited to $15\text{ kHz}$, and $3\sigma$ loading is used. [20]
> Determine the following:
> (i) The received signal power '$S_i$'
> (ii) The output signal power '$S_0$'
> (iii) The output noise power '$N_0$'
>
> (b) A three-phase, 4-pole, $50\text{ Hz}$ induction motor has a rotor resistance of $4.5\text{ }\Omega\text{/phase}$ and a standstill reactance of $8.5\text{ }\Omega\text{/phase}$ with no external resistance in the rotor circuit. The starting torque of the motor is $85\text{ Nm}$. Neglecting stator voltage drop, determine the following: [20]
> (i) The rotor voltage at standstill
> (ii) The starting torque, if a $3\text{ }\Omega$ resistance were added in each rotor phase
> (iii) The rotor induced voltage and the torque at a slip of 0.03
>
> (c) A $220\text{ V}$, $1500\text{ rpm}$, $10\text{ A}$ separately excited dc motor has an armature resistance of $1\text{ ohm}$. It is fed from a single phase fully-controlled bridge rectifier with an ac source voltage of $230\text{ V}$, $50\text{ Hz}$. Assuming continuous load current, determine the following: [10]
> (i) Motor speed at the firing angle of $30^\circ$ and torque of $5\text{ Nm}$
> (ii) Developed torque at the firing angle of $45^\circ$ and speed of $1000\text{ rpm}$

---
