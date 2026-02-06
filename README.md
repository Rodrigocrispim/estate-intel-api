# vehicle-price-tracker
A scalable Python backend system to track automotive market trends. Built with FastAPI, Docker, and PostgreSQL, featuring AI-powered price analysis.

**Status:** 🚧 In Development (v0.1)

## Project Overview
This project is a high-performance backend system designed to scrape, aggregate, and analyze vehicle pricing data from major marketplaces. The goal is to provide real-time market intelligence and AI-driven valuation insights using a modern Python stack.

## Tech Stack (Target Architecture)
* **Language:** Python 3.12+
* **API Framework:** FastAPI (Async/Await)
* **Data Processing:** Pandas & BeautifulSoup4
* **Database:** PostgreSQL (with pgvector for RAG features)
* **Infrastructure:** Docker & Docker Compose
* **AI Integration:** OpenAI API for price sentiment analysis

## Architecture
The system follows a modular architecture:
1.  **ETL Pipeline:** Scrapes market data and cleanses it using Pandas.
2.  **Storage:** Persists structured data in PostgreSQL.
3.  **API Layer:** Exposes data via RESTful endpoints using FastAPI.
4.  **Intelligence:** An AI agent analyzes price deviations and flags "good deals".

## Roadmap
- [ ] **Phase 1:** Core Logic & Web Scraping (Current Focus)
- [ ] **Phase 2:** Data Persistence & CSV/SQL handling
- [ ] **Phase 3:** REST API Implementation with FastAPI
- [ ] **Phase 4:** Docker Containerization & AI Integration

## Project Mission
This repository serves as a practical masterclass in modern Backend Engineering. It is a self-taught initiative designed to go beyond academic theory and implement a production-grade system.
The primary goal is to master the complete data lifecycle:
1.  **Backend Architecture:** Building robust APIs with **Python/FastAPI**.
2.  **Data Engineering:** Implementing complex **ETL pipelines** (Extract, Transform, Load).
3.  **AI Integration:** Orchestrating LLMs for real-world analysis (not just chatbots).
4.  **Infrastructure:** Managing state and deployment with **Docker** and **PostgreSQL**.

---

*Author: Rodrigo Crispim*
