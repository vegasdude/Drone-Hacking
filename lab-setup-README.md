# Drone Security Lab – Setup Guide

This folder contains everything needed to build a **reproducible, offline-safe, and permission-based**
drone security research lab for defensive and educational use.

The lab is designed to support:
- PX4-based systems
- ArduPilot-based systems
- SITL and HITL workflows
- network and telemetry monitoring
- detection and policy testing

---

## 🎯 Lab Objectives

The purpose of this lab is to:

- study UAV communication and control paths
- validate detection rules and safety policies
- analyze logs and telemetry
- reproduce security scenarios in a safe environment
- avoid testing on real or third-party aircraft

---

## 🧱 Supported Lab Types

### 1. Software-in-the-Loop (SITL)
- Flight stack runs on the host machine
- No real hardware required
- Ideal for protocol and detection research

### 2. Hardware-in-the-Loop (HITL)
- Real flight controller
- Simulated sensors and environment
- Used for timing and hardware behavior testing

---

## 🗂️ Recommended Sub-Folders

You may create the following structure inside this folder:
