## SECTION-A

### [EE1-2017-Q1] Thevenin's Theorem and Superposition Verification · Signal Transformation Sketches, Distortionless-Line Constants, Diode Clipper & Induction Motor Performance

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Find
- **Theme (primary):** Thevenin's Theorem and Superposition Verification
- **Theme (secondary):** Signal Transformation Sketches, Distortionless-Line Constants, Diode Clipper & Induction Motor Performance
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh/Delta-Y))
- **Has figure:** yes

> 1. (a) For the circuit shown in Fig. 1(a), find the current through $5\ \Omega$ resistor by using Thevenin's theorem and verify the same by using superposition theorem. [10]
>
> **Figure ID:** FIG-EE1-2017-Q1a
> **Circuit description (netlist form):** Planar DC circuit with nodes A, B, C, and D. A $5\ \Omega$ resistor connects node A to node B. Connected in parallel between node A and node D are three branches: an independent DC voltage source $E_1 = 100\text{ V}$ (positive terminal at node A, negative at node D), a $20\ \Omega$ resistor, and a series branch of an independent DC voltage source $E_2 = 40\text{ V}$ (positive terminal at node A) in series with a $6\ \Omega$ resistor to node D. Connected between node D and node C is an independent DC voltage source $E_3 = 20\text{ V}$ (positive terminal at node D, negative at node C) in series with a $10\ \Omega$ resistor to node C. Connected in parallel between node B and node C are three branches: a series branch of an independent DC voltage source $E_4 = 20\text{ V}$ (negative terminal at node B, positive at bottom) in series with a $7\ \Omega$ resistor to node C, an independent DC voltage source $E_5 = 50\text{ V}$ (positive terminal at node B, negative at node C), and a series branch of an independent DC voltage source $E_6 = 30\text{ V}$ (negative terminal at node B, positive at bottom) in series with a $4\ \Omega$ resistor to node C.
> **Symbolic form:** not derivable from figure.
>
> (b) A continuous time signal $x(t)$ is shown in Fig. 1(b). Sketch and label each of the following signals:
> (i) $x(t)u(2-t)$
> (ii) $x(t)\delta(t-\frac{7}{2})$ [10]
>
> **Figure ID:** FIG-EE1-2017-Q1b
> **Circuit description (netlist form):** Plot of a continuous-time signal $x(t)$ versus time $t$. The signal is zero for $t < -2$; increases linearly from $0$ at $t = -2$ to $1$ at $t = 0$; holds a constant value of $1$ for $0 \le t < 2$; undergoes a step jump to $2$ at $t = 2$; remains constant at $2$ for $2 \le t \le 4$; and drops to zero for $t > 4$.
> **Symbolic form:** $x(t) = (0.5t + 1)[u(t+2) - u(t)] + [u(t) - u(t-2)] + 2[u(t-2) - u(t-4)]$
>
> (c) Show that for a distortionless transmission line, the attenuation constant $\alpha$ does not depend on frequency, whereas the phase constant $\beta$ depends linearly on it. [10]
>
> (d) For the circuit given in Fig. 1(d)—
> (i) draw the input and output waveforms;
> (ii) find the average value of the output voltage waveform.
> Assume that the diode in the circuit is ideal. [10]
>
> **Figure ID:** FIG-EE1-2017-Q1d
> **Circuit description (netlist form):** Operational amplifier circuit powered by $+15\text{ V}$ and $-15\text{ V}$ supplies. The non-inverting input terminal ($+$) is connected via a $660\ \Omega$ resistor to an AC voltage source $v(s) = \sin\omega t$ with $\omega = 2\times 50\times \pi\text{ rad/s}$, referenced to ground. The inverting input terminal ($-$) is connected to the output node $V_o$ through a $2\text{ k}\Omega$ feedback resistor. The inverting input terminal ($-$) is also connected to ground through the series combination of an ideal diode (cathode at inverting input terminal, anode connected to a $1\text{ k}\Omega$ resistor) and the $1\text{ k}\Omega$ resistor to ground.
> **Symbolic form:** not derivable from figure.
>
> (e) A 15-hp, 220-V, 3-phase, 50-Hz, 6-pole, Y-connected induction motor has the following parameters per phase:
> $r_{1}=0\cdot128\ \Omega$, $r_{2}^{\prime}=0\cdot0935\ \Omega$, $(x_{1}+x_{2}^{\prime})=0\cdot496\ \Omega$, $r_{c}=183\ \Omega$, $x_{\phi}=8\ \Omega$
> The rotational losses are equal to the stator core losses (hysteresis and eddy-current). For a slip of 3%, find the line current and power factor. [10]

---

### [EE1-2017-Q2] Prime Implicants and Minimal NAND Realization of a Boolean Function · Electrical Length of a Transmission Line & Normal-Distribution PDF Properties

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS).
- **Directive:** Find
- **Theme (primary):** Prime Implicants and Minimal NAND Realization of a Boolean Function
- **Theme (secondary):** Electrical Length of a Transmission Line & Normal-Distribution PDF Properties
- **Repeat cluster:** RC17 (Digital IC Families & Number Systems)
- **Has figure:** no

> 2. (a) For the Boolean function
> $F(W,X,Y,Z)=\Sigma(0,2,5,6,7,8,10,13)$
> (i) find all the prime implicants;
> (ii) give minimal representation;
> (iii) find minimal two-level realization using NAND gates only. [20]
>
> (b) (i) What is meant by an infinite transmission line? Also, explain the term 'electrical length' of a transmission line. In what units is it measured?
> (ii) Determine the electrical length of a 20 m long transmission line operating at 1 MHz, if $u=0\cdot7c$ on the line. Take $c=3\times10^{8}\text{ m/s}$. [20]
>
> (c) Discuss the properties of a probability density function. What additional features a normal distribution has? [10]

---

### [EE1-2017-Q3] Transformer Performance from O.C./S.C. Test Data · 3-Phase Diode Rectifier Performance Measures & R-L-C Switching Transient

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers.
- **Directive:** Determine
- **Theme (primary):** Transformer Performance from O.C./S.C. Test Data
- **Theme (secondary):** 3-Phase Diode Rectifier Performance Measures & R-L-C Switching Transient
- **Repeat cluster:** RC20 (Transformer Performance & Testing)
- **Has figure:** yes

> 3. (a) The following test data were taken on a 30-kVA, 2400/240 V, 50-Hz, single-phase transformer:
> Open-circuit test: $V=2400\text{ V}$, $I=0\cdot3\text{ A}$, $P=230\text{ W}$
> Short-circuit test: $V=70\text{ V}$, $I=18\cdot8\text{ A}$, $P=1050\text{ W}$
> Determine the primary voltage, real and reactive power input, and efficiency, when a current of 12.5 A at 240 V is drawn from the low-voltage side by a load of 0.8 p.f. lagging. [20]
>
> (b) A three-phase uncontrolled diode rectifier supplies a constant load current of 10 A and its supply voltage is 400 V line-to-line. Determine the following performance measures:
> (i) Average output voltage
> (ii) Supply r.m.s. current
> (iii) Supply fundamental r.m.s. current
> (iv) Supply 3rd, 5th, 7th and 9th harmonic r.m.s. current
> (v) Supply current displacement factor
> (vi) Supply power factor
> (vii) AC power (supply power)
> (viii) DC power (load power) [20]
>
> (c) Consider the R-L-C circuit shown in Fig. 3(c), wherein
> $I_{S}=10\text{ A}$, $R=2\ \Omega$, $L=1\text{ H}$, $C=0\cdot5\ \mu\text{F}$, $i_{L}(0^{-})=0$
> Determine $v(0^{+})$, $\frac{dv}{dt}(0^{+})$ and $\frac{d^{2}v}{dt^{2}}(0^{+})$ after the switch is closed. [10]
>
> **Figure ID:** FIG-EE1-2017-Q3c
> **Circuit description (netlist form):** An independent DC current source $I_S = 10\text{ A}$ is connected across a series switch that closes at $t = 0$ in the top wire. Downstream of the switch, three parallel branches connect between the upper rail and the lower reference rail: a resistor $R = 2\ \Omega$ with downward current $i_R$, an inductor $L = 1\text{ H}$ with downward current $i_L$, and a capacitor $C = 0.5\ \mu\text{F}$ with downward current $i_C$. The voltage across the parallel combination is denoted $v$ with positive polarity at the upper rail. Initial current in the inductor is $i_L(0^-) = 0$.
> **Symbolic form:** $I_S u(t) = \frac{v(t)}{R} + \frac{1}{L}\int_{-\infty}^{t} v(\tau)\,d\tau + C\frac{dv(t)}{dt}$

---

### [EE1-2017-Q4] SSB vs DSB-SC Modulation Comparison · Laplace Transform of a Rectified Sinusoid & Zener-Clipped Op-Amp Output

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Linear CW modulation: Amplitude modulation : DSB, DSB-SC and SSB. Modulators and Demodulators;
- **Directive:** Explain and differentiate
- **Theme (primary):** SSB vs DSB-SC Modulation Comparison
- **Theme (secondary):** Laplace Transform of a Rectified Sinusoid & Zener-Clipped Op-Amp Output
- **Repeat cluster:** RC27 (Amplitude Modulation Analysis)
- **Has figure:** yes

> 4. (a) Explain and differentiate between the single sideband (SSB) modulation and double sideband suppressed carrier (DSB-SC) modulation. Show the DSB-SC modulated waveform for any chosen baseband signal waveform and spectrum of the baseband and the DSB-SC modulated wave. [20]
>
> (b) Find the Laplace transform of the function $f(t)=u(\sin 2t)$. [20]
>
> (c) Find the average voltage at the point $V_{0}$ in the circuit given in Fig. 4(c): [10]
>
> **Figure ID:** FIG-EE1-2017-Q4c
> **Circuit description (netlist form):** Operational amplifier circuit powered by $+15\text{ V}$ and $-15\text{ V}$ rails. The inverting input terminal ($-$) is connected through a $1\text{ k}\Omega$ resistor to an AC voltage source $v(t) = 5\sin\omega t$ with $\omega = 2\times \pi\times 50\text{ rad/s}$ referenced to ground. The non-inverting input terminal ($+$) is connected to ground through a Zener diode (cathode at the non-inverting terminal, anode at ground) with Zener voltage $V_Z = 2\cdot5\text{ V}$ and forward voltage drop $V_{FZ} = 0\text{ V}$. The non-inverting terminal ($+$) is also connected to the output node $V_o$ through a $1\text{ k}\Omega$ feedback resistor.
> **Symbolic form:** not derivable from figure.

---

## SECTION-B

### [EE1-2017-Q5] Boolean Algebra Identity Proof · Power-Factor Correction, Boost Converter Duty Cycle, AM Modulation Factor & Two-Port Z-Parameters

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS).
- **Directive:** Prove
- **Theme (primary):** Boolean Algebra Identity Proof
- **Theme (secondary):** Power-Factor Correction, Boost Converter Duty Cycle, AM Modulation Factor & Two-Port Z-Parameters
- **Repeat cluster:** RC17 (Digital IC Families & Number Systems)
- **Has figure:** no

> 5. (a) Prove that $\overline{A}B+\overline{B}C+\overline{A}C=\overline{A}B+\overline{B}C$. [10]
>
> (b) An industrial consumer is operating a 1 kW induction motor at a lagging power factor of 0.8 and at a source voltage of 200 V r.m.s. In order to reduce expenditure on power consumption, he wishes to raise the power factor to 0.95 lagging by connecting a circuit element in parallel with the load. Indicate the type of the circuit element (inductive or capacitive) and find the value if the operating frequency is 50 Hz. [10]
>
> (c) (i) Explain the operation of Boost converter with voltage and current waveforms across the Boost inductor. Assume continuous conduction.
> (ii) Derive its output voltage equation in terms of duty cycle and input voltage. [10]
>
> (d) An amplitude modulated signal, viewed on an oscilloscope, has a crest voltage of 44 V peak-to-peak. The bottom (or trough) point of the wave measures 6 V peak-to-peak. Find the modulation factor, percentage modulation and peak-to-peak unmodulated carrier voltage. [10]
>
> (e) Obtain z-parameters of a two-port network in terms of its ABCD parameters. [10]

---

### [EE1-2017-Q6] Single-Phase Bridge Rectifier Average and RMS Current · Discrete-Time System Transfer Function & Wien Bridge Oscillator Design

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** phase control rectifiers; bridge converters: fully-controlled and half-controlled;
- **Directive:** Find
- **Theme (primary):** Single-Phase Bridge Rectifier Average and RMS Current
- **Theme (secondary):** Discrete-Time System Transfer Function & Wien Bridge Oscillator Design
- **Repeat cluster:** RC22 (Controlled Rectifier / Converter Circuits)
- **Has figure:** yes

> 6. (a) (i) Find the value of average current flow through the load resistor for the circuit given in Fig. 6(a).
> (ii) Find the value of r.m.s. current drawn from the source. [20]
>
> **Figure ID:** FIG-EE1-2017-Q6a
> **Circuit description (netlist form):** Single-phase bridge rectifier fed by an AC voltage source $v(t) = 320\sin\omega t$ with $\omega = 2\times\pi\times 50\text{ rad/s}$. The bridge is composed of four diodes $D_1, D_2, D_3, D_4$. Cathodes of $D_1$ and $D_2$ connect to the top DC rail; anodes of $D_3$ and $D_4$ connect to the bottom DC rail. Source terminal 1 connects to the junction between $D_1$ anode and $D_3$ cathode. Source terminal 2 connects to the junction between $D_2$ anode and $D_4$ cathode. Across the top and bottom DC rails is connected a branch with a $320\text{ k}\Omega$ resistor in series with a $160\text{ V}$ DC source (positive terminal toward the resistor, negative terminal connected to the bottom rail).
> **Symbolic form:** not derivable from figure.
>
> (b) Determine the transfer function and therefrom the impulse response of the causal linear time invariant system described by the difference equation
> $y[n]-\frac{1}{4}y[n-1]-\frac{3}{8}y[n-2]=-x[n]+2x[n-1]$ [20]
>
> (c) (i) Draw the circuit diagram of Wien bridge oscillator using OP-AMP.
> (ii) Find the value of R to get a sustained oscillation of 1115 Hz. Assume that the value of the capacitor is $0\cdot1\ \mu\text{F}$. [10]

---

### [EE1-2017-Q7] EM Field Phasor Representation Satisfying Maxwell's Equations · Mod-7 JK Flip-Flop Counter & DC Series Motor Speed/Torque

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves.
- **Directive:** Determine
- **Theme (primary):** EM Field Phasor Representation Satisfying Maxwell's Equations
- **Theme (secondary):** Mod-7 JK Flip-Flop Counter & DC Series Motor Speed/Torque
- **Repeat cluster:** RC18 (Electromagnetic Field Theory (Maxwell's Equations & Poynting Theorem))
- **Has figure:** no

> 7. (a) The electric field and magnetic field in free space are given by
> $E=\frac{100}{\rho}\cos(2\times10^{7}t+\beta z)\hat{a}_{\phi}\text{ V/m}$
> $H=\frac{H_{0}}{\rho}\cos(2\times10^{7}t+\beta z)\hat{a}_{\rho}\text{ A/m}$
> Express these fields in phasor form and determine the constants $H_{0}$ and $\beta$ such that these fields satisfy Maxwell's equations. The permeability and permittivity of the free space are $4\pi\times10^{-7}\text{ H/m}$ and $8\cdot854\times10^{-12}\text{ F/m}$ respectively. [20]
>
> (b) Find the state transition diagram and realization using J-K flip-flops to count Mod 7 in the following sequence:
> 000, 001, 011, 100, 101, 111 [20]
>
> (c) A 230-V, 10-hp DC series motor draws a line current of 36 A, when delivering rated power at its rated speed of 1200 r.p.m. The armature circuit resistance is $0\cdot2\ \Omega$ and the series field winding resistance is $0\cdot1\ \Omega$. The magnetization curve may be considered linear.
> (i) Find the speed of this motor when it draws a line current of 20 A.
> (ii) What is the developed torque at the new condition? [10]

---

### [EE1-2017-Q8] Unbalanced Delta-Connected Load: Line Currents and Power · Op-Amp Bandpass Filter Design & Stationary vs Non-Stationary Random Processes

- **Exam:** UPSC Mains 2017 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Determine
- **Theme (primary):** Unbalanced Delta-Connected Load: Line Currents and Power
- **Theme (secondary):** Op-Amp Bandpass Filter Design & Stationary vs Non-Stationary Random Processes
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** no

> 8. (a) A 400-V, 3-phase balanced source is connected to an unbalanced $\Delta$-connected load of impedances $\overline{Z}_{ab}=10\angle+45^{\circ}\ \Omega$, $\overline{Z}_{bc}=10\angle0^{\circ}\ \Omega$ and $\overline{Z}_{ca}=10\angle-45^{\circ}\ \Omega$. Determine the line currents (in phasor form), total active (real) and reactive powers. [20]
>
> (b) (i) Draw the circuit diagram of a bandpass filter using OP-AMP. Its parameters are $f_{L}=300\text{ Hz}$, $f_{H}=2\text{ kHz}$ and passband gain is 4.
> (ii) Calculate the value of Q. Assume that the capacitor value is $0\cdot01\ \mu\text{F}$. [20]
>
> (c) Differentiate between stationary and non-stationary random processes. Give the properties of the first and second-order distribution function of stationary random processes. [10]

---
