# AF-003 - Job Evidence Brief Tool Kit

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
https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-test/refs/heads/main/af-003-job-evidence-brief/README.md

---

## Purpose

This TEST deployment supports bounded validation of three AF-003 companion tools around the stable production Job Evidence Brief.

The tools under test are:

- Due Diligence Brief;
- Invisible Requirements Analysis;
- Qualifications Brief.

The Job Evidence Brief is included unchanged as the production baseline required by the workflow.

---

## Tool Set

| Repository Object | Tool | Status | Default Classification |
| --- | --- | --- | --- |
| `JOB_EVIDENCE_BRIEF` | Job Evidence Brief | Production baseline | Private candidate analysis |
| `DUE_DILIGENCE_BRIEF` | Due Diligence Brief | Public beta test | Private candidate research |
| `INVISIBLE_REQUIREMENTS_ANALYSIS` | Invisible Requirements Analysis | Public beta test | Private working analysis |
| `QUALIFICATIONS_BRIEF` | Qualifications Brief | Public beta test | Shareable after Human review |

---

## Recommended Workflow

```text
Job Evidence Brief
        |
        +--> Due Diligence Brief (optional)
        |           |
        |           v
        |   Invisible Requirements Analysis (optional)
        |           |
        +-----------+
                    v
           Qualifications Brief
```

Each companion tool may be used independently when its required inputs are available.

---

## Start Here

1. Load `ROOT_LIBRARY`.
2. Resolve and load `ROOT_SETUP`.
3. Load only the tool objects required for the test.
4. Provide the required candidate and opportunity materials.
5. Review every output before use or disclosure.

Do not infer missing repository objects or substitute recalled instructions.

---

## Test Objective

Determine whether the three companion tools:

- maintain distinct purposes and disclosure boundaries;
- fail closed when research or evidence cannot be verified;
- produce useful outputs across different opportunities and AI platforms;
- avoid unsupported employer claims and candidate evidence inflation;
- add value beyond the Job Evidence Brief without duplicating it.

No production promotion is implied by this TEST deployment.
