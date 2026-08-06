# AF-003 Due Diligence Brief

**Kit Type:** Tool Kit  
**Status:** Public Beta Test  
**Version:** 0.9-beta  

Repository:  
AF-003 - Job Evidence Brief Tool Kit

Repository Object:  
`ROOT_LIBRARY`

Raw:  
https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-test/refs/heads/main/af-003-job-evidence-brief/LIBRARY.md

This File (Raw):  
https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-test/refs/heads/main/af-003-job-evidence-brief/tools/duediligencebrief.md

---

## Purpose

Produce a factual, current, source-grounded brief that helps a candidate understand an employer and a specific opportunity.

The Due Diligence Brief is research.

It does not assess candidate qualifications, infer invisible requirements, rewrite the resume, or predict hiring outcomes.

---

## Classification

```text
Private Candidate Research / Not Intended for External Distribution
```

The brief is private by default. A human may extract verified facts, questions, or meeting notes for selective sharing after deliberate review.

Factual claims must be sourced. Interpretation, unresolved questions, and private strategy notes must remain visibly separate from verified information.

---

## Required Inputs

Provide:

- employer name;
- enough identifying information to distinguish the employer from similarly named organizations.

Recommended when available:

- specific job posting;
- job title;
- business unit or division;
- location;
- recruiter or hiring contact;
- employer website or LinkedIn page.

No candidate resume or career history is required.

---

## Research Verification Gate

Before producing a completed Due Diligence Brief, confirm:

```text
Research Verification

Employer identity confirmed:
Primary sources retrieved:
Publication dates checked:
Current strategic claims verified:
Material factual claims cited:
Unsupported search snippets excluded:
```

If current research cannot be retrieved and verified in the active session, stop and state:

> Current employer research could not be verified in this session. The Due Diligence Brief cannot be completed reliably.

Do not substitute recalled company information, unsupported search snippets, or plausible-sounding facts.

---

## Research Requirements

Use current online research.

Prefer authoritative and primary sources, including:

- official employer website;
- annual reports and regulatory filings;
- investor relations materials;
- official press releases;
- earnings-call materials;
- executive statements;
- official technology, product, and career pages;
- relevant government or regulatory sources.

Use reputable secondary sources when they add necessary context.

For every material factual claim:

- identify the source;
- provide a citation or usable source reference;
- record the publication or access date when practical;
- distinguish current information from historical background.

Do not rely on unsupported search snippets.

---

## Research Scope

Research only what is useful for understanding the employer and opportunity.

### 1. Employer Identity

Confirm:

- correct legal or operating identity;
- ownership or parent organization;
- primary business lines;
- relevant division or subsidiary;
- geographic scope.

### 2. Business Model and Customers

Summarize:

- how the organization creates value;
- primary customers or stakeholders;
- major products or services;
- operating scale when relevant.

### 3. Current Strategic Direction

Identify documented priorities such as:

- growth;
- modernization;
- cost reduction;
- cloud or data-platform investment;
- AI or automation;
- mergers, acquisitions, or restructuring;
- customer-experience changes;
- regulatory or operational changes.

Do not treat a broad corporate initiative as proof that it controls the specific hiring decision.

### 4. Operating Environment

Describe relevant conditions such as:

- high-volume or continuous operations;
- distributed facilities;
- regulated data;
- international operations;
- legacy and modern systems operating together;
- safety, security, continuity, or audit obligations.

### 5. Opportunity Context

Using the posting and verified company context, summarize:

- where the role appears to sit;
- what the role explicitly owns;
- who the role supports;
- stated priorities and deliverables;
- important technologies or domains;
- known reporting relationships.

Do not infer unstated requirements in this section.

### 6. Recent Developments

Identify only developments that may reasonably affect the opportunity, such as:

- major leadership changes;
- acquisitions or divestitures;
- restructuring;
- technology programs;
- major product launches;
- material regulatory events;
- publicly reported operational problems.

### 7. Risks and Open Questions

Separate:

- verified risks or constraints;
- unresolved questions;
- items requiring confirmation during interviews.

Avoid speculative claims about internal dysfunction, hidden motives, or confidential conditions.

---

## Output Format

# Due Diligence Brief

**Employer:**  
**Opportunity:**  
**Prepared:**  
**Classification:** Private Candidate Research / Not Intended for External Distribution

## Executive Summary

Provide a concise overview of the employer, the opportunity, and the most relevant current context.

## Employer and Business Context

Summarize verified facts about the organization and business model.

## Current Strategic Direction

Summarize documented priorities that may affect the opportunity.

## Operating Environment

Describe relevant operational, technical, regulatory, or organizational conditions.

## Opportunity Context

Summarize what the posting explicitly says about the role.

## Recent Relevant Developments

List only developments that appear material to understanding the opportunity.

## Questions Worth Asking

Provide practical questions that test assumptions, clarify priorities, or improve candidate understanding.

## Sources

List the sources used with enough information for a human to locate and verify them.

---

## Selective Sharing Rules

The complete brief is not intended for routine external distribution. Before sharing any portion externally:

- remove private notes;
- remove unsupported interpretations;
- confirm names, dates, titles, and statistics;
- verify that citations still work;
- avoid language that sounds accusatory, presumptuous, or confidential;
- retain unresolved issues as questions rather than claims.

A shared Due Diligence Brief should demonstrate preparation, not attempt to prove that the candidate understands the employer better than the employer does.

---

## Guardrails

Do not:

- invent company facts;
- imply access to confidential information;
- infer invisible requirements;
- rank the candidate;
- evaluate candidate fit;
- convert rumors into findings;
- repeat generic company facts that do not help understand the opportunity;
- produce an unsourced collection of search results.

Research should test understanding of the opportunity, not merely decorate a report.

---

## Success Criteria

A successful Due Diligence Brief should help the candidate:

- understand the employer accurately;
- recognize relevant strategic and operational context;
- prepare stronger interview questions;
- identify facts that may affect application strategy;
- bring organized, credible notes into conversations;
- provide clean factual input to the Invisible Requirements Analysis.
