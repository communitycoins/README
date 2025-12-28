source: Editorial Process for Rooty Documents  
version: v0.1  
status: draft  

---

### 1. Purpose

This document defines the editorial process for Rooty documents.
Its purpose is to ensure clarity, transparency, and traceability of changes,
while preserving readability of the authoritative text.

The process is designed to support discussion, dissent, and gradual refinement,
without requiring premature formal governance structures.

---

### 2. Document roles

Each Rooty document consists of multiple representations,
each serving a distinct purpose.

#### 2.1 Canonical document

The canonical document is the authoritative version of the text.
It represents the current accepted wording.

Properties:
- Clean prose
- Paragraph-based structure
- No editorial comments or suggestions
- Updated only through explicit acceptance

Readers should consider the canonical document as the current statement of intent.

---

#### 2.2 Sequential document

The sequential document is an editorial representation of the canonical text.
It exists solely to support precise reference and revision tracking.

Properties:
- One sentence per line
- Stable sentence numbering
- No semantic authority
- Derived mechanically from the canonical document

The sequential document is not intended for general readership.

---

#### 2.3 Revision ledger

The revision ledger records all proposed changes, objections, and motivations.
It is the primary space for editorial discussion.

Properties:
- References sentences in the sequential document
- Contains proposed wording, rationale, and status
- Does not directly alter the canonical text

---

### 3. Editorial actions

#### 3.1 Proposing a revision

Any contributor may propose a revision by adding an entry to the revision ledger.

Each revision entry must include:
- Target document and version
- Sentence number(s) in the sequential document
- Original sentence(s)
- Proposed alternative wording
- Rationale for the proposal
- Author and date

Revisions may concern language, clarity, consistency, or structure.
Interpretative or normative changes should be explicitly identified as such.

---

#### 3.2 Discussion and objection

Revisions may be discussed by adding remarks or objections to the same entry.
Objections should focus on clarity, intent, or consequences of the proposed change.

No revision is considered accepted by default.

---

#### 3.3 Acceptance and rejection

Acceptance or rejection of revisions is the responsibility of the maintainer.

When a revision is accepted:
1. The canonical document is updated accordingly.
2. The sequential document is regenerated.
3. The document version is incremented.
4. The revision entry is marked as accepted and references the new version.

When a revision is rejected or deferred,
its status is updated with a brief explanation.

---

### 4. Authority

The maintainer has final responsibility for the canonical text.
This authority is explicit and documented through versioned changes.

The existence of maintainer authority does not preclude forks.
Any party remains free to adopt alternative editorial decisions.

---

### 5. Versioning

Document versions are incremented when accepted revisions alter the canonical text.
Minor language changes and structural changes are treated equally with respect to versioning.

Version numbers indicate editorial progression, not finality.

---

### 6. Scope and limitations

This editorial process defines how text changes are handled.
It does not define governance, voting rights, or legal authority.

Those concerns may be addressed in separate documents, if and when required.

---

### 7. Provisional nature

This editorial process is itself provisional.
It may be revised using the same mechanism described herein.
