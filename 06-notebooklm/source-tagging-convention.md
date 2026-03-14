# Source Tagging Convention

> How to label sources when uploading to NotebookLM so they are easy to filter and cite.

## Tag format

`[TYPE]-[SEGMENT]-[DATE]-[ID]`

### Examples

- `INTERVIEW-SMB-2025Q1-001` — customer interview, SMB segment, Q1 2025, first of its kind
- `SURVEY-ENT-2025Q2-003` — enterprise survey, Q2 2025, third response
- `SUPPORT-ALL-2025Q3-012` — support ticket batch, all segments, Q3 2025
- `ARTICLE-NA-20250310` — external article (no segment), dated March 10 2025

## Type codes

| Code | Type |
|---|---|
| INTERVIEW | Customer interview |
| SURVEY | Survey response or batch |
| SUPPORT | Support ticket or escalation |
| NPS | NPS verbatim |
| ARTICLE | External article or report |
| INTERNAL | Internal doc (non-confidential) |
| ANALYSIS | Your own analysis document |

## Segment codes

| Code | Segment |
|---|---|
| SMB | Small / medium business |
| ENT | Enterprise |
| MID | Mid-market |
| PLG | Product-led growth / self-serve |
| ALL | All segments / not segmented |
| NA | Not applicable |

## Notes

- Use consistent tags from the start — retroactive retagging is painful
- Include the tag in the source title when uploading
