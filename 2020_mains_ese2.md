### [Engineering Service Paper II-2020-1(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 1(a) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Derive, sketch
* **Theme (primary):** Analog Electronics
* **Theme (secondary):** Operational Amplifier
* **Repeat cluster:** 
* **Has figure:** yes

> For the circuit shown in the figure below, derive the expression for output voltage and sketch the nature of the output when $V_{2}=10$ V and $V_{1}=5~V.$ (12)
> 
> **Figure ID:** FIG-EE2-2020-Q1a
> **Circuit description (netlist form):** An op-amp circuit with two op-amps. First op-amp is configured as an integrator/differentiator type circuit. Inverting input receives signal from ground via series capacitor $C_1$, non-inverting is at $V_1$. Feedback resistor $R_1$ connects output to inverting input. The output of the first op-amp is connected via resistor $R_1$ to the inverting input of the second op-amp. The non-inverting input of the second op-amp is at $V_2$. A feedback capacitor $C_1$ connects the output of the second op-amp (which provides $V_0$) to its inverting input.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-1(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 1(b) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion;
* **Directive:** Find
* **Theme (primary):** Control Systems
* **Theme (secondary):** Bode Plot
* **Repeat cluster:** 
* **Has figure:** yes

> A continuous LTIV system S with frequency response $H (j\Omega)$ is constructed by cascading two continuous-time LTIV systems with frequency response $H_{1} (j\Omega)$ and $H_{2} (j\Omega)$, respectively. Figures a and b show the straight-line approximations of Bode magnitude plots of $H_{1} (j\Omega)$ and $H (j\Omega)$, respectively. Find $H_{2} (j\Omega)$. (12)
> 
> **Figure ID:** FIG-EE2-2020-Q1b
> **Circuit description (netlist form):** Two Bode magnitude plots. Plot (a) shows $20 \log_{10}|H_1(j\Omega)|$ starting at 6 dB, increasing at 20 dB/decade from $\Omega=1$ to $\Omega=8$, flat at 24 dB from $\Omega=8$ to $\Omega=40$, and decreasing at -20 dB/decade from $\Omega=40$ onwards. Plot (b) shows $20 \log_{10}|H(j\Omega)|$ flat at -20 dB up to $\Omega=8$, then decreasing at -40 dB/decade from $\Omega=8$ onwards.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-1(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 1(c) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** Induction Motor
* **Repeat cluster:** 
* **Has figure:** no

> Consider a three-phase induction motor with the following parameters:
> Number of poles : 4
> Supply frequency : 50 Hz
> Full load speed : 1470 rpm
> Rotor resistance : 0.12 $\Omega$
> Standstill reactance : 1.12 $\Omega$
> Find the
> (i) Slip for maximum torque (4)
> (ii) Ratio of maximum torque to full load torque. (8)

### [Engineering Service Paper II-2020-1(d)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 1(d) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** What, Explain
* **Theme (primary):** Power Systems
* **Theme (secondary):** Smart Grid
* **Repeat cluster:** 
* **Has figure:** no

> (i) What is Smart Grid ? (4)
> (ii) Compared to Supervisory Control And Data Acquisition (SCADA) system, what are the advantages of Phasor Measurement Unit (PMU)? (4)
> (iii) Explain operation of PMU with a neat diagram. (4)

### [Engineering Service Paper II-2020-1(e)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 1(e) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Power Electronics
* **Theme (secondary):** Grid Integration
* **Repeat cluster:** 
* **Has figure:** yes

> A PV panel is connected with a single phase fully controlled converter as shown in the circuit below. The panel is supplying a current of 5 A and generated power is 1000 W. The series inductance in the circuit is large to make the current flat and continuous. Find (i) the triggering angle of the thyristor bridge, (ii) output voltage at rectifier terminal, and (iii) input power factor. (12)
> 
> **Figure ID:** FIG-EE2-2020-Q1e
> **Circuit description (netlist form):** A 230 V, 50 Hz AC source is connected to a single-phase fully controlled thyristor bridge rectifier. The DC output of the rectifier is connected in series with a resistor $R=1~\Omega$, a large inductor L, and a PV panel. The PV panel acts as a DC source delivering 5 A of current flowing in the direction of the bridge (acting as an inverter).
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-2(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 2(a) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Power Electronics
* **Theme (secondary):** Boost Converter
* **Repeat cluster:** 
* **Has figure:** yes

> The DC-DC converter given below is operating at 30 kHz and drawing an input current of 25 A at 48 V DC.
> (i) For a load current of 10 A, find
> I. the duty ratio of the switch,
> II. output voltage,
> III. peak inductor current,
> IV. output voltage ripple, and
> V. the load current where the inductor current just becomes discontinuous. (15)
> (ii) Also find the critical value of L to keep the inductor current just continuous when the input voltage changes to 60 V with output remaining same.
> (Assume lossless operation of converter components) (5)
> 
> **Figure ID:** FIG-EE2-2020-Q2a
> **Circuit description (netlist form):** A boost converter circuit. A DC input voltage $V_{in}$ is connected in series with an inductor $L=200~\mu H$. A switch Sw connects the node after the inductor to the negative return rail. A diode points from the inductor-switch node towards a parallel combination of a capacitor $C=1000~\mu F$ and a Load.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-2(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 2(b) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Sketch, What, Find
* **Theme (primary):** Analog Communication
* **Theme (secondary):** Amplitude Modulation
* **Repeat cluster:** 
* **Has figure:** no

> A signal $m(t)=2~\cos(20~\pi t)-\cos(40~\pi t),$ where the unit of time is millisecond, is amplitude modulated using the carrier frequency $(f_{c})$ of 600 kHz. The AM signal is given by
> $s(t)=5~\cos 2\pi f_{c}t+m(t)\cos 2\pi f_{c}t$
> (i) Sketch the magnitude spectrum of $s(t).$ What is its bandwidth ? (5)
> (ii) What is the modulation index? (5)
> (iii) The AM signal is passed through a high-pass filter with cut-off frequency 595 kHz (i.e., the filter passes all frequencies above 595 kHz, and cuts off all frequencies below 595 kHz). Find an explicit time-domain expression for the quadrature component of the filter output with respect to a 600 kHz frequency reference. (10)

### [Engineering Service Paper II-2020-2(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 2(c) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Determine
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** DC Motor
* **Repeat cluster:** 
* **Has figure:** no

> A 400 V DC shunt motor has armature and field resistances of 0.2 $\Omega$ and 200 $\Omega$ respectively. It draws a current of 6 A on no-load and 70 A on full-load. If its no-load and full-load speeds are the same, determine the field weakening due to load current as percentage of no-load flux. (20)

### [Engineering Service Paper II-2020-3(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 3(a) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Calculate
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** Synchronous Alternator
* **Repeat cluster:** 
* **Has figure:** no

> A salient pole star connected alternator is connected to infinite bus operating at 1.0 p.u. voltage. The alternator has $X_{d}=0\cdot75$ p.u. and $X_{q}=0\cdot5$ p.u. on per phase basis. It is delivering 1.0 p.u. power to the infinite bus at 0.8 p.f. lag. Calculate (i) the load angle and excitation voltage under this condition, (ii) the maximum power that can be delivered by the alternator with same excitation and the corresponding load angle, (iii) the armature current and p.f. under maximum power condition, and (iv) the theoretical value of maximum power that the alternator can deliver when its field circuit is suddenly disconnected due to fault. (20)

### [Engineering Service Paper II-2020-3(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 3(b) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** Design of lead-lad compensators.
* **Directive:** Modify
* **Theme (primary):** Control Systems
* **Theme (secondary):** Cascaded Compensation
* **Repeat cluster:** 
* **Has figure:** no

> A closed loop system with unity feedback and having the forward loop transfer function as
> $G(s)=\frac{14\cdot4}{s(1+0\cdot1s)}.$
> Modify the design using cascaded compensation to satisfy the optimum performance criterion, so that the transient response to unit step input reaches its final steady state value in minimum time without having any overshoot. (20)

### [Engineering Service Paper II-2020-3(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 3(c) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** analysis of symmetrical and unsymmetrical faults.
* **Directive:** Evaluate
* **Theme (primary):** Power Systems
* **Theme (secondary):** Fault Analysis
* **Repeat cluster:** 
* **Has figure:** no

> Two 11 kV, 30 MVA, three-phase synchronous generators operate in parallel supplying a sub-station through a feeder having an impedance of $(0\cdot6+j0\cdot8)$ ohms to positive and negative sequence currents and $(1\cdot0+j2\cdot6)$ ohms to zero sequence currents. Each generator has $X_{1}=0\cdot8$ ohms, $X_{2}=0\cdot5$ ohms and $X_{0}=0\cdot2$ ohms and has its neutral grounded through a reactance of 0.2 ohms. Evaluate the fault currents in each line and the potential above earth attained by the generator neutrals, consequent to simultaneous occurrence of earth fault on the Y and B phases at the sub-station. (20)

### [Engineering Service Paper II-2020-4(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 4(a) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Show, How
* **Theme (primary):** Signals and Systems
* **Theme (secondary):** Signal Sampling
* **Repeat cluster:** 
* **Has figure:** no

> A signal $g(t)$ band limited to B Hz is sampled by a periodic pulse train $p_{T}(t)$ made up of a rectangular pulse of width $\frac{1}{8~B}$ sec (centered at origin) repeating at the Nyquist rate (2 B pulses per sec). Show that the sampled signal $g_{s}(t)$ is given by
> $g_{s}(t)=\frac{1}{4}g(t)+\sum_{n=1}^{\infty}\frac{2}{n\pi}\sin(\frac{n\pi}{4})g(t)\cos(4~n\pi~Bt)$
> How will you recover $g(t)$ from the signal $g_{s}(t)$? (15+5)

### [Engineering Service Paper II-2020-4(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 4(b) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Power Electronics
* **Theme (secondary):** Motor Drives
* **Repeat cluster:** 
* **Has figure:** no

> A 3-phase half-controlled rectifier with free-wheeling diode is supplying a separately excited DC motor for speed control purpose. The AC input to the converter is 415 V, 3-phase, 50 Hz. The motor parameters are:
> $V=220$ V DC, $P=10\cdot5~kW$
> Rated speed $=1100$ rpm, Armature resistance $r_{a}=0\cdot4~\Omega.$
> The field current is kept constant at rated value. The motor is operated at rated speed delivering half rated torque.
> (i) Find motor terminal voltage and triggering angle of thyristor bridge.
> (ii) Find the speed of the motor if one of the input phases to the converter is out due to fault and the triggering angle is kept as before with same load torque.
> (iii) Also find the new triggering angle if the motor speed is to be maintained at rated value with same load torque.
> (Neglect losses in the machine) (20)

### [Engineering Service Paper II-2020-4(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 4(c) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** load flow;
* **Directive:** Obtain
* **Theme (primary):** Power Systems
* **Theme (secondary):** Load Flow
* **Repeat cluster:** 
* **Has figure:** yes

> The figure below shows single line diagram of a power system with generators at bus-1 and bus-3. The voltage at bus-1 is 1.05 $\angle0^{\circ}$ p.u. and at bus-3, $|V|=1\cdot04$ p.u. Line impedances are in p.u. and line charging susceptances are neglected. Obtain state vector using Fast Decoupled Load Flow (FDLF) for one iteration. (20)
> 
> **Figure ID:** FIG-EE2-2020-Q4c
> **Circuit description (netlist form):** A 3-bus power system. Bus 1 is a slack bus with a generator. Bus 2 is a load bus with $P_2=400$ MW, $Q_2=250$ MW. Bus 3 is a generator bus with $P_3=200$ MW, $|V_3|=1.04$ p.u. Line impedances: $z_{12}=(0.02+j0.04)$ p.u., $z_{13}=(0.01+j0.03)$ p.u., $z_{23}=(0.0125+j0.025)$ p.u.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-5(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 5(a) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Determine
* **Theme (primary):** Power Electronics
* **Theme (secondary):** Thyristor Conduction Loss
* **Repeat cluster:** 
* **Has figure:** yes

> A thyristor is having the I-V characteristic as given in the figure below. It is used in a half wave rectifier circuit with resistive load operating at $\alpha=30^{\circ}$ and carrying a peak load current of 100 A. Determine the average conduction loss in the thyristor. (12)
> 
> **Figure ID:** FIG-EE2-2020-Q5a
> **Circuit description (netlist form):** An I-V characteristic graph of a thyristor. The x-axis is $V_d$ (voltage) and the y-axis is $i_d$ (current). The current is zero until $V_d = 1.0$ V, after which it rises linearly, reaching 200 A at $V_d = 2.0$ V.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-5(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 5(b) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** Steady-state performance of overhead transmission lines and cables;
* **Directive:** What
* **Theme (primary):** Power Systems
* **Theme (secondary):** Corona Loss
* **Repeat cluster:** 
* **Has figure:** no

> A three-phase equilateral transmission line has a total corona loss of 55 kW at 110 kV and 100 kW at 114 kV. What is the disruptive critical voltage between lines? What is the corona loss at 120 kV ? (12)

### [Engineering Service Paper II-2020-5(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 5(c) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Show
* **Theme (primary):** Signals and Systems
* **Theme (secondary):** Fourier Transform
* **Repeat cluster:** 
* **Has figure:** no

> A Gaussian pulse is specified by
> $g(t)=Ae^{-\alpha^{2}t^{2}}$
> where $\alpha$ is an arbitrary attenuation coefficient and A is constant. Show that the Fourier transform of $g(t)$ is also Gaussian. (12)

### [Engineering Service Paper II-2020-5(d)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 5(d) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** Design of lead-lad compensators.
* **Directive:** What
* **Theme (primary):** Control Systems
* **Theme (secondary):** Lead and Lag Networks
* **Repeat cluster:** 
* **Has figure:** no

> What are the advantages and limitations of Lead and Lag networks in a practical control system? (12)

### [Engineering Service Paper II-2020-5(e)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 5(e) | **Marks:** 12 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Prove
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** Transformers
* **Repeat cluster:** 
* **Has figure:** no

> For a Scott connected transformer, prove that the number of turns on primary of the teaser transformer is $\frac{\sqrt{3}}{2}$ times the number of turns in primary of main transformer. (12)

### [Engineering Service Paper II-2020-6(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 6(a) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** Synchronous Motor Excitation
* **Repeat cluster:** 
* **Has figure:** no

> A 15 kW, 400 V, 3-phase, star connected synchronous motor has synchronous impedance of $0\cdot4+j4~\Omega$. Find the motor excitation voltage for full load output at 0.866 leading power factor. Take the armature efficiency of 95%. (20)

### [Engineering Service Paper II-2020-6(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 6(b) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** Concepts of system stability: swing curves and equal area criterion.
* **Directive:** Determine
* **Theme (primary):** Power Systems
* **Theme (secondary):** Equation of Motion
* **Repeat cluster:** 
* **Has figure:** yes

> A synchronous machine is connected to an infinite bus through a transformer and a double circuit line shown in the figure. The infinite bus voltage is $V=1\cdot0\angle0^{\circ}$ p.u. The direct axis transient reactance of the machine is 0.20 p.u., the transformer reactance is 0.10 p.u. and the reactance of each of the transmission lines is 0.4 p.u., all to a base of the rating of the synchronous machine. Initially the machine is delivering 0.8 p.u. power with a terminal voltage of 1.05 p.u. The inertia constant $H=5$ MJ/MVA. All resistances are neglected. Determine the equation of motion of the machine rotor. (20)
> 
> **Figure ID:** FIG-EE2-2020-Q6b
> **Circuit description (netlist form):** A synchronous generator with internal voltage E = E1\angle\delta connected to a bus. From this bus, a double circuit transmission line (Line-1 and Line-2) connects to an infinite bus-bar with voltage V = 1.0\angle0^\circ p.u.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-6(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 6(c) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** Stability: Routh Hurwitz criterion, root-loci, Bode-plots and polor plots, Nyquist's criterion;
* **Directive:** Find, What
* **Theme (primary):** Control Systems
* **Theme (secondary):** Stability
* **Repeat cluster:** 
* **Has figure:** no

> The open loop transfer function of unity feedback control system is given by
> $G(s)=\frac{K}{s(s+a)(s+b)}~0<a\le b$
> (i) Find the range of the gain constant $K(>0)$ for stability using Routh-Hurwitz criterion. (8)
> (ii) What type of control do you use if the system is required to have zero steady-state error for ramp input? Let 'A' be the parameter that can be varied in the introduced control. Find the range of 'K' for stability in terms of parameters a, b and A using Routh-Hurwitz criterion. (12)

### [Engineering Service Paper II-2020-7(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 7(a) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** economic operation;
* **Directive:** Find, Evaluate
* **Theme (primary):** Power Systems
* **Theme (secondary):** Economic Load Dispatch
* **Repeat cluster:** 
* **Has figure:** yes

> A system consists of two plants connected by a transmission line and a load is at power plant-2 as shown in the figure. Data for the loss equation consists of the information that 200 MW transmitted from plant-1 to the load results in transmission loss of 20 MW. Find the optimum generation schedule considering transmission losses to supply a load of 204.41 MW. Also evaluate the amount of financial loss that may be incurred if at the time of scheduling transmission losses are not coordinated. The incremental fuel cost characteristics of plant-1 and plant-2 are given by
> $\frac{df_{1}}{dP_{1}}=0\cdot025~P_{1}+14$ /MW-hr
> $\frac{df_{2}}{dP_{2}}=0\cdot05~P_{2}+16$ /MW-hr (20)
> 
> **Figure ID:** FIG-EE2-2020-Q7a
> **Circuit description (netlist form):** A 2-bus system. Plant-1 is connected to Bus 1. A transmission line connects Bus 1 to Bus 2. Plant-2 is connected to Bus 2. A load is also connected to Bus 2.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-7(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 7(b) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Design, Find, Determine
* **Theme (primary):** Digital Signal Processing
* **Theme (secondary):** Bilinear Transformation
* **Repeat cluster:** 
* **Has figure:** no

> A continuous-time integrator has a system function $H_{a}(s)=\frac{1}{s}$ .
> (i) Design a discrete-time integrator using bilinear transformation and find the difference equation relating the input $x[n]$ to the output y[n] of the discrete-time system. (10)
> (ii) Find the frequency response of the discrete-time integrator found in part (i) and determine whether or not this system is a good approximation of the continuous time system. (10)
> (For $\theta<<1$, $\sin~\theta\approx\theta$ and $\cos~\theta\approx1-\frac{\theta^{2}}{2}$)

### [Engineering Service Paper II-2020-7(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 7(c) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** Inverter Fed Induction Motor
* **Repeat cluster:** 
* **Has figure:** yes

> For a 3-phase, 50 Hz, 415 V, 4-pole induction motor, the standstill resistance and reactance are 3.0 $\Omega$ and 5.0 $\Omega$ at 50 Hz respectively. The machine has magnetising inductance of 350 mH and stator resistance of 1.2 $\Omega$. The machine is supplied from a 3-phase voltage source inverter with quasi square wave output voltage waveform per phase as shown in the figure below. The DC bus voltage is 500 V.
> If the machine is operating at 4% slip, find (i) the fundamental input current, (ii) harmonic copper losses in the machine up to 13 harmonics, and (iii) input power factor.
> Assume negligible core losses, equal distribution of stator and rotor leakage reactances and linear magnetic circuit. (20)
> 
> **Figure ID:** FIG-EE2-2020-Q7c
> **Circuit description (netlist form):** A quasi square wave voltage waveform. The voltage is $1/3 V_d$ from $\omega t=0$ to $\pi/3$, rises to $2/3 V_d$ from $\pi/3$ to $2\pi/3$, drops to $1/3 V_d$ from $2\pi/3$ to $\pi$, drops to $-1/3 V_d$ from $\pi$ to $4\pi/3$, drops further to $-2/3 V_d$ from $4\pi/3$ to $5\pi/3$, and rises to $-1/3 V_d$ from $5\pi/3$ to $2\pi$ where the cycle repeats.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-8(a)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 8(a) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Find
* **Theme (primary):** Electrical Machines
* **Theme (secondary):** Induction Motor Operation
* **Repeat cluster:** 
* **Has figure:** no

> A 50 Hz, 3-phase induction motor has a slip of 0.2 for maximum torque, when operated on rated frequency and rated voltage. If the motor is run on 60 Hz supply with application of rated voltage, find the ratio of
> (i) Starting currents (7)
> (ii) Starting torques (7)
> (iii) Maximum torques (6)
> with respective values at 50 Hz.
> Neglect the stator impedance.

### [Engineering Service Paper II-2020-8(b)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 8(b) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** Signal conditioning circuit;
* **Directive:** Find
* **Theme (primary):** Measurement and Instrumentation
* **Theme (secondary):** Active Filter Design
* **Repeat cluster:** 
* **Has figure:** yes

> The current of an induction motor is sensed through a suitable arrangement and converted to equivalent voltage. The current contains fundamental and higher order $5^{th}$ and $7^{th}$ harmonics. In order to separate the fundamental, the equivalent voltage waveform is passed through the following circuit as given in figure. Find the (i) cut-off frequencies of each section, (ii) overall gain attenuation in dB for fundamental, $5^{th}$ and $7^{th}$ harmonics, and (iii) overall phase shift of the measured fundamental current. (20)
> 
> **Figure ID:** FIG-EE2-2020-Q8b
> **Circuit description (netlist form):** A two-stage active filter circuit. The first stage is a non-inverting op-amp with input $V_i$ passed through a low-pass RC network (series $7.5~k\Omega$ resistor, shunt $0.33~\mu F$ capacitor to ground) to the non-inverting input. The op-amp is configured as a voltage follower with a $10~k\Omega$ feedback resistor. The output of the first stage connects via a $0.33~\mu F$ series capacitor to the non-inverting input of the second op-amp. A $12~k\Omega$ resistor connects this non-inverting input to ground. The second op-amp is also configured as a voltage follower with a $10~k\Omega$ feedback resistor. The output is $V_0$.
> **Symbolic form:** not derivable from figure.

### [Engineering Service Paper II-2020-8(c)]

* **Exam:** UPSC Mains 2020 | **Paper:** Engineering Service Paper II | **Q.No:** 8(c) | **Marks:** 20 | **Words:** N/A
* **Syllabus:** UNMAPPED
* **Directive:** Determine, specify
* **Theme (primary):** Signals and Systems
* **Theme (secondary):** Laplace Transform
* **Repeat cluster:** 
* **Has figure:** no

> Given the following facts about a real signal $x(t)$ with Laplace transform $X(s)$:
> A: $X(s)$ has exactly two poles
> B : $X(s)$ has no zeros in the finite s-plane
> C : $X(s)$ has a pole at $s=-1+j$
> D : $e^{2t}x(t)$ is not absolutely integrable
> E: $X(0)=8$
> Determine $X(s)$ and specify its region of convergence. (10+10)