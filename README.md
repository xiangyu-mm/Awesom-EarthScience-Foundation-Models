# Awesome-Earth-System-Foundation-Models

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Foundation Models](https://img.shields.io/badge/Topic-Foundation%20Models-blue)
![Geoscience](https://img.shields.io/badge/Domain-Geoscience-green)

A curated list of Large Foundation Models (LFMs) for Earth System Science, covering Perception, Reasoning, and Discovery across the five principal Earth spheres.

> **Note**: This repository is structured based on the survey: *Earth Science Foundation Models: A Survey on Perception, Reasoning, and Discovery*.

---

## 🧭 Taxonomy

The repository is organized by both **Earth Spheres** (Where the model is applied) and **Model Paradigms** (How the model is built).

- **Spheres**: Atmosphere, Hydrosphere, Cryosphere, Lithosphere, and Anthroposphere.
- **Paradigms**: Vision Foundation Models (VFM), Language Foundation Models (LLM), and Vision-Language Models (VLM).

---

## 🌌 1. Cross-Sphere & Multi-modal Models
*General-purpose models designed to handle multiple geoscience tasks or cross-domain data.*

| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Intern-S1** | arXiv 2024 | Scientific multi-modal foundation model | [Paper](https://arxiv.org/abs/2410.14732) |
| **AnySat** | CVPR 2024 | Multi-resolution, multi-scale, and multi-modal EO model | [Paper](https://arxiv.org/abs/2401.17180) |
| **Earth-Agent** | arXiv 2024 | Agent-based system for Earth Observation exploration | [Paper](https://arxiv.org/abs/2407.10423) |

---

## 🌬️ 2. Atmosphere & Climate (Atmosphere)
*Models for weather forecasting, climate projection, and atmospheric chemistry.*

### Foundation Models (WxC)
- **Climax**: A general foundation model for weather and climate. (ICLR 2023)
- **Aurora**: A foundation model for the entire atmosphere. (arXiv 2024)
- **Prithvi WxC**: A foundation model specifically for weather and climate applications. (arXiv 2024)

### Numerical Weather Prediction (NWP) & Downscaling
- **GraphCast**: Learning skillful medium-range global weather forecasting. (Science 2023)
- **FuXi / FengWu**: High-precision global medium-range forecasting systems.
- **ResDeepD**: Residual deep super-resolution network for precipitation downscaling.

---

## 🛰️ 3. Remote Sensing & Earth Observation (Vision-Centric)
*Focuses on satellite imagery understanding, segmentation, and change detection.*

| Category | Model / Paper | Description |
| :--- | :--- | :--- |
| **Vision (VFM)** | **Skysense** | Multi-modal RS foundation model for general interpretation. |
| **Vision (VFM)** | **SpectralEarth** | Large-scale hyperspectral foundation model. |
| **Multi-modal (VLM)** | **EarthGPT** | Universal multi-modal LLM for cross-sensor imagery. |
| **Multi-modal (VLM)** | **GeoChat** | Grounded vision-language model for Remote Sensing. |
| **Generative** | **DiffusionSat** | Generative foundation model for satellite imagery. |

---

## 💧 4. Hydrosphere, Ocean & Cryosphere
*Focuses on water cycles, marine biology, and sea ice dynamics.*

- **OceanGPT**: The first LLM for ocean science with the OceanBench benchmark.
- **WaterGPT / Water-Agent**: LLM and multi-agent framework for hydrology experts.
- **MarineGPT**: Unlocking the mysteries of the ocean via large language models.
- **IceDiff**: High-resolution Arctic sea-ice forecasting with generative diffusion priors.
- **SICFormer**: 3D-Swin Transformer for sea ice concentration prediction.

---

## 🪨 5. Lithosphere & Solid Earth
*Models for geology, seismology, and mineral exploration.*

- **K2 / GeoGalactica**: Foundation LLMs specialized in geoscience knowledge.
- **JiuZhou (九州)**: Open-source foundation model and framework for Earth science.
- **SeisCLIP**: Multi-modal seismic feature extraction using contrastive learning.
- **MineAgent**: Multi-modal LLM-driven agent for mineral exploration.

---

## 🏙️ 6. Anthroposphere & Smart City
*Human-Earth interaction, urban planning, and intelligent transportation.*

- **UrbanGPT**: Spatio-temporal large language models for urban computing.
- **TrafficGPT / LLMLight**: LLM-based agents for traffic signal control and management.
- **PlanGPT-VL**: Vision-Language models for enhanced urban planning.

---

## 📊 7. Datasets & Benchmarks
*Essential data resources for training and evaluation.*

- **SkyScript**: Large-scale RS vision-language dataset with diverse semantics.
- **RS5M**: A 5-million scale remote sensing vision-language dataset.
- **FloodNet**: High-resolution imagery for post-disaster scene understanding.
- **OceanBench**: A comprehensive benchmark for marine science models.

---

## 🛠️ Installation & Usage
To use the references provided in this repository, you can import the `references.bib` file into your LaTeX project or reference manager (Zotero/Mendeley).

```bash
git clone [https://github.com/your-username/Awesome-Earth-System-Foundation-Models.git](https://github.com/your-username/Awesome-Earth-System-Foundation-Models.git)
cd Awesome-Earth-System-Foundation-Models
