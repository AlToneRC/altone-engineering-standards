# AI and Computing System Repository Standard

**Standard Version:** 1.0  
**Family Identifier:** `ai-computing-system`  
**Status:** Approved Foundation

## Purpose

This family is used for software-centered, AI-centered, workstation, infrastructure, and mixed computing systems.

Current examples include Project Bezalel and Project EXODUS.

## Standard Structure

```text
00_Foundation/
01_Architecture/
02_Workstation_or_Hardware/
03_Development/
04_Monitoring/
05_Engineering_Journal/
06_Learning/
07_Scripts/
08_Documentation/
09_Roadmap/
10_Standards/
11_Templates/
12_Configuration/
Assets/
README.md
CHANGELOG.md
project-manifest.yaml
```

A repository may use `02_Workstation` or `02_Hardware` depending on the system. The chosen name must be declared in the manifest and remain stable.

## Folder Roles

### `00_Foundation`

Project identity, mission, vision, philosophy, responsibilities, authority, naming, communication style, registry information, and ecosystem relationships.

The repository's approved name-and-purpose record should be stored here or mapped here through `project-manifest.yaml`.

### `01_Architecture`

System design, current state, AI or software architecture, networking, security architecture, memory, boot process, reliability, failover, and major system relationships.

### `02_Workstation_or_Hardware`

Host computer, local hardware, storage, network interfaces, attached devices, embedded controllers, and physical computing components.

### `03_Development`

Development environment, installation, programming tools, models, dependencies, source-control practices, and active implementation documentation.

### `04_Monitoring`

Health monitoring, operational status, recurring reports, performance records, alerts, and system history.

### `05_Engineering_Journal`

Dated progress records, milestone summaries, troubleshooting narratives, and approved implementation history.

### `06_Learning`

Educational explanations, code walkthroughs, training records, and learning materials.

### `07_Scripts`

Runnable scripts and their supporting documentation.

### `08_Documentation`

User guides, operating guides, installation instructions, maintenance documentation, and supporting technical documents not owned by another authoritative folder.

### `09_Roadmap`

Detailed plans, milestones, phased development, and future approved work.

### `10_Standards`

Standards applied within the repository. Shared organizational standards should be referenced from `altone-engineering-standards` rather than unnecessarily duplicated.

### `11_Templates`

Reusable templates specific to the project or repository family.

### `12_Configuration`

Authoritative configuration descriptions, system prompts, verified configuration artifacts, deployment configuration, voice settings, and environment-specific configuration documentation.

### `Assets`

Images, diagrams, approved media, and supporting non-source assets.

## Current-State Requirement

Every AI or computing repository must provide one clearly identified current-state document. Its path must be declared in `project-manifest.yaml`.

## Name-and-Purpose Requirement

Every AI or computing repository must provide one approved document explaining its official name, source references, defined meaning, relationship to the system mission, boundaries, and canonical answer. The path must be declared in `project-manifest.yaml` when the manifest is adopted.

## Retrieval Requirement

Bezalel, EXODUS, and future approved systems should:

1. Read the project manifest.
2. Identify the authoritative information role.
3. Retrieve the current-state or architecture document first when answering status questions.
4. Use journal and commit history as supporting records, not as substitutes for the current authoritative state.
5. Distinguish verified deployment artifacts from plans and placeholders.

## Compatibility

Project Bezalel's current numbered structure is the operational reference for this family. Adoption of this standard must not require unnecessary movement of existing Bezalel files.

EXODUS may retain approved project-specific folders where needed, provided their information roles are declared in its manifest and do not create duplicate authorities.
