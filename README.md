<h3 align="center">🚀 Python + IA + Three.js</h3>
### 🧰 Tools & Technologies

<p align="center">
  <img src="https://github.com/elisioMassaqui/elisioMassaqui/blob/main/Three.js_Icon.svg.png" alt="Three.js" width="90" height="90">
  <img src="https://github.com/elisioMassaqui/elisioMassaqui/raw/main/Antu_arduino-icon-small.svg.png" alt="Arduino" width="90" height="90">
  <img src="https://github.com/elisioMassaqui/elisioMassaqui/blob/main/py.png" alt="Python" width="100" height="100">
  <img src="https://img.icons8.com/?size=100&id=108784&format=png&color=000000" alt="JavaScript" width="100" height="100">
  <img src="https://github.com/arduino/arduino-cli/blob/master/docs/img/CLI_Logo_small.png" alt="Arduino-CLI" width="100" height="100">
  <img src="https://github.com/eliMassaqui/eliMassaqui/blob/main/logo-square-green.svg" alt="Anaconda" width="100" height="100">
</p>

```python
import cv2

class VisaoComputacional:
    def __init__(self):
        self.stack = "Python + OpenCV + MediaPipe + YOLO"
        self.foco = "Visão em tempo real e sistemas inteligentes"
        self.estado = "Evolução contínua em IA visual"

    def iniciar(self):
        cap = cv2.VideoCapture(0)
        print("Sistema de visão inicializado")
        return cap


if __name__ == "__main__":
    visao = VisaoComputacional()
    cap = visao.iniciar()
```
# ⚙️ Full Engineering Stack

<p align="center">
  <img src="https://img.shields.io/badge/Simulation-00B3A4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Robotics-2ECC71?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Real--Time-E74C3C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/3D-Visualization-3498DB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Web-Integration-9B59B6?style=for-the-badge" />
</p>

## 🐍 Python
<p>
  <img src="https://img.shields.io/badge/Hardware-Integration-E67E22" />
  <img src="https://img.shields.io/badge/Realtime-Sockets-9B59B6" />
  <img src="https://img.shields.io/badge/Desktop-Qt-2C2255" />
  <img src="https://img.shields.io/badge/Backend-APIs-009688" />
  <img src="https://img.shields.io/badge/Vision-AI-F1C40F" />
</p>

## 🌐 Web / Node.js
<p>
  <img src="https://img.shields.io/badge/3D-Three.js-FF8C00" />
  <img src="https://img.shields.io/badge/Physics-Simulation-E67E22" />
  <img src="https://img.shields.io/badge/Realtime-Socket.IO-9B59B6" />
  <img src="https://img.shields.io/badge/Tooling-Vite-95A5A6" />
</p>

## 📦 Quick Install

### PY
```bash
pip install pyserial websockets python-socketio pyqt6 PyQt6-WebEngine pyqtgraph pyinstaller pygame pillow
```
### JS
```bash
npm install three@0.183.2 vite gsap cannon-es @dimforge/rapier3d socket.io-client lil-gui postprocessing three-stdlib howler gl-matrix three-ik
```

## 📦 Full Setup - Anaconda + Arduino CLI

<p align="center">
  <img src="https://img.shields.io/badge/Anaconda-Python-blue?logo=anaconda&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-CLI-red?logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white" />
</p>

```bash
# ---------------------------
# 1️⃣ Anaconda Environment
# ---------------------------
# Siga o link oficial se Anaconda não estiver instalada:
# https://www.anaconda.com/products/distribution

# Criação de ambiente isolado
conda create -n engineering-lab python=3.10
conda activate engineering-lab

# Instalar pacotes científicos
conda install numpy scipy pandas matplotlib opencv-python mediapipe

# ---------------------------
# 2️⃣ Arduino CLI
# ---------------------------
# Windows: baixar MSI oficial
# macOS/Linux: via Homebrew ou apt

arduino-cli core update-index
arduino-cli core install arduino:avr

# Teste de instalação
arduino-cli board list
