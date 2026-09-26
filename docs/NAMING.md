# Product naming and aliases

The repository uses one canonical navigation name for each product while retaining legacy/internal names as aliases for searchability.

| Canonical repository name | Legacy/internal aliases | ServiceNow scope |
| --- | --- | --- |
| **Advanced Incident Management** | KT Analysis; K-T Incident Analysis; IM Plugin; Incident Management Plugin | `x_ket_kt_analysis` |
| **Advanced Problem Management (RCA)** | Advanced Problem Management; APM; KT Problem V2; Problem Management App; RCA | `x_ket_apm` |
| **Advanced Case Management** | ACM; Case Analysis | `x_ket_acm` |

## Rule for future files

Use the canonical product name in customer-facing navigation and README content. Preserve technical scope names exactly where they are relevant. Put older product names in an `Also known as` or `Aliases` section instead of using them as competing folder names.

## File naming

Prefer descriptive, stable names for the current copy:

- `installation-guide.docx`
- `design.docx`
- `test-plan.docx`
- `field-reference.xlsx`
- `design-overview.pptx`

Put dated/versioned superseded copies in `archive/` rather than making visitors infer which filename is newest.
