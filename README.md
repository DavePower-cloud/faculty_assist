# 🧠 Generative AI Faculty Assistant for Clinical Simulation

[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-Live%20App-yellow)](https://huggingface.co/spaces/2O24dpower2024/faculty-assist)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/DavePower-cloud/faculty_assist)

---

## 📌 Overview

This project presents a **faculty-facing generative AI assistant** designed to support **live clinical simulation delivery and debriefing**.

High-fidelity simulation places significant cognitive demands on faculty, particularly during emergency scenarios where facilitators must simultaneously manage:
- clinical accuracy  
- scenario flow  
- learner support  
- debrief preparation  

This tool provides **just-in-time support** during live simulation and structured guidance during debriefing, without disrupting scenario delivery.

---

## 🚀 Live Demo

👉 **Try the live application:**  
https://huggingface.co/spaces/2O24dpower2024/faculty-assist

---

## 🎯 Motivation

Most applications of generative AI in medical education are:
- learner-facing (e.g. tutoring)
- post-session content generation

There is **limited practical reporting of AI tools supporting faculty during live simulation**.

This project addresses that gap by providing:
- real-time clinical support  
- structured debrief scaffolding  
- low-friction integration into live simulation workflows  

---

## ⚙️ System Design

The application is built around a large language model accessed via API and structured prompt design.

It operates in **two modes**:

---

### 🔴 1. Live Support Mode (During Simulation)

Faculty can enter a clinical condition or query to receive:

- immediate actions  
- escalation guidance  
- drug treatments and dosing (when appropriate)  
- structured prompts for facilitation  

#### 🛡️ Safety Features

- Responses grounded to **allowlisted trusted sources (EMED)**  
- Explicit **source citation prompts**  
- Redirect behaviour for unsupported conditions  
- No autonomous decision-making  
- **Human-in-the-loop control at all times**
  
![Live Image 1](faculty_assist_output4.PNG)

---

### 🔵 2. Debrief Mode (Post-Scenario)

Faculty input:
- a brief scenario summary  
- debrief focus  

The system generates a structured scaffold aligned with the **PEARLS framework**, including:

- opening script (psychological safety)  
- reaction and description questions  
- advocacy–inquiry prompts  
- targeted teaching points  
- take-home messages  
- optional **5-minute debrief format**

![Debrief Image 1](faculy_assist_output1.PNG)

---

## 🧪 Evaluation

This system was evaluated as a **feasibility and usability pilot** during emergency simulation courses for newly qualified doctors.

### Key findings:

- Feasible to use **during live simulation**
- Did not disrupt **scenario flow**
- Supported:
  - clinical confirmation  
  - escalation prompts  
  - structured debriefing  
- Particularly valuable for **less experienced faculty**

Evaluation was based on **faculty feedback during real-world use**, consistent with iterative design approaches in simulation-based education.

---

## 🔁 Iterative Development

The system was refined in real time across multiple simulation sessions, with:

- rapid prompt tuning  
- guardrail adjustments  
- interface improvements  

This reflects a **design-based research approach** grounded in practical deployment.

---

## 📄 Related Work

This project builds on broader research into **multi-agent and generative AI systems in clinical simulation**:

- Power, D., & Power, T. (2026). *Can Large Language Models Simulate the Clinical Conversation? A Multi-Agent Approach*  
  https://doi.org/10.35542/osf.io/etv6d_v1

---

## 📖 Preprint

A short report describing this work is currently under review:

- Power, D. (2026). *Generative AI Support for Faculty During Live Simulation*  


Preprint: [TODO]

---

## 🧠 Research Context

This work forms part of an ongoing research programme focused on:

- AI-supported clinical simulation  
- multi-agent LLM systems  
- structured communication and escalation  
- simulation faculty support tools  

---

## 📜 Citation

If you use this work in academic settings, please consider citing the associated research:

