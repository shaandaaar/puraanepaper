[EE1-2023-Q1] Circuits & Systems · Network Theorems & Transient Analysis
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 1 | Marks: 50 | Words: N/A
Syllabus: Circuit components; network graphs; KCL, KVL; Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications; transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits. Two-port networks.
Directive: Obtain, Find, Calculate, Prove
Theme (primary): Network Analysis & Energy Conversion
Theme (secondary): BJT Small Signal
Repeat cluster: none
Has figure: yes
(a) Obtain Norton equivalent circuit at terminals ab of the coupled circuit shown in the figure. Using it, find out the current passing through 5 Ω resistor connected between the terminals ab. [10]
Figure ID: FIG-EE1-2023-Q1a
Circuit description (netlist form): An AC circuit with an independent source 10∠0° V connected in series with a 4 Ω resistor and a j8 Ω coupled inductor to node 'a'. A second AC source 10∠90° V is connected in series with a 2 Ω resistor and a j4 Ω coupled inductor to node 'a'. The negative terminals of both sources connect to a common bottom reference wire, which connects directly to terminal 'b'. The mutual coupling between the j8 Ω and j4 Ω inductors is j5 Ω, with dot markings located at the source-side terminal of the j8 Ω inductor and at the resistor-side terminal of the j4 Ω inductor.
Symbolic form: not derivable from figure.

(b) Obtain the Laplace transform of the following periodic waveforms: [10]
(i)
Figure ID: FIG-EE1-2023-Q1bi
Circuit description (netlist form): A plot of periodic waveform f(t) versus time t. Over one period T = a, the signal rises linearly from 0 at t = 0 to 1 at t = a, drops instantaneously to 0 at t = a, and repeats periodically.
Symbolic form: f(t) = t/a, 0 ≤ t < a, f(t+a) = f(t)
(ii)
Figure ID: FIG-EE1-2023-Q1bii
Circuit description (netlist form): A plot of periodic waveform f(t) versus time t. Over one period T = 4a, the signal rises linearly from 0 at t = 0 to 1 at t = a, remains constant at 1 from t = a to t = 3a, ramps down linearly to 0 at t = 4a, and repeats periodically.
Symbolic form: not derivable from figure.

(c) A 3-phase, 50 Hz, star-connected cage-type induction motor has standstill input impedance of (1·0+j 3·0) Ω per phase. The motor is connected through a cable from 400 V, 3-phase balanced supply so that the blocked rotor voltage at its terminal is dropped by 20% from the supplied voltage. The motor is to be started through a DOL starter from the same supply and cable as above.
Find:
(i) the cable impedance per phase,
(ii) the motor starting current,
(iii) input power factor at the time of starting.
(Assume negligible stator impedance of the motor and cable R/X ratio of 3:1 at 50 Hz supply. Also ignore magnetizing current and core losses.) [10]

(d) Calculate the lower corner frequency for the circuit shown below. Take transistor parameters as: β=100, V_BE=0.7 V and V_A=∞. [10]
Figure ID: FIG-EE1-2023-Q1d
Circuit description (netlist form): A common-emitter BJT amplifier circuit powered by V_CC=12 V. An input AC signal v_i with series resistance R_S=0.5 kΩ is connected through coupling capacitor C_C=0.1 μF to the base of an NPN transistor. A voltage divider consisting of R_1=10 kΩ connected between V_CC and base and R_2=1.5 kΩ connected between base and ground provides biasing. The collector is connected to V_CC via R_C=1 kΩ where output voltage v_o is taken. The emitter is connected to ground through R_E=0.1 kΩ.
Symbolic form: not derivable from figure.

(e) A metal bar slides over a pair of conducting rails in a uniform magnetic field B=a_zB_0 Wb/m² with a constant velocity u m/s as shown below in the figure. A resistance 'R' Ω is connected between terminals 1 and 2. Prove that this system upholds the principle of conservation of energy. Neglect the electrical resistance of the metal bar and the pair of conducting rails, and the mechanical friction of this ideal system. [10]
Figure ID: FIG-EE1-2023-Q1e
Circuit description (netlist form): Two parallel conducting rails separated by distance h meters lie in the X-Y plane parallel to the X-axis. A resistor R is connected between terminals 1 and 2 at the left ends of the rails. A conducting metal bar placed across the rails slides in the +X direction with constant velocity u. A uniform magnetic field B=a_z B_0 Wb/m² is oriented perpendicular to the rail plane in the +Z direction.
Symbolic form: not derivable from figure.

[EE1-2023-Q2] Network & Systems Analysis · LTI Systems
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 2 | Marks: 50 | Words: N/A
Syllabus: Circuit analysis methods: nodal analysis, mesh analysis; basic network theorems and applications; transient analysis: RL, RC and RLC circuits; sinusoidal steady state analysis; resonant circuits; coupled circuits; balanced 3-phase circuits. Two-port networks.
Directive: Obtain, Determine, Find
Theme (primary): Nodal Analysis
Theme (secondary): Discrete-Time LTI Systems & BJT Differential Pair
Repeat cluster: none
Has figure: yes
(a) For the circuit shown in the figure, obtain the value of voltage across 0·5 Ω and 2·5 Ω resistors using nodal current analysis. [20]
Figure ID: FIG-EE1-2023-Q2a
Circuit description (netlist form): A four-node bridge network with outer nodes V_1, V_2, V_3, V_4 and a central ground reference node. An independent DC voltage source of 12 V has its negative terminal connected to node V_2 and positive terminal connected to the central ground node. An independent current source of 2 A is connected from the central ground node directed towards node V_3. A resistor of 0.5 Ω is connected between node V_2 and node V_3 with voltage drop V_x (+ at V_3, - at V_2). A resistor of 2 Ω is connected between node V_3 and node V_4. A dependent current source of value 0.5 V_x is connected from the central ground node directed towards node V_4. A resistor of 1 Ω is connected between the central ground node and node V_1. A dependent voltage source of value 0.2 V_y is connected between node V_1 (negative terminal) and node V_4 (positive terminal). A resistor of 2.5 Ω is connected between node V_2 and node V_1 with voltage drop V_y (+ at V_1, - at V_2).
Symbolic form: not derivable from figure.

(b) A causal discrete-time LTI system is described by:
y[n]-3/4y[n-1]+1/8y[n-2]=x[n],
where x[n] and y[n] are the input and output of the system respectively.
(i) Determine the system transfer function H(z).
(ii) Find the impulse response h[n] of the system.
(iii) Find the step response s[n] of the system. [20]

(c) Consider the figure of differential pair given below. Neglecting the early effect, determine the change in V_X, V_Y, V_X-V_Y if
(i) V_CC rises by ΔV and R_C1=R_C2=R_C
(ii) I_EE experiences a change of ΔI and R_C1=R_C2=R_C.
(iii) R_C1=R_C2+ΔR. [10]
Figure ID: FIG-EE1-2023-Q2c
Circuit description (netlist form): A differential pair consisting of two matched NPN transistors Q_1 and Q_2. The common-mode input voltage source V_CM is connected between ground and the tied base terminals of Q_1 and Q_2. The emitters of Q_1 and Q_2 are tied together to a constant tail current source I_EE connected to ground. The collector of Q_1 is connected to power rail V_CC via resistor R_C1 with collector voltage labeled V_X. The collector of Q_2 is connected to V_CC via resistor R_C2 with collector voltage labeled V_Y.
Symbolic form: not derivable from figure.

[EE1-2023-Q3] Digital Electronics & Systems · Shift Registers
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 3 | Marks: 50 | Words: N/A
Syllabus: Boolean algebra; minimisation of Boolean functions; logic gates; digital IC families (DTL, TTL, ECL, MOS, CMOS). Combinational circuits arithmetic circuits, code converters, multiplexers and decoders. Sequential circuits: latches and flip-flops, counters and shift-registers. Comparators, timers, multivibrators. Sample and hold circuits, ADCs and DACs. Semiconductor memories. Logic implementation using programmable devices (ROM, PLA, FPGA).
Directive: Complete, Determine, Sketch, Find, Calculate
Theme (primary): Sequential Logic
Theme (secondary): Fourier Transforms & Op-Amp Operations
Repeat cluster: none
Has figure: yes
(a) (i) Consider the shift register shown in the figure below, which is implemented using D flip-flops and 2:1 multiplexers.
Figure ID: FIG-EE1-2023-Q3ai-1
Circuit description (netlist form): A 4-bit synchronous shift register constructed using four D flip-flops (stages 0, 1, 2, 3) and four 2:1 multiplexers. All flip-flops share a common clock line CK and an active-low clear line CLR_bar. A control line 'Load' is connected to the select input of each multiplexer. For stage 0, MUX input 0 is serial input X_L, input 1 is parallel input X_0, and MUX output connects to the D input of flip-flop 0. For stages 1, 2, and 3, MUX input 0 is connected to the Q output of the previous stage (Q_0, Q_1, Q_2), input 1 is connected to parallel inputs X_1, X_2, X_3, and MUX output connects to the D input of that stage's flip-flop, producing outputs Q_0, Q_1, Q_2, Q_3.
Symbolic form: not derivable from figure.

Complete the truth table shown as follows:
| Inputs | | | Next State | | | |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| CK | CLR_bar | Load | Q_3 | Q_2 | Q_1 | Q_0 |
| X | 0 | X | | | | |
| ↑ | 1 | 0 | | | | |
| ↑ | 1 | 1 | | | | |

Complete the timing diagram below assuming X_3X_2X_1X_0=0101.
Figure ID: FIG-EE1-2023-Q3ai-2
Circuit description (netlist form): A digital timing diagram over ten clock cycles showing input waveforms for clock CK, active-low clear CLR_bar, control signal Load, serial data input X_L, and rows for output signals Q_0, Q_1, Q_2, Q_3.
Symbolic form: not derivable from figure.

(ii) Use 4:1 multiplexer and logic gates to implement the function:
F(A,B,C,D)=Σm(3,4,5,6,7,9,10,12,14,15) [10]

(b) (i) The figure shows a triangular pulse which is zero for all time except -a/2 ≤ t ≤ a/2. For this pulse
(I) determine the Fourier transform.
(II) sketch the continuous amplitude spectrum. [10]
Figure ID: FIG-EE1-2023-Q3bi
Circuit description (netlist form): A plot of a symmetric triangular pulse f(t) centered at t=0 with peak amplitude V_0, base width spanning from t=-a/2 to t=a/2, and zero elsewhere.
Symbolic form: f(t) = V_0 (1 - 2|t|/a) for |t| ≤ a/2, 0 otherwise

(ii) Find L^-1[F_1(s) F_2(s)] by using convolution for the following F_1(s) and F_2(s):
F_1(s) = s/(s+1), F_2(s) = 1/(s^2+1) [10]

(c) An inverting Op-Amp circuit is to be designed such that the weighted sum v_0=-(v_1+4v_2). Resistors R_1, R_2 and R_f are to be chosen in a way that for a maximum output voltage of 4 V, the current in the feedback resistor does not exceed 1 mA.
Figure ID: FIG-EE1-2023-Q3c
Circuit description (netlist form): An operational amplifier summing circuit. Input voltages v_1 and v_2 are connected via resistors R_1 and R_2 respectively to the inverting input terminal (-). The non-inverting input terminal (+) is connected to ground. A feedback resistor R_f is connected between the inverting input terminal and the output terminal v_o.
Symbolic form: v_o = -( (R_f/R_1)v_1 + (R_f/R_2)v_2 )
Calculate the values of R_1, R_2 and R_f. [10]

[EE1-2023-Q4] Analog Electronics · BJT Saturation
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 4 | Marks: 50 | Words: N/A
Syllabus: Characteristics and equivalent circuits (large and small-signal) of Diode, BJT, JFET and MOSFET. Diode circuits Clipping, clamping, rectifier. Biasing and bias stability. FET amplifiers. Current mirror; Amplifiers: single and multi-stage, differential, operational feedback and power. Analysis of amplifiers; frequency-response of amplifiers. OPAMP circuits. Filters; sinusoidal oscillators: criterion for oscillation; single-transistor and OPAMP configurations. Function generators and wave-shaping circuits. Linear and switching power supplies.
Directive: Find, Use, Obtain
Theme (primary): Transistor Biasing
Theme (secondary): Logic Design & Two-Port Networks
Repeat cluster: none
Has figure: yes
(a) For the circuit shown below, early voltage V_A=∞ and β=100. Find the reverse saturation current if:
(i) the collector current of Q_1=0.5 mA.
(ii) Q_1 is biased at the edge of saturation. [20]
Figure ID: FIG-EE1-2023-Q4a
Circuit description (netlist form): An NPN BJT circuit with a DC supply V_CC=2·5 V. A voltage divider consisting of a 50 kΩ resistor from V_CC to base and a 30 kΩ resistor from base to ground biases the base of transistor Q_1. The collector is connected to V_CC through a 3 kΩ resistor. The emitter is connected directly to ground.
Symbolic form: not derivable from figure.

(b) Consider the control circuitry of a machine copier with four switches as shown below in the figure. These switches are at various points along the path of the machine. Each switch is normally open and closes only when the paper passes over it. Let there be a restriction that switch 1 and switch 4 cannot close simultaneously. Use Karnaugh map to design a logic circuit that produces a high output whenever two or more switches are closed at the same time. [20]
Figure ID: FIG-EE1-2023-Q4b
Circuit description (netlist form): A schematic showing four single-pole switches SW1, SW2, SW3, SW4. One side of each switch is connected to ground, while the other side is pulled up to a 5 V supply through a resistor and connected as an input line to a block labeled "Logic Circuit", which produces output X.
Symbolic form: not derivable from figure.

(c) The experimental data for the two-port network shown in the figure is given in the table. [10]
Figure ID: FIG-EE1-2023-Q4c
Circuit description (netlist form): A two-port network block with port 1 excited by voltage source V_S1 with entering current I_1, and port 2 excited by voltage source V_S2 with entering current I_2.
Symbolic form: not derivable from figure.
| | V_S1 Volts | V_S2 Volts | I_1 Amp | I_2 Amp |
| :--- | :---: | :---: | :---: | :---: |
| Experiment 1 | 100 | 50 | 5 | -30 |
| Experiment 2 | 50 | 100 | -20 | -5 |
| Experiment 3 | 25 | 0 | | |
| Experiment 4 | | | 5 | 0 |
Obtain Z-parameters, Y-parameters and fill in the missing data.

[EE1-2023-Q5] Energy Conversion & Power Electronics · Synchronous Motors
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 5 | Marks: 50 | Words: N/A
Syllabus: Principles of electromechanical energy conversion: Torque and emf in rotating machines. DC machines characteristics and performance analysis; starting and speed control of motors. Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers. 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
Directive: Find, Show, Calculate
Theme (primary): Synchronous Machines
Theme (secondary): Controlled Converters & AM Modulation
Repeat cluster: none
Has figure: yes
(a) A 400 V, 50 Hz, 3-phase star-connected cylindrical rotor synchronous motor has synchronous impedance of (0·5+j 2·5) Ω per phase. It develops a maximum power of 50 kW at rated terminal voltage. Find the excitation voltage, motor current and input power factor under maximum power condition. [10]

(b) A half-controlled converter fed from 240 V, 50 Hz single-phase ac source is feeding 1800 W power to a 100 V battery as shown in the figure below. The battery is connected in series with a large inductance and a resistance of 2 Ω. The inductance is large enough to make the load current flat and continuous.
Find:
(i) the triggering angle of the thyristors,
(ii) rms value of fundamental component of converter input current, and
(iii) the input power factor in the ac side.
(Assume the inductor has a resistance of 1 Ω) [10]
Figure ID: FIG-EE1-2023-Q5b
Circuit description (netlist form): A single-phase half-controlled bridge converter connected to a 240 V, 50 Hz AC source. The upper arms contain two thyristors and the lower arms contain two diodes, with a freewheeling diode across the output terminals. The DC load consists of a 2 Ω resistor in series with a large inductor L = Large (internal resistance 1 Ω) and a battery rated 100 V, 1800 W.
Symbolic form: not derivable from figure.

(c) A signal x(t) is described as
x(t)=(5/2)cos(160×10^3π t)+7cos(170×10^3π t)+(5/2)cos(180×10^3π t)
Show that this is an Amplitude modulated signal.
Find:
(i) the ratio P_s/P_c where P_s is power in side bands and P_c is power in carrier.
(ii) the power efficiency in this AM signal. [10]

(d) When a transmission line of characteristic impedance 50 Ω is short-circuited at the termination, the voltage minima were found to be 25 cm apart. If the short circuit is replaced by unknown load impedance Z_L, the minima shifted 8 cm towards the load and the standing wave ratio was found to be 4. Calculate the unknown load impedance Z_L. [10]

(e) In the series RLC circuit shown in the figure, the capacitor has an initial charge Q_0=1 mC and the switch is in position 1 long enough to establish the steady state. Find the transient current which results when the switch is moved from position 1 to 2 at t=0. [10]
Figure ID: FIG-EE1-2023-Q5e
Circuit description (netlist form): A circuit with a two-position switch. Terminal 1 connects to a 10 V DC source referenced to ground. Terminal 2 connects to a capacitor of 200 μF with initial charge Q_0 = 1 mC (top plate negative, bottom plate positive) referenced to ground. The common pole connects to a series branch consisting of a 5 Ω resistor and a 0.1 H inductor to ground, carrying transient current i_0.
Symbolic form: not derivable from figure.

[EE1-2023-Q6] Energy Conversion · DC Shunt Motor
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 6 | Marks: 50 | Words: N/A
Syllabus: Principles of electromechanical energy conversion: Torque and emf in rotating machines. DC machines characteristics and performance analysis; starting and speed control of motors. Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers. 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
Directive: Find, Calculate, Determine
Theme (primary): Motor Fault Operation
Theme (secondary): Wave Absorption
Repeat cluster: none
Has figure: yes
(a) A 200 V, 1100 rpm, dc shunt motor takes 1.5 A and runs at 1150 rpm under no load condition at rated voltage. Its armature resistance including brushes is 0·5 Ω. While running under full load, its field circuit gets open circuited due to fault and the motor takes 5 times of its rated input current to deliver rated torque.
Find:
(i) the full load torque of the machine, and
(ii) the speed of the motor under field fault condition.
Assume no armature copper losses at no load and no armature reaction. [20]

(b) An absorber material of relative permeability and relative permittivity of ε_r=μ_r=6-j6 is coated on a perfectly conducting sheet and this combination is placed in free space as shown in the figure given below. A 500 MHz wave is incident on it normally from free space. Calculate the thickness of the absorber required to attenuate the reflected wave by 30 dB. [20]
Figure ID: FIG-EE1-2023-Q6b
Circuit description (netlist form): A diagram depicting a uniform plane electromagnetic wave labeled "Incident wave" normally incident from "Free Space" onto a planar slab of "Absorber material" coated onto a "Conducting sheet".
Symbolic form: not derivable from figure.

(c) A 120 V, 1000 rpm, 350 W separately excited dc motor is supplied via half-controlled single-phase bridge rectifier for speed control purpose. The supply voltage to the rectifier is 200 V, 50 Hz ac and to obtain the desired speed, the triggering angle is set at 105° at one instant. The armature current is discontinuous with an average value of 2 A and it continues up to 30° beyond voltage zero. The motor armature resistance is 1·5 Ω. Determine the operating speed of the motor.
(Assume constant flux operation and no armature reaction) [10]

[EE1-2023-Q7] Energy Conversion · Synchronous Condenser
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 7 | Marks: 50 | Words: N/A
Syllabus: Principles of electromechanical energy conversion: Torque and emf in rotating machines. DC machines characteristics and performance analysis; starting and speed control of motors. Transformers: principles of operation and analysis; regulation, efficiency; 3-phase transformers. 3-phase induction machines and synchronous machines characteristics and performance analysis; speed control.
Directive: Find, Show, Derive, Calculate
Theme (primary): Reactive Power Compensation
Theme (secondary): Thyristor Commutation
Repeat cluster: none
Has figure: yes
(a) A 400 V, 3-phase, 50 Hz, star-connected synchronous motor has per phase synchronous impedance Z_s=(0·5+j3·5) Ω. It is required to operate the motor as synchronous condenser to deliver 100 kVAr at rated voltage and no load. Find the motor current and excitation voltage under this condition. (Assume zero motor input power at no load) [20]

(b) (i) Two statistically independent Poisson random variables X_1 and X_2 with respective parameters λ_1 and λ_2 are added to form Y=X_1+X_2.
Show that the random variable Y is Poisson distributed with parameter (λ_1+λ_2). [10]
(ii) Derive the relationship between Binomial and Poisson random variables when Binomial distribution becomes equal to the Poisson distribution. [10]

(c) The circuit given in the figure below is in steady state initially before the thyristor is triggered. The thyristor is triggered at t=0. Calculate
(i) the maximum current the thyristor will carry.
(ii) the instant of carrying maximum current by the thyristor.
(iii) the conduction time of the thyristor.
(Assume zero latching and holding current for the thyristor) [10]
Figure ID: FIG-EE1-2023-Q7c
Circuit description (netlist form): A DC circuit powered by a 200 V DC voltage source. Connected across the supply is a branch containing a thyristor (SCR, anode up, cathode down) in series with a 4 Ω resistor to the negative rail. Connected in parallel across the thyristor is a series LC resonant branch consisting of a 1.5 mF capacitor and a 3.0 mH inductor.
Symbolic form: not derivable from figure.

[EE1-2023-Q8] Power Electronics & Drives · Induction Motor Control
Exam: UPSC Mains 2023 | Paper: EE1 | Q.No: 8 | Marks: 50 | Words: N/A
Syllabus: Semi-conductor power devices diode, transistor, thyristor, triac, GTO and MOSFET-static characteristics and principles of operation; triggering circuits; phase control rectifiers; bridge converters: fully-controlled and half-controlled; principles of thyristor choppers and inverters; DC-DC converters; Switch mode inverter; basic concepts of speed control of dc and ac motor drives applications of variable-speed drives.
Directive: Find, Calculate, Determine
Theme (primary): VVVF Speed Control
Theme (secondary): Modulation & Transformer Loads
Repeat cluster: none
Has figure: yes
(a) A 415 V, 4-pole, 3-phase, 50 Hz, star-connected squirrel cage induction motor has per phase parameters of r_s=1·1 Ω, r_r=1·3 Ω, X_m=167 Ω and X_ls=X_lr=3·5 Ω, all at rated frequency. The motor has a rated slip of 4%. Its speed is to be controlled by VVVF method using a VSI (Voltage Source Inverter). Find the voltage to be applied to the motor at 5 Hz operating frequency to maintain same peak torque as in 50 Hz. Also determine the speed at which rated torque appears at this frequency.
(Neglect core losses in the motor and all motor parameters referred from stator side) [20]

(b) (i) A 300 W carrier is modulated to a depth of 70%. Calculate the total power transmitted in case of Vestigial Side Band (VSB) modulation. Assume 15% of the other side band is transmitted along with wanted side band. Also find the saving in power when compared to Double Side Band (DSB) transmission. [10]
(ii) Find the temperature of the attenuator in the system shown in the figure below so that the overall noise figure of the system does not exceed 3·5 dB. The attenuator introduces a loss of 3 dB. [10]
Figure ID: FIG-EE1-2023-Q8bii
Circuit description (netlist form): A cascade connection of three stages: an Attenuator with loss = 3 dB, followed by an Amplifier with Gain = 1000 and Noise figure = 1·5 dB, followed by a Mixer with Gain = 100 and Noise figure = 8 dB.
Symbolic form: not derivable from figure.

(c) A bank of three identical single-phase transformers having 11000 V/231 V voltage ratio are connected in delta-star combination with delta side connected to 11 kV, 3-phase balanced supply. The star side is supplying a balanced load of 120 kVA at 0-8 pf lag. A single-phase load of 40 kW, upf is now connected between one line and neutral of the secondary side. Calculate the input line currents at the delta side under this condition.
(Neglect any magnetising currents of the transformers) [10]