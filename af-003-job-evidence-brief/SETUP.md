# AF-003 Setup

**Kit Type:** Tool Kit  
**Status:** Test  
**Version:** 1.2-test  

Repository:  
AF-003 - Job Evidence Brief Tool Kit

Repository Object:  
`ROOT_LIBRARY`

Raw:  
https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-test/refs/heads/main/af-003-job-evidence-brief/LIBRARY.md

This File (Raw):  
https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-test/refs/heads/main/af-003-job-evidence-brief/SETUP.md

---

## Startup Sequence

1. Load `ROOT_LIBRARY` from its published raw location.
2. Resolve all required Repository Objects through `ROOT_LIBRARY`.
3. Load only the tools required for the selected workflow.
4. Confirm each loaded tool's purpose, status, inputs, and disclosure classification.
5. Request missing user inputs before operating.

Do not infer paths or reconstruct missing Repository Objects.

---

## Workflow A - Job Evidence Brief

Required object:

```text
JOB_EVIDENCE_BRIEF
```

Required inputs:

- a specific job posting or role description;
- candidate evidence such as a resume, career history, accomplishments, or project descriptions.

No online employer research is required.

---

## Workflow B - Due Diligence Brief

Required object:

```text
DUE_DILIGENCE_BRIEF
```

Required inputs:

- employer name;
- enough information to identify the employer accurately.

Recommended inputs:

- job posting;
- role title;
- business unit, location, recruiter, or hiring organization.

Current online research is mandatory. If current facts cannot be retrieved and verified, stop without producing a completed brief.

Default classification:

```text
Private Candidate Research / Not Intended for External Distribution
```

---

## Workflow C - Invisible Requirements Analysis

Required objects:

```text
INVISIBLE_REQUIREMENTS_ANALYSIS
JOB_EVIDENCE_BRIEF
DUE_DILIGENCE_BRIEF
```

Required inputs:

- original job posting;
- completed Job Evidence Brief;
- completed and research-verified Due Diligence Brief;
- validated candidate evidence.

If any upstream artifact is missing, stale, or unverified, stop and report the issue.

Default classification:

```text
Private Working Analysis / Not Intended for External Distribution
```

---

## Workflow D - Qualifications Brief

Required object:

```text
QUALIFICATIONS_BRIEF
```

Required inputs:

- specific job posting;
- completed Job Evidence Brief;
- candidate resume or source career materials.

Optional inputs:

- verified Due Diligence Brief;
- human-approved Invisible Requirements insights;
- portfolio, project, recruiter, or hiring-manager information.

Before final output, confirm that candidate claims are traceable, employer facts are sourced, proposed approaches are labeled, and private hypotheses are not exposed as facts.

Default classification:

```text
External Candidate Representation / Shareable After Human Review
```

---

## Retrieval Failure

If a required Repository Object cannot be retrieved:

1. Stop.
2. Identify the inaccessible object.
3. Report the failed location.
4. Do not infer, reconstruct, or substitute content.
5. Request a corrected location or another authorized copy.

---

## Human-in-Command Rule

The AI recommends and drafts.

The human decides whether an output is accurate, useful, complete, appropriate to share, or ready for further action.
