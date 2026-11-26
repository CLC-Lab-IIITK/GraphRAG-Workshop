
# GraphRAG Workshop
### Connecting Knowledge Graphs with Large Language Models

A hands-on introduction to Knowledge Graphs and Graph Retrieval-Augmented Generation (GraphRAG), organized by the **Culture, Language, Life and Computing (CLC) Lab**, Department of Computer Science and Engineering, IIIT Kottayam.

This workshop introduces the concepts and practical techniques for representing knowledge as graphs and connecting graph-based retrieval with Large Language Models (LLMs).

## About the Workshop

Retrieval-Augmented Generation (RAG) enables LLMs to generate responses grounded in external information. Knowledge Graphs provide a structured representation of entities and their relationships, enabling retrieval of connected information and multi-hop relationships.

This workshop explores how structured data and unstructured text can be transformed into Knowledge Graphs, and how these graphs can be connected with LLMs to build a simple GraphRAG application.

The hands-on activities use cloud-based tools, allowing participants to experiment without installing software locally.

## Learning Outcomes

By the end of this workshop, participants will be able to:

- Understand the fundamentals of Knowledge Graphs and GraphRAG.
- Represent entities, relationships, and properties as a Knowledge Graph.
- Construct Knowledge Graphs from structured tables.
- Extract entities and relationships from unstructured text using an LLM.
- Explore and query a graph database using Cypher.
- Connect a Knowledge Graph with an LLM for natural-language question answering.
- Experiment with prompt engineering to improve Text-to-Cypher generation.

## Workshop Materials

### 1. Workshop Slides

The presentation introduces RAG, Knowledge Graphs, graph construction, and GraphRAG.

[View / Download Workshop Slides (PDF)](GraphRAG-SIMAT.pdf)

### 2. Hands-on Notebooks

The notebooks are designed to run in Google Colab.

| Notebook | Description | Open in Colab |
|---|---|---|
| KG-RAG-SIMAT-ATAL-1.ipynb | Knowledge Graph construction and exploration | [Open Notebook](https://colab.research.google.com/github/CLC-Lab-IIITK/GraphRAG-Workshop/blob/main/KG-RAG-SIMAT-ATAL-1.ipynb) |
| Graph-RAG-SIMAT.ipynb | GraphRAG: connecting a Knowledge Graph with an LLM | [Open Notebook](https://colab.research.google.com/github/CLC-Lab-IIITK/GraphRAG-Workshop/blob/main/Graph-RAG-SIMAT.ipynb) |

### 3. Sample Cypher Queries

A collection of Cypher queries is provided to help participants explore the graph database.

[View Sample Queries](Sample%20Queries.txt)

## Tools and Technologies

The workshop uses the following tools and technologies:

- **Google Colab** – Cloud-based notebook environment
- **Neo4j AuraDB** – Cloud-hosted graph database
- **Hugging Face Transformers** – Loading and running open-source LLMs
- **Qwen** – Open-source instruction-tuned language model
- **Cypher** – Query language for Neo4j graph databases

## Getting Started

### Step 1: Open Google Colab

Open the relevant notebook using the **Open in Colab** links provided above.

You will need a Google account to use Google Colab.

### Step 2: Enable GPU Runtime

For LLM-based activities, a GPU runtime is recommended.

In Google Colab:

1. Select **Runtime → Change runtime type**.
2. Select a GPU under Hardware accelerator, if available.
3. Save the changes.

GPU availability may depend on your Colab account and current resource availability.

### Step 3: Set Up Neo4j AuraDB

The graph database is hosted using Neo4j AuraDB.

Participants who wish to run the notebooks independently should:

1. Create

