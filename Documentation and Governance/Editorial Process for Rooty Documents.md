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

#### 1.1 Scope of application

> ***This editorial process applies exclusively to statements and documents
that are explicitly endorsed by all participating CommunityCoin teams.***

Such documents represent shared positions of the CommunityCoins initiative
and are intended for public presentation, including publication on
the communitycoins.org website.

Participation in the editorial process does not require direct use of
the communitycoins platform.
Endorsement may be expressed orally, in writing, or through other
mutually accepted forms of communication.

### 2. Document roles

Each Rooty document consists one durectory and multiple representations
```
/Documentation and Governance/
└─ community-coins/
   ├─ README.md      — canonical document
   ├─ sequential.md  — sentence-indexed editorial reference
   └─ revisions      — proposed language and content changes
   ├─ history/
   │  ├─ v0.1/
   │  │  ├─ README.md
   │  │  ├─ sequential
   │  │  └─ revisions
   │  └─ v0.2/
   │     ├─ README.md
   │     ├─ sequential
   │     └─ revisions
   └─ changelog```

#### 2.1 README.md

The canonical document is the authoritative version of the text.
It represents the current accepted wording and the contents are directly visible when the user visits the directory

---

#### 2.2 Sequential document

The sequential document is an editorial representation of the canonical text.
It exists solely to support precise reference and revision tracking.

Properties:
- One sentence per line
- Stable sentence numbering
- Derived mechanically from the canonical document

The sequential document is not intended for general readership.

---

#### 2.3 Revision ledger

Each revision ledger should be accompanied by an issue. The `issue:issue id` is the first line in the ledger.
That way the issue becomes:
- Central place for discussion
- Objections and consent don’t clutter the revision file
- Maintainer can judge consensus quality, not vote counts

The revision ledger records all proposed changes, objections, and motivations.
It is the primary space for editorial discussion. 
Any contributor may propose a revision by adding an entry to the revision ledger.

structure for small changes:
```#<revision-number>
<sentence-number>:<original text>
:::<proposed text>
@<username>: <motivation>
```

structure for multi-line changes:
```#<revision-number>
<sentence-start-number>..<sentence-end-number>
<original text>
:::
<proposed text>
@<username>: <motivation>
```
---

#### 2.4 Acceptance and rejection

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
