---
title: "MnM Hospital Multi-Agent Information Retrieval System"
description: "Multi-agent system helping healthcare workers quickly access institutional knowledge across hospital operations"
year: "2025"
tag: "System"
weight: 1
draft: false
github: "https://github.com/matthijshulsebos/google-agents-hackathon"
award: "Google AI Agents Hackathon Winner"
---

## Overview

Picture this: It's 3 AM in a hospital cardiology ward. A nurse who just rotated onto the floor needs to find the current protocol for administering high-dose anticoagulation therapy. She starts searching through SharePoint sites, shared drives, and email archives, trying to figure out which documentation is actually current. This scenario plays out in hospitals worldwide, every single day.

We built MnM Hospital to solve this problem. It's a multi-agent system that helps healthcare workers quickly access institutional knowledge—policies, procedures, and clinical protocols. The system uses specialized agents for different departments (Nursing, HR, Pharmacy) with multilingual support and document-grounded responses with citations.

Built with Google's Agent Development Kit and Vertex AI Search, the system automatically routes queries to the appropriate specialist and provides answers in English, Spanish, French, or German. By focusing on institutional knowledge rather than patient data, we were able to navigate HIPAA and GDPR constraints while delivering practical value for hospital operations.

## Key Contributions

- Multi-agent orchestration with intelligent routing based on query content
- Help agent for onboarding new users before domain-specific routing
- Multilingual support (English, Spanish, French, German) with automatic language detection
- Document-grounded responses with citations to source material
- Real-time medication tracking including inventory and batch information
- Modular architecture for adding new departments and data sources

## Technical Stack

- Backend: Python with Google Agent Development Kit (ADK)
- AI/ML: Vertex AI Search for document retrieval and grounding
- Frontend: TypeScript with responsive chat interface
- Cloud: Google Cloud Platform (Cloud Run)

## Team

Osman Semih Kayhan, Tiago Stutz, Arman N., Matthijs Hulsebos, Raymond Steenvoorden

## Links

- [GitHub Repository](https://github.com/matthijshulsebos/google-agents-hackathon)
