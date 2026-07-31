# AI Retrieval and Project Manifest Standard

**Standard Version:** 1.0  
**Status:** Approved Foundation  
**Applies To:** Bezalel, EXODUS, and future approved AI systems

## Purpose

This standard allows approved AI systems to locate authoritative information consistently without assuming that every engineering repository has the same internal technical needs.

## Core Retrieval Order

When answering a project question, an approved AI system should use this order:

1. Identify the project through the AlTone Engineering Project Registry.
2. Identify the authoritative repository.
3. Read `project-manifest.yaml` when available.
4. Use the manifest to locate the correct information role.
5. Consult the current-state document for project-status questions.
6. Consult the approved name-and-purpose document for questions about a project's name, biblical foundation, meaning, motto, or symbolism.
7. Consult architecture and subsystem documentation for technical questions.
8. Consult tests for verified capability claims.
9. Consult design decisions for the reasons behind choices.
10. Consult the engineering journal for historical sequence and implementation context.
11. Use commit history as supporting evidence when necessary.

## Source Authority

- GitHub is the authoritative engineering record.
- The project repository is authoritative for detailed project facts.
- The Engineering Library Index is authoritative for repository availability and documented structure.
- The Project Registry is authoritative for project identity, classification, purpose, and relationship to the wider ecosystem.
- Newer approved project documentation supersedes older summaries when they conflict.

## Retrieval Rules

An approved AI system must:

- Identify the repository searched.
- Identify the exact document path used when possible.
- Distinguish current, verified, planned, proposed, and superseded information.
- Distinguish measurements from estimates.
- Preserve approved names, spellings, scriptural references, meanings, and stated symbolic boundaries.
- Avoid inventing files, paths, repositories, specifications, or capabilities.
- State clearly when required information is missing or stale.
- Avoid treating a placeholder file as proof of implementation.
- Prefer the strongest authoritative source for focused factual questions.

## Project Manifest Requirement

Each active repository should contain a root-level `project-manifest.yaml`.

The manifest declares:

- Project name
- Approved name-and-purpose document
- Repository family
- Standards version
- Project status
- Authoritative document paths
- Information-role mappings
- Privacy classification
- Migration state

## Compatibility During Migration

When paths change:

1. Add the new path to the manifest.
2. Preserve the old path in a migration map.
3. Update the Engineering Library Index and Project Registry.
4. Update Bezalel or EXODUS path mappings before deleting the old path.
5. Re-index the repository when required.
6. Run retrieval-validation questions.
7. Remove compatibility references only after successful validation.

## Minimum Retrieval Validation

A migrated project should be tested with questions covering:

- Project identity and purpose
- Current status
- Major hardware or software configuration
- One documented design decision
- One verified test result
- One known limitation or pending task
- Location of the latest authoritative current-state document

## Repository Families

The manifest must use one approved family identifier:

- `ai-computing-system`
- `physical-platform`

Future family identifiers must be approved and documented in the AlTone Engineering Standards repository before use.
