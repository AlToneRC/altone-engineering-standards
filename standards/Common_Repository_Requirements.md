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
- `PROJECT_VISION.md` or an approved equivalent in the repository foundation
- `ROADMAP.md` or an approved roadmap location
- `TODO.md` or an approved current-action location
- `CHANGELOG.md`
- `project-manifest.yaml`

A repository may use a documented equivalent when its approved family standard places the information elsewhere.

## Required Information Roles

Every repository must provide clear authoritative locations for:

1. Project identity and purpose
2. Current state
3. System architecture
4. Hardware or platform engineering, when applicable
5. Software and configuration, when applicable
6. Testing and verification
7. Operations or deployment procedures
8. Engineering journal records
9. Design decisions
10. Lessons learned
11. Reference material
12. Security and private-asset handling, when applicable

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
- Use ISO dates in dated filenames: `YYYY-MM-DD`.
- Do not create multiple folders serving the same information role.
- Do not create a new abbreviation without defining it.

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
