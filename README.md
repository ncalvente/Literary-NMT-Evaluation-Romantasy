# 🌟 Análisis de Traducción Automática y LLMs en Equivalencia Estilística Literaria
# 🌟 Análisis de Traducción Automática y LLMs en Equivalencia Estilística Literaria

**Máster en Traducción e Interculturalidad (Calificación: 10/10, Matrícula de Honor)**  
📄 [TFM completo](https://idus.us.es/server/api/core/bitstreams/63f4d4f5-251a-4f77-acbd-d658f859db6b/content)

---

### 🚀 Tecnologías y Herramientas

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)  
[![PNL](https://img.shields.io/badge/PNL-spaCy%2F%20NLTK-2AA7DA?style=for-the-badge&logo=spacy&logoColor=white)](https://spacy.io/)  
[![LLMs](https://img.shields.io/badge/LLMs-HuggingFace-FFC300?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/)  
[![Deep Learning](https://img.shields.io/badge/DL-TensorFlow%2F%20Pytorch-5C0A72?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)  
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)  

[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)  
[![GitHub Repo Size](https://img.shields.io/github/repo-size/tuusuario/TFM-Traduccion-AI)](https://github.com/tuusuario/TFM-Traduccion-AI)

---

## 💡 Resumen Ejecutivo

Este repositorio recopila la metodología, el *pipeline* de análisis y las conclusiones del proyecto de Máster.  

Se analiza el impacto de la **Inteligencia Artificial** en la **traducción literaria** (*romantasy*, EN>ES), usando **Lingüística Computacional** para evaluar la calidad de traducciones automáticas (NMT y LLMs) frente a traducciones humanas.

---

## ❓ Problema Central y Objetivos

**Título del TFM:**  
*"De sangre y cenizas de Armentrout: un análisis de sus elementos diegéticos y extradiegéticos mediante traducción humana, traducción automática e Inteligencia Artificial"*

<details>
<summary>🎯 Objetivos</summary>

1. **Equivalencia Estilística:** Evaluar cómo la IA mantiene el tono, registro y voz del autor.  
2. **Adecuación Cultural y Pragmática:** Analizar cómo maneja elementos diegéticos y extradiegéticos.  
3. **Benchmarking de Modelos:** Comparar NMT tradicionales y LLMs en entornos literarios.

</details>

---

## 🛠 Metodología

<details>
<summary>🔍 Ver Metodología Completa</summary>

1. **Selección de corpus:** Capítulos seleccionados del libro *De sangre y cenizas*.  
2. **Traducciones:**  
   - Traducción humana de referencia.  
   - Traducciones automáticas (NMT).  
   - Traducciones generadas con LLMs.  
3. **Análisis lingüístico y estilístico:**  
   - Frecuencia de léxico literario.  
   - Cohesión y coherencia textual.  
   - Mantenimiento de elementos diegéticos/extra-diegéticos.  
4. **Evaluación comparativa:**  
   - Métricas objetivas: BLEU, METEOR, BERTScore.  
   - Evaluación subjetiva: juicio experto sobre estilo y fidelidad cultural.

</details>

---

## 📊 Resultados

<details>
<summary>📈 Ver Resultados Detallados</summary>

- LLMs muestran mayor **fluidez** y mejor **coherencia narrativa**, pero con **inconsistencias en elementos culturales específicos**.  
- NMT clásico es **preciso léxicamente**, pero menos capaz de mantener **estilo literario**.  
- La **traducción humana** sigue siendo el estándar en **equivalencia estilística**.

### 🔹 Ejemplos Visuales

![Ejemplo de análisis](docs/images/ejemplo_analisis.png)  
*Captura de notebook con análisis comparativo.*

![Gráfico de resultados](docs/images/grafico_resultados.png)  
*Comparación de métricas BLEU, METEOR y BERTScore.*

</details>

---

## ⚙️ Instalación y Uso

```bash
# Crear entorno virtual
python -m venv env
source env/bin/activate  # Linux/macOS
env\Scripts\activate     # Windows

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar notebooks
jupyter notebook

TFM-Traduccion-AI/
│
├─ notebooks/         # Notebooks con análisis paso a paso
├─ data/              # Corpus original y traducciones
├─ scripts/           # Scripts de preprocesamiento y evaluación
├─ results/           # Resultados y gráficos
├─ docs/images/       # Capturas y gráficos para README
├─ README.md
└─ requirements.txt


---


