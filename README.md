# Álvaro Gil | Software Engineer & IoT Systems

Ingeniero enfocado en arquitectura de software limpia (Clean / Hexagonal Architecture), aplicaciones web local-first de alta resiliencia y sistemas embebidos IoT con telemetría en tiempo real.

---

## 🚀 Proyectos Destacados

### 1. Ganaderos Campo PWA
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![SQLite WASM](https://img.shields.io/badge/SQLite-WASM_%2B_IndexedDB-003B57?logo=sqlite&logoColor=white)](https://sqlite.org)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)](https://python.org)
[![PWA](https://img.shields.io/badge/PWA-Offline--First-5A0FC8?logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

**Repositorio:** [github.com/Alvaro137/ganaderos](https://github.com/Alvaro137/ganaderos)  
**Entorno:** PWA local-first en producción real sobre pastos y dehesas.

Aplicación web progresiva para gestión ganadera en extensivo diseñada para operar al 100% en zonas sin cobertura móvil:
- **Motor Relacional Local-First:** Ejecución completa de SQLite en el navegador del dispositivo móvil compilado a WebAssembly (SQL.js) con persistencia binaria en IndexedDB. Cero peticiones de red al consultar censo, genealogías o supresiones sanitarias.
- **Clean Architecture & Backend Asíncrono:** Arquitectura hexagonal estricta en Python (FastAPI + Pydantic v2) separando dominio puro, casos de uso e adaptadores de infraestructura.
- **Asistente por Voz con IA en Sandbox:** Consulta en lenguaje natural mediante transcripción Whisper y generación SQL restringida a un sandbox de solo lectura en SQLite (`query_only`), con fallback determinista mediante Intent Calling estructurado.
- **Conciliación Bidireccional:** Pipeline de ingesta y conciliación automática con bases de datos heredadas (Access Jet/MDB) y sincronización transaccional idempotente.
- **Testing Exhaustivo:** Cobertura integral con Pytest (unitarios e integración) y flujos end-to-end automatizados en navegador con Playwright.

**Stack:** Python • FastAPI • SQLite WASM • Vanilla JavaScript (ES Modules) • PWA • Docker • Playwright

---

### 2. Sainlogic IoT Weather Station
[![PlatformIO](https://img.shields.io/badge/PlatformIO-Firmware-blue?logo=platformio)](https://github.com/Alvaro137/Sainlogic_esp32_wifi)
[![C++](https://img.shields.io/badge/C++-ESP32-00599C?logo=cplusplus&logoColor=white)](https://espressif.com)
[![FastAPI](https://img.shields.io/badge/FastAPI-Telemetry-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)

**Repositorio:** [github.com/Alvaro137/Sainlogic_esp32_wifi](https://github.com/Alvaro137/Sainlogic_esp32_wifi)  
**Producción:** [https://meteo.alvaro137.com/](https://meteo.alvaro137.com/)

Sistema integral de telemetría meteorológica y monitorización continua desplegado en servidor edge:
- **Firmware ESP32 (C++ / PlatformIO):** Muestreo, decodificación por interrupciones de sensores meteorológicos (viento, lluvia, presión, temperatura y humedad), reconexión WiFi autónoma y publicación telemétrica HTTP/JSON.
- **Backend & Servidor Edge:** Servicio FastAPI asíncrono sobre Linux ARM con base de datos SQLite optimizada para series temporales y servidor web Caddy.
- **Frontend Web Dashboard:** Visualización reactiva en tiempo real, gráficas dinámicas de tendencias y exportación de históricos.

**Stack:** C++ • ESP32 • PlatformIO • Python (FastAPI) • JavaScript • Linux Edge

---

## 🛠️ Stack Tecnológico

| Dominio | Tecnologías |
| :--- | :--- |
| **Backend & Arquitectura** | Python (FastAPI, Pydantic, Uvicorn), Clean Architecture, REST APIs, Microservicios Docker |
| **Frontend & Offline-First** | Progressive Web Apps (PWA), SQLite WebAssembly (SQL.js), IndexedDB, ES Modules, CSS3 |
| **Sistemas & Edge / IoT** | C++, ESP32, PlatformIO, Linux (Armbian/Debian), Caddy, Cloudflare Zero Trust, Systemd |
| **Bases de Datos** | SQLite (WAL mode), Microsoft Access Jet Engine ETL, IndexedDB |
| **Calidad & Testing** | Pytest, Playwright (E2E), Ruff, Pip-Audit, Gitleaks, GitHub Actions CI/CD |

---

## 📩 Contacto  
- **GitHub:** [@Alvaro137](https://github.com/Alvaro137)  
- **LinkedIn:** [alvaro-gil-5bb0062b6](https://linkedin.com/in/alvaro-gil-5bb0062b6)  
- **Email:** [Alvarogil137@gmail.com](mailto:Alvarogil137@gmail.com)  

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=80&section=footer"/>
</p>
