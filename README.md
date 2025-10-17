# Network Project Management — Activity Sequencing & Resource Requirements Planning
A project demonstrating CPM scheduling, network diagramming, and resource levelling techniques.

## 📌 Overview

This project applies **network planning techniques** to manage and schedule activities effectively.  
It focuses on:

- Building a **Network Diagram** using the Activity-on-Arrow (AOA) method  
- Finding the **Critical Path** using the Critical Path Method (CPM)  
- Creating a **Resource Requirements Plan** to calculate worker days and resource utilization  
- Applying **Resource Levelling / Smoothing** to balance resources under fixed availability

---

## 🏗️ Project Objectives

- Construct a network diagram to visualize activity dependencies  
- Determine the critical path to calculate the minimum project duration  
- Plan and analyze resource requirements across activities  
- Optimize resource usage through levelling without exceeding fixed resources

---

## 📝 Project Details

### 1. Activity Sequencing

- Activities **A–G** are defined with durations, predecessors, and worker requirements.  
- Dependencies are represented using an **AOA network diagram**.  
- Example: A must be completed before D → D before G → C before F, etc.

---

### 2. Critical Path Method (CPM)

The CPM calculation identifies the **critical path** and calculates **Earliest Finish (EF)**, **Latest Finish (LF)**, and **Slack** for each activity.

**Critical Path:** `B → E → G`  
**Project Duration:** 14 days

| Activity | EF | LF | Slack |
|----------|----|----|-------|
| A        | 4  | 7  | 3     |
| B        | 7  | 7  | 0     |
| C        | 5  | 7  | 2     |
| D        | 7  | 10 | 3     |
| E        | 10 | 10 | 0     |
| F        | 11 | 14 | 3     |
| G        | 14 | 14 | 0     |

---

### 3. Resource Requirements & Utilization

- **Total worker days:** 77  
- **Peak usage:** 8 workers during mid-project  
- Identified periods of high fluctuation in resource usage

---

### 4. Resource Levelling / Smoothing

- Applied **resource-limited scheduling**  
- Activities with **less slack** get higher priority  
- Activities with **more slack** are delayed to keep resource use within fixed limits  
- This can extend the project time but avoids exceeding available resources

---


##  Key Concepts

- Activity-on-Arrow (AOA)  
- Critical Path Method (CPM)  
- Slack analysis  
- Resource planning  
- Resource levelling / smoothing

---

## 👤 Author

**Andile Nomaqhiza**  
Project Management | Network Planning | Resource Scheduling



