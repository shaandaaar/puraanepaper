# PAPER I

### [EE1-2018-Q1] Total Average Power in a Three-Phase Balanced Circuit · Laplace Transform of a Periodic Sawtooth, Thyristor Gate Drive, Op-Amp Ladder Gain & Induction-Motor Starting Methods

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Derive
- **Theme (primary):** Total Average Power in a Three-Phase Balanced Circuit
- **Theme (secondary):** Laplace Transform of a Periodic Sawtooth, Thyristor Gate Drive, Op-Amp Ladder Gain & Induction-Motor Starting Methods
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> (a) Derive the expression of total average power in three-phase balanced circuit. [10]
>
> (b) Find the Laplace transform of the periodic function $f(t)$ shown in Figure 1(b). [10]
>
> **Figure ID:** FIG-EE1-2018-Q1b
> **Circuit description (netlist form):** Periodic sawtooth waveform $f(t)$ versus time $t$ with fundamental period $T = 2\text{ s}$. Over the first period $[0, 2]$, the function starts at $(0, 0)$ and increases linearly to $(1, 2)$ at $t = 1\text{ s}$, then abruptly drops to $0$ at $t = 1\text{ s}$, remaining at $0$ for $1 < t \le 2\text{ s}$. The cycle repeats identically for subsequent intervals $[2, 4]$, $[4, 6]$, etc.
> **Symbolic form:** $f(t) = \begin{cases} 2t, & 0 \le t < 1 \\ 0, & 1 \le t < 2 \end{cases}, \quad f(t+2) = f(t)$
>
> (c) (i) Draw thyristor gate characteristics and state its application in design of gate drive circuit.
>
> (ii) A thyristor has a maximum average gate power dissipation limit of 0-4 watts. It is triggered with pulsed gate current of frequency 20 kHz at a duty ratio of 0-5. If the gate cathode voltage drop is 1 volt, find permissible peak gate current magnitude. [10]
>
> (d) For the op-amp circuit shown in Figure 1(d), determine the gain $A_v = \frac{v_o}{v_i}$. Assume that all resistors are equal. [10]
>
> **Figure ID:** FIG-EE1-2018-Q1d
> **Circuit description (netlist form):** Inverting operational amplifier circuit with an R-ladder feedback network. The non-inverting terminal (+) is connected to ground (0 V). The input node $v_i$ is connected via series input resistor $R$ carrying current $i$ to the inverting input terminal (-). From the inverting input terminal, a series resistor $R$ connects to internal node 1. Internal node 1 is connected to ground via shunt resistor $R$, and via series resistor $R$ to internal node 2. Internal node 2 is connected to ground via shunt resistor $R$, and via series resistor $R$ to the op-amp output terminal $v_o$.
> **Symbolic form:** $A_v = \frac{v_o}{v_i} = -8$
>
> (e) A squirrel cage induction motor has a starting current of six times the full load current, at a slip of 0-04. Calculate the line current and starting torque in p.u. (per unit) of full load values for the following starting methods:
> (i) Direct switching
> (ii) Star-Delta starting [10]

---

### [EE1-2018-Q2] Boolean Expression Conversion to NAND-Only Logic · Transmission-Line SWR/Impedance & SSB-to-AM Power Conversion

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS).
- **Directive:** Convert
- **Theme (primary):** Boolean Expression Conversion to NAND-Only Logic
- **Theme (secondary):** Transmission-Line SWR/Impedance & SSB-to-AM Power Conversion
- **Repeat cluster:** RC17 (Digital IC Families & Number Systems)
- **Has figure:** no

> (a) Convert the following logic equation to NAND logic and draw the circuit using NAND gates:
> $$Z = (\overline{A+B})C + A(\overline{B+C})$$ [20]
>
> (b) (i) A low loss transmission line has characteristic impedance $Z_0 = 70~\Omega$ and is terminated by another impedance of $115 - j80~\Omega$. The wavelength on the line is 2-5 m.
> Find:
> I. SWR (Standing Wave Ratio)
> II. Maximum and minimum line impedance, $Z_{1\text{max}}$ and $Z_{1\text{min}}$ [10]
>
> (ii) If the input impedances of a short and open circuited transmission line of length 1-5 m are $Z_{SC} = -j78~\Omega$ and $Z_{OC} = j90~\Omega$ respectively, determine the characteristic impedance $Z_0$ and propagation constant $\gamma$ of the line. [10]
>
> (c) An SSB transmitter transmits with 10 kW power. This transmitter is to be replaced by a standard amplitude modulated signal with same total power content. Determine the carrier power and each sideband power, when the percentage modulation is 80%. [10]

---

### [EE1-2018-Q3] Transformer Efficiency at Varying Load and Power Factor · H-Bridge Inverter RL-Load Analysis & DC Network Node Voltage

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers.
- **Directive:** Calculate
- **Theme (primary):** Transformer Efficiency at Varying Load and Power Factor
- **Theme (secondary):** H-Bridge Inverter RL-Load Analysis & DC Network Node Voltage
- **Repeat cluster:** RC20 (Transformer Performance & Testing)
- **Has figure:** yes

> (a) The maximum efficiency of a 50 KVA transformer is 97.4% and occurs at 90% of full load, at unity power factor. Calculate the efficiency at
> (i) Full load at 0-8 power factor (p.f.)
> (ii) Half the full load at 0-9 power factor (p.f.) [20]
>
> (b) A full bridge or H-bridge inverter has a switching sequence which results in a square wave output voltage. Let the switching frequency be 50 Hz and inverter is supplying a RL load having $R = 10~\Omega$ and $L = 30\text{ mH}$. Determine:
> (i) An expression for load current
> (ii) The power absorbed by load
> (iii) The average current in the D.C. source
> (iv) The area in output voltage waveform where antiparallel diodes across switches conduct
> (Assume Input D.C. voltage $= 100\text{ V}$) [20]
>
> (c) In the circuit shown in Figure 3(c), find the voltage $v_0$ across the $8~\Omega$ resistor. [10]
>
> **Figure ID:** FIG-EE1-2018-Q3c
> **Circuit description (netlist form):** DC planar resistive circuit with common bottom ground rail. Leftmost branch contains a $4~\Omega$ resistor in parallel with an independent DC current source of $3\text{ A}$ directed downwards. From the upper terminal of this parallel branch, a $2~\Omega$ resistor is connected in series to an upper central node. Across the upper central node and ground rail is connected an $8~\Omega$ resistor with terminal voltage labeled $v_o$ (positive reference at top node, negative reference at bottom rail). From the upper central node, a $3~\Omega$ resistor is connected in series to an independent DC voltage source of $12\text{ V}$ whose positive terminal is connected to the resistor and negative terminal is connected to ground.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2018-Q4] AM Modulation Index from Antenna Current Enhancement · DC Shunt Motor Plugging & Op-Amp Integrator Slew-Rate Limits

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Linear CW modulation: Amplitude modulation : DSB, DSB-SC and SSB. Modulators and Demodulators;
- **Directive:** Find
- **Theme (primary):** AM Modulation Index from Antenna Current Enhancement
- **Theme (secondary):** DC Shunt Motor Plugging & Op-Amp Integrator Slew-Rate Limits
- **Repeat cluster:** RC27 (Amplitude Modulation Analysis)
- **Has figure:** yes

> (a) The antenna current of a transmitter is 11-5 amperes, when it is modulated to a depth of 45% by an audio wave. The current enhances to 12-5 amperes on account of simultaneous modulation by another audio sine wave. Find the modulation index of the second audio wave. [20]
>
> (b) A 400 volts D.C. shunt motor draws 30 amperes while supplying the rated load at a speed of $120\text{ rad/sec}$. The armature resistance is 1.0 ohm and the field winding resistance is 250 ohms. Determine the external resistance that must be inserted in series with armature circuit so that, the armature current should not exceed 150% of its rated value, when the motor is plugged. Find the braking torque, at the instant of plugging. [20]
>
> (c) The integrator circuit shown in Figure 4(c) is to be used to generate a triangular waveform from a 500 Hz square wave connected to its input. Suppose that the square wave alternates between $\pm 12\text{ V}$.
> (i) Find the minimum slew rate required for the amplifier.
> (ii) Find the maximum output voltage the amplifier can generate. [10]
>
> **Figure ID:** FIG-EE1-2018-Q4c
> **Circuit description (netlist form):** Practical op-amp integrator circuit. Non-inverting input terminal (+) is connected to ground through a $370~\Omega$ resistor. Input terminal is connected to the inverting input (-) via a $400~\Omega$ input resistor and driven by a square wave source. Feedback path connected between inverting input (-) and output terminal $v_o$ consists of a parallel branch containing a $4\cdot7\text{ k}\Omega$ feedback resistor and a $1~\mu\text{F}$ feedback capacitor.
> **Symbolic form:** $\frac{V_o(s)}{V_i(s)} = -\frac{R_f / R_{in}}{1 + s R_f C_f} = -\frac{4700 / 400}{1 + s (4700)(10^{-6})} = -\frac{11.75}{1 + 0.0047s}$

---

### [EE1-2018-Q5] D-Flip-Flop to S-R Flip-Flop Conversion · DC Generator EMF Scaling, 3-Phase Half-Wave Rectifier, Maxwell's Equation & Thevenin's Theorem

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Sequential circuits: latches and flip-flops, counters and shift-registers.
- **Directive:** Convert
- **Theme (primary):** D-Flip-Flop to S-R Flip-Flop Conversion
- **Theme (secondary):** DC Generator EMF Scaling, 3-Phase Half-Wave Rectifier, Maxwell's Equation & Thevenin's Theorem
- **Repeat cluster:** RC14 (Sequential Logic (Flip-Flops/Counters))
- **Has figure:** yes

> (a) Convert a D flip flop to function as an S-R flip flop. Draw the circuit. [10]
>
> (b) A D.C. generator has an armature e.m.f. of 100 volts, when the useful flux per pole is 20 mWb and the speed is 800 r.p.m.
> Calculate the generated e.m.f.
> (i) with the same flux and a speed of 1000 r.p.m.
> (ii) with flux per pole of 24 mWb and a speed of 900 r.p.m. [10]
>
> (c) Draw output voltage and current waveforms and determine r.m.s. output voltage of a three-phase half-wave rectifier supplied by three-phase balanced a.c. supply. Also determine the form factor.
> If the supply voltage of the above converter is 220 V (r.m.s.) at 50 Hz and the load is of 1 kW at 200 V, purely resistive, determine power consumed by the load with given supply voltage. [10]
>
> (d) (i) Derive the Maxwell's equation for time varying magnetic field based on Ampere's circuital law.
> (ii) A parallel plate capacitor with plate area of $5\text{ cm}^2$ and plate separation of 3 mm has a voltage of $50\sin 10^3 t\text{ V}$ applied to its plates. Calculate the displacement current assuming $\epsilon = 2\epsilon_0$. [10]
>
> (e) Using Thevenin's theorem, find the current through the $40~\Omega$ resistor connected between terminals a and b in Figure 5(e). [10]
>
> **Figure ID:** FIG-EE1-2018-Q5e
> **Circuit description (netlist form):** DC bridge circuit powered by an independent $220\text{ V}$ DC source connected between top and bottom supply rails. Left leg consists of a $3\text{ k}\Omega$ resistor in series with a $1\text{ k}\Omega$ resistor to ground; intermediate node between them is labeled 'a'. Right leg consists of a $400~\Omega$ resistor in series with a $600~\Omega$ resistor to ground; intermediate node between them is labeled 'b'. A $40~\Omega$ load resistor is connected across terminals 'a' and 'b'.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2018-Q6] Buck Converter LC Filter Design for Ripple Reduction · Fourier-Transform Circuit Response & Colpitts Oscillator Frequency

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** principles of thyristor choppers and inverters; DC-DC converters; Switch mode inverter;
- **Directive:** Prove
- **Theme (primary):** Buck Converter LC Filter Design for Ripple Reduction
- **Theme (secondary):** Fourier-Transform Circuit Response & Colpitts Oscillator Frequency
- **Repeat cluster:** RC25 (DC Choppers & Switch-Mode Converters)
- **Has figure:** yes

> (a) A buck converter (D.C.-D.C. converter) has LC filter in the output to reduce ripple in output voltage. For continuous conduction mode, draw the waveforms of output voltage, inductor current and capacitor current. If the converter is switched at frequency 'f', prove that minimum values of 'L' and 'C' for $\Delta I_L$ ripple in inductor current and $\Delta V_0$ ripple in output voltages are given by
> $$C = \frac{(1-D)}{8L(\Delta V_0/V_0)f^2}$$
> and
> $$L = \frac{V_o(1-D)}{(\Delta I_L)f}$$
> Assume any data missing. D is duty cycle of switch and $V_0$ is the average output voltage. [20]
>
> (b) Find $i_0(t)$ in the circuit shown in Figure 6(b) using Fourier transform method when $i_s(t) = 10\sin 2t\text{ Amp}$. [20]
>
> **Figure ID:** FIG-EE1-2018-Q6b
> **Circuit description (netlist form):** AC circuit driven by an independent current source $i_s(t) = 10\sin 2t\text{ A}$ directed upwards. Connected in parallel with the source are two branches: first branch contains a $2~\Omega$ resistor; second branch contains a series combination of a $4~\Omega$ resistor and a $0\cdot5\text{ F}$ capacitor carrying downward current $i_o(t)$.
> **Symbolic form:** $I_o(s) = I_s(s) \frac{2}{2 + 4 + \frac{1}{0.5s}} = I_s(s) \frac{s}{3s + 1}$
>
> (c) Determine the feedback fraction and the operating frequency for the oscillator circuit shown in Figure 6(c). [10]
>
> **Figure ID:** FIG-EE1-2018-Q6c
> **Circuit description (netlist form):** BJT Colpitts oscillator circuit. NPN transistor with emitter connected to ground. Base terminal is biased via voltage divider with resistor $R_{B1}$ connected to $V_{CC}$ and $R_{B2}$ to ground. Collector is connected to supply $V_{CC}$ through a radio frequency choke $RFC = 100~\mu\text{H}$, and coupled to the output terminal $v_o$ via coupling capacitor $C_C = 100\text{ pF}$. Resonant tank network consists of capacitor $C_2 = 10\text{ pF}$ from collector to ground, capacitor $C_1 = 100\text{ pF}$ from ground to lower feedback node, and inductor $L_1 = 1~\mu\text{H}$ connected between collector and the lower feedback node. The lower feedback node is coupled to the transistor base through a coupling capacitor $C_C = 100\text{ pF}$.
> **Symbolic form:** $f_0 = \frac{1}{2\pi \sqrt{L_1 \left(\frac{C_1 C_2}{C_1 + C_2}\right)}}$

---

### [EE1-2018-Q7] EM Wave Transmission Through a Dielectric Slab · Synchronous D-Flip-Flop Counter Design & Controlled-Rectifier DC Motor Firing Angle

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Maxwell's equations, wave propagation in bounded media. Boundary conditions, reflection and refraction of plane waves.
- **Directive:** Determine
- **Theme (primary):** EM Wave Transmission Through a Dielectric Slab
- **Theme (secondary):** Synchronous D-Flip-Flop Counter Design & Controlled-Rectifier DC Motor Firing Angle
- **Repeat cluster:** RC18 (Electromagnetic Field Theory (Maxwell's Equations & Poynting Theorem))
- **Has figure:** yes

> (a) (i) A travelling $\overline{E}$ field in the free space of amplitude $100\text{ V/m}$ strikes a perfect dielectric as shown in Figure 7(a)(i). Determine the value of $E_t$. [10]
>
> **Figure ID:** FIG-EE1-2018-Q7ai
> **Circuit description (netlist form):** Electromagnetic wave propagation through a planar dielectric slab. Region 1 on the left is free space with incident traveling electric field $\overline{E}_i$ of amplitude $100\text{ V/m}$. A lossless dielectric medium of thickness $1\text{ mm}$ is bounded between interface plane A and interface plane B with material parameters $\epsilon_r = 20, \mu_r = 1, \sigma = 0$. Region 3 to the right of interface B is free space with transmitted electric field $E_t$.
> **Symbolic form:** not derivable from figure.
>
> (ii) A uniform plane wave in air partially reflects from the surface of a material whose properties are unknown. Measurements of the electric field in front of the interface region yield a 1-5 m spacing between maxima, with the first maximum occurring 0-75 m from the interface. A standing wave ratio of 5 is measured. Determine the intrinsic impedance $\eta_w$ of the unknown material. [10]
>
> (b) Design a synchronous counter using D flip flop that counts in the following sequence:
> 6, 3, 5, 0, 2, 6, 3, 5, 0, 2, 6, ...
> Draw the circuit. [20]
>
> (c) A 220 volts, 1500 r.p.m., 50 A separately excited D.C. motor is fed from a three-phase fully controlled rectifier. The rectifier is supplied with a balanced three-phase source with phase voltage of 230 volts (r.m.s.) at 50 Hz. Motor is holding an overhauling load at 1200 r.p.m. at full load torque. Determine the firing angle of converter if armature resistance is assumed to be $0\cdot2~\Omega$. [10]

---

### [EE1-2018-Q8] AC Resonant-Circuit Branch Currents and Power Factor · Multi-Input Op-Amp Summing-Differencing Output & Single-Tone FM Parameters

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Find
- **Theme (primary):** AC Resonant-Circuit Branch Currents and Power Factor
- **Theme (secondary):** Multi-Input Op-Amp Summing-Differencing Output & Single-Tone FM Parameters
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> (a) For the circuit shown in Figure 8(a), $v(t) = 311\cdot12\sin 377t\text{ volts}$:
> (i) Find the values of $\overline{I}_1$, $\overline{I}_2$, $\overline{I}_3$, $\overline{I}_4$ and $\overline{I}_5$.
> (ii) Also compute $\overline{V}_{bc}$ and $\overline{V}_{cd}$.
> (iii) Compute the power supplied by the source.
> (iv) Find the line power factor. [20]
>
> **Figure ID:** FIG-EE1-2018-Q8a
> **Circuit description (netlist form):** AC network energized by an independent sinusoidal source $v(t) = 311\cdot12\sin 377t\text{ V}$. Source delivers total current $\overline{I}_5$ to node a. Node a branches into: a vertical shunt branch carrying current $\overline{I}_4$ into a parallel LC tank consisting of inductor $L_1 = 0\cdot096\text{ H}$ (carrying current $\overline{I}_1$) in parallel with capacitor $C_1 = 73\cdot3~\mu\text{F}$ (carrying current $\overline{I}_2$) returning to bottom ground node d; and a rightward branch carrying current $\overline{I}_3$ through a $4~\Omega$ series resistor to node b. From node b to node c is an inductor of $0\cdot096\text{ H}$, and from node c to node d is a series capacitor of $73\cdot3~\mu\text{F}$. Bottom node d connects back to the negative terminal of the AC source.
> **Symbolic form:** not derivable from figure.
>
> (b) Calculate the output voltage $v_0$ in terms of the input voltages $v_{i_1}$, $v_{i_2}$, $v_{i_3}$ and $v_{i_4}$ for the circuit shown in Figure 8(b). [20]
>
> **Figure ID:** FIG-EE1-2018-Q8b
> **Circuit description (netlist form):** Op-amp summing-differencing amplifier. Inverting input (-) receives inputs $v_{i1}$ through resistor $R_1$ and $v_{i2}$ through resistor $R_2$, and is connected to output node $v_o$ via feedback resistor $R_F$. Non-inverting input (+) receives inputs $v_{i3}$ through resistor $R_A$ and $v_{i4}$ through resistor $R_B$, and is tied to ground via resistor $R_C$.
> **Symbolic form:** $v_o = \left(1 + \frac{R_F}{R_1 \parallel R_2}\right) \left(\frac{\frac{v_{i_3}}{R_A} + \frac{v_{i_4}}{R_B}}{\frac{1}{R_A} + \frac{1}{R_B} + \frac{1}{R_C}}\right) - \frac{R_F}{R_1}v_{i_1} - \frac{R_F}{R_2}v_{i_2}$
>
> (c) A single tone FM is represented by the voltage equation as
> $$v(t) = 12\cos(6\times 10^8 t + 5\sin 1250 t).$$
> Determine:
> (i) Carrier frequency
> (ii) Modulation frequency
> (iii) Maximum deviation
> (iv) Bandwidth
> (v) Power dissipated in a $10~\Omega$ resistance [10]

---
