---
title: "Room-CanCell: AI-Driven Patient Room Automation"
description: "Simulated 3D hospital room that responds to patient vitals in real-time for pediatric cancer care"
year: "2025"
tag: "System"
weight: 2
draft: false
github: "https://github.com/TheCanCell/Room-CanCell"
award: "Solve with Google Hackathon - BeatSuite Case"
---

## Overview

For children undergoing cancer treatment at Prinses Máxima Centrum, the hospital environment can significantly impact their comfort and recovery. Room-CanCell demonstrates how AI can transform a patient's room into a responsive space that adapts to their needs in real-time.

The system monitors patient vitals and uses AI to make decisions about environmental controls—adjusting lighting, playing calming music, or creating the right atmosphere based on the patient's current state. Built for the Solve with Google Hackathon's BeatSuite case, our team was selected as the only group to present our solution for improving pediatric cancer patient care through intelligent room automation.

The project consists of three integrated applications: an AI decision-making engine that processes patient data, a 3D room simulator that visualizes and controls the environment, and a vital signs interface that feeds real-time health metrics into the system. The architecture demonstrates bi-directional data flow, with vitals flowing from sensors to the AI orchestrator, which then recommends interventions that the room applies automatically.

## Key Contributions

- Real-time patient vital monitoring with AI-driven environmental responses
- 3D visualization of hospital room with dynamic lighting and music controls
- Modular architecture with three independent applications working in concert
- Simulated wearable data interface for testing and demonstration
- Optional Google Vertex AI integration for advanced decision-making
- Docker-based deployment for easy setup and scalability

## Technical Stack

- Backend: Python (Flask), Node.js (Express)
- Frontend: Three.js for 3D room visualization
- AI/ML: Google Vertex AI (Gemini)
- Infrastructure: Docker, Docker Compose
- Architecture: Microservices with REST APIs

## Team

Ramin, Daniele, Onur, and Osman Semih Kayhan

## Impact

Developed for Prinses Máxima Centrum, a leading pediatric oncology center, this system explores how AI can create more comfortable and responsive hospital environments for children undergoing cancer treatment.

## Links

- [GitHub Repository](https://github.com/TheCanCell/Room-CanCell)
