# Dynamic Knowledge System

[![Contributors](https://img.shields.io/github/contributors/your-username/dynamic-knowledge-system)](https://github.com/CharlesEmehel/dynamic-knowledge-system/graphs/contributors)

## Overview

The **Dynamic Knowledge System (DKS)** research project aims to explore new approach of knowledge representation and reasoning that adapt to evolving information in real-time. Traditional knowledge systems often face limitations in handling non-static, changing environments, often with manual processes of matching, adjusting, resolving and combining data, information and knowledge systems. These cannot reflect the dynamic nature of many real-world domains and digital models like digital twins and data spaces applications. DKS attempts to overcome these challenges through well researched algorithms, methodologies, architectures and models that allow for flexible, timely, and context-aware knowledge integration.

## Table of Contents
- [Introduction](#introduction)
- [Motivation](#motivation)
- [Core Components](#core-components)
- [Research Objectives](#research-objectives)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Knowledge representation and reasoning (KR&R) has been a foundational area of artificial intelligence (AI). While traditional KR&R systems work well for static environments with fixed ontologies, they falter in scenarios where data, rules, and knowledge bases change dynamically over time with uncertainties. My research, **Dynamic Knowledge System** or **DKS** seeks to address these limitations by developing systems that can autonomously update, evolve, and reason over knowledge bases and under uncertainties as new information becomes available.

The system is designed to be interdisciplinary, encompassing principles from:

- **Ontology learning**
- **Automated reasoning**
- **Dynamic semantics**
- **Neurosymbolic computing**
- **Temporal and probabilistic logic**

## Motivation

The increasing complexity of modern systems, such as:

- **Digital Twin**
- **Data Spaces**
- **Autonomous agents**
- **IoT networks**
- **Real-time decision-making systems**
- **Smart energy grids**


...calls for the development of knowledge systems that are not only aware of current states of the world but also capable of predicting and adapting to future changes in these systems, their data and metadata. The **Dynamic Knowledge System** aims to provide a framework that can:

1. Adapt to environmental changes in real-time.
2. Learn new facts and ontologies automatically using standards like CIM (IEC61968, IEC61970 and IEC62325), BFO (IEC/ISO21838) and W3C's (JSON-LD) standard.
3. Provide consistent, temporal and spatial reasoning and decision-making under uncertainty.
4. Interoperate with various data sources and ontological frameworks.

## Core Components

The **Dynamic Knowledge System** consists of the following core components:

1. **Ontology Management**:
   - Automatic creation, evolution, and alignment of ontologies.
   - Supports heterogeneous data sources and formats.
   - Suports computational efficiency and alignment during convergence of ontologies

2. **Dynamic Reasoning Engine**:
   - Capable of real-time reasoning under incomplete or evolving information.
   - Leverages a combination of symbolic and sub-symbolic (machine learning-based) techniques.

3. **Temporal and Probabilistic Logic**:
   - Integrates temporal reasoning (reasoning about time and change) and Probabilistic logic (logical reasoning under uncertainty) to support dynamic environments.

4. **Knowledge Updating Mechanism**:
   - Efficient methods for prunning, adding, modifying, or removing knowledge while preserving consistency.

5. **Interoperability and Integration**:
   - Supports integration with various other AI frameworks and external knowledge sources.
   - Uses semantic web technologies to ensure compatibility with existing knowledge standards.

## Research Objectives

The **Dynamic Knowledge System** project aims to achieve the following:

1. **Develop scalable models** for real-time knowledge acquisition, representation, and reasoning.
2. **Formalize dynamic knowledge** systems using advanced ontology learning, knowledge graphs, temporal logic and probabilistic logic.
3. **Build neurosymbolic models** that combine the interpretability of symbolic AI with the robustness of deep learning.
4. **Create a reference architecture** for dynamic knowledge systems that can be adapted to multiple domains, including building, EV mobility, and cyber physical components in the smart grid.
5. **Develop a DKS as a service** for modularity by interfacing to other use cases services through application programming interfaces.


## Methodology

The research follows a multi-step methodology to achieve its objectives:

1. **Problem Identification**: Define the limitations of current static knowledge systems and the need for dynamic capabilities.
2. **Formalization**: Develop formal models that describe how knowledge can evolve over time.
3. **Implementation**: Build a prototype using available AI Agents and knowledge representation technologies.
4. **Evaluation**: Test the system using gold standards or groundtrucths with real-world dynamic environments, such as autonomous driving, EV mobility or IoT networks.
5. **Iterative Improvement**: Continuously refine models based on performance, scalability, and accuracy metrics.

## Core Technologies Used

The following technologies and tools are used in the development of the **Dynamic Knowledge System**:

- **Python**: Main programming language for scripting implementation.
- **C++**: for interfacing to Context Brokers for speed in processing semantic link open data objects.
- **Java**: for reasoning with OWL-API using SPARQL Queries.
- **Node-js**: for translating different vendor data formats to the NGSI-ETSI standards.
- **Problog/PRISM**: that allows you to define probabilistic facts, axioms and rules and automatically computes the probabilities of different outcomes in a trial.
- **TensorFlow / PyTorch**: For machine learning components in neuro-symbolic systems.
- **Protégé**: For ontology management.
- **SPARQL**: For querying knowledge graphs.
- **Temporal Logic Tools**: For integrating temporal reasoning.
- **Docker**: To containerize the application and its components for creating services for integration purposes.
- **GraphQL**: For interacting with dynamic knowledge APIs.

## Installation

To install and run the **Dynamic Knowledge System** locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dynamic-knowledge-system.git

## Usage
Once the system is up and running, you can interact with it using the provided APIs or through a web interface. The system supports various modes of operation:

- **Ontology Creation**: Create and evolve ontologies using a combination of machine learning and rule-based methods.
- **Dynamic Querying**: Query dynamic knowledge bases in real-time using SPARQL and other querying languages.
- **Reasoning Engine**: Integrate the reasoning engine for real-time decision-making system.

Example query:

1. query the knowledge base:
   ```sparql
    SELECT ?entity ?property WHERE {
      ?entity rdf:type :DynamicConcept .
      ?entity :hasProperty ?property .
    }

## Contributing
We welcome contributions from the research community, developers, and AI enthusiasts! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit and push (`git push origin feature-branch`).
5. Submit a Pull Request.

Please ensure you follow the contribution guidelines outlined in the `CONTRIBUTING.md` file.

## License

The project is licensed under the MIT License and the artifacts, codebases and architecture belongs to RWTH Aachen University and can be obtained through the Automation of Complex Power Systems institute at the E.ON Energy research Center.

## Contact
For any questions, suggestions, or collaboration opportunities, feel free to reach out to:

Research Lead: [C. W. Emehel]
Email: [charles.emehel@eonerc.rwth-aachen.de]
Institution: [RWTH Aachen University/Institue for the Automation of Complex Power Systems]
Twitter: [@cemehel]