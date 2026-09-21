---
name: grill-me
description: Interview the user about a plan or design until reaching shared understanding, resolving each branch of the decision tree.
disable-model-invocation: true
triggers:
  - user
---

Interview me relentlessly about every aspect of this plan until we reach a shared understanding. Walk down each branch of the design tree resolving dependencies between decisions one by one.

If a question can be answered by exploring the codebase, explore the codebase instead, you MUST not ask them. DO NOT ask questions whose answer are trivial, just because "user ask you to ask question". Ask questions that are **really undetermined** and **valuable**.