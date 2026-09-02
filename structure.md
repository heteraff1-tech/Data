# Data repository specification

## Purpose

Это основное хранилище входных данных для AI-команды.

## Folders

```
raw/
  original-files/
    interviews/
    conversations/
    tasks/
    documents/

context/
  projects/
  people/
  products/

insights/
  hypotheses/
  research-results/

chain/
  decisions/
  assumptions/
  next-steps/
```

## Rule

Raw files are never edited. AI agents create derived documents in context/insights/chain.
