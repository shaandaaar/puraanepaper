## Section-A

### [EE1-2010-Q1] Network Time Constants & 3-Phase Circuit Analysis · BJT Bias Stability, TTL Gates, Rectifiers, Induction Motor & Transmission-Line Noise

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Determine
- **Theme (primary):** Network Time Constants & 3-Phase Circuit Analysis
- **Theme (secondary):** BJT Bias Stability, TTL Gates, Rectifiers, Induction Motor & Transmission-Line Noise
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> 1.
> (a) (i) Determine the time constant for the network shown in Fig. 1: [5]
> 
> **Figure ID:** FIG-EE1-2010-Q1a(i)
> **Circuit description (netlist form):** A DC voltage source of $10\text{ V}$ connected between node 1 and ground (node 0). Switch S connected between node 1 and node 2. Resistor of value $R$ connected between node 2 and node 3. In parallel across node 3 and node 0 are a resistor of value $2R$ and a capacitor of value $C$.
> **Symbolic form:** $\tau = \frac{2}{3}RC$
> 
> (ii) For a 3-phase, 400 V, 50 Hz, acb system, write the voltages $v_{ac}$ and $v_{bn}$ in instantaneous form, assuming $V_{bc}$ as a reference phasor. [5]
> 
> (iii) The discrete time system is described by $y(n)=x(n)+nwx(n-1)$. Check whether this system is causal/time variant. [5]
> 
> (b) (i) For the circuit shown in Fig. 2—
> 1. determine the operating point;
> 2. find the stability factor.
> Given : $V_{BE}=0.6\text{ V}$, $\beta=50$.
> 
> **Figure ID:** FIG-EE1-2010-Q1b(i)
> **Circuit description (netlist form):** An NPN BJT circuit with voltage divider bias supplied by $V_{CC}=15\text{ V}$. Resistor $39\text{ k}\Omega$ connected between $V_{CC}$ and the base node. Resistor $4.7\text{ k}\Omega$ connected between base and ground. Collector resistor $4.7\text{ k}\Omega$ connected between $V_{CC}$ and the collector node. Emitter resistor $1\text{ k}\Omega$ connected between emitter and ground. Input terminals are across base and ground; output terminals are across collector and ground. Transistor has $\beta=50$.
> **Symbolic form:** not derivable from figure.
> 
> [$6+4=10$]
> 
> (ii) Draw the circuit of TTL NAND gate and explain its operation. [5]
> 
> (c) (i) Draw a circuit diagram for a single-phase, full-wave, midpoint diode rectifier. Sketch waveforms for source voltage, load voltage, voltage across one diode and source current. Take turns ratio from each secondary to primary as unity. Derive expressions for average and r.m.s. output voltages. [10]
> 
> (ii) Why is the air-gap length in a 3-phase induction motor kept as small as is mechanically possible? [5]
> 
> (d) (i) Determine the primary constants of a 50-ohm lossless line at 100 MHz, if it has a phase constant of 3·14 rad/m. Sketch its $\pi$-type equivalent circuit. Is this distortionless line? [5]
> 
> (ii) Determine the power density spectrum of the noise voltage across the terminals $aa'$ of the circuit shown in Fig. 3: [10]
> 
> **Figure ID:** FIG-EE1-2010-Q1d(ii)
> **Circuit description (netlist form):** A one-port passive network connected between top terminal $a$ and bottom terminal $a'$. Three parallel branches connect terminal $a$ to terminal $a'$: branch 1 is a series combination of a $1\ \Omega$ resistor and a $1\text{ H}$ inductor; branch 2 is a $1\text{ F}$ capacitor; branch 3 is a series combination of a $2\ \Omega$ resistor and a $1\text{ F}$ capacitor.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2010-Q2] Thevenin's Theorem & Discrete Convolution · Cascode Amplifiers, Feedback, Counters & Controlled Rectifiers

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Find
- **Theme (primary):** Thevenin's Theorem & Discrete Convolution
- **Theme (secondary):** Cascode Amplifiers, Feedback, Counters & Controlled Rectifiers
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh))
- **Has figure:** yes

> 2.
> (a) (i) Use Thevenin's theorem to find the current in $4\,\Omega$ branch of the network given in Fig. 4: [10]
> 
> **Figure ID:** FIG-EE1-2010-Q2a(i)
> **Circuit description (netlist form):** A circuit with a common bottom reference rail. A $12\text{ V}$ DC source (positive terminal up) connected in series with a $5\ \Omega$ resistor carrying current $I_1$ to node 2. An independent current source of $12\text{ A}$ connected from the reference rail into node 2. A dependent voltage source $10I_1$ connected with positive terminal at node 2 and negative terminal at node 3. In series between node 3 and the reference rail are a $4\ \Omega$ resistor, a $1\ \Omega$ resistor, and a $20\text{ V}$ DC source (positive terminal pointing upward toward the $1\ \Omega$ resistor).
> **Symbolic form:** not derivable from figure.
> 
> (ii) Obtain the convolution sum $y(n)=x(n)*h(n)$ for $n=2$, using the property $x(n)*\delta(n-n_{0})=x(n-n_{0})$. Assume $x(n)=\left(\frac{1}{2}\right)^{n}u(n)$, $h(n)=\left(\frac{1}{3}\right)^{n}u(n)$. [10]
> 
> (b) (i) Draw the circuit of a Cascode amplifier. Indicate the two configurations of transistors used. Why is this circuit preferred in high-frequency applications? [6]
> 
> (ii) For the voltage series feedback amplifier shown in Fig. 5, calculate $V_{f}$, feedback ratio $\beta$, voltage gain without feedback $A_{V}$ and voltage gain with feedback $A_{V_{f}}$: [6]
> 
> **Figure ID:** FIG-EE1-2010-Q2b(ii)
> **Circuit description (netlist form):** A voltage-series feedback amplifier block diagram. The basic amplifier block has gain $A_V$, differential input terminals with input voltage $5\text{ mV}$ ($+$ on top), and output terminals supplying load voltage $V_o = 2\text{ V}$. Input voltage source $V_s$ is connected in series with the feedback voltage $V_f$ across the amplifier input terminals. A resistive divider inside a dashed box consists of a $19\text{ k}\Omega$ series resistor from the top output rail and a $1\text{ k}\Omega$ shunt resistor connected across the feedback port developing $V_f$.
> **Symbolic form:** $V_{f} = V_{o}\left(\frac{1\text{ k}\Omega}{19\text{ k}\Omega + 1\text{ k}\Omega}\right) = \frac{V_o}{20}$
> 
> (iii) Design a decade counter using JK FF's (MOD-10 counter) and draw the timing diagrams. [8]
> 
> (c) (i) A d.c. battery having a constant e.m.f. $E$ is charged through a 1-phase full converter. A resistor $R$ limits the battery charging current. Single-phase source voltage is $V_{m}\sin\omega t$. Sketch waveforms for source voltage, output voltage and charging current. Derive an expression for the average charging current on the assumption that each pair of thyristors is fired continuously in each half-cycle. Take $V_{r}$ as the voltage drop in each conducting pair. [16]
> 
> (ii) In part (i) above, find the value of $R$ in case battery charging current is 5 A, supply voltage is 40 V, 50 Hz; $E=12\text{ V}$ and $V_{r}=1\text{ V}$. [4]

---

### [EE1-2010-Q3] Darlington Amplifier & Binary-to-Gray Conversion · Induction Motor Frequency Variation, EM Wave Polarization & SSB Detection

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits.
- **Directive:** Draw
- **Theme (primary):** Darlington Amplifier & Binary-to-Gray Conversion
- **Theme (secondary):** Induction Motor Frequency Variation, EM Wave Polarization & SSB Detection
- **Repeat cluster:** none
- **Has figure:** no

> 3.
> (a) (i) Draw the circuit of Darlington emitter follower. Obtain the expressions for overall current gain and input impedance. You can use suitable approximations. Find the above two quantities if $R_{B}=2\text{ M}\Omega$, $R_{E}=1\text{ k}\Omega$. The device parameters are identical.
> $h_{fe_{1}}=h_{fe_{2}}=50$
> $h_{ie_{1}}=h_{ie_{2}}=1\text{ K}$
> $h_{oe_{1}}=h_{oe_{2}}=20\ \mu\text{A/V}$
> [$6+4=10$]
> 
> (ii) Design a binary to Gray code converter. [10]
> 
> (b) (i) Draw the exact equivalent circuit of a three-phase induction motor. Write clearly what the various parameters represent. [10]
> 
> (ii) A three-phase, 400 V, 20 kW, 1440 r.p.m., 50 Hz, star-connected induction motor has rotor leakage impedance of $(0.4+j1\cdot6)\,\Omega$ per phase. Stator leakage impedance and rotational losses are assumed negligible. If this motor is energized from 120 Hz, 400 V, three-phase source, then calculate—
> 1. the motor speed at rated load torque;
> 2. the slip at which maximum torque occurs. [10]
> 
> (c) (i) A plane wave has
> $\overline{E}=E_{0}\cos(\omega t-\beta x)\hat{y}$
> and
> $\overline{H}=\frac{E_{0}}{\eta}\cos(\omega t-\beta x)\hat{z}$
> in free space, satisfying Maxwell's equations. Find the general expressions for phase constant $\beta$ and intrinsic impedance $\eta$, in terms of medium parameters. Hence, calculate their values at 10 MHz. Identify the direction of propagation and type of polarization. [10]
> 
> (ii) A message signal $m(t)$ containing the frequency components 100 Hz, 200 Hz and 400 Hz is applied to an SSB modulator together with a carrier at 100 kHz with only USB retained. The coherent detector employed at the receiver uses a local oscillator that gives a sine wave of frequency 100·02 kHz.
> 1. Determine the frequency components of detector output.
> 2. Determine the frequency components of detector output if only LSB is transmitted. [10]

---

### [EE1-2010-Q4] Resonant Circuits & Coupled Coil Analysis · Induction Motor V/f Control, Transmission-Line VSWR & Angle Modulation

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Determine
- **Theme (primary):** Resonant Circuits & Coupled Coil Analysis
- **Theme (secondary):** Induction Motor V/f Control, Transmission-Line VSWR & Angle Modulation
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> 4.
> (a) (i) Determine the resonant frequency of the following circuit (Fig. 6) : [6]
> 
> **Figure ID:** FIG-EE1-2010-Q4a(i)
> **Circuit description (netlist form):** An AC voltage source connected in series with a $10\ \Omega$ resistor. The combination is connected across a parallel network consisting of two branches: upper branch has a $4\text{ H}$ inductor in series with a $1\text{ F}$ capacitor; lower parallel branch has a $1\text{ F}$ capacitor.
> **Symbolic form:** not derivable from figure.
> 
> (ii) The applied a.c. voltage and the resulting current in the following circuit (Fig. 7) are in phase. Determine the coefficient of coupling and the dot polarity of coil PQ : [4]
> 
> **Figure ID:** FIG-EE1-2010-Q4a(ii)
> **Circuit description (netlist form):** A single-loop AC circuit consisting of a sinusoidal voltage source in series with a capacitive reactance $-j12\ \Omega$, a resistance of $10\ \Omega$, a first inductor of reactance $j8\ \Omega$ with a polarity dot on its left terminal, and a second inductor of reactance $j2\ \Omega$ connected between terminals P and Q, with mutual coupling coefficient $K$ indicated between the two inductors.
> **Symbolic form:** not derivable from figure.
> 
> (iii) The input ($x$)-output ($y$) relationship for the system is given by
> $y(n+2)+3y(n+1)+2y(n)=x(n)$
> $y(0)=1$ and $y(n)=0$ for $n<0$
> Determine $y(n)$ for unit step sequence input. [10]
> 
> (b) (i) Discuss how volts/hertz control for a three-phase induction motor is similar to armature-voltage control of a d.c. motor. [8]
> 
> (ii) A 10 kW, 50 Hz, 6-pole polyphase induction motor has a full-load slip of 0·04. If its friction and windage losses are 4% of the output, then compute—
> 1. rotor ohmic loss at full load;
> 2. full-load electromagnetic torque;
> 3. rotor efficiency. [12]
> 
> (c) (i) Find the reflection coefficient and VSWR of a $75\,\Omega$ rf line terminated in each case with a load of (1) short circuit, (2) open circuit, (3) $+j75\,\Omega$ and (4) $-j75\,\Omega$, and compare the results with those of matched load. What is the shortest length of such a line to produce an input reactance of $+j75\,\Omega$, if its propagation constant is $(0+j1\cdot25)$? [7]
> 
> (ii) A lossless coaxial cable has the two-conductor diameter ratio of 2·0. Find its inductance, capacitance and $Z_{0}$, assuming a filling of dielectric with $\epsilon_{r}=2\cdot25$. [3]
> 
> (iii) For the probability density function $f(x)=ae^{-4|x|}$ of a random variable $X$ with $x$ ranging between $-\infty$ to $+\infty$, find the distribution function value of $a$ and the probability that $X$ lies between 0 and 1. [6]
> 
> (iv) For the angle-modulated signal given by
> $v(t)=5\cos\{\pi\times10^{7}t+2\sin 500\pi t\}$
> find the maximum phase deviation and frequency deviation, and bandwidth. Is this an FM signal or a PM signal? [4]

---

## Section-B

### [EE1-2010-Q5] Laplace Transform & Signal Energy Analysis · Op-Amp Circuits, 555 Timer, Transformer Windings & Noise Bandwidth

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Sketch
- **Theme (primary):** Laplace Transform & Signal Energy Analysis
- **Theme (secondary):** Op-Amp Circuits, 555 Timer, Transformer Windings & Noise Bandwidth
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** yes

> 5.
> (a) (i) Sketch the following function and find its Laplace transforms :
> $f(t)=r(t)-r(t-3)$
> $r(t)$ is unit ramp function. [5]
> 
> (ii) Sketch the following function and determine the energy or power contained in a signal :
> $x(t)=u(t)+5u(t-1)-6u(t-2)$ [5]
> 
> (iii) In the circuit shown below (Fig. 8), the switch S is in position '1' long enough to establish steady-state conditions and at $t=0$ is switched to position '2'. Draw 's-domain' network : [5]
> 
> **Figure ID:** FIG-EE1-2010-Q5a(iii)
> **Circuit description (netlist form):** A single-pole double-throw switch S. Position 1 connects to the positive terminal of a $50\text{ V}$ DC source; position 2 connects to the positive terminal of a $100\text{ V}$ DC source. Negative terminals of both DC sources are tied to a bottom reference rail. The common pole of switch S connects to a series branch containing a $25\ \Omega$ resistor and a $2\text{ H}$ inductor that returns to the reference rail.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) Draw the circuit of an opamp integrator. Sketch the output waveform, when the input is a symmetrical square wave of amplitude 3 V and the repetition frequency is 1 kHz. [4]
> 
> (ii) Determine the reading of the ideal voltmeter connected across a silicon diode shown in Fig. 9: [4]
> 
> **Figure ID:** FIG-EE1-2010-Q5b(ii)
> **Circuit description (netlist form):** A $5\text{ V}$ DC source connected with its positive terminal to a $1\text{ k}\Omega$ resistor. The resistor is connected to the anode of a silicon diode D, whose cathode is grounded to the source negative return. An ideal voltmeter V is connected directly across the terminals of diode D.
> **Symbolic form:** not derivable from figure.
> 
> Assume the forward voltage of diode to be 0.7 V. Find also the current through the diode.
> 
> (iii) Realize an Astable Multivibrator using 555 timer to produce a square wave of frequency 1 kHz with duty cycle of 50%. Mention three applications of timer. [7]
> 
> (c) (i) In three-phase transformers, discuss the use of tertiary windings. [10]
> 
> (ii) A three-phase star-delta transformer has its secondary delta open-circuited. A voltmeter is placed across open-circuited terminals. Will the voltmeter read zero? Discuss. [5]
> 
> (d) (i) A 50-ohm lossless line is terminated with a dipole of input impedance $(73+j42)\,\Omega$. Find the reflection coefficient, VSWR, and estimate the reflected and transmitted powers, if the input power to the line is 10 W. Also calculate the maximum and minimum impedances on the line, and suggest two methods of matching such a load to the line appropriately. [10]
> 
> (ii) Determine the noise bandwidth of the first-order RC integrator with cut-off frequency $f_{c}$. Define the term noise bandwidth. [5]

---

### [EE1-2010-Q6] Fourier Transform Network Response · Two-Port Networks, Active Filters, DAC Design & DC Choppers

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Obtain
- **Theme (primary):** Fourier Transform Network Response
- **Theme (secondary):** Two-Port Networks, Active Filters, DAC Design & DC Choppers
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** yes

> 6.
> (a) (i) Using Fourier transform method, obtain expression for $v(t)$ in the following network (Fig. 10): [6]
> 
> **Figure ID:** FIG-EE1-2010-Q6a(i)
> **Circuit description (netlist form):** A single-pair parallel network with an upward-directed independent current source $e^{-t}u(t)$ in parallel with a $0.5\ \Omega$ resistor and a $1\text{ F}$ capacitor. The voltage across the parallel combination is denoted $v(t)$ with positive reference at the top rail.
> **Symbolic form:** $V(\omega) = \frac{1}{(1+j\omega)(2+j\omega)}$
> 
> (ii) The z-parameters of a symmetrical two-port network (consisting of passive elements only) are given by $z_{11}=\frac{2}{3}\,\Omega$ and $z_{21}=\frac{1}{3}\,\Omega$. Obtain equivalent T-network. If this network is excited by a 2-volt source having internal resistance of 1 ohm, determine the load resistance to be connected across port-2 which will receive maximum power. [10]
> 
> (iii) State the differentiation property of Fourier transforms. Hence, obtain the Fourier transform of a Signum function. Sketch its magnitude spectrum. [4]
> 
> (b) (i) Design an opamp second-order Butterworth low-pass filter (LPF) for a cut-off frequency of 2 kHz. Compare the response curve with that of first-order LPF. [10]
> 
> (ii) With the aid of circuit, draw R/2R ladder DAC and discuss its operation. [6]
> 
> (iii) With $V_{REF}=5\text{ V}$ for the DAC, find the resolution and full-scale output of this converter. [4]
> 
> (c) Write voltage equations governing the performance of type-A chopper during on-period $T_{on}$ and off-period $T_{off}$ for the RLE type load. Hence, obtain therefrom, using Laplace transform, the expressions for the maximum and minimum currents taken by the load. Assume continuous conduction. [20]

---

### [EE1-2010-Q7] Wien Bridge Oscillator Design · Flip-Flop Conversion, Induction Motor Speed Control & FM Emphasis Filters

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Filters; sinusoidal oscillators: criterion for oscillation; single-transistor and OPAMP configurations. Function generators and wave-shaping circuits.
- **Directive:** Design
- **Theme (primary):** Wien Bridge Oscillator Design
- **Theme (secondary):** Flip-Flop Conversion, Induction Motor Speed Control & FM Emphasis Filters
- **Repeat cluster:** RC05 (Op-Amp Oscillator/Filter Design)
- **Has figure:** no

> 7.
> (a) (i) Using an opamp and RC network, explain the working of a Wien bridge oscillator. For a frequency of 1 kHz, design a Wien bridge oscillator. [$6+4=10$]
> 
> (ii) Convert a clocked SR Flip-Flop to a clocked JK FF. [$4+3+3=10$]
> 
> (b) (i) Speed control of a three-phase induction motor with constant supply voltage and reduced supply frequency is rarely used in practice. Justify this statement. [6]
> 
> (ii) Describe stator frequency control for the speed control of a three-phase induction motor. Derive expressions for motor torque, maximum torque and the slip at which it occurs. State the various assumptions made. [14]
> 
> (c) (i) A lossy non-magnetic medium has $\epsilon_{r}=4\cdot0$ and a phase constant of 0.10 rad/m at 2.0 MHz. Determine its loss tangent, conductivity, propagation constant, intrinsic impedance and skin depth. [10]
> 
> (ii) An FM system uses pre-emphasis and de-emphasis filters having the following transfer functions :
> 1. $H_{p}(f)=k\left[1+j\frac{f}{f_{0}}\right]$
> 2. $H_{d}(f)=\frac{1}{k}\left[\frac{1}{1+j(f/f_{0})}\right]$
> 
> Find the scaling factor k so that the average power of the emphasized signal is same as that of original signal $m(t)$.
> 
> Find the corresponding value of improvement factor $I$ produced by using this pair of pre-emphasis and de-emphasis filters. [10]

---

### [EE1-2010-Q8] Driving-Point Admittance & AC Nodal Analysis · Transformer Core Effects, Wave Reflection & AM Modulation

- **Exam:** UPSC Mains 2010 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications;
- **Directive:** Determine
- **Theme (primary):** Driving-Point Admittance & AC Nodal Analysis
- **Theme (secondary):** Transformer Core Effects, Wave Reflection & AM Modulation
- **Repeat cluster:** RC01 (Network Theorems (Thevenin/Millman/Nodal-Mesh))
- **Has figure:** yes

> 8.
> (a) (i) A linear network has a driving-point admittance $Y(s)$ given by
> $$Y(s)=\frac{12(s+1)}{s(s+2)(s+3)}$$
> Determine current in the network supplied by unit impulse voltage. What would be the current in the circuit when a unit step voltage is applied? [10]
> 
> (ii) Write the node equations for the network shown in Fig. 11. Assume node 3 as a reference node : [10]
> 
> **Figure ID:** FIG-EE1-2010-Q8a(ii)
> **Circuit description (netlist form):** An AC circuit with node 3 as reference. AC voltage source $50\angle 0^\circ\text{ V}$ connected in series with a $5\ \Omega$ resistor to node 1. Inductor with impedance $j2\ \Omega$ connected between node 1 and reference node 3. Resistor of $4\ \Omega$ connected between node 1 and node 2. Capacitor with impedance $-j2\ \Omega$ connected between node 2 and reference node 3. AC voltage source $50\angle 90^\circ\text{ V}$ connected in series with a $2\ \Omega$ resistor to node 2.
> **Symbolic form:** not derivable from figure.
> 
> (b) (i) The primary winding of a single-phase transformer is energized from a fixed sinusoidal voltage with secondary open-circuited. If a small portion of iron core is removed, discuss what would happen to the magnitudes of its exciting current, core flux and the no-load power factor. [7]
> 
> (ii) Explain why transformer rating is expressed in VA or kVA. Describe the significance of all the items mentioned on the nameplate of a single-phase transformer. [6]
> 
> (iii) Derive an expression for the per unit voltage regulation of a single-phase transformer. Show that magnitude of per unit voltage regulation is equal to per unit value of equivalent leakage impedance of the transformer. [7]
> 
> (c) (i) A plane wave having $\overline{E}=110\cos(\omega t-4\pi x)\hat{z}\text{ V/m}$ is normally incident on a medium of $\epsilon_{r}=9$, $\mu_{r}=4$ and $\sigma=0$, from a perfect dielectric medium of $\epsilon_{r}=4\cdot0$. Find the reflection and transmission coefficients, phase constants and list out the time-domain expressions for the incident, reflected and transmitted electric fields. [10]
> 
> (ii) Establish the time-domain expression for the AM signal at 60% modulation level with modulating signal as $5\cos(200\pi t)$ and carrier as $50\cos(10^{4}\pi t)$ and list out its Fourier transform. Find out the amplitude sensitivity constant, side-band powers and efficiency. [10]

---
