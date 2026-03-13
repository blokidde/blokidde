# Hi, I'm Jurriaan Egmond

Computer Science student (HBO-ICT Technische informatica) at the Amsterdam University of Applied Sciences.

Currently working on:
- Edge AI systems
- Computer vision pipelines
- Embedded systems
- backend systems

## Projects

### Edge AI Computer Vision Pipeline

End-to-end wildlife recognition pipeline covering the full machine learning workflow: dataset engineering, model training, evaluation, and edge deployment.

The system combines **YOLO object detection with a species classification model** to identify animals in images or camera streams. Models are trained using transfer learning (MobileNet / EfficientNet) and exported to **TensorFlow Lite for edge inference**.

A real-time demo runs on **embedded hardware (ESP32-P4)** with camera input and LCD rendering.

**Technologies**

- Python  
- TensorFlow / Keras  
- YOLO  
- OpenCV  
- TensorFlow Lite  
- C / C++  
- ESP-IDF

### Financial Report Simplifier

Web application that simplifies complex financial reports using both **local and cloud-based large language models**.

The system processes documents (PDF, DOCX, TXT), extracts relevant content, and generates simplified explanations tailored for non-expert users.

**Technologies**

- Python  
- FastAPI  
- Large Language Models (LLMs)  
- Document Parsing (PDF / DOCX / TXT)

**Repository**

---

### Step-Hear Indoor Navigation Platform

Indoor navigation system designed to assist visually impaired users. The platform combines a backend API, an admin management app, and an accessible user application.

The system uses **Bluetooth signal strength, compass direction and graph-based routing (Neo4j)** to guide users between Points of Interest (PoIs) inside buildings with spoken instructions.

**My contributions included**

- Designing an accessible **2×2 interface** with large buttons and text-to-speech feedback  
- Implementing **BLE scanning and RSSI filtering** for PoI detection and positioning  
- Adding **compass-based direction guidance** combined with spoken navigation instructions  
- Developing **admin tools** for device filtering, whitelisting and PoI management  
- Implementing **map-based PoI placement and connection management**

**Technologies**

- Flutter  
- Python  
- FastAPI  
- Neo4j  
- Bluetooth Low Energy (BLE)  
- Text-to-Speech (TTS)

---
