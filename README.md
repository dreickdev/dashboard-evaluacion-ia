# Alerta temprana — Dashboard de desempeño

Dashboard interactivo para análisis de desempeño académico y detección temprana de estudiantes en riesgo.

## 🔗 Demo en vivo

👉 https://dreickdev.github.io/dashboard-evaluacion-ia/

## 📋 Funcionalidades

- Carga de archivos Excel (`.xlsx`, `.xls`, `.csv`)
- Reconocimiento automático de hojas por nombre (`particip`, `practic`, `parcial`)
- Cálculo de nota final ponderada (participación 30 %, prácticas 30 %, parcial 40 %)
- Índice de riesgo 0–100 basado en tres señales: distancia a la nota mínima, déficit de participación y brecha prácticas-parcial
- Tres niveles de riesgo: alto (≥ 55), medio (≥ 30), bajo (< 30)
- Acción pedagógica sugerida por estudiante
- Exportación de lista de riesgo a CSV
- Procesamiento 100 % local: los datos nunca salen del navegador

## 🛠️ Tecnologías

- HTML5 + CSS3 + JavaScript vanilla
- [SheetJS](https://sheetjs.com/) para lectura de Excel
- GitHub Pages para hosting estático

## 🧠 Modelo predictivo
