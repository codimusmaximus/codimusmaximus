# Hey, I'm Alexander 👋

Building databases for the AI era.

## ChimeraDB

I'm the creator of **[ChimeraDB](https://github.com/codimusmaximus/chimeradb)** - a knowledge graph database that combines vector embeddings, Cypher graph queries, and full SQL analytics in a single SQLite file.

```python
from chimeradb import KnowledgeGraph

kg = KnowledgeGraph("my.db")

# Vector search - find by meaning
kg.search("who works on language models?")

# Graph queries - express relationships naturally
kg.cypher("MATCH (p:Person)-[:WORKS_AT]->(c:Company) RETURN p, c")

# SQL analytics - when you need it
kg.query("SELECT COUNT(*) FROM graph_nodes")
```

**Why it matters:** Most AI apps need semantic search, graph relationships, AND analytics. ChimeraDB gives you all three without managing separate databases.

**Perfect for:** RAG systems, AI agents, recommendation engines, knowledge graphs

[Install from PyPI](https://pypi.org/project/chimeradb/) | [Documentation](https://github.com/codimusmaximus/chimeradb/tree/main/docs) | [Examples](https://github.com/codimusmaximus/chimeradb/tree/main/examples)

## What I'm Working On

- Expanding ChimeraDB platform support (Linux/Windows)
- Building AI tools that combine semantic understanding with structured data
- Exploring the intersection of databases, vector search, and graph analytics

## Tech Stack

**Languages:** Python, SQL, TypeScript
**Interests:** Databases, Vector Search, Graph Algorithms, LLM Applications, RAG

## Connect

- 🌐 [alexander.space](https://alexander.space)
- 📧 alexander@prismeta.com
- 🐙 Open to collaboration on database tooling and AI infrastructure

---

*Currently: Making databases smarter for LLM applications*
