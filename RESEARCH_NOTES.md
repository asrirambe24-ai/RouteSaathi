# Routesaathi — Research Notes

**Last reviewed:** 12 November 2026  
**Research phase:** Competitor Analysis and Research Foundation  
**Project scope:** Himachal Pradesh, India

---

## 1. Research Objective

The objective of this research is to understand the existing travel technology landscape, identify limitations in current travel-planning approaches and establish a defensible technical research direction for Routesaathi.

Routesaathi aims to develop an evidence-first AI travel intelligence platform combining natural language processing, retrieval-augmented generation, temporal reasoning, geospatial analytics and destination recommendation.

The focus is on travel information for under-documented destinations in the Indian Himalayas.

## 2. Competitor Analysis

### 2.1 TripYara
Website: https://tripyara.in/

Observed capabilities:
- AI-generated day-wise itineraries.
- Route planning and travel estimates.
- Offline trip access.
- Fuel and expense planning.
- Packing checklists.
- Emergency information.
- Group trip sharing.
- Motorcycle group Ride Mode.

Assessment:

TripYara is the closest Indian competitor to Routesaathi's travel-planning proposition.

Routesaathi should not claim AI-based Indian road-trip planning as a novel feature.

Potential differentiation:
- Route-segment-level evidence history.
- Temporal evidence processing.
- Contradiction identification.
- Historical geospatial hazard exposure.
- Claim-level source provenance.

### 2.2 Wanderlog
Website: https://wanderlog.com/

Observed capabilities:
- AI travel assistant.
- Itinerary management.
- Route optimisation.
- Interactive maps.
- Budget and expense tracking.
- Accommodation and reservation organisation.
- Collaboration.
- Offline itinerary access.

Assessment:

Wanderlog demonstrates strong integration of travel-planning activities into one application.

Routesaathi should learn from its user experience while differentiating through evidence quality and journey intelligence.

### 2.3 Roadtrippers
Website: https://roadtrippers.com/

Observed capabilities:
- Offbeat destination discovery.
- Route-based recommendations.
- Multi-stop trip planning.
- Fuel estimation.
- Traveller reviews.
- Turn-by-turn navigation.
- Offline maps.
- Live traffic.

Assessment:

Roadtrippers is a strong reference for road-trip discovery and route-based exploration.

Routesaathi should focus on evidence about remote mountain journeys rather than duplicating its navigation and route-planning features.

### 2.4 Tripoto
Website: https://www.tripoto.com/

Observed capabilities:
- User-generated travel stories.
- Traveller-created itineraries.
- Destination discovery.
- Travel photographs.
- Travel maps.
- Travel creator community.
- Search and filtering by travel preferences.

Assessment:

Tripoto demonstrates the value of first-hand traveller experiences.

Routesaathi could eventually extract structured, attributable travel-condition information from voluntarily contributed observations.

### 2.5 Competitor Research Conclusion

AI itineraries, route optimisation, semantic recommendation, offline planning and crowdsourced travel discovery are established capabilities.

Routesaathi will differentiate through geographically anchored, temporally aware travel evidence and explicit uncertainty handling.

Features not documented in the competitors' reviewed public materials should not automatically be assumed absent from their internal systems.

---

## 3. Academic Research

### Paper 1
**MRAG: A Modular Retrieval Framework for Time-Sensitive Question Answering**

Venue: Findings of EMNLP 2025.

Link: https://aclanthology.org/2025.findings-emnlp.167/

Relevance:
- Temporal question processing.
- Semantic-temporal retrieval.
- Fine-grained evidence selection.
- Time-sensitive RAG evaluation.

Routesaathi application:

Adapt temporal retrieval ideas to geographical route-condition questions by incorporating route-segment matching, source provenance and observation-time information.

### Paper 2
**A Survey on Point-of-Interest Recommendations Leveraging Heterogeneous Data**

Authors: Zehui Wang, Wolfram Höpken and Dietmar Jannach.

Published: 2025.

Link: https://link.springer.com/article/10.1007/s40558-024-00301-3

Relevance:
- Personalised tourism recommendation.
- Heterogeneous data integration.
- Context-aware POI recommendation.

Routesaathi application:

Combine natural-language preferences, destination attributes, geographical context and activity compatibility.

### Paper 3
**Towards Travel Recommendation Interpretability: Disentangling Tourist Decision-Making Process via Knowledge Graph**

Published: 2023.

Link: https://doi.org/10.1016/j.ipm.2023.103369

Relevance:
- Explainable destination recommendations.
- Tourism knowledge graphs.
- Geographical and functional relationships.

Routesaathi application:

Investigate graph-enhanced destination ranking and explainable recommendations.

### Paper 4
**Ontology-Based Approaches for Multi-Destination Tourism Planning: A Systematic Literature Review**

Published: 2026.

Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC13429745/

Relevance:
- Tourism knowledge representation.
- Multi-destination planning.
- Itinerary-level relationships.
- Semantic route planning.

Routesaathi application:

Investigate how route sequences, destination dependencies and journey constraints can be represented systematically.

---

## 4. Identified Research Opportunity

Proposed research direction:

**Geographically and Temporally Aware Evidence Retrieval for Travel-Condition Question Answering.**

Research proposition:

A travel-condition retrieval system may benefit from combining semantic relevance, temporal relevance, geographical entity matching and source provenance rather than relying exclusively on document-level semantic similarity.

This proposition requires experimental validation.

## 5. Proposed Research Questions

RQ1: Does geo-temporal evidence ranking improve retrieval performance compared with conventional RAG for travel-condition questions?

RQ2: Does claim-level evidence extraction improve source attribution and contradiction detection?

RQ3: Does geographical route-segment matching reduce retrieval errors caused by reports about nearby but unrelated roads?

RQ4: Does evidence-based abstention reduce unsupported claims about current accessibility?

RQ5: Can historical landslide exposure provide useful explanatory context for route comparisons?

## 6. Proposed Technical Contribution

### Route Evidence Passport

A route-segment-oriented evidence model recording:
- Geographical segment.
- Observation time.
- Publication time.
- Source identity.
- Claim type and status.
- Extraction confidence.
- Location-matching confidence.
- Verification status.
- Conflict relationships.

### GeoTemporal Evidence RAG

Proposed retrieval pipeline:

1. Natural-language question processing.
2. Temporal constraint extraction.
3. Geographic entity resolution.
4. Claim-level and document-level retrieval.
5. Semantic and temporal relevance ranking.
6. Spatial relevance matching.
7. Source-aware conflict resolution.
8. Evidence-grounded response generation.
9. Abstention when sufficient evidence is unavailable.

### Himalayan Historical Hazard Lens

Overlay historical landslide observations and available environmental data on mapped route corridors.

This will be presented as historical exposure analysis, not live hazard prediction.

## 7. Proposed Research Benchmark

Working name: HimaRouteBench.

Purpose:

Evaluate geographically and temporally grounded travel-condition question answering.

Initial benchmark components:
- Temporal relevance questions.
- Route-segment matching questions.
- Source provenance questions.
- Contradictory evidence scenarios.
- Historical hazard interpretation.
- Abstention scenarios.

Initial evaluation metrics:
- Recall@5.
- MRR@10.
- nDCG@10.
- Spatial entity-matching accuracy.
- Temporal-state accuracy.
- Conflict detection F1.
- Citation correctness.
- Unsupported-answer rate.

The benchmark will be manually reviewed and split using geographical and temporal separation to reduce data leakage.

## 8. Planned Baseline Comparisons

| Experiment | Baseline | Proposed approach |
|---|---|---|
| Retrieval | Dense vector search | Geo-temporal hybrid retrieval |
| RAG | Standard RAG | Evidence-aware RAG |
| Destination ranking | Attribute matching | Hybrid semantic ranking |
| Recommendation | Embedding-based model | Graph-enhanced experiment |
| Evidence resolution | Document-level processing | Claim-level processing |
| Itinerary planning | Unconstrained generation | Constraint-validated planning |

## 9. Research Limitations

- Existing research already covers temporal RAG, tourism recommendation and knowledge-graph-based itinerary planning.
- Public competitor documentation cannot establish the absence of undisclosed technical features.
- Live road-condition information may be unavailable or incomplete.
- Historical landslide records cannot establish current hazard conditions.
- Source reuse rights vary between data providers.
- The proposed benchmark requires original annotation and independent evaluation.
- Product differentiation does not automatically imply scientific novelty.

## 10. Initial Research References

1. Zhang et al. (2025), MRAG: https://aclanthology.org/2025.findings-emnlp.167/
2. Wang et al. (2025), POI Recommendation Survey: https://doi.org/10.1007/s40558-024-00301-3
3. Gao et al. (2023), Explainable Tourism Recommendation: https://doi.org/10.1016/j.ipm.2023.103369
4. Izani and Che Lah (2026), Tourism Knowledge Graph Review: https://pmc.ncbi.nlm.nih.gov/articles/PMC13429745/

---

**Research conclusion:**

Routesaathi will focus on evidence-grounded travel intelligence for the Indian Himalayas. Its central research direction is the combination of temporal and geographical evidence retrieval, claim-level source traceability and explicit uncertainty management.
