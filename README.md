# Deadlock Prevention and Recovery Toolkit

A Python + Flask based interactive simulation for Deadlock Prevention, Detection, and Recovery, integrating traditional Operating System algorithms (Banker's Algorithm and Resource Allocation Graph) with AI-based suggestions.

---

## Features

- 🔄 **Add Processes and Allocate Resources** dynamically
- ✅ **Banker's Algorithm**: Deadlock prevention with safe sequence validation
- ⚖️ **Resource Allocation Graph (RAG)**: Detect cycles to identify deadlocks
- 🤖 **AI-Based Suggestions**: Recommend which process to preempt to resolve deadlock
- 🔍 **Interactive Graph Visualizations** using Vis.js
- 🌐 **Flask Web Interface**: User-friendly simulation dashboard
- 🛠️ **Reset Simulation** anytime

---

## Technologies Used

- Python 3
- Flask (for backend server)
- Tailwind CSS (for styling frontend)
- Vis.js (for dynamic graph visualization)

---

## Folder Structure

```
project/
|│
|├── app.py
|└── templates/
    └── index.html
```

---

## Installation & Setup

1. Clone the repository or extract the ZIP.
2. Navigate into the project folder.
3. Install dependencies:
   ```bash
   pip install flask
   ```
4. Run the app:
   ```bash
   python app.py
   ```
5. Open your browser and go to:
   ```
   http://localhost:8080
   ```

---

## How to Use

1. **Add Processes**:
   - Define Max Needs and Allocated Resources for each process.
2. **Check for Deadlocks**:
   - Select an algorithm (Banker's or RAG) and detect deadlocks.
3. **Resolve Deadlocks**:
   - If deadlock detected, follow AI suggestion to resolve.
4. **View Visualizations**:
   - Graphical representation of processes and resource dependencies.
5. **Reset**:
   - Reset the simulation to start fresh.

---

## Project Overview

- **Title**: Deadlock Prevention and Recovery Toolkit
- **Objective**: Prevent and recover from deadlocks using classic algorithms enhanced with AI.
- **Scope**: Simulated environment, educational tool.
- **Significance**: Demonstrates real-world system resilience techniques.

---

## Future Enhancements

- Integration of real-time monitoring.
- Expansion to N-resource types (currently 3).
- Use of Machine Learning models for advanced deadlock prediction.
- Support for distributed systems.

---

## License

This project is open-source and intended for educational purposes.

