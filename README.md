# 🎓 Laboratorio remoto con ESP32-CAM y Telegram

**Tesis 2022**  
“IMPLEMENTACIÓN DE LABORATORIO CON INTERACCIÓN REMOTA PARA AUMENTAR LA SATISFACCIÓN ESTUDIANTIL DURANTE PRÁCTICAS VIRTUALES”

Este proyecto implementa un sistema de laboratorio remoto utilizando un **ESP32-CAM**, controlado mediante **Telegram**, que permite a estudiantes interactuar con equipos reales a distancia.

---

## 🧠 ¿Qué hace el sistema?

- 📷 Visualización en tiempo real del laboratorio  
- 🤖 Control de cámara mediante Telegram  
- 💡 Encendido remoto de luces  
- 🖥️ Encendido de PC del laboratorio  
- 🎛️ Control de cámaras adicionales y PLC  
- 🔄 Movimiento de cámara con servomotor  

Todo desde un chat de Telegram.

---

## 🏗️ Arquitectura del sistema

Usuario → Telegram → ESP32-CAM → Laboratorio físico

El ESP32-CAM recibe comandos desde Telegram y ejecuta acciones físicas en el laboratorio.

---

## 🧰 Hardware utilizado

- ESP32-CAM  
- Servomotor  
- Relés de control  
- PC de laboratorio  
- Cámaras adicionales  
- PLC S7-1200  

---

## 💻 Software utilizado

- Arduino (C++)  
- ESP32  
- Telegram Bot API  
- TeamViewer  

---

## 📸 Imágenes del proyecto

<img width="1330" height="747" alt="Captura de pantalla 2026-02-23 001055" src="https://github.com/user-attachments/assets/c83e1efa-378f-4263-9c63-5bb5ae4ea202" />
<img width="1327" height="747" alt="Captura de pantalla 2026-02-23 001041" src="https://github.com/user-attachments/assets/e0888b26-c3fc-422b-83b5-36b23456d4d1" />
<img width="1330" height="746" alt="Captura de pantalla 2026-02-23 001124" src="https://github.com/user-attachments/assets/487b3a01-4ee5-424d-aa4a-eb5c288d54ce" />


---

## 📂 Código

El código Arduino se encuentra en la carpeta:
/arduino
