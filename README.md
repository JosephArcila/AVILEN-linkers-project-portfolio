# AVILEN Linkers Project Portfolio
*December 2024 - February 2025*

## Overview
This repository documents my work as an AI Developer at AVILEN, where I implemented an automated research system based on the STORM architecture. The system generates comprehensive research reports in Japanese by gathering and synthesizing information from academic papers, patents, and web sources.

![STORM Architecture Overview](/images/storm-architecture-jp.png)
![STORM Architecture Overview](/images/storm-architecture-en.png)

## Project Phases

### Phase 1: Technology Evaluation (December 2024)
- Led evaluation of various AI technologies and search APIs
- Created systematic assessment framework
- Documented capabilities and limitations of different approaches

### Phase 2: Implementation & Testing (January-February 2025)
- Implemented STORM architecture with Japanese language support
- Created separate implementations for different data sources:
  * Academic paper research using OpenAlex API
  * Patent information search using SerpAPI
  * Web information search using DuckDuckGo
- Documented system design and results in both Japanese and English

## Repository Structure
```
AVILEN-linkers-project-portfolio/
├── README.md                              # Main project README
├── technology-evaluation/
│   ├── README.md                          # Was evaluation-summary.md
└── implementation/
    ├── README.md                          # Was storm-architecture.md
    └── experimental-outputs/
```

## Key Features
- Japanese language support throughout the system
- Modular search implementations for different source types
- Multi-perspective research approach
- Automated citation management
- Structured data handling using Pydantic

## Technologies Used
- AI/ML: LangGraph, OpenAI GPT models
- Search APIs:
  * OpenAlex API for academic papers
  * SerpAPI for Google Patents
  * DuckDuckGo for web search
- Development: Python, Pydantic
- Documentation: Bilingual (Japanese/English)

## Test Topics
System tested with topics including:
- エクソソームの研究のトレンド (Exosome Research Trends)
- アミンを用いた固体状のCO2吸着剤のトレンド (CO2 Absorption Technologies)
- 熱・風以外の方法で髪の毛を乾かす技術のトレンド (Novel Hair Drying Technologies)
- 安全に関する行動変容手法のトレンド (Behavioral Change Methods)
- 加熱調理器における料理品質・体験・機能に関する開発のトレンド (Cooking Appliance Innovations)
