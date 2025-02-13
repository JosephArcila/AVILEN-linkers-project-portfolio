# STORM Architecture Implementation

## Overview
I implemented an automated research system based on the STORM (Synthesis of Topic Outlines through Retrieval and Multi-perspective Question Asking) architecture. The system automatically gathers information and generates comprehensive research reports in Japanese.

## System Architecture
![STORM Architecture Diagram](/images/storm-architecture-jp.png)

## System Flow with Intermediate Outputs

### Step 1: Research Input (入力トピック)
- System accepts Japanese research topic
- Example input: "エクソソームの研究のトレンド"
![Step 1 Output](/images/step1_input.png)

### Step 2: Initial Outline Generation (初期記事アウトライン生成)
- Creates preliminary structure for research
- Based on LLM's initial understanding
![Step 2 Output](/images/step2_outline.png)

### Step 3-4: Perspective Generation (関連トピック生成 & N個の異なる視点を生成)
- Creates diverse research perspectives
- Each perspective brings unique insights
![Step 3-4 Output](/images/step3_4_perspectives.png)

### Step 5-8: Information Gathering Through Dialog
- Expert conversations simulated
- Questions generated from each perspective
- Information gathered with citations
![Step 5-8 Output](/images/step5_8_dialog.png)

### Step 9-12: Report Generation and Refinement
- Final report assembly
- Citation integration
- Professional formatting
![Step 9-12 Output](/images/step9_12_final.png)

## Implementation Details

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
