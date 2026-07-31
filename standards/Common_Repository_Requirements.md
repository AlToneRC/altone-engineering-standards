# Common Repository Requirements

**Standard Version:** 1.0  
**Status:** Approved Foundation  
**Applies To:** All AlTone engineering repositories

## Purpose

This standard defines the requirements shared by every approved AlTone engineering repository, regardless of repository family.

## Authority

- Alton Hampton retains final engineering and organizational authority.
- GitHub is the authoritative engineering record.
- AI systems may retrieve, explain, recommend, review, organize, and draft.
- Permanent repository changes, destructive actions, and engineering decisions require Alton's approval.

## Required Root Documents

Every active engineering repository should contain:

- `README.md`
- `NAME_AND_BIBLICAL_FOUNDATION.md` or an approved equivalent in the repository foundation
- `PROJECT_VISION.md` or an approved equivalent in the repository foundation
- `ROADMAP.md` or an approved roadmap location
- `TODO.md` or an approved current-action location
- `CHANGELOG.md`
- `project-manifest.yaml`

A repository may use a documented equivalent when its approved family standard places the information elsewhere.

## Required Information Roles

Every repository must provide clear authoritative locations for:

1. Project identity and purpose
2. Official name, origin, meaning, and relationship to the mission
3. Current state
4. System architecture
5. Hardware or platform engineering, when applicable
6. Software and configuration, when applicable
7. Testing and verification
8. Operations or deployment procedures
9. Engineering journal records
10. Design decisions
11. Lessons learned
12. Reference material
13. Security and private-asset handling, when applicable

## Documentation Rules

- Describe what is currently documented and verified.
- Label unimplemented capabilities as planned, proposed, or under development.
- Distinguish measured facts from estimates.
- Date status reports, tests, journal entries, and time-sensitive decisions.
- Preserve superseded records when they provide engineering history.
- Identify the newer authoritative document when a prior record has been superseded.
- Avoid duplicating the same authoritative fact in multiple locations without identifying the source of truth.

## Naming Rules

- Use descriptive names.
- Use consistent capitalization within each repository.
- Preserve the approved official spelling of the project or platform name.
- Document the name's biblical, linguistic, historical, or organizational foundation without inventing unsupported claims.
- Explain how the approved meaning relates to the project's actual mission.
- Include a concise canonical answer that Bezalel, EXODUS, and future approved systems may use.
- State clearly when a project name is symbolic and does not claim a spiritual identity, divine authority, or verified operational capability.
- Use ISO dates in dated filenames: `YYYY-MM-DD`.
- Do not create multiple folders serving the same information role.
- Do not create a new abbreviation without defining it.

Detailed naming requirements are defined in `standards/Platform_Naming_and_Purpose_Standard.md`.

## Change Management

Before moving or renaming authoritative documentation:

1. Record the reason for the change.
2. Create a migration map.
3. Update the project manifest.
4. Update the Engineering Library Index and Project Registry when applicable.
5. Update retrieval rules or path mappings before removing old paths.
6. Verify that known questions still retrieve correct documents.
7. Record the completed migration in the changelog or engineering journal.

## Repository Family Selection

Each repository must declare one approved family in `project-manifest.yaml`:

- `ai-computing-system`
- `physical-platform`

A future family may be added only after its standard is documented and approved in this repository.

## Empty Folders and Placeholders

- Empty folders should not be created unless needed for a near-term approved purpose.
- Empty placeholder documents must be clearly labeled as placeholders.
- The existence of a placeholder does not establish an operational capability.

## Privacy and Publication

Repositories must identify information that should remain private, including:

- Credentials and tokens
- Private model files
- Personal data
- Restricted vendor materials
- Proprietary customer information
- Sensitive mission or location information

Public repositories must exclude private assets while documenting their existence and handling policy when necessary.
