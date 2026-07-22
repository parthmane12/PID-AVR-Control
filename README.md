# PID-Based Automatic Voltage Regulator (AVR)

A MATLAB Simulink project that models and simulates an Automatic Voltage Regulator (AVR) using a PID controller to maintain a stable generator terminal voltage under varying operating conditions. The project focuses on improving transient response, minimizing steady-state error, and analyzing overall system stability.

---

## 📌 Overview

An Automatic Voltage Regulator (AVR) is a control system used in synchronous generators to regulate terminal voltage by controlling the excitation voltage.

This project implements a closed-loop AVR model in MATLAB Simulink and compares the system performance before and after applying a PID controller.

---

## 🎯 Objectives

- Model an Automatic Voltage Regulator (AVR) in MATLAB Simulink.
- Design and tune a PID controller.
- Improve voltage regulation performance.
- Reduce settling time and steady-state error.
- Analyze transient response characteristics.

---

## 🛠 Software Used

- MATLAB R2023a (or later)
- Simulink
- Control System Toolbox

---

## ⚙ System Components

The AVR model consists of:

- Amplifier
- Exciter
- Generator
- Voltage Sensor
- PID Controller

The controller continuously adjusts the excitation voltage to maintain the desired generator terminal voltage.

---

## 🚀 Working Principle

1. A reference voltage is applied to the system.
2. The sensor measures the generator terminal voltage.
3. The measured voltage is compared with the reference voltage.
4. The resulting error is processed by the PID controller.
5. The controller adjusts the excitation voltage.
6. The process repeats continuously until the output voltage stabilizes.

---

## 📊 Performance Analysis

The following parameters were analyzed:

- Rise Time
- Settling Time
- Peak Overshoot
- Steady-State Error
- System Stability

The PID-controlled system demonstrates faster response and improved voltage regulation compared to the open-loop system.

---


## 📈 Results

The PID controller significantly improves system performance by:

- Reducing steady-state error
- Improving voltage stability
- Decreasing settling time
- Reducing overshoot
- Providing a faster transient response

---

## 📚 Key Concepts

- Automatic Voltage Regulation
- Closed-Loop Control Systems
- PID Controller Design
- Transfer Function Modeling
- Step Response Analysis
- System Stability
- Control Engineering

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Modeling control systems in MATLAB Simulink
- Designing and tuning PID controllers
- Analyzing dynamic system response
- Evaluating control system performance using transient characteristics

---


## 📷 Screenshots


- Simulink Block Diagram
- Open-Loop Step Response
- Closed-Loop Step Response
- PID Tuning Results
- Scope Output

