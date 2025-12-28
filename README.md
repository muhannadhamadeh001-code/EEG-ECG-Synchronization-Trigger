# EEG–ECG Synchronization Trigger PCB

This repository contains the design of a hardware trigger PCB used to synchronize EEG and ECG recordings in neuroscience experiments.

## Overview
The board generates a single, opto-isolated digital trigger at the start of an experimental session. This trigger is recorded simultaneously by both EEG and ECG systems, providing a shared time reference for accurate offline alignment of bio-signals recorded on independent devices.

The system is designed for research use, with an emphasis on electrical safety, signal integrity, and reproducibility.

## Key Features
- Microcontroller-based digital trigger generation
- USB-to-UART interface for PC-controlled triggering
- Opto-isolated trigger output for biomedical safety and noise immunity
- Isolated DC-DC power regulation
- 2-layer PCB with careful grounding and keep-out regions

## Use Case
The trigger is intended to be fired once per session, typically at the moment EEG recording begins, allowing EEG and ECG data streams to be temporally aligned during analysis.

## Status
- PCB design completed
- Sent for manufacturing (JLCPCB)
- Assembly and validation pending
- Firmware to be added

## Disclaimer
This project is intended for research and experimental use only.
