[EE2-2022-Q1a] EE Core · Control Systems
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q1a | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Control Systems
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(a) A closed-loop system is shown in the figure below. The maximum overshoot for the system is 40% and the peak time is 2 seconds. Calculate the values of A and B. Consider $J=1\text{ kg-m}^{2}$: [10]

**Figure ID:** FIG-EE2-2022-Q1a
**Circuit description (netlist form):** Closed-loop control block diagram. Input $R(s)$ enters a first summing junction with negative feedback from the output $C(s)$. The error signal feeds a second summing junction with inner negative feedback from a block of gain $B$. The resulting signal is applied to block $\frac{A}{Js}$, whose output feeds the feedback block $B$ and an integrator $\frac{1}{s}$ to yield output $C(s)$.
**Symbolic form:** $$\frac{C(s)}{R(s)}=\frac{A}{Js^2 + ABs + A}$$



[EE2-2022-Q1b] EE Core · Control Systems
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q1b | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Control Systems
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(b) Draw the Nyquist plot for the system shown below. Using Nyquist stability criterion, determine the range of K for which the system is stable. Assume $K\in\mathbb{R}$ (set of real numbers): [10]

**Figure ID:** FIG-EE2-2022-Q1b
**Circuit description (netlist form):** Closed-loop feedback system. Input $R$ enters a summing junction $\Sigma$ with negative feedback. The error signal passes through gain block $K$ and forward transfer function $\frac{1}{s^2+2s+2}$ to produce output $Y$. Output $Y$ is fed back to the summing junction through feedback block $\frac{1}{s+1}$.
**Symbolic form:** $$G(s)H(s)=\frac{K}{(s^2+2s+2)(s+1)}$$



[EE2-2022-Q1c] EE Core · Control Systems
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q1c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Control Systems
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) Show an instruction cycle with possible machine cycles and clock cycles (T-states) in it, for the microprocessor 8085. If the processor is working at 3 MHz, calculate the minimum and maximum possible execution time for an instruction. [10]



[EE2-2022-Q1d] EE Core · Control Systems
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q1d | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Control Systems
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(d) The distributed capacitance of a coil is resonated at 10 MHz with 100 pF in parallel and is then again resonated at twice the frequency with 16 pF. Calculate its equivalent distributed capacitance and the inductance of the coil. [10]



[EE2-2022-Q1e] EE Core · Control Systems
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q1e | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Control Systems
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(e) In a symmetrical three-phase system supplying a balanced load of 28 A at 400 V, a wattmeter reading is 5 kW, when its current coil is connected in the red phase and its voltage coil is connected between the neutral and red phase. Determine the instrument reading for the phase sequence RYB, if the voltage coil is connected between the blue and yellow phases. (The current coil remains unchanged) [10]

---


[EE2-2022-Q2a] EE Core · Steady-State Error & Stability
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q2a | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Steady-State Error & Stability
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(a) A unity feedback system is shown in the figure below. Determine the range of $\alpha$ for which the system is stable and the steady-state error for unit step input is less than 5%: [20]

**Figure ID:** FIG-EE2-2022-Q2a
**Circuit description (netlist form):** A unity negative feedback control system with input $R(s)$ entering a summing junction and error driving forward block with transfer function $\frac{s+\alpha}{s^3+(1+\alpha)s^2+(\alpha-1)s+(1-\alpha)}$ to output $C(s)$, with direct unity feedback to the summing junction.
**Symbolic form:** $$G(s)=\frac{s+\alpha}{s^3+(1+\alpha)s^2+(\alpha-1)s+(1-\alpha)},\quad H(s)=1$$



[EE2-2022-Q2b] EE Core · Steady-State Error & Stability
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q2b | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Steady-State Error & Stability
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) Explain each step of the assembly language program given below for microprocessor 8085 and calculate the total time taken by the processor in its execution if the processor is working at 3 MHz. (The number of clock cycles for instructions is given in the table for reference): [20]

```assembly
LXI SP, 5000 H
LXI D, 00F9 H
CALL SUBROUTINE 1
HLT
SUBROUTINE 1: DCX D
              MOV A, D
              ORA E
              JNZ SUBROUTINE 1
              RET
```

| Instruction | Clock cycle |
| :--- | :--- |
| LXI | 10 |
| CALL | 18 |
| DCX D | 6 |
| MOV A, D | 4 |
| ORA E | 4 |
| JNZ | $7/10$ (for $Z=1$ or 0) |
| RET | 10 |



[EE2-2022-Q2c] EE Core · Steady-State Error & Stability
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q2c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Steady-State Error & Stability
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) A resistance strain gauge having a resistance of $100\ \Omega$ and gauge factor of 2 is connected in series to a load resistance of $200\ \Omega$ across 24 volts. The modulus of elasticity is $200\text{ GN/m}^{2}$. Calculate the change in output voltage due to the applied stress of $120\text{ MN/m}^{2}$. [10]

---


[EE2-2022-Q3ai] EE Core · Shunt Ohmmeter Design
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q3ai | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Shunt Ohmmeter Design
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(a) (i) The figure below shows a schematic diagram of shunt ohmmeter. It consists of a battery in series with an adjustable resistance $R_{1}$ and a d.c. measuring PMMC ammeter. The unknown resistance $R_{x}$ to be measured is connected across the terminals A-B. S is the off-on switch. Write down its design equations. What are your observations when the terminals A-B are shorted and open-circuited? [10]

**Figure ID:** FIG-EE2-2022-Q3ai
**Circuit description (netlist form):** Shunt ohmmeter circuit. DC voltage source $E$ in series with variable resistor $R_1$ supplying current $I_1$. Across parallel terminals A and B, a basic PMMC meter with internal resistance $R_m$ carrying meter current $I_m$ is connected. Unknown resistor $R_x$ is connected across terminals A-B. Switch S is placed in the bottom return line.
**Symbolic form:** not derivable from figure.



[EE2-2022-Q3aii] EE Core · Shunt Ohmmeter Design
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q3aii | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Shunt Ohmmeter Design
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(a) (ii) Determine the value of the resistor in series with the battery to adjust the full-scale deflection and the point (in %) of full scale at which $100\ \Omega$ will be marked on the scale. Consider the e.m.f. of internal battery as 2 volts, full-scale current of 2 mA and an internal resistance of $20\ \Omega$. [10]



[EE2-2022-Q3b] EE Core · Shunt Ohmmeter Design
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q3b | Marks: Unknown | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Shunt Ohmmeter Design
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) Consider the system
$$\dot{\overline{x}}=\begin{bmatrix}0& 16& 0& 0\\ -1& -8& 0& 0\\ 4& 8& 1& 15\\ 0& 0& 3& -3\end{bmatrix}\overline{x}+\begin{bmatrix}0\\ 0\\ 1\\ 0\end{bmatrix}u$$


[EE2-2022-Q3i] EE Core · Shunt Ohmmeter Design
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q3i | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Shunt Ohmmeter Design
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(i) Find the eigenvalues of this system.
(ii) Find the controllable and uncontrollable modes of this system.
(iii) Show that there are an infinite number of feedback gains K that will relocate the modes of the system to 5, -3, 4, 4.
(iv) Find the unique matrix $\overline{K}$ that achieves these pole locations and prevents initial conditions on the uncontrollable part of the system from ever affecting the controllable part. [20]



[EE2-2022-Q3ci] EE Core · Shunt Ohmmeter Design
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q3ci | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Shunt Ohmmeter Design
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) (i) Explain the use of MAR in interfacing the external memory to processor. [10]



[EE2-2022-Q3cii] EE Core · Shunt Ohmmeter Design
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q3cii | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Shunt Ohmmeter Design
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) (ii) Name various 8-bit and 16-bit internal registers in microprocessor 8085 and also, indicate which 8-bit registers can be paired to act as 16-bit register in several instructions. [10]

---


[EE2-2022-Q4ai] EE Core · 8085 Interrupts & SIM
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q4ai | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): 8085 Interrupts & SIM
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(a) (i) List various interrupts in microprocessor 8085 in order of decreasing priority. Specify which of these are edge-sensitive and which are level-sensitive.
Explain why TRAP is having good noise immunity as compared to other interrupts.
(ii) What will be the action of running the given assembly program segment?
```assembly
MVI A, 0B H
SIM
``` [20]



[EE2-2022-Q4b] EE Core · 8085 Interrupts & SIM
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q4b | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): 8085 Interrupts & SIM
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(b) The values of the components in the Maxwell bridge for balance condition are shown below in the circuit diagram. Write the balance equation and calculate the values of $L_{s}$, $R_{s}$ and Q for the unknown sample coil: [20]

**Figure ID:** FIG-EE2-2022-Q4b
**Circuit description (netlist form):** Maxwell inductance-capacitance AC bridge driven by a $5\text{ V AC}$, $100\text{ Hz}$ supply. Arm 1 (top-left) contains resistor $R_1 = 1\text{K}6$ ($1600\ \Omega$). Arm 2 (top-right) contains the unknown sample coil modeled as series inductance $L_s$ and series resistance $R_s$. Arm 3 (bottom-left) contains parallel combination of variable resistor $R_3 = 400\text{E}$ ($400\ \Omega$) and variable capacitor $C_3 = 0\cdot2\ \mu\text{F}$. Arm 4 (bottom-right) contains resistor $R_4 = 500\text{E}$ ($500\ \Omega$). A detector D is connected between the intermediate nodes.
**Symbolic form:** not derivable from figure.



[EE2-2022-Q4c] EE Core · 8085 Interrupts & SIM
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q4c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): 8085 Interrupts & SIM
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(c) Determine the transfer function $C(s)/R(s)$ for the signal flow graph of the system shown below using Mason's gain formula: [10]

**Figure ID:** FIG-EE2-2022-Q4c
**Circuit description (netlist form):** Signal flow graph with input node $R(s)$ and output node $C(s)$. Forward path passes sequentially through nodes 1, 2, 3, 4 via branches with gains $G_1(s)$, $G_2(s)$, $G_3(s)$, and $G_4(s)$. Feedback loops include: a self-loop of gain $-1$ at node 1; a feedback branch of gain $-1$ from node 4 to node 3; a feedback branch of gain $-1$ from node 4 to node 2; and a feedback branch of gain $-1$ from node 4 to node 1.
**Symbolic form:** not derivable from figure.

---

## SECTION B


[EE2-2022-Q5a] EE Core · Transmission Line Inductance
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q5a | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Transmission Line Inductance
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(a) Determine the inductance of a single-phase transmission line consisting of three conductors of 2 cm radii in the 'go' conductor and two conductors of 4 cm radii in the 'return' conductor as shown in the figure below: [10]

**Figure ID:** FIG-EE2-2022-Q5a
**Circuit description (netlist form):** Spatial layout diagram for a single-phase composite transmission line. Composite conductor A ('go') comprises three conductors $a, b, c$ arranged in a vertical line with $4\text{ m}$ spacing between $a$ and $b$, and $4\text{ m}$ spacing between $b$ and $c$, each having radius $2\text{ cm}$. Composite conductor B ('return') comprises two conductors $a', b'$ arranged in a vertical line with $4\text{ m}$ spacing, horizontally separated from conductor A by $6\text{ m}$, each having radius $4\text{ cm}$.
**Symbolic form:** not derivable from figure.



[EE2-2022-Q5b] EE Core · Transmission Line Inductance
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q5b | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Transmission Line Inductance
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(b) The schematic diagram of a radial transmission system is shown in the figure below. The ratings and reactances of various components are shown therein. A load of 60 MW at 0.9 power factor lagging is tapped from 66 kV substation which is to be maintained at 60 kV. Calculate the terminal voltage of the synchronous generator: [10]

**Figure ID:** FIG-EE2-2022-Q5b
**Circuit description (netlist form):** Single-line diagram of a power system. A synchronous generator with terminal voltage $V_1$ is connected to a step-up transformer rated $11/220\text{ kV}$, $100\text{ MVA}$, $X=12\%$. The transformer connects to a transmission line with reactance $j100\ \Omega$, which feeds a step-down transformer rated $220/66\text{ kV}$, $100\text{ MVA}$, $X=10\%$. The secondary bus has voltage $V_2 = 60\text{ kV}$ supplying a load of $60\text{ MW}$ at $0\cdot9$ pf lagging.
**Symbolic form:** not derivable from figure.



[EE2-2022-Q5c] EE Core · Transmission Line Inductance
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q5c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Transmission Line Inductance
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) Explain how arc is initiated and sustained in a circuit breaker when the circuit breaker contact separates. Also, derive an expression for the restriking voltage in terms of system voltage, inductance and capacitance, across the circuit breaker contacts. (Assume that the neutral of the system is solidly grounded) [10]



[EE2-2022-Q5d] EE Core · Transmission Line Inductance
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q5d | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Transmission Line Inductance
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(d) Show that, with a non-uniform quantizer, the mean square value of the quantization error is approximately equal to $\frac{1}{12}\sum_{i}\Delta_{i}^{2}p_{i}$, where $\Delta_{i}$ is the ith step size and $p_{i}$ is the probability that the input signal amplitude lies within the ith interval. Assume that the step size $\Delta_{i}$ is small compared with the excursion of the input signal. [10]



[EE2-2022-Q5e] EE Core · Transmission Line Inductance
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q5e | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Transmission Line Inductance
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(e) Prove that all vectors in the same coset have the same syndrome that is unique to that coset in the standard array for any linear block code. [10]

---


[EE2-2022-Q6a] EE Core · Long Transmission Line Analysis
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q6a | Marks: Unknown | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Long Transmission Line Analysis
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(a) A three-phase, 50 Hz transmission line is 400 km long. The voltage at the sending end is 220 kV. The line parameters are $r=0\cdot125\ \Omega\text{/km}$, $x=0\cdot4\ \Omega\text{/km}$ and $y=2\cdot8\times10^{-6}\text{ mho/km}.$


[EE2-2022-Q6i] EE Core · Long Transmission Line Analysis
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q6i | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Long Transmission Line Analysis
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(i) Find the sending-end current and receiving-end voltage when there is no load on the line. Comment on the result.
(ii) Find the maximum permissible line length if the receiving-end no-load voltage is not to exceed 230 kV.
(iii) Find the maximum permissible line frequency if the no-load voltage is not to exceed 250 kV. [20]



[EE2-2022-Q6bi] EE Core · Long Transmission Line Analysis
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q6bi | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Long Transmission Line Analysis
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) (i) Two 11 kV, 25 MVA, three-phase, star-connected generators $G_{1}$ and $G_{2}$ operate in parallel. The positive, negative and zero sequence reactances of each generator are j0.09 pu, j0.05 pu and j0.04 pu respectively. A single line to ground fault occurs at the terminals of one of the generators. Find the fault current in pu. Also, find the voltage across the grounding resistor $R_{n}$ in pu. Assume that the neutral of only generator $G_{1}$ is grounded through a resistor $R_{n}=1\ \Omega$. [10]



[EE2-2022-Q6bii] EE Core · Long Transmission Line Analysis
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q6bii | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Long Transmission Line Analysis
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) (ii) A 50 Hz, 11 kV, three-phase synchronous generator with earthed neutral has a reactance of $4\ \Omega\text{/phase}$ and is connected to a busbar through a circuit breaker (CB). The capacitance to earth for the CB and generator is $0\cdot02\ \mu\text{F}$ per phase, and resistance may be ignored. Find the maximum voltage across the contacts of the circuit breaker, frequency of the transient oscillation and the average rate of rise of restriking voltage up to the first peak of the oscillation. [10]



[EE2-2022-Q6c] EE Core · Long Transmission Line Analysis
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q6c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Long Transmission Line Analysis
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) Find the capacity of the cascade connection of n binary symmetric channels with the same crossover probability $p$. What is the capacity when the number of channels goes to infinity? [10]

---


[EE2-2022-Q7a] EE Core · Convolutional Encoder
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q7a | Marks: Unknown | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Convolutional Encoder
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(a) The figure below shows the encoder for a rate $r=\frac{1}{2},$ constraint length $k=4$ convolutional code :


[EE2-2022-Q7i] EE Core · Convolutional Encoder
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q7i | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Convolutional Encoder
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(i) Determine the encoder output produced by the message sequence 11011
(ii) Also, construct the code tree for the encoder. Trace the path through the tree that corresponds to the message 11011 .... Compare the resulting output with that determined in (i). [20]

**Figure ID:** FIG-EE2-2022-Q7a
**Circuit description (netlist form):** Rate 1/2 convolutional encoder consisting of 3 flip-flop shift register stages (F/F). The input stream and taps from stages 2 and 3 are connected to an upper Modulo-2 adder to generate output $g^{(1)}(x)$. The input stream and taps from stages 1 and 3 are connected to a lower Modulo-2 adder to generate output $g^{(2)}(x)$. A commutator switch samples $g^{(1)}(x)$ and $g^{(2)}(x)$ alternately to yield the serial coded output.
**Symbolic form:** $$g^{(1)}=(1,0,1,1),\quad g^{(2)}=(1,1,0,1)$$



[EE2-2022-Q7bi] EE Core · Convolutional Encoder
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q7bi | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Convolutional Encoder
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) (i) Explain in brief about the necessity of automatic load frequency control in the power generating system. Draw the schematic diagram of load frequency and voltage control regulators. [10]



[EE2-2022-Q7bii] EE Core · Convolutional Encoder
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q7bii | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Convolutional Encoder
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) (ii) Two generators rated 200 MW and 400 MW are operating in parallel. The droop characteristics of their governors are 4% and 6% respectively from no load to full load. Assuming that the governors are operating at 50 Hz at no load, how would a load of 600 MW be shared between them? What would be the corresponding system frequency at this load? Assume free governor operation. [10]



[EE2-2022-Q7c] EE Core · Convolutional Encoder
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q7c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): Convolutional Encoder
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) Explain in brief about different types of HVDC links, their advantages and disadvantages. [10]

---


[EE2-2022-Q8a] EE Core · IDMT & Earth Fault Relays
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q8a | Marks: Unknown | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): IDMT & Earth Fault Relays
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(a) Answer the following:


[EE2-2022-Q8i] EE Core · IDMT & Earth Fault Relays
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q8i | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): IDMT & Earth Fault Relays
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(i) Write the recommended expression for time-current relationship of standard IDMT relay and draw its characteristic curve. Why is this type of relay commonly used for protection of electrical machines?
(ii) Draw the circuit arrangements for connecting earth fault relay in $3\phi$ supply and explain its working for core balance current transformer as well as for three CT system. [20]



[EE2-2022-Q8b] EE Core · IDMT & Earth Fault Relays
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q8b | Marks: Unknown | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): IDMT & Earth Fault Relays
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(b) The received signal in a binary communication system that employs antipodal signals is $r(t)=s(t)+n(t)$ where $s(t)$ is shown in the figure below and $n(t)$ is AWGN with power spectral density $\frac{N_{0}}{2}\frac{\text{W}}{\text{Hz}}$ :


[EE2-2022-Q8i] EE Core · IDMT & Earth Fault Relays
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q8i | Marks: 20 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): IDMT & Earth Fault Relays
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: yes
(i) Sketch the impulse response of the filter matched to $s(t)$.
(ii) Sketch the output of the matched filter when the input is s(t).
(iii) Determine the variance of the noise at the output of the matched filter at $t=3$.
(iv) Determine the probability of error as a function of A and $N_{0}$. [20]

**Figure ID:** FIG-EE2-2022-Q8b
**Circuit description (netlist form):** Plot of baseband antipodal pulse signal $s(t)$ versus time $t$. The signal has amplitude $A$ from $t=0$ to $t=1$, amplitude 0 from $t=1$ to $t=2$, amplitude $A$ from $t=2$ to $t=3$, and is 0 elsewhere.
**Symbolic form:** $$s(t) = A[u(t)-u(t-1)] + A[u(t-2)-u(t-3)]$$



[EE2-2022-Q8c] EE Core · IDMT & Earth Fault Relays
Exam: UPSC Mains 2022 | Paper: EE2 | Q.No: Q8c | Marks: 10 | Words: none
Syllabus: UNMAPPED
Directive: Calculate/Solve
Theme (primary): IDMT & Earth Fault Relays
Theme (secondary): Technical Application
Repeat cluster: none
Has figure: no
(c) Find the steady-state power limit of a system consisting of a generator having equivalent reactance of 0.5 pu, connected to an infinite bus through a series reactance of 1.0 pu. The terminal voltage of the generator is held at 1.20 pu and the voltage of the infinite bus at 1.0 pu. [10]
