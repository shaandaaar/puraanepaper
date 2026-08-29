# SECTION A

### [EE2-2014-Q1] Identifying a Minimum-Phase Transfer Function from a Bode Plot · 8085 Interrupt Priorities, Piezoelectric Transducer Uses, IDMT Relay Curves & Symmetrical-Component Fault Analysis

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 1 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Identify
- **Theme (primary):** Identifying a Minimum-Phase Transfer Function from a Bode Plot
- **Theme (secondary):** 8085 Interrupt Priorities, Piezoelectric Transducer Uses, IDMT Relay Curves & Symmetrical-Component Fault Analysis
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> Answer all of the following:
> 
> (a) An approximate Bode plot of magnitude for a system was obtained and is shown below. Identify the system in terms of minimum phase transfer function. [10]
> 
> **Figure ID:** FIG-EE2-2014-Q1a
> **Circuit description (netlist form):** Bode magnitude plot displaying magnitude $M_{\text{dB}}$ versus $\log\omega$. Plot begins at $\omega = 0\cdot1\text{ rad/s}$ at $66\text{ dB}$ with a slope of $-20\text{ dB/dec}$ down to $50\text{ dB}$ at $\omega = 1\cdot0\text{ rad/s}$; horizontal constant line of $50\text{ dB}$ ($0\text{ dB/dec}$) from $\omega = 1\cdot0\text{ rad/s}$ to $\omega = 10\text{ rad/s}$; slope of $-20\text{ dB/dec}$ from $\omega = 10\text{ rad/s}$ down to $30\text{ dB}$ at $\omega = 100\text{ rad/s}$; followed by a slope of $-40\text{ dB/dec}$ for $\omega > 100\text{ rad/s}$ passing through $\omega = 1000\text{ rad/s}$.
> **Symbolic form:** $G(s)=\frac{K(1+s)}{s(1+0\cdot1s)(1+0\cdot01s)}$
> 
> (b) (i) Write the various interrupts available in the microprocessor 8085 in the order of decreasing priority. [6]
> (ii) Specify multiplexed and non-multiplexed bus lines in 8085 microprocessor. [4]
> 
> (c) Explain the function of piezoelectric crystal as transducer. Specify its use in
> (i) Kitchen lighter
> (ii) Ultrasound diagnostic equipments
> (iii) Industrial cleaning machines. [10]
> 
> (d) Draw the typical characteristics of an IDMT Relay and explain how to use these curves. [10]
> 
> (e) Using symmetrical component theory for analysing an unbalanced fault, show that under certain circumstances, it is possible that the fault current for a S-L-G fault can exceed the fault current for a 3-phase fault in the same system. [10]

---

### [EE2-2014-Q2] PD Controller Design for Specified Closed-Loop Pole Locations · 2-Bus Power-Flow Derivation & IDMT Relay Timing Calculation

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 2 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Proportional, PI, PID controllers.
- **Directive:** Evaluate
- **Theme (primary):** PD Controller Design for Specified Closed-Loop Pole Locations
- **Theme (secondary):** 2-Bus Power-Flow Derivation & IDMT Relay Timing Calculation
- **Repeat cluster:** RC21 (PID/Compensator Controller Design)
- **Has figure:** yes

> (a) What is the effect of introducing derivative control action on the response of a system?
> A system has open-loop transfer function given by
> $$G(s)=\frac{10}{(s+1)(s+4)}$$
> Evaluate the parameters of a PD controller with this system with unity feedback so that the closed loop system has poles located at $-3\pm j4$. Indicate the nature of closed loop time response to unit step input change. [20]
> 
> (b) For a 2-bus system shown below, derive expressions for Real Power and Reactive Power at receiving end and sending end. [20]
> 
> **Figure ID:** FIG-EE2-2014-Q2b
> **Circuit description (netlist form):** Single-line diagram of a two-bus transmission system. An AC generator supplies the sending-end bus with phasor voltage $|V_S|\angle \delta^\circ$ and complex power $S_S = P_S + jQ_S$. A transmission line characterized by two-port parameters $A, B, C, D$ connects the sending-end bus to the receiving-end bus with phasor voltage $|V_R|\angle 0^\circ$. A load is connected to the receiving-end bus drawing complex power $S_R = P_R + jQ_R$.
> **Symbolic form:** not derivable from figure.
> 
> (c) An IDMT Relay has a current setting of $150\%$ and has a time multiple setting of $0\cdot5$. The relay is connected in a circuit through a C.T. having a ratio of $500:5\text{ amps}$. Calculate the time of operation of the relay if the circuit carries a fault current of $6,000\text{ A}$. Use the table given below :
> 
> | P.S.M. | 2 | 3.6 | 5 | 8 | 10 | 15 | 20 |
> | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> | Time in seconds for T.M.S. of 1.0 | 10 | 6 | 3.9 | 3.15 | 2.8 | 2.2 | 2.1 |
> 
> [10]

---

### [EE2-2014-Q3] Underdamped Second-Order Step Response Under Varying Pole Conditions · Medium Transmission-Line π-Model & Bewley-Lattice Diagrams

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 3 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** LTI systems: time-domain and transform-domain analysis.
- **Directive:** Draw
- **Theme (primary):** Underdamped Second-Order Step Response Under Varying Pole Conditions
- **Theme (secondary):** Medium Transmission-Line π-Model & Bewley-Lattice Diagrams
- **Repeat cluster:** RC06 (Control System Time-Domain Response)
- **Has figure:** no

> (a) Draw the approximate time response of an underdamped second order system subjected to unit step input disturbance in desired value for the following cases of complex conjugate poles:
> (i) with constant real part
> (ii) with constant imaginary part
> (iii) with constant damping ratio
> In each case consider at least 2 sets of values and mention the most important feature of the response. [20]
> 
> (b) (i) Draw the equivalent of a medium length transmission line using $\pi$-model.
> (ii) Assume that the receiving end is supplying a lagging power factor load. Draw the Phasor diagram showing all voltages and currents.
> (iii) Derive the A, B, C and D constants of this line in terms of line parameters Z and Y. [20]
> 
> (c) Explain what is meant by Bewley-Lattice diagram. What is the use of this diagram? [10]

---

### [EE2-2014-Q4] Ramp-Type ADC and Digital Voltmeter Block Diagrams · 8085 Addressing Modes & PCM Quantization-Level Calculation

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 4 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Signal conditioning circuit; Electronic measuring instruments multimeter, CRO, digital voltmeter, frequency counter, Q-meter, spectrum-analyser, distoration-meter.
- **Directive:** Describe
- **Theme (primary):** Ramp-Type ADC and Digital Voltmeter Block Diagrams
- **Theme (secondary):** 8085 Addressing Modes & PCM Quantization-Level Calculation
- **Repeat cluster:** RC09 (Electronic Measuring Instruments)
- **Has figure:** no

> (a) Describe with a block diagram the Ramp type analog-to-digital conversion. Also draw the block diagram of Ramp type digital voltmeter. [20]
> 
> (b) Describe the various addressing modes in the microprocessor 8085. Give suitable examples for each addressing mode. [10]
> 
> (c) A sinusoidal signal is transmitted using P.C.M. The output signal to quantization noise is required to be $55\cdot8\text{ dB}$. Find the minimum number of quantization levels. Derive the equation used. [20]

---

# SECTION B

### [EE2-2014-Q5] Nyquist Stability Analysis via Nyquist Path and Plot · PCM Bandwidth & Sampling Parameters, Alternator Neutral Grounding & ADC Resolution

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 5 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Nyquist Stability Analysis via Nyquist Path and Plot
- **Theme (secondary):** PCM Bandwidth & Sampling Parameters, Alternator Neutral Grounding & ADC Resolution
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** no

> Answer all of the following:
> 
> (a) A plant has open-loop transfer function
> $$G(s)=\frac{2}{s(1+0\cdot1s)(1+0\cdot5s)}$$
> Determine the complete stability information of the unity feedback closed loop system by sketching Nyquist path and Nyquist plot. [10]
> 
> (b) Derive an expression for the Bandwidth of 'P.C.M.' system. [10]
> 
> (c) A channel with bit rate, $R_{b}=36\text{ kbps}$ is available for 'P.C.M.' voice transmission. Find the appropriate values of binary digits $N$, the number of quantization levels ($M$) and the sampling rate ($f_{s}$), assuming $f_{m}=3\cdot2\text{ kHz}$. [10]
> 
> (d) Explain the importance of adding impedance in the neutral path of an alternator. [10]
> 
> (e) An analog transducer with a $0\text{--}10\text{ V}$ input is able to distinguish a change of $1\text{ mV}$ in its signal. Calculate (i) its resolution (ii) the minimum number of bits of ADC so that the digital output has almost the same resolution as transducer. Also calculate the (iii) quantization interval and (iv) number of decision levels. [10]

---

### [EE2-2014-Q6] LVDT-Bellows System for Pressure Measurement · Microprocessor Addressing Modes & (7,4) Linear Block Code

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 6 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Transducers: thermocouple, thermistor, LVDT, strain-guage, piezo-electric crystal.
- **Directive:** Draw
- **Theme (primary):** LVDT-Bellows System for Pressure Measurement
- **Theme (secondary):** Microprocessor Addressing Modes & (7,4) Linear Block Code
- **Repeat cluster:** RC10 (Transducer Characteristics (LVDT/Strain Gauge/Capacitive/Piezo))
- **Has figure:** no

> (a) (i) LVDT with bellow is used for measuring the pressure. Draw the circuit diagram of LVDT-bellow system. [6]
> (ii) The sensitivity of LVDT-bellow system is $40\text{ V per mm}$. The bellows are deflected by $0\cdot15\text{ mm}$ by a pressure of $1\cdot0\times10^{6}\text{ N per m}^{2}$. Determine the pressure when the output voltage of LVDT is $3\cdot9\text{ V}$. [14]
> 
> (b) Explain: (i) Direct addressing (ii) Register indirect addressing (iii) Immediate addressing (iv) Register addressing. [20]
> 
> (c) The parity check matrix $\overline{H}$ of a linear (7, 4) block code is given by
> $$\overline{H}=\begin{bmatrix}1&0&1&1&1&0&0\\ 1&1&0&1&0&1&0\\ 0&1&1&1&0&1&1\end{bmatrix}$$
> Determine the coded word for the data 0101. [10]

---

### [EE2-2014-Q7] Compensator Gain and Zero-Location Design for Closed-Loop Stability · 8085 Hardware Single-Stepping & Delta-Modulation SNR (No-Slope-Overload)

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 7 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators.
- **Directive:** Determine
- **Theme (primary):** Compensator Gain and Zero-Location Design for Closed-Loop Stability
- **Theme (secondary):** 8085 Hardware Single-Stepping & Delta-Modulation SNR (No-Slope-Overload)
- **Repeat cluster:** RC08 (Control System Stability Criteria)
- **Has figure:** yes

> (a) For a position control system as shown in the figure below, determine the range of compensator gain $K$ and the location of zero in left half for which the system is stable. [20]
> 
> **Figure ID:** FIG-EE2-2014-Q7a
> **Circuit description (netlist form):** Unity negative feedback control system block diagram. Input $R(s)$ (Desired position) enters a summing comparator (+ terminal), with feedback signal subtracted from output $Y(s)$ (Actual position). Error signal feeds into Compensator block $\frac{K(s+a)}{(s+1)}$, whose output enters Plant block $\frac{1}{s(s+2)(s+3)}$, generating output $Y(s)$.
> **Symbolic form:** $T(s)=\frac{Y(s)}{R(s)}=\frac{K(s+a)}{s(s+1)(s+2)(s+3)+K(s+a)}$
> 
> (b) Explain hardware single stepping used in 8085 microprocessor. [20]
> 
> (c) Derive the expression for maximum signal to quantization noise ratio for sinusoidal message input when waveform coding is done by D.M. under no-slope overload condition. [10]

---

### [EE2-2014-Q8] State-Space Signal-Flow Graph, Transfer Function & Controllability Test · Circuit-Breaker Restriking Transients & Unit (Differential) Protection Principle

- **Exam:** UPSC Mains 2014 | **Paper:** EE Optional Paper II | **Q.No:** 8 | **Marks:** 50 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** State-variable representation and analysis of control systems.
- **Directive:** Draw
- **Theme (primary):** State-Space Signal-Flow Graph, Transfer Function & Controllability Test
- **Theme (secondary):** Circuit-Breaker Restriking Transients & Unit (Differential) Protection Principle
- **Repeat cluster:** RC11 (State-Variable/State-Space Analysis)
- **Has figure:** no

> (a) (i) A system is modelled in state-space form as
> $$\dot{X}=\begin{bmatrix}0&1&0\\ 0&0&1\\ -1&-7&-5\end{bmatrix}X+\begin{bmatrix}0\\ 0\\ 1\end{bmatrix}u$$
> $$C=\begin{bmatrix}3&4&0\end{bmatrix}$$
> Draw the signal flow graph and obtain the transfer function. [10]
> 
> (ii) Define state controllability of a system. Apply the controllability test to determine the controllability of a system modelled by the state-space model as
> $$\dot{X}=\begin{bmatrix}-2&-2&0\\ 0&0&1\\ 0&-3&-4\end{bmatrix}X+\begin{bmatrix}1&0\\ 0&1\\ 1&1\end{bmatrix}\begin{bmatrix}u_{1}\\ u_{2}\end{bmatrix}$$
> $$y=\begin{bmatrix}1&1&0\end{bmatrix}X$$ [10]
> 
> (b) In a $220\text{ kV}$, $50\text{ c/s}$ power system, the reactance and capacitance upto the circuit breaker are $8\text{ ohms}$ and $0\cdot025\ \mu\text{F}$ respectively. A resistance of $600\text{ ohms}$ is connected across the circuit breaker contacts.
> Determine the following:
> (i) Natural frequency of oscillation
> (ii) Damped frequency of oscillation
> (iii) Value of Critical Resistance which will give no transient oscillations
> (iv) The value of resistance which when connected across circuit breaker contacts will give damped frequency of oscillation of one-fourth of the natural frequency of oscillation. [20]
> 
> (c) Show how unit protection principle can be employed in balanced voltage system. [10]

---
