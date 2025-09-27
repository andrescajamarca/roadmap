# Plan ML 36W — Roadmap y Portafolio

**Objetivo**: en 6–12 meses, construir base sólida de ML, publicar 3 proyectos con demo y prepararse para **Google Professional Machine Learning Engineer (PMLE)**.

- Estudio: 6 h/semana · 36 semanas.
- Herramientas: Python/Linux, Platzi, Cursor-AI, Kaggle, GCP (Vertex AI), GitHub Actions.
- Guía por defecto: “Plan ML 36W”.

## Cómo usar este repo
1. Cada semana crea/actualiza el **issue de la semana (W##)** usando la plantilla.
2. Trabaja en `weeks/W##` y/o en un proyecto bajo `projects/`.
3. Sube entregables con commits pequeños y PRs enlazados al issue.
4. Marca el issue como Done al cumplir los criterios de aceptación.

## Estructura
- `weeks/W##`: notebooks, scripts y notas semanales.
- `projects/`: 3 proyectos principales de portafolio.
- `src/`: utilidades compartidas (p. ej., `features.py`, `train.py`).
- `tests/`: pruebas con `pytest`.

## Roadmap (W1–W36)

| Semana | Tema breve | Issue | Estado |
|---|---|---|---|
| W01 | Entorno & Pandas | #W01 | ☐ |
| W02 | Estadística I | #W02 | ☐ |
| W03 | Probabilidad I | #W03 | ☐ |
| W04 | Álgebra lineal I | #W04 | ☐ |
| W05 | Ingeniería de datos básica | #W05 | ☐ |
| W06 | Métricas & validación | #W06 | ☐ |
| W07 | Buenas prácticas + CI | #W07 | ☐ |
| W08 | SQL & datos | #W08 | ☐ |
| W09 | Regresión lineal/regularización | #W09 | ☐ |
| W10 | Clasificación lineal | #W10 | ☐ |
| W11 | Árboles & Ensembles | #W11 | ☐ |
| W12 | Tuning & Pipelines | #W12 | ☐ |
| W13 | No supervisado (PCA/Clustering) | #W13 | ☐ |
| W14 | Series de tiempo (🟦) | #W14 | ☐ |
| W15 | NLP clásico (TF-IDF) | #W15 | ☐ |
| W16 | **Capstone clásico** | #W16 | ☐ |
| W17 | API (FastAPI) | #W17 | ☐ |
| W18 | Docker | #W18 | ☐ |
| W19 | Monitoreo | #W19 | ☐ |
| W20 | MLflow/Evidently | #W20 | ☐ |
| W21 | CI/CD | #W21 | ☐ |
| W22 | **API pública + UI** | #W22 | ☐ |
| W23 | PyTorch básico | #W23 | ☐ |
| W24 | Visión (🟦) | #W24 | ☐ |
| W25 | NLP moderno (🟦) | #W25 | ☐ |
| W26 | Regularización & trucos DL | #W26 | ☐ |
| W27 | Serving DL | #W27 | ☐ |
| W28 | **Capstone DL** | #W28 | ☐ |
| W29 | GCP fundamentos | #W29 | ☐ |
| W30 | BigQuery/Dataflow (🟦) | #W30 | ☐ |
| W31 | Vertex AI (train) | #W31 | ☐ |
| W32 | Vertex Pipelines | #W32 | ☐ |
| W33 | Vertex Prediction/Monitoring | #W33 | ☐ |
| W34 | **PMLE Focus** | #W34 | ☐ |
| W35 | Portafolio & entrevistas | #W35 | ☐ |
| W36 | Simulacro PMLE & búsqueda | #W36 | ☐ |

> Marca con ✅ al cerrar cada issue.

## Proyectos clave
- **P1 — Capstone clásico** (tabular + SHAP + métricas claras)
- **P2 — API pública** (FastAPI + Docker + CI/CD + monitoreo + demo)
- **P3 — Deep Learning** (NLP o CV + serving)
- **P4 — Vertex AI** (pipeline end-to-end + monitoring)

## Criterios de calidad
- Tests (`pytest`), CI verde, `Dockerfile`, README con diagrama y demo, costos/latencia documentados, límites y próximos pasos.

## Pedidos de ayuda (formato)
`Plan ML 36W | Semana: W## | Tarea: <detalle> | Contexto: <dataset/objetivo> | Entregable: <notebook/script/metrics>`
