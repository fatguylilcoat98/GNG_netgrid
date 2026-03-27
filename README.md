# GNG_NetGrid — Interactive Network Topology Demo

Built by Christopher Hughes  
The Good Neighbor Guard  
Truth · Safety · We Got Your Back

---

## What This Is

GNG_NetGrid is an interactive network topology demo that lets you visually build and explore network layouts.

You can:
- Add nodes (servers, routers, databases, services)
- Drag and position them freely
- Create connections between nodes
- Trace paths between systems
- Import and export network structures
- Simulate activity (CPU usage, outages, alerts)

This is designed to test the **UI/UX side of network visualization**, not to manage real infrastructure.

---

## Important (Read This)

This is a **demo simulation**.

- No real network data is used  
- Metrics are randomly generated  
- No actual devices are monitored or controlled  

This exists to explore how a system *could feel*, not to replace real tools.

---

## Try It Live

👉 [Live Demo](PASTE_YOUR_GITHUB_PAGES_LINK_HERE)

---

## Features

### Core Interaction
- Click to select nodes  
- Drag to reposition  
- Connect nodes (A → B)  
- Delete connections by clicking the link  

### Path Tracing
- Select two nodes  
- Visualize the path between them  
- Animated data flow simulation  

### Simulation Engine
- Random CPU fluctuations  
- Nodes can go offline/online  
- Alert system (high CPU / offline detection)  

### Import / Export
- Load simple or structured JSON  
- Export full topology as JSON  

### Session Storage
- Save your layout locally  
- Reload previous sessions  

---

## Example Import Format

### Simple
```json
[
  {"name":"Server A","ip":"10.0.0.1","type":"server"},
  {"name":"DB 1","ip":"10.0.0.2","type":"db"}
]
