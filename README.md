# P1▶Y

**An open-source, portable protocol for turning personal context into clear actions, observable results, and continuous feedback.**

P1AY gives different AI clients access to the same structured context without locking that context inside one model, chat, application, or vendor.

Instead of starting from zero in every conversation, P1AY connects relevant history, decisions, projects, current state, external reality, actions, and results into one user-owned system.

**Website:** [p1ay.one](https://p1ay.one)

## Why P1AY exists

People already have years of useful context spread across:

- AI conversations
- notes and diaries
- documents and archives
- projects and task systems
- messages and relationships
- decisions and unfinished ideas
- health, energy, and state records
- real-world actions and outcomes

Most AI tools treat each conversation as an isolated request or keep memory inside a closed vendor-controlled system.

That creates several problems:

- useful context is fragmented;
- the same history must be explained repeatedly;
- AI-generated inference can become mixed with user-stated facts;
- decisions lose their original reasoning;
- corrections do not reliably replace outdated assumptions;
- different AI clients build incompatible versions of the same person;
- plans are generated without checking current state, constraints, or results;
- personal data becomes difficult to inspect, transfer, correct, or remove.

P1AY provides a shared protocol for working with this context over time.

## What P1AY does

P1AY helps an AI client:

1. load the relevant context;
2. distinguish facts, experience, interpretation, hypotheses, models, and vision;
3. connect information across time and projects;
4. identify patterns, contradictions, and missing evidence;
5. compare intentions with current state and external reality;
6. turn ideas, questions, and tasks into clear actions;
7. preserve important decisions and their sources;
8. verify observable results instead of treating generated output as completion;
9. use feedback to update the next action.

The core cycle is:

`EXPERIENCE → INSIGHT → MODEL → TEST → ACTION → REALITY → FEEDBACK`

P1AY treats context as a living system rather than a static profile.

## Core principles

### Reality over model

A convincing answer is not the same as a real result.

P1AY separates:

- proposed;
- prepared;
- sent;
- received;
- accepted;
- implemented;
- verified.

Generated text, plans, dashboards, and models remain representations until reality confirms them.

### Evidence over story

P1AY preserves the source and status of information.

A user report, external fact, AI inference, hypothesis, and verified result are not treated as interchangeable.

Unknown information remains unknown instead of being filled with plausible details.

### Context into action

P1AY is not only a memory layer.

It connects historical context with:

- current priorities;
- available resources;
- external constraints;
- personal state;
- active projects;
- possible actions;
- observable outcomes.

The purpose is not to produce more text. The purpose is to make the next real step clearer and test what happens.

### User-owned data

P1AY stores context as readable files in a folder controlled by the user.

The same context can be used by different compatible AI clients without moving the person’s history into a new proprietary memory system each time.

### Portable architecture

P1AY is model-independent and vendor-independent at the protocol level.

Compatible clients can include ChatGPT, Claude, Codex, local models, or future AI systems capable of reading the files and following the protocol.

### Minimum data, maximum signal

P1AY does not require importing everything.

The system should load and expose only the context needed for the current task. Personal data remains private by default and is shared by choice.

## Architecture

A P1AY installation is built from several separate layers.

### `CORE`

Universal rules, operating principles, verification requirements, write procedures, and system architecture.

### Language layer

Language- and culture-specific wording that preserves the meaning of the universal CORE.

### `USER`

The person’s structured context: identity, current situation, priorities, decisions, active directions, state, history, and confirmed corrections.

### `COMMUNICATION`

Communication style, terminology, tone, cultural references, boundaries, and collaboration preferences.

### `CONTEXT`

Sources, conversations, evidence, extended history, decision records, and other material loaded only when relevant.

### Project contours

Each substantial project can have its own folder and CORE.

A project starts with the minimum structure it needs and can grow into the same layered architecture without mixing its data into unrelated projects or personal masters.

## Context loading

P1AY loads context by declared paths rather than selecting files by revision number, hash, or search result.

A pointer identifies:

- active master files;
- loading order;
- current revisions;
- file sizes;
- hashes;
- connected project contours;
- the designated writer.

This allows different clients to resolve the same current context and detect drift between versions.

Context is loaded progressively:

- the kernel is always available;
- personal and communication layers are loaded for the user;
- extended history and project-specific context are opened only when the task requires them.

## Provenance and epistemic status

P1AY separates information by origin and status.

Examples include:

- `OWNER_STATED` — stated directly by the owner;
- `ASSISTANT_PROPOSED` — proposed by an AI;
- `OPEN` — unresolved or awaiting confirmation;
- external evidence;
- interpretation;
- hypothesis;
- historical or superseded information;
- verified result.

An AI proposal does not automatically become a user fact.

When a confirmed correction replaces an earlier statement, the new assertion becomes current while the previous version remains preserved as historical or superseded.

## One writer, many readers

A P1AY installation has one designated master writer.

Other AI clients can:

- read the active masters;
- work with the current context;
- prepare proposals;
- create pending changes in `TEMP`.

They do not directly edit canonical masters.

The designated writer reconciles pending changes with the current authoritative state before merging them.

This reduces conflicting edits across clients and preserves a visible path from proposal to confirmation.

## Safe updates

Canonical updates follow a controlled sequence:

`resolve authority → compare current state → backup → write → read back → verify → update pointer`

Important changes are not considered synchronized merely because an AI generated them or created a local file.

Old versions are preserved rather than silently erased.

## Privacy, ownership, and security

Privacy and security are parts of P1AY, but they are not its entire purpose.

P1AY supports:

- user-controlled storage;
- readable and transferable data;
- separation of private and shared context;
- provenance for important records;
- explicit confirmation of material changes;
- controlled write access at the protocol level;
- revision and hash checks;
- recovery from conflicting or damaged context;
- visibility into what an AI is treating as current.

P1AY is a protocol and workflow layer, not a replacement for operating-system, cloud-storage, identity, or cryptographic security.

Its protection still depends on the permissions and integrity of the underlying storage.

A client with direct access to the storage may modify files outside the intended workflow. Hashes expose drift only while the verification metadata remains trusted.

## State and trajectory

P1AY does not treat a person as a fixed profile.

State changes with context, action, recovery, and feedback.

A simplified model is:

`STATE₀ → CONTEXT → ACTION → STATE₁ → RESULT`

P1AY can account for:

- energy;
- attention;
- emotional condition;
- physical condition;
- available time;
- financial and social constraints;
- recovery needs;
- readiness for action.

A native Pulse layer provides basic state awareness.

More advanced state work can connect to the separate **State Navigator** contour without making it mandatory for every P1AY installation.

## Paths and active directions

P1AY can organise active movement across four independent contours:

- `WORLD`
- `BUSINESS`
- `ART`
- `STATE`

In Russian-facing interfaces these are called **ПУТИ**.

The purpose is to keep a limited set of meaningful active directions visible while preserving other possibilities for later selection.

Paths connect intentions with concrete actions, state, results, and feedback.

## Life Hours

P1AY uses **Life Hours** as a core value metric.

Time is not treated only as calendar availability or productivity.

The system can examine whether a tool, decision, process, or collaboration:

- returns time;
- consumes time;
- improves the quality of lived time;
- creates reusable value;
- reduces repeated work;
- helps a person spend attention on what matters.

## Feedback field

P1AY is not a fixed board or a static database.

It works as a living feedback field:

- context changes interpretation;
- action changes state;
- reality tests the model;
- feedback changes the next action;
- confirmed corrections update the active context;
- history remains available without remaining falsely current.

## Digital Twin

P1AY can connect to a separate **Digital Twin** contour.

The Digital Twin structures a broader model of the person, their relationships, projects, history, patterns, and possible trajectories.

It is a connected system, not a mandatory replacement for the P1AY USER layer.

P1AY remains the protocol that coordinates context, action, verification, and feedback across these connected contours.

## Pulse and dashboard

P1AY can generate factual views such as Pulse and dashboard interfaces.

These views may display:

- current paths;
- active actions;
- state;
- progress;
- results;
- levels;
- achievements;
- Life Hours;
- available next directions.

A dashboard is a generated view, not an authoritative master.

The source data can change the dashboard. The dashboard must never silently change the source data.

## What P1AY is not

P1AY is not:

- a single AI model;
- a closed memory database;
- a replacement for secure storage;
- a claim of permanent AI memory;
- a static personality profile;
- a generated dashboard presented as reality;
- a system that treats every AI inference as fact;
- a requirement to upload all personal data;
- an application that must remain tied to one vendor.

It is an open protocol and portable engine for structured context, action, verification, and continuity across AI clients.

## What’s in this release

### VALENTINA 1.0

- `P1AY_START_HERE.json` — entry instructions for installing or updating P1AY;
- `P1AY_FIRST_RUN.py` — installer for Python 3.8+ with no external dependencies;
- `system/` — CORE, language layer, templates for USER, COMMUNICATION, CONTEXT, onboarding, and dashboard generation;
- `RELEASE_MANIFEST.json` — release file list with SHA-256 hashes.

## Install

1. Download the release archive from this repository.
2. Attach it to a compatible AI client.
3. Write: **Install P1AY**  
   Russian: **«Установи P1AY»**
4. Review the onboarding and choose whether to start from scratch or add existing context.

Importing personal data is optional and requires the user’s consent.

You can also run the installer directly:

```bash
python3 P1AY_FIRST_RUN.py --dry-run
python3 P1AY_FIRST_RUN.py
python3 P1AY_FIRST_RUN.py --sync-status
```

### Commands

- `--dry-run` — show planned changes without installing;
- default command — create a clean installation next to the installer;
- `--sync-status` — compare current masters with the active pointer.

## Status

P1AY is under active development.

Architecture, operating rules, onboarding, context layers, sync procedures, and dashboard components exist. Individual features may have different levels of implementation and verification.

A documented mechanism should not be treated as independently proven security, predictive accuracy, or completed product functionality unless corresponding evidence is published.

## License

MIT
````

Да/Нет?
