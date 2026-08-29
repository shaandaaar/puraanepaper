### [EE1-2012-Q1] Two-Port Transmission (ABCD) Parameters · Fourier Transform Duality, Sampling Theorem, Transmission-Line Losses & Op-Amp Impedance

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 1 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Two-port networks.
- **Directive:** Determine
- **Theme (primary):** Two-Port Transmission (ABCD) Parameters
- **Theme (secondary):** Fourier Transform Duality, Sampling Theorem, Transmission-Line Losses & Op-Amp Impedance
- **Repeat cluster:** RC13 (Two-Port Network Parameters)
- **Has figure:** yes

> **SECTION-A**
> 
> 1. (a) Determine the transmission matrix for the circuit shown and explain why open circuit impedance parameters can not be defined for this circuit. [12]
> 
> **Figure ID:** FIG-EE1-2012-Q1a
> **Circuit description (netlist form):** Two-port network with input port terminals (+, -) having voltage $V_1$ and current $i_1$ entering the positive terminal, and output port terminals (+, -) having voltage $V_2$ and current $i_2$ entering the positive terminal. An impedance $Z$ is connected in series between the positive terminal of port 1 and the positive terminal of port 2. The negative terminal of port 1 is directly connected to the negative terminal of port 2 via a continuous reference conductor.
> **Symbolic form:** $\begin{bmatrix} V_1 \\ I_1 \end{bmatrix} = \begin{bmatrix} 1 & Z \\ 0 & 1 \end{bmatrix} \begin{bmatrix} V_2 \\ -I_2 \end{bmatrix}$
> 
> (b) Using duality property show that the Fourier transform of $[\frac{1}{1+j2\pi t}]$ is equal to $e^f u(-f)$ where $u(t)$ is the unit step. [12]
> 
> (c) A continuous time signal is given by
> $$x(t) = A \cos (8000 \pi t) \cos (2000 \pi t)$$
> The signal is sampled with a sample period of $3 \times 10^{-4}$ seconds. Can we recover the signal from the sampled version using an appropriate low pass filter ? [12]
> 
> (d) A lossless transmission line having a length of 100 metre is terminated by a resistive load of 200 ohms. It is fed by a generator of voltage $\angle 0^\circ$ volts and has impedance 100 ohms. If characteristic impedance of the line is 300 ohms, calculate the transmission loss and return loss in decibels. [12]
> 
> (e) Assuming ideal op-amps, determine the expression for the input impedance of the given circuit and a simple passive equivalent of the circuit looking into terminal . [12]
> 
> **Figure ID:** FIG-EE1-2012-Q1e
> **Circuit description (netlist form):** Circuit with two operational amplifiers. Input terminal pair (+, -) has input voltage $V_{in}$ and input current $i_{in}$ entering the non-inverting input (+) of the first op-amp. The inverting input (-) of the first op-amp is connected directly to its output terminal. Output of the first op-amp is connected via capacitor $C_0$ to the non-inverting input (+) of the second op-amp. Resistor $R_1$ is connected between the non-inverting input (+) of the second op-amp and the bottom reference terminal (-). Resistor $R_2$ is connected between the top input terminal and the inverting input (-) of the second op-amp. The inverting input (-) of the second op-amp is connected directly to its output terminal.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2012-Q2] Resonance Condition in a Parallel RL–RC Network · Cascaded-System Impulse Response & Widlar Current Source

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 2 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits.
- **Directive:** Show
- **Theme (primary):** Resonance Condition in a Parallel RL–RC Network
- **Theme (secondary):** Cascaded-System Impulse Response & Widlar Current Source
- **Repeat cluster:** RC04 (Resonant/Transient Circuits)
- **Has figure:** yes

> 2. (a) Show that there can be no value of $R_L$ in the circuit given in Fig. that will make it resonant. [20]
> 
> **Figure ID:** FIG-EE1-2012-Q2a
> **Circuit description (netlist form):** Two-terminal parallel network. Branch 1 contains a variable resistor $R_L$ connected in series with an inductor having an inductive reactance of $j10\text{ ohm}$. Branch 2, connected in parallel across Branch 1, contains a resistor of $4\ \Omega$ connected in series with a capacitor having a capacitive reactance of $-j5\ \Omega$.
> **Symbolic form:** not derivable from figure.
> 
> (b) A system consists of two blocks connected in cascade. The first block has impulse response $h_1(t) = 2u(t)$. The second block is shown below :
> 
> **Figure ID:** FIG-EE1-2012-Q2b
> **Circuit description (netlist form):** Two-port L-section network. Series branch between the top input terminal and top output terminal consists of an inductor $L$. Shunt branch connected between the top output terminal and the bottom reference rail consists of a capacitor labeled $R$. Bottom input terminal is connected directly to the bottom output terminal.
> **Symbolic form:** not derivable from figure.
> 
> Find the impulse response of the overall system using the relation
> $$h(t) = h_1(t) * h_2(t).$$ [20]
> 
> (c) Determine the output current of the Widlar current source; given that $\pm V = \pm 15\text{ volts}$, $I_{C_0} = 10^{-14}\text{ amp.}$, $\beta = 200$, $V_T = 25\text{ mV}$. [20]
> 
> **Figure ID:** FIG-EE1-2012-Q2c
> **Circuit description (netlist form):** Widlar current source circuit. Diode-connected PNP BJT $Q_1$ has its emitter connected to $+V$, and its base shorted to its collector. Collector of $Q_1$ is connected through a $39\text{ k}\Omega$ resistor to the collector of NPN BJT $Q_2$. Transistor $Q_2$ has its collector connected to its base, its emitter connected to $-V$, and its reference collector current denoted as $I_{in}$. Base of $Q_2$ is connected to the base of NPN BJT $Q_3$. Transistor $Q_3$ has its emitter connected to $-V$ through a $5\text{ k}\Omega$ resistor, and its collector carries the output current $I_o$.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2012-Q3] Two-Port Y/Z Parameters & Tellegen's Theorem · EM Plane-Wave Propagation in a Lossless Dielectric & Op-Amp Oscillator Design

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 3 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Two-port networks.
- **Directive:** Find
- **Theme (primary):** Two-Port Y/Z Parameters & Tellegen's Theorem
- **Theme (secondary):** EM Plane-Wave Propagation in a Lossless Dielectric & Op-Amp Oscillator Design
- **Repeat cluster:** RC13 (Two-Port Network Parameters)
- **Has figure:** yes

> 3. (a) (i) Find Y and Z parameters for the following circuit : [20]
> 
> **Figure ID:** FIG-EE1-2012-Q3ai
> **Circuit description (netlist form):** Two-port network. Port 1 has voltage $V_1$ across terminals (+, -) and current $I_1$ entering the positive terminal. Port 2 has voltage $V_2$ across terminals (+, -) and current $I_2$ entering the positive terminal. The positive terminal of Port 1 connects to the positive terminal of a current-dependent voltage source of value $5I_2$. The negative terminal of the source connects to an internal node. A resistor of $2\ \Omega$ is connected between this internal node and the positive terminal of Port 2. The internal node is connected directly to the common ground/bottom reference rail connecting the negative terminals of Port 1 and Port 2.
> **Symbolic form:** not derivable from figure.
> 
> (ii) State Tellegen's theorem for network analysis.
> 
> (b) A particular lossless material has $\mu_r = 4$ and $\epsilon_r = 9$. A 10 MHz uniform plane wave is propagating in the $a_y$ direction with $E_{x_0} = 400\text{ V/m}$ and $E_{y_0} = E_{z_0} = 0$ at $P(0\cdot6, 0\cdot6, 0\cdot6)$ at $t = 60\text{ ns}$.
> Determine :-
> (i) $\beta, \lambda, v_p$ and $\eta$
> (ii) $E(t)$
> (iii) $H(t)$. [20]
> 
> (c) Figure shows a sinusoidal oscillator. By an appropriate analysis, determine the condition of oscillation and frequency of oscillation in terms of circuit elements assuming ideal op-amps. [20]
> 
> **Figure ID:** FIG-EE1-2012-Q3c
> **Circuit description (netlist form):** Three op-amp oscillator circuit. Stage 1 op-amp: inverting input (-) connected to resistor $R_o$ from overall output $V_o$ feedback and feedback resistor $R_o$ to its output; non-inverting input (+) connected to capacitor $C_1$ in parallel with resistor $R_1$ to ground, with input fed from overall output $V_o$. Stage 2 op-amp: inverting input (-) connected to resistor $R_o$ from stage 1 output and feedback resistor $R_o$ to its output; non-inverting input (+) connected to capacitor $C_2$ in parallel with resistor $R_2$ to ground, fed from stage 1 output. Stage 3 op-amp: inverting amplifier with resistor $R_3$ from stage 2 output to inverting input (-), feedback resistor $R_4$ from output $V_o$ to inverting input (-), and non-inverting input (+) connected to ground. Output $V_o$ feeds back to the inputs of Stage 1.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2012-Q4] Discrete-Time System Transfer Function H(z) · Transmission-Line VSWR/Loss Parameters & Op-Amp Astable Multivibrator

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 4 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Fourier transform, Laplace transform, Z-transform, Transfer function.
- **Directive:** Determine
- **Theme (primary):** Discrete-Time System Transfer Function H(z)
- **Theme (secondary):** Transmission-Line VSWR/Loss Parameters & Op-Amp Astable Multivibrator
- **Repeat cluster:** RC02 (Transform Techniques (Laplace/Fourier/Z))
- **Has figure:** yes

> 4. (a) The block diagram of a discrete time LTI system is given below :
> 
> **Figure ID:** FIG-EE1-2012-Q4a
> **Circuit description (netlist form):** Discrete-time system block diagram. Input $x(n)$ enters an input summing node. The output of this summing node passes through a cascade of two unit delay blocks $z^{-1}$; feedback from after the first delay through gain $-1/3$ and after the second delay through gain $1/6$ are added into the input summing node. The output of the input summing node branches into two parallel feedforward paths: Path 1 has gain $2/3$ into a recursive block with feedback delay $z^{-1}$ through gain $-1/3$; Path 2 has gain $1/3$ into a recursive block with feedback delay $z^{-1}$ through gain $1/6$. The outputs of both paths are summed at an output adder to produce $y(n)$.
> **Symbolic form:** not derivable from figure.
> 
> Determine the transfer function $H(z)$. [20]
> 
> (b) A 50 ohm lossless line connects a matched signal of 100 kHz to a load of 100 ohm. Load power is 100 mW. Estimate:
> (i) Voltage reflection coefficient of load.
> (ii) VSWR of the load.
> (iii) Position of first $V_{min}$ and $V_{max}$.
> (iv) Impedance at $V_{max}$ and $V_{min}$ and values of $V_{max}$ and $V_{min}$.
> Define the terms Attenuation loss, Reflection loss, Transmission loss, Return loss and Insertion loss. [20]
> 
> (c) Explain the operation of the given circuit by sketching relevant waveforms assuming that positive and negative saturation levels of output voltage of the op-amp comparator are $+V_{sat_1}$ and $-V_{sat_2}$ respectively and are not equal. Determine an expression for the frequency of the generated output voltage. [20]
> 
> **Figure ID:** FIG-EE1-2012-Q4c
> **Circuit description (netlist form):** Op-amp astable multivibrator circuit. Inverting input (-) connected to ground through capacitor $C$ and to output terminal $V_o$ through resistor $R$. Non-inverting input (+) connected to ground through resistor $R_a$ and to output terminal $V_o$ through resistor $R_b$. Op-amp powered by $+V$ and $-V'$ rails. Output voltage is $V_o$.
> **Symbolic form:** not derivable from figure.

---

### [EE1-2012-Q5] D-to-SR Flip-Flop Conversion · Number-Base Conversion, AC Machine EMF Induction, Boost Converter & PDF Verification

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 5 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Sequential circuits: latches and flip-flops, counters and shift-registers.
- **Directive:** Show
- **Theme (primary):** D-to-SR Flip-Flop Conversion
- **Theme (secondary):** Number-Base Conversion, AC Machine EMF Induction, Boost Converter & PDF Verification
- **Repeat cluster:** RC14 (Sequential Logic (Flip-Flops/Counters))
- **Has figure:** no

> **SECTION-B**
> 
> 5. (a) Show how a D flip-flop can be converted to SR flip-flop. [12]
> 
> (b) Convert decimal 65,535 to its hexadecimal and binary. [12]
> 
> (c) A 2-pole full pitch concentrated coil of n turns is placed in the stator of an electric machine in two slots diagonally opposite to each other. A permanent magnet 2-pole rotor is rotating at N rpm producing a flux per pole with its flux density sinusoidally varying in space in the airgap. At time $t=0$ rotor field axis is in line with the stator coil axis. Write an expression for the flux linking the stator coil as a function of time. Derive from this expression the r.m.s. value of the voltage induced in the stator coil. Draw the waveform of flux linkage and voltage generated. Write expression for frequency of voltage in terms of speed. [12]
> 
> (d) Draw the simplified circuit diagram for a voltage step-up DC-converter and show that when duty cycle is zero, the output of DC-converter is equal to source voltage whereas DC voltage is infinity if the duty cycle is unity. [12]
> 
> (e) Evaluate whether the following function given by expression
> $$f_X(x) = \begin{cases} 0 & \text{for } x < 2 \\ \frac{1}{18}(3+2x) & \text{for } 2 \le x \le 4 \\ 0 & \text{for } x > 4 \end{cases}$$
> is a probability density function (PDF). [12]

---

### [EE1-2012-Q6] Flip-Flop Requirements for Modulo-N Counters · Auto-Transformer Rating Conversion & Superheterodyne Spurious Response

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 6 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Sequential circuits: latches and flip-flops, counters and shift-registers.
- **Directive:** Indicate
- **Theme (primary):** Flip-Flop Requirements for Modulo-N Counters
- **Theme (secondary):** Auto-Transformer Rating Conversion & Superheterodyne Spurious Response
- **Repeat cluster:** RC14 (Sequential Logic (Flip-Flops/Counters))
- **Has figure:** no

> 6. (a) Indicate how many flip-flops are required to construct each of the following counters:
> (i) mod-3
> (ii) mod 6
> (iii) mod-9. [20]
> 
> (b) Two winding 10 kVA, 500/50 V transformer is converted to an auto-transformer to obtain the rating of:
> (i) $550/50\text{ V}$,
> (ii) 500/550 V, and
> (iii) 500/450 V.
> Compute the kVA rating of auto transformer for the above connections, VA transferred conductivity and magnetically. [20]
> 
> (c) (i) Consider a superhet receiver with $f_{LO} = f_c + f_{IF}$, $f_{IF} = 455\text{ kHz}$, $f_c = 2\text{ MHz}$. The RF amplifier is preceded by a first order RLC band pass filter with $f_o = 2\text{ MHz}$ and $B = 0\cdot5\text{ MHz}$. Assume the IF-BPF is nearly ideal and mixer has unity gain. What is the minimum spurious frequency input rejection ratio in dB ? [10]
> 
> (ii) If the above receiver has a LO with a second harmonic whose voltage level is half that of the fundamental component, determine what input frequencies will be accepted and at what power level in dB as compared to the correct input. [20]

---

### [EE1-2012-Q7] Memory Addressing Schemes (Binary/Decimal/Hex) · Induction-Motor Soft-Starting, V/f Control & FM/AM Parameters

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 7 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** Semiconductor memories. Logic implementation using programmable devices (ROM, PLA, FPGA).
- **Directive:** Determine
- **Theme (primary):** Memory Addressing Schemes (Binary/Decimal/Hex)
- **Theme (secondary):** Induction-Motor Soft-Starting, V/f Control & FM/AM Parameters
- **Repeat cluster:** none
- **Has figure:** no

> 7. (a) What would be the binary address for a memory system having a capacity of $10^{24}$ bits. For the above memory system, what is the decimal address for the binary address 1011001101? What is the address in hexadecimal ? [20]
> 
> (b) (i) Explain with diagram the soft starting of induction motor to start from zero speed to rated speed. Briefly compare with a star-delta starter used for the same purpose.
> 
> (ii) A 3-phase, 4-pole 50 Hz induction motor is controlled by a variable frequency inverter that maintains the ratio of voltage to frequency across the motor constant. Torque-speed curve in stable region is a straight line. It has a maximum torque of 2 p.u. and slip speed at maximum torque at all frequency is constant at 150 rpm. Draw a family of Torque speed characteristics (on a graph paper) at 10, 20, 30, 40 & 50 Hz with usual assumptions. It is driving a load whose torque is directly proportional to speed giving rated torque at 50 Hz. Graphically calculate speeds at all the above frequencies. [20]
> 
> (c) (i) In an FM system, when the audio frequency (AF) is 500 Hz and AF voltage is 2.4 V, the deviation is 4.8 kHz. If the AF voltage is now increased to 7.2 V, what is the new deviation? If the AF voltage is raised to 10 V while AF is dropped to 200 Hz, what is the deviation? Evaluate modulation index in each case.
> 
> (ii) If $x(t) = \cos 200 \pi t$, determine AM transmission bandwidth $B_T$ and average transmitted power $S_T$ for the AM modulated signal assuming $A_c = 10$ and $\mu$ (modulation index) $= 0\cdot6$.
> What will be the values of $B_T$ and $S_T$ in the case of DSB transmission ? [20]

---

### [EE1-2012-Q8] DC Shunt Motor Response to Halved Terminal Voltage · Line-Commutated Inverter Computations & FM/AM Bandwidth-SNR Calculations

- **Exam:** UPSC Mains 2012 | **Paper:** EE Optional Paper I | **Q.No:** 8 | **Marks:** 60 | **Words:** N/A (no per-question word limit in this pre-2015 paper format)
- **Syllabus:** DC machines characteristics and performance analysis; starting and speed control of motors.
- **Directive:** Explain
- **Theme (primary):** DC Shunt Motor Response to Halved Terminal Voltage
- **Theme (secondary):** Line-Commutated Inverter Computations & FM/AM Bandwidth-SNR Calculations
- **Repeat cluster:** RC15 (DC Machine Characteristics)
- **Has figure:** no

> 8. (a) A d.c. shunt motor is driving a constant torque load. If the voltage across the motor is halved explain how the armature current and speed would be changed. [20]
> 
> (b) A 11 kV dc source having internal resistance of 1 ohm supplies 600 A to a 5 kV, 3 phase, 6-pulse 50 Hz inverter. Compute the :
> (i) reactive power absorbed by the inverter,
> (ii) effective value of the ac line current,
> (iii) the required firing angle,
> (iv) dc voltage generated by the inverter, and
> (v) dc current carried by each SCR. [20]
> 
> (c) (i) A commercial FM radio station alternates between music and talk show/call in formats. The broadcasted CD music is band limited to 15 kHz based on convention. Assuming D (deviation ratio) $= 5$ is used for both music and voice, what percentage of the available transmission bandwidth is used during the talk show if we take $W = 5\text{ kHz}$ for voice signals ?
> 
> (ii) An AM system with envelope detection has $(S/N)_D = 30\text{ dB}$ under full load tone modulation condition with $W = 8\text{ kHz}$. If all bandwidths are increased accordingly, while other parameters are held fixed, what is the largest usuable value of W? [20]

---
