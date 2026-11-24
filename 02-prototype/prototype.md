# Prototype · Juno

> Module 2 · Prototype the Idea Worth Building. The working build that tests your idea, made with your build tool of choice.

Prompt Used:
Build a low-fidelity internal PM screen called “Juno Evidence Brief.”

A product manager selects five fictional customer-feedback notes. Juno creates an evidence-backed brief with customer problem, persona, repeated signals, source references, confidence, missing information, possible duplicate requests, and a recommended next action.

Do not invent customer facts. Clearly label assumptions and low-confidence results. The PM can accept, edit, or reject each section. Use synthetic data only.

## Prototype link

_The public share URL from your build tool. No share URL? A screenshot of the working flow is fine, the prompt is what is assessed._

_____

## What it demonstrates

A product manager selects five synthetic customer-feedback notes and reviews a Juno-generated evidence brief. The brief distinguishes source-grounded findings from assumptions and low-confidence results. The PM can accept, edit, or reject each brief section before the brief is shared or used for follow-up discovery.

_____

## Debrief

- **What worked:** The evidence boundary is visible throughout the flow. Each finding includes source references, and the prototype clearly marks assumptions, possible duplicates, and missing information. The accept, edit, and reject controls make the PM the reviewer, not a passive reader of AI output.
- **What broke / felt like a toy:** The feedback data is synthetic and fixed. Regenerating the brief does not yet change the analysis based on different selected notes, duplicate detection is only a labeled hypothesis, and there is no persistence, authentication, or real export.
- **What I'd change next pass:** Add a small set of alternate synthetic note sets so that selection changes the generated brief. Test whether PMs understand the evidence and confidence labels without explanation. Then add saved review decisions and a structured discovery handoff only if the review flow proves useful.
