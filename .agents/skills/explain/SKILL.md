---
name: explain
description: instructions on explaining something to user
disable-model-invocation: true
triggers:
  - user
---

# explain-unit

Explain 1 thing. Only explain the thing I told you to explain. 
DO NOT:
- extrapolate,
- write any code,
- give a bunch of background info,
- give "one liner explanation",
- ask me a new question,
- ask me if we need to modify any code, etc.
Simply explain the thing to me.
