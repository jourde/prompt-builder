Use only the consolidated evidence below as the basis for your decisions.
Do not return to the raw initial list.
Do not invent new categories.
Do not add any field or option that cannot be traced back to the consolidated list.

Your task is to convert the consolidated evidence into a FINAL INTERFACE FIELD SCHEMA for a prompt-building tool used by educational support coordinators in European Schools.

Use these four headings only:
# PERSONA / ROLE
# OBJECTIVE
# AUDIENCE
# BOUNDARIES & STYLE

Important distinction:
- FIELD = one interface control
- OPTION = one selectable item inside a field

A merged theme is not automatically a field.
Create one field only when it represents one real user choice.
If several consolidated items belong to the same user decision, group them as options inside one field.

Use only these input types:
- FREE TEXT
- DROP-DOWN
- TICK BOXES

Decision rules:
- DROP-DOWN = one option usually selected; stable list
- TICK BOXES = multiple options may apply at once
- FREE TEXT = too varied, too detailed, or too open-ended for a useful fixed list
- Add “Other (specify)” only when a field is mostly structured but contains a few genuine outliers
- Prefer a small number of reusable fields over many niche fields
- Create a maximum of 10 fields in total, unless the data makes fewer impossible
- Do not create a structured field with fewer than 2 grounded options
- If a possible field has only 1 grounded option, either absorb it into a broader field or make it FREE TEXT
- Sort options by frequency, most frequent first
- Keep the interface practical and implementation-ready

Required output:

# FINAL FIELD SCHEMA

Create one table for the whole interface with these columns:

| Global order | Heading | Field label | Input type | Single-select or multi-select | Exact options/items | Include “Other (specify)” | Required or optional | Reason |

Rules:
- For DROP-DOWN, write “single-select”
- For TICK BOXES, write “multi-select”
- For FREE TEXT, write “—” for selection mode and options
- In “Exact options/items”, list the exact labels in display order
- Mark one-off options with [unique]
- Mark unclear options with [to clarify]
- Make final decisions; do not describe alternatives

After the table, add:

# FIELD-BY-FIELD NOTES

For each field, provide:
- Purpose
- Why this control type
- Why the field is structured or open
- Whether “Other (specify)” is necessary
- Any item that still needs user validation before implementation

Then add:

# FULL INTERFACE ORDER
Provide one numbered list showing the final interface from top to bottom.

Then add:

# EXCLUDED ITEMS
List any consolidated items not included in the schema and explain exactly why they were excluded, merged into another field, or left to FREE TEXT.

Consolidated evidence:
[PASTE THE OUTPUT OF PROMPT 1 HERE]
