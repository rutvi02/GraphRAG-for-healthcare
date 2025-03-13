# Abstract 

In recent years, transformer-based large language models (LLMs) have emerged as powerful tools for generating human-like text. However, a significant challenge remains: the phenomenon of ”hallucination”, where models produce factually
incorrect outputs due to insufficient data support. This issue is particularly critical in the healthcare domain, where inaccurate
information can lead to severe consequences for patient care and
decision- making. Previous methods for mitigating hallucinations,
such as retrieval augmented generation (RAG) provide direct
relationships between entities, leaving out high-level connections.
GraphRAG is a technique that utilizes knowledge graphs (KGs)
to incorporate information from large complex data in a struc-
tured format, facilitating context-aware responses from LLMs.
However, extracting information from knowledge graphs built
from large datasets presents significant challenges, particularly in
information retrieval. We will be using the Semantic MEDLINE
Database (SemMedDB), which contains automatically extracted
information from medical literature, to construct a knowledge
graph. By integrating this structured data into a Neo4j graph
database, we enable effective querying using Cypher. Our study
will explore generating these queries from natural language
through LLMs, using techniques such as prompt engineering
and entity extraction. By leveraging GRAG, we aim to enhance
the reliability of LLM outputs, ensuring they are both accurate
and contextually relevant in medical applications.

# Approach 

<img width="432" alt="Screenshot 2025-03-13 at 6 59 05 PM" src="https://github.com/user-attachments/assets/fd1fe676-5228-4df8-976e-0d9c25ff1aaf" />
