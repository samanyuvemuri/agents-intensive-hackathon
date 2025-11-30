# TripVerse: AI-Powered Multi-Agent Travel Planner
### Built with Gemini 2.5 + Tools + Function Calling

---

## 🚀 Overview

**TripVerse** is an AI-driven multi-agent travel planning system that automates destination research, weather awareness, currency conversion, and day-by-day itinerary generation.

The system uses **two collaborating agents**:

1. **Research Agent** – Fetches real-time destination info using the Google Search tool  
2. **Plan Agent** – Converts user budgets using a custom tool and generates a structured itinerary

TripVerse demonstrates how intelligent agents and tool-calling can orchestrate a full end-to-end planning workflow.

---

## 🧩 Problem Statement

Travel planning is tedious and fragmented. Users must look up:

- Attractions
- Weather
- Local currency conversion
- Hidden gems
- Daily itineraries
- Budget considerations  

This requires extensive manual work. Beginners especially struggle to create a structured, optimized travel plan.

**TripVerse solves this by letting specialized agents do the research and planning automatically.**

---

## 💡 Why Agents?

### **1. Specialization**
Each agent handles a distinct domain—research vs planning—for reliability and clarity.

### **2. Autonomous Tool Use**
Agents independently call tools such as:

- Google Search  
- Currency converter API  

This allows for accurate results grounded in real data.

### **3. Coordinated Reasoning**
Agents share context and build upon each other's outputs, forming a predictable workflow.

---

## 🛠️ Key Features (Aligned With Competition Rubric)

TripVerse includes more than three required agent features:

| Feature | Description |
|--------|-------------|
| Multi-Agent Workflow | Dedicated Research & Planner agents |
| Tool Calling | Google Search tool + custom currency converter |
| Function Routing | Agents detect and execute tool calls automatically |
| Structured System Instructions | Behaviors enforced through prompts |
| AFC (Auto Function Calling) | Enabled for tool invocation |
| Real-Time Info | Weather and attraction data via search |
| Markdown Formatting | Final planning output in clean Markdown |

---

## 🏗️ Architecture

