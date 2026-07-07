# MCP Knowledge Base

MCP allows AI clients to connect to external tools and knowledge sources.

Noda can be used as an MCP-connected knowledge base for AI clients.

The purpose is simple: let an AI client search and read Noda articles instead of guessing.

## What MCP Enables

With an MCP-style connection, an AI client may use tools such as:

* search;
* article retrieval.

This makes it possible to connect Noda knowledge to:

* ChatGPT;
* Claude;
* Codex;
* internal AI assistants;
* support bots;
* custom AI clients;
* developer tools.

## Access Control

Noda access is controlled through access keys and permissions.

A key can be configured with:

* enabled or disabled status;
* Read permission;
* Write permission, if needed;
* allowed operations;
* allowed categories.

This means an AI client does not automatically get access to all knowledge. Access depends on the configured key and category permissions.

## Safe Helpdesk Setup

For a public helpdesk bot, a safe setup is usually:

Enabled: yes
Read: yes
Write: no
Allowed operations: search, article
Allowed categories: noda-helpdesk

This allows the AI client to read helpdesk materials without editing the knowledge base.

## Summary

Noda can act as a knowledge base for MCP-connected AI clients.

The AI client searches and reads Noda articles, while access keys and categories control what it can access.
