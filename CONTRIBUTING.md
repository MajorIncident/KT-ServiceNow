# Contributing to the Kepner-Tregoe ServiceNow Apps repository

Thank you for working with this Kepner-Tregoe (KT) codebase. Improvements from client and implementation teams help preserve useful fixes, documentation, and implementation knowledge.

## Where does my change belong?

Choose the product area first:

- `advanced-incident-management/` - Advanced Incident Management / KT Analysis / IM Plugin
- `advanced-problem-management/` - Advanced Problem Management (RCA) / APM / KT Problem V2
- `advanced-case-management/` - Advanced Case Management / ACM
- `shared/` - genuinely cross-product ServiceNow material

Put current-facing product documentation under `docs/current/`. Put superseded or historical material under the product's `archive/` directory instead of mixing multiple competing versions in the current path.

See [`docs/NAMING.md`](docs/NAMING.md) for canonical product names and aliases.

## What to share back

Please share back:

- bug fixes or patches
- feature enhancements
- updated installation or setup instructions
- implementation lessons or compatibility notes
- improved documentation
- other changes that make the applications easier to maintain or use

## How to contribute

**Pull request (preferred):** create a branch, make the change in the correct product area, document what changed, and open a pull request.

**Email submission:** if you cannot submit a pull request, send an archive of the changed files to your KT contact or Shane Chagpar at `schagpar@kepner-tregoe.com`.

## Guidelines

- Clearly describe the problem and the change.
- Do not remove or alter license/copyright notices.
- Do not include third-party code unless its license permits the intended use and the dependency is clearly identified.
- Preserve historical material when it is useful for traceability; move superseded material to `archive/` rather than leaving several apparently-current versions side by side.
- Use canonical product names for navigation while preserving technical names/scopes where relevant.

All contributions are reviewed before inclusion in KT-maintained versions of the codebase.
