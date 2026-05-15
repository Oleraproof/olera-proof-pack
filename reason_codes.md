# OLERA Reason Codes — Demo Legend

This document describes demo reason codes used in the OLERA public Proof Pack.

## Main buckets

### SAFE

Rows with enough structured information to be considered technically strong candidates for further review.

### REVIEW

Rows with useful information but ambiguity, missing context or possible alternatives.

### HOLD

Rows that should not be forced because the available information is insufficient or unsafe for candidate assignment.

---

## Reason codes

| Reason code | Meaning |
|---|---|
| `STRUCTURED_MATCH` | The row contains enough structured information for a technically strong candidate hint. |
| `LOCAL_LANGUAGE_VARIANT` | The row appears to be a local-language or local-naming variant and requires confirmation. |
| `SPECIMEN_CONTEXT_NEEDED` | Specimen information is present but requires additional review. |
| `SPECIMEN_OR_TIMING_CONTEXT_NEEDED` | Specimen and/or timing information may affect candidate selection. |
| `CALCULATED_RESULT_CONTEXT` | The row may represent a calculated result and requires method/context review. |
| `NAME_AMBIGUOUS` | The test name is ambiguous and may refer to multiple possible concepts. |
| `DUPLICATE_VARIANT` | The row may duplicate or partially overlap another catalog item. |
| `INSUFFICIENT_CONTEXT` | The row does not contain enough information for a defensible candidate hint. |
| `PANEL_NOT_ATOMIC_TEST` | The row appears to represent a panel or group rather than a single atomic test. |

---

## Operational note

Reason codes are designed to make review work visible.

They do not replace expert review.

They help separate what is technically strong, what requires review and what should not be forced.
