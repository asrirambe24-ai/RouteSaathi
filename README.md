# Routesaathi 🏔️

### Evidence-First AI Travel Intelligence for the Indian Himalayas

Routesaathi is an AI-powered travel intelligence platform designed to help independent travellers discover offbeat destinations and make informed travel decisions.

Unlike conventional travel planners that primarily focus on generating itineraries, Routesaathi aims to combine **Natural Language Processing (NLP), Retrieval-Augmented Generation (RAG), geospatial analytics, temporal reasoning and recommendation systems** to evaluate the practical feasibility of a journey.

The initial focus is on Himachal Pradesh, India, with the long-term vision of expanding across the Indian Himalayan region.

---

## 🎯 The Problem

Planning journeys to remote and less-commercialised destinations often requires gathering information from multiple disconnected sources, including travel blogs, government advisories, maps, weather reports and traveller experiences.

Important information regarding road accessibility, transportation, seasonal conditions and last-mile connectivity can be outdated, contradictory or difficult to verify.

Routesaathi aims to address this information gap by transforming fragmented travel information into structured, geographically relevant and time-aware evidence.

## 💡 Our Vision

To build an intelligent travel decision-support system that answers three fundamental questions:

- **Where should I go?** Discover destinations based on personal preferences rather than popularity alone.
- **How can I get there?** Understand routes, transportation options, accessibility and last-mile connectivity.
- **Can I realistically make this journey?** Evaluate time, budget, seasonal conditions and available evidence before committing to a trip.

## 🚀 Core Modules

### 1. Destination Intelligence
- Natural-language preference extraction.
- Semantic destination discovery.
- Personalised recommendation ranking.
- Explainable destination recommendations.

### 2. Journey Intelligence
- Geospatial route modelling.
- Route segmentation and accessibility analysis.
- Transport and last-mile connectivity research.
- Alternative route identification.

### 3. Evidence Intelligence
- Travel document ingestion and processing.
- Transformer-based information extraction.
- Hybrid retrieval using lexical and semantic search.
- Retrieval-Augmented Generation (RAG).
- Temporal evidence tracking and conflict detection.
- Source citations and evidence freshness indicators.

### 4. Journey Feasibility
- Budget and duration constraints.
- Transport compatibility.
- Weather evidence integration.
- Historical hazard exposure analysis.
- Explainable feasibility assessments.

### 5. Adaptive Itinerary Intelligence
- Constraint-based itinerary generation.
- Alternative destination recommendations.
- Disruption-aware itinerary repair.
- Preservation of user preferences and constraints.

## 🔬 Research and Innovation

Routesaathi explores the integration of geographical, temporal and semantic information for evidence-grounded travel decision support.

Key research directions include:

- **Route Evidence Passport:** Maintaining a source-linked history of travel-condition observations associated with individual route segments.
- **Temporal Evidence Resolution:** Distinguishing recent, historical, expired and conflicting travel information.
- **Himalayan Historical Hazard Lens:** Analysing historical landslide exposure along mapped routes using geospatial datasets.
- **HimaRouteBench:** A proposed benchmark for evaluating temporal, geographical and evidence-grounded travel question answering.
- **Adaptive Route Repair:** Investigating itinerary optimisation when route conditions or travel constraints change.

These are ongoing research directions. Their effectiveness and novelty will be evaluated through comparative experiments and documented benchmarks.

## 🛠️ Technology Stack

| Domain | Technologies |
|---|---|
| Programming | Python |
| Frontend | React, Next.js, TypeScript |
| Backend | FastAPI |
| Deep Learning | PyTorch |
| NLP | Hugging Face Transformers |
| Embeddings | Sentence Transformers |
| RAG | Hybrid Retrieval, Reranking |
| Relational Database | PostgreSQL |
| Geospatial Database | PostGIS |
| Vector Database | Qdrant |
| Maps and Geospatial Analysis | OpenStreetMap, GeoPandas, Shapely |
| Route Optimisation | OR-Tools |
| Experiment Tracking | MLflow |
| Dataset Versioning | DVC |
| Deployment | Docker |
| Testing | Pytest |

The technology stack will be implemented incrementally as the project progresses.

## 📊 Data Sources

Potential data sources include:

- [India Meteorological Department (IMD)](https://api.imd.gov.in/public/api_reference.html) — Weather forecasts and warnings.
- [Himachal Pradesh State Disaster Management Authority](https://sdma.hp.gov.in/) — Disaster and incident information.
- [NRSC Landslide Atlas](https://www.nrsc.gov.in/nrscnew/resources_atlas_landslide.php) — Historical landslide inventory.
- [Himachal Geo-Environmental Dataset](https://data.mendeley.com/datasets/mxpg845z62/2) — Geospatial landslide research data.
- [OpenStreetMap](https://www.openstreetmap.org/) — Roads, settlements and geographical features.
- Publicly accessible, appropriately licensed travel reports and traveller contributions.

All data acquisition and usage will be subject to applicable licences, source attribution requirements, API terms and privacy considerations.

## 🗺️ Development Roadmap

| Phase | Focus |
|---|---|
| Phase 1 | Project foundation and research |
| Phase 2 | Data acquisition and ingestion |
| Phase 3 | NLP dataset creation and Transformer development |
| Phase 4 | RAG and temporal evidence intelligence |
| Phase 5 | Destination recommendation engine |
| Phase 6 | Geospatial and historical hazard intelligence |
| Phase 7 | Journey feasibility and itinerary optimisation |
| Phase 8 | Frontend integration and deployment |
| Phase 9 | Research evaluation and benchmarking |

## 📍 Initial Geographic Scope

The first version will focus on selected destinations in Himachal Pradesh, including:

- Barot
- Rajgundha
- Bir–Billing
- Gushaini
- Tirthan Valley
- Jibhi
- Sainj Valley
- Kasol
- Kalpa
- Chitkul

Geographic coverage will expand progressively as reliable data becomes available.

## 📈 Project Status

**Current stage: Project initiation and infrastructure setup.**

The initial research, dataset preparation, backend infrastructure and database development are planned as the first milestones.

Features listed above represent the intended architecture and development direction, not necessarily completed functionality.

## ⚠️ Important Disclaimer

Routesaathi is intended as a travel information and decision-support platform. Historical hazard exposure, crowdsourced observations and AI-generated assessments are not safety certifications or guarantees of current road accessibility. Travellers must independently verify critical information with relevant local authorities before travelling.

## 👨‍💻 Development

Routesaathi is currently being developed as an independent, research-oriented project with the long-term possibility of evolving into a travel technology product.

Contributions, research discussions and constructive feedback are welcome.

---

**Routesaathi — Discover the unexplored. Understand the journey.**
