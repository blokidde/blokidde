# Hi, I'm Jurriaan Egmond

Computer Science student (HBO-ICT Technische informatica) at the Amsterdam University of Applied Sciences.

Currently working on:
- Edge AI systems
- Computer vision pipelines
- Embedded systems
- backend systems
## Skills

### Programming

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-555555?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)

### AI / Machine Learning

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111111)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00)

### Backend / APIs

![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-000000)

### Mobile Development

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)

### Databases

![MariaDB](https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?logo=neo4j&logoColor=white)

### Edge / Embedded Systems

![ESP32](https://img.shields.io/badge/ESP32-E7352C)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-000000)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?logo=raspberrypi&logoColor=white)

### DevOps / Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
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

**Repository**
[animal recognition](https://github.com/blokidde/animal-recognition)

### Financial Report Simplifier

Web application that simplifies complex financial reports using both **local and cloud-based large language models**.

The system processes documents (PDF, DOCX, TXT), extracts relevant content, and generates simplified explanations tailored for non-expert users.

**Technologies**

- Python  
- FastAPI  
- Large Language Models (LLMs)  
- Document Parsing (PDF / DOCX / TXT)

**Repository**
[Financial Simplifier](https://github.com/blokidde/Financial_Simplifier)


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

**Repository**

[Stephear App](https://github.com/blokidde/Stephear-app)

---
