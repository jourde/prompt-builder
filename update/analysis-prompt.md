I am going to give you a list of prompts collected from a group of educational support coordinators in European Schools. They were asked to describe their professional needs in order to adapt a prompt-building tool to their work.

══════════════════════════════════
YOUR TASK
══════════════════════════════════

Analyse all responses and turn them into an IMPLEMENTATION-READY INTERFACE SPECIFICATION for a prompt-building tool.

Your goal is NOT only to consolidate themes.
Your goal is to tell me exactly:

- which interface fields should exist
- under which of the four headings each field belongs
- whether each field should be FREE TEXT, DROP-DOWN, or TICK BOXES
- the exact items/options to include in each non-free-text field
- the order in which the fields should appear in the interface

Use these four headings as the top-level structure:

# PERSONA / ROLE
# OBJECTIVE
# AUDIENCE
# BOUNDARIES & STYLE

══════════════════════════════════
CORE PRINCIPLE
══════════════════════════════════

You must distinguish clearly between:

- FIELD = one interface control the user interacts with
- OPTION = one selectable item inside that field

Important:
A merged theme is NOT automatically a separate field.
If several responses belong to the same user decision, group them into ONE field with multiple options.

Example:
Do NOT output:
- Primary teacher → drop-down
- TA → drop-down
- SEN specialist → drop-down

Instead output:
Field label: Role
Input type: DROP-DOWN
Options:
- Primary / classroom teacher
- Early years practitioner
- SEN / inclusion specialist
- TA / support staff
- etc.

══════════════════════════════════
ANALYSIS PROCESS
══════════════════════════════════

For each of the four headings, follow this process:

STEP 1 — MERGE
Identify responses that express the same idea, even if worded differently.
Merge them into one clear, neutral professional label.

STEP 2 — DECIDE THE FIELD STRUCTURE
Decide whether the merged ideas under that heading should become:
- one single interface field
- or several separate fields

Create separate fields only when the user should reasonably answer them independently.

Examples:
- Under AUDIENCE, “age/phase” and “support needs” should usually be separate fields.
- Under BOUNDARIES & STYLE, “tone”, “output format”, and “constraints” should usually be separate fields.

STEP 3 — SPECIFY THE UI CONTROL
For each field, choose exactly one:
- FREE TEXT
- DROP-DOWN
- TICK BOXES

Use these rules:
- Use DROP-DOWN when one option is usually selected and the set is reasonably stable.
- Use TICK BOXES when multiple options may apply at the same time.
- Use FREE TEXT when the responses are too varied, too detailed, or too open-ended for a fixed list.
- If a field is mostly structured but contains a few rare one-off cases, keep the structured field and add:
  - Other (specify)

STEP 4 — DEFINE THE EXACT OPTIONS
For every DROP-DOWN or TICK BOXES field:
- provide the exact option list
- sort options by frequency, most frequent first
- mark options that appeared only once with [unique]
- mark options that are semantically unclear with [to clarify]

STEP 5 — TRACEABILITY
Every option or free-text field must trace back to at least one spreadsheet response.
Do not invent categories that are not grounded in the data.

══════════════════════════════════
OUTPUT FORMAT
══════════════════════════════════

For each heading, produce BOTH outputs below.

A) INTERFACE BLUEPRINT

Create a table with these columns:

| Order | Field label | Input type | Single-select or multi-select | Exact options/items | Include “Other (specify)” | Reason |

Rules:
- “Order” means the position of the field within that heading.
- For FREE TEXT fields, write “—” in the “Exact options/items” column.
- For DROP-DOWN, use “single-select”.
- For TICK BOXES, use “multi-select”.
- In the “Reason” column, explain briefly why this control type is the best fit.

B) CONSOLIDATED EVIDENCE LIST

After the table, provide a numbered list of the merged items that informed the interface design.
Format:
1. Item label (×frequency)
2. Item label (×frequency) [unique]
3. Item label (×frequency) [to clarify]

Important:
This evidence list is for traceability.
It does NOT need to mirror the exact interface structure one-to-one.

══════════════════════════════════
GLOBAL OUTPUT AFTER ALL FOUR HEADINGS
══════════════════════════════════

After the four headings, add two final sections:

# PROPOSED FULL INTERFACE ORDER

Give one single ordered list showing the complete interface from top to bottom across all headings.
Example format:
1. Role — DROP-DOWN
2. Objective — DROP-DOWN
3. Age / phase — DROP-DOWN
4. Support needs — TICK BOXES
5. Output format — DROP-DOWN
6. Tone — TICK BOXES
7. Must include — FREE TEXT
8. Must avoid — FREE TEXT

# DESIGN NOTES

Provide short implementation notes covering:
- where a structured field is sufficient
- where “Other (specify)” is necessary
- where FREE TEXT is unavoidable
- any fields that should be split because they combine different kinds of information
- any ambiguous categories that should be validated with users before building the interface

# UNCLASSIFIED

Do not discard any response without explanation.
If a response does not fit under any of the four headings, place it here and explain briefly why.

══════════════════════════════════
IMPORTANT CONSTRAINTS
══════════════════════════════════

- Do not invent items.
- Do not discard rare items; include them either as options, “Other (specify)”, or in UNCLASSIFIED.
- Preserve professional terminology used by respondents where possible.
- Standardise wording, but do not over-generalise.
- If the spreadsheet contains more than one language, work from meaning, not wording.
- Produce all output in English.
- Optimise for actual interface design, not only thematic analysis.
