# Research Analytics Portfolio by Mouhamad Ibrahim, PhD

Welcome to my research-driven analytics portfolio! This repository showcases a collection of research projects focused on data analysis, sensor optimization, and bioimpedance modeling conducted during my PhD and post-doc work.

---

**Pioneered data storytelling, authoring 5+ highly cited papers and transforming data into industry-shaping insights—one ranked in the top 25% by Altmetric. Notably, one of my research publications, ["Geometric parameters optimization of planar interdigitated electrodes for bioimpedance spectroscopy"](https://dimensions.altmetric.com/details/81105616#score), was ranked in the top 25% by Altmetric, reflecting the significant impact and reach of my work in the field.**  
[View my full publication list on Google Scholar](https://scholar.google.com/citations?user=b7XuxZIAAAAJ&hl=en)

---

**Industry Adoption and Impact**  
Throughout my research, I engineered models that expanded analysis capabilities by 65% and boosted sensor sensitivity by 18% at IJL. The work led to significant breakthroughs in sensor design, culminating in the adoption and patenting of the optimized conductivity sensor design by 4 industry leaders [as documented here](https://dimensions.altmetric.com/details/81105616/patents). The key milestones include:

- Upgraded conductivity sensor design with MATLAB by engineering bioimpedance models, mining physiological characteristics as electrical elements, resulting in adoption by 4 industry leaders, each securing a patent.
- Identified the optimal sensor design ratio (S/W = 0.66), which expanded the analysis band by 65% and boosted sensitivity by 18%.
- Expanded measurement analysis band from 600 MHz to 988 MHz via engineering optimal biosensors, significantly improving sensitivity for health applications by 18%.

This repository documents the full research process, including key calculations, simulations, and the real-world impact of these contributions.

---

## Table of Contents

1. [PhD Research: Bioimpedance Modeling and Sensor Optimization](#phd-research-bioimpedance-modeling-and-sensor-optimization)
   - [Engineering Models to Determine Optimal Sensor Design (S/W = 0.66)](#1-engineering-models-to-determine-optimal-sensor-design-sw--066)
   - [Calculation of the 65% Improvement in Analysis Effectiveness](#2-calculation-of-the-65-improvement-in-analysis-effectiveness)
   - [Calculation of the 18% Sensitivity Improvement](#3-calculation-of-the-18-sensitivity-improvement)
   - [References and Resources](#references-and-resources-for-bioimpedance-modeling-and-sensor-optimization)
2. [Post-Doc Research](#post-doc-research)
   - [Development of an Instrumented Microfluidic Platform (Gliomatrack) for Studying Glioma Cell Adhesion and Migration on a 3D Fibrous Scaffold Mimicking Neural Topography](#1-development-of-an-instrumented-microfluidic-platform-gliomatrack-for-studying-glioma-cell-adhesion-and-migration-on-a-3d-fibrous-scaffold-mimicking-neural-topography)
   - **[Placeholder for Post-Doc Project 2](#placeholder-for-post-doc-project-2)**
   - [References and Resources](#references-and-resources-for-post-doc-research)

## PhD Research: Bioimpedance Modeling and Sensor Optimization

### 1. Engineering Models to Determine Optimal Sensor Design (S/W = 0.66)

This section covers the analytical and experimental work that led to the identification of the optimal ratio for sensor geometry (S/W = 0.66), resulting in a 65% improvement in analysis effectiveness.

#### Project Overview
The primary objective was to optimize the design of planar interdigitated electrodes for bioimpedance spectroscopy. This involved:
- Developing a mathematical model to determine the ideal gap (S) to width (W) ratio.
- Validating the model through simulations and experimental data.

#### Mathematical Modeling and Insights
The bioimpedance model was developed by analyzing physiological characteristics as electrical components. The key steps involved:
- Deriving impedance equations based on electrode geometry.
- Conducting simulations to identify the optimal sensor configuration.
- The results demonstrated that the S/W ratio of 0.66 provided the best performance, expanding the analysis band and reducing the cutoff frequency.

### 2. Calculation of the 65% Improvement in Analysis Effectiveness

The analysis band was expanded by 65% by comparing the optimal sensor (S/W = 0.66) with other configurations. The calculation process included:
- Determining the cutoff frequency for each configuration.
- Calculating the analysis band as the difference between the maximum frequency and the cutoff frequency.
- The 65% improvement was the highest observed across the tested sensors.

#### Calculation Process
- **Optimized Sensor (S/W = 0.66):** F(Low) = 1.2 × 10⁵ Hz  
  Analysis Band = 9.88 × 10⁶ Hz
- **Non-Optimized Sensor (S/W = 4):** F(Low) = 40 × 10⁵ Hz  
  Analysis Band = 6 × 10⁶ Hz

**Improvement Calculation:**  
The analysis band increased from 6 × 10⁶ Hz (non-optimized) to 9.88 × 10⁶ Hz (optimized), leading to an approximate 65% enhancement. The calculation is:  
Improvement (%) = [(9.88 × 10⁶ - 6 × 10⁶) / 6 × 10⁶] × 100 ≈ 65%

### 3. Calculation of the 18% Sensitivity Improvement

This section documents the improvement in sensor sensitivity achieved by reducing measurement errors:
- The optimized sensor showed a relative change in conductivity of 4%, compared to 22% for non-optimized sensors.
- The difference in error rates (22% - 4%) equates to an 18% improvement in sensitivity.

#### Experiment Details
- Conductivity measurements were compared against standard values (0.7 S/m).
- The optimized sensor (Sensor 5) outperformed non-optimized configurations (Sensors 7 and 8) by providing more accurate readings.

### References and Resources for Bioimpedance Modeling and Sensor Optimization
- [Download the publication: Geometric parameters optimization of planar interdigitated electrodes for bioimpedance spectroscopy](resources/Geometric%20parameters%20optimization%20of%20planar%20interdigitated%20electrodes%20for%20bioimpedance%20spectroscopy.pdf)
- [Access the publication online](https://doi.org/10.5617/jeb.304)
- [Access the thesis for further details](https://hal.univ-lorraine.fr/tel-01749652)  
  **Citation:**  
  Mouhamad Ibrahim. *Mesure de bioimpédance électrique par capteurs interdigités*. Médecine humaine et pathologie. Université de Lorraine, 2012. Français. ⟨NNT: 2012LORR0307⟩. ⟨tel-01749652⟩

## Post-Doc Research

### 1. Development of an Instrumented Microfluidic Platform (Gliomatrack) for Studying Glioma Cell Adhesion and Migration on a 3D Fibrous Scaffold Mimicking Neural Topography

#### Project Overview
This project involved developing a microfluidic platform integrated with a 3D fibrous scaffold that simulates the brain’s neural environment. The platform was designed to study glioma cell adhesion and migration, offering insights into the factors influencing glioma growth and migration for personalized therapeutic strategies.

#### Objectives
- Develop a 3D fibrous scaffold that accurately replicates the neural topography.
- Design and validate a microfluidic platform that differentiates between highly migratory and proliferative gliomas.
- Explore factors influencing glioma growth and migration, focusing on potential therapeutic interventions.

#### Collaboration Teams
The project was a cross-functional collaboration between:
- **IEMN**: The primary team responsible for BioMEMS and microfluidic platform development.
- **IEM**: Focused on electrospinning synthesis of fibers and chemical biofunctionalization.
- **IRI**: Specialized in surface chemistry, patterning, and biosensors.
- **INM**: Handled glioma cell studies and clinical validation.

#### Methodology Highlights
- **Electrospinning Synthesis**: Created axon-mimicking fibers to study cell behavior.
- **Microfluidic Platform Development**: Incorporated shear force generators to monitor single-cell motility.
- **Cross-Functional Data Analysis**: Integrated fiber analysis, cell culture experiments, and microfluidic design for a comprehensive study.

#### Results and Impact (70% and 60% Metrics Focus)
- **400% Improvement in Data Collection Efficiency**: The multi-zone, single-flow device enabled simultaneous measurements across five distinct shear stress conditions, reducing wasted time by 5x.
- **30% Error Reduction via Strategic Bubble Prevention**: A novel dual-gate injection system was engineered to eliminate air bubbles, a common cause of up to 30% measurement errors in microfluidic systems. By integrating this technique, the device significantly improved data reliability and elevated overall data quality.
- **70% Reduction in Production Costs**: The shift from silicon to PDMS for microfluidic device fabrication led to substantial cost savings by simplifying the fabrication process and reducing material expenses.
- **60% Time Savings in Production**: By utilizing PDMS over silicon, the device creation cycle was streamlined, reducing time spent on fabrication by 60%.

#### Context and Problem Statement
The initial microfluidic device design faced multiple issues:
1. **Fluidic Resistance**: Narrow lateral access tubes (75 µm) led to high fluidic resistance, limiting achievable shear stress and affecting the effectiveness of cell detachment studies.
2. **Stair-Step Flow Profiles**: Inconsistent shear stress across the channel led to memory effects during detachment protocols, making it difficult to obtain reproducible results.
3. **Air Bubble Formation**: Air bubbles disrupted flow patterns, obscured optical readings, and interfered with cell adhesion measurements, leading to up to 30% inaccuracies in data.
4. **High Production Costs and Long Fabrication Time**: The use of silicon for device fabrication was costly and time-consuming due to the complex processes involved, including photolithography and etching.

#### Solution and Improvements
The newly engineered multi-zone microfluidic device introduced the following advancements:
1. **Optimized Access Points**: Larger top-access fluidic channels (800 µm) reduced fluidic resistance, allowing for higher shear stress levels, which are critical for accurate studies.
2. **Single-Flow, Multi-Zone Design**: The device’s five zones, with varying widths (500 µm to 2531 µm), generated a wide range of shear stresses (14 dy/cm² to 75 dy/cm²) using a single flow rate (1500 µl/min).
3. **Advanced Bubble Prevention Techniques**: Developed a dual-gate injection system and implemented strategic channel designs, eliminating air bubbles and reducing measurement errors by 30%.
4. **PDMS-Based Fabrication**: By transitioning from silicon to PDMS, production costs were reduced by 70% and fabrication time was cut by 60%, streamlining the creation cycle and making the process more accessible for rapid prototyping.

#### Quantified Impact
- **400% Increase in Data Collection Efficiency**: The design allowed for comprehensive experiments in less time, reducing wasted time by 5x.
- **30% Error Reduction**: Improved data quality and reliability through effective bubble mitigation.
- **70% Reduction in Production Costs**: Lowered overall production expenses by shifting from silicon to PDMS.
- **60% Time Savings in Production**: Simplified the fabrication process, reducing the time required to create the device.

### References and Resources for Post-Doc Research

1. **[5 Visualization Zones Single-Flow Device (PDF)](resources/5%20Visualization%20Zones%20Single-Flow%20Device.pdf)**  
   Detailed design document explaining the development of the multi-zone microfluidic device, featuring variable widths and shear stress conditions.

2. **[Gliomatrack Project Results (PDF)](resources/Gliomatrack%20Project%20Results.pdf)**  
   Comprehensive presentation of the experimental results, challenges encountered, and metrics achieved throughout the Gliomatrack project.

3. **[Core: PDMS Fabrication Benefits (PDF)](https://core.ac.uk/download/pdf/4401627.pdf)**  
   Resource on the advantages of using PDMS in microfluidic device fabrication over silicon, highlighting cost and time savings.

4. **[NCBI: Microfluidic Device Fabrication (Article)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7921936/)**  
   Overview of the benefits of PDMS-based microfluidic devices, particularly in terms of rapid prototyping and cost-effectiveness.



## Contact
For more information, feel free to reach out at [mouhamaad.ibrahim@gmail.com](mailto:mouhamaad.ibrahim@gmail.com).
