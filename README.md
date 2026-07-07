# Noda AI Helpdesk Case

Noda is a knowledge base for AI clients, MCP connections, and AI helpdesk bots.

This repository describes how we use Noda to build and test an AI helpdesk for the Noda website itself.

Live site: [https://noda.sekura.world](https://noda.sekura.world)

The goal is simple: make an AI helpdesk answer from short canonical knowledge-base articles instead of relying on a large prompt, LoRA, or fine-tuning.

## What We Built

We built an AI helpdesk chat for Noda.

The helpdesk itself works on Noda:

* product knowledge is stored as short articles;
* articles are organized by category and tags;
* the AI helpdesk searches the knowledge base;
* the AI reads relevant articles;
* the answer is generated from the retrieved knowledge.

This is a dogfooding case: Noda is used to explain Noda.

## Why We Built It

Many AI helpdesk and support bot projects become complicated very quickly.

Typical problems include:

* long system prompts;
* unclear source of truth;
* duplicated answers;
* outdated documentation;
* hard-to-maintain RAG setup;
* attempts to use LoRA or fine-tuning too early;
* AI answers that sound confident but are not grounded in approved knowledge.

We wanted to test a simpler approach:

Improve the knowledge base first, not the prompt first.

## Core Idea

short article -> searchable knowledge -> grounded AI answer

Instead of putting all product knowledge into one large prompt, Noda keeps knowledge in reusable articles.

When the helpdesk gives a weak answer, we do not start by rewriting the whole prompt. We add or improve the article that should have answered the question.

## Articles

* [AI Helpdesk Without Fine-Tuning](articles/01-ai-helpdesk-without-finetuning.md)
* [Knowledge Base for AI Agents](articles/02-knowledge-base-for-ai-agents.md)
* [MCP Knowledge Base](articles/03-mcp-knowledge-base.md)
* [Canonical Articles](articles/04-canonical-articles.md)
* [Noda Dogfooding Case](articles/05-noda-dogfooding-case.md)
* [Commercial Knowledge Service](articles/06-commercial-knowledge-service.md)
* [Why Not Just RAG?](articles/07-why-not-just-rag.md)
* [Who Can Use Noda?](articles/08-who-can-use-noda.md)

## Project

Project: Noda
Company: Jupiter Soft
Location: Astana Hub, Kazakhstan

Noda focuses on a simple principle:

AI answers become better when knowledge is structured better.
