# Noda Dogfooding Case

Noda uses Noda to explain Noda.

This is a dogfooding case: the AI helpdesk for the Noda website works from articles stored in Noda.

## What We Test

We test whether a small team can improve an AI helpdesk by improving the knowledge base.

The main questions are:

* Can users understand what Noda is?
* Can the helpdesk explain MCP connection clearly?
* Can it answer pricing and access questions?
* Can it avoid inventing information?
* Can new user questions be turned into new canonical articles?
* Can the helpdesk improve without fine-tuning?
* Can short articles replace a large fragile prompt?

## How the Loop Works

The improvement loop is simple:

1. A user asks a question.
2. The helpdesk answers.
3. We check whether the answer is clear and grounded.
4. If the answer is weak, we identify the missing or unclear article.
5. We add or improve the article.
6. The helpdesk improves through the knowledge base.

## Example

A user may ask:

Can I sell access to my knowledge stored in Noda?

If the helpdesk gives a vague answer, we add a canonical article that explains:

* Noda does not define the user's business model;
* the user controls who gets access and under what conditions;
* Noda provides the technical platform and access-control tools;
* payments, contracts, taxes, and client obligations remain outside Noda.

After that, the helpdesk can answer the question more clearly.

## Main Effect

The main effect is operational simplicity.

Instead of maintaining one large prompt or retraining a model, we maintain a set of short articles.

This gives us:

* faster updates;
* clearer source of truth;
* easier debugging of bad answers;
* reusable helpdesk material;
* better separation between product knowledge and model behavior.

## Summary

Noda dogfooding shows the core product idea in practice:

if the AI answer is weak, improve the knowledge base.
