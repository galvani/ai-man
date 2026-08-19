# AGENTS.md

> **If you are a learner's AI, this is not your file.** Load `persona/PERSONA.md` and configure yourself from that.
>
> This file is for AI agents that contribute to this repository — writing and editing its curriculum content.

## Purpose

This repository contains the design and content of AI Engineering Path: a practical, public 21-day introduction for people who have never programmed and are trying to discover whether AI engineering is for them.

This file is the working instruction set for AI agents contributing to this repository.

## Core philosophy

- The goal is not to teach traditional programming first and AI later.
- The goal is to teach people how to create real software with AI.
- AI should do as much implementation work as practical.
- The learner defines the goal, directs the AI, evaluates the result, understands important parts, and learns to diagnose and fix problems.
- Every practical project should produce a real, visible result and have a reason to exist.
- Theory is introduced when it becomes useful, not because it traditionally belongs in an introductory curriculum.
- The learner should be treated as an adult. Never patronize, infantilize, manipulate, or use fake enthusiasm.

## Four parallel tracks

Every day should ideally combine these four tracks:

1. BUILD — create something real.
2. UNDERSTAND — learn the concepts needed to understand what was built.
3. READ — read AI news, documentation, technical material, or relevant articles.
4. WORK WITH AI — learn to direct AI effectively as part of software development.

The balance can change from day to day.

## Teaching principles

### Meaning before terminology

When introducing a new technical concept:

1. Start with a concrete situation, example, analogy, or mental model.
2. Make sure the learner can understand why the concept exists.
3. Introduce the technical term.
4. Only then give a more precise technical definition when useful.

Never explain a new concept primarily through other concepts the learner has not encountered yet.

Do not overload an early explanation with every technically correct detail. Establish a correct basic model first and refine it later when the learner has a reason to care.

Explain a term where it first appears, and link it to `concepts/GLOSSARY.md`. The glossary holds the short canonical definition; the day keeps its own narrative introduction. A term that reaches the learner with neither is a defect, not a style preference.

### Learn by needing

Do not create artificial lessons such as "Today we learn ports" without a reason.

Instead:

- the project needs a server
- the server needs a port
- therefore we explain the port

The same applies to HTTP, JSON, APIs, databases, Linux, Git, processes, networking, etc.

### AI writes code

Do not force the learner to manually write code in order to "learn programming."

AI can write, modify, refactor, debug, and explain code.

The learner should instead learn to:

- describe what needs to be built
- provide useful context
- give good instructions
- inspect generated work
- run it
- read errors
- ask useful follow-up questions
- verify results
- understand important architectural and technical decisions

The goal is AI-assisted software creation, not typing practice.

### Understanding still matters

"AI wrote it" is not the end of the process.

The learner should gradually be able to explain:

- what the software does
- what its main components are
- how data moves through it
- why important parts exist
- what went wrong when something failed
- how to change or extend it

The required depth of understanding should grow with the learner.

## Technical foundations

Introduce foundational concepts progressively and in context, including when needed:

- files and directories
- programs and processes
- operating systems
- Windows vs Linux
- terminal
- localhost
- IP addresses
- ports
- HTTP
- requests and responses
- APIs
- JSON
- databases and SQL
- Python or another suitable language
- Git and GitHub
- deployment and basic infrastructure

Do not turn these into a traditional prerequisite curriculum.

## AI foundations

The learner should progressively build an accurate mental model of modern AI.

Eventually cover concepts such as:

- AI vs model vs application
- LLMs
- tokens and tokenization
- next-token prediction
- context
- inference
- sampling
- embeddings
- RAG
- tool/function calling
- agents
- MCP
- local models
- model size and parameters
- quantization
- GPU, VRAM, and inference performance
- evaluation and reliability

A core concept is that an LLM should not be presented as a human-like mind. Explain that language generation is fundamentally based on model prediction over tokens, while also explaining why this can produce surprisingly capable behavior.

Avoid both extremes:
- "AI is basically a person."
- "AI is just autocomplete."

The goal is a technically useful mental model.

## Working with AI as a software collaborator

The learner should gradually learn that AI is more than a chat window.

Introduce, when useful:

- project context
- project instructions
- README files
- AGENTS.md
- CLAUDE.md and equivalent files
- tools
- coding agents
- tool calling
- Git workflows
- tests
- documentation
- repeatable development workflows

Always explain why a mechanism is useful when it is first introduced.

## English

The project is bilingual by design.

- Explanations may be in Czech.
- Technical terms should retain their real English names where appropriate.
- Code, identifiers, variable names, filenames, Git usage, and technical documentation should use English.
- The learner does not need to speak or write English fluently.
- Reading technical English is an explicit goal.
- AI news and technical material should increasingly be read in English.
- Do not turn this into a school-style English course.

## AI news and ecosystem awareness

The learner should develop the habit of following the AI ecosystem.

Relevant topics include:

- new foundation models
- model releases and capabilities
- coding agents
- AI IDEs and developer tools
- APIs
- open-source models
- inference technology
- agent frameworks
- MCP
- important technical developments

Do not require the learner to follow every announcement.

The goal is to develop the habit of asking:

> What changed, and why does it matter?

Prefer current primary sources and good technical reporting when selecting reading.

## Tone and writing

Write for an adult beginner.

The tone should be:
- direct
- friendly
- natural
- respectful
- practical
- occasionally informal

Avoid:
- childish language
- "buddy", "sidekick", "AI pal", or similar forced familiarity
- motivational clichés
- marketing language
- condescending explanations
- unnecessary emojis
- fake claims about what the learner "must be excited about"

Do not tell the learner how they are supposed to feel.

## Curriculum design

The 21-day program is an experiment, not a promise of employment.

The primary outcome is:

> Does this person enjoy building things with AI enough to want to continue?

Each day should have a clear outcome.

Prefer:
- a concrete task
- a visible result
- a small amount of relevant theory
- one or more useful new concepts
- some reading
- reflection only when useful

Avoid:
- long theory chapters before practical work
- toy exercises with no purpose
- artificial programming drills
- overwhelming lists of technologies
- teaching terminology for its own sake

No day may depend on another person being reachable. Help is available on demand, but the material must work with nobody else present.

Learner-facing material names no prices and never asks the learner to buy anything. How a learner's access is funded is handled outside the curriculum.

The curriculum can change as we learn what works.

## Public project

This repository is intended for more people than the original pilot learner.

Do not write content around a specific individual.

The original learner is a pilot user, not the target audience.

Public materials should be useful to any motivated adult starting from zero or near-zero.

## Source of truth

Repository content is the source of truth.

Do not invent a second curriculum in a chat response when an existing repository document already defines it.

When modifying the curriculum:
- update the relevant source document
- keep terminology consistent
- avoid duplicating the same rule in many places
- prefer linking/referencing canonical documents

## File roles

- `AGENTS.md` — instructions for AI agents working on this repository.
- `SPECS.md` — evolving product/curriculum specification and design decisions.
- `persona/PERSONA.md` — canonical persona/instructions intended for the learner's AI. This is what a learner's AI loads when it arrives at the repository.
- `README.md` — public introduction and navigation.
- `21-days/` — learner-facing daily material.
- `concepts/` — reusable explanations of concepts. `concepts/GLOSSARY.md` is the canonical short definition of every term the material uses; day files link into it by anchor and keep their own narrative introduction.
- `projects/` — project briefs and project-related material.
- `resources/` — curated external resources.

## Change discipline

Before adding a new rule or concept, check whether it already exists.

Prefer improving an existing principle over adding a duplicate.

When a design decision is uncertain, record it in `SPECS.md` rather than silently inventing behavior.

Do not create Day 0, Day 1, or other learner-facing material merely to fill the repository. Build them from the agreed specification.

## Keeping the documents current

Every session that changes the product writes the decision down before it ends. A decision left only in a chat log is already lost: the next agent re-derives it differently, and the product drifts a little further each time. That drift is the failure this section exists to prevent.

Where a thing belongs:

- how the material is **written** — tone, terminology, structure, what may be assumed of the reader — this file
- what the product **is** — audience, scope, sequence, support model, and what was rejected — `SPECS.md`
- a **term the learner meets** — `concepts/GLOSSARY.md`

Write it in one of them, not two. State it where it belongs and reference it from the other; the same rule in two files becomes two different rules.

Record rejected options and the reason for rejecting them. Most drift is not a new mistake — it is re-proposing something already considered and turned down, because nobody wrote down why.

When a decision makes an existing line false, fix that line in the same session. A stale sentence in these documents is a defect: it will be read as current and acted on.

Read this file and `SPECS.md` before starting work. If what you are about to do contradicts either, say so and get it resolved — do not quietly do it your way and leave the documents describing something else.
