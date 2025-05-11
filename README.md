# Process_Mining - DABL Reimplementation with Llama 3.1-8B
## Overview
Anomaly detection in business processes plays a critical role in maintaining operational stability and efficiency. Traditional frequency-based approaches have inherent limitations, as not all rare behaviors are necessarily undesirable. Semantic analysis offers more precise anomaly detection, though current methods often decompose processes into event pairs, losing crucial long-term dependency information.

This project reimplements DABL (Detecting Anomalies in Business Processes using LLMs) from the original research (https://paperswithcode.com/paper/dabl-detecting-semantic-anomalies-in-business), with key modifications to adapt to constrained computational resources.

## Key Improvements
Model Optimization: Replaced Llama 2-13B with the more efficient Llama 3.1-8B architecture

Enhanced Training: Fine-tuned on a simulated dataset of 20,000 real-world business processes

Cross-Domain Testing: Validated model performance across multiple process datasets

## Methodology
Our implementation focuses on:

Preserving semantic relationships in end-to-end process analysis

Capturing long-term dependencies often missed by pairwise event approaches

Maintaining detection accuracy while reducing computational requirements

## Dataset
The training corpus contains:

Synthetically generated business processes

Annotated semantic anomalies

Real-world process patterns from operational logs