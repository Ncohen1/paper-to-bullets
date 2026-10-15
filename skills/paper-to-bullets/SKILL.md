---
name: paper-to-bullets
description: "Turn a paper into five bullets: title, question, method, result, limitation. Use when the user shares a paper or asks to triage one."
---

# Paper to bullets

1. Read the file the user names. If no file is named, ask which one.
2. Output exactly these five bullets, in this order, and nothing else:

- **Title:** the paper's title.
- **Question:** the main question or problem the paper addresses.
- **Method:** how the authors tried to answer it.
- **Result:** the main finding.
- **Limitation:** the most important weakness or caveat.

Keep each bullet to one or two sentences. If the paper does not state something (for example, no limitation is mentioned), say "Not stated in the paper" rather than guessing.
