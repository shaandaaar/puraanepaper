# PAPER II

### [EE2-2018-Q1] Quantization Levels from a Given Probability Density Function · Generator-to-Infinite-Bus Power Transfer, Root-Locus Asymptotes, CT Phase Error & 8085 ADC Interfacing

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Pulse code modulation (PCM), defferential pulse code modulation (DPCM), delta modulation (DM),
- **Directive:** Determine
- **Theme (primary):** Quantization Levels from a Given Probability Density Function
- **Theme (secondary):** Generator-to-Infinite-Bus Power Transfer, Root-Locus Asymptotes, CT Phase Error & 8085 ADC Interfacing
- **Repeat cluster:** none
- **Has figure:** yes

> (a) A signal having probability density function
> $$f(x)=\begin{cases}k e^{-|x|}; & -4<x<4\\ 0; & \text{elsewhere}\end{cases}$$
> is quantized with four quantization levels.
> (i) Determine the value of k. [6]
> (ii) Determine step size s. [2]
> (iii) Determine the four quantization levels. [2]
>
> (b) A generator is connected to an infinite bus as shown in the figure. Derive the expressions for real power and reactive power supplied by the generator to the infinite bus: [10]
>
> **Figure ID:** FIG-EE2-2018-Q1b
> **Circuit description (netlist form):** Synchronous generator represented as an ideal AC voltage source with phasor voltage $E\angle\delta$ connected in series with an inductive reactance $jX$ to an infinite bus maintained at voltage phasor $V\angle 0^\circ$.
> **Symbolic form:** $P = \frac{EV}{X}\sin\delta, \quad Q = \frac{EV}{X}\cos\delta - \frac{V^2}{X}$
>
> (c) For the open-loop transfer function $G(s)H(s)=\frac{K}{s(s+4)(s+5)}$, determine the following:
> (i) Point of intersection of asymptotes with real axis
> (ii) Point of intersection of root locus with imaginary axis and the value of K at this point [10]
>
> (d) The magnetizing and loss component of exciting current of a current transformer rated 1000/5 A, are 15 A and 9 A respectively. The phase angle between secondary winding induced voltage and current is 40 degree. Determine the phase angle error of the transformer. [10]
>
> (e) Draw the schematic diagram for interfacing an 8-bit analog to digital converter to 8085 microprocessor using 8255 PPI. [10]

---

### [EE2-2018-Q2] Short Transmission-Line Sending-End Voltage and Power Factor · Energy-Meter Revolutions/Error, AM Spectrum Display & 8085 LED Control Program

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation;
- **Directive:** Determine
- **Theme (primary):** Short Transmission-Line Sending-End Voltage and Power Factor
- **Theme (secondary):** Energy-Meter Revolutions/Error, AM Spectrum Display & 8085 LED Control Program
- **Repeat cluster:** RC32 (Transmission Line & Economic Power-System Operation)
- **Has figure:** no

> (a) A 3-phase, 11 kV transmission line delivers a load of 2395 kVA at 0-8 p.f. (lag) over a distance of 25 km. The transmission line has an impedance per phase of $(3.25+j7.55)$ ohms. Determine the sending-end voltage and sending-end power factor. [20]
>
> (b) (i) An energy meter is designed to have 80 revolutions of the disc per unit of energy consumed. Calculate the number of revolutions made by the disc when measuring the energy consumed by the load carrying 30 A at 230 V and 0-6 power factor. Find the percentage error if the meter actually makes 330 revolutions. Also specify whether the meter runs slower or faster. [10]
>
> (ii) Explain how the spectra of amplitude-modulated signal are displayed on a spectrum analyzer. [10]
>
> (c) Write an 8085 microprocessor assembly language program to turn ON an LED connected to bit 4 of the 8155 I/O port B. Use address of port B as $22_{16}$. [10]

---

### [EE2-2018-Q3] PCM-TDM System Design for Multiplexed Signals · Controller Gain from Position-Error-Constant/Gain-Margin Specs & Alternator Differential Protection

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Pulse code modulation (PCM), defferential pulse code modulation (DPCM), delta modulation (DM),
- **Directive:** Design
- **Theme (primary):** PCM-TDM System Design for Multiplexed Signals
- **Theme (secondary):** Controller Gain from Position-Error-Constant/Gain-Margin Specs & Alternator Differential Protection
- **Repeat cluster:** RC59 (PCM System Design & Quantization)
- **Has figure:** no

> (a) Design a PCM system that multiplexes three signals $m_1$, $m_2$ and $m_3$ having bandwidths 5 kHz, 10 kHz and 5 kHz respectively. Each signal is sampled at its Nyquist rate and quantized to 256 levels.
> (i) Sketch the block diagram of the system. [6]
> (ii) What is the maximum bit duration that can be used? [8]
> (iii) What is the channel bandwidth required to pass the PCM signal? [4]
> (iv) What is the commutator speed in revolutions per second? [2]
>
> (b) For the system, whose open-loop transfer function is
> $$G(s)H(s)=\frac{K}{(s+2)^2(s+3)},$$
> determine K which satisfies the following specifications:
> (i) Position error constant $K_p \ge 2$
> (ii) Gain margin $\ge 3$ [20]
>
> (c) An 11 kV, 100 MVA alternator is provided with differential protection. The percentage of winding to be protected against phase-to-ground fault is 85%. The relay is set to operate when there is 20% out of balance current. Determine the value of the resistance to be placed in the neutral-to-ground connection. [10]

---

### [EE2-2018-Q4] Percentage Overshoot and Steady-State Error for a Unity-Feedback System · Power-System Transient Stability Margin & 8085 Instruction-Pair Differentiation

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** LTI systems: time-domain and transform-domain analysis.
- **Directive:** Determine
- **Theme (primary):** Percentage Overshoot and Steady-State Error for a Unity-Feedback System
- **Theme (secondary):** Power-System Transient Stability Margin & 8085 Instruction-Pair Differentiation
- **Repeat cluster:** RC06 (Control System Time-Domain Response)
- **Has figure:** no

> (a) Consider a unity feedback control system whose forward path transfer function is given by
> $$G(s)=\frac{9}{s(s+1)}$$
> Determine-
> (i) percentage overshoot resulting from application of unit step input;
> (ii) steady-state error resulting from application of unit step and unit ramp input. [10]
>
> (b) A three-phase power system consists of a synchronous machine connected through a lossless transmission line to an infinite bus. A fault occurs on the transmission line. The maximum power transfer of this system when there is no fault is 5 p.u. and the power transfer is 2-5 p.u. The power angle curves during the fault and post-fault conditions have peak values of 2 p.u. and 4 p.u. respectively. Determine the permissible increase in the angular displacement between the voltages at the two ends of the system beyond which the circuit breakers could not clear the fault in time for the system to remain in synchronism. [20]
>
> (c) Differentiate between the following pairs of instructions:
> (i) LDA addr and STA addr
> (ii) LDAX rp and SHLD addr
> (iii) LDAX rp and STAX rp
> (iv) RLC and RAL
> (v) PCHL and SPHL [20]

---

### [EE2-2018-Q5] Capacitor VAR Rating for Bus Voltage Support · Two-Wattmeter Reactive Power, Convolutional Encoding, 8085 Interrupt Masking & Routh-Hurwitz Pole Count

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation;
- **Directive:** Compute
- **Theme (primary):** Capacitor VAR Rating for Bus Voltage Support
- **Theme (secondary):** Two-Wattmeter Reactive Power, Convolutional Encoding, 8085 Interrupt Masking & Routh-Hurwitz Pole Count
- **Repeat cluster:** RC32 (Transmission Line & Economic Power-System Operation)
- **Has figure:** yes

> (a) For the system shown in the figure, $S_{D_1}$ and $S_{D_2}$ are complex power demands at bus-1 and bus-2 respectively. If $|V_2|=1\text{ p.u.}$, compute VAR rating of the capacitor $(Q_{G_2})$ connected at bus-2 in MVAr: [10]
>
> **Figure ID:** FIG-EE2-2018-Q5a
> **Circuit description (netlist form):** Two-bus power system single-line diagram. Bus 1 is a slack bus connected to generator $S_{G1}$ with bus voltage phasor $V_1 = 1\angle 0^\circ\text{ p.u.}$ and local load demand $S_{D1} = (1 + j0)\text{ p.u.}$ Bus 1 is connected to Bus 2 through a transmission line of series reactance $X = j0\cdot5\text{ p.u.}$ Bus 2 has a load demand $S_{D2} = (1 + j0)\text{ p.u.}$ and a shunt capacitor bank of rating $Q_{G2}$ connected to ground, with bus voltage magnitude $|V_2| = 1\text{ p.u.}$
> **Symbolic form:** not derivable from figure.
>
> (b) A wattmeter reads 5 kW when its current coil is connected in red phase and its voltage coil is connected between neutral and red phase of a symmetrical three-phase star-connected system supplying a balanced three-phase inductive load of 25 A at 440 V. What will be the reading of the wattmeter if the connection of the current coil remains unchanged and voltage coil is connected between blue and yellow phase? Hence determine the total reactive power in the circuit. [10]
>
> (c) A convolutional encoder is shown below:
>
> **Figure ID:** FIG-EE2-2018-Q5c
> **Circuit description (netlist form):** Rate $1/2$ convolutional encoder circuit diagram. Input binary sequence $U$ is fed into a 2-stage shift register (flip-flops $D_1, D_2$). Upper modulo-2 adder combines input $U$, output of stage 1, and output of stage 2 to generate sequence $v_1$. Lower modulo-2 adder combines input $U$ and output of stage 2 to generate sequence $v_2$. A multiplexer switches between $v_1$ and $v_2$ to form the serialized output code sequence $V$.
> **Symbolic form:** $g_1 = (1, 1, 1) \implies g_1(D) = 1 + D + D^2; \quad g_2 = (1, 0, 1) \implies g_2(D) = 1 + D^2$
>
> (i) Write down all the generator sequences and corresponding generator polynomial. [4]
> (ii) Determine the output sequence V, if the input sequence is U = (1 0 0 1 1). [6]
>
> (d) (i) What do you mean by maskable interrupts? Which interrupt cannot be masked? [5]
> (ii) Write an assembly language program to enable RST 6-5 interrupt. [5]
>
> (e) The characteristic equation of a system is given by
> $$s^4+3s^3+10s^2+20s+100=0$$
> By Routh-Hurwitz criterion, determine the number of poles of the system with positive real parts. [10]

---

### [EE2-2018-Q6] Circuit-Breaker Selection by System Voltage Range · Shannon-Fano Source Coding & 8085 Addressing Modes

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Principles of overcurrent, differential and distance protection. Concept of solid state relays. Circuit brakers.
- **Directive:** Discuss
- **Theme (primary):** Circuit-Breaker Selection by System Voltage Range
- **Theme (secondary):** Shannon-Fano Source Coding & 8085 Addressing Modes
- **Repeat cluster:** RC16 (Circuit-Breaker/Relay Protection Principles)
- **Has figure:** no

> (a) (i) Write about the selection of various circuit breakers for different ranges of system voltage. Mention the type of circuit breaker to be recommended by the utilities for a particular range of voltage. [10]
>
> (ii) Discuss the difficulty in the development of high voltage DC (HVDC) circuit breaker. Describe its construction and principle of operation. [10]
>
> (b) (i) Write the step-by-step procedure to obtain source code by using Shannon-Fano algorithm. [10]
>
> (ii) Obtain the source code for a source that generates messages with the following probabilities:
> $$m_1 \quad p_1 = 1/4$$
> $$m_2 \quad p_2 = 1/4$$
> $$m_3 \quad p_3 = 1/8$$
> $$m_4 \quad p_4 = 1/8$$
> $$m_5 \quad p_5 = 1/16$$
> $$m_6 \quad p_6 = 1/16$$
> $$m_7 \quad p_7 = 1/16$$
> $$m_8 \quad p_8 = 1/16$$
> Also calculate the efficiency of the code. [10]
>
> (c) Explain five addressing modes of 8085 microprocessor. [10]

---

### [EE2-2018-Q7] Nyquist Plot for a Two-Pole Open-Loop Transfer Function · AC Bridge Stray-Capacitance Elimination & Generator Neutral-Grounding Reactance

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Sketch
- **Theme (primary):** Nyquist Plot for a Two-Pole Open-Loop Transfer Function
- **Theme (secondary):** AC Bridge Stray-Capacitance Elimination & Generator Neutral-Grounding Reactance
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> (a) For the open-loop transfer function
> $$G(s)H(s)=\frac{1}{(s+p_1)(s+p_2)}; \quad p_1, p_2>0$$
> sketch Nyquist plot. Comment on the stability of the closed-loop system. [20]
>
> (b) Which method is used to eliminate the effect of stray capacitances in a four-arm AC bridge? Describe with circuit diagram. [20]
>
> (c) A three-phase generator rated 11 kV, 20 MVA has a solidly grounded neutral. Its positive, negative and zero sequence reactances are 60%, 25% and 15% respectively. Calculate the value of the reactance that should be placed in generator neutral such that the current for single line-to-ground fault does not exceed the rated current. [10]

---

### [EE2-2018-Q8] DPSK and BPSK Waveform Construction · State-Space Model from a Block Diagram, Lead-Compensator Bode Plot & Tap-Changer Reactive Power

- **Exam:** UPSC Mains 2018 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this paper format)
- **Syllabus:** Digital modulation and demodulation schemes: amplitude, phase and frequency keying schemes (ASK, PSK, FSK).
- **Directive:** Draw
- **Theme (primary):** DPSK and BPSK Waveform Construction
- **Theme (secondary):** State-Space Model from a Block Diagram, Lead-Compensator Bode Plot & Tap-Changer Reactive Power
- **Repeat cluster:** RC60 (Digital Modulation Schemes (ASK/FSK/PSK/QPSK/DPSK))
- **Has figure:** yes

> (a) (i) Draw the block diagram of a DPSK communication system. [8]
> (ii) The data stream to be transmitted by means of DPSK is $d(t)=00100110011110$. Determine the DPSK bit stream. [6]
> (iii) Sketch BPSK waveform if the transmitted data stream is 101000 and carrier frequency is $f_c$. [6]
>
> (b) (i) Consider the block diagram of a system shown below:
>
> **Figure ID:** FIG-EE2-2018-Q8bi
> **Circuit description (netlist form):** Open-loop control system block diagram with input signal $E(s)$ passing into a single forward path block with transfer function $\frac{K}{s(Ts+1)}$ to produce output position signal $\theta(s)$.
> **Symbolic form:** $\frac{\theta(s)}{E(s)} = \frac{K}{s(Ts+1)} \implies T\ddot{\theta}(t) + \dot{\theta}(t) = K e(t)$
>
> Write the differential equation relating $\theta$ to e and hence write the state model of the system choosing state variables as $\theta(t)$ and $\dot{\theta}(t)$. [10]
>
> (ii) Sketch Bode plot of a lead compensator. [10]
>
> (c) Two substations are connected by two lines in parallel with negligible impedance, but each containing a tap-changing transformer of reactance 0-18 p.u. on the basis of its rating of 200 MVA. Find the net absorption of reactive power in MVAr when the transformer taps are set to (1: 1-1) and (1: 0-9) respectively. Assume per unit voltages to be equal at two ends of the substation. [10]

---
