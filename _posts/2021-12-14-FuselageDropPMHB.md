---
title: 'Full Scale Fuselage Drop Test with ATDs and PMHSs'
date: 2021-12-15
permalink: /posts/2021/01/FuselageDropPMHB/
tags:
  - Drop Test
  - Simulation
  - DIC
  - LS-Dyna
  - Testing
  - PMHS
  - ATD Hybrid III 50th Percentile
  - 
---

---
**Contracting Organization**: Federal Aviation Administration  

**Domain**: Drop Test/ Fuselage/ ATDs/ PMHS

**Tools**: Drop Apparatus, Digital Image Correlation (DIC), DAQ, ATDs


## Scope

<div style="text-align: justify;">


As part of an ongoing fifteen-year research program on the Crashworthiness Certification of Composite and Metallic Aircraft Structures, a drop test was conducted at the new AVET facilities with the support of the Injury Biomechanics Research Center of Ohio State University. The OSU team provided their support and expertise with the three PMHS passengers.  <br/>

The test carried four concurrent objectives: to verify and validate the finite element modeling techniques underpinning virtual crashworthiness certification of future aircraft programs; to collect injury data from the seated PMHS occupants and compare their biomechanical response against FAA Hybrid III 50th percentile ATDs; to generate datasets for the verification and validation of finite element human body models intended for injury prediction; and to characterize the injury potential for an occupant in a supine position on a medical stretcher, directly supporting the human body modeling activities of the Office of Naval Research I-Predict program.  <br/>

</div>


## Task

<div style="text-align: justify;">I don't remember the last time I was so excited to come to work that I would be there very early in the morning (except during a LEAP engine certification program at Safran, which was my first time participating in a certification process). I was consistently arriving at work before 5:30 a.m. and still finding colleagues already on site. Between DIC setup under challenging lighting conditions and ATD preparation, I managed to shadow the OSU biomechanics team and gain firsthand exposure to their sensor placement philosophy, their handling protocols for the PMHS occupants, and their calibration and data acquisition procedures. <br/>

The person who shaped my understanding of the instrumentation side most directly was Jonathan Conklin, who headed AVET's calibration lab at the time and held full responsibility for the ATDs from pre-test calibration through post-test teardown and maintenance. Data acquisition was, as it should be, treated as a critical and fragile component of the entire effort, and the collective frustration on site when R&D personnel unfamiliar with its requirements would walk over wiring or mishandle DAQ equipment was considerable and entirely justified. <br/>

Working in close proximity to cadavers was at turns awe-inducing and disorienting, in the way that any sustained encounter with the fundamental materiality of the human body tends to be. What proved equally striking, and what has stayed with me longer, was the parallel immersion in the state of ATD technology and the extent of its limitations. The regulatory standard for aviation emergency landing testing remains a male dummy whose design is rooted in decades-old anthropometric data. The existing female ATD is not derived from female anatomical data at all, but is a geometrically scaled-down version of the male model, carrying none of the physiologically distinct properties of female musculature, spinal geometry, bone density, or injury response. A true 50th percentile female ATD does not exist in regulatory use, and the injury data bears that out in ways that are neither subtle nor acceptable. <br/>

Through daily calibration routines and sustained conversations with Jonathan, a picture of the gap between what the PMHS data was capturing and what the ATDs could actually represent began to take shape. His methodical precision and deep understanding of every sensor, every tolerance, and every procedural boundary made those exchanges genuinely instructive, and the questions they raised about how PMHS-derived datasets could drive improvements in both ATD modeling and fabrication remain as consequential as the test data itself. <br/>


We joked, but not really, that even the regulatory standard for the male ATD does not reflect the average data of the male population as of now, age or health wise. And while testing remains expensive, and PMHS procuration does not guarantee finding average measurements reflecting of the intricacies of the humans of today, this is yet another arguent for certification-by-analysis, and the importance of augmenting simulation capabilities and incorporating them to the certification lifecycle: Libraries of accurate human body models and investigations of crash related simulations involving them would bridge some of the gap that sole physical testing doesn't get right, and allow to dimension better for a more inclusive scope of humans. That's why projects such as the <a href="https://pubmed.ncbi.nlm.nih.gov/38780890/">I Predict</a> (SwRI has an excellent <a href="https://www.swri.org/newsroom/technology-today/enhancing-the-human-experience">introduction</a> to the full concept) are crucial step towards the right direction, and deserve keen attention and serious funding, that's why body donation is priceless in the way it would inform the next generation of inclusive regulations.

</div>

## Nota Bene: ATDs

<div style="text-align: justify;">The <a href="https://www.humaneticsgroup.com/products/anthropomorphic-test-devices/frontal-impact/hybrid-iii-50th-male/hybrid-iii-50th-male">FAA Hybrid III 50th percentile male ATD</a>, which remains the regulatory standard for aviation emergency landing testing, is a derivative of a design developed based on <a href="https://www.tandfonline.com/doi/full/10.1080/23311916.2022.2105558">U.S. anthropometric data from 1976</a>, codified in federal regulation with drawing packages dated as late as <a href="https://www.ecfr.gov/current/title-49/subtitle-B/chapter-V/part-572">1998</a>. The existing female ATD, a 5th percentile figure introduced in 1966, is not derived from female anatomical data but is instead a scaled-down version of the male model, carrying none of the physiologically distinct properties of female musculature, spinal alignment, bone density, or injury response. A true 50th percentile female ATD <a href="https://genderedinnovations.stanford.edu/case-studies/crash.html">does not exist.</a> The consequences are measurable: <a href="https://www.consumerreports.org/car-safety/crash-test-bias-how-male-focused-testing-puts-female-drivers-at-risk/">a 2019 University of Virginia study</a> found that women are 73% more likely to be injured in a frontal crash than men, controlling for age, height, BMI, crash severity, and vehicle model year, and <a href="https://www.legalexaminer.com/whitley/transportation/new-attention-on-gender-gaps-in-crash-safety-why-female-drivers-remain-at-higher-risk/">NHTSA data</a> indicates women sustain roughly 80% more injuries to the neck, chest, and pelvis. The <a href="https://www.nhtsa.gov/sites/nhtsa.gov/files/2024-04/NHTSA-Advanced-Anthropomorphic-Test-Devices-Development-Implementation-041624-v1-tag.pdf">THOR-50M</a>, NHTSA's next-generation male ATD with improved biofidelity and expanded instrumentation, has been under development since 2009 and as of 2024 remains in regulatory validation. An equivalent female THOR is not yet on a confirmed regulatory timeline. <br/>

</div>   

## Learn more

- [Video of the Drop Test](https://www.youtube.com/watch?v=CwaLsrH319g)
- [Media Release](https://www.linkedin.com/pulse/niar-full-scale-fuselage-drop-test-gerardo-olivares)
- [Previous drop test from Olivares' group in the old facilities](https://www.wichita.edu/industry_and_defense/NIAR/Documents/jams-presentations/22-Olivares-Certification-by-Analysis.pdf)



