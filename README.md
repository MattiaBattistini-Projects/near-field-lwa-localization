# Near-Field User Localization with Leaky-Wave Antennas

**BSc Thesis in Electronic Engineering · University of Bologna (Cesena Campus)**

> *Study and Simulation of Leaky-Wave Antenna Systems for Near-Field User Localization*

![MATLAB](https://img.shields.io/badge/MATLAB-simulation-orange)
![Topic](https://img.shields.io/badge/topic-6G%20%7C%20RF%20%7C%20Antennas-blue)
![Status](https://img.shields.io/badge/code-coming%20soon-lightgrey)

---

## Demo

[![Watch the demo](https://img.youtube.com/vi/GjaPi_-ZlkM/hqdefault.jpg)](https://youtu.be/GjaPi_-ZlkM)

*Simulation of a multi-port leaky-wave antenna locating three users in the near-field through frequency scanning.*

---

## Overview

Future 6G networks will operate at very high frequencies, where large antenna apertures place many users in the **near-field (radiative Fresnel) region**. In this regime, the classic far-field assumptions no longer hold, and both the **angle and the distance** of a user can be estimated.

**Leaky-wave antennas (LWAs)** are a promising low-complexity solution: their main beam steers with frequency, so each direction in space is associated with a different frequency.

In this thesis I developed a **MATLAB simulator** to study LWA-based systems for near-field user localization, including:

- modelling of a **multi-port LWA aperture** and its frequency-scanning beams;
- simulation of **near-field scenarios** with multiple users at different distances and angles;
- **estimation of user position** (distance and angle) from the received signals;
- **visualization tools** for beams, wavefronts and localization results.

---

## Key concepts

| Concept | Role in the project |
| --- | --- |
| Leaky-wave antenna | Frequency-scanning radiator: the beam angle depends on frequency |
| Multi-port aperture | Multiple feeds along the antenna, enabling distance estimation |
| Near field | Region where wavefront curvature carries distance information |
| 6G / sub-THz | Target scenario for the simulated system |

---

## Code availability

The source code of the simulator **will be released after the publication** of the related research work. Star or watch this repository to be notified.

---

## Author

**Mattia Battistini**
MSc student in Electronic Engineering for Artificial Intelligence · University of Bologna

- LinkedIn: [Mattia Battistini](https://www.linkedin.com/in/mattia-battistini-518657426/)
- GitHub: [@MattiaBattistini-Projects](https://github.com/MattiaBattistini-Projects)
