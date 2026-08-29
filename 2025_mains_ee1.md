[EE1-2025-Q1] Circuits & Systems · Network Theorems & Signals
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 1 | Marks: 50 | Words: N/A
Syllabus: Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications; transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits. Two-port networks.
Directive: Find, Determine, Draw, Design, Calculate
Theme (primary): DC Circuits & Z-Parameters
Theme (secondary): DTFT & Sequential Logic
Repeat cluster: none
Has figure: yes
(a) In the circuit given below, find the voltages at point A and point B.

**Figure ID:** FIG-EE1-2025-Q1a
**Circuit description (netlist form):** Node G is connected to the ground reference ($0\text{ V}$). Branch between node G and node A consists of a $6\ \Omega$ resistor in series with a $6\text{ V}$ independent DC voltage source (positive terminal towards A). Node A connects to intermediate node $N_1$ via a $12\ \Omega$ resistor. Between node $N_1$ and node B, a $6\ \Omega$ resistor is connected in parallel with an independent $3\text{ A}$ current source directed from node B to node $N_1$. Node A connects to internal node $N_L$, and node B connects to internal node $N_R$. A $9\ \Omega$ resistor is connected between node $N_L$ and node $N_R$. A $3\ \Omega$ resistor is connected between node $N_L$ and ground node G. A $4\ \Omega$ resistor is connected between node $N_R$ and ground node G. A branch between node B and ground node G consists of a $4\ \Omega$ resistor in series with a $12\text{ V}$ independent DC voltage source (negative terminal towards the $4\ \Omega$ resistor, positive terminal connected to ground node G).
**Symbolic form:** not derivable from figure.

[10]

(b) Determine the time domain signal $x(t)$ corresponding to the DTFT given below:

**Figure ID:** FIG-EE1-2025-Q1b
**Circuit description (netlist form):** Frequency-domain plot of DTFT magnitude $|X(e^{j\Omega})|$ and phase spectrum $\arg[X(e^{j\Omega})]$ plotted versus $\Omega$. Magnitude spectrum $|X(e^{j\Omega})|$ is periodic with period $2\pi$, having shape $\sin(\Omega)$ for $0 \le \Omega \le \pi/2$ with peak value 1 at $\Omega = \pi/2$, symmetric variation from $-\pi/2$ to $0$, and zero value in the intervals $[-\pi, -\pi/2]$ and $[\pi/2, \pi]$. Phase spectrum $\arg[X(e^{j\Omega})]$ is periodic with period $2\pi$, exhibiting linear ramps passing through the origin from $-2\pi$ at $\Omega = -\pi$ to $2\pi$ at $\Omega = \pi$.
**Symbolic form:** not derivable from figure.

[10]

(c) Draw the output voltage waveform of the circuit given below for 5 V, 50 Hz ac rms input. Forward voltage drop in diode $D_1$ is 0-6 V.

**Figure ID:** FIG-EE1-2025-Q1c
**Circuit description (netlist form):** Input voltage terminals are applied across the input port with the bottom terminal serving as the common reference rail. In the top rail, a capacitor $C_1 = 100\ \mu\text{F}$ is connected in series (with polarity marking $-$ at the input terminal and $+$ at the internal node). A parallel resistor $R_1 = 10\text{ k}\Omega$ is connected across the output terminals. In parallel with $R_1$, a series branch consisting of a diode $D_1$ (anode connected to the bottom DC source terminal, cathode connected to the top output rail) and a $3\text{ V}$ DC battery (positive terminal at top towards diode anode, negative terminal at bottom reference rail) is connected.
**Symbolic form:** not derivable from figure.

[10]

(d) Design a sequential circuit with two D flip flops A and B and one input X. Let the state of the circuit remain the same for $X=0$ However, when $X=1$, the circuit goes through the state transitions from 00 to 10 to 11 to 01, back to 00 and then repeats.
[10]

(e) Calculate Z-parameters for the two-port network given in the circuit diagram.

**Figure ID:** FIG-EE1-2025-Q1e
**Circuit description (netlist form):** Two-port network with Port 1 (voltage $V_1$, entering current $I_1$) and Port 2 (voltage $V_2$, entering current $I_2$) having a common bottom ground rail. A bridging resistor of $3\ \Omega$ is connected across the upper terminals of Port 1 and Port 2. A bridged T-network inside consists of two series $3\ \Omega$ resistors between Port 1 and Port 2 meeting at a central node, and a shunt resistor of $3\ \Omega$ connected from the central node to the bottom reference rail.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2025-Q2] Circuits & Analog Electronics · Transient & Op-Amps
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 2 | Marks: 50 | Words: N/A
Syllabus: Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications; transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits. Two-port networks.
Directive: Plot, Find, Draw, Calculate, Modify, Determine
Theme (primary): RC Transient Analysis
Theme (secondary): Op-Amp Waveform Generator & Z-Transform
Repeat cluster: none
Has figure: yes
(a) In the circuit shown in the diagram, initially key $K_1$ is closed and capacitor has no charge (at time $t=0$).
Now at time $t=10$ seconds, key $K_1$ is opened and at $t=18\cdot68$ seconds it is again closed.
Plot output voltage across the capacitor with respect to time and find output voltage values at time 10 seconds, 18.68 seconds and 28.68 seconds.

**Figure ID:** FIG-EE1-2025-Q2a
**Circuit description (netlist form):** Node A is the ground reference node. An independent current source of $0.1\text{ A}$ is connected between node A and an intermediate node, directed upward. Switch $K_1$ is connected in parallel with the $0.1\text{ A}$ current source between node A and the intermediate node. A resistor of $5\ \Omega$ is connected between the intermediate node and a top node. An independent current source of $1\text{ A}$ is connected in parallel with the $5\ \Omega$ resistor between the intermediate node and the top node, directed upward. From the top node, a $95\ \Omega$ resistor is connected in series with a $5\text{ V}$ DC voltage source (negative terminal on left, positive terminal on right) to output terminal B. A capacitor $C = 0.1\text{ F}$ is connected between output terminal B and ground terminal A.
**Symbolic form:** not derivable from figure.

[20]

(b) Consider the circuit of an operational amplifier given here in which Zener diodes $Z_1$ and $Z_2$ are having reverse breakdown voltage $=7.4\text{ V}$ and forward voltage drop $=0\cdot6\text{ V}.$
(i) Draw the output voltage waveform showing voltage value with time and calculate frequency of output waveform.
(ii) Modify the circuit for duty cycle factor $D=0\cdot25$ by replacing $R_1$ from combination of suitable resistances and diodes, so that output frequency is not changed.

**Figure ID:** FIG-EE1-2025-Q2b
**Circuit description (netlist form):** Operational amplifier powered by dual supplies $+12\text{ V}$ and $-12\text{ V}$. Inverting input ($-$) is connected to node $V_1$, which connects to ground via capacitor $C_1 = 0.1\ \mu\text{F}$ and connects to output node $V_3$ through feedback resistor $R_1 = 100\text{ k}\Omega$. Non-inverting input ($+$) is connected to node $V_2$. Op-amp output connects through resistor $R_2 = 1\text{ k}\Omega$ to output node $V_3$. A voltage divider between node $V_3$ and ground consists of series resistors $R_3 = 39\text{ k}\Omega$ and $R_4 = 1\text{ k}\Omega$, with intermediate tap at node $V_2$. Two back-to-back Zener diodes $Z_1$ and $Z_2$ are connected in series between node $V_3$ and ground.
**Symbolic form:** not derivable from figure.

[20]

(c) Determine the causal signal $x[n]$ if its z-transform $X(z)$ is specified by a pole-zero pattern shown in the figure below. Take the constant $G=\frac{1}{4}$.

**Figure ID:** FIG-EE1-2025-Q2c
**Circuit description (netlist form):** Pole-zero diagram in the complex z-plane. Two real zeros are located on the real axis at $z = -1/2$ and $z = -1/4$. Three poles are shown: one real pole at $z = 1/2$ and a pair of complex conjugate poles at radius $r = 1/\sqrt{2}$ and angle $\theta = \pm \pi/4$, having real part $1/4$ and imaginary parts $\pm 1/4$.
**Symbolic form:** $$X(z) = G \frac{(z + 1/2)(z + 1/4)}{(z - 1/2)(z - \frac{1}{\sqrt{2}}e^{j\pi/4})(z - \frac{1}{\sqrt{2}}e^{-j\pi/4})} = \frac{1}{4}\frac{(z + 1/2)(z + 1/4)}{(z - 1/2)(z^2 - z + 1/2)}$$

[10]

[EE1-2025-Q3] Digital Logic & Analog Electronics · MUX & Amplifiers
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 3 | Marks: 50 | Words: N/A
Syllabus: Combinational circuits arithmetic circuits, code converters, multiplexers and decoders. Sequential circuits: latches and flip-flops, counters and shift-registers. Comparators, timers, multivibrators. Sample and hold circuits, ADCs and DACs. Semiconductor memories. Logic implementation using programmable devices (ROM, PLA, FPGA).
Directive: Implement, Calculate, Find
Theme (primary): Multiplexer Implementation
Theme (secondary): Multi-Stage BJT Amplifier & Convolution
Repeat cluster: none
Has figure: yes
(a) Consider the Boolean function:
$$F(A,B,C,D)=\Sigma m(1,3,4,11,12,13,14,15)$$
Implement it with a 4-to-1 multiplexer and external gates. Connect inputs A and B to the selection lines. Input to the four data lines is a function of the variables C and D which are obtained by expressing F as a function of C and D for each of the four cases when AB = 00, 01, 10 and 11. Functions are to be implemented with external gates.
[20]

(b) In the circuit given below, transistors $T_1$ and $T_2$ are having $V_{BE}=0\cdot6\text{ V}$ and $\beta=499$
(i) Calculate small signal ac voltage gain of the amplifier at 20 Hz and 2 kHz.
(ii) Find dc voltages on collectors of transistors $T_1$ and $T_2$ respectively.

**Figure ID:** FIG-EE1-2025-Q3b
**Circuit description (netlist form):** Two-stage BJT amplifier circuit operated from supply voltage $V_{CC} = 12\text{ V}$ and ground reference. Transistor $T_1$ has its collector connected to $V_{CC}$ via resistor $R_1 = 9.1\text{ k}\Omega$, base connected to input through coupling capacitor $C_1 = 10\ \mu\text{F}$, and emitter connected to an intermediate node. Transistor $T_2$ has its collector connected to $V_{CC}$ via resistor $R_2 = 2\text{ k}\Omega$, base directly connected to collector of $T_1$, and emitter connected to ground through resistor $R_7 = 1\text{ k}\Omega$ in parallel with bypass capacitor $C_5 = 100\ \mu\text{F}$. Output is taken from collector of $T_2$ through coupling capacitor $C_3 = 100\ \mu\text{F}$ across load resistor $R_L = 10\text{ k}\Omega$. AC feedback loop from collector of $T_2$ connects through capacitor $C_2 = 10\ \mu\text{F}$ in series with $R_3 = 36\text{ k}\Omega$ to the emitter node of $T_1$. Resistor $R_4 = 100\text{ k}\Omega$ connects the emitter node of $T_1$ to the emitter of $T_2$. Below the emitter node of $T_1$, a series branch consisting of $R_5 = 200\ \Omega$ and $R_6 = 1.3\text{ k}\Omega$ goes to ground, with $R_6$ bypassed by capacitor $C_4 = 3.3\ \mu\text{F}$.
**Symbolic form:** not derivable from figure.

[20]

(c) Impulse response of an LTI system, $h(n)$ is defined in the interval $N_0\le n\le N_1$. If the input $x(n)$ to the LTI system is zero except in the interval $N_2\le n\le N_3$, find the interval for which the output $y(n)$ exists in forms of $N_0$, $N_1$, $N_2$ and $N_3$.
[10]

[EE1-2025-Q4] Analog Electronics & Signals · BJTs & Fourier Transform
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 4 | Marks: 50 | Words: N/A
Syllabus: Characteristics and equivalent circuits (large and small-signal) of Diode, BJT, JFET and MOSFET. Diode circuits Clipping, clamping, rectifier. Biasing and bias stability. FET amplifiers. Current mirror; Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits. Filters; sinusoidal oscillators: criterion for oscillation; single-transistor and OPAMP configurations. Function generators and wave-shaping circuits. Linear and switching power supplies.
Directive: Determine, Find, Calculate
Theme (primary): Schottky Transistor Inverter
Theme (secondary): Fourier Transform & AC Maximum Power
Repeat cluster: none
Has figure: yes
(a) For the Schottky transistor circuit shown below, determine $I_B$, $I_D$, $I_C$ and $V_{CE}$. Next, remove the Schottky diode and determine $I_B$, $I_D$, $I_C$ and $V_{CE}$ assuming additional values of $V_{BE}\text{ (sat.)} = 0\cdot8\text{ V}$ and $V_{CE}\text{ (sat.)} = 0\cdot1\text{ V}$. Assume parameter values of $\beta=50$, $V_{BE}(on)=0\cdot7\text{ V}$ and $V_f=0\cdot3\text{ V}$ for the Schottky diode.

**Figure ID:** FIG-EE1-2025-Q4a
**Circuit description (netlist form):** NPN BJT circuit with a Schottky clamp diode connected between base (anode) and collector (cathode) carrying current $I_D$. The base terminal carries current $I_B$ and is connected via series resistor $R_S = 10\text{ k}\Omega$ to DC source $V_{BB} = 5.8\text{ V}$. The collector terminal carries current $I_C$ and is connected via load resistor $R_C = 1\text{ k}\Omega$ to DC supply $V_{CC} = 5\text{ V}$. The transistor emitter, the negative terminal of $V_{BB}$, and the negative terminal of $V_{CC}$ are connected to common ground.
**Symbolic form:** not derivable from figure.

[20]

(b) Find the Fourier transform of the following signals:
(i) $x(t)=\left[\frac{2\sin(3\pi t)}{\pi t}\right]\cdot\left[\frac{\sin(2\pi t)}{\pi t}\right]$
(ii) $x(t)=\int_{-\infty}^{t}\frac{\sin(2\pi t)}{\pi t}dt$
Specify the properties used.
[20]

(c) In the circuit shown below, is the ac voltage source given by $V_s=V_0\cos\omega t$, with $V_0=14\cdot14\text{ V}$ and $\omega=300\text{ rad/sec}$.
Calculate the value of load resistance $R_L$ for maximum power transfer and also find out maximum power transferred to load.

**Figure ID:** FIG-EE1-2025-Q4c
**Circuit description (netlist form):** AC voltage source $V_s$ operating at $\omega = 300\text{ rad/sec}$ is connected in series with internal resistance $R_1 = 40\ \Omega$ and the primary winding of an ideal transformer/coupled inductor with coupling coefficient $k=1$ and turns ratio $n=0.2$. The secondary winding is connected across a variable load resistance $R_L$.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2025-Q5] EM Theory & Energy Conversion · Waves & Transformers
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 5 | Marks: 50 | Words: N/A
Syllabus: Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves. Transmission lines travelling and standing waves, impedance matching, Smith chart.
Directive: Determine, Show, Calculate
Theme (primary): Electromagnetic Boundary Conditions
Theme (secondary): Transformer Regulation & Thyristor Overlap
Repeat cluster: none
Has figure: yes
(a) As shown in the figure, just inside the surface of a dielectric slab, the electric field $(E_1)$ is 15 V/m and it makes an angle of $30^\circ$ with the surface. The electric field $(E_2)$ makes $65\cdot5^\circ$ angle with the surface, just above the surface. Determine the magnitude of $E_2$ and the dielectric constant of the slab.

**Figure ID:** FIG-EE1-2025-Q5a
**Circuit description (netlist form):** Planar interface between medium 1 (dielectric slab, bottom) and medium 2 (region above surface, top). In medium 1, electric field vector $E_1$ of magnitude $15\text{ V/m}$ approaches the interface making an angle of $30^\circ$ with the boundary. In medium 2, electric field vector $E_2$ leaves the interface making an angle of $65.5^\circ$ with the boundary, with tangential component $E_{t2}$ along the horizontal interface and normal component $E_{n2}$ directed vertically upward along the normal.
**Symbolic form:** not derivable from figure.

[10]

(b) Show with the help of suitable derivations that the voltage regulation of a transformer varies with the power factor of the load. At what power factor will the voltage regulation be:
(i) zero, and
(ii) maximum?
[10]

(c) A single-phase Thyristor converter circuit as shown in the figure is feeding to a constant current load of 10 A. The supply voltage is of 230 V, 50 Hz and source inductance of 2 mH. Assume the Thyristors are ideal and triggering angle $\alpha=30^\circ$. Calculate (i) the overlap angle u, and (ii) the drop in output voltage.

**Figure ID:** FIG-EE1-2025-Q5c
**Circuit description (netlist form):** Single-phase fully-controlled bridge rectifier circuit. An AC source $v_s$ in series with source inductance $L_s = 2\text{ mH}$ carrying current $i_s$ feeds the AC terminals of a four-thyristor full-bridge converter. The DC output terminals are connected to a constant current load of $10\text{ A}$ (represented as an ideal current sink).
**Symbolic form:** not derivable from figure.

[10]

(d) Show that for a binomial random variable, the mean is given by np and the variance is given by np (1-p), where n gives the number of trials and p gives the probability of successes.
[10]

(e) The frequency range of operation of a superheterodyne FM receiver is 88 MHz - 108 MHz. The centre frequency of the IF amplifier $(f_{IF})$ and the frequency of the local oscillator $(f_{LO})$ are so chosen that $f_{IF}<f_{LO}.$ The design has to be so carried out that the image frequency $f_c'$ falls outside of the 88 MHz - 108 MHz region. Determine the minimum required value of $f_{IF}$ and the corresponding range of variations in $f_{LO}$ for that chosen value of $f_{IF}$.
[10]

[EE1-2025-Q6] Energy Conversion & Comm · DC Machines & Modulation
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 6 | Marks: 50 | Words: N/A
Syllabus: Principles of electromechanical energy conversion: Torque and emf in rotating machines. DC machines characteristics and performance analysis; starting and speed control of motors. Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers. 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
Directive: What is, Show, Determine
Theme (primary): Armature Reaction & Motor Efficiency
Theme (secondary): Rectifier Charger & DSB-SC Demodulation
Repeat cluster: none
Has figure: yes
(a) (i) What is meant by armature reaction in DC machines? Show with the help of developed view of armature conductors and poles that the effect of armature m.m.f. on the main field is entirely cross-magnetizing.
[10]
(ii) A 10 kW, 220 V DC shunt motor draws a line current of 5 A while running at no-load speed of 1200 rpm. It has an armature resistance of 0.2 $\Omega$ and field resistance of 200 $\Omega$. Determine the efficiency of the motor when it delivers rated load.
[10]

(b) A converter circuit as shown in the figure is being used to charge a battery of voltage $E=24\text{ V}$. The average charging current $I_{dc}=6\text{ A}$ and supply voltage $V_s=60\text{ V}$, 50 Hz. Determine
(i) the value of limiting resistor 'R', and
(ii) input power factor.

**Figure ID:** FIG-EE1-2025-Q6b
**Circuit description (netlist form):** Single-phase half-wave diode rectifier circuit. AC voltage source $V_s = 60\text{ V}$, $50\text{ Hz}$ is connected in series with a diode (anode connected to source, cathode pointing clockwise), a current limiting resistor $R$, and a battery of EMF $E = 24\text{ V}$ (positive terminal connected to resistor $R$, negative terminal returning to the AC voltage source).
**Symbolic form:** not derivable from figure.

[10]

(c) A DSB-SC amplitude-modulated signal with power spectral density as shown in figure (a) is corrupted with additive noise that has a $\left(\frac{N_0}{2}\right)$ power spectral density within the passband region of the signal. The received signal-plus-noise is demodulated and low pass filtered as shown in figure (b). Determine the SNR at the output of the LPF.
[BW: bandwidth]
[Given: carrier signal $=\cos(2\pi f_c t)$]

**Figure ID:** FIG-EE1-2025-Q6c
**Circuit description (netlist form):** Figure (a) illustrates the power spectral density $S_u(f)$ of a DSB-SC signal located at $\pm f_c$, spanning from $f_c - W$ to $f_c + W$ with triangular spectral density reaching peak value $P_0$. Figure (b) depicts a coherent demodulator block diagram where received signal $r(t)$ is multiplied by carrier $\cos(2\pi f_c t)$ and subsequently passed through an ideal low-pass filter (LPF) of bandwidth $BW = W$ with transfer function $|H(f)| = 1$ for $-W \le f \le W$ to yield the output.
**Symbolic form:** not derivable from figure.

[20]

[EE1-2025-Q7] EM Theory & Drives · Waves & AC Machines
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 7 | Marks: 50 | Words: N/A
Syllabus: Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves. Transmission lines travelling and standing waves, impedance matching, Smith chart.
Directive: Determine, Plot, State, Show, Demonstrate, Calculate
Theme (primary): Wave Propagation Vectors
Theme (secondary): Induction Motor Torque & Buck-Boost
Repeat cluster: none
Has figure: no
(a) It is given that $\vec{E}=E_m\sin(\omega t-\alpha z)\hat{a}_y$ in free space and $\alpha>0$.
(i) Determine $\vec{D}$, $\vec{B}$, and $\vec{H}$. Plot $\vec{E}$ and $\vec{H}$ at $t=0$. State clearly if any assumption is made.
[10]
(ii) Show that these $\vec{E}$ and $\vec{H}$ fields constitute a wave travelling in the z-direction. Also demonstrate that the wave speed and E/H depend solely on the properties of free space.
Given : $\mu_0=4\pi\times10^{-7}\text{ H/m}$ and $\epsilon_0=\frac{1}{36\pi}\times10^{-9}\text{ F/m}$.
[10]

(b) (i) A 3-phase, 4-pole, 400 V, 10 kW, 50 Hz slip ring induction motor develops rated output at rated voltage and frequency with its slip ring short-circuited. The maximum torque equal to twice the full load torque, occurs at a slip of 12.5% with zero external resistance in rotor circuit. Neglect stator impedance, stator core and mechanical losses. Determine:
I. slip and motor speed at full load torque, and
II. starting current in terms of full load current.
[10]
(ii) An industry has an average electrical load of 600 kW at a p.f. of 0.6 lagging. A synchronous motor with an efficiency of 90% is used to raise the combined p.f. to 0.9 lagging and at the same time supply a mechanical load of 100 kW. Calculate kVA capacity of the synchronous motor and synchronous motor operating power factor.
[10]

(c) The buck-boost converter has an input voltage of $V_s=12\text{ V}$. The duty cycle $D=0\cdot25$ and the switching frequency is 20 kHz. The inductance $L=150\ \mu\text{H}$ and filter capacitor $C=250\ \mu\text{F}$. The average load current $I_0=1.25\text{ A}$. Determine :
(i) the peak-to-peak ripple in the inductor current, and
(ii) the critical values of inductor L and capacitor C for CCM.
[10]

[EE1-2025-Q8] EM Theory & Comm · Smith Chart & AM Envelope
Exam: UPSC Mains 2025 | Paper: EE1 | Q.No: 8 | Marks: 50 | Words: N/A
Syllabus: Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves. Transmission lines travelling and standing waves, impedance matching, Smith chart.
Directive: Show, Determine, Discuss
Theme (primary): Smith Chart R-Circles & Wave Reflection
Theme (secondary): AM Envelope Detection & Inverter Control
Repeat cluster: none
Has figure: yes
(a) (i) Show that the Smith chart constructed for a lossless transmission line gives a family of r-circles, having a radius of $\frac{1}{(1+r)}$ for each circle which is centred at $\Gamma_r=\frac{r}{(1+r)}$ and $\Gamma_i=0$. Here, $r=\text{normalized resistance of the load impedance}$, $\Gamma_r$ and $\Gamma_i=\text{real and imaginary parts of voltage reflection coefficient of the load impedance, respectively}$.
[10]
(ii) In the figure given below, determine the amplitudes of the reflected and transmitted $\vec{E}$ and $\vec{H}$ at the interface, if $E_0^i=1\cdot2\times10^{-3}\text{ V/m}$ in region 1, where $\epsilon_{r1}=7.5$, $\mu_{r1}=1$ and $\sigma_1=0$. Given Region 2 is a free space and assume normal incidence. Also, $\mu_0=4\pi\times10^{-7}\text{ H/m}$ and $\epsilon_0=\frac{1}{36\pi}\times10^{-9}\text{ F/m}$.

**Figure ID:** FIG-EE1-2025-Q8aii
**Circuit description (netlist form):** Normal incidence boundary problem between medium 1 on left ($\epsilon_{r1} = 7.5, \mu_{r1} = 1, \sigma_1 = 0$) and medium 2 on right (free space $\epsilon_0, \mu_0$). Incident wave in medium 1 has upward electric field vector $E_0^i$ and propagation direction vector $\psi^i$ pointing to the right towards interface. Reflected wave in medium 1 has upward electric field vector $E_0^r$ and propagation direction vector $\psi^r$ pointing to the left. Transmitted wave in medium 2 has upward electric field vector $E_0^t$ and propagation direction vector $\psi^t$ pointing to the right.
**Symbolic form:** not derivable from figure.

[10]

(b) A sinusoidal modulating signal $m(t)$ of frequency $f_m$ produces an AM signal: $u(t) = A_c[1 + \beta \cos (2\pi f_m t)] \cos (2\pi f_c t)$, where $f_c$ is carrier frequency. Here, $f_c \gg f_m$ and $\beta=2$. This $u(t)$ is applied to an ideal envelope detector which produces an output $x(t)$.
(i) Determine the Fourier series representation of $x(t)$.
(ii) Also determine the ratio of second harmonic amplitude to fundamental amplitude in $x(t)$.
[20]

(c) Discuss in brief various methods of voltage control within 3-phase inverters.
[10]