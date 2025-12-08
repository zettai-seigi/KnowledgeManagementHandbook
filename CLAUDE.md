# Claude Code Project Instructions

## Project Overview

This is the **Knowledge Management Handbook** - a comprehensive guide to enterprise and ITSM Knowledge Management published on GitHub Pages.

- **URL:** https://zettai-seigi.github.io/KnowledgeManagementHandbook/
- **Repository:** https://github.com/zettai-seigi/KnowledgeManagementHandbook
- **Theme:** Jekyll with Just the Docs
- **License:** MIT

## Project Structure

```
KnowledgeManagementHandbook/
├── docs/                    # GitHub Pages content (MAIN CONTENT)
│   ├── _config.yml         # Jekyll configuration
│   ├── index.md            # Home page
│   ├── table-of-contents.md # Full TOC
│   ├── part1-foundations.md # Part overview pages
│   ├── part2-architecture.md
│   ├── part3-operations.md
│   ├── part4-itsm.md
│   ├── part5-governance.md
│   ├── part6-implementation.md
│   ├── chapters/           # All 24 chapters
│   └── assets/images/      # Published images
├── README.md               # Repository documentation
├── LICENSE                 # MIT License
├── CLAUDE.md               # This file
└── .gitignore              # Git ignore rules
```

## Key Framework Elements

### DIKW Hierarchy
- **Data** - Raw facts without context
- **Information** - Data with context and meaning
- **Knowledge** - Information with experience applied
- **Wisdom** - Knowledge applied with judgment

### SECI Model (Knowledge Conversion)
- **Socialization** - Tacit to Tacit (shared experience)
- **Externalization** - Tacit to Explicit (documentation)
- **Combination** - Explicit to Explicit (systemization)
- **Internalization** - Explicit to Tacit (learning by doing)

### Knowledge Types
- **Tacit** - Personal, experiential, hard to articulate
- **Explicit** - Documented, codified, shareable
- **Implicit** - Articulable but undocumented
- **Embedded** - Built into processes and systems

### 8 Critical Success Factors (CSFs)
1. Executive Sponsorship and Vision (Leadership)
2. Knowledge-Sharing Culture (Culture)
3. Clear Governance and Ownership (Governance)
4. Quality Content and Curation (Content)
5. Intuitive Tools and Systems (Technology)
6. Integration with Work Processes (Process)
7. Recognition and Incentives (People)
8. Continuous Measurement and Improvement (Metrics)

### 6 Key Performance Indicators (KPIs)
1. Knowledge Article Usage Rate (target: ≥70%)
2. First Contact Resolution (target: ≥75%)
3. Article Quality Score (target: ≥4.0/5.0)
4. Knowledge Contribution Rate (target: ≥80%)
5. Search Success Rate (target: ≥85%)
6. Time to Resolution Improvement (target: ≥30%)

### 5 Maturity Levels
1. Initial (Ad-hoc)
2. Developing (Emerging practices)
3. Defined (Standardized)
4. Managed (Metrics-driven)
5. Optimizing (Continuous improvement)

## Content Guidelines

### Chapter Structure
Each chapter should include:
1. YAML frontmatter with layout, title, parent, nav_order, permalink
2. Learning Objectives section
3. Main content with ## and ### headings
4. Tables for structured data
5. Practical examples
6. Key Takeaways (bullet points)
7. Summary paragraph
8. Chapter Navigation links

### Writing Style
- Professional, instructional tone
- Consistent ITIL and KM terminology
- Cross-reference other chapters where relevant
- Use real-world examples
- Target 2000-4000 words per chapter

### Image Placeholders
When images are needed but not yet created, use:
```
**Figure X.X:** [Title]
*Caption:* [Description]
*Position:* [Placement guidance]
```

## Common Tasks

### Editing Chapters
- Chapter files are in `docs/chapters/`
- Use Edit tool for precise changes
- Maintain consistent formatting

### Adding Images
- Place in `docs/assets/images/`
- Reference with `../assets/images/filename.png`

### Git Operations
```bash
git add .
git commit -m "Description"
git push origin main
```

## Important Notes

- Always maintain DIKW and SECI model consistency across chapters
- The book is for GitHub Pages - don't create files that break Jekyll
- When editing, verify cross-references remain accurate
- CSF numbering should be consistent (1-8)
- KPI definitions must match across chapters
- KCS methodology details should be consistent throughout
