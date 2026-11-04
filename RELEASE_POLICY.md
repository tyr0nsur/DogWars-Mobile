# Releases

The initial releases of this repository are **documentation milestones**. They distribute the public record, not a game, engine, installer, recovered source or IPA.

## Documentation release procedure

1. Complete a material milestone with actual evidence. Record the validation scope and remaining gaps.
2. Update the milestone note, data/progress.json receipts/checklist and CHANGELOG.md.
3. Regenerate media/progress.svg from the checklist. A denominator change also changes scopeVersion.
4. Run one grouped documentation/public-file check. Review the exact public diff and release attachments.
5. Tag the reviewed commit as `milestone-m0-2026-11-04`, `milestone-m1-YYYY-MM-DD`, or an equivalent unambiguous milestone tag.
6. Publish a release whose title begins **Documentation milestone:** and whose first paragraph says **No playable game, IPA or game content is included.**

Attach only sanitized documentation metadata or original SVG graphics if an attachment is useful. GitHub's source archive contains this documentation repository only. Do not attach lab archives, raw inventories, build logs, recovered assets, SDKs, keys, executables or private source.

## Future software builds

A future playable-build release requires separate decisions about distribution rights, the intended channel, signing, game-content provenance and the exact validation scope. Publishing documentation does not authorize publishing those materials. A package compiling successfully is not sufficient to call it a working complete port.

Use an explicit development/pre-release version, identify the exact implementation/content build, state which platforms and devices were exercised, and list the material missing behavior. A release cannot claim working independent multiplayer without a recorded multi-client session.

No software-build release is available at M0.
