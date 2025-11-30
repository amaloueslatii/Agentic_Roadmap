# Agentic Roadmap Notebook

This notebook documents the process of building a simple agentic workflow for generating a learning or work roadmap and scheduling it automatically on Google Calendar.

The notebook walks through the logic behind several agents, how they interact, and how they are assembled into a LangGraph workflow.

---

## Notebook Structure

The notebook is organized into the following sections:

### **1. Interview Agent**
Initial agent used to ask questions and gather information required to build a roadmap.

### **2. Refine Agent**
Takes the initial answers and refines them to produce clearer and more structured inputs.

### **3. Roadmap Agent**
Generates a step-by-step roadmap based on the refined information.

### **4. Linking Google Calendar**
Setup needed to connect the system to Google Calendar using the appropriate API and credentials.

### **5. Fixing Time Slots**
Logic for assigning durations, available times, and constraints to the roadmap items.

### **6. Scheduling**
Transforms the roadmap + time slots into actual calendar events.

### **7. LangGraph GraphState**
Definition of the shared state that passes between the different nodes of the graph.

### **8. Defining the Nodes**
Implementation of the nodes (agents) that the graph will use.

### **9. Building the Graph**
Assembling all agents and logic into a LangGraph workflow.

### **10. Generating and Scheduling the Final Roadmap**
Running the graph to:
- generate the roadmap  
- refine it  
- schedule it  
- push it to Google Calendar

---

## Purpose

The notebook provides a clear, step-by-step walkthrough of:
- designing multiple agents,
- connecting them together with LangGraph,
- integrating planning logic,
- and automating scheduling through Google Calendar.

It serves as both documentation and an executable prototype for an agentic planning workflow.

---
