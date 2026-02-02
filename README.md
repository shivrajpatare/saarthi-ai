# Saarthi AI

Saarthi AI is a multilingual, voice-first AI assistant designed to help people in India access public services easily.

This project is currently in the **idea and design stage** and is being submitted as part of an **idea submission phase**. The repository contains problem understanding, requirements, system design, and a clear implementation plan.

---

## Why Saarthi AI

Millions of people in India struggle to access public services because of:
- Language barriers
- Low digital literacy
- Text-heavy and complex apps
- Fragmented government and transport systems

Most digital services assume users can read English, navigate apps, and understand bureaucratic terms. This excludes migrant workers, first-generation students, elderly citizens, and rural-to-urban newcomers.

Saarthi AI is built to reduce this gap using **voice-first interaction in Indian languages**.

---

## What Saarthi AI Does

Saarthi AI acts like a digital companion that users can simply talk to.

It helps users with:

### 1. Public Transport Navigation
- Step-by-step directions using buses, metro, walking
- Landmark-based guidance instead of exact addresses
- Estimated cost, time, and accessibility info

Example:
*"How do I go from Connaught Place to AIIMS?"*

---

### 2. Government Scheme Discovery
- Finds schemes a user may be eligible for
- Explains eligibility in simple language
- Guides users through application steps
- Lists required documents and where to apply

Example:
*"I am a daily wage worker. What schemes can help me?"*

---

### 3. Voice-First Interaction
- Users speak instead of typing
- Supports multiple Indian languages
- Handles mixed language speech like Hinglish
- Text fallback available if voice fails

---

## Target Users

- Migrant workers
- First-generation students
- Elderly citizens
- Rural-to-urban newcomers
- NGO workers and community volunteers

The system is designed for users with **limited digital literacy**, not power users.

---

## Project Status

This repository represents the **ideation and system design phase**.

Currently included:
- `requirements.md` – detailed functional and non-functional requirements
- `design.md` – system architecture and technical design
- Implementation task breakdown and roadmap

No production code has been written yet.

---

## High-Level Architecture (Planned)

- Voice input → Speech-to-Text
- Language detection
- Intent understanding using LLM
- Retrieval from transport and scheme knowledge base
- Response generation
- Text-to-Speech output

The system is designed to be:
- Serverless
- Scalable
- Privacy-first
- Accessible on low-end devices

---

## Technology Stack (Proposed)

- **Frontend**: React (PWA), TypeScript
- **Backend**: AWS Lambda, API Gateway
- **AI**: AWS Bedrock (LLM), RAG pipeline
- **Speech**: AWS Transcribe, AWS Polly
- **Data**: DynamoDB, OpenSearch, S3

---

## Repository Purpose

This repository is submitted to demonstrate:
- Clear problem understanding
- User-centered thinking
- Strong requirement definition
- Scalable and realistic system design
- Feasibility for real-world impact in India

---

## Team

**Team Name:** The Shoiki  
**Team Leader:** Shivraj Patare  

---

## Note

This is an idea-stage submission.  
The actual implementation will begin after the idea evaluation phase.