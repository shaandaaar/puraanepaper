# INDEX SHARD — EE2 · EE2-COMM-02 · EE2-COMM-02

chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
paper: EE2
syllabus_code: EE2-COMM-02
parent_topic: EE2-COMM-02
years_present: 2012, 2013, 2015, 2017, 2019, 2020, 2021, 2022, 2024
question_count: 12

Every row below is self-describing. Cite the qid exactly as written.

## qid: EE2-2012-Q3c
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2012 | qno: 3c
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 20 | word_limit: - | directive: Explain
- authenticity: official
- keywords: Digital Modulation/Block Codes

question_text: (c) (i) Explain ASK, FSK and PSK modulation schemes used for transmitting the data. Draw clearly the block diagram for coherent detection and non-coherent detection of FSK modulation scheme. (ii) A (6,3) systematic linear block code encodes the information sequence $X=(x_1,x_2,x_3)$ into code word $C = (c_1, c_2, c_3, c_4, c_5, c_6)$ such that $c_4$ is a parity check on $c_1$ and $c_2$, to make the overall parity even, i.e., $c_1\oplus c_2\oplus c_4=0$. Similarly $c_5$ is a parity check on $c_2$ and $c_3$, and $c_6$ is a parity check on $c_1$ and $c_3$. (1) Determine the generator matrix of this code. (2) Find the parity check matrix for this code. (3) Using the parity check matrix, determine the minimum distance of this code. (4) How many errors of this code are capable of correcting?

## qid: EE2-2013-Q5c
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2013 | qno: 5c
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 10 | word_limit: - | directive: What
- authenticity: official
- keywords: FSK/PSK Signaling

question_text: (c) (i) What is the need for sending digital data over analog carriers? In this regard how is FSK better than PSK ? (ii) With reference to the 7 layer architecture of data networks, distinguish between Protocol Data Unit (PDU) and Service Data Unit (SDU).

## qid: EE2-2013-Q7c
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2013 | qno: 7c
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 10 | word_limit: - | directive: What
- authenticity: official
- keywords: Addressing Modes; BPSK Formulation vs Baseband Transmission

question_text: (c) What are the advantages of digital carrier systems over Baseband digital transmission ? Develop the mathematical formulation for a BPSK signal.

## qid: EE2-2015-Q7b
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2015 | qno: 7b
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 20 | word_limit: - | directive: Draw
- authenticity: official
- keywords: ASK, FSK and PSK Waveform Representation; QPSK and Data-Rate Improvement

question_text: (i) Draw the waveforms showing modulation of the binary signal 0011010010 using ASK, FSK and PSK. (ii) What is Quadrature Phase Shift Keying (QPSK)? How does it help to improve the data transmission rate?

## qid: EE2-2017-Q8b
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2017 | qno: 8b
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 15 | word_limit: - | directive: Write
- authenticity: official
- keywords: QPSK Signal-Space Diagram

question_text: (b) Write down expression for the signal set and draw signal space diagram for coherent quadri-phase shift keying system. For the input binary sequence 11001001, sketch inphase and quadrature components of the modulated quadri-phase shift keying signal.

## qid: EE2-2019-Q5c
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2019 | qno: 5c
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 10 | word_limit: - | directive: Find
- authenticity: official
- keywords: Gram-Schmidt Orthogonalization of Signal Waveforms; Orthonormal Basis and Signal-Space Diagram

question_text: Four signals $s_{1}(t)$, $s_{2}(t)$, $s_{3}(t)$ and $s_{4}(t)$ are shown in the figure below. Find an orthonormal basis for this set of signals by making use of the Gram-Schmidt orthogonalization procedure. Draw the corresponding signal space diagram:

## qid: EE2-2019-Q6b
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2019 | qno: 6b
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 20 | word_limit: - | directive: Show
- authenticity: official
- keywords: Binary ASK Error Probability Derivation; PLL Demodulation of a Phase-Modulated Data Signal

question_text: (i) Consider an ON-OFF keying version of a binary ASK system, where symbol 1 (hypothesis $H_{1}$) is denoted by transmitting a DC level of amplitude A and symbol 0 (hypothesis $H_{0}$) is denoted by not communicating any signal over the channel. Assume that symbols 0 and 1 occur with equal probability. The channel is perturbed by Additive White Gaussian Noise (AWGN) with zero mean and variance $\sigma^{2}$. Show that the average probability of error for this ASK system is $$P_{e}=Q\left[\frac{A}{2\sigma}\right],$$ where $Q(\alpha)\triangleq\frac{1}{\sqrt{2\pi}}\int_{\alpha}^{\infty}e^{-u^{2}/2}du$ (ii) Consider a phase-locked loop (PLL) consisting of a multiplier, loop filter and voltage-controlled oscillator (VCO). Let the signal applied to the multiplier input be defined as $s(t)=A_{c}\cos[2\pi f_{c}t+k_{p}\cdot m(t)]$, where $k_{p}$ is the phase sensitivity and data signal is having value +1 for binary symbol 1 and -1 for binary symbol 0. The VCO output is $r(t)=A_{v}\sin[2\pi f_{c}t+\theta(t)]$. Evaluate the loop filter output, assuming that the filter removes the modulated components with frequency $2f_{c}$. Show that the loop filter output is proportional to the data signal $m(t)$, when the loop is phase-locked, that is, $\theta(t)=0$. Illustrate your answer with a neat sketch.

## qid: EE2-2020-Q4b
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2020 | qno: 4b
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 20 | word_limit: - | directive: Explain
- authenticity: official
- keywords: Digital Modulation Power/Bandwidth Efficiency Tradeoffs

question_text: (b) (i) Explain the power efficiency and bandwidth efficiency of a digital modulation scheme. (ii) Comment on the power efficiency for a given bandwidth efficiency for a good modulation scheme. (iii) Comment on the bandwidth efficiency for a given power efficiency for a good modulation scheme. (iv) Compare the bandwidth efficiency of ASK and QAM modulation techniques. (v) Comment on the bandwidth efficiency of M-ary orthogonal signalling scheme for large M. (vi) Write the fundamental tradeoff equation between power and bandwidth efficiency under which reliable communication is possible.

## qid: EE2-2021-Q3b
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2021 | qno: 3b
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 20 | word_limit: - | directive: Find
- authenticity: official
- keywords: Optimum Detector Error Probability (Laplacian Noise)

question_text: (b) Consider a signal detector with an input $$r=\pm A+n$$ where $+A$ and $-A$ occur with equal probability and the noise variable $n$ is characterized by the Laplacian pdf shown. (i) Determine the probability of error as a function of the parameters A and $\sigma$. (ii) Determine the SNR required to achieve an error probability of $10^{-6}.$

## qid: EE2-2022-Q8b
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2022 | qno: 8b
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: unknown | word_limit: - | directive: Calculate/Solve
- authenticity: official
- keywords: IDMT & Earth Fault Relays; Technical Application

question_text: (b) The received signal in a binary communication system that employs antipodal signals is $r(t)=s(t)+n(t)$ where $s(t)$ is shown in the figure below and $n(t)$ is AWGN with power spectral density $\frac{N_{0}}{2}\frac{\text{W}}{\text{Hz}}$ :

## qid: EE2-2022-Q8i-2
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2022 | qno: 8i
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 20 | word_limit: - | directive: Sketch
- authenticity: official
- keywords: IDMT & Earth Fault Relays; Technical Application

question_text: (i) Sketch the impulse response of the filter matched to $s(t)$. (ii) Sketch the output of the matched filter when the input is s(t). (iii) Determine the variance of the noise at the output of the matched filter at $t=3$. (iv) Determine the probability of error as a function of A and $N_{0}$.

## qid: EE2-2024-Q1e
- chunk_tag: EE2|EE2-COMM-02|EE2-COMM-02
- paper: EE2 | year: 2024 | qno: 1e
- syllabus_code: EE2-COMM-02 | parent_topic: EE2-COMM-02 | micro_theme: -
- marks: 10 | word_limit: - | directive: Explain
- authenticity: official
- keywords: Ohmmeter Scale; Cable Loss

question_text: Q1. (e) Explain the concept of a constellation diagram. Draw the PSK signal constellations for the value of $M=2$, 4 and 8, if all have same transmitted signal energy $E_{s}$.
