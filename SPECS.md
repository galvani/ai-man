# SPECS.md

# AI Engineering Path — Working Specification

Status: Draft / evolving

## 1. Product idea

AI Engineering Path is a public, practical learning experience for someone who starts with little or no IT knowledge and wants to discover whether AI engineering is a direction worth pursuing.

The first milestone is a 21-day experiment.

It is not intended to turn someone into a professional AI engineer in 21 days.

The purpose of the 21 days is to create enough real experience to answer:

> Do I enjoy this enough to continue?

## 2. Target learner

The material should work for an adult who:

- is curious about AI
- has little or no professional programming experience
- may not know basic IT terminology
- can learn independently with AI assistance
- is willing to build things
- does not necessarily have strong English skills

The learner should never be treated as a child.

## 3. Core learning model

The program combines four activities:

### BUILD

Create useful or interesting software.

### UNDERSTAND

Learn enough of the underlying technology to understand what was built and diagnose problems.

### READ

Develop a habit of reading AI news, model announcements, documentation, and technical material.

### WORK WITH AI

Learn to use AI as an active software-development collaborator.

These four activities should reinforce each other.

## 4. Learning philosophy

The curriculum should start from practical outcomes.

The learner should not spend weeks preparing to build something.

Instead:

1. build something interesting
2. encounter a problem
3. learn the concept needed to solve it
4. use the concept
5. understand it better because it now has a purpose

## 5. Role of AI

AI is expected to perform substantial implementation work.

The learner should use AI to:

- write code
- modify code
- debug
- explain
- research
- generate tests
- inspect documentation
- explore alternatives

The learner is responsible for:

- defining goals
- providing context
- directing the AI
- evaluating results
- verifying behavior
- understanding important decisions
- diagnosing failures

This is deliberately different from a traditional "learn to code by typing everything yourself" curriculum.

## 6. Technical foundation

The curriculum should introduce fundamentals when required by a practical task.

Likely progression of concepts includes:

- computer and operating system basics
- files and directories
- processes
- terminal
- Windows and Linux
- networking basics
- localhost
- ports
- HTTP
- APIs
- JSON
- databases
- SQL
- programming
- Git
- GitHub
- deployment

The exact order is not fixed.

## 7. AI foundation

The learner should eventually understand a technically sound model of modern LLM systems.

Topics include:

- models
- tokens
- tokenization
- next-token prediction
- context
- inference
- sampling
- embeddings
- RAG
- tool calling
- agents
- MCP
- local models
- parameters
- quantization
- GPU / VRAM
- evaluation

The learner should understand why LLMs can appear intelligent without being human-like minds.

## 8. AI ecosystem awareness

Following the rapidly changing AI ecosystem is part of the curriculum.

The learner should develop a habit of checking:

- new models
- new model capabilities
- coding agents
- AI development tools
- APIs
- open-source releases
- important technical developments

Reading should focus on understanding significance rather than consuming every announcement.

## 9. English

The project is bilingual.

Czech is used to maximize understanding.

English is used for:
- code
- identifiers
- technical names
- documentation
- GitHub material
- AI news
- technical reading

The learner is not required to become an English speaker or writer.

Technical reading ability is the goal.

## 10. Learner AI persona

The learner should choose an AI platform/model first.

After choosing, the learner receives a platform-appropriate version of the canonical persona.

The persona should tell the learner's AI how to work with the curriculum.

The learner should not need to understand the underlying repository structure or synchronization mechanism.

The canonical persona is maintained in the repository.

Platform-specific variants may be generated for:
- ChatGPT
- Claude
- Codex / AGENTS.md
- other suitable tools

## 11. Persona synchronization concept

The intended experience is:

1. learner chooses an AI
2. learner gives the AI the AI Engineering Path repository URL
3. AI loads the current persona from `persona/PERSONA.md`
4. AI uses those instructions during the learner's work
5. AI checks for updated instructions when appropriate

The repository remains the source of truth.

The exact technical mechanism depends on the selected AI platform and must not be assumed until verified.

## 12. Daily structure

A day should normally contain:

- a clear goal
- something to build
- concepts needed for that task
- a short reading/research component
- a concrete end state

Not every day needs equal amounts of all four tracks.

The learner should finish a day knowing what they created and what they learned.

## 13. Explanation standard

For new concepts:

1. concrete example or situation
2. intuitive mental model
3. terminology
4. precise technical detail when useful

Never define a new concept using unexplained concepts.

Explanations should be layered: start with enough information to build a correct mental model, then deepen it when the learner needs it.

## 14. Project quality

Projects should:

- produce a visible result
- solve a real or interesting problem
- use AI meaningfully
- become more sophisticated as the learner progresses
- create reasons to learn new technical concepts

Avoid:
- calculators
- generic todo apps
- pointless CRUD exercises
- copy-paste tutorials
- projects whose only purpose is demonstrating syntax

Toy examples are acceptable only when they are used briefly to explain a real concept.

## 15. Evaluation after 21 days

The main evaluation is not a test score.

Look for signs such as:

- curiosity outside assigned tasks
- willingness to debug
- interest in how systems work
- desire to build personal projects
- interest in new AI developments
- ability to explain what was built
- ability to identify when AI output is wrong

The outcome is a decision:

- continue deeper into AI engineering
- explore a neighboring technical direction
- stop and pursue something else

## 16. Open questions

These should be resolved as the project develops:

- final project name
- exact public positioning
- final 21-day sequence
- recommended AI platforms
- exact persona format for each platform
- how the learner AI checks repository updates
- whether learner progress is stored and how
- exact daily time commitment
- recommended news sources
- recommended first project(s)
- what should be in the public repository vs learner-specific material
