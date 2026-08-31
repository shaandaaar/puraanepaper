# INDEX SHARD — EE2 · EE2.1 · EE2.1

chunk_tag: EE2|EE2.1|EE2-1
paper: EE2
syllabus_code: EE2.1
parent_topic: EE2.1
years_present: 2016, 2017, 2018, 2019, 2020, 2021, 2023, 2024, 2025, 2026
question_count: 44

Every row below is self-describing. Cite the qid exactly as written.

## qid: EE2-2016-Q1e
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 1e
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 4 | word_limit: - | directive: Explain
- authenticity: ese
- keywords: Microprocessors; 8259 Interrupt Controller

question_text: What are the internal registers of 8259? Explain each one of them.

## qid: EE2-2016-Q1f
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 1f
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 4 | word_limit: - | directive: Find, Show
- authenticity: ese
- keywords: BJT amplifiers; Q-point and AC load line

question_text: Find the Q-point and the maximum symmetrical $V_{out}$ for the transistor amplifier shown in the following figure. Show both dc and ac load lines. Assume standard design rules.

## qid: EE2-2016-Q2b
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 2b
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Draw, Give
- authenticity: ese
- keywords: Microprocessor interfacing; Memory mapped I/O; 8085

question_text: An 8085A system is configured using 74LS373 data latch, two 2732 EPROM, two 6116 RAM and two 8255 PPI. The relevant control pins of these chips are given below: 2732 A EPROM ($4k \times 8$) : OE, CE 6116 RAM ($2k \times 8$) : OE, WE, CE 8255A PPI : RD, WR, CE, A1, A0, RESET The peripheral devices are interfaced with the processor using memory mapped I/O. Draw a neat connection diagram for interfacing these chips to the system bus including Power-ON RESET circuit. Use 74LS138 for decoding. Give the addresses of all memory chips and peripheral devices.

## qid: EE2-2016-Q3c
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 3c
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Find
- authenticity: ese
- keywords: BJT biasing; Multi-stage amplifier

question_text: Find R such that at dc, $V_{out}=0$ for the circuit shown in the following figure. Also find $I_{CQ1}$ and $I_{CQ2}$. Assume that $V_{BE}=0.7 \text{ V}$ and $\beta=100$ for both transistors.

## qid: EE2-2016-Q4c
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 4c
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Draw
- authenticity: ese
- keywords: Op-amp circuits; Transfer characteristic

question_text: Draw the transfer characteristic $V_o / V_{in}$ of the OP-AMP circuit shown in the following figure.

## qid: EE2-2016-Q5b
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 5b
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Show
- authenticity: ese
- keywords: Digital adders; Full adder; logic gate

question_text: Show that a full adder can be constructed with two half adder circuits and a logic gate.

## qid: EE2-2016-Q6b
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 6b
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Draw, Write
- authenticity: ese
- keywords: Microprocessor programming; Assembly language

question_text: An array of 8-bit signed numbers (in 2's complement) is stored in sequential memory locations starting from SGNDNOS. The length of the array is $N(<255)$. Draw a flow chart and write an assembly language program to count positive non-zero numbers and store the result in sequential memory location 'POS'. Include the necessary remarks in the ALP.

## qid: EE2-2016-Q7d
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2016 | qno: 7d
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Draw
- authenticity: ese
- keywords: Sequential circuits; Timing diagram; flip-flop

question_text: A T flip-flop and a D flip-flop are interconnected as shown in the following figure. Draw a timing diagram showing their operation through six complete clock cycles. Assume $Q_{A}Q_{B}=00$ initially.

## qid: EE2-2017-Q1e
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2017 | qno: 1e
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Find
- authenticity: ese
- keywords: Ideal OP-AMP; Voltage Gain

question_text: Find the gain $v_o/v_i$ for the ideal OP-AMP shown in the figure below: (12)

## qid: EE2-2017-Q2c
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2017 | qno: 2c
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Write
- authenticity: ese
- keywords: Assembly Language; Microprocessor Programming

question_text: A set of 10 readings whose individual values are less than $(127)_{10}$ is stored in memory location starting at XX 80 H. Write an assembly language program- (i) to check each reading to determine whether it is + ve or - ve; (ii) to reject all negative readings; (iii) to add all +ve readings; (iv) to output this sum to PORT 1, at any time when the sum exceeds eight bits to indicate overflow, otherwise display the sum to PORT 2. (20)

## qid: EE2-2017-Q5d
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2017 | qno: 5d
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Convert, Draw
- authenticity: ese
- keywords: Digital Flip-Flops; D to J-K Conversion; logic gate

question_text: Convert a D flip-flop into a J-K flip-flop. Use additional logic gates. Draw the implementation. (12)

## qid: EE2-2018-Q3a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2018 | qno: 3a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Calculate
- authenticity: ese
- keywords: Analog Electronics; Operational Amplifiers

question_text: For the circuit shown below, calculate the output voltage : $R_{1}=1~k\Omega$ $R_{4}=10~k\Omega$ $R_{2}=2~k\Omega$ $R_{5}=10~k\Omega$ $R_{3}=3~k\Omega$ $R_{6}=100~k\Omega$ $V_{1}=-1~V$ $V_{2}=-2~V$ $V_{3}=8~V$

## qid: EE2-2019-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2019 | qno: 1a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Determine
- authenticity: ese
- keywords: Analog Electronics; Operational Amplifiers; diode

question_text: Determine the values of slope $K_{1}$, $K_{2}$, $K_{3}$ and the voltages $L_{+}$ and $L_{-}$ for the amplifier and its transfer characteristics shown in the figure given below: $(R_{1}=30~k\Omega$, $R_{2}=R_{5}=9~k\Omega$, $R_{3}=R_{4}=3~k\Omega$, $R_{f}=60~k\Omega)$. The diodes may be assumed to be ideal.

## qid: EE2-2019-Q2a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2019 | qno: 2a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Determine, Find
- authenticity: ese
- keywords: Analog Electronics; Operational Amplifiers

question_text: Determine the value of $v_{p}$, $v_{n}$ and $v_{out}$ in the circuit given below which uses an ideal operational amplifier. Find a resistance R that, when connected in parallel with the 1 mA source, will cause $v_{out}$ to drop to half its value when R is not present.

## qid: EE2-2019-Q5e
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2019 | qno: 5e
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Find
- authenticity: ese
- keywords: Digital Electronics; Data Converters; adc

question_text: A 12-bit dual-slope ADC utilizes a 1 MHz clock and has $V_{ref}=10$ V. Its analog input voltage is in the range of 0 to -10 V. Find out the time required to convert an input signal equal to the full-scale value. Also find the integrator time constant if the peak voltage reached at the output of the integrator is 10 V.

## qid: EE2-2019-Q6c
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2019 | qno: 6c
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Design, Realize
- authenticity: ese
- keywords: Digital Electronics; Combinational Circuits

question_text: Design a circuit that takes as input two 2-bit numbers, $N_{1}$ and $N_{2}$ for comparison and generates three outputs: $N_{1}=N_{2}$, $N_{1}<N_{2}$ and $N_{1}>N_{2}$. These three binary outputs are represented by $F_{eq}$, $F_{lt}$ and $F_{gt}$ respectively. Realize the outputs in Sum of Products (SoP) form.

## qid: EE2-2020-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2020 | qno: 1a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Derive, sketch
- authenticity: ese
- keywords: Analog Electronics; Operational Amplifier

question_text: For the circuit shown in the figure below, derive the expression for output voltage and sketch the nature of the output when $V_{2}=10$ V and $V_{1}=5~V.$ (12)

## qid: EE2-2020-Q8b
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2020 | qno: 8b
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Find
- authenticity: ese
- keywords: Measurement and Instrumentation; Active Filter Design; induction motor

question_text: The current of an induction motor is sensed through a suitable arrangement and converted to equivalent voltage. The current contains fundamental and higher order $5^{th}$ and $7^{th}$ harmonics. In order to separate the fundamental, the equivalent voltage waveform is passed through the following circuit as given in figure. Find the (i) cut-off frequencies of each section, (ii) overall gain attenuation in dB for fundamental, $5^{th}$ and $7^{th}$ harmonics, and (iii) overall phase shift of the measured fundamental current. (20)

## qid: EE2-2021-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2021 | qno: 1a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Calculate, What
- authenticity: ese
- keywords: Analog Electronics; Op-amp; closed loop

question_text: For a non-inverting amplifier with $A_{0}=\infty$, calculate the closed loop gain. What happens to the result when $R_{1}\rightarrow 0$ and $R_{3}\rightarrow 0$?

## qid: EE2-2021-Q2ai
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2021 | qno: 2ai
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 8 | word_limit: - | directive: Prove, What, Calculate
- authenticity: ese
- keywords: Digital Electronics; Data converters; op-amp

question_text: Analytically prove that the following Op-Amp circuit does the function of differential integrator:

## qid: EE2-2021-Q2aii
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2021 | qno: 2aii
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Prove, What, Calculate
- authenticity: ese
- keywords: Digital Electronics; Data converters; r-2r ladder

question_text: A. What is the full scale output of a R-2R ladder for 4-bit numbers with $R_{F}=3R$ and state $0\rightarrow 0$ V, state $1\rightarrow 5$ V? B. What is the output of above converter with input: 1001? (iii) An analog signal sensed by a sensor needs to be digitized. The range of analog signal is $0-2$ V it is desired that variation of 0.01 V be detected. Assuming maximum frequency content in analog signal is not more than 2 kHz samples, calculate conversion time and resolution required.

## qid: EE2-2021-Q6a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2021 | qno: 6a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Write, Implement
- authenticity: ese
- keywords: Digital Electronics; Logic expression

question_text: Consider the function $Y(A,B,C)$ given in the truth table. | A | B | C | $Y(A,B,C)$ | |---|---|---|---| | 0 | 0 | 0 | 1 | | 0 | 0 | 1 | 0 | | 0 | 1 | 0 | 0 | | 0 | 1 | 1 | 0 | | 1 | 0 | 0 | 1 | | 1 | 0 | 1 | 1 | | 1 | 1 | 0 | 0 | | 1 | 1 | 1 | 1 | (i) Write a logic expression for $Y(A,B,C).$ (ii) Implement $Y(A,B,C)$ using only 2-input gates. (iii) Implement $Y(A,B,C)$ using only 2-input NAND gates.

## qid: EE2-2023-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2023 | qno: 1a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Draw, Explain
- authenticity: ese
- keywords: Microprocessors and Microcomputers; Timing Diagrams; 8085

question_text: Draw memory read machine cycle of 8085 microprocessor and explain.

## qid: EE2-2023-Q2a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2023 | qno: 2a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Find
- authenticity: ese
- keywords: Analog Electronics; Op-Amp Filters

question_text: For the circuit given below, find the value of the components. Gain is 5 at a frequency of 32 kHz.

## qid: EE2-2023-Q3a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2023 | qno: 3a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Design, Draw, Plot
- authenticity: ese
- keywords: Analog Electronics; Active Filters; op-amp

question_text: Design a second order low pass filter using Op-Amp with feedback gain 1-586. High cut-off frequency is 10 kHz. Assume capacitor 0-1 µF and $R_{1}=10~k\Omega$ (resistor connected between input source to input terminal of Op-Amp). Draw the circuit diagram and plot the frequency response.

## qid: EE2-2023-Q4a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2023 | qno: 4a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Draw, Derive
- authenticity: ese
- keywords: Digital Electronics; DAC Circuits; converter; op-amp

question_text: Draw a 4-bit digital to analog $(D-A)$ converter circuit diagram using Op-Amp and binary weighted resistors. Derive the output voltage equation to get bidirectional signal output. Assume digital input 5 V and bias power supply are ± 15 V.

## qid: EE2-2024-Q2a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2024 | qno: 2a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Design
- authenticity: ese
- keywords: Digital Electronics; Sequence Detectors; flip-flop

question_text: Design a digital sequence detector circuit to detect the sequence 0110 in a serial input signal, using D flip-flops. The sequence detector should produce an output 1 whenever it detects the sequence 0110 in the serial input signal, e.g., Serial Input X: `00110101101` Output Y: `00001000010`

## qid: EE2-2024-Q6b
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2024 | qno: 6b
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Insert, Write
- authenticity: ese
- keywords: Microprocessors and Microcomputers; 8085 Assembly; assembly language

question_text: In an 8085 microprocessor, an array of 34 bytes data is stored from memory location `8000H` onwards. Certain six bytes data is available at memory location from `8100H` to `8105H`. Insert these six bytes into 34 bytes array starting from fourth location, i.e., `8003H` onwards, such that the final array expands to 40 bytes. Write 8085 assembly language program with comments for this operation.

## qid: EE2-2024-Q7ci
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2024 | qno: 7ci
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Calculate, Sketch
- authenticity: ese
- keywords: Analog Electronics; OPAMPs; op-amp

question_text: The schematic diagram of a practical differentiator circuit using op-amp is as shown in the figure below: (1) Calculate the various component values, if the differentiator differentiates input signal from frequency 10 Hz to 2 kHz effectively. (2) Also, sketch the output voltage $(v_{o})$ waveform, when the triangular wave as shown in the figure below is applied as input signal:

## qid: EE2-2024-Q7cii
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2024 | qno: 7cii
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Calculate, Compute
- authenticity: ese
- keywords: Analog Electronics; OPAMPs; op-amp

question_text: For the op-amp circuit shown in the figure below, calculate the output voltage $v_{o}$ and the current through $1\text{ k}\Omega$ resistor, when the input voltage $v_{i}=2\text{ V}$ and $R=5\text{ k}\Omega$ : Also, compute the current i, if $1\text{ k}\Omega$ resistor is replaced by $2\text{ k}\Omega$ resistor.

## qid: EE2-2025-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2025 | qno: 1a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Give
- authenticity: ese
- keywords: Analog Circuits; Clamper; op-amp

question_text: Give the circuit diagram of a negative peak clamper circuit using op-amp, and (i) Considering $V_{ref}=+2 V$, sketch the output waveform for an input signal $v_i=2 \sin (1000 t)$. (ii) Provide conditions to achieve precision clamping and explain how will you protect op-amp against excessive discharge currents. (iii) State how will you modify your circuit to achieve positive peak clamping.

## qid: EE2-2025-Q3a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2025 | qno: 3a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Give
- authenticity: ese
- keywords: Active Filters; op-amp

question_text: Give the circuit diagram of a second order highpass Butterworth filter circuit using op-amp. Evaluate the component values, such that the filter has lower cutoff frequency of 5 kHz and a pass band gain $A_F = 2$. Also give expression for voltage gain magnitude and sketch its frequency response.

## qid: EE2-2025-Q4bii
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2025 | qno: 4bii
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: What
- authenticity: ese
- keywords: Digital-to-Analog Converters (DAC)

question_text: What is the largest value of output voltage from an 8-bit DAC that produces 2.0 V for digital Input of 01110010?

## qid: EE2-2026-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 1a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Write
- authenticity: ese
- keywords: Microprocessors; 8085 Microprocessor Assembly; assembly language

question_text: In an 8085 microprocessor, 16 binary numbers are stored at memory locations from address F040 to F04F. Write 8085 assembly language program to divide these numbers by two and rearrange them in descending order.

## qid: EE2-2026-Q2a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 2a
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Prove
- authenticity: ese
- keywords: Digital Electronics; Dual Slope A/D Converter; counter

question_text: Prove that in a dual slope A/D converter, the count in the counter is direct numeric equivalent of the applied voltage, provided the known reference voltage $V_R=2^N$, where N represents the number of bits in the binary counter.

## qid: EE2-2026-Q4ai
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 4ai
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Give, Explain, Sketch
- authenticity: ese
- keywords: Analog Electronics; Voltage Limiter Design; op-amp

question_text: Give schematics and explain the working of a voltage limiter circuit that uses op-amp, resistors and certain non-linear semiconductor devices. The non-linear semiconductor devices involved have the following input-output characteristics as shown in the figure below: Also sketch the output voltage waveform of the voltage limiter circuit when $v_{in}=200\text{ mV}$ peak-to-peak sinusoidal with frequency 50 Hz. The resistances used in the circuit may be assumed to be of the value $1\text{ k}\Omega$. (The op-amp(s) is/are supplied with $\pm 14\text{ V}$ supply)

## qid: EE2-2026-Q4aii
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 4aii
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Find, Sketch, State
- authenticity: ese
- keywords: Analog Electronics; Non-linear Op-Amp Circuit

question_text: For the circuit shown below, find the analytical relation between the output $v_o$ and the input $v_{in}$: Also sketch the output voltage waveform for $v_o(t)$ when the input voltage is $v_{in}=4\sin(100\pi t)$ volts. Also state which component(s) is/are responsible for compensating forward drops across $D_1$ and $D_2$.

## qid: EE2-2026-Q5c
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 5c
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 12 | word_limit: - | directive: Implement, Build, Find
- authenticity: ese
- keywords: Digital Electronics; Digital Logic Implementation; multiplexer; flip-flop

question_text: A Boolean function f is expressed in terms of minterm expression as $f = \sum m(0, 1, 2, 5, 7, 9, 12, 15)$. Implement this function using $8\times 1$ multiplexer and suitable gates. (ii) Build the truth table for the following digital circuit: Also find which type of flip-flop, the overall circuit acts like.

## qid: EE2-2026-Q1a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 1(a)
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Evaluate
- authenticity: official
- keywords: -

question_text: A unity feedback system has open loop transfer function $G(s) = \frac{K}{s(s+q)}$ Evaluate the value of $K$ and $q$ so that settling time and peak overshoot will be 6 seconds and 20% respectively.

## qid: EE2-2026-Q2a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 2(a)
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Determine
- authenticity: official
- keywords: -

question_text: Determine the response of the system shown in the following figure when it is excited by a unit step input.

## qid: EE2-2026-Q3a_i
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 3(a)(i)
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Evaluate
- authenticity: official
- keywords: -

question_text: A system has a unit response as $c(t) = 1 - e^{-0.5t}$. Evaluate its unit impulse and unit ramp response, assuming zero initial conditions.

## qid: EE2-2026-Q3a_ii
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 3(a)(ii)
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Evaluate
- authenticity: official
- keywords: -

question_text: A linear time-invariant system is characterized by the homogeneous state equation. $\begin{bmatrix} \dot{x}_1 \\ \dot{x}_2 \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ -1 & -2 \end{bmatrix} \begin{bmatrix} x_1 \\ x_2 \end{bmatrix}$ Evaluate the solution of the homogeneous equation assuming the initial state vector as $x(0) = \begin{bmatrix} 1 \\ 0 \end{bmatrix}$.

## qid: EE2-2026-Q4a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 4(a)
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 20 | word_limit: - | directive: Design, Determine
- authenticity: official
- keywords: -

question_text: Design a PI controller so that a unity feedback system having open loop transfer function $G(s)H(s) = \frac{10}{(s+2)(s+3)}$ will have the damping ratio of 0.6 and natural frequency of oscillations will be 4 rad/sec. Also determine the characteristic equation of this controller.

## qid: EE2-2026-Q5a
- chunk_tag: EE2|EE2.1|EE2-1
- paper: EE2 | year: 2026 | qno: 5(a)
- syllabus_code: EE2.1 | parent_topic: EE2.1 | micro_theme: -
- marks: 10 | word_limit: - | directive: Write
- authenticity: official
- keywords: -

question_text: Write the state space equation for the following circuit.
