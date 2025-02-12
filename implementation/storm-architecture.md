# STORM Architecture Implementation

## Overview
I implemented an automated research system based on the STORM (Synthesis of Topic Outlines through Retrieval and Multi-perspective Question Asking) architecture. The system automatically gathers information and generates comprehensive research reports in Japanese.

## System Architecture
![STORM Architecture Diagram](/images/storm-architecture.png)

## How It Works

### 1. Research Input
- The system accepts a research topic in Japanese
- Example: "エクソソームの研究のトレンド" (Exosome Research Trends)

### 2. Multi-Perspective Analysis
- The system creates different research perspectives to ensure comprehensive coverage
- Each perspective brings unique insights to the research
- Examples include technical experts, market researchers, and domain specialists

### 3. Information Gathering
Created separate implementations for different source types:
- Academic Papers: Using OpenAlex API
- Patents: Using SerpAPI (Google Patents)
- Web Information: Using DuckDuckGo

### 4. Expert Dialogue Simulation
- Simulates research conversations between:
  * A researcher asking specific questions
  * An expert providing detailed, cited answers
- All responses include proper citations
- Creates structured information gathering

### 5. Report Generation
Based on the prompts in the implementation:
- Generates initial outline
- Refines outline based on gathered information
- Creates sections with cited content
- Maintains professional Japanese writing style

## Key Features

### Japanese Language Support
- Complete Japanese language integration
- Natural writing style
- Professional formatting standards

### Citation Management
- Tracks information sources
- Automatically adds citations
- Creates formatted references

### Search Integration
- Modular search implementation
- Flexible API integration
- Structured data handling

## Results
The system successfully:
- Processes complex technical topics
- Maintains proper citations
- Produces clear Japanese writing
- Follows professional formatting
- Organizes technical information systematically
