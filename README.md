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

## 🌌 1. General-Purpose Large Models
*Models designed to handle multiple geoscience tasks, cross-domain data, and autonomous workflows.*

### Foundation Models (Transformer)
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Intern-S1** | arXiv 2024 | Scientific multi-modal foundation model | [Paper](https://arxiv.org/abs/2410.14732) |
| **OFA-Net** | arXiv 2024 | Unified foundation model for Earth vision using a shared backbone | [Paper](https://arxiv.org/abs/2401.07527) |
| **Aurora** | arXiv 2024 | 1.3B parameter foundation model for the Earth system and atmosphere | [Paper](https://arxiv.org/abs/2405.13063) |

### Agents
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **PANGAEA GPT** | arXiv 2026 | Hierarchical multi-agent framework for autonomous geoscientific data discovery | [Paper](https://arxiv.org/abs/2602.21351) |
| **Earth-Agent** | arXiv 2025 | Agentic framework unifying RGB and spectral EO data with tool ecosystems | [Paper](https://arxiv.org/abs/2509.23141) |
| **LLM-Find** | arXiv 2024 | Autonomous GIS agent framework for geospatial data retrieval | [Paper](https://arxiv.org/abs/2407.21024) |
| **GeoFactory** | Journal 2025 | LLM performance enhancement framework for geoscience factual and inferential tasks | [Paper](https://doi.org/10.1080/20964471.2025.2506291) |

## 🌬️ 2. Atmosphere & Climate
*Models designed for weather forecasting, climate projection, and multimodal atmospheric analysis.*

### Vision Geo-foundation
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **FourCastNet** | Nvidia 2022 | High-resolution global data-driven weather forecasting | [Paper](https://arxiv.org/abs/2202.11214) |
| **GraphCast** | Google 2022 | Medium-range weather forecasting with Graph Neural Networks | [Paper](https://arxiv.org/abs/2212.12794) |
| **PanGu-Weather** | HUAWEI 2023 | 3D Earth-specific transformer for global weather forecasting | [Paper](https://arxiv.org/abs/2211.02556) |
| **FengWu** | SHAI 2023 | Multi-modal and multi-task global weather forecasting system | [Paper](https://arxiv.org/abs/2304.02948) |
| **FuXi** | FuDan 2023 | Cascade machine learning system for 15-day forecasts | [Paper](https://arxiv.org/abs/2306.12873) |
| **W-MAE** | UESTC 2023 | Pre-trained weather model using Masked Autoencoders | [Paper](https://arxiv.org/abs/2304.08754) |
| **Aurora** | Microsoft 2024 | Flexible foundation model for atmospheric physics | [Paper](https://arxiv.org/abs/2405.13063) |
| **ClimaX** | UCLA 2023 | Foundation model for weather and climate using heterogeneous data | [Paper](https://arxiv.org/abs/2301.10343) |
| **Prithvi WxC** | IBM 2024 | Scalable foundation model for various downstream WxC tasks | [Paper](https://arxiv.org/abs/2409.13598) |
| **WeatherGFM** | SHAI 2024 | Generative foundation model for probabilistic forecasting | [Paper](https://arxiv.org/abs/2404.14818) |

---

### LLM-powered Models & Agents
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **ClimateBert** | FAU 2021 | Specialized LLM for climate-related text analysis | [Paper](https://arxiv.org/abs/2110.12010) |
| **CliMedBert** | UNMC 2022 | Transformer model for climate and health-related text | [Paper](https://www.researchgate.net/publication/365942995_CliMedBERT_A_Pre-trained_Language_Model_for_Climate_and_Health-related_Text) |
| **ClimateGPT** | AppTek 2025 | AI synthesis of interdisciplinary climate research | [Paper](https://arxiv.org/abs/2401.09646) |
| **ClimateLLM** | USC 2025 | Efficient weather forecasting via frequency-aware LLMs | [Paper](https://arxiv.org/abs/2502.11059) |

---

### MLLM-powered Models & Agents
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **CLLMate** | HKST 2024 | Multimodal benchmark and model for weather events | [Paper](https://arxiv.org/abs/2410.15579) |
| **From News to Forecast** | USYD 2024 | Integrating event news into LLM-based weather forecasting | [Paper](https://arxiv.org/abs/2401.12560) |
| **RadarQA** | SHAI 2025 | Multimodal quality analysis and QA for weather radar | [Paper](https://openreview.net/forum?id=f7c16f2237) |
| **Aquilon** | HDSI 2025 | Multimodal weather LLM based on Qwen-VL architecture | [Paper](https://arxiv.org/abs/2410.22238) |
| **ZEPHYRUS** | UCSD 2025 | Agentic framework for comprehensive weather science | [Paper](https://arxiv.org/abs/2510.04017) |

---

## 💧 3. Hydrosphere, Ocean & Cryosphere
*Focuses on water cycles, marine biology, sea ice dynamics, and maritime understanding.*

### Pretrained LLM / QA
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **OceanGPT** | ZJU 2023 | The first LLM for ocean science with the OceanBench benchmark | [Paper](https://arxiv.org/abs/2310.02031) |
| **WaterGPT** | REN Lab 2024 | Specialized LLM and QA framework for hydrology and water resources | [Paper](https://arxiv.org/abs/2403.01374) |
| **LITE** | HRLICS 2024 | Multimodal ecosystem model for intelligent water-environment analysis | [Paper](https://arxiv.org/abs/2406.12328) |
| **Llamarine** | OpenMaritime 2025 | Large language model for reasoning in maritime navigation | [Paper](https://arxiv.org/abs/2501.12351) |

---

### Vision–Language Perception
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **MarineGPT** | HKUST-VGD 2023 | Vision-language understanding for underwater and maritime scenes | [Paper](https://arxiv.org/abs/2311.13473) |
| **CoralSCOP** | HKST 2024 | Transformer-based coral image segmentation and health assessment | [Paper](https://arxiv.org/abs/2403.04221) |
| **MarineDet** | USYD 2023 | Unified transformer framework for marine object detection | [Paper](https://arxiv.org/abs/2305.15843) |
| **MarineInst** | HKST 2023 | Instance segmentation and description for marine biology | [Paper](https://arxiv.org/abs/2307.01340) |
| **CoralVQA** | BUPT 2024 | Visual Question Answering model for fine-grained coral recognition | [Paper](https://arxiv.org/abs/2408.09876) |

---

### Vision (Oceanic & Water Body)
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **KUNPENG** | SHOU 2024 | Global ocean environmental forecasting using transformer backbones | [Paper](https://arxiv.org/abs/2405.08922) |
| **MarineSaliency** | UCSD 2025 | Diffusion-based model for saliency segmentation in marine images | [Paper](https://arxiv.org/abs/2501.03456) |
| **MF-SegFormer** | Tiany-Lab 2023 | Efficient transformer for large-scale water-body extraction | [Paper](https://doi.org/10.1109/LGRS.2023.3276510) |

---

### Cryosphere (Sea Ice)
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **IceDiff** | arXiv 2024 | Arctic sea-ice forecasting with generative diffusion priors | [Paper](https://arxiv.org/abs/2401.12560) |
| **SICFormer** | arXiv 2023 | 3D-Swin Transformer for sea ice concentration prediction | [Paper](https://arxiv.org/abs/2310.15174) |

---

## 🪨 4. Lithosphere & Solid Earth
*Models for geology, seismology, mineral exploration, and subsurface imaging.*

### Domain-Tuned LLM / VLM
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **K2** | SJTU 2025 | Large language model specialized in Geoscience QA (Geology and Earthquake) | [Paper](https://arxiv.org/abs/2403.01285) |
| **SeisMoLLM** | PJLAB 2025 | Specialized transformer model for earthquake monitoring and analysis | [Paper](https://arxiv.org/abs/2409.07727) |
| **SeisGPT** | Tongji Univ. 2024 | LLM-based framework for post-earthquake building damage assessment | [Paper](https://doi.org/10.1016/j.engstruct.2024.118650) |

---

### Hazard Monitoring
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Fish** | PJLAB 2024 | Fast earthquake intensity shell for monitoring and early warning using RetNet | [Paper](https://arxiv.org/abs/2406.10515) |
| **SeisT** | USGS 2024 | Hybrid CNN-Transformer model for robust earthquake monitoring | [Paper](https://doi.org/10.1785/0220230133) |
| **SeisCLIP** | Caltech 2024 | Contrastive learning for earthquake classification and localization | [Paper](https://arxiv.org/abs/2310.15340) |

---

### Resource Exploration & Geological Structure Imaging
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **MineAgent** | Curtin Univ. 2024 | MLLM-driven agent for remote sensing-based mineral exploration | [Paper](https://arxiv.org/abs/2406.02102) |
| **InversionNet** | Los Alamos 2019 | Deep learning for real-time subsurface ultrasonic and seismic imaging | [Paper](https://arxiv.org/abs/1905.01306) |
| **DispFormer** | SJTU 2025 | Transformer-based approach for high-resolution subsurface structure imaging | [Paper](https://arxiv.org/abs/2408.03157) |

---

### Lithology
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Geo-MMRAG** | CUG 2024 | Vision-language model using RAG for precise lithology identification | [Paper](https://arxiv.org/abs/2410.13432) |

---

## 🏙️ 5. Anthroposphere & Smart City
*Human-Earth interaction, urban planning, intelligent transportation, and urban environmental monitoring.*

### Urban Planning
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **UrbanPlanBench** | Tongji Univ. 2025 | Comprehensive benchmark for urban planning knowledge and QA | [Paper](https://arxiv.org/abs/2501.12351) |
| **PlanGPT-VL** | Tsinghua Univ. 2025 | Vision-Language model for urban planning document generation and evaluation | [Paper](https://arxiv.org/abs/2501.07173) |
| **City-LEO** | Peking Univ. 2024 | Planning and decision-making model under urban uncertainty | [Paper](https://arxiv.org/abs/2404.10300) |

---

### Transportation
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Open-TI** | MIT 2024 | Large language model for traffic demand optimization and signal control | [Paper](https://arxiv.org/abs/2404.10777) |
| **TransitGPT** | CMU 2025 | Natural language query interface for public transit systems | [Paper](https://arxiv.org/abs/2412.14660) |
| **TrafficGPT** | Tsinghua Univ. 2024 | LLM-based dialogue system for traffic management and query | [Paper](https://arxiv.org/abs/2401.07548) |
| **CityGPT** | UChicago 2024 | Unified language interface for cross-city information retrieval | [Paper](https://arxiv.org/abs/2401.12193) |
| **LA-Light** | Tsinghua Univ. 2024 | Hybrid LLM and tool-augmented agent for traffic signal control | [Paper](https://arxiv.org/abs/2312.16032) |
| **iLLM-TSC** | NUS 2024 | RL-assisted transformer for intelligent traffic signal control | [Paper](https://arxiv.org/abs/2407.12659) |
| **CoLLMLight** | MIT 2025 | Multi-agent signal optimization using collaborative LLMs | [Paper](https://arxiv.org/abs/2402.01257) |
| **ST-LLM** | Tsinghua Univ. 2024 | Spatio-temporal transformer for robust traffic forecasting | [Paper](https://arxiv.org/abs/2401.11470) |
| **TPLLM** | REN Lab 2024 | Traffic prediction using pre-trained language model backbones | [Paper](https://arxiv.org/abs/2403.02334) |
| **UrbanGPT** | Shenzhen Univ. 2024 | Spatio-temporal LLM for forecasting under data-scarce urban scenarios | [Paper](https://arxiv.org/abs/2403.00813) |

---

### Public Safety & Security
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **TrafficSafetyGPT** | UBC 2023 | LLM-based reasoning for traffic accident prediction and safety analysis | [Paper](https://arxiv.org/abs/2310.15174) |
| **ChatLaw** | Stanford Univ. 2023 | Specialized legal assistance model for urban regulations and laws | [Paper](https://arxiv.org/abs/2306.16092) |
| **WatchoverGPT** | UCLA 2024 | Multi-modal agent for emergency response and public monitoring | [Paper](https://arxiv.org/abs/2407.03478) |

---

### Environmental Sustainability
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **DeepAir** | KAUST 2023 | CNN-Transformer hybrid for high-precision air quality forecasting | [Paper](https://arxiv.org/abs/2304.14324) |
| **AirFormer** | Zhejiang Univ. 2023 | Global air quality foundation model based on transformer architecture | [Paper](https://arxiv.org/abs/2301.12644) |
| **LLM4DistReconfig** | Imperial Coll. 2025 | LLM-based framework for smart power-grid reconfiguration | [Paper](https://arxiv.org/abs/2406.10178) |

---

## 🌿 6. Biosphere
*Models for ecology, molecular biology, species distribution, and vegetation analysis.*

### Domain-Tuned LLM / QA
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Chatecology** | SSRN 2024 | Specialized LLM for ecological knowledge and Green-Tide disaster QA | [Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4842147) |
| **BioRAG** | ZoeChenLab 2024 | Retrieval-augmented generation framework for molecular biology and genetics | [Paper](https://arxiv.org/abs/2410.12560) |

---

### Observation & Language
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **Le-SINR** | UMass 2024 | Combining language embeddings with spatial networks for species range estimation | [Paper](https://arxiv.org/abs/2406.12056) |

---

### Vision Foundation
| Model | Publication | Key Contribution | Links |
| :--- | :--- | :--- | :--- |
| **DepthAnyCanopy** | DARTH 2024 | Zero-shot canopy height estimation using self-supervised depth foundation models | [Paper](https://arxiv.org/abs/2405.13063) |

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
