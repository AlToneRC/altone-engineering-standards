# AlTone Engineering Standards

**Built With Purpose**

This repository defines the documentation, organization, and development standards used across AlTone engineering projects.

Its purpose is to ensure that engineering knowledge remains:

- Well documented
- Version controlled
- Easy to understand
- Easy to maintain
- Easy to expand
- Accessible to future engineers and approved AI systems

## Guiding Principles

- Documentation is as important as code.
- Design decisions should be recorded.
- Every project should tell its story.
- Consistency is more valuable than unnecessary complexity.
- GitHub is the authoritative engineering record.
- Planned capabilities must not be presented as completed.
- Repository structures should support reliable retrieval by Bezalel, EXODUS, and future approved systems.
- Build with purpose.
- Preserve knowledge for future generations.

## Approved Repository Families

AlTone engineering repositories currently use two approved structural families.

### 1. AI and Computing Systems

Used for software-centered, AI-centered, workstation, infrastructure, and mixed computing systems.

Current examples:

- Project Bezalel
- Project EXODUS

Standard:

- [`standards/AI_Computing_System_Repository_Standard.md`](standards/AI_Computing_System_Repository_Standard.md)

### 2. Physical Platforms

Used for autonomous vehicles, robots, boats, aircraft, rovers, mobile platforms, and other hardware-centered engineering systems.

Current and planned examples:

- Praxis Aqua 1
- Ark Faithful Rover
- Cherub Wings
- Future physical research and mission platforms

Standard:

- [`standards/Physical_Platform_Repository_Standard.md`](standards/Physical_Platform_Repository_Standard.md)

Additional repository families may be created later when a project type cannot be represented clearly by either approved family. New families must be documented here before they are adopted.

## Common Requirements

All repositories must follow the shared requirements defined in:

- [`standards/Common_Repository_Requirements.md`](standards/Common_Repository_Requirements.md)
- [`standards/AI_Retrieval_and_Manifest_Standard.md`](standards/AI_Retrieval_and_Manifest_Standard.md)

A reusable manifest template is available at:

- [`templates/project-manifest.yaml`](templates/project-manifest.yaml)

## Migration Policy

Existing repositories must not be reorganized simply to improve appearance.

Before moving or renaming authoritative documents:

1. Confirm the repository family.
2. Document the intended target structure.
3. Update the project manifest and Engineering Library Index.
4. Preserve a migration map from old paths to new paths.
5. Update Bezalel retrieval references before removing old paths.
6. Test retrieval against known project questions.
7. Record the approved change in GitHub.

## Engineering Ecosystem

This standards repository supports the wider AlTone Engineering Library, including:

- Bezalel Workbench
- EXODUS Engineering Assistant
- Praxis Aqua 1
- Ark Faithful Rover
- Cherub Wings
- Ground stations and field systems
- Future AlTone engineering projects

---

**AlTone LLC**

*Built With Purpose*
