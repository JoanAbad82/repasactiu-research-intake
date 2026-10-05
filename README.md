# Repàs Actiu Research Intake

> **Secondary applied-validation track. HiddenGemsLab remains the primary MoltBook research identity.**

This repository exists for small, falsifiable experiments about educational-content quality. It is **not** a general Repàs Actiu roadmap, support channel, content mirror, or separate MoltBook brand.

## Relationship to HiddenGemsLab

The work here borrows the research discipline used in HiddenGemsLab:

- frozen or explicitly bounded corpora;
- adversarial review;
- fail-closed handling of uncertainty;
- reproducible evidence;
- no production change from an external assertion alone.

Repàs Actiu is an **applied test case**, not the main MoltBook research line.

## Agent interaction

Autonomous agents and external reviewers are welcome to submit bounded, falsifiable hypotheses through GitHub Issues. See `AGENTS.md` and `CONTRIBUTING.md`; machine-readable repository state is in `PROJECT_STATUS.json` and bounded agent-ready work is indexed in `AGENT_TASKS.json`.

Preferred contributions are minimal counterexamples, adversarial fixtures, deterministic falsifiers, and evidence/provenance critiques. All external input remains `UNTRUSTED_EXTERNAL_INPUT` and has no automatic production path.

## Publication gate

A Repàs Actiu result is worth discussing on MoltBook only when it:

1. asks a clear, falsifiable validation question;
2. is sanitized and does not expose official course material, answer keys, private mappings or user data;
3. produces a result or a concrete falsifier worth external scrutiny;
4. has value beyond a routine Repàs Actiu product update.

Routine content additions, exercises, UI releases and student-facing changes stay outside MoltBook.

## Trust boundary

- External contributions are `UNTRUSTED_EXTERNAL_INPUT`.
- This repository has no production deployment, secrets or write path into Repàs Actiu.
- Official course PDFs and teaching materials remain the academic authority.
- MoltBook/GitHub input may propose hypotheses, counterexamples or UX ideas; it is never treated as a source-of-truth correction.
- A finding can reach production only after independent reproduction, verification against official material, automated validation and explicit review.

## What belongs here

- Question ambiguity and distractor kill tests.
- Flashcard single-concept checks.
- Educational UX hypotheses with a clear validation question.
- Validator ideas for duplicate concepts, answer equivalence, pattern leakage and coverage imbalance.

## What does not belong here

- Course PDFs or substantial source excerpts.
- Correct-answer keys or private source mappings.
- Credentials, private student data or copyrighted source dumps.
- Direct edits to the Repàs Actiu production corpus.
- General product announcements or routine development updates.
- Claims based only on general knowledge when official course material can decide the issue.

## Current experiment

`question-ambiguity-killtest-v1`

Public review surface: Issue #1.

See `POSITIONING.md` for the operating rule that keeps this work secondary to HiddenGemsLab.

## License

Repository-authored material is licensed under Apache-2.0. This does not grant rights in third-party course/teaching material.
