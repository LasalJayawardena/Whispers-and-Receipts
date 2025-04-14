# Spill The Data – Whispers & Receipts

**_For Educational Purposes Only_**

Welcome to *Spill The Data – Whispers & Receipts*, an academic exploration that transforms a corpus of over 11,000+ viral TikTok comments into an exquisitely detailed knowledge graph. This project models the alleged intricate, scandalous, and humorous interactions between celebrities and influencers using Neo4j and Cypher queries. All content is intended solely for educational purposes.

---

## NeoDash Analysis Video

For walkthrough of a preliminary analysis, watch the video below:

https://github.com/user-attachments/assets/df4cab8f-5fef-4188-a12c-f5341c86adac

---

## Overview

In this experiment, I scraped viral TikTok comments from the Kalathma Video and leveraged a large language model (LLM) to extract and categorize relationships among influential figures. The resulting graph includes:

- **Nodes:**  
  Represent celebrities, photographers, and various influential entities.

- **Edges:**  
  Depict dynamic interactions such as:
  - Represent dynamic interactions between entities. These interactions span a range of categories including, for example, `Cheating`, `Engagement`, `Dating`, `Scandal`, `Rumor`, `Flirting`, `Advice`, `Family`, etc.

Duplicate relationships between the same node pairs for a given relationship type are automatically merged to maintain clarity.


## Workflow

1. **Data Collection & Categorization:**  
   - Over 11,000 TikTok comments were scraped using Selenium on the Tiktok Page.  
   - A local LLM was used to categorize each comment into one of the interaction types listed above and automatically generated the comprehensive Cypher queries.

2. **Graph Construction:**  
   - The generated Cypher script creates nodes and over 600+ relationships and 800+ entities, each accompanied by the comment captured as the sources.
   - Duplicate edges are pruned automatically, ensuring a clean, interpretable graph.

3. **Visualization & Analysis:**  
   - Explore and interact with the graph using advanced visualization tools like NeoDash or Neo4j Bloom.
   - Dynamic filtering and rich visualizations provide a compelling overview of the complex network.

---

## Getting Started

- **Neo4j Setup:**  
  Download Neo4j from the [official website](https://neo4j.com/download/) and start running your cypher queries. No extensive setup instructions are necessary – simply download, load, and explore the graph in the Neo4j Browser.

---

## Disclaimer

This project is intended solely for educational and experimental purposes. Please note that:
- The data, extracted relationships, and corresponding Cypher queries were generated using LLMs which can hallucinate details or produce inaccuracies.
- This is a very quick experiment based on speculative analysis; the information presented here is not verified and does not represent my personal views.
- All content and extracted relationships are used exclusively as a demonstration of advanced graph modeling techniques in Neo4j. All intellectual property and content rights remain with their respective owners.

---

## Contributing

We welcome contributions from the community! Whether you have suggestions for additional relationship types, improvements to the data processing pipeline, or new visualization ideas, feel free to fork the repository and submit a pull request.

---

## Acknowledgements

- **TikTok:**  
  For bringing the oppurtunity to analyse and play with viral content.
- **Neo4j:**  
  For the powerful graph database technology enabling this exploration.
- **Isuru Alagiyawanna:**  
  Originally came up with the idea. I just wanted to have my own twist on it :).

Cheers Guys! This project is all about learning, exploration, and the art of storytelling through data.
