# Advanced Case Management

Advanced Case Management is the Case Management / Case Analysis application in this repository.

## Names you may encounter

- **Advanced Case Management** - canonical repository/customer-facing name and ServiceNow application name
- **ACM** - common shorthand and technical prefix
- **Case Analysis** - terminology visible inside the application

## Technical identity

| Item | Value |
| --- | --- |
| ServiceNow application | `Advanced Case Management` |
| Application scope | `x_ket_acm` |
| Version in packaged 2024-07-12 export | `1.0.2` |
| Primary ServiceNow record family | Customer Service Case (`CS...`) |

## Quick download

[**Advanced Case Management v1.0.2 release**](https://github.com/MajorIncident/KT-ServiceNow/releases/tag/case-v1.0.2) includes the ServiceNow application package and installation guide.

## Start here

1. Review [`docs/current/`](docs/current/) for installation, design, test, and overview material.
2. The ServiceNow application package is under [`package/`](package/).
3. Case and `x_ket_acm` reference data exports are under [`data-backups/`](data-backups/).
4. Generic ServiceNow certification templates are consolidated under [`../shared/templates/`](../shared/templates/) instead of being duplicated inside product folders.

## Folder guide

```text
advanced-case-management/
├── README.md
├── package/
├── docs/current/
├── data-backups/
└── archive/
```
