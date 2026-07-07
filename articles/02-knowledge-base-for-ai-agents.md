# Knowledge Base for AI Agents

AI agents need reliable knowledge.

Without a clear source of truth, an AI agent may:

* guess;
* mix unrelated facts;
* use outdated information;
* answer confidently but incorrectly;
* fail to explain where the answer came from.

Noda is designed as a knowledge base for AI clients and AI agents.

## What Noda Stores

Noda stores knowledge as short canonical articles.

Each article should answer one clear question or explain one stable piece of knowledge.

Examples:

* What is Noda?
* What is an access key?
* How do I connect Noda to ChatGPT?
* What should I do after connecting Noda to an AI client?
* Can I use Noda for an AI helpdesk?
* Can I provide access to my own knowledge service?

## Why Short Articles

Short articles are easier for AI agents to use than large documents.

They help the system:

* search more precisely;
* read only relevant knowledge;
* reduce unrelated context;
* avoid mixing topics;
* update answers quickly;
* keep support answers consistent.

## How AI Agents Use Noda

A typical workflow looks like this:

1. The user asks a question.
2. The AI client searches Noda.
3. Noda returns relevant articles.
4. The AI client reads the article.
5. The AI client answers from the article.

The AI should not guess when the answer already exists in the knowledge base.

## Summary

Noda gives AI agents a structured knowledge layer.

Instead of relying only on model memory or long prompts, the AI client can search and read approved knowledge before answering.
