# Inteligencia Artificial Generativa y Multimodal
## Escuela de Ciencias Informáticas (ECI) 2026 — Departamento de Computación, FCEyN, Universidad de Buenos Aires

**Docente:** [Valentín Barriere](https://valbarriere.github.io/) — Universidad de Chile

Este repositorio contiene el material (laboratorios, tutoriales y diapositivas) del curso **Inteligencia Artificial Generativa y Multimodal**, dictado en la [ECI 2026](https://eci.dc.uba.ar/cursos-eci/) (Escuela de Ciencias Informáticas, FCEyN - UBA), del **lunes 27 al viernes 31 de julio de 2026**.

* **Turno:** Tarde, 13:30 a 16:30 hs
* **Idioma:** Español
* **Aula Magna**
* **Página del curso:** https://eci.dc.uba.ar/t2-barriere/

### Resumen

Este curso ofrece una introducción práctica y conceptual a los fundamentos y aplicaciones de la inteligencia artificial generativa y multimodal. A través de una combinación equilibrada entre teoría y práctica, se explorará cómo los modelos generativos modernos —modelos de visión (GANs, autoencoders variacionales, modelos de difusión), modelos de audio, y modelos de lenguaje de gran escala (textuales y multimodales)— pueden crear, transformar y comprender distintos tipos de contenido (texto, imágenes, audio y datos multimodales).

Los laboratorios *hands-on* permiten experimentar directamente con herramientas y bibliotecas actuales del ecosistema de IA (`transformers`, `diffusers`, `peft`, …) de Hugging Face para construir, adaptar y combinar modelos generativos en escenarios reales.

### Prerrequisitos

Bases de Machine Learning y Deep Learning. Se recomienda (no es obligatorio) tener bases de NLP y de procesamiento de señales (STFT, escala Mel, etc.).


## Contenido del curso
https://colab.research.google.com/github/valbarriere/CC6XXX-Generative-AI/blob/main/Labs/Lab1-Toonification.ipynb
El curso está organizado en **5 días**. Cada día combina una **clase cátedra** (teoría, 1h30) con un **laboratorio hands-on** (práctica, 1h30) sobre el mismo tema.

| # | Tema | Diapositivas | Laboratorio |
|---|------|--------------|--------------|
| 1 | **Modelos de Visión** — GANs, modelos autoregresivos, autoencoders variacionales y modelos de difusión | [Generative_vision.pdf](https://users.dcc.uchile.cl/~vbarrier/ECI2026_MModal_GenAI/slides_es/Generative_vision.pdf) | [Lab1](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Labs/Lab1/Lab1-Toonification.ipynb) — Edición de caras con GANs (StyleGAN toonification) |
| 2 | **Modelos de Lenguaje (LLM)** — modelización del lenguaje, tokenización, entropía y temperatura, In-Context Learning, instrucciones, alineamiento, entrenamiento y evaluación en la práctica | [Generative_LLMs.pdf](https://users.dcc.uchile.cl/~vbarrier/ECI2026_MModal_GenAI/slides_es/Generative_LLMs.pdf) | [Lab2](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Labs/Lab2/Lab2-alignment_deployment.ipynb) — Instruction-tuning (SFT + LoRA) de Qwen2.5, base vs. SFT vs. Instruct |
| 3 | **Modelos de Audio** — procesamiento del audio, wav2vec/HuBERT/WavLM/AST, Speech-aware LLMs, tokenización y códecs, generación de música | [Audio_models.pdf](https://users.dcc.uchile.cl/~vbarrier/ECI2026_MModal_GenAI/slides_es/Audio_models.pdf) | [Lab3-1](https://colab.research.google.com/github/valbarriere/blob/main/ECI2026_MModal_GenAI/Labs/Lab3/Lab3-1_AudioProcessing.ipynb) y [Lab3-2](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Labs/Lab3/Lab3-2_AudioClassification.ipynb) — Preprocesamiento de audio y clasificación de género musical (GTZAN) con modelos preentrenados |
| 4 | **Modelos Multimodales** — tipos de fusión, CLIP, Stable Diffusion, modelos generativos (BLIP-1/2), modelos basados en LLM (Flamingo, LLaVA) | [Multimodal_LLM.pdf](https://users.dcc.uchile.cl/~vbarrier/ECI2026_MModal_GenAI/slides_es/Multimodal_LLM.pdf) | [Lab4](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Labs/Lab4/Lab4.ipynb) — Clasificación multimodal de tweets de desastres (CrisisMMD) con fusión de texto e imagen |
| 5 | **LLM y LMM avanzados** — eficiencia, RAG, herramientas y agentes, Large Multimodal Models | [Advanced_llm.pdf](https://users.dcc.uchile.cl/~vbarrier/ECI2026_MModal_GenAI/slides_es/Advanced_llm.pdf) | [Lab5](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Labs/Lab5/Lab5-lmm_final.ipynb) — Captioning y Visual Question Answering con SmolVLM y BLIP-2 |

## Material complementario: Tutoriales

Como material de apoyo adicional, se incluyen dos tutoriales introductorios en [`Tutoriales/`](Tutoriales):

* [1_Hugging_Face_Transformers_Tutorial](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Tutoriales/1_Hugging_Face_Transformers_Tutorial.ipynb) — Introducción a la librería `transformers` de Hugging Face (pipelines, tokenizers, modelos preentrenados).
* [2_Multimodalidad](https://colab.research.google.com/github/valbarriere/ECI2026_MModal_GenAI/blob/main/Tutoriales/2_Multimodalidad.ipynb) — Introducción a modelos y representaciones multimodales.
