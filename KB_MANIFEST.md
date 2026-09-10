# KB MANIFEST — Theme Cartographer index shards

- source file: `master_index.csv`
- rows read: 3015
- unique questions (qid+authenticity): 3015
- shards written: 101
- secondary (dual-node) filings: 262

## Integrity report

- true duplicates (same qid AND same authenticity): 0
- EE qids shared across CSE/ESE streams: 458 (expected — not an error; the unique key in EE is qid+authenticity)
- rows missing marks: 16
- directives derived from text: 1
- authenticity breakdown: official=2298, ese=717

> Shard `question_count` includes secondary filings, so the sum of all
> shard counts exceeds the number of distinct questions by exactly
> 262. Per-shard rows carry `primary_node: no` and
> must not be double-counted in cross-shard totals.

## Shard inventory

| File | Paper | Code | Topic | Q | Span |
|---|---|---|---|---|---|
| IDX_EE1_EE1-10_Energy-Conversion-Electrical-Machines.md | EE1 | EE1.10 | Energy Conversion (Electrical Machines) | 7 | 2021–2025 |
| IDX_EE1_EE1-11_Power-Systems-Analysis-and-Control.md | EE1 | EE1.11 | Power Systems: Analysis and Control | 1 | 2025–2025 |
| IDX_EE1_EE1-12_Signals-and-Systems.md | EE1 | EE1.12 | Signals and Systems | 3 | 2016–2021 |
| IDX_EE1_EE1-13_Analog-and-Digital-Communication.md | EE1 | EE1.13 | Analog and Digital Communication | 7 | 2021–2026 |
| IDX_EE1_EE1-1_Transient-Resonant-Circuits.md | EE1 | EE1.1 | Transient & Resonant Circuits | 170 | 2009–2026 |
| IDX_EE1_EE1-2_LTI-Systems-Convolution.md | EE1 | EE1.2 | LTI Systems & Convolution | 128 | 2009–2026 |
| IDX_EE1_EE1-3_Maxwell-s-Equations-Field-Theory.md | EE1 | EE1.3 | Maxwell's Equations & Field Theory | 119 | 2009–2026 |
| IDX_EE1_EE1-4_Device-Characteristics-Diode-BJT-FET.md | EE1 | EE1.4 | Device Characteristics (Diode/BJT/FET) | 163 | 2009–2026 |
| IDX_EE1_EE1-5_Sequential-Circuits.md | EE1 | EE1.5 | Sequential Circuits | 131 | 2009–2026 |
| IDX_EE1_EE1-6_DC-Machines.md | EE1 | EE1.6 | DC Machines | 156 | 2009–2026 |
| IDX_EE1_EE1-7_Choppers-Inverters-DC-DC-Converters.md | EE1 | EE1.7 | Choppers, Inverters & DC-DC Converters | 85 | 2009–2026 |
| IDX_EE1_EE1-8_Random-Variables-Probability.md | EE1 | EE1.8 | Random Variables & Probability | 97 | 2009–2026 |
| IDX_EE1_EE1-9_Control-Systems.md | EE1 | EE1.9 | Control Systems | 5 | 2016–2016 |
| IDX_EE2_EE2-1_Microprocessors-and-Computer-Organisatio.md | EE2 | EE2.1 | Microprocessors and Computer Organisation | 93 | 2016–2026 |
| IDX_EE2_EE2-2_Communication-Systems-and-Modulation.md | EE2 | EE2.2 | Communication Systems and Modulation | 60 | 2016–2026 |
| IDX_EE2_EE2-3_Transient-and-Time-Response-Analysis.md | EE2 | EE2.3 | Transient and Time Response Analysis | 58 | 2017–2026 |
| IDX_EE2_EE2-4_Transformers.md | EE2 | EE2.4 | Transformers | 118 | 2016–2026 |
| IDX_EE2_EE2-5_Transmission-Line-and-Cable-Performance.md | EE2 | EE2.5 | Transmission Line and Cable Performance | 62 | 2016–2026 |
| IDX_EE2_EE2-6_Controlled-Rectifiers-and-Converters.md | EE2 | EE2.6 | Controlled Rectifiers and Converters | 71 | 2009–2026 |
| IDX_EE2_EE2-COMM-01_Communication-PCM-DPCM-Delta-Modulation.md | EE2 | EE2-COMM-01 | Communication: PCM / DPCM / Delta Modulation | 25 | 2009–2025 |
| IDX_EE2_EE2-COMM-02_Communication-Digital-Modulation-ASK-PSK.md | EE2 | EE2-COMM-02 | Communication: Digital Modulation (ASK/PSK/FSK) | 12 | 2012–2024 |
| IDX_EE2_EE2-COMM-03_Communication-Error-Control-Coding.md | EE2 | EE2-COMM-03 | Communication: Error Control Coding | 23 | 2009–2025 |
| IDX_EE2_EE2-COMM-04_Communication-Information-Measure-Source.md | EE2 | EE2-COMM-04 | Communication: Information Measure & Source Coding | 8 | 2016–2025 |
| IDX_EE2_EE2-COMM-05_Communication-Data-Networks-7-Layer-Arch.md | EE2 | EE2-COMM-05 | Communication: Data Networks & 7-Layer Architecture | 6 | 2010–2024 |
| IDX_EE2_EE2-CTRL-01_Control-Systems-Elements-Block-Diagrams.md | EE2 | EE2-CTRL-01 | Control Systems: Elements & Block Diagrams | 29 | 2009–2025 |
| IDX_EE2_EE2-CTRL-02_Control-Systems-Time-Transform-Domain-LT.md | EE2 | EE2-CTRL-02 | Control Systems: Time & Transform Domain (LTI Analysis) | 22 | 2009–2025 |
| IDX_EE2_EE2-CTRL-03_Control-Systems-Stability-Root-Locus-Bod.md | EE2 | EE2-CTRL-03 | Control Systems: Stability, Root Locus, Bode/Nyquist, Compensators | 39 | 2009–2025 |
| IDX_EE2_EE2-CTRL-04_Control-Systems-P-PI-PID-Controllers.md | EE2 | EE2-CTRL-04 | Control Systems: P, PI, PID Controllers | 4 | 2014–2024 |
| IDX_EE2_EE2-CTRL-05_Control-Systems-State-Variable-Represent.md | EE2 | EE2-CTRL-05 | Control Systems: State-Variable Representation & Analysis | 11 | 2009–2023 |
| IDX_EE2_EE2-DE-01_Digital-Electronics-Microprocessors-8085.md | EE2 | EE2-DE-01 | Digital Electronics & Microprocessors: 8085/Peripherals | 90 | 2009–2025 |
| IDX_EE2_EE2-MEAS-01_Measurements-Error-Analysis-Bridge-Measu.md | EE2 | EE2-MEAS-01 | Measurements: Error Analysis & Bridge Measurements | 39 | 2009–2025 |
| IDX_EE2_EE2-MEAS-02_Measurements-Signal-Conditioning-Electro.md | EE2 | EE2-MEAS-02 | Measurements: Signal Conditioning & Electronic Instruments | 14 | 2010–2025 |
| IDX_EE2_EE2-MEAS-03_Measurements-Transducers.md | EE2 | EE2-MEAS-03 | Measurements: Transducers | 18 | 2009–2025 |
| IDX_EE2_EE2-PWR-01_Power-Systems-HVDC-Transmission.md | EE2 | EE2-PWR-01 | Power Systems: HVDC Transmission | 7 | 2010–2024 |
| IDX_EE2_EE2-PWR-02_Power-Systems-Computer-Aided-Numeric-Pro.md | EE2 | EE2-PWR-02 | Power Systems: Computer-Aided / Numeric Protection | 3 | 2015–2024 |
| IDX_EE2_EE2-PWR-03_Power-Systems-System-Stability-Swing-Cur.md | EE2 | EE2-PWR-03 | Power Systems: System Stability (Swing Curves) | 5 | 2009–2012 |
| IDX_EE2_EE2-PWR-04_Power-Systems-Overcurrent-Differential-D.md | EE2 | EE2-PWR-04 | Power Systems: Overcurrent/Differential/Distance Protection & Circuit Breakers | 39 | 2009–2025 |
| IDX_EE2_EE2-PWR-05_Power-Systems-Transmission-Line-Performa.md | EE2 | EE2-PWR-05 | Power Systems: Transmission Line Performance & Load Flow | 47 | 2009–2025 |
| IDX_EE2_EE2-PWR-06_Power-Systems-Symmetrical-Components-Fau.md | EE2 | EE2-PWR-06 | Power Systems: Symmetrical Components & Fault Analysis | 16 | 2009–2025 |
| IDX_EE2_EE2-UNMAPPED_Unmapped-Outside-listed-EE2-syllabus-top.md | EE2 | EE2-UNMAPPED | Unmapped / Outside listed EE2 syllabus (topic not found in official syllabus lines) | 16 | 2011–2024 |
| IDX_ESSAY_ESSAY_Essay-Writing.md | ESSAY | ESSAY | Essay Writing | 108 | 2013–2026 |
| IDX_GS1_GS1-10_World-Physical-Geography.md | GS1 | GS1.10 | World Physical Geography | 33 | 2013–2026 |
| IDX_GS1_GS1-11_Natural-Resources-Industry-Location.md | GS1 | GS1.11 | Natural Resources & Industry Location | 44 | 2013–2026 |
| IDX_GS1_GS1-12_Geophysical-Phenomena.md | GS1 | GS1.12 | Geophysical Phenomena | 35 | 2013–2026 |
| IDX_GS1_GS1-1_Art-Literature-Architecture.md | GS1 | GS1.1 | Art, Literature & Architecture | 36 | 2013–2026 |
| IDX_GS1_GS1-2_Modern-Indian-History.md | GS1 | GS1.2 | Modern Indian History | 18 | 2013–2026 |
| IDX_GS1_GS1-3_Freedom-Struggle.md | GS1 | GS1.3 | Freedom Struggle | 19 | 2013–2026 |
| IDX_GS1_GS1-4_Post-Independence-Consolidation.md | GS1 | GS1.4 | Post-Independence Consolidation | 11 | 2013–2026 |
| IDX_GS1_GS1-5_World-History.md | GS1 | GS1.5 | World History | 17 | 2013–2025 |
| IDX_GS1_GS1-6_Indian-Society-Diversity.md | GS1 | GS1.6 | Indian Society & Diversity | 23 | 2014–2026 |
| IDX_GS1_GS1-7_Women-Population-Urbanization.md | GS1 | GS1.7 | Women, Population & Urbanization | 36 | 2013–2026 |
| IDX_GS1_GS1-8_Globalization-Indian-Society.md | GS1 | GS1.8 | Globalization & Indian Society | 14 | 2013–2026 |
| IDX_GS1_GS1-9_Social-Empowerment-Secularism.md | GS1 | GS1.9 | Social Empowerment & Secularism | 15 | 2013–2026 |
| IDX_GS2_GS2-10_Government-Policies-Interventions.md | GS2 | GS2.10 | Government Policies & Interventions | 14 | 2013–2026 |
| IDX_GS2_GS2-11_Development-Processes-NGOs.md | GS2 | GS2.11 | Development Processes & NGOs | 14 | 2013–2025 |
| IDX_GS2_GS2-12_Welfare-Schemes-for-Vulnerable-Sections.md | GS2 | GS2.12 | Welfare Schemes for Vulnerable Sections | 13 | 2013–2026 |
| IDX_GS2_GS2-13_Social-Sector-Health-Education-HR.md | GS2 | GS2.13 | Social Sector (Health/Education/HR) | 16 | 2013–2026 |
| IDX_GS2_GS2-14_Poverty-Hunger.md | GS2 | GS2.14 | Poverty & Hunger | 10 | 2015–2026 |
| IDX_GS2_GS2-15_Governance-E-Governance.md | GS2 | GS2.15 | Governance & E-Governance | 18 | 2013–2026 |
| IDX_GS2_GS2-16_Civil-Services.md | GS2 | GS2.16 | Civil Services | 6 | 2014–2026 |
| IDX_GS2_GS2-17_India-Neighborhood.md | GS2 | GS2.17 | India & Neighborhood | 10 | 2013–2026 |
| IDX_GS2_GS2-18_International-Groupings.md | GS2 | GS2.18 | International Groupings | 29 | 2013–2026 |
| IDX_GS2_GS2-19_Diaspora-Foreign-Policy-Impact.md | GS2 | GS2.19 | Diaspora & Foreign Policy Impact | 9 | 2017–2026 |
| IDX_GS2_GS2-1_Indian-Constitution.md | GS2 | GS2.1 | Indian Constitution | 29 | 2013–2025 |
| IDX_GS2_GS2-20_International-Institutions.md | GS2 | GS2.20 | International Institutions | 13 | 2013–2025 |
| IDX_GS2_GS2-2_Centre-State-Relations.md | GS2 | GS2.2 | Centre-State Relations | 28 | 2013–2026 |
| IDX_GS2_GS2-3_Separation-of-Powers.md | GS2 | GS2.3 | Separation of Powers | 6 | 2013–2020 |
| IDX_GS2_GS2-4_Constitutional-Comparison.md | GS2 | GS2.4 | Constitutional Comparison | 6 | 2022–2026 |
| IDX_GS2_GS2-5_Parliament-State-Legislatures.md | GS2 | GS2.5 | Parliament & State Legislatures | 17 | 2013–2026 |
| IDX_GS2_GS2-6_Executive-Judiciary.md | GS2 | GS2.6 | Executive & Judiciary | 16 | 2013–2026 |
| IDX_GS2_GS2-7_Representation-of-People-s-Act.md | GS2 | GS2.7 | Representation of People's Act | 6 | 2019–2026 |
| IDX_GS2_GS2-8_Constitutional-Bodies.md | GS2 | GS2.8 | Constitutional Bodies | 15 | 2014–2026 |
| IDX_GS2_GS2-9_Statutory-Regulatory-Bodies.md | GS2 | GS2.9 | Statutory/Regulatory Bodies | 12 | 2013–2025 |
| IDX_GS3_GS3-10_Investment-Models.md | GS3 | GS3.10 | Investment Models | 8 | 2013–2022 |
| IDX_GS3_GS3-11_S-T-Developments-Everyday-Applications.md | GS3 | GS3.11 | S&T Developments & Everyday Applications | 13 | 2013–2026 |
| IDX_GS3_GS3-12_Indigenous-S-T-Achievements.md | GS3 | GS3.12 | Indigenous S&T Achievements | 8 | 2014–2019 |
| IDX_GS3_GS3-13_IT-Space-Robotics-Nanotech-Biotech-IPR.md | GS3 | GS3.13 | IT, Space, Robotics, Nanotech, Biotech & IPR | 25 | 2013–2026 |
| IDX_GS3_GS3-14_Conservation-Pollution-EIA.md | GS3 | GS3.14 | Conservation, Pollution & EIA | 31 | 2013–2026 |
| IDX_GS3_GS3-15_Disaster-Disaster-Management.md | GS3 | GS3.15 | Disaster & Disaster Management | 20 | 2013–2026 |
| IDX_GS3_GS3-16_Development-Extremism-Linkages.md | GS3 | GS3.16 | Development & Extremism Linkages | 8 | 2013–2026 |
| IDX_GS3_GS3-17_External-State-Non-State-Actors-Internal.md | GS3 | GS3.17 | External State/Non-State Actors & Internal Security | 12 | 2014–2025 |
| IDX_GS3_GS3-18_Cyber-Security-Media-Money-Laundering.md | GS3 | GS3.18 | Cyber Security, Media & Money Laundering | 19 | 2013–2026 |
| IDX_GS3_GS3-19_Border-Security-Organised-Crime-Terroris.md | GS3 | GS3.19 | Border Security & Organised Crime-Terrorism Linkages | 17 | 2013–2026 |
| IDX_GS3_GS3-1_Indian-Economy-Planning-Resource-Mobiliz.md | GS3 | GS3.1 | Indian Economy: Planning, Resource Mobilization, Growth & Employment | 20 | 2014–2026 |
| IDX_GS3_GS3-20_Security-Forces-Agencies.md | GS3 | GS3.20 | Security Forces & Agencies | 4 | 2015–2023 |
| IDX_GS3_GS3-2_Inclusive-Growth.md | GS3 | GS3.2 | Inclusive Growth | 10 | 2014–2026 |
| IDX_GS3_GS3-3_Government-Budgeting.md | GS3 | GS3.3 | Government Budgeting | 11 | 2013–2025 |
| IDX_GS3_GS3-4_Cropping-Patterns-Irrigation-Storage-Mar.md | GS3 | GS3.4 | Cropping Patterns, Irrigation, Storage, Marketing & e-Technology | 29 | 2014–2026 |
| IDX_GS3_GS3-5_Farm-Subsidies-MSP-PDS-Buffer-Stock-Food.md | GS3 | GS3.5 | Farm Subsidies, MSP, PDS, Buffer Stock & Food Security | 16 | 2013–2026 |
| IDX_GS3_GS3-6_Food-Processing-Industries-Supply-Chain.md | GS3 | GS3.6 | Food Processing Industries & Supply Chain | 8 | 2015–2026 |
| IDX_GS3_GS3-7_Land-Reforms.md | GS3 | GS3.7 | Land Reforms | 6 | 2013–2024 |
| IDX_GS3_GS3-8_Liberalization-Industrial-Policy.md | GS3 | GS3.8 | Liberalization & Industrial Policy | 9 | 2013–2025 |
| IDX_GS3_GS3-9_Infrastructure-Energy-Ports-Roads-Airpor.md | GS3 | GS3.9 | Infrastructure: Energy, Ports, Roads, Airports, Railways | 15 | 2013–2026 |
| IDX_GS4_GS4-1_Ethics-and-Human-Interface.md | GS4 | GS4.1 | Ethics and Human Interface | 32 | 2013–2026 |
| IDX_GS4_GS4-2_Attitude.md | GS4 | GS4.2 | Attitude | 8 | 2014–2022 |
| IDX_GS4_GS4-3_Aptitude-and-Foundational-Values-for-Civ.md | GS4 | GS4.3 | Aptitude and Foundational Values for Civil Service | 44 | 2013–2026 |
| IDX_GS4_GS4-4_Emotional-Intelligence.md | GS4 | GS4.4 | Emotional Intelligence | 10 | 2013–2024 |
| IDX_GS4_GS4-5_Contributions-of-Moral-Thinkers-and-Phil.md | GS4 | GS4.5 | Contributions of Moral Thinkers and Philosophers | 50 | 2013–2026 |
| IDX_GS4_GS4-6_Public-Civil-Service-Values-and-Ethics-i.md | GS4 | GS4.6 | Public/Civil Service Values and Ethics in Public Administration | 67 | 2013–2026 |
| IDX_GS4_GS4-7_Probity-in-Governance.md | GS4 | GS4.7 | Probity in Governance | 34 | 2013–2026 |
| IDX_GS4_GS4-8_Case-Studies.md | GS4 | GS4.8 | Case Studies | 40 | 2014–2026 |
