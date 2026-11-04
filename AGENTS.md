# Public documentation repository instructions

This repository is the public development record of DogWars Mobile. The private recovery/build workspace is a separate location and is never a publication source by default.

## Authorized work

The user's standing instruction permits maintaining this public project record and announcing actual verified milestones with appropriate documentation releases. Routine updates within that instruction do not need another confirmation. Preserve the user's current instructions when they change the scope. This authorization does not expand to publishing game material, implementation source, credentials or private lab artifacts.

## Public file boundary

Publish only Markdown documentation, sanitized JSON project metadata/schema, original SVG project graphics and repository metadata required for that documentation. Keep game executables, DLLs, packages, maps, models, textures, audio, SDK dumps, recovered code, native source, private paths, keys, signing material, secrets and raw logs out of commits, pull requests, issues and release attachments. Never upload those files as a workaround for a Git restriction. Do not copy private AGENTS instructions or machine inventories here.

Third-party game/source rights are not granted by an open-source tool's license. Do not add a license purporting to cover game content or private implementation code. Public graphics must be original; do not use official game artwork, logos or screenshots as project art without permission.

## Evidence and claims

- Separate plans, source staging, static checks, engine compilation, device installation and runtime behavior.
- Mark a checklist task completed only after its stated outcome has evidence. Add a sanitized receipt to data/progress.json and link a milestone note.
- A tool README, generated class header, an extracted table, a compiling recovery host or a successful package build is not evidence of a complete playable port.
- Never call a build iPhone-tested without an actual physical-device record. Describe the device/build scope and remaining failures.
- Independent server validation needs real controlled-client evidence; an RCON panel is not the game server.
- Use broad integration checkpoints rather than tests after every reversible step, as requested by the user. Required compile/integration/device checks still have to happen before the corresponding claims.
- Keep failed or partial results visible when they affect the conclusion. Do not invent dates, frame rates, coverage or recovered-code percentages.

## Progress model and graphics

The versioned task list in data/progress.json owns every sector denominator. Percentages equal the completed tasks divided by all tasks in that sector, with equal task weight within that sector. This does not measure game completeness or engineering effort. Keep overallGameCompletionPercent null while the original-game denominator is unknown. Never average the bars into a global game percentage.

Every completed task must name an existing receipt. Changing any task list requires a new scopeVersion, a milestone explanation and regenerated media/progress.svg. Keep README, JSON, SVG and the latest milestone consistent. Graphics must state the measurement boundary.

## Milestone publication

At a material verified milestone: update its note, receipts, checklist and changelog; regenerate the SVG; run one grouped documentation check for JSON/schema consistency, links, SVG validity and the public-file boundary; then use the existing publication authorization. Follow RELEASE_POLICY.md. A documentation release must say it contains no playable game or IPA. Retain the exact commit associated with the release. Never attach private reports or raw logs.

## Style

Lead with the result and its evidence. English is primary; keep the short Spanish status current. Write plainly and avoid suggesting an official partnership. Cite primary sources for external technical claims. Current evidence takes priority over old README or release text.
