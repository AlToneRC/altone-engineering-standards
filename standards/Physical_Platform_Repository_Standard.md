# Physical Platform Repository Standard

**Standard Version:** 1.0  
**Family Identifier:** `physical-platform`  
**Status:** Approved Foundation

## Purpose

This family is used for autonomous vehicles, boats, aircraft, rovers, mobile platforms, robots, and other hardware-centered engineering systems.

Current and planned examples include Praxis Aqua 1, Ark Faithful Rover, Cherub Wings, and Witness.

## Standard Structure

```text
00_Foundation/
01_System_Architecture/
02_Mechanical/
03_Electrical/
04_Computing_and_Control/
05_Software/
06_Testing/
07_Operations/
08_Engineering_Journal/
09_Decisions_and_Lessons/
10_Reference/
11_Standards/
12_Configuration/
Assets/
README.md
CHANGELOG.md
project-manifest.yaml
```

## Folder Roles

### `00_Foundation`

Project identity, official name and meaning, mission, vision, requirements, design targets, roadmap, current priorities, ownership, and project boundaries.

The repository's approved name-and-purpose record should be stored here or mapped here through `project-manifest.yaml`.

### `01_System_Architecture`

Whole-system architecture, subsystem relationships, interfaces, operating concept, data flow, mission architecture, and authoritative current-state documentation.

### `02_Mechanical`

Hull, chassis, frame, structure, materials, fabrication, assembly, CAD, drawings, 3D prints, mounting systems, enclosures, canopy, and mechanical hardware.

Recommended subfolders may include:

```text
CAD/
3D_Prints/
Materials/
Assembly/
Structures/
Enclosures/
```

Only create subfolders that the project actually needs.

### `03_Electrical`

Power distribution, wiring, protection, batteries, connectors, lighting, schematics, pinouts, electrical interfaces, and electrical safety.

Recommended subfolders may include:

```text
Power/
Wiring/
Lighting/
Connectors/
Schematics/
```

### `04_Computing_and_Control`

Flight controllers, rover controllers, companion computers, receivers, telemetry, radios, GPS, sensors, communications, control architecture, and embedded computing.

### `05_Software`

Firmware, scripts, configuration utilities, mission software, companion-computer software, data-processing tools, dependencies, and source documentation.

### `06_Testing`

Bench tests, subsystem tests, integration tests, waterproofing tests, weight reports, buoyancy tests, field trials, mission validation, performance measurements, failures, and verification records.

### `07_Operations`

Mission procedures, checklists, field setup, maintenance, safety, transport, launch and recovery, operating limits, and mission records.

### `08_Engineering_Journal`

Dated build records, progress summaries, EOC project updates, troubleshooting narratives, milestone records, and approved integration history.

### `09_Decisions_and_Lessons`

Formal design decisions, trade studies, accepted risks, lessons learned, and knowledge intended to inform future platforms.

Recommended subfolders:

```text
Design_Decisions/
Lessons_Learned/
```

### `10_Reference`

Datasheets, external research notes, approved vendor documentation references, regulations, standards references, and supporting technical material.

### `11_Standards`

Project-specific standards and references to shared organizational standards. Shared standards should not be copied unnecessarily.

### `12_Configuration`

Authoritative configuration records, parameter sets, calibration data, firmware versions, mission-controller settings, receiver mappings, and verified deployment configurations.

### `Assets`

Images, diagrams, photographs, branding assets, and supporting media.

## Current-State Requirement

Every physical platform repository must provide one clearly identified current-state document containing at least:

- Current project phase
- Completed subsystems
- Installed components
- Planned components
- Known measurements
- Weight or mass status when applicable
- Current risks and blockers
- Next milestones
- Last update date

The path must be declared in `project-manifest.yaml`.

## Name-and-Purpose Requirement

Every physical-platform repository must provide one approved document explaining:

- Official platform name and spelling
- Biblical, linguistic, historical, or organizational foundation
- Primary references
- Defined meaning
- Relationship between the name and the platform mission
- Guiding principles
- Boundaries on what the symbolic name does not claim
- A concise canonical answer for approved AI retrieval

The approved template is `templates/Platform_Name_and_Biblical_Foundation.md`.

## Design-Decision Requirement

Major decisions must be recorded separately from daily build notes. Each decision should identify:

- Decision
- Date
- Reason
- Alternatives considered
- Tradeoffs
- Current status
- Related files or tests

## Testing Requirement

A planned capability must not be described as operational until an appropriate test or verification record exists.

## Compatibility and Migration

Praxis Aqua 1 is the first physical-platform repository to be aligned with this standard.

Migration must be controlled. Existing documents should be mapped into the new structure only after:

1. The current repository is reviewed.
2. Authoritative paths are identified.
3. A migration map is approved.
4. Bezalel's Engineering Library Index and Project Registry are updated.
5. Retrieval tests confirm continuity.

Do not reorganize Ark Faithful Rover, Cherub Wings, Witness, or future platforms independently. They should begin from this approved family standard.
