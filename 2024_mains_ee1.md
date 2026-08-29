[EE1-2024-Q1] Circuits & Systems · Network Theorems & Signals
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 1 | Marks: 50 | Words: N/A
Syllabus: Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications; transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits. Two-port networks.
Directive: Find, Determine, Design, Draw
Theme (primary): DC Circuits & Z-Transform
Theme (secondary): Current Mirror & BCD Error Detector
Repeat cluster: none
Has figure: yes
1. (a) Find the voltage on points A and B of the given circuit:

**Figure ID:** FIG-EE1-2024-Q1a
**Circuit description (netlist form):** A DC circuit with reference ground at the bottom rail. An independent 10 V DC voltage source has its negative terminal connected to ground and positive terminal connected to a 2 $\Omega$ resistor. The 2 $\Omega$ resistor connects to node A. A 2 $\Omega$ resistor is connected between node A and ground. From node A, a series combination of a 1 $\Omega$ resistor and a 2 A independent current source (directed rightward) connects to a node defined by the positive terminal of an independent 5 V DC voltage source. The negative terminal of the 5 V source is connected to ground. In parallel with the 5 V source is a voltage divider consisting of a 2 $\Omega$ resistor connected between the positive terminal of the 5 V source and terminal B, and a 3 $\Omega$ resistor connected between terminal B and ground.
**Symbolic form:** not derivable from figure.

[10]

(b) Determine the Z-transform of $x[n]=n(\frac{1}{2})^{n+2}u[n+2].$ Specify the properties used. [10]

(c) In the circuit diagram given here, $T_{1}$ and $T_{2}$ are transistors with matched characteristics. The transistor parameters in active region are $\beta=200$ and $V_{BE}=688\text{ mV}$. Find $V_{CE}$ of transistor $T_{2}$:

**Figure ID:** FIG-EE1-2024-Q1c
**Circuit description (netlist form):** A BJT current mirror circuit supplied by a $+12\text{ V}$ DC rail and reference ground. Transistor $T_1$ (NPN) has its emitter connected to ground, and its collector connected to its base (diode-connected) and via a $560\ \Omega$ pull-up resistor to the $+12\text{ V}$ rail. Transistor $T_2$ (NPN) has its emitter connected to ground, its base connected to the base of $T_1$, and its collector connected to the $+12\text{ V}$ rail through a $470\ \Omega$ pull-up resistor.
**Symbolic form:** not derivable from figure.

[10]

(d) A Binary Coded Decimal (BCD) code is to be transmitted to a remote receiver. Bits are arranged as $A_{3}$ $A_{2}$ $A_{1}$ $A_{0}$. Design a circuit at the receiving end which has an error detector to check the legal BCD code and produce a HIGH for any error condition. [10]

(e) In the circuit given here, $D_{1}$ is an ideal diode and key $K_{1}$ is ON for a long period of time. Now at time $t_{0}$, key $K_{1}$ is opened. Draw the voltage waveform on capacitor $C_{1}$ and find the final steady-state voltage on the capacitor :

**Figure ID:** FIG-EE1-2024-Q1e
**Circuit description (netlist form):** A DC circuit with a $9\text{ V}$ DC voltage source whose negative terminal is connected to the common ground rail. An inductor $L = 10\text{ mH}$ is connected between the positive terminal of the $9\text{ V}$ source and a switching node. A branch consisting of a switch $K_1$ in series with a resistor $R_1 = 0\cdot9\ \Omega$ is connected between the switching node and ground, with the switch opening at time $t_0$. An ideal diode $D_1$ has its anode connected to the switching node and its cathode connected to a capacitor $C_1 = 100\ \mu\text{F}$, whose other terminal is connected to ground.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2024-Q2] Digital Electronics & Systems · CMOS & Signals
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 2 | Marks: 50 | Words: N/A
Syllabus: Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS). Combinational circuits arithmetic circuits, code converters, multiplexers and decoders. Sequential circuits: latches and flip-flops, counters and shift-registers. Comparators, timers, multivibrators. Sample and hold circuits, ADCs and DACs. Semiconductor memories. Logic implementation using programmable devices (ROM, PLA, FPGA).
Directive: Draw, Find, Sketch
Theme (primary): CMOS Gate Implementation
Theme (secondary): Signal Integration & Dependent Sources
Repeat cluster: none
Has figure: yes
2. (a) Draw the circuit diagram, function table, logic symbol and switch model for a CMOS gate (using six transistors) with two inputs A and B and an output Z, such that
$Z=0$ if $A=1$ and $B=0$, and $Z=1$ otherwise [20]

(b) For the signals $f_{1}(t)$ and $f_{2}(t)$ shown in the figures below, find and sketch $\int_{-\infty}^{t}f(x)dx$:

**Figure ID:** FIG-EE1-2024-Q2b
**Circuit description (netlist form):** Two continuous-time signal waveform plots versus time $t$. The first plot, $f_1(t)$, starts at $t=0$ with a rectangular pulse of amplitude $+1$ for $0 < t < 1$, followed by a negative pulse of amplitude $-1$ from $t=1$ to $t=3$, and an upward impulse of strength $+1$ located at $t=3$, being zero elsewhere. The second plot, $f_2(t)$, shows a constant signal level of $1$ along with three downward impulses of strength $-1$ located at $t=1$, $t=2$, and $t=3$.
**Symbolic form:** not derivable from figure.

[20]

(c) In the circuit given here, find the value of voltage $v_{1}$:

**Figure ID:** FIG-EE1-2024-Q2c
**Circuit description (netlist form):** A DC network with a common ground rail at the bottom. The left portion consists of four parallel branches connected between an upper node and ground: an independent current source of $12\text{ mA}$ directed upwards, a voltage-controlled current source of value $\frac{v_x}{20}$ directed upwards, a $2\text{ k}\Omega$ resistor with voltage $v_1$ across it (positive at top), and an independent current source of $2\text{ mA}$ directed downwards. The right portion consists of a node with voltage $v_x$ across a parallel $1\text{ k}\Omega$ resistor to ground (positive at top) and an independent current source of $-5\text{ mA}$ directed upwards from ground. This node connects via a $4\text{ k}\Omega$ series resistor to a node held at $+5\text{ V}$ by an independent $5\text{ V}$ voltage source referenced to ground. In parallel with the $5\text{ V}$ source is a branch consisting of a $1\text{ k}\Omega$ resistor in series with an independent current source of $2\text{ mA}$ directed upwards.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2024-Q3] Signals & Analog Electronics · Laplace & Op-Amps
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 3 | Marks: 50 | Words: N/A
Syllabus: Representation of continuous-time and discrete-time signals and systems; LTI systems; convolution; impulse response; time-domain analysis of LTI systems based on convolution and differential/difference equations. Fourier transform, Laplace transform, Z-transform, Transfer function. Sampling and recovery of signals DFT, FFT Processing of analog signals through discrete-time systems.
Directive: Determine, Explain, Draw, Find, Write
Theme (primary): Bilateral Laplace Transform
Theme (secondary): Op-Amp Waveform Generator & NAND Logic
Repeat cluster: none
Has figure: yes
3. (a) Determine the time signal that corresponds to the following bilateral Laplace transform and the ROCs given below by using the method of partial fractions:
$$X(s)=\frac{4s^{2}+8s+10}{(s+2)(s^{2}+2s+5)}$$
(i) With ROC $\text{Re}(s)<-2$
(ii) With ROC $\text{Re}(s)>-1$
(iii) With ROC $-2<\text{Re}(s)<-1$ [20]

(b) Explain the working of the given OPAMP circuit. Draw the output waveforms at points A and B showing the time and voltage.
Given that, $V_{Z_{1}}=V_{Z_{2}}=3\cdot3\text{ V}$, $C_{1}=1\ \mu\text{F}$, the power supply voltage to OPAMPs is $\pm 12\text{ V}$ and $R_{1}=R_{2}=R_{3}=R_{4}=R_{5}=R_{6}=2\text{ k}\Omega$:

**Figure ID:** FIG-EE1-2024-Q3b
**Circuit description (netlist form):** A waveform generator circuit with three operational amplifiers ($I_1, I_2, I_3$). Op-amp $I_1$ has its inverting terminal grounded and non-inverting terminal connected to a node receiving feedback through resistor $R_1$ from output terminal A and through resistor $R_2$ from node D. The output of $I_1$ is connected via resistor $R_3$ to node D, which is clamped to ground by two series back-to-back Zener diodes $Z_1$ and $Z_2$. Node D connects via resistor $R_4$ to the inverting input of integrator op-amp $I_2$, which has its non-inverting terminal grounded and a feedback capacitor $C_1$ between its inverting input and output terminal A. Node D also connects to the non-inverting input of op-amp $I_3$. The inverting input of $I_3$ is connected to a voltage divider consisting of resistor $R_5$ to ground and feedback resistor $R_6$ connected to output terminal B. All op-amps are powered by $\pm 12\text{ V}$.
**Symbolic form:** not derivable from figure.

Suggest to replace suitable resistances so that the output voltages at A and B are having swing of $\pm 6\text{ V}$ and the output frequency is fixed to $500\text{ Hz}$. [20]

(c) Find the logic equations for the outputs in the concise form and write the corresponding truth table for the circuit given below :

**Figure ID:** FIG-EE1-2024-Q3c
**Circuit description (netlist form):** A digital logic circuit with two inputs $D_0$ and $D_1$, four outputs $\overline{Y}_0, \overline{Y}_1, \overline{Y}_2, \overline{Y}_3$, and four NAND gates. A first 2-input NAND gate receives inputs $D_0$ and $D_1$, and its output connects directly to output terminal $\overline{Y}_3$, as well as to inputs of the other three gates. A second 2-input NAND gate receives input $D_0$ and the output of the first NAND gate, producing output $\overline{Y}_1$. A third 2-input NAND gate receives input $D_1$ and the output of the first NAND gate, producing output $\overline{Y}_2$. A fourth 3-input NAND gate receives inputs from the output of the first NAND gate, the output $\overline{Y}_1$, and the output $\overline{Y}_2$, producing output $\overline{Y}_0$.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2024-Q4] Circuits & Analog Electronics · Network Theorems & Op-Amps
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 4 | Marks: 50 | Words: N/A
Syllabus: Characteristics and equivalent circuits (large and small-signal) of Diode, BJT, JFET and MOSFET. Diode circuits Clipping, clamping, rectifier. Biasing and bias stability. FET amplifiers. Current mirror; Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits. Filters; sinusoidal oscillators: criterion for oscillation; single-transistor and OPAMP configurations. Function generators and wave-shaping circuits. Linear and switching power supplies.
Directive: Draw, Calculate, Define, Determine
Theme (primary): Thevenin Equivalent & Op-Amps
Theme (secondary): Voltage Regulators & Multiplexers
Repeat cluster: none
Has figure: yes
4. (a) In the circuit diagram given here, load resistance $R_{L}$ is to be set for maximum power transfer. Draw Thevenin equivalent circuit across ab and calculate the value of $R_{L}$ for maximum power transfer. Also calculate the power loss in resistance $R_{3}$, when the circuit is delivering maximum power to load $R_{L}$:

**Figure ID:** FIG-EE1-2024-Q4a
**Circuit description (netlist form):** A linear circuit with output terminals $a$ and $b$. A $9\text{ V}$ DC source (positive terminal up) is connected in series with a resistor $R_1 = 12\ \Omega$ to an internal node. A second branch consisting of a resistor $R_2 = 12\ \Omega$ in series with a $3\text{ V}$ DC source (positive terminal up) connects the internal node to the common bottom rail $b$. A dependent voltage source with value $2V_{ab}$ (negative terminal left, positive terminal right) is connected between the internal node and terminal $a$. A resistor $R_3 = 4\ \Omega$ and a variable load resistor $R_L$ are connected in parallel across terminals $a$ and $b$, with the voltage across terminals $a$ and $b$ designated as $V_{ab}$.
**Symbolic form:** not derivable from figure.

[20]

(b) (i) Define input bias current and input offset voltage for an OPAMP. Using an OPAMP, draw an inverting amplifier circuit with gain $=-4$ in such a way that the effect of bias current is minimized. [10]

(ii) In the linear regulated power supply circuit shown here, calculate the output voltage adjustment range and maximum power dissipation in transistor $T_{1}$ in worst case:

**Figure ID:** FIG-EE1-2024-Q4b
**Circuit description (netlist form):** A series linear regulated power supply circuit with input $15\text{ V}$ to $20\text{ V}$ DC and reference ground. A $1\text{ k}\Omega$ resistor biases a $12\text{ V}$ Zener diode from the input rail. Connected in parallel with the Zener diode is a divider consisting of a $1\text{ k}\Omega$ resistor, a $10\text{ k}\Omega$ potentiometer, and a $1\text{ k}\Omega$ resistor connected to ground. The non-inverting input of op-amp $I_1$ connects to the potentiometer wiper. The output of $I_1$ drives the base of NPN pass transistor $T_1$ through a $470\ \Omega$ resistor. Transistor $T_1$ has its collector connected to the input rail and its emitter connected to a $0\cdot7\ \Omega$ current-sensing resistor. An NPN current-limit transistor $T_2$ has its base-emitter junction connected across the $0\cdot7\ \Omega$ resistor and its collector connected to the base of $T_1$. The inverting input of $I_1$ is connected to the load side of the $0\cdot7\ \Omega$ resistor, which forms the regulated output terminal with respect to ground.
**Symbolic form:** not derivable from figure.

($T_{1}$ and $T_{2}$ are Si transistors) [10]

(c) A circuit using three 2-input multiplexers is shown below. Determine the function performed by this circuit:

**Figure ID:** FIG-EE1-2024-Q4c
**Circuit description (netlist form):** A digital multiplexer network composed of three 2-to-1 multiplexers. The upper-left multiplexer receives data inputs $I_3$ and $I_2$, controlled by select line $S_1$, producing intermediate output $Z_2$. The lower-left multiplexer receives data inputs $I_1$ and $I_0$, controlled by the same select line $S_1$, producing intermediate output $Z_1$. The right multiplexer receives data inputs $Z_2$ and $Z_1$, controlled by select line $S_0$, and produces the circuit output $Z$.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2024-Q5] EM Theory & Energy Conversion · Waves & Transformers
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 5 | Marks: 50 | Words: N/A
Syllabus: Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves. Transmission lines travelling and standing waves, impedance matching, Smith chart.
Directive: Find, How can, Is the, Determine
Theme (primary): Uniform Plane Waves
Theme (secondary): Transformers & FM Systems
Repeat cluster: none
Has figure: yes
5. (a) A uniform plane wave travels in vacuum along +y direction. The electric field of the wave at some instant is given as $\vec{E}=4\hat{x}+3\hat{z}.$ Find the vector magnetic field $\vec{H}.$ (Given, $\mu_{0}=4\pi\times10^{-7}\text{ H/m}$, $\epsilon_{0}=\frac{1}{36\pi}\times10^{-9}\text{ F/m}$) [10]

(b) The maximum efficiency of a 200 kVA, 3300/600 V, 50 Hz, single-phase transformer is 98% and occurs at 75% full load and unity power factor. If the leakage impedance is 10%, find the voltage regulation at full load and power factor 0-8 lagging. [10]

(c) A diode circuit with an L-C load is shown in the figure, with the capacitor having an initial voltage $V_{C}(t=0)=120\text{ V}$, capacitance $C=12\ \mu\text{F}$ and inductance $L=48\ \mu\text{H}$. If switch S is closed at $t=0\text{ s}$, then find the following:
(i) Peak value of current $i$
(ii) Conduction time of the diode

**Figure ID:** FIG-EE1-2024-Q5c
**Circuit description (netlist form):** A closed series resonant loop consisting of a switch $S$ (closing at $t=0$), an inductor $L = 48\ \mu\text{H}$, a capacitor $C = 12\ \mu\text{F}$ with initial voltage $V_C(t=0) = 120\text{ V}$ (positive at the upper terminal), and a diode in the return path with its anode connected to the switch and cathode connected to the bottom plate of the capacitor. The loop current is designated as $i$.
**Symbolic form:** not derivable from figure.

[10]

(d) How can linear pre-emphasis and de-emphasis filters be employed to improve the performance of an FM system? Is the improvement in output SNR dependent on both the frequency responses of the pre-emphasis filter and the de-emphasis filter? [10]

(e) A transmission line is 25 m long. It has characteristic impedance $Z_{0}=40\ \Omega$ and operates at 2 MHz. The line is terminated with a load of $Z_{L}=(50+j30)\ \Omega$. If the wave velocity is $u=0\cdot8c$ (with $c=3\times10^{8}\text{ m/s}$), determine (i) the reflection coefficient and (ii) the input impedance. [10]

[EE1-2024-Q6] Analog Communication & Power Electronics · AM/FM & Inverters
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 6 | Marks: 50 | Words: N/A
Syllabus: Random variables: continuous, discrete; probability, probability functions. Statistical averages; probability models; Random signals and noise white noise, noise equivalent bandwidth; signal transmission with noise; signal to noise ratio. Linear CW modulation: Amplitude modulation : DSB, DSB-SC and SSB. Modulators and Demodulators; Phase and Frequency modulation: PM & FM signals; narrows band FM; generation & detection of FM and PM, Deemphasis, Preemphasis. CW modulation system: Superhetrodyne receivers, AM receivers, communication receivers, FM receivers, phase locked loop, SSB receiver Signal to noise ratio calculation or AM and FM receivers.
Directive: Show, Determine, Plot, Explain, Draw, Find
Theme (primary): AM Demodulation & Narrowband FM
Theme (secondary): PWM Inverters & Induction Motor
Repeat cluster: none
Has figure: yes
6. (a) (i) An AM signal $s(t)=A_{c}[1+k_{a}m(t)]\cos(2\pi f_{c}t)$ is applied to the system shown in the figure. Show that the message signal $m(t)$ can be obtained from the square-rooter output $v_{3}(t)$:

**Figure ID:** FIG-EE1-2024-Q6a
**Circuit description (netlist form):** A block diagram of a demodulator system. The input AM signal $s(t)$ enters a Squarer block producing $v_1(t) = s^2(t)$. The signal $v_1(t)$ is fed into a Low-pass filter producing intermediate signal $v_2(t)$. The signal $v_2(t)$ then passes into a Square rooter block to produce output signal $v_3(t) = \sqrt{v_2(t)}$.
**Symbolic form:** $$v_3(t) = \sqrt{\text{LPF}\{s^2(t)\}}$$

Assume that $|k_{a}m(t)|<1$ for all $t$, the message signal $m(t)$ is limited to the interval $-W\le f\le W$, and the carrier frequency $f_{c}>2W.$ [10]

(ii) A narrow band FM signal is approximately given as
$$s(t)\approx A_{c}\cos(2\pi f_{c}t)-\beta A_{c}\sin(2\pi f_{c}t)\sin(2\pi f_{m}t)$$
Determine the envelope of this modulated signal. Also determine the ratio of the maximum to the minimum value of this envelope. Plot this ratio versus $\beta$, with $\beta$ restricted to the interval $0\le\beta\le0\cdot4$.
Also determine the average power of the narrow band FM signal, expressed as a percentage of the average power of the unmodulated carrier wave. [10]

(b) (i) Explain why PWM inverters are preferred over square wave inverters. Further, draw the harmonic spectrum to highlight the differences in unipolar and bipolar PWM techniques. [10]

(ii) A single-phase, full-bridge inverter has DC-link voltage $V_{DC}=400\text{ V}$, and the fundamental frequency of 50 Hz. Find the r.m.s. value of the voltages of the fundamental and next two prominent harmonics for the following cases:
(1) Square wave mode
(2) Voltage cancellation mode with $\alpha=20^{\circ}$ [10]

(c) A 50 hp, 440 V, 50 Hz, star-connected, three-phase induction motor has a starting torque of 75% and maximum torque of 250% of the full-load torque. Find the following:
(i) Slip at which maximum torque occurs
(ii) Slip at full-load torque [10]

[EE1-2024-Q7] Power Electronics & EM Theory · Rectifiers & Fields
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 7 | Marks: 50 | Words: N/A
Syllabus: Semi-conductor power devices diode, transistor, thyristor, triac, GTO and MOSFET-static characteristics and principles of operation; triggering circuits; phase control rectifiers; bridge converters: fully-controlled and half-controlled; principles of thyristor choppers and inverters; DC-DC converters; Switch mode inverter; basic concepts of speed control of dc and ac motor drives applications of variable-speed drives.
Directive: Draw, Derive, Find, Show, Determine
Theme (primary): Three-Phase Rectifiers
Theme (secondary): Synchronous Generators & EM Field Boundary
Repeat cluster: none
Has figure: yes
7. (a) (i) Draw the neat and properly labelled output voltage waveform of a three-phase, phase-controlled rectifier having firing angle $\alpha$. Also derive the relationship for average output voltage in terms of line voltage $V_{LL}$ and firing angle $\alpha$. [10]

(ii) A three-phase full-wave controlled rectifier is being operated from a star-connected, 415 V, 50 Hz supply. This rectifier is feeding a constant current load of 15 kW. It is required to obtain an average output voltage of 80% of maximum possible output voltage. Find the firing angle, r.m.s. value of line current and input power factor. Assume devices are ideal. [10]

(b) (i) Show that the maximum power that a synchronous generator can supply when connected to constant voltage, constant frequency busbars increases with the excitation. [10]

(ii) An 11 kV, 3-phase, star-connected turbo-alternator delivers 250 A at unity power factor when running on constant voltage and frequency busbars. If the excitation is increased so that the delivered current rises to 300 A, find the power factor at which now machine works and percentage increase in the induced e.m.f., assuming a constant steam supply and unchanged efficiency. The armature resistance is $0\cdot5\ \Omega$ per phase and the synchronous reactance is $10\ \Omega$ per phase. [10]

(c) A medium has infinite conductivity for $z\le0,$ $\epsilon_{r}=7$ and $\mu_{r}=18$, and $\sigma=0$ for $z>0$. The electric field for $z>0$ is given as $\vec{E}=10\cos(3\times10^{8}t-15x)\hat{z},$ as shown below. Determine the surface charge density and surface current density at location (3, 4, 0) at $t=0\cdot8\text{ ns}$. Given, $\mu_{0}=4\pi\times10^{-7}\text{ H/m}$, $\epsilon_{0}=\frac{1}{36\pi}\times10^{-9}\text{ F/m}$:

**Figure ID:** FIG-EE1-2024-Q7c
**Circuit description (netlist form):** A boundary representation at $z = 0$ between a perfectly conducting medium occupying $z \le 0$ (with $\epsilon_r = 7, \mu_r = 18$) and a non-conducting medium occupying $z > 0$ (with $\sigma = 0$), showing the electric field vector $\vec{E}$ oriented in the $+z$ direction in the region $z > 0$.
**Symbolic form:** not derivable from figure.

[10]

[EE1-2024-Q8] EM Theory & Communication · Boundary Conditions & Modulations
Exam: UPSC Mains 2024 | Paper: EE1 | Q.No: 8 | Marks: 50 | Words: N/A
Syllabus: Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves. Transmission lines travelling and standing waves, impedance matching, Smith chart.
Directive: Determine, What is
Theme (primary): Magnetic Boundary Conditions
Theme (secondary): Analog Modulation SNR & DC-DC Converter
Repeat cluster: none
Has figure: yes
8. (a) In the figure given below, region 1 is the side of the plane $y+z=1$ containing the origin and in this region, $\mu_{r_{1}}=5$. In region 2, $\mu_{r_{2}}=7.$ It is given that $\vec{B}_{1}=3\cdot0\vec{a}_{x}+1\cdot0\vec{a}_{y}\text{ (T)}.$ Determine $\vec{B}_{2}$ and $\vec{H}_{2}$. Given, $\mu_{0}=4\pi\times10^{-7}\text{ H/m}$:

**Figure ID:** FIG-EE1-2024-Q8a
**Circuit description (netlist form):** A two-dimensional boundary diagram on the $y$-$z$ plane with origin $O$. The boundary line represents the plane $y+z=1$. Region 1 contains the origin and has relative permeability $\mu_{r_1} = 5$. Region 2 is on the opposite side of the boundary and has relative permeability $\mu_{r_2} = 7$.
**Symbolic form:** not derivable from figure.

[20]

(b) The message signal $m(t)$ has a bandwidth of 20 kHz, a power of 20 W and a maximum amplitude of 8. It is desired to transmit this message through a channel to the destination with 80 dB attenuation and additive white noise with power spectral density $S_{n}(f)=\frac{N_{0}}{2}=0.5\times10^{-12}\text{ W/Hz}$ and achieve an SNR at the modulator output of at least 50 dB. What is the required transmitter power and channel bandwidth, if the modulation scheme employed is as under?
(i) DSB-SC AM
(ii) SSB AM
(iii) Conventional DSB AM with modulation index 0.6 [20]

(c) An ideal DC-DC converter as shown in the figure has an input voltage of $V_{s}=20\text{ V}$, the duty ratio $D=0\cdot25$ and the switching frequency is 20 kHz. The inductance $L=150\ \mu\text{H}$ and capacitance $C=240\ \mu\text{F}$. The average diode current is 1-2 A. Determine the following:
(i) Peak-peak ripple current of the inductor
(ii) Peak current through the switch S

**Figure ID:** FIG-EE1-2024-Q8c
**Circuit description (netlist form):** A DC-DC converter circuit with input DC voltage source $V_s$ (positive at top). Switch $S$ is connected in series from the positive input terminal to an intermediate node. An inductor $L = 150\ \mu\text{H}$ is connected in shunt between this intermediate node and the bottom negative return rail. A diode is connected in the top branch between the intermediate node and the output node, with its cathode connected to the intermediate node and its anode connected to the output node. A capacitor $C = 240\ \mu\text{F}$ and a LOAD block are connected in parallel between the output node and the common bottom return rail, with output voltage labeled $V_o$ (positive at top).
**Symbolic form:** not derivable from figure.

[10]