# Neuro-Symbolic-AI-for-Human-Like-Reasoning
This project implements a Neuro-Symbolic AI system that integrates Neural Perception (System 1) with Symbolic logic-based Reasoning (System 2) to achieve explainable and human-like reasoning. Inspired by dual-process cognitive theory, the system processes textual and visual inputs, converts neural outputs into symbolic representations, and performs logical inference to generate interpretable answers.

## Cognitive Motivation
Human intelligence relies on fast, intuitive perception and slow, analytical reasoning. Deep learning models excel at perception but lack structured reasoning, while symbolic systems provide logical inference but struggle with unstructured data. This project bridges both paradigms to model cognitively plausible and explainable AI reasoning.

## System Workflow
* Accept textual premises or visual inputs
* Perform neural-based perception and information extraction
* Convert extracted information into symbolic facts
* Store facts and rules in a knowledge base
* Apply symbolic reasoning to infer answers and explanations


## Functional Modules

### Neural Perception (System 1)
* Processes raw text or visual inputs
* Extracts entities, attributes, relations, quantities, and temporal cues
* Handles ambiguity and noise using deep learning models

### Symbolic Reasoning (System 2)
* Represents knowledge using logical predicates and rules
* Performs deductive, relational, numerical, spatial, and temporal reasoning
* Produces transparent and explainable inference outputs

## Architecture
<img width="334" height="526" alt="Neuro-Symbolic AI Flowchart" src="https://github.com/user-attachments/assets/1e7df298-0480-4bf1-b96b-9b1a73a65f4f" />

## Reasoning Capabilities
* Yes / No inference
* Who / What / Where / When questions
* Numerical and quantitative reasoning
* Spatial, relational, and causal reasoning

## Technical Details
* Programming Language - Python
* Neural Processing
        - Natural Language Processing for text understanding
        - Tokenization, embedding, and semantic feature extraction
        - Deep learning models for entity and relation detection
* Visual Processing (Optional Extension)
        - Object and attribute extraction from visual scenes
        - Spatial relationship identification
* Symbolic Reasoning
        - Logic-based knowledge representation
        - Predicate logic and rule-based inference
        - Query-driven logical reasoning
* Neuro-Symbolic Integration
        - Mapping neural outputs to symbolic predicates
        - Confidence-based fact generation
        - Hybrid neural–symbolic inference pipeline
  * Data Handling
        - Structured text reasoning datasets
        - Logic rule definitions and query sets
  * Libraries & Tools
        - PyTorch
        - NLP libraries
        - Logic programming frameworks
        - NumPy, Pandas
    
## Features
* Cognitively inspired dual-process architecture
* Explainable reasoning with logical traces
* Modular and extensible system design
* Supports multiple reasoning types and answer formats

## Output
* Logical answers to reasoning questions
* Interpretable reasoning steps and inference paths

