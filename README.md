# P1▶Y

**An open-source, privacy-first protocol and portable engine for user-owned AI context.**

P1AY keeps your identity, history, decisions, projects, state, and AI memory as readable files in a folder you control—not inside a vendor’s black box.

Compatible AI clients can load the same context. Provenance, explicit confirmation, and a controlled write path help prevent AI inference from silently becoming personal fact.

## What it does

P1AY connects:

`CONTEXT → STATE → ACTION → REALITY → FEEDBACK`

It helps AI:

- restore relevant context instead of starting from zero;
- separate facts, experience, interpretation, and hypotheses;
- connect patterns across time, projects, and conversations;
- turn ideas and questions into clear actions;
- verify real outcomes instead of treating generated text as completion;
- update the next action from feedback.

## Core foundations

- **User-owned data.** Plain JSON files in storage controlled by the user.
- **Privacy by default.** Minimum necessary context is loaded and shared.
- **Portable context.** The same system can work with ChatGPT, Claude, Codex, local models, and other compatible AI clients.
- **Provenance.** User statements, AI proposals, external evidence, and unresolved claims remain distinguishable.
- **Reality-tested action.** Plans are checked against state, constraints, actions, and observable results.
- **Continuity.** Corrections update the current context without deleting history.

## Architecture

P1AY separates context into:

- `CORE` — shared rules and operating principles;
- language layer — local wording without changing meaning;
- `USER` — personal context and confirmed state;
- `COMMUNICATION` — terminology and collaboration style;
- `CONTEXT` — sources, history, and extended evidence;
- project contours — isolated context for individual projects.

One designated writer updates canonical masters. Other AI clients read them and submit proposed changes through `TEMP`.

A pointer records active files, revisions, sizes, and SHA-256 hashes.

## Beyond memory

P1AY is not only a memory layer.

It can connect personal context with:

- active Paths across `WORLD`, `BUSINESS`, `ART`, and `STATE`;
- Pulse and basic state awareness;
- Life Hours as a value metric;
- factual dashboards;
- optional State Navigator and Digital Twin contours.

## Security boundaries

P1AY improves transparency, traceability, portability, and recovery. It does not replace storage permissions, encryption, operating-system security, or cryptographic access control.

## Install

1. Download the release archive.
2. Attach it to a compatible AI.
3. Write: **Install P1AY**  
   Russian: **«Установи P1AY»**

Or run:

```bash
python3 P1AY_FIRST_RUN.py --dry-run
python3 P1AY_FIRST_RUN.py
python3 P1AY_FIRST_RUN.py --sync-status
```

## Release

**VALENTINA 1.0**

Includes the installer, CORE, language layer, USER / COMMUNICATION / CONTEXT templates, onboarding, dashboard builder, and SHA-256 release manifest.

## License

MIT
