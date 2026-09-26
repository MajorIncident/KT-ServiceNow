# Advanced Problem Management (RCA)

Advanced Problem Management (RCA) is the Problem Management / Root Cause Analysis application in this repository.

## Names you may encounter

- **Advanced Problem Management (RCA)** - canonical repository/customer-facing name
- **Advanced Problem Management** - common full name
- **APM** - common shorthand and technical prefix
- **KT Problem V2** - historical repository/development name
- **Problem Management App** / **RCA** - common descriptions

## Technical identity

| Item | Value |
| --- | --- |
| Application scope | `x_ket_apm` |
| Primary ServiceNow record family | Problem (`PRB...`) |
| Analysis record prefix visible in data | `KTAPM...` |

## Start here

1. Use [`docs/current/`](docs/current/) for the current-facing installation guide and principal design/test/reference files.
2. The scoped-application/update-set backup is under [`package/`](package/).
3. Problem and `x_ket_apm` reference data exports are under [`data-backups/`](data-backups/).
4. Older installation guides, design/test iterations, blog/source material, and development notes are retained under [`archive/`](archive/).

## Folder guide

```text
advanced-problem-management/
├── README.md
├── package/
├── docs/current/
├── data-backups/
└── archive/
    ├── installation-guides/
    ├── design-history/
    ├── test-plan-history/
    ├── blog-series/
    └── development-reference/
```

## Which installation guide should I use?

The root-level 2025-contributed APM installation guide has been promoted into `docs/current/` so visitors no longer need to choose among several similarly named historical files. Older versions remain in `archive/installation-guides/`.
