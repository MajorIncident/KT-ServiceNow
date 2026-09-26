# Kepner-Tregoe ServiceNow Apps

This repository contains the Kepner-Tregoe (KT) applications, installation packages, supporting documentation, and reference data for ServiceNow.

## Choose the application you need

| Application | What it supports | You may also know it as | Start here |
| --- | --- | --- | --- |
| **Advanced Incident Management** | Structured incident analysis and major-incident/service-restoration work | **KT Analysis**, K-T Incident Analysis, IM Plugin, Incident Management Plugin | [`advanced-incident-management/`](advanced-incident-management/) |
| **Advanced Problem Management (RCA)** | Root cause analysis and prevention of recurring problems | **APM**, KT Problem V2, Problem Management App, RCA | [`advanced-problem-management/`](advanced-problem-management/) |
| **Advanced Case Management** | Structured analysis in case/customer-service workflows | **ACM**, Case Analysis | [`advanced-case-management/`](advanced-case-management/) |

If someone sent you here looking for the **KT Incident Management plugin**, choose **Advanced Incident Management**.

## Repository map

```text
KT-ServiceNow/
├── advanced-incident-management/   # Incident Management / KT Analysis
├── advanced-problem-management/    # Problem Management / RCA
├── advanced-case-management/       # Case Management
├── shared/                         # Shared ServiceNow instructions and templates
├── docs/                           # Repository-level guidance
├── CONTRIBUTING.md
└── LICENSE_KT.txt
```

Each product area follows the same pattern:

- `README.md` - what the product is, aliases, technical identity, and where to start
- `package/` - ServiceNow scoped-application/update-set backup
- `docs/current/` - the documentation a visitor should use first
- `data-backups/` - application/reference data exports
- `archive/` - historical, superseded, development, or certification-reference material

## Current technical identities

| Product | ServiceNow application / scope | Version visible in repository package |
| --- | --- | --- |
| Advanced Incident Management | `KT Analysis` / `x_ket_kt_analysis` | `1.3.2` |
| Advanced Problem Management (RCA) | `x_ket_apm` | See packaged export / current installation documentation |
| Advanced Case Management | `Advanced Case Management` / `x_ket_acm` | `1.0.2` |

The names above deliberately preserve both the customer-facing product names and the legacy/internal ServiceNow identifiers so that older references remain searchable.

## Installing or evaluating an app

Start in the product folder rather than browsing raw XML files at the repository root. Each product README points to its current installation material and package.

Shared ServiceNow import/reference instructions are under [`shared/installation/`](shared/installation/).

## Historical files

Older installation guides, design iterations, test-plan versions, blog/source material, and development notes are retained under each product's `archive/` area. They are kept for traceability and reference but should not be assumed to be the current installation path.

## License and usage

Use of this source code is governed by [`LICENSE_KT.txt`](LICENSE_KT.txt). The repository being accessible on GitHub does **not** change the license terms or grant redistribution, sublicensing, or other rights beyond those terms.

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for how to share fixes, enhancements, documentation, and other improvements back with KT.

## Support

For questions about the applications or repository, contact your KT representative or Shane Chagpar at `schagpar@kepner-tregoe.com`.
