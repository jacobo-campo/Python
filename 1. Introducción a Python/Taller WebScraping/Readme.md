# 📘 Taller en Clase: Análisis e Interpretación de Datos

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)]()
[![Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab&logoColor=white)](PEGAR_AQUI_TU_LINK_DE_COLAB)

---

## 👨‍🏫 Información general

**Profesor:** Jacobo Campo Robledo  
**Facultad de Ciencias Económicas y Administrativas**  
**Universidad Católica de Colombia**

Este repositorio contiene la solución del ejercicio de **web scraping y análisis de texto** aplicado a la página **Books to Scrape**.

---

## 🎯 Objetivo

Extraer información de libros desde una página web y aplicar técnicas de:

- **web scraping**
- **limpieza de texto**
- **conteo de n-gramas**
- **matriz de frecuencia de términos**
- **visualización de datos**

---

## 🌐 Fuente de datos

Página utilizada en el ejercicio:

**Books to Scrape – Sandbox**

---

## 🧩 Preguntas del ejercicio

<details>
<summary><strong>1. Web scraping</strong></summary>

Construir un `dataframe` a partir de la página web, donde:

- cada fila corresponda a un libro,
- las columnas incluyan al menos:
  - **título**
  - **precio**

</details>

<details>
<summary><strong>2. Limpieza de texto</strong></summary>

Realizar el preprocesamiento de los títulos de los libros. Para ello:

- remover las **stopwords**,
- convertir todo el texto a **minúsculas**,
- eliminar **caracteres especiales**,
- eliminar **números**.

La base resultante debe llamarse:

```python
datos_limpios
