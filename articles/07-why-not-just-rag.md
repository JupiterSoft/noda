# Why Not Just RAG?

RAG can be useful, but many teams make the project too complex too early.

A typical RAG project may require:

* document ingestion;
* chunking;
* embeddings;
* vector search;
* retrieval tuning;
* reranking;
* prompt design;
* evaluation;
* monitoring;
* repeated debugging.

This can be valuable for large systems, but it may be too much for a small team that mainly needs a reliable helpdesk or internal assistant.

## The Noda Difference

Noda starts with the knowledge structure.

Instead of asking "how do we index everything?", Noda asks:

what should the AI actually know, and what is the canonical answer?

This leads to short articles that are easier to search and easier to maintain.

## Not Anti-RAG

Noda is not against retrieval.

Noda itself is based on the idea that AI should retrieve relevant knowledge before answering.

The difference is that Noda encourages teams to prepare knowledge as reusable canonical articles, not only as large unstructured documents.

## Why This Helps

Structured knowledge helps reduce common problems:

* irrelevant retrieved context;
* outdated information;
* conflicting answers;
* prompt bloat;
* hard-to-debug hallucinations;
* unclear source of truth.

## When RAG May Still Be Needed

A more complex RAG system may be useful when:

* the knowledge base is very large;
* documents cannot be rewritten into articles;
* retrieval requires advanced ranking;
* multiple data sources must be combined;
* the use case requires deep document analysis.

## Summary

Noda is a simpler starting point for many AI helpdesk and support workflows.

The idea is not "no retrieval".

The idea is:

structured knowledge first, complex retrieval later if needed
