---
layout: default
title: "Chapter 2: Core Concepts and Knowledge Types"
parent: "Part I: Foundations"
nav_order: 2
permalink: /chapters/02-core-concepts/
---

# Chapter 2: Core Concepts and Knowledge Types

## Learning Objectives

After completing this chapter, you will be able to:
- Explain the DIKW hierarchy and its significance
- Differentiate between tacit, explicit, implicit, and embedded knowledge
- Understand knowledge characteristics and their implications
- Recognize the challenges of different knowledge types
- Apply knowledge classification to organizational contexts

---

## The DIKW Hierarchy

The **Data-Information-Knowledge-Wisdom (DIKW)** hierarchy is a foundational model for understanding how raw data transforms into actionable wisdom.

### The Four Levels

| Level | Definition | Characteristics | Example |
|-------|------------|-----------------|---------|
| **Data** | Raw facts, figures, and observations | No context, unorganized, objective | Server CPU: 95% |
| **Information** | Data with context and meaning | Organized, answers "who, what, when, where" | Server CPU spiked to 95% during nightly backup at 2 AM |
| **Knowledge** | Information combined with experience | Actionable, answers "how" | Backup jobs on this server type cause CPU spikes; schedule during low-usage periods |
| **Wisdom** | Knowledge applied with judgment | Strategic, answers "why" and enables foresight | Design infrastructure to isolate backup workloads; implement resource governance |

### Transformation Process

```
Data → (Context) → Information → (Experience) → Knowledge → (Judgment) → Wisdom
```

| Transformation | Process | Activities |
|---------------|---------|------------|
| Data → Information | Contextualization | Categorize, calculate, condense, contextualize |
| Information → Knowledge | Application | Compare, connect, converse, consider consequences |
| Knowledge → Wisdom | Integration | Reflect, evaluate, anticipate, exercise judgment |

### DIKW in Practice

**Service Desk Example:**

| Level | Content |
|-------|---------|
| **Data** | Error code: 0x80070005 |
| **Information** | User received error 0x80070005 when trying to access shared folder at 9:15 AM |
| **Knowledge** | Error 0x80070005 is an access denied error; check user permissions on folder, verify group membership, reset permissions if needed |
| **Wisdom** | Implement proactive permission auditing and automated group membership reviews to prevent access issues |

---

## Types of Knowledge

### The Tacit-Explicit Spectrum

Knowledge exists on a spectrum from tacit (personal, hard to articulate) to explicit (documented, easily shared).

```
Tacit ←――――――――――――――――――――――→ Explicit
(Personal)    (Implicit)    (Documented)
```

### Tacit Knowledge

**Definition**: Personal knowledge rooted in individual experience, insights, intuition, and skills that is difficult to articulate or document.

| Characteristic | Description |
|----------------|-------------|
| **Personal** | Resides in individuals' minds |
| **Context-dependent** | Meaning tied to specific situations |
| **Hard to articulate** | "I know it when I see it" |
| **Acquired through experience** | Learning by doing |
| **Difficult to transfer** | Requires observation, mentoring |

**Examples of Tacit Knowledge:**
- Experienced technician's ability to diagnose problems by "feel"
- Manager's intuition about team dynamics
- Expert's ability to recognize patterns quickly
- Skilled negotiator's sense of timing
- Craftsperson's motor skills and techniques

**Challenges with Tacit Knowledge:**

| Challenge | Impact | Mitigation |
|-----------|--------|------------|
| Difficult to capture | Knowledge loss when experts leave | Mentoring, shadowing programs |
| Hard to validate | Quality varies, inconsistent | Peer review, testing |
| Not searchable | Can't find when needed | Expert directories, skill mapping |
| Context-sensitive | May not transfer to new situations | Scenario documentation |

### Explicit Knowledge

**Definition**: Knowledge that has been articulated, codified, and documented in formats that can be easily shared and understood.

| Characteristic | Description |
|----------------|-------------|
| **Documented** | Written, recorded, or coded |
| **Shareable** | Easily transmitted to others |
| **Storable** | Can be captured in repositories |
| **Searchable** | Can be indexed and found |
| **Replicable** | Can be copied and distributed |

**Examples of Explicit Knowledge:**
- Standard operating procedures
- Knowledge base articles
- Technical documentation
- Policy manuals
- Training materials
- Process diagrams

**Explicit Knowledge Formats:**

| Format | Use Case | Strengths |
|--------|----------|-----------|
| Documents | Procedures, guides | Detailed, comprehensive |
| Videos | Demonstrations, training | Visual, engaging |
| Diagrams | Processes, architectures | Clear visualization |
| Databases | Structured data | Searchable, relational |
| FAQs | Common questions | Quick reference |
| Wikis | Collaborative content | Easy updates, versioning |

### Implicit Knowledge

**Definition**: Knowledge that can be articulated but has not yet been documented. It exists between tacit and explicit.

| Characteristic | Description |
|----------------|-------------|
| **Articulable** | Can be expressed if asked |
| **Undocumented** | Not yet captured |
| **Accessible** | Can be obtained through inquiry |
| **Convertible** | Can become explicit with effort |

**Examples:**
- Unwritten team norms and practices
- Workarounds that "everyone knows"
- Informal processes not in procedure manuals
- Institutional memory of "how things really work"

**Converting Implicit to Explicit:**

| Technique | Description |
|-----------|-------------|
| Interviews | Structured conversations with knowledge holders |
| Observation | Watching experts perform tasks |
| Think-aloud protocols | Experts verbalize their thought process |
| After-action reviews | Capturing lessons immediately after events |
| Documentation sprints | Focused efforts to document specific areas |

### Embedded Knowledge

**Definition**: Knowledge that is built into processes, systems, products, or organizational structures.

| Characteristic | Description |
|----------------|-------------|
| **Systemic** | Part of how things work |
| **Often invisible** | Not recognized as knowledge |
| **Institutional** | Belongs to the organization |
| **Persistent** | Survives personnel changes |

**Examples:**
- Business rules in software systems
- Workflow automations
- Templates with built-in best practices
- Organizational structures reflecting strategy
- Physical layouts optimizing workflow

---

## Knowledge Characteristics

### Dimensions of Knowledge

| Dimension | Spectrum | Implications |
|-----------|----------|--------------|
| **Codifiability** | Tacit ↔ Explicit | Affects capture and transfer methods |
| **Complexity** | Simple ↔ Complex | Affects documentation and training needs |
| **Specificity** | General ↔ Specific | Affects reusability across contexts |
| **Volatility** | Stable ↔ Dynamic | Affects maintenance requirements |
| **Criticality** | Nice-to-have ↔ Essential | Affects prioritization and governance |

### Knowledge Life Cycle Stage

| Stage | Description | KM Focus |
|-------|-------------|----------|
| **Emerging** | New knowledge being created | Capture, validation |
| **Maturing** | Knowledge being refined and validated | Quality, standardization |
| **Stable** | Established, proven knowledge | Maintenance, accessibility |
| **Declining** | Becoming outdated or obsolete | Review, archival, retirement |

### Knowledge Characteristics Assessment

| Characteristic | Questions to Ask |
|----------------|------------------|
| **Source** | Who knows this? Where did it originate? |
| **Validity** | How accurate is it? When was it validated? |
| **Applicability** | In what contexts does it apply? |
| **Completeness** | Is it sufficient for the use case? |
| **Accessibility** | Who can access it? How easily? |
| **Currency** | How current is it? When does it expire? |

---

## Individual vs. Organizational Knowledge

### Individual Knowledge

Knowledge held by individual employees:

| Type | Examples | Risk |
|------|----------|------|
| **Skills** | Technical abilities, soft skills | Lost when employee leaves |
| **Experience** | Lessons learned, pattern recognition | Hard to transfer |
| **Networks** | Relationships, contacts | Personal, not organizational |
| **Context** | History, background understanding | Often undocumented |

### Organizational Knowledge

Knowledge that belongs to the organization:

| Type | Examples | Storage |
|------|----------|---------|
| **Documented processes** | SOPs, procedures, guidelines | Knowledge bases, wikis |
| **Institutional memory** | Historical decisions, rationale | Archives, case studies |
| **Collective capabilities** | Team skills, organizational competencies | Skill databases, assessments |
| **Structural knowledge** | How the organization works | Org charts, process maps |

### Converting Individual to Organizational Knowledge

| Strategy | Description | Example |
|----------|-------------|---------|
| **Documentation** | Capture expertise in written form | Procedure guides, knowledge articles |
| **Training** | Transfer through education | Courses, workshops, certifications |
| **Mentoring** | One-on-one knowledge transfer | Pairing experts with newcomers |
| **Communities** | Group learning and sharing | CoPs, forums, special interest groups |
| **Embedding** | Build into systems and processes | Automation, templates, checklists |

---

## Knowledge Quality Dimensions

### Quality Attributes

| Attribute | Definition | Assessment Question |
|-----------|------------|---------------------|
| **Accuracy** | Free from errors | Is the information correct? |
| **Completeness** | Contains all necessary information | Is anything missing? |
| **Currency** | Up-to-date and timely | Is it current? |
| **Relevance** | Applicable to the use case | Does it address the need? |
| **Clarity** | Easy to understand | Is it clear and unambiguous? |
| **Accessibility** | Easy to find and retrieve | Can users get to it? |
| **Credibility** | Trustworthy source | Is the source reliable? |
| **Consistency** | Aligns with other knowledge | Does it contradict other sources? |

### Quality Assessment Matrix

| Quality Level | Characteristics | Action Required |
|---------------|-----------------|-----------------|
| **Gold** | Accurate, complete, current, validated | Promote and reference |
| **Silver** | Generally accurate, may need minor updates | Schedule review |
| **Bronze** | Useful but needs improvement | Flag for enhancement |
| **Needs Work** | Incomplete, potentially inaccurate | Major revision required |
| **Archive** | Outdated but historically valuable | Move to archive |
| **Retire** | No longer valid or useful | Remove from active use |

---

## Knowledge in Context

### Contextual Factors

Knowledge meaning and applicability depend on context:

| Factor | Impact on Knowledge |
|--------|---------------------|
| **Time** | What was true may no longer be |
| **Location** | Practices vary by region/site |
| **Role** | Different needs for different roles |
| **Situation** | Emergency vs. routine scenarios |
| **Technology** | System-specific knowledge |
| **Regulatory** | Compliance requirements vary |

### Context Capture Requirements

| Context Element | Examples | Why It Matters |
|-----------------|----------|----------------|
| **When created** | Date, version | Assess currency |
| **Who created** | Author, expert | Assess credibility |
| **What problem** | Use case, scenario | Assess relevance |
| **Which system** | Application, platform | Assess applicability |
| **What conditions** | Prerequisites, limitations | Assess validity |

---

## Key Takeaways

- The DIKW hierarchy shows how data transforms into wisdom through context, experience, and judgment
- Tacit knowledge (personal, experiential) is harder to capture but often more valuable than explicit knowledge
- Implicit knowledge can be converted to explicit with intentional effort
- Embedded knowledge persists in organizational systems and processes
- Knowledge quality must be actively managed across accuracy, completeness, currency, and other dimensions
- Context is essential for knowledge to be meaningful and applicable
- Converting individual knowledge to organizational knowledge protects against knowledge loss

---

## Summary

Understanding the different types and characteristics of knowledge is fundamental to effective Knowledge Management. The DIKW hierarchy provides a framework for understanding how raw data becomes actionable wisdom. Recognizing the differences between tacit, explicit, implicit, and embedded knowledge helps organizations develop appropriate strategies for capture, sharing, and application. Quality dimensions ensure that knowledge remains accurate, current, and useful, while context ensures knowledge is applied appropriately.

---

## Chapter Navigation

| Previous | Up | Next |
|----------|-------|------|
| [← Chapter 1: Introduction](/KnowledgeManagementHandbook/chapters/01-introduction/) | [Part I: Foundations](/KnowledgeManagementHandbook/part1-foundations/) | [Chapter 3: Frameworks →](/KnowledgeManagementHandbook/chapters/03-frameworks/) |
