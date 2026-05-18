# OLERA Reason Codes — Demo Legend

## Main buckets

### SAFE

Rows with enough structured information to be considered technically strong candidates for further review.

### REVIEW

Rows with useful information but ambiguity, missing context or possible alternatives.

### HOLD

Rows that should not be forced because the available information is insufficient or unsafe for candidate assignment.

## Reason codes

| Reason code | Meaning |
|---|---|
| STRUCTURED_MATCH | Enough structured information for a technically strong candidate hint. |
| LOCAL_LANGUAGE_VARIANT | Local-language or local-naming variant requiring confirmation. |
| SPECIMEN_CONTEXT_NEEDED | Specimen information is present but requires review. |
| SPECIMEN_OR_TIMING_CONTEXT_NEEDED | Specimen and/or timing may affect candidate selection. |
| CALCULATED_RESULT_CONTEXT | Calculated result requiring method/context review. |
| NAME_AMBIGUOUS | Ambiguous name with multiple possible concepts. |
| DUPLICATE_VARIANT | Possible duplicate or overlapping catalog item. |
| INSUFFICIENT_CONTEXT | Not enough information for defensible candidate hint. |
| PANEL_NOT_ATOMIC_TEST | Panel/group rather than atomic test. |

## Operational note

Reason codes make review work visible. They do not replace expert review.
