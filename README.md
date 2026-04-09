<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d1a,40:16213e,100:0f3460&height=270&section=header&text=Gael%20Burrola&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Ingeniero%20de%20Software%20%7C%20IoT%20%7C%20Cloud%20%7C%20Automatización%20Logística&descColor=8892b0&descAlignY=58&descAlign=50&animation=twinkling" width="100%"/>
</div>

<br>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=64ffda&center=true&vCenter=true&width=800&height=55&lines=Desarrollador+Full-Stack+%26+Ingeniero+IoT;Automatización+Logística+%7C+Sistemas+en+Tiempo+Real;Visión+por+Computadora+%7C+Integración+de+Hardware;Oracle+Cloud+%7C+Firebase+%7C+Edge+Computing" alt="Typing SVG"/>
</div>

<br>

<div align="center">

[![Gmail](https://img.shields.io/badge/gaelburrola249%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gaelburrola249@gmail.com)&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gaelvb152-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/gaelvb152)&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-gaelvb152-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/gaelvb152)&nbsp;&nbsp;
[![Visitas](https://komarev.com/ghpvc/?username=gaelvb152&style=flat-square&color=brightgreen&label=visitas+al+perfil)](https://github.com/gaelvb152)

</div>

<br>

---

## `$ whoami`

```python
class GaelBurrola:
    ubicacion   = "Nogales, Sonora, México 🌵"
    universidad = "Ingeniería en Desarrollo y Gestión de Software — UTN"
    empresa     = "Intern @ Transmex · Sistemas de Logística y Flotillas"

    stack = {
        "lenguajes" : ["Python", "C#", "PHP", "JavaScript", "Dart"],
        "frontend"  : ["HTML5", "CSS3", "Flutter", "Leaflet.js"],
        "cloud"     : ["Oracle Cloud", "Firebase", "Power Automate"],
        "hardware"  : ["Arduino", "ESP32", "OpenCV", "YOLOv8", "Tesseract"],
        "bases_datos": ["MySQL", "SQLite", "Firebase Realtime DB"],
        "herramientas": ["Docker", "Postman", "Tampermonkey"],
    }

    intereses = ["Sistemas en Tiempo Real", "IoT", "Visión por Computadora", "Tech Logística"]

    def __str__(self):
        return "Construyendo sistemas donde el hardware, la nube y la logística convergen."

print(GaelBurrola())
# → Construyendo sistemas donde el hardware, la nube y la logística convergen.
```

<br>

---

## 🛠 Stack Tecnológico

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cs,php,nodejs,js,html,css,flutter,dart&theme=dark&perline=9" />

<img src="https://skillicons.dev/icons?i=arduino,opencv,firebase,mysql,sqlite,docker,postman&theme=dark&perline=9" />

</div>

<br>

<div align="center">

| Área | Tecnologías |
|------|-------------|
| **Backend y Scripting** | Python · C# · PHP · Node.js |
| **Frontend y Móvil** | JavaScript · HTML5 · CSS3 · Flutter/Dart |
| **Cloud y Automatización** | Oracle Cloud · Firebase · Power Automate |
| **IoT y Visión Artificial** | Arduino · ESP32 · OpenCV · YOLOv8 · Tesseract OCR |
| **Datos y Almacenamiento** | MySQL · SQLite · Firebase Realtime DB |
| **Herramientas** | Docker · Postman · Leaflet.js · Tampermonkey |

</div>

<br>

---

## 💼 Experiencia

<br>

**Intern — Desarrollo Multiplataforma** &nbsp;·&nbsp; 🚛 **Transmex** &nbsp;·&nbsp; `Mayo 2025 – Presente`

> Tecnología logística para operaciones de transporte de largo recorrido.

- Construí un **dashboard de rastreo de flotilla en tiempo real** integrando la API REST de Zonar con Firebase, proporcionando visibilidad GPS en vivo a través de múltiples puntos de control.
- Diseñé un **editor avanzado de geocercas** con Leaflet.js — creación de polígonos, gestión de coordenadas, sincronización en mapa y alertas por zona.
- Automaticé el flujo de alertas operativas usando **Power Automate** disparado por eventos en Firebase, reemplazando la supervisión manual.
- Desarrollé una **herramienta de BI interna** para comparar costos de viaje vs. ingresos, identificando rutas no rentables y mejorando la toma de decisiones.
- Construí un **script de automatización de documentos BOL** que convierte hojas de Excel en documentos oficiales de logística, eliminando errores de transcripción manual.

<br>

---

## 🚀 Proyectos

<br>

<details open>
<summary>&nbsp;<strong>🚚 Plataforma de Visibilidad Logística — Zonar API + Firebase</strong></summary>
<br>

**Problema:** Sin visibilidad en tiempo real de la ubicación de la flotilla, cruces de geocercas o estado operacional.

**Solución:** Sistema full-stack que integra la API REST de Zonar como fuente de datos GPS, sincronizando con Firebase Realtime DB cada ~30s, con un dashboard web de monitoreo en vivo.

```
Stack: JavaScript · Firebase · Zonar API · Leaflet.js · Power Automate · Tampermonkey
```

- ✦ Mapa en vivo de la flotilla con geocercas superpuestas y detección de cruces
- ✦ Sistema de alertas automatizado vía Power Automate en eventos por zona
- ✦ Reportes operativos por turno generados automáticamente
- ✦ Reducción de ~80% en tiempo de seguimiento manual del equipo de operaciones

<br>
</details>

---

<details>
<summary>&nbsp;<strong>👁 Reconocimiento de Placas + Medición de Velocidad — IoT + IA</strong></summary>
<br>

**Problema:** La identificación manual de vehículos en puntos de control es lenta, propensa a errores y no captura datos de velocidad.

**Solución:** Pipeline de visión por computadora con YOLOv8 para detección de placas + Tesseract OCR para extracción de texto, sincronizado con hardware ESP32/Arduino para medición de velocidad en tiempo real.

```
Stack: Python · YOLOv8 · OpenCV · Tesseract OCR · Firebase · Arduino · ESP32
```

- ✦ Precisión de reconocimiento de placas >85% en condiciones reales
- ✦ Medición física de velocidad mediante sensores ultrasónicos conectados a ESP32
- ✦ Todos los registros (placa + velocidad + timestamp) enviados a Firebase en tiempo real
- ✦ Pipeline completamente autónomo sin intervención humana después de la configuración

<br>
</details>

---

<details>
<summary>&nbsp;<strong>💰 "VIAJES DEALER" — Análisis Financiero para Transporte</strong></summary>
<br>

**Problema:** Los gerentes de operaciones no tenían visibilidad clara de la rentabilidad real por viaje.

**Solución:** Herramienta de análisis en Python que ingesta datos de Excel de viajes y produce desgloses de costo vs. ingreso con visualizaciones de tendencias.

```
Stack: Python · Pandas · OpenPyXL · Matplotlib · Firebase
```

- ✦ Desglose por viaje: combustible, casetas y mano de obra vs. ingreso facturado
- ✦ Tendencias de rentabilidad por ruta en ventanas de tiempo configurables
- ✦ Tiempo de análisis reducido de días → **minutos**

<br>
</details>

---

<details>
<summary>&nbsp;<strong>📄 Automatización de BOL — Generador de Bill of Lading</strong></summary>
<br>

**Problema:** El personal de logística copiaba manualmente datos de Excel a documentos BOL oficiales — lento y propenso a errores.

**Solución:** Script automatizado en Python con interfaz web simple que lee hojas de Excel estructuradas y genera documentos BOL en formato PDF listos para imprimir en segundos.

```
Stack: Python · OpenPyXL · FPDF · HTML/CSS
```

- ✦ Procesamiento en lote de múltiples registros en una sola ejecución
- ✦ Cero errores de transcripción tras la implementación
- ✦ Usado diariamente por personal de logística sin conocimientos técnicos

<br>
</details>

---

<details>
<summary>&nbsp;<strong>✅ SafeTaskApp — Gestión de Tareas de Equipo (Móvil)</strong></summary>
<br>

**Problema:** Sin herramienta centralizada para asignación, seguimiento y rendición de cuentas de tareas en equipos de trabajo.

**Solución:** App Flutter multiplataforma con backend Firebase para gestión de tareas en tiempo real, notificaciones push y dashboards de equipo.

```
Stack: Flutter · Dart · Firebase Auth · Firestore · Cloud Messaging
```

- ✦ Asignación de tareas por usuario, prioridad y fecha límite
- ✦ Notificaciones push en actualizaciones de tareas
- ✦ Dashboard de productividad del equipo con historial de actividad

<br>
</details>

---

<details>
<summary>&nbsp;<strong>🗓 Sistema de Gestión UTN — Motor de Reglas de Negocio</strong></summary>
<br>

**Problema:** El cálculo manual de días de vacaciones, días sindicales y prestaciones según contratos colectivos era complejo y generaba errores constantes en RR.HH.

**Solución:** Sistema web PHP/MySQL con un motor de reglas personalizado que automatiza todos los cálculos según categoría de empleado y términos del contrato.

```
Stack: PHP · MySQL · HTML/CSS/JS · FPDF
```

- ✦ Soporte para múltiples categorías de empleado y tipos de contrato
- ✦ Reportes PDF generados automáticamente por empleado
- ✦ Eliminación de incidentes de cálculo incorrecto en RR.HH. tras la implementación

<br>
</details>

<br>

---

## 📊 Actividad en GitHub

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=gaelvb152&theme=tokyonight&hide_border=true&stroke=64ffda&ring=64ffda&fire=e94560&currStreakLabel=64ffda" alt="GitHub Streak"/>
</div>

<br>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=gaelvb152&theme=tokyo-night&hide_border=true&area=true&color=64ffda&line=64ffda&point=ffffff" alt="Gráfico de Contribuciones" width="95%"/>
</div>

<br>

---

## 🌱 Explorando Actualmente

<div align="center">

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Microservicios](https://img.shields.io/badge/Microservicios-0080FF?style=flat-square)

</div>

<br>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,60:16213e,100:0d0d1a&height=120&section=footer" width="100%"/>
  <br>
  <sub>Abierto a colaborar en proyectos de IoT, Cloud y automatización logística.</sub><br>
  <sub>Construyamos algo que realmente funcione en producción. 🚀</sub>
</div>
