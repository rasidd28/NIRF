#  NIRF Analytics RAG System v3.0

**Advanced Retrieval-Augmented Generation & Analytics Pipeline for Indian Higher Education**

**NIRF/AMU Ready · Deep Faculty Analytics · Multi-Stage Data Processing · Rich Interactive Query & Export**

---

## 🏗️ Pipeline Architecture

This repository provides a highly modular, production-grade pipeline for extracting, cleaning, structuring, enhancing, and interactively analyzing NIRF reports and related institutional data.

### 🔄 Pipeline Stages

| Stage | Script                      | Purpose                                                                 |
|-------|-----------------------------|-------------------------------------------------------------------------|
| 1     | `pdf_extractor.py`          | PDF to clean text and metadata (multi-engine, OCR fallback)            |
| 2     | `embedding_preprocessor.py` | Cleans text, semantic chunking, category tagging & metadata enrichment |
| 3     | `enhanced_nirf_uploader.py` | Upload chunked data to vector DB (Qdrant), applies strong structuring  |
| 4     | `enhanced_faculty_cleaner.py` | Advanced post-processing/parsing for faculty section (quality analytics) |
| 5     | `nirf_rag_query.py`         | Interactive RAG querying, NIRF parameter analytics, stats, export      |

---

## 📦 Features

- 🔄 Robust multi-stage document ingestion and organization  
- 🔍 Semantic search-ready data via vector DB (Qdrant, Sentence Transformers)  
- 👩‍🏫 Deep, automated faculty data extraction and analytics  
- 📊 Comprehensive NIRF parameter integration (TLR, RP, GO, OI, PR)  
- 🖥️ Interactive terminal UI with rich tables, session statistics, and multi-format exporting  
- 🏛️ Custom institution focus (e.g., AMU), comparative and trend reports  

---

## 🖥️ Quick Start (Google Colab)

> 💡 This project is Colab-compatible! You can run each stage in a separate Colab notebook or cell block.



