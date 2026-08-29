# PAPER I

## SECTION A

### [EE1-2020-Q1] RL Circuit Transient Response After Switching · Signal Sketching, DC Motor Field Control, Darlington Pair Biasing & PLA Boolean Implementation

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Find
- **Theme (primary):** RL Circuit Transient Response After Switching
- **Theme (secondary):** Signal Sketching, DC Motor Field Control, Darlington Pair Biasing & PLA Boolean Implementation
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> (a) The switch shown in Figure 1(a) has been closed for a very long time and it is opened at time $t=0$.
> (i) Find the value of $i_{L}$ for $t<0$.
> (ii) Just after the switch is opened, find the value of $i_{L}(0^{+})$.
> (iii) Determine the expression for $i_{L}(t)$ for $t>0$ and find the value of $i_{L}(\infty)$. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q1a
> **Circuit description (netlist form):** A circuit consists of a reference ground node (bottom rail, node 0) and a common top node (node 1). A 100 V DC voltage source is connected between node 0 (negative) and node 2 (positive), followed by a $20\,\Omega$ resistor connected between node 2 and node 1. A central branch connected to node 1 contains a switch that opens at $t=0$, in series with a $5\,\Omega$ resistor and a 100 V DC voltage source with its negative terminal at the resistor side and positive terminal at node 0. A rightmost branch connects an inductor $L = 0.5\text{ H}$ between node 1 and node 0, with inductor current $i_L$ directed downward from node 1 to node 0.
> **Symbolic form:** not derivable from figure.
> 
> (b) Sketch the continuous-time signal $x(t)=t[u(-t+1)-u(-t-1)]$ over a suitable range of t, where $u(t)$ is a unit step function. [10]
> 
> (c) A 220 V, 8-pole lap wound dc shunt motor has 1200 conductors and has a field resistance of $220\,\Omega$. The motor takes a line current of 50 A at full load and rated speed. Find the additional resistance required in the field circuit if its speed is to be raised by 40 percent while maintaining its torque output at previous full load value. Assume linear magnetic circuit for the machine and resistance of each armature conductor as $50\text{ m}\Omega$. [10]
> 
> (d) A Darlington transistor pair circuit is shown in Figure 1(d) below. Both the transistors have dc current gain of 30. In the circuit $V_{CC}=+12\text{ V}$, $R_{E}=1\cdot5\text{ k}\Omega$.
> (i) Find the value of $R_{1}$ needed to bias the circuit such that $V_{CEQ_{2}}=5\text{ V}$ for transistor $T_{2}$.
> (ii) With the same value of $R_{1}$ as obtained above, determine the value of $V_{CEQ_{1}}$.
> Assume both $T_{1}$ and $T_{2}$ are Si transistors. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q1d
> **Circuit description (netlist form):** A Darlington pair configuration consisting of two NPN transistors $T_1$ and $T_2$. A DC supply rail $V_{CC} = +12\text{ V}$ is connected to the collector of $T_1$, the collector of $T_2$, and one end of resistor $R_1$. The other end of $R_1$ is connected to the base of $T_1$. The emitter of $T_1$ is directly connected to the base of $T_2$. The emitter of $T_2$ is connected to ground through resistor $R_E = 1.5\text{ k}\Omega$.
> **Symbolic form:** not derivable from figure.
> 
> (e) Implement the following Boolean functions with a $4\times3$ Programmable Logic Array (PLA):
> $F_{1}=\overline{B}\overline{C}+A\overline{B}$
> $F_{2}=AB\overline{C}+A\overline{B}C\overline{D}$
> $F_{3}=\overline{A}\overline{B}\overline{C}D+A\overline{B}CD$ [10]

---

### [EE1-2020-Q2] Two-Port h-Parameters and Output Impedance · Boost-Converter Switch Timing, LTI System Response & Combinational SOP Minimization

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Two-port networks.
- **Directive:** Find
- **Theme (primary):** Two-Port h-Parameters and Output Impedance
- **Theme (secondary):** Boost-Converter Switch Timing, LTI System Response & Combinational SOP Minimization
- **Repeat cluster:** RC13 (Two-Port Network Parameters)
- **Has figure:** yes

> (a) (i) Find the h-parameters of the two-port circuit shown in Figure 2(a)(i). If the input contains a source voltage with series resistance of $200\,\Omega$, find the output impedance $(Z_{out})$ of the circuit. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q2ai
> **Circuit description (netlist form):** A two-port network with input port terminals at node 1 (+) and node 0 (-), across which input voltage $V_1$ appears. Between node 1 and node 0, a $1\text{ k}\Omega$ resistor and a voltage-controlled current source of value $10^{-5}V_2$ directed upward from node 0 to node 1 are connected in parallel. At the output port, a voltage-controlled voltage source of value $100V_1$ is connected with negative terminal at node 3 and positive terminal at node 0; a $10\text{ k}\Omega$ resistor is connected between node 3 and node 2 (+ output terminal), with output voltage $V_2$ across node 2 and node 0.
> **Symbolic form:** not derivable from figure.
> 
> (ii) In Figure 2(a)(ii)(A), the ideal switch S is switched on and off with a switching frequency $f=10\text{ kHz}$. The circuit is operated in steady state at the boundary of continuous and discontinuous conduction, so that the inductor current i is as shown in the Figure 2(a)(ii)(B). Find the values of on-time $T_{on}$ of the switch and peak current of inductor $I_{p}$. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q2aii
> **Circuit description (netlist form):** A DC source of 100 V (+ top, - bottom) is connected via a switch S to node 1. An inductor of $100\,\mu\text{H}$ is connected between node 1 and ground (node 0) carrying downward current $i$. A diode has its cathode connected to node 1 and its anode connected to the negative terminal of a 500 V DC source, whose positive terminal is connected to ground node 0. An associated timing diagram shows switch S operating with period $T = T_{on} + T_{off}$, and inductor current $i$ rising linearly from 0 to $I_p$ during $T_{on}$ and falling from $I_p$ to 0 during $T_{off}$.
> **Symbolic form:** not derivable from figure.
> 
> (b) The unit-impulse response of a linear time-invariant continuous-time system is given by $h(t)=[3e^{-3t}+2t\,e^{-3t}]u(t)$.
> Determine the system response $y(t)$ for an input $x(t)=10e^{-3t}u(t)$, where $u(t)$ is a step function. [20]
> 
> (c) Design a combinational circuit to implement the minimal sum-of-products of the logic function $F=\Sigma_{WXYZ}(1,2,3,5,7,11,13)$. [10]

---

### [EE1-2020-Q3] Differential Amplifier with Active Load: Small-Signal Gain · Coupled-Coil Voltage Ratio, Thevenin Equivalent & Finite-Sequence Z-Transform

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits.
- **Directive:** Calculate
- **Theme (primary):** Differential Amplifier with Active Load: Small-Signal Gain
- **Theme (secondary):** Coupled-Coil Voltage Ratio, Thevenin Equivalent & Finite-Sequence Z-Transform
- **Repeat cluster:** RC19 (Op-Amp/Transistor Amplifier Characteristics)
- **Has figure:** yes

> (a) Shown below (Figure 3(a)) is a differential amplifier with a three transistor active load. Draw the small signal equivalent circuit of its output stage with active load and calculate its small signal differential mode voltage gain.
> Assume the output impedances of the transistors $Q_{1}$ to $Q_{5}$ to be $r_{01}$ to $r_{05}$ respectively.
> Assume the base currents to be negligible. [20]
> 
> **Figure ID:** FIG-EE1-2020-Q3a
> **Circuit description (netlist form):** Differential amplifier with positive rail $+V_{CC}$ and negative rail $-V_{CC}$. NPN pair $Q_1, Q_2$ have emitters connected to a constant current sink $I_Q$ going to $-V_{CC}$. Base of $Q_1$ is driven by $+v_d/2$ and base of $Q_2$ by $-v_d/2$. Active load consists of PNP transistors $Q_3, Q_4$ with emitters tied to $+V_{CC}$ and bases connected together to the emitter of PNP transistor $Q_5$. Collector of $Q_5$ is connected to $-V_{CC}$, and base of $Q_5$ is tied to collector of $Q_3$ and collector of $Q_1$. Collector of $Q_4$ connects to collector of $Q_2$, coupling capacitor $C_C$, and output node $v_o$ terminated with resistor $R_L$ to ground. Small-signal currents indicated: $i_1 = g_m v_d / 2$, $i_2 = g_m v_d / 2$, $i_4 = g_m v_d / 2$, and output branch current $i_o$.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) Let $\omega=1000\text{ rad/sec}$ for the circuit of Figure 3(b)(i) and determine the value of the ratio $V_{o}/V_{s}$, if $L_{1}=1\text{ mH}$, $L_{2}=25\text{ mH}$ and $k=1$. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q3bi
> **Circuit description (netlist form):** AC voltage source $V_s$ is connected in series with a $2\,\Omega$ resistor and a primary inductor $L_1 = 1\text{ mH}$ to a common bottom ground node. A secondary inductor $L_2 = 25\text{ mH}$ has mutual coupling coefficient $k=1$ with $L_1$. Both inductors have their dot polarity markings at their upper terminals and lower terminals tied to the common ground. A load resistor of $40\,\Omega$ is connected across $L_2$, with output voltage $V_o$ measured across it (+ at top, - at bottom).
> **Symbolic form:** not derivable from figure.
> 
> (ii) An electrical network is fed by two ac sources, as shown in Figure 3(b)(ii). Given that $Z_{1}=(1-j)\,\Omega$, $Z_{2}=(1+j)\,\Omega$ and $Z_{L}=(1+j0)\,\Omega$.
> Find the values of Thevenin voltage and impedance across terminals X and Y. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q3bii
> **Circuit description (netlist form):** A network with reference node Y and terminal node X. Left branch consists of an AC source $V_1 = 30\angle 45^\circ\text{ V}$ (+ top, - bottom at node Y) in series with impedance $Z_1 = (1-j)\,\Omega$ to node X. Right branch consists of an AC source $V_2 = 30\angle -45^\circ\text{ V}$ (+ top, - bottom at node Y) in series with impedance $Z_2 = (1+j)\,\Omega$ to node X. Load impedance $Z_L = (1+j0)\,\Omega$ is connected across terminals X and Y.
> **Symbolic form:** not derivable from figure.
> 
> (c) Find the Z transform of a discrete sequence $x[n]=n[u[n]-u[n-4]]$, where $u[n]$ is a unit step sequence. [10]

---

### [EE1-2020-Q4] 4-Point DFT of a Sampled Cosine Signal · D-Flip-Flop Sequential Circuit Design & First-Order Active Low-Pass Filter

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Sampling and recovery of signals DFT, FFT Processing of analog signals through discrete-time systems.
- **Directive:** Obtain
- **Theme (primary):** 4-Point DFT of a Sampled Cosine Signal
- **Theme (secondary):** D-Flip-Flop Sequential Circuit Design & First-Order Active Low-Pass Filter
- **Repeat cluster:** none
- **Has figure:** yes

> (a) A continuous-time signal $x(t)=\cos(2\pi\cdot 400t)$ is sampled with a sampling frequency $f_{s}=1600\text{ Hz}$. Obtain the 4-point DFT of the sampled sequence and plot the magnitude and phase spectrum. [20]
> 
> (b) Design a synchronous sequential circuit with D-flip-flops for a state diagram shown in Figure 4(b). [20]
> 
> **Figure ID:** FIG-EE1-2020-Q4b
> **Circuit description (netlist form):** State transition diagram with eight 3-bit states: 000, 001, 100, 111, 101, 010, 011, 110. The primary state cycle follows directional transitions: $000 \to 001 \to 100 \to 111 \to 101 \to 000$. Entry transitions are: state 010 transitions to 000, state 011 transitions to 100, and state 110 transitions to 101.
> **Symbolic form:** not derivable from figure.
> 
> (c) A first order low pass filter circuit is shown in Figure 4(c) below. It is desired that the dc gain of the filter be 5 and the input impedance is $10\text{ k}\Omega$. The value of the capacitor $C = 100\text{ nF}$. Find the values of R, $R_{1}$ and the cut-off frequency $f_{c}$ of the filter. (Assume ideal OP-AMP) [10]
> 
> **Figure ID:** FIG-EE1-2020-Q4c
> **Circuit description (netlist form):** Inverting operational amplifier first-order low-pass filter. Input voltage $V_i$ is connected through input resistor $R_1$ to the inverting input (-) of an ideal op-amp. Non-inverting input (+) is connected to ground. Feedback path between output node $V_o$ and inverting input (-) consists of a parallel combination of resistor $R$ and capacitor $C = 100\text{ nF}$.
> **Symbolic form:** $\frac{V_o(s)}{V_i(s)} = -\frac{R/R_1}{1 + sRC}$

---

## SECTION B

### [EE1-2020-Q5] DC Motor Speed Control via Fully-Controlled Bridge Converter · Displacement Current, Induction Motor Voltage Limits, VSB Filter Condition & AC Branch Currents

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** phase control rectifiers; bridge converters: fully-controlled and half-controlled;
- **Directive:** Calculate
- **Theme (primary):** DC Motor Speed Control via Fully-Controlled Bridge Converter
- **Theme (secondary):** Displacement Current, Induction Motor Voltage Limits, VSB Filter Condition & AC Branch Currents
- **Repeat cluster:** RC22 (Controlled Rectifier / Converter Circuits)
- **Has figure:** yes

> (a) A separately excited dc motor is controlled by varying its armature voltage using a single-phase fully-controlled converter bridge as shown in Figure 5(a). The field current is kept constant at rated value. The motor has an armature resistance of $0\cdot2\,\Omega$, and the motor voltage constant is $2\cdot5\text{ V/(rad/sec)}$. The motor is driving a mechanical load having a constant torque of 140 Nm.
> 
> **Figure ID:** FIG-EE1-2020-Q5a
> **Circuit description (netlist form):** A single-phase fully-controlled bridge rectifier consisting of four thyristors is fed by a 250 V rms, 50 Hz AC source. The DC output of the bridge is connected to a DC motor armature in series with armature resistance $R_a = 0.2\,\Omega$. The field winding with constant flux ($\phi = \text{constant}$) is excited separately from a DC source.
> **Symbolic form:** not derivable from figure.
> 
> For the firing angle of the converter being $60^{\circ}$ and assuming the armature current to be continuous and ripple free,
> (i) calculate the motor armature constant.
> (ii) evaluate the motor speed in rad/sec.
> (iii) calculate the rms value of the fundamental component of the input current to the bridge converter. [10]
> 
> (b) A parallel plate capacitor is made of circular discs of radius 0.1 m. The medium inside is air. The spacing between the two plates is 0.05 m. A voltage of $50\cos 10^{4}t\text{ volts}$ is applied between the two plates. Find the rms value of the displacement current flowing through the capacitor using Maxwell's equations.
> Also show that the rms value of the total capacitor current calculated from voltage equation is same as the displacement current.
> Assume permittivity of free space $\epsilon_{0}=\frac{1}{36\pi}\times10^{-9}\text{ F/m}$. [10]
> 
> (c) A three-phase 4-pole squirrel cage type induction motor develops maximum torque at 20 percent slip. The maximum to rated torque ratio of the motor is 2.8. If the input voltage fluctuates during its operation, find the minimum voltage as a percentage of full load voltage allowable to develop rated torque. Also find the developed torque as a percentage of full load torque at rated slip under this condition.
> Assume standstill rotor resistance of $1\cdot5\,\Omega$ per phase, negligible stator side impedance and linear magnetic circuit. [10]
> 
> (d) Vestigial sideband modulated wave is to be generated by passing a double sideband suppressed carrier wave through a filter.
> Show that the transfer function $H(f)$ of this filter must satisfy the condition $H(f-f_{c})+H(f+f_{c})=2H(f_{c})$, where $H(f_{c})$ is constant.
> Assume the message signal to be m(t). [10]
> 
> (e) Find the values of branch currents $I_{a}$, $I_{b}$ and $I_{c}$ as indicated in the circuit of Figure 5(e). [10]
> 
> **Figure ID:** FIG-EE1-2020-Q5e
> **Circuit description (netlist form):** An AC circuit with reference ground node 0. An independent AC current source of $10.6\angle 0^\circ\text{ A}$ is connected between node 0 and node 1 directed upwards. A $10\,\Omega$ resistor is connected between node 1 and node 0 carrying downward current $I_a$. A series combination of a $1\,\Omega$ resistor and an inductor with reactance $j2\,\Omega$ connects node 1 to node 2 carrying current $I_x$ to the right. A capacitor with reactance $-j5\,\Omega$ connects node 2 to node 0 carrying downward current $I_c$. A $5\,\Omega$ resistor connects node 2 to node 3 carrying current $I_b$ to the right into the positive terminal of a current-controlled voltage source of value $20I_x$, whose negative terminal connects to node 0.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2020-Q6] Distortionless Transmission Line: Frequency-Independent Attenuation and Velocity · Boost-Converter Ripple Analysis & FM Slope-Detector Demodulation

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Transmission lines travelling and standing waves, impedance matching, Smith chart.
- **Directive:** Explain
- **Theme (primary):** Distortionless Transmission Line: Frequency-Independent Attenuation and Velocity
- **Theme (secondary):** Boost-Converter Ripple Analysis & FM Slope-Detector Demodulation
- **Repeat cluster:** RC63 (Transmission Line Impedance/Reflection Parameters (Paper I))
- **Has figure:** yes

> (a) Under what conditions do the attenuation constant $\alpha$ and the velocity of propagation v, for a distortionless transmission line, become independent of the frequency simultaneously? Why is it not practical to have such a transmission line? [20]
> 
> (b) (i) Figure 6(b) shows a step-up dc-dc converter with ideal devices and elements. In its steady-state analysis the output filter capacitor is assumed to be very large to ensure a constant output voltage $v_{o}(t)\cong V_{o}$. The switch is turned on and off periodically with a frequency of $f_{s}$ and duty ratio of D. With the help of neat waveforms, find the expressions for peak-to-peak current ripple of inductor ($I_{L}$, peak) and output voltage ripple $(\Delta V_{0})$ at steady-state in terms of circuit parameters and variables.
> 
> **Figure ID:** FIG-EE1-2020-Q6b
> **Circuit description (netlist form):** Boost DC-DC converter circuit consisting of an input DC voltage source $V_d$ connected to node 1 (+ terminal). An inductor $L$ with voltage drop $v_L$ (+ left, - right) is connected between node 1 and node 2. A controllable switch S is connected between node 2 and ground node 0. A diode has its anode connected to node 2 and cathode connected to node 3. A filter capacitor $C$ and a load resistor $R$ are connected in parallel between output node 3 and ground node 0, with output voltage $V_o$ across the load.
> **Symbolic form:** not derivable from figure.
> 
> (ii) In a step-up dc-dc converter shown in Figure 6(b), $V_{d}=12\text{ V}$, $V_{o}=24\text{ V}$, $I_{0}=0\cdot5\text{ A}$, $L=150\,\mu\text{H}$, $C=470\,\mu\text{F}$, and $f_{s}=20\text{ kHz}$. Calculate peak-to-peak output voltage ripple $(\Delta V_{0})$ and the rms value of the ripple in diode current (which also flows through the capacitor). [20]
> 
> (c) Shown below is the frequency response of an ideal slope circuit.
> 
> **Figure ID:** FIG-EE1-2020-Q6c
> **Circuit description (netlist form):** Frequency response curve of an ideal slope circuit showing $H_1(f)/j$ versus frequency $f$. For the positive frequency band from $f_c - B_T/2$ to $f_c + B_T/2$, the response is a linear ramp starting from zero with slope equal to $2\pi a$. For the negative frequency band from $-f_c - B_T/2$ to $-f_c + B_T/2$, the response is an odd-symmetric linear ramp starting at a negative value and reaching zero.
> **Symbolic form:** not derivable from figure.
> 
> How can it be used to demodulate an FM signal
> $s(t)=A_{c}\cos\left[2\pi f_{c}t+2\pi k_{f}\int_{0}^{t}m(t)dt\right]$
> with a transmission bandwidth $B_T$, in combination with an envelope detector? [10]

---

### [EE1-2020-Q7] Salient-Pole Alternator Maximum Power and Load Angle · FM Delay-Line Demodulator Analysis & Plane-Wave Dielectric Slab Reflection

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
- **Directive:** Find
- **Theme (primary):** Salient-Pole Alternator Maximum Power and Load Angle
- **Theme (secondary):** FM Delay-Line Demodulator Analysis & Plane-Wave Dielectric Slab Reflection
- **Repeat cluster:** RC26 (AC Machine Performance (Induction & Synchronous))
- **Has figure:** yes

> (a) A 220 V, 50 Hz, 3-phase star-connected salient pole alternator has six poles. With a field current of 2.4 A, it produces rated terminal voltage on open circuit condition. On short circuit, it requires 0.8 A field current to produce an armature current of 27.0 A. The alternator has $X_{d}$ to $X_{q}$ ratio of 1.5. It is connected to bus bars of 220 V line-to-line and its excitation required under this condition is 250 V.
> (i) Find the maximum power that the alternator can deliver and the corresponding load angle with the excitation remaining unchanged.
> (ii) Also find the maximum power that the alternator can deliver if a sudden loss of excitation occurs during the synchronised condition.
> Assume linear magnetic circuit. [20]
> 
> (b) Consider the frequency demodulation scheme shown in Figure 7(b) below:
> 
> **Figure ID:** FIG-EE1-2020-Q7b
> **Circuit description (netlist form):** Block diagram of an FM demodulator. An incoming FM wave $s(t)$ splits into two branches: one connects to the non-inverting (+) input of a summing junction, while the other passes through a Delay line block producing delay $T$, which connects to the inverting (-) input of the summing junction. The output of the summing junction is fed into an Envelope detector block, producing output signal $a(t)$.
> **Symbolic form:** not derivable from figure.
> 
> Here, the incoming FM wave $s(t)$ is passed through a delay line that produces a phase shift of $\frac{\pi}{2}$ radians at the carrier frequency $f_{c}$. The delay line output is subtracted from the incoming FM wave and the resulting composite wave is then envelope detected. Assuming that
> $s(t)=A_{c}\cos[2\pi f_{c}t+\beta\sin(2\pi f_{m}t)]$
> analyse the operation of this demodulator when the modulation index $\beta$ is less than unity and the delay T produced by the delay line is sufficiently small to justify the approximation $\cos(2\pi f_{m}T)\approx1$ and $\sin(2\pi f_{m}T)\approx2\pi f_{m}T$. [20]
> 
> (c) A uniform plane wave travelling in air is having an electric field of 50 V/m and is normally incident on an infinitely thick slab of dielectric constant 10. Find the electric and magnetic fields just inside the slab surface.
> Also find the penetrated power inside the slab and the reflected electric and magnetic fields from the slab surface.
> Assume $\mu_{0}=4\pi\times10^{-7}\text{ H/m}$ and $\epsilon_{0}=\frac{1}{36\pi}\times10^{-9}\text{ F/m}$. [20]

---

### [EE1-2020-Q8] SCR Minimum Trigger Pulse Width for Turn-ON · VFD Induction Motor V/f Control, Miss-Distance PDF & Transformer Efficiency at Changed Frequency

- **Exam:** UPSC Mains 2020 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Semi-conductor power devices diode, transistor, thyristor, triac, GTO and MOSFET-static characteristics and principles of operation; triggering circuits;
- **Directive:** Find
- **Theme (primary):** SCR Minimum Trigger Pulse Width for Turn-ON
- **Theme (secondary):** VFD Induction Motor V/f Control, Miss-Distance PDF & Transformer Efficiency at Changed Frequency
- **Repeat cluster:** none
- **Has figure:** yes

> (a) (i) An SCR having a turn ON time of $5\,\mu\text{sec}$, latching current of 50 mA and holding current of 40 mA is triggered by a short duration pulse and is used in the circuit shown in Figure 8(a)(i). Find the minimum pulse width required to turn the SCR ON. [10]
> 
> **Figure ID:** FIG-EE1-2020-Q8ai
> **Circuit description (netlist form):** A 100 V DC source connects between ground node 0 (-) and node 1 (+). An SCR has its anode at node 1 and cathode at node 2. Connected in parallel between node 2 and node 0 are two load branches: the first contains a series combination of a $20\,\Omega$ resistor and a $0.5\text{ H}$ inductor; the second contains a $5\text{ k}\Omega$ resistor.
> **Symbolic form:** not derivable from figure.
> 
> (ii) A 3-phase, delta-connected, 6-pole, 50 Hz, 400 V, 925 rpm, squirrel cage induction motor has the following parameters:
> $R_{s}=0\cdot2\,\Omega$, $R_{r}^{\prime}=0\cdot3\,\Omega$, $X_{s}=0\cdot5\,\Omega$, $X_{r}^{\prime}=1\,\Omega$
> The motor is fed from a voltage source inverter with constant V/f ratio below 50 Hz and constant voltage of 400 V above 50 Hz frequency. Calculate:
> (1) Speed for the frequency of 35 Hz and half of full-load torque,
> (2) Frequency for a speed of 600 rpm and 80% of full-load torque and
> (3) Torque for a frequency of 35 Hz and speed of 650 rpm.
> Assume motor speed torque curves to be parallel straight lines in the region of interest. [20]
> 
> (b) (i) Which type of probability density function is applicable in case of calculating errors with aiming of missiles/projectiles, if errors in each of the two rectangular coordinates have independent Gaussian probability density functions?
> Find its mean, mean square value, variance and its cumulative distribution function.
> 
> (ii) Suppose an archer shoots at a target, 3 m in diameter for which the bull's eye is centered on the origin of an XY coordinate system. The position at which any arrow strikes the target is a random variable having an X-component and a Y-component. It is determined that the standard deviation of these components is $\frac{1}{6}\text{ m}$, i.e. $\sigma_{x}=\sigma_{y}=\frac{1}{6}$.
> Assume that the X and Y components of the hit position are independent Gaussian random variables. What is the type of random variable that can be assigned to the distance of origin from the hit position (i.e. the miss distance)? Write its probability density function and find the mean value, its standard deviation and the probability that the target will be missed completely. [20]
> 
> (c) A 150 KVA, 11 KV/415 V, 50 Hz single-phase transformer has maximum possible efficiency of 98.5% at 50 Hz, 125 KVA, 0.8 lag p.f. load. Its hysteresis and eddy current loss components are also same under this condition. Find the transformer efficiency at rated KVA and unity power factor load with its supply frequency changed to 40 Hz at unchanged input voltage.
> Assume Steinmetz constant $x=1\cdot6$ for the transformer core. [10]

---
