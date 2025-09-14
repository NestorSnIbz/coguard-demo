# Bandit SAST Demo for Python Applications

Este repositorio acompaña el artículo **“Applying Bandit SAST Tool to a Python Application”**, mostrando cómo utilizar la herramienta **Bandit** para realizar análisis de seguridad estáticos (SAST) en proyectos Python.

---

## 📖 Descripción

El análisis de seguridad de aplicaciones estáticas (SAST) permite revisar el código fuente en busca de debilidades que podrían derivar en vulnerabilidades, como inyecciones de comandos o manejo inseguro de credenciales. A diferencia de las pruebas dinámicas, SAST analiza el software “desde adentro” antes de que sea ejecutado, ofreciendo retroalimentación temprana y fomentando prácticas de codificación seguras.

**Bandit** es una herramienta que detecta problemas de seguridad frecuentes en proyectos Python mediante el análisis de su Abstract Syntax Tree (AST) y la ejecución de diversos plugins de detección.

---

## 📂 Contenido del Repositorio

- `prueba.py` → Archivo Python de ejemplo con vulnerabilidades.  
- `.github/workflows/bandit.yml` → Flujo de trabajo de GitHub Actions para automatizar el análisis SAST.  
- `report.html` → Ejemplo de reporte generado por Bandit (opcional, si se ejecuta localmente).

---

## ⚙️ Instalación de Bandit

Para instalar Bandit localmente:

```bash
pip install bandit
