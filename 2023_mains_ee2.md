[EE2-2023-Q1] Control Systems · Step Response
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 1 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Determine, Explain, Calculate
Theme (primary): System Dynamics
Theme (secondary): Power Circuit Breakers & Microprocessors
Repeat cluster: none
Has figure: yes
(a) The figure shows a unity feedback system. The steady-state value of the unit step response c(t) is 0.8. Determine the maximum overshoot in the response c(t): [10]
Figure ID: FIG-EE2-2023-Q1a
Circuit description (netlist form): A unity negative feedback control system with reference input u(t) entering a summing junction. The forward path transfer function is K/((s+1)(s+2)), producing output c(t) which is fed back negatively to the summing junction with unity feedback gain.
Symbolic form: C(s)/U(s) = K/(s^2 + 3s + 2 + K)

(b) A circuit breaker is rated as 2500 A, 1500 MVA, 33 kV, 3 sec, 3-phase, oil circuit breaker. Determine its rated normal current, breaking current, making current and short-time rating (current). [10]

(c) An audio signal, whose bandwidth is 15 kHz, is to be digitized using PCM. Uniform quantization with 1024 levels and binary encoding are assumed. Determine the minimum sampling rate. If the actual sampling rate is 20% excess of the minimum rate, determine the minimum permissible bit rate. [10]

(d) Briefly explain the following logical instructions of 8085 microprocessor:
(i) ANA M
(ii) XRA M
(iii) CMC
(iv) STC
(v) RRC [10]

(e) In a three-phase 400 km long transmission line, the conductors are spaced at the corners of an equilateral triangle of side 5 m. The diameter of each conductor is 3 cm. Calculate the capacitance per phase of the 400 km long conductor. [10]

[EE2-2023-Q2] Control Systems · Root Locus
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 2 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Sketch, What is, Find, Draw, Write, Derive, Determine, Calculate
Theme (primary): Stability Analysis
Theme (secondary): Instrumentation & Digital Comm
Repeat cluster: none
Has figure: yes
(a) The block diagram of a feedback system is shown in the figure.
(i) Sketch the complete root locus of the system.
(ii) What is the value of K at s=0?
(iii) Find the range of K for closed-loop stability. [20]
Figure ID: FIG-EE2-2023-Q2a
Circuit description (netlist form): A closed-loop feedback control system where input R(s) enters a summing junction (+ terminal). The forward path transfer function is K/((s-1)(s^2+4s+7)) producing output C(s). The feedback transfer function block is s+4 connected from C(s) back to the negative terminal of the summing junction.
Symbolic form: G(s)H(s) = K(s+4)/((s-1)(s^2+4s+7))

(b) Draw the connection diagram of a Schering bridge to measure the capacitance and dissipation factor. Write the balance equations and derive the formulae for finding the capacitance and dissipation factor. [20]

(c) A linear delta modulator is designed to transmit speech signal bandlimited to 4 kHz. The specifications are-
sampling rate =10 times Nyquist rate
step size =100 mV
The system is tested with 1 kHz sinusoidal signal. Determine the maximum amplitude of the test signal so that slope overload does not occur. Calculate the maximum power that can be transmitted without slope overload. [10]

[EE2-2023-Q3] Control Systems · State Space Analysis
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 3 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Write, Check, Differentiate, Discuss, Calculate
Theme (primary): Controllability and Observability
Theme (secondary): Microprocessor Addressing & Cables
Repeat cluster: none
Has figure: yes
(a) Write the state and output equations for the system shown in the figure. Choose state variables x_1 and x_2 as shown in the figure. Check the controllability and observability of the system: [20]
Figure ID: FIG-EE2-2023-Q3a
Circuit description (netlist form): A control system block diagram with input u entering an input summing junction (+) and feedback x_2 entering (-). The error signal feeds into two parallel forward paths: one through a block with transfer function -5/(s+4) to produce state variable x_1, and the other through a gain block of 1. The outputs of both forward blocks enter an output summing junction (+ and +) to yield system output y. The output y is fed into a feedback block 1/(s-1) whose output defines state variable x_2, which is fed back into the input summing junction.
Symbolic form: not derivable from figure.

(b) (i) Differentiate between full decoding and partial decoding techniques used by 8085 microprocessor to decode an address. Give advantages and disadvantages of each technique. [10]
(ii) Discuss with example how BCD number addition is performed using DAA instruction of 8085 microprocessor. [10]

(c) A 6600 V, 50 Hz, single-core, lead-sheathed cable has the following data:
Conductor diameter = 1.6 cm
Length = 5 km
Internal diameter of the sheath =3·2 cm
Resistivity of insulation =1.5×10^12 Ω-m
Relative permittivity of insulation =3·8
Calculate the insulation resistance, capacitance and the maximum electric stress in the insulation. [10]

[EE2-2023-Q4] Digital Communication · Linear Block Codes
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 4 | Marks: 50 | Words: N/A
Syllabus: Pulse code modulation (PCM), defferential pulse code modulation (DPCM), delta modulation (DM), Digital modulation and demodulation schemes: amplitude, phase and frequency keying schemes (ASK, PSK, FSK). Error control coding: error detection and correction, linear block codes, convolation codes. Information measure and source coding. Data networks, 7-layer architecture.
Directive: Find, How many, Determine, Explain
Theme (primary): Error Control Coding
Theme (secondary): Transmission Line Parameters
Repeat cluster: none
Has figure: no
(a) Consider a systematic linear block code with binary elements whose parity check equations are
p_1=m_1+m_2+m_3
p_2=m_2+m_3+m_4
p_3=m_1+m_3+m_4
p_4=m_1+m_2+m_4
where m_i are message digits and p_i are parity check digits.
(i) Find the generator matrix and parity check matrix for the code.
(ii) How many errors can this code detect? How many errors can be corrected?
(iii) If 10100100 is the received code word, find the corresponding transmitted code word assuming that single-bit error has been made during transmission. [20]

(b) A transmission line has the following parameters:
A=D=1∠5°, B=88∠75° Ω
(i) Determine the sending-end voltage and the voltage regulation if the line supplies a load of 40 MW at 0.8 p.f. lagging with receiving-end voltage 132 kV.
(ii) Find the power and power factor of the load if the voltages at the two ends are 132 kV and with a phase difference of 30°. [20]

(c) Explain four instructions which are used to control interrupt structure of 8085 microprocessor. [10]

[EE2-2023-Q5] Control Systems · Compensator Networks
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 5 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Determine, Calculate, Compute
Theme (primary): Attenuation
Theme (secondary): Transducers & Relay Protection
Repeat cluster: none
Has figure: yes
(a) The figure shows a compensator network, where R_1=3 MΩ, R_2=1 MΩ, C=1 μF. V_i(t) and V_0(t) are the input voltage and output voltage respectively. Determine the attenuation in dB provided by this network at very high frequencies: [10]
Figure ID: FIG-EE2-2023-Q5a
Circuit description (netlist form): A passive filter network with input voltage V_i(t) connected in series with resistor R_1 = 3 MΩ. The output voltage V_o(t) is measured across a parallel shunt branch consisting of a series combination of capacitor C = 1 μF and resistor R_2 = 1 MΩ.
Symbolic form: V_o(s)/V_i(s) = (s C R_2 + 1) / (s C (R_1 + R_2) + 1)

(b) A resistive strain gauge, with a gauge factor 2.2, is cemented on a rectangular steel bar with the elastic modulus, E=205×10^6 kN/m^2. The width and thickness of the steel bar is 3·5 cm and 0·55 cm respectively. An axial force of 12 kN is applied. If the nominal resistance of the strain gauge is 100 Ω, determine the change in resistance of the strain gauge. [10]

(c) A three-phase, 50 Hz, 415 V supply delivers 250 kW power at power factor of 0·8 lagging. The line power factor is desired to be improved to 0.9 lagging by installing shunt capacitors. Calculate the capacitance if they are connected in delta. [10]

(d) Binary data is transmitted over additive white Gaussian noise (AWGN) channel at a bit rate of 5 kilobits/sec. The single-sided power spectral density for the channel is 10^-7 W/Hz. Non-coherent orthogonal binary FSK with higher frequency signalling tone of 1 MHz is used. The bit energy, E_b=2×10^-6 J. Determine the minimum required bandwidth and average bit error probability. [10]

(e) Consider a three-phase, Δ-Y connected, 30 MVA, 33/11 kV transformer with differential relay protection. If the CT ratios are 500:5A on the primary side and 2000:5A on the secondary side, compute the relay current setting for faults drawing up to 200% of rated transformer current. [10]

[EE2-2023-Q6] Power Systems · Economic Load Dispatch
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 6 | Marks: 50 | Words: N/A
Syllabus: Steady-state performance of overhead transmission lines and cables; principles of active and reactive power transfer and distribution; per-unit quantities; bus admittance and impedance matrices; load flow; voltage control and power factor correction; economic operation; symmetrical components, analysis of symmetrical and unsymmetrical faults. Concepts of system stability: swing curves and equal area criterion. Static VAR system. Basic concepts of HVDC transmission.
Directive: Determine, Find, Write, Describe
Theme (primary): Optimal Generation
Theme (secondary): Microprocessor Interfacing & RLC Damping
Repeat cluster: none
Has figure: yes
(a) (i) A power system has two generators with the following cost curves:
Generator 1: C_1(P_g1)=0·008 P_g1^2+8P_g1+380 (thousand rupees/hour)
Generator 2: C_2(P_g2)=0·009 P_g2^2+7P_g2+430 (thousand rupees/hour)
The generator limits are
120 MW ≤ P_g1 ≤ 680 MW
60 MW ≤ P_g2 ≤ 550 MW
A load demand of 650 MW is supplied by the generators in an optimal manner. Determine the optimal generation of each generator, neglecting losses in the transmission network. [10]
(ii) A three-bus network is shown in the figure below, indicating the p.u. impedance of each element:
Figure ID: FIG-EE2-2023-Q6aii
Circuit description (netlist form): A 3-bus power system network. Bus 1 is connected to ground through an inductive impedance of j0·15 p.u. and to Bus 2 through an inductive impedance of j0·25 p.u. Bus 2 is connected to Bus 3 through a capacitive impedance of -j0·08 p.u. Bus 3 is connected to ground through an inductive impedance of j0·15 p.u.
Symbolic form: not derivable from figure.
Find the bus admittance matrix, Y_bus, of the network. [10]

(b) (i) Write the steps involved in DMA data transfer. Also describe the functions of 8085 pins which are used in DMA data transfer. [12]
(ii) Write an 8085 assembly language program to read and complement the contents of the flag register. [8]

(c) Find the value of R so that the system shown in the figure is critically damped. V_i(t) is the input voltage and output V_0(t) is the voltage across the capacitance. L=90 μH, C=120 nF: [10]
Figure ID: FIG-EE2-2023-Q6c
Circuit description (netlist form): A second-order series RLC network where input voltage V_i(t) is applied across the series combination of resistor R, inductor L = 90 μH, and shunt capacitor C = 120 nF. The output voltage V_o(t) is measured across capacitor C.
Symbolic form: V_o(s)/V_i(s) = 1 / (LCs^2 + RCs + 1)

[EE2-2023-Q7] Digital Communication · Source Coding
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 7 | Marks: 50 | Words: N/A
Syllabus: Pulse code modulation (PCM), defferential pulse code modulation (DPCM), delta modulation (DM), Digital modulation and demodulation schemes: amplitude, phase and frequency keying schemes (ASK, PSK, FSK). Error control coding: error detection and correction, linear block codes, convolation codes. Information measure and source coding. Data networks, 7-layer architecture.
Directive: Design, Determine, Find, What is, Derive, Draw
Theme (primary): Huffman Coding
Theme (secondary): Power System Relaying
Repeat cluster: none
Has figure: yes
(a) A discrete memoryless source generates three independent message symbols m_1, m_2 and m_3 with probabilities 0·9, 0·08 and 0·02 respectively.
(i) Design a binary variable length Huffman code. (Assign '0' to the message with highest probability). Determine the average code length, compression ratio and coding efficiency.
(ii) Design a binary first-order extension code for this source and find the average code length for the designed code. Determine the compression ratio and efficiency for the extended code. [20]

(b) What is the universal relay torque equation? Using this equation, derive the impedance relay, reactance relay and mho relay characteristics. Also draw the operating characteristic and indicate clearly the zones of operation and no operation. [20]

(c) A single-phase distributor ABC fed at A is shown in the figure below. The impedances of the sections AB and BC are same and equal to (0·15+j0·25) Ω. The power factors are lagging with respect to the voltage at the far end. If the voltage at the far end is 240 V, then determine the supply voltage and its phase angle with respect to the far end: [10]
Figure ID: FIG-EE2-2023-Q7c
Circuit description (netlist form): A single-phase AC distributor consisting of feeder point A, intermediate tap point B, and end point C. Section AB and section BC each have line impedance (0·15 + j0·25) Ω. A load of 150 A at 0·6 p.f. lagging is tapped at node B, and a load of 150 A at 0·8 p.f. lagging is connected at node C.
Symbolic form: not derivable from figure.

[EE2-2023-Q8] Control Systems · Frequency Response
Exam: UPSC Mains 2023 | Paper: EE2 | Q.No: 8 | Marks: 50 | Words: N/A
Syllabus: Elements of control systems; block-diagram representations; open-loop & closed-loop systems; principles and applications of feed-back. Control system components. LTI systems: time-domain and transform-domain analysis. Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion; Design of lead-lad compensators. Proportional, PI, PID controllers. State-variable representation and analysis of control systems.
Directive: Sketch, Determine, Find
Theme (primary): Polar Plot
Theme (secondary): Instrumentation & Short-Circuit Capacity
Repeat cluster: none
Has figure: yes
(a) The figure shows a unity feedback system with G(s)=2/(s(s+1)(s+2)(s+3)).
(i) Sketch the approximate polar plot of G(s).
(ii) Determine the closed-loop stability of the system using the polar plot of G(s).
(iii) Determine the gain margin of the system. [20]
Figure ID: FIG-EE2-2023-Q8a
Circuit description (netlist form): A unity negative feedback system block diagram with reference input R(s), forward open-loop transfer function block G(s), output C(s), and unity negative feedback connected from output to the input summing point.
Symbolic form: C(s)/R(s) = G(s)/(1+G(s))

(b) Two ammeters having resistances of 1 Ω and 2 Ω respectively give full-scale deflections with 200 mA and 250 mA respectively. Find the shunt to be connected with these ammeters to extend their range to 20 A. The range extended ammeters are connected in parallel and then placed in a circuit in which a total current of 15 A is flowing. Find the readings of the ammeters. [20]

(c) Two generating stations having short-circuit capacities of 1500 MVA and 1000 MVA respectively, and operating at 11 kV, are linked by an interconnected cable having a reactance of 0·72 Ω per phase. Determine the short-circuit capacity of each station after interconnection. [10]