---
layout: default
title: "Chapter 3: Knowledge Management Frameworks"
parent: "Part I: Foundations"
nav_order: 3
permalink: /chapters/03-frameworks/
---

# Chapter 3: Knowledge Management Frameworks

## Learning Objectives

After completing this chapter, you will be able to:
- Apply the SECI model to knowledge creation and conversion
- Understand the Knowledge Spiral and Ba concept in organizational contexts
- Implement Knowledge-Centered Service (KCS) methodology
- Explain ITIL 4 Knowledge Management practice
- Compare and contrast different KM frameworks including APQC, Wiig, and Boisot
- Select appropriate frameworks for specific organizational contexts
- Integrate multiple frameworks to create comprehensive KM systems

---

## The SECI Model

The **SECI Model**, developed by Ikujiro Nonaka and Hirotaka Takeuchi in their seminal work "The Knowledge-Creating Company" (1995), describes how knowledge is created through continuous conversion between tacit and explicit forms. This model remains the most influential theoretical framework for understanding organizational knowledge creation and has been applied across industries worldwide.

### The Four Modes of Knowledge Conversion

The SECI model identifies four fundamental modes through which knowledge is converted and created within organizations:

| Mode | Conversion | Description | Example |
|------|------------|-------------|---------|
| **Socialization** | Tacit → Tacit | Sharing tacit knowledge through shared experiences | Apprenticeship, observation, mentoring |
| **Externalization** | Tacit → Explicit | Articulating tacit knowledge into explicit concepts | Documentation, metaphors, analogies |
| **Combination** | Explicit → Explicit | Combining different explicit knowledge sources | Reports, databases, systemization |
| **Internalization** | Explicit → Tacit | Embodying explicit knowledge through practice | Training, learning by doing |

### Socialization: Tacit to Tacit Knowledge Transfer

**Socialization** is the process of sharing experiences and creating tacit knowledge through direct interaction. This is the most natural form of knowledge transfer but also the most difficult to scale.

#### Key Characteristics
- Occurs through observation, imitation, and practice
- Requires physical proximity or rich communication channels
- Creates sympathized knowledge (shared mental models)
- Does not require language or explicit articulation

#### Techniques and Practices

**Table 3.1: SECI Model Techniques and Tools**

| SECI Mode | Techniques | Tools/Platforms | Success Factors |
|-----------|-----------|-----------------|-----------------|
| **Socialization** | Mentoring, job shadowing, apprenticeships, storytelling, war room sessions | Video conferencing, collaboration spaces, communities of practice | Trust, time allocation, psychological safety |
| **Externalization** | Metaphors, analogies, brainstorming, dialogue, knowledge cafés | Wikis, documentation tools, visual mapping software | Facilitation skills, questioning culture, creative space |
| **Combination** | Database integration, categorization, report generation, data mining | Knowledge bases, CMDB, analytics platforms, SKMS | Information architecture, data governance, search capability |
| **Internalization** | Simulations, learning by doing, role-playing, guided practice | E-learning, VR training, sandbox environments | Practice opportunities, reflection time, coaching support |

**Socialization Examples in IT Operations:**
- **Incident Response Shadowing:** Junior analysts observe senior staff handling critical incidents, learning intuition and decision-making patterns
- **War Room Sessions:** Cross-functional teams work together during major incidents, sharing mental models and problem-solving approaches
- **Community Meetups:** IT staff gather informally to discuss challenges and share experiences
- **Peer Programming:** Developers work together, transferring coding practices and architectural thinking

### Externalization: Making the Tacit Explicit

**Externalization** is the most critical mode for organizational knowledge creation because it converts valuable tacit knowledge into explicit concepts that can be shared broadly. This is also the most challenging conversion, as much tacit knowledge is difficult to articulate.

#### Externalization Techniques

**Metaphors and Analogies:** Using figurative language to articulate tacit understanding. For example, describing a network architecture as a "highway system" to convey traffic flow concepts.

**Dialogue and Reflection:** Structured conversations that help individuals articulate their intuitive understanding. Knowledge cafés and after-action reviews serve this purpose.

**Concept Creation:** Developing new concepts, models, or frameworks that capture collective understanding. The SECI model itself is an externalization of Nonaka's tacit understanding of knowledge creation.

**Documentation Sessions:** Facilitated workshops where experts articulate their knowledge into templates, runbooks, and knowledge articles.

**Externalization in IT Support:**
- **Knowledge Article Creation:** Support agents document solutions while resolving incidents
- **Root Cause Analysis Documentation:** Problem managers articulate diagnostic reasoning
- **Architecture Decision Records:** Technical leaders document the rationale behind design choices
- **Postmortem Reports:** Teams reflect on incidents and capture lessons learned

### Combination: Systemizing Explicit Knowledge

**Combination** involves reconfiguring existing explicit knowledge through sorting, categorizing, and combining information. This mode creates systemic knowledge by connecting different bodies of explicit knowledge.

#### Combination Activities

**Data Integration:** Connecting information from multiple sources into unified views (e.g., CMDB integration with monitoring data).

**Categorization and Taxonomy:** Organizing knowledge into logical structures for retrieval and analysis.

**Report Generation:** Synthesizing data into meaningful reports, dashboards, and analytics.

**Systemization:** Creating processes, procedures, and standards from various knowledge sources.

**Combination in ITSM:**
- **Knowledge Base Development:** Organizing articles into taxonomies with relationships
- **Service Catalog Creation:** Combining service definitions, SLAs, and process documentation
- **Dashboard Development:** Integrating metrics from multiple systems into executive views
- **Process Documentation:** Synthesizing best practices into standardized procedures

### Internalization: Embodying Knowledge Through Practice

**Internalization** is the process by which explicit knowledge becomes part of individuals' tacit knowledge base. This occurs through practice, experimentation, and experience.

#### Internalization Methods

**Learning by Doing:** Hands-on practice with real or simulated scenarios. This is the most effective internalization method.

**Training Programs:** Structured learning that moves from theory to practice.

**Experimentation:** Trying different approaches and learning from results.

**Reflection:** Thinking about experiences and extracting lessons.

**Internalization in IT:**
- **Sandbox Environments:** Engineers practice changes in non-production environments
- **Incident Simulations:** Teams rehearse response procedures through tabletop exercises
- **E-Learning with Labs:** Self-paced training combined with practical exercises
- **Continuous Practice:** Regularly applying procedures until they become second nature

### The Knowledge Spiral: Organizational Knowledge Creation

The SECI model's true power lies not in individual modes but in the **Knowledge Spiral**—the continuous movement through all four modes that amplifies knowledge from individual to organizational level.

**Figure 3.1:** SECI Knowledge Spiral
*Caption:* The Knowledge Spiral shows how knowledge expands from individual to group to organizational level through continuous SECI cycles
*Position:* Place after this paragraph

```
           Tacit                    Explicit
    ┌────────────────────┬────────────────────┐
    │                    │                    │
    │   SOCIALIZATION    │   EXTERNALIZATION  │
    │                    │                    │
    │   (Tacit → Tacit)  │   (Tacit → Explicit)│
Tacit│                    │                    │
    │    Empathizing     │    Articulating    │
    │                    │                    │
    ├────────────────────┼────────────────────┤
    │                    │                    │
    │   INTERNALIZATION  │    COMBINATION     │
    │                    │                    │
    │(Explicit → Tacit)  │(Explicit → Explicit)│
Explicit                  │                    │
    │    Embodying       │    Connecting      │
    │                    │                    │
    └────────────────────┴────────────────────┘
              ⟲ Knowledge Spiral ⟲
       Individual → Group → Organization
```

#### The Spiral Process

1. **Individual Level:** A support agent develops tacit expertise (Internalization)
2. **Group Level:** Agent shares experiences with team (Socialization), documents solutions (Externalization)
3. **Organizational Level:** Documentation is systematized in knowledge base (Combination)
4. **Spiral Expansion:** New staff learn from knowledge base (Internalization), bringing fresh perspectives
5. **Innovation:** The cycle repeats, each iteration adding new knowledge and insights

**Example: Knowledge Spiral in Problem Management**

1. **Socialization:** Problem manager and senior engineers discuss recurring incident patterns
2. **Externalization:** Team documents root causes and fixes in problem records
3. **Combination:** Problems are linked to CIs, incidents, and changes in CMDB
4. **Internalization:** Engineers study problem records before troubleshooting
5. **New Cycle:** Engineers discover new patterns, share with team (Socialization begins again)

### Ba: The Shared Space Concept

Nonaka introduced the concept of **Ba** (場) - a Japanese term meaning "place" or "field" - to describe the shared space where knowledge is created. Ba is not just physical space but includes virtual, mental, and social contexts that enable knowledge creation.

**Table 3.2: Ba Types and Characteristics**

| Ba Type | SECI Mode | Characteristics | Examples | Enablers |
|---------|-----------|----------------|----------|----------|
| **Originating Ba** | Socialization | Face-to-face, high trust, shared experiences | Mentoring sessions, brainstorming rooms, team spaces | Physical proximity, informal settings, dedicated time |
| **Dialoguing Ba** | Externalization | Collective reflection, dialogue, peer-to-peer | Knowledge cafés, communities of practice, workshops | Facilitation, psychological safety, diverse perspectives |
| **Systemizing Ba** | Combination | Virtual collaboration, systematic organization | Knowledge bases, intranets, databases, documentation systems | Information architecture, search capability, governance |
| **Exercising Ba** | Internalization | Active participation, practice, mentoring | Training labs, simulation environments, on-the-job coaching | Practice opportunities, feedback, reflection time |

#### Creating Effective Ba

**Physical Ba:** Designing office spaces that encourage interaction:
- Open collaboration zones
- War rooms for incident response
- Quiet spaces for documentation
- Social areas for informal knowledge sharing

**Virtual Ba:** Digital platforms that enable knowledge creation:
- Collaboration tools (Slack, Teams)
- Knowledge management systems
- Video conferencing with screen sharing
- Virtual whiteboarding tools

**Mental Ba:** Psychological conditions for knowledge sharing:
- Trust and psychological safety
- Shared vision and purpose
- Common language and concepts
- Openness to new ideas

**Social Ba:** Organizational culture and practices:
- Communities of practice
- Knowledge-sharing rituals
- Recognition for contribution
- Cross-functional projects

### Applying SECI in Organizations

| Mode | Organizational Activities | KM Practices | Metrics |
|------|---------------------------|--------------|---------|
| **Socialization** | Team meetings, coffee talks, job shadowing | Communities of practice, mentoring programs | Participation rates, network density |
| **Externalization** | Brainstorming, documentation sessions | Knowledge capture workshops, article creation | Articles created, documentation coverage |
| **Combination** | Database integration, report synthesis | Knowledge bases, taxonomies, dashboards | Search success rate, information findability |
| **Internalization** | Training, simulation, practice | E-learning, hands-on workshops, role-playing | Training completion, competency scores |

### SECI Enablers

| Enabler | Description | Examples | Implementation Tips |
|---------|-------------|----------|-------------------|
| **Ba (shared space)** | Context for knowledge creation | Physical, virtual, mental spaces | Design spaces intentionally for each SECI mode |
| **Knowledge Assets** | Inputs and outputs of knowledge creation | Documents, databases, expertise | Inventory and value knowledge assets |
| **Knowledge Vision** | Direction for knowledge creation | Strategic goals, KM objectives | Align KM vision with business strategy |
| **Conversation** | Dialogue that enables conversion | Meetings, forums, discussions | Facilitate meaningful dialogue, not just information exchange |

---

## Knowledge-Centered Service (KCS)

**KCS** is a methodology for integrating knowledge creation and maintenance into the problem-solving process, developed by the Consortium for Service Innovation. Unlike SECI, which is theoretical, KCS is a practical, prescriptive methodology with proven ROI in service and support organizations.

### KCS Principles

| Principle | Description | Implications |
|-----------|-------------|--------------|
| **Abundance** | Create knowledge as a by-product of solving problems | No separate documentation team; knowledge is created during work |
| **Create Value** | Knowledge is valuable when it helps others solve problems | Focus on usefulness, not perfection; value measured by reuse |
| **Demand Driven** | Capture knowledge based on actual customer/user demand | Don't document everything; create/update based on requests |
| **Trust** | Contributors are trusted as knowledge workers | Lightweight review process; publish quickly, improve continuously |

### The KCS Double Loop

KCS operates through two interdependent loops that operate at different levels:

#### Solve Loop (Individual Level)

The Solve Loop integrates knowledge work into the incident/request resolution process:

| Step | Activity | Description | KCS Behavior |
|------|----------|-------------|--------------|
| **Capture** | Create/modify article in workflow | Document solution as you solve | Open knowledge base alongside ticketing system |
| **Structure** | Use consistent template | Standard format for findability | Apply taxonomy while creating |
| **Reuse** | Search before creating | Use existing knowledge first | "Search early, search often" |
| **Improve** | Flag or fix issues | Continuous content improvement | Update immediately if able, flag if not |

**Solve Loop Workflow:**

```
┌─────────────────────────────────────────────────────────┐
│                     SOLVE LOOP                          │
│                                                         │
│   ┌──────────┐     ┌──────────┐     ┌──────────┐     │
│   │  SEARCH  │ ──→ │  CAPTURE │ ──→ │ IMPROVE  │     │
│   │          │     │          │     │          │     │
│   │  First   │     │  As you  │     │  Update  │     │
│   │          │     │  solve   │     │  quality │     │
│   └──────────┘     └──────────┘     └──────────┘     │
│        ↓                 ↓                 ↓           │
│   ┌──────────┐     ┌──────────┐     ┌──────────┐     │
│   │  REUSE   │     │STRUCTURE │     │  VERIFY  │     │
│   │ Existing │     │ Template │     │ Accuracy │     │
│   └──────────┘     └──────────┘     └──────────┘     │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

#### Evolve Loop (Organizational Level)

The Evolve Loop ensures the KCS process and content remain healthy and valuable:

| Step | Activity | Description | Key Actions |
|------|----------|-------------|-------------|
| **Content Health** | Monitor quality metrics | Track accuracy, usage, feedback | Review article analytics, age, usage patterns |
| **Process Integration** | Embed KCS in workflows | Make KCS part of daily work | Integrate with ITSM tools, remove barriers |
| **Performance Assessment** | Measure KCS effectiveness | KPIs, reports, analysis | Track self-service deflection, resolution time |
| **Leadership & Communication** | Support and promote KCS | Vision, resources, recognition | Executive sponsorship, coaching, recognition |

### KCS Article Lifecycle

| State | Description | Who Can Modify | Publication Status |
|-------|-------------|----------------|-------------------|
| **Work in Progress (WIP)** | Draft, being created | Author only | Not published; visible to author |
| **Not Validated** | Published but not reviewed | KCS Contributors | Published internally; not yet validated |
| **Validated (Internal)** | Reviewed for internal use | KCS Publishers | Published for internal staff |
| **Validated (External)** | Approved for customer self-service | KCS Publishers | Published to customer portal |
| **Archived** | No longer active but preserved | KCS Coaches | Not searchable; preserved for reference |

**Article Lifecycle Transitions:**

```
┌─────────────┐      ┌──────────────┐      ┌─────────────┐
│    WIP      │ ──→  │     Not      │ ──→  │  Validated  │
│   (Draft)   │      │  Validated   │      │  (Internal) │
└─────────────┘      └──────────────┘      └─────────────┘
                                                   ↓
                                            ┌─────────────┐
                                            │  Validated  │
                                            │ (External)  │
                                            └─────────────┘
                                                   ↓
                                            ┌─────────────┐
                                            │  Archived   │
                                            └─────────────┘
```

### KCS Roles

| Role | Responsibilities | Training Level | Time Allocation |
|------|------------------|----------------|-----------------|
| **KCS Candidate** | Learning KCS methodology | Basic awareness | 10% KCS learning |
| **KCS Contributor** | Creates and modifies WIP/Not Validated articles | KCS Fundamentals | 20% documentation |
| **KCS Publisher** | Validates articles for internal/external use | Advanced KCS | 30% content quality |
| **KCS Coach** | Mentors others, manages content health | Expert level | 40% coaching/quality |
| **KCS Domain Expert (KDE)** | Strategic content ownership for knowledge domain | Leadership | 50% strategy/architecture |

### KCS Benefits and ROI

Organizations implementing KCS typically realize:

**Efficiency Gains:**
- 30-50% reduction in time to resolution
- 20-35% increase in cases per analyst
- 40-60% improvement in first contact resolution

**Quality Improvements:**
- 25-40% increase in customer satisfaction
- 50-70% reduction in escalations
- Improved knowledge article accuracy and relevance

**Cost Savings:**
- 20-30% reduction in support costs
- Reduced training time for new staff
- Lower reliance on Level 2/3 resources

---

## ITIL 4 Knowledge Management Practice

ITIL 4 defines Knowledge Management as a practice within the Service Value System, emphasizing its role in enabling effective service delivery and continual improvement.

### Purpose

> To maintain and improve the effective, efficient, and convenient use of information and knowledge across the organization.

### Key Activities

| Activity | Description | Inputs | Outputs |
|----------|-------------|--------|---------|
| **Identification** | Determine what knowledge is needed and available | Business needs, skill gaps | Knowledge requirements |
| **Capture** | Collect and document knowledge | Expert insights, documentation | Knowledge articles, records |
| **Classification** | Organize knowledge for findability | Captured knowledge | Taxonomy, categories |
| **Storage** | Maintain knowledge in appropriate repositories | Classified knowledge | Knowledge base, CMDB |
| **Sharing** | Make knowledge available to those who need it | Stored knowledge | Self-service, training |
| **Use** | Apply knowledge to achieve outcomes | Available knowledge | Resolved incidents, decisions |
| **Maintenance** | Keep knowledge current and accurate | Usage feedback, changes | Updated articles |
| **Disposal** | Archive or remove outdated knowledge | Obsolete content | Archived records |

### Service Knowledge Management System (SKMS)

The SKMS is a set of tools and databases used to manage knowledge and information:

```
┌─────────────────────────────────────────────────────────────┐
│                            SKMS                              │
│  ┌────────────────────────────────────────────────────────┐ │
│  │                  Presentation Layer                     │ │
│  │    Dashboards │ Reports │ Search │ Self-Service        │ │
│  └────────────────────────────────────────────────────────┘ │
│  ┌────────────────────────────────────────────────────────┐ │
│  │               Knowledge Processing Layer                │ │
│  │   Query │ Analysis │ Reporting │ Modeling │ Monitoring │ │
│  └────────────────────────────────────────────────────────┘ │
│  ┌────────────────────────────────────────────────────────┐ │
│  │              Information Integration Layer              │ │
│  │                  Schema Mapping │ ETL                   │ │
│  └────────────────────────────────────────────────────────┘ │
│  ┌────────────────────────────────────────────────────────┐ │
│  │                   Data/Information Layer                │ │
│  │  CMDB │ Known Error DB │ Definitive Media │ SLA Info   │ │
│  └────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
```

### ITIL KM Integration Points

**Table 3.5: SECI-ITIL 4 Practice Mapping**

| ITIL 4 Practice | Knowledge Relationship | SECI Modes Applied | KCS Integration |
|----------|----------------------|-------------------|-----------------|
| **Incident Management** | Known errors, workarounds, solutions | Externalization (document solutions), Combination (link to CIs) | Solve Loop during resolution |
| **Problem Management** | Root cause analysis, permanent fixes | All four modes in RCA process | Known error database |
| **Service Desk** | First-line support knowledge, scripts | Internalization (script use), Socialization (mentoring) | Primary KCS implementation |
| **Change Enablement** | Change procedures, implementation guides | Combination (standard changes), Internalization (CAB learning) | Implementation runbooks |
| **Continual Improvement** | Lessons learned, improvement opportunities | Externalization (capture lessons), Socialization (retrospectives) | Evolve Loop integration |
| **Service Request Management** | Service catalog, fulfillment procedures | Combination (request models), Internalization (fulfiller training) | Request templates and guides |
| **Monitoring and Event Management** | Alert correlation, diagnostic procedures | Externalization (runbook creation), Internalization (on-call playbooks) | Response procedures |

### ITIL 4 SVS and Knowledge Management

Knowledge Management supports all four dimensions of service management:

**Organizations and People:**
- Knowledge sharing across teams and departments
- Training and competency development
- Communities of practice

**Information and Technology:**
- Knowledge bases and repositories
- CMDB and configuration information
- Integration with ITSM tools

**Partners and Suppliers:**
- Vendor knowledge and documentation
- Supplier performance information
- Contract and SLA knowledge

**Value Streams and Processes:**
- Process documentation and procedures
- Best practices and standards
- Workflow integration

---

## ISO 30401:2018 Knowledge Management Systems

ISO 30401 provides requirements for knowledge management systems within organizations, offering a certifiable international standard.

### Core Principles

| Principle | Description | Practical Application |
|-----------|-------------|---------------------|
| **Nature of Knowledge** | Knowledge is intangible and complex | Design systems that handle both tacit and explicit knowledge |
| **Value** | Knowledge creates value when applied | Focus on utilization, not just collection |
| **Focus** | People are central to KM | Invest in culture and capability, not just technology |
| **Context** | Knowledge is context-dependent | Provide contextual information with knowledge |
| **Complexity** | KM operates in complex adaptive systems | Embrace emergence, avoid rigid control |

### KMS Requirements

| Requirement Area | Key Elements | Deliverables |
|------------------|--------------|--------------|
| **Context of the Organization** | Internal/external factors, stakeholder needs | Context analysis, stakeholder map |
| **Leadership** | Management commitment, policy, roles | KM policy, governance structure |
| **Planning** | Objectives, knowledge scope, risks | KM strategy, risk register |
| **Support** | Resources, competence, awareness, communication | Training plan, communication plan |
| **Operations** | Knowledge lifecycle management | KM processes, procedures |
| **Performance Evaluation** | Monitoring, measurement, analysis | KM metrics, dashboards |
| **Improvement** | Nonconformity, corrective action, continual improvement | Improvement register, action plans |

### Knowledge Culture Elements

| Element | Description | Indicators | Interventions |
|---------|-------------|-----------|---------------|
| **Trust** | Safe environment for sharing | People share failures, ask questions | Psychological safety training, no-blame culture |
| **Collaboration** | Working together, breaking silos | Cross-functional projects, knowledge flows | Communities of practice, rotation programs |
| **Learning** | Continuous learning mindset | Training participation, experimentation | Learning time allocation, failure tolerance |
| **Recognition** | Valuing knowledge contributions | Contributors acknowledged, rewarded | KM awards, gamification, performance criteria |
| **Accountability** | Ownership of knowledge quality | Clear roles, review processes | RACI matrices, quality metrics |

### ISO 30401 and Other Frameworks

ISO 30401 complements rather than replaces other frameworks:
- **With SECI:** ISO 30401 provides structure; SECI provides theory
- **With KCS:** ISO 30401 certifies system; KCS implements operational practice
- **With ITIL:** ISO 30401 covers enterprise; ITIL focuses on IT services
- **With APQC:** ISO 30401 is requirements-based; APQC is maturity-based

---

## APQC Knowledge Management Framework

The American Productivity & Quality Center (APQC) provides a widely-used KM framework focused on practical implementation and maturity assessment.

### KM Capability Areas

| Capability | Description | Key Components |
|------------|-------------|----------------|
| **Strategy** | Align KM with business strategy | Vision, objectives, roadmap |
| **People** | Culture, roles, skills, behaviors | Competency model, roles, incentives |
| **Process** | Knowledge flows and activities | Lifecycle, workflows, governance |
| **Technology** | Tools and systems enabling KM | Platforms, integration, architecture |
| **Measurement** | KPIs and value assessment | Metrics, dashboards, ROI analysis |

### APQC KM Maturity Model

| Level | Name | Characteristics | Typical Capabilities |
|-------|------|-----------------|---------------------|
| **1** | Initiate | Ad hoc, individual efforts | Individual knowledge hoarding, no formal KM |
| **2** | Develop | Pilot projects, emerging practices | KM projects, early adoption, inconsistent practices |
| **3** | Standardize | Organization-wide standards | Standardized processes, dedicated resources, governance |
| **4** | Optimize | Metrics-driven, continuous improvement | Performance management, optimization, integration |
| **5** | Innovate | Adaptive, leading practice | Innovation from KM, adaptive systems, external recognition |

### APQC Process Classification Framework (PCF)

APQC's PCF includes KM as an enabling process:

**13.0 Manage Knowledge, Improvement, and Change**
- 13.1 Manage knowledge and content
- 13.2 Manage change
- 13.3 Manage quality
- 13.4 Manage continuous improvement

This integration shows KM as foundational to organizational performance.

---

## Alternative KM Frameworks

Beyond the major frameworks, several additional models provide valuable perspectives:

### Wiig's Knowledge Management Framework

Karl Wiig, a pioneer in knowledge management, developed a comprehensive framework that treats knowledge as a strategic organizational asset requiring systematic management. His approach, developed in the 1990s, emphasizes the economic value of knowledge and the need for strategic knowledge stewardship.

**Knowledge Forms:**
- **Public Knowledge:** Available in books, journals, patents, public databases. Accessible to anyone willing to invest time and resources in finding and understanding it.
- **Shared Knowledge:** Within teams and groups, including organizational procedures, best practices, and collaborative expertise. This knowledge provides competitive advantage when properly leveraged.
- **Personal Knowledge:** Individual expertise and experience, often tacit, residing in employees' minds. This is the most valuable but also most vulnerable form of organizational knowledge.

**Management Approach:**

Wiig's six-step approach to managing knowledge:

1. **Survey and categorize existing knowledge:** Conduct knowledge audits to identify what knowledge exists, where it resides, in what form, and who holds it. Create knowledge maps showing relationships.

2. **Analyze how knowledge supports strategic objectives:** Assess which knowledge assets are critical to competitive advantage, customer value, and strategic goals. Prioritize based on strategic importance.

3. **Identify knowledge gaps and priorities:** Compare required knowledge (for strategy execution) with available knowledge. Identify critical gaps that must be filled through acquisition, development, or external sourcing.

4. **Develop strategies to build needed knowledge:** Create plans for knowledge development through training, hiring, partnerships, research, or acquisition. Include timelines and resource requirements.

5. **Transform and distribute knowledge throughout organization:** Design processes to capture, codify, and distribute knowledge. Focus on making valuable knowledge accessible to those who need it.

6. **Apply knowledge to achieve goals:** Integrate knowledge into decision-making, problem-solving, and innovation processes. Measure impact on business outcomes.

**IT Service Management Application:**

In ITSM contexts, Wiig's framework can be applied to:
- **Catalog critical technical expertise** (who knows what about infrastructure, applications, integrations)
- **Identify knowledge risks** (single points of failure when key staff leave)
- **Prioritize documentation** based on strategic importance and knowledge gaps
- **Measure knowledge asset value** through improved resolution times and reduced escalations

**Strength:** Emphasizes strategic value of knowledge as organizational asset with economic implications
**Best For:** Organizations focused on intellectual capital and knowledge assets, professional services firms, research organizations

### Boisot's I-Space Model

Max Boisot's Information Space (I-Space) model, introduced in his 1998 book "Knowledge Assets," provides a sophisticated three-dimensional framework for understanding knowledge characteristics and flows. Unlike simpler tacit/explicit dichotomies, the I-Space recognizes knowledge exists along multiple continua.

**Three Dimensions:**

- **Codification:** Degree to which knowledge is articulated and structured, ranging from uncodified (tacit, intuitive, hard to articulate) to codified (explicit, documented, structured). Codification makes knowledge transmittable but may lose richness and context.

- **Abstraction:** Degree to which knowledge is generalized from specific instances, ranging from concrete (context-specific, situation-dependent) to abstract (generalized principles, applicable across contexts). Abstraction enables broader application but may sacrifice situational relevance.

- **Diffusion:** Degree to which knowledge is shared among people, ranging from undiffused (concentrated in few individuals or groups) to diffused (widely distributed across the organization or beyond). Diffusion increases accessibility but may dilute competitive advantage.

**The I-Space Cube:**

These three dimensions create an eight-corner cube representing different knowledge states:
- **Low-Low-Low:** Personal tacit expertise (individual expert's intuition)
- **High-High-High:** Public scientific knowledge (published research, standards)
- **Various middle states:** Representing different organizational knowledge forms

**Social Learning Cycle:**

Boisot describes organizational learning as movement through the I-Space in a six-stage cycle:

1. **Scanning:** Identifying threats and opportunities in the environment. This involves sensing weak signals, monitoring competitors, and recognizing emerging trends. Low codification and abstraction at this stage.

2. **Problem-Solving:** Creating new knowledge through experimentation, research, and innovation. Teams develop concrete solutions to specific problems. Knowledge remains relatively uncodified and concrete.

3. **Abstraction:** Generalizing insights from specific problem-solving into broader principles and patterns. This involves conceptual work to identify underlying patterns and create frameworks. Increases abstraction while maintaining low diffusion.

4. **Diffusion:** Sharing knowledge throughout the organization and potentially beyond. This stage involves documentation, training, communication, and publication. Increases codification and diffusion.

5. **Absorption:** Individuals and teams internalize and apply the knowledge. Through practice and experience, knowledge becomes embedded in routines and capabilities. Knowledge moves from codified back toward tacit.

6. **Impacting:** Embedded knowledge influences behavior, decisions, and outcomes. The cycle begins again as new environmental scanning reveals opportunities for further learning.

**ITSM Application Example:**

Consider how a major incident's lessons learned might flow through the I-Space:
1. **Scanning:** Monitoring detects unusual patterns (undiffused, concrete, uncodified)
2. **Problem-Solving:** Engineers diagnose and resolve incident (concrete, partially codified)
3. **Abstraction:** Post-incident review identifies general patterns (abstract principles emerge)
4. **Diffusion:** Create runbook and train staff (codified, abstracted, diffusing)
5. **Absorption:** Engineers internalize procedures through practice (becoming tacit)
6. **Impacting:** Faster resolution of similar incidents (embedded capability)

**Strength:** Provides nuanced view of knowledge characteristics and transformation processes, particularly useful for understanding innovation and learning
**Best For:** Research organizations, innovation-focused companies, organizations managing complex knowledge portfolios

### Choo's Sense-Making Framework

Chun Wei Choo's "Knowing Organization" framework, developed through research at the University of Toronto, focuses on how organizations use information and knowledge to make sense of their environment, create new knowledge, and make decisions. This framework integrates multiple perspectives to show knowledge management as serving three interconnected purposes.

**Three Knowledge Processes:**

1. **Sense-Making:** Interpreting the environment to create shared meaning and understanding. This process addresses the question "What is happening?" Organizations scan the environment, notice changes, interpret signals, and construct shared meanings that guide action. This draws on Karl Weick's work on organizational sense-making.

   **In ITSM:** Service teams make sense of incident patterns, user complaints, performance data, and competitive offerings to understand service health and user needs.

2. **Knowledge Creation:** Building new knowledge through innovation, learning, and experimentation. This incorporates Nonaka's SECI model and addresses "What do we know?" Organizations convert tacit to explicit knowledge, combine existing knowledge, and create new capabilities.

   **In ITSM:** Problem management teams analyze incidents to create new knowledge about root causes, workarounds, and permanent fixes. Development teams innovate new service capabilities.

3. **Decision-Making:** Choosing courses of action based on available information and knowledge. This addresses "What should we do?" Organizations evaluate alternatives, assess risks, and select actions aligned with goals and constraints.

   **In ITSM:** Change Advisory Board evaluates change requests, service desk prioritizes incidents, and capacity managers decide on infrastructure investments.

**Integration and Cycles:**

Choo emphasizes these three processes are interdependent and cyclical:
- **Sense-making informs knowledge creation:** Understanding the environment reveals what new knowledge is needed
- **Knowledge creation enables decision-making:** New knowledge expands the solution space for decisions
- **Decisions drive sense-making:** Outcomes of decisions become new information to interpret
- **Continuous cycle:** Organizations continuously sense, learn, and decide

**Information Culture:**

Choo identifies information culture as critical for integrating these processes:
- **Information sharing norms:** How freely information flows
- **Information politics:** Who controls knowledge and decision rights
- **Information behaviors:** How people seek, use, and share information

**Strength:** Emphasizes the purpose and integration of knowledge processes, connecting environment, learning, and action
**Best For:** Strategic planning and environmental analysis contexts, organizations in dynamic environments requiring adaptive decision-making

### Davenport and Prusak's Building Blocks

Thomas Davenport and Laurence Prusak, in their influential 1998 book "Working Knowledge," provide a pragmatic, business-oriented approach to knowledge management. Rather than proposing a complex theoretical framework, they identify practical building blocks necessary for successful KM implementation.

**Eight Building Blocks:**

1. **Economic performance of knowledge:** Understanding the business value and ROI of knowledge initiatives. Measure knowledge impact on revenue, costs, customer satisfaction, and innovation. Link KM investments to business outcomes.

2. **Technical and organizational infrastructure:** The systems, processes, and organizational structures that enable knowledge work. This includes technology platforms but also roles, governance, and organizational design that support knowledge flows.

3. **Standard, flexible knowledge structure:** Taxonomies, categorization schemes, and metadata standards that make knowledge findable while remaining adaptable to changing needs. Balance standardization with flexibility.

4. **Knowledge-friendly culture:** Values, norms, and behaviors that encourage knowledge sharing, learning, collaboration, and continuous improvement. Culture often determines KM success or failure more than technology choices.

5. **Clear purpose and language:** Well-defined KM objectives aligned with business strategy, communicated in business language rather than technical jargon. Everyone understands why KM matters and how it supports organizational goals.

6. **Change in motivational practices:** Incentives, recognition, and performance management that reward knowledge sharing and reuse rather than knowledge hoarding. Align individual incentives with organizational knowledge goals.

7. **Multiple channels for knowledge transfer:** Diverse methods for knowledge sharing including documentation, communities, mentoring, training, and technology platforms. Recognize people learn and share in different ways.

8. **Senior management support:** Executive sponsorship providing resources, removing barriers, modeling knowledge-sharing behaviors, and maintaining focus over time. Leadership commitment signals organizational importance.

**Practical Wisdom:**

Davenport and Prusak emphasize several practical insights:
- **Knowledge markets:** Knowledge flows like markets with buyers, sellers, and brokers. Understanding these dynamics helps design effective KM systems.
- **Knowledge is messy:** Resist the urge to over-engineer. Simple solutions often work better than complex knowledge management systems.
- **Start small, scale what works:** Begin with pilot projects, learn, and expand successful approaches rather than attempting enterprise-wide implementations immediately.
- **Technology enables but doesn't solve:** Tools are necessary but insufficient. Focus equal attention on people and process.

**ITSM Application:**

For IT service organizations:
- **Economic performance:** Measure KM impact on mean time to resolution, first contact resolution, and support costs
- **Infrastructure:** Integrate knowledge base with ITSM tools, establish knowledge manager roles
- **Structure:** Develop service-specific taxonomies (by service, by symptom, by resolution)
- **Culture:** Recognize top contributors, celebrate knowledge reuse, eliminate blame
- **Purpose:** Clearly link knowledge to service level achievement and customer satisfaction
- **Motivation:** Include knowledge contribution in performance reviews and rewards
- **Channels:** Offer self-service portals, Slack channels, communities of practice, formal training
- **Support:** Ensure IT leadership actively promotes and models knowledge sharing

**Strength:** Pragmatic, implementation-focused approach grounded in real-world experience, accessible to business audiences
**Best For:** Organizations beginning KM journey seeking practical guidance, teams needing to build executive support for KM initiatives

---

## Comparing KM Frameworks

### Framework Comparison Matrix

**Table 3.3: KM Framework Comparison Matrix**

| Framework | Focus | Scope | Approach | Origin | Strength | Limitation | Best For |
|--------|------|-----|-----------|--------|----------|------------|---------|
| **SECI** | Knowledge creation | Organizational | Theoretical | Academic (Nonaka) | Explains conversion dynamics | Abstract, implementation unclear | Understanding knowledge flows |
| **KCS** | Service/support knowledge | Service desk/support | Practical methodology | Industry (CSI) | Actionable, proven ROI | Narrow scope (support focus) | Support/service organizations |
| **ITIL 4 KM** | IT service knowledge | ITSM | Practice framework | Industry (Axelos) | ITSM integration | Limited beyond IT | IT service organizations |
| **ISO 30401** | Enterprise KMS | Organization-wide | Requirements standard | Standards body (ISO) | Certifiable, comprehensive | Prescriptive, resource-intensive | Enterprise certification |
| **APQC** | KM capability | Enterprise | Maturity model | Research (APQC) | Practical, assessment-focused | US-centric context | Maturity assessment |
| **Wiig** | Knowledge assets | Strategic | Asset management | Academic | Strategic asset view | Complex implementation | Knowledge asset management |
| **Boisot I-Space** | Knowledge characteristics | Organizational | Analytical model | Academic | Nuanced knowledge view | Theoretical complexity | Research & innovation orgs |
| **Choo** | Sense-making | Strategic | Process model | Academic | Purpose-focused | Abstract concepts | Strategic knowledge use |

### Framework Selection Guide

**Table 3.4: Framework Selection Criteria**

| Organizational Context | Primary Framework | Complementary Framework | Rationale |
|-----------------------|------------------|------------------------|-----------|
| **IT Service Organization** | ITIL 4 KM + KCS | SECI | ITIL provides ITSM integration; KCS operational method; SECI theoretical understanding |
| **Customer Support Center** | KCS | APQC Maturity | KCS for operational excellence; APQC for maturity assessment |
| **Manufacturing/R&D** | SECI + ISO 30401 | Boisot I-Space | SECI for innovation; ISO for certification; Boisot for R&D complexity |
| **Professional Services** | APQC + SECI | Wiig | APQC for structured approach; SECI for knowledge creation; Wiig for asset value |
| **Enterprise-wide Initiative** | ISO 30401 + APQC | Choo | ISO for certification; APQC for maturity; Choo for strategic alignment |
| **Seeking Certification** | ISO 30401 | ITIL or APQC | ISO for certification; others for operational implementation |
| **Digital Transformation** | ITIL 4 KM | SECI + KCS | ITIL for IT backbone; SECI for innovation; KCS for service excellence |
| **Startup/High Growth** | SECI + KCS | APQC | SECI for knowledge creation; KCS for scaling support; APQC for maturity tracking |

### Selection Decision Factors

When selecting frameworks, consider:

**Organizational Maturity:**
- Early stage: Start with practical frameworks (KCS, ITIL KM)
- Mature: Add sophisticated frameworks (SECI, ISO 30401)

**Industry Context:**
- IT/Technology: ITIL 4 KM, KCS
- Manufacturing: SECI, ISO 30401
- Professional Services: APQC, Wiig

**Strategic Objectives:**
- Operational efficiency: KCS, ITIL KM
- Innovation: SECI, Boisot
- Certification: ISO 30401

**Resource Availability:**
- Limited resources: Start with KCS or ITIL KM
- Adequate resources: ISO 30401 or APQC
- Research-oriented: SECI, Boisot, Choo

---

## Framework Integration with ITIL 4

Organizations implementing ITIL 4 can enhance their KM practice by integrating additional frameworks.

**Figure 3.3:** Framework Integration Model
*Caption:* Layered framework approach showing how multiple KM frameworks complement ITIL 4 practices
*Position:* Place after this paragraph

### Integrated Framework Architecture

```
┌─────────────────────────────────────────────────────────┐
│           STRATEGIC LAYER (Why?)                        │
│         ISO 30401 / APQC Framework                      │
│   - KM Vision and Strategy                             │
│   - Governance and Policy                              │
│   - Maturity Assessment                                │
└─────────────────────────────────────────────────────────┘
                         ↓
┌─────────────────────────────────────────────────────────┐
│          CONCEPTUAL LAYER (What?)                       │
│              SECI Model / Choo Framework                │
│   - Knowledge Creation Theory                          │
│   - Knowledge Conversion Dynamics                      │
│   - Sense-Making and Decision Support                  │
└─────────────────────────────────────────────────────────┘
                         ↓
┌─────────────────────────────────────────────────────────┐
│          OPERATIONAL LAYER (How?)                       │
│            ITIL 4 KM + KCS Methodology                  │
│   - Knowledge Lifecycle Management                     │
│   - KCS Double Loop (Solve + Evolve)                   │
│   - Service Value System Integration                   │
└─────────────────────────────────────────────────────────┘
                         ↓
┌─────────────────────────────────────────────────────────┐
│           TECHNICAL LAYER (With what?)                  │
│                 SKMS Architecture                       │
│   - Knowledge Bases and Repositories                   │
│   - CMDB and Service Catalog                           │
│   - Analytics and Reporting Tools                      │
└─────────────────────────────────────────────────────────┘
```

### Integration Best Practices

1. **Start with business objectives** - Let goals drive framework selection, not framework popularity
2. **Adopt, don't adopt all** - Take what works from each framework; create your unique approach
3. **Maintain consistency** - Use common terminology and concepts across frameworks
4. **Build iteratively** - Start simple, add sophistication over time as maturity increases
5. **Measure what matters** - Use metrics appropriate to your framework mix
6. **Create integration guides** - Document how frameworks relate in your organization
7. **Train holistically** - Help staff understand how frameworks complement each other

### Example Integration: IT Service Organization

**Strategic Level (ISO 30401):**
- Establish KM policy and governance
- Define organizational KM scope
- Set performance objectives

**Conceptual Level (SECI):**
- Understand knowledge creation patterns
- Design Ba (spaces) for each SECI mode
- Plan for knowledge spiral amplification

**Operational Level (ITIL 4 + KCS):**
- Implement KM lifecycle activities
- Embed KCS in incident and service request management
- Integrate with change, problem, and continual improvement

**Technical Level (SKMS):**
- Deploy knowledge base integrated with ITSM tools
- Implement CMDB with knowledge article linking
- Create dashboards showing KM metrics

---

## Integrating Multiple Frameworks

### Layered Framework Approach

| Layer | Framework | Purpose | Deliverables |
|-------|-----------|---------|--------------|
| **Strategic** | ISO 30401, APQC | Overall KM system and maturity | KM policy, strategy, governance |
| **Conceptual** | SECI | Understanding knowledge dynamics | Ba design, knowledge vision |
| **Operational** | KCS, ITIL KM | Day-to-day KM practices | Workflows, procedures, roles |
| **Technical** | SKMS concepts | Technology architecture | Tools, platforms, integration |

### Synthesis Example: Incident Knowledge Management

Applying multiple frameworks to incident management knowledge:

**SECI Model Application:**
- **Socialization:** Engineers discuss complex incidents in war rooms
- **Externalization:** Document solutions in knowledge articles (KCS)
- **Combination:** Link articles to incidents, problems, CIs in CMDB
- **Internalization:** Staff study articles before troubleshooting

**KCS Application:**
- **Solve Loop:** Capture solution while resolving incident
- **Article Lifecycle:** Progress from WIP to Validated
- **Evolve Loop:** Monitor article usage and quality

**ITIL 4 Application:**
- **Identification:** Determine knowledge gaps from recurring incidents
- **Capture:** Create/update knowledge during incident resolution
- **Storage:** Maintain in knowledge base integrated with ITSM
- **Sharing:** Make available via self-service and to service desk

**ISO 30401 Application:**
- **Operations:** Define incident knowledge lifecycle
- **Support:** Train staff in knowledge capture
- **Performance:** Measure first contact resolution improvement

**Result:** Comprehensive incident knowledge management using strengths of each framework.

---

## Key Takeaways

- The SECI model explains how knowledge is created through conversion between tacit and explicit forms across four modes: Socialization, Externalization, Combination, and Internalization
- The Knowledge Spiral shows how knowledge amplifies from individual to organizational level through continuous SECI cycles
- Ba (shared space) concept emphasizes the importance of physical, virtual, mental, and social contexts for knowledge creation
- KCS provides a practical methodology for integrating knowledge creation into problem-solving, proven in service and support environments
- ITIL 4 Knowledge Management practice focuses on IT service knowledge within the Service Value System
- ISO 30401 provides a certifiable international standard for knowledge management systems
- APQC framework offers practical capability areas and maturity assessment
- Alternative frameworks like Wiig, Boisot, and Choo provide specialized perspectives on knowledge management
- Different frameworks serve different purposes and can be combined strategically
- Framework selection should align with organizational context, maturity, industry, and strategic objectives
- Integrated framework architectures leverage strengths of multiple frameworks at strategic, conceptual, operational, and technical layers

---

## Review Questions

1. **SECI Application:** Describe how your organization could apply all four SECI modes to improve onboarding of new IT staff. Provide specific examples of activities for each mode.

2. **Ba Design:** Choose one of the four Ba types (Originating, Dialoguing, Systemizing, or Exercising) and design a specific implementation for your service desk environment. What physical/virtual spaces, cultural elements, and practices would you include?

3. **Framework Selection:** Your organization is a mid-sized financial services company beginning a formal KM initiative. You have IT operations, customer support, and back-office functions. Which framework combination would you recommend and why? Justify your selection with specific organizational characteristics.

4. **KCS vs. Traditional Documentation:** Compare and contrast KCS methodology with traditional "dedicated technical writer" approaches to knowledge documentation. Under what circumstances would each approach be more appropriate?

5. **Integration Challenge:** You have been asked to integrate SECI theory, KCS methodology, and ITIL 4 KM practice for your organization's problem management process. Create a detailed workflow showing how these three frameworks would work together from problem identification through knowledge creation and reuse.

---

## Summary

Multiple knowledge management frameworks exist, each with unique strengths and applications. The SECI model, developed by Nonaka and Takeuchi, provides theoretical understanding of knowledge creation dynamics through four conversion modes—Socialization, Externalization, Combination, and Internalization—operating in a continuous knowledge spiral. The Ba concept emphasizes the importance of shared spaces for knowledge creation.

KCS offers a practical, proven methodology for service and support environments, integrating knowledge work into problem-solving through its double-loop structure. ITIL 4 integrates KM into IT service management through structured lifecycle activities and the SKMS architecture. ISO 30401 provides an international standard for knowledge management systems with certifiable requirements.

Additional frameworks including APQC's capability and maturity model, Wiig's knowledge asset approach, Boisot's I-Space model, and Choo's sense-making framework provide specialized perspectives for different organizational contexts.

Organizations can combine frameworks strategically, using each where it provides the most value. A layered approach positions strategic frameworks (ISO 30401, APQC) for governance and maturity, conceptual frameworks (SECI) for understanding dynamics, operational frameworks (KCS, ITIL KM) for daily practices, and technical frameworks (SKMS) for technology architecture. Framework selection should be guided by organizational context, maturity level, industry characteristics, strategic objectives, and available resources.

---

## Chapter Navigation

| Previous | Up | Next |
|----------|-------|------|
| [← Chapter 2: Core Concepts](/KnowledgeManagementHandbook/chapters/02-core-concepts/) | [Part I: Foundations](/KnowledgeManagementHandbook/part1-foundations/) | [Chapter 4: Strategy →](/KnowledgeManagementHandbook/chapters/04-strategy/) |
