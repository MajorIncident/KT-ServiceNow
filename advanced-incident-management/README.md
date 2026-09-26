# Advanced Incident Management

**Looking for the KT Incident Management plugin? You are in the right place.**

Advanced Incident Management is the Incident Management application in this repository.

## Names you may encounter

This product has accumulated several names across its history. They all point to this product area:

- **Advanced Incident Management** - canonical repository/customer-facing name
- **KT Analysis** - ServiceNow scoped-application name
- **K-T Incident Analysis** - name used in older installation documentation
- **IM Plugin** / **Incident Management Plugin** - common shorthand

## Technical identity

| Item | Value |
| --- | --- |
| ServiceNow application | `KT Analysis` |
| Application scope | `x_ket_kt_analysis` |
| Version in packaged 2024-07-12 export | `1.3.2` |
| Primary ServiceNow record family | Incident (`INC...`) |

## Quick download

[**Advanced Incident Management v1.3.2 release**](https://github.com/MajorIncident/KT-ServiceNow/releases/tag/incident-v1.3.2) includes the ServiceNow application package and installation guide.

## Start here

1. Review [`docs/current/`](docs/current/) for the current-facing installation/test/reference material retained in this repository.
2. The ServiceNow application package is under [`package/`](package/).
3. Application/reference data exports are under [`data-backups/`](data-backups/).
4. Older installation-guide iterations and development material are under [`archive/`](archive/).

## Folder guide

```text
advanced-incident-management/
├── README.md
├── package/          # KT Analysis scoped-application export
├── docs/current/     # Current-facing installation/test/field reference
├── data-backups/     # Incident + x_ket_kt_analysis data exports
└── archive/          # Historical install guides and development references
```

## Historical material

Files in `archive/` are intentionally retained for traceability and development history. If you simply need to install or understand the current app, start with `docs/current/` instead.
