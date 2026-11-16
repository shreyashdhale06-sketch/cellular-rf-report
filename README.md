# Cellular Network Frequency Planning and Propagation Analysis Report

## Overview
A professional RF engineering web application and technical report modeling frequency planning, cell boundary sizing, channel reuse, and signal propagation for a mid-sized city[cite: 31]. The tool features an interactive **Okumura-Hata Path Loss Calculator** simulating urban, suburban, and open environments[cite: 31].

## Key Engineering Features
1. **Cellular Grid & Topology:** Hexagonal cellular planning across a 5.0 km city radius with hierarchical cell sizing (500m urban core, 1.5km suburban, 3.0km open)[cite: 31, 32].
2. **GSM 900 MHz Frequency Planning:** Implements a 7-cell cluster reuse pattern ($N=7$) with 3-sector base stations yielding an estimated Signal-to-Interference Ratio (SIR) of ~18.3 dB[cite: 31].
3. **Okumura-Hata Propagation Model:** Dynamic path loss estimation taking into account base station height, mobile receiver height, frequency, and distance[cite: 31].
4. **Antenna Configuration & Handoff:** Sectorized 18 dBi directional panel antennas with electrical down-tilt and hysteresis-based handoff algorithms.