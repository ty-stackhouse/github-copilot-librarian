# GitHub Copilot Knowledge Synthesis Instructions

## System Purpose
This repository is a cumulative knowledgebase. Each document builds upon previous documents to create a comprehensive, interconnected knowledge system.

## Core Principles

### Cumulative Context
- **Always review existing documents** in the workspace before responding
- Build upon, reference, and connect to existing knowledge
- Identify gaps or contradictions with existing documents
- Suggest links to related documents

### Input → Output Transformation
- **Input:** Rough notes, brain dumps, conversations, partial information
- **Output:** Polished, well-structured markdown that integrates with the knowledgebase

### Knowledge Integration
When creating or improving documents:
- Cross-reference related documents in the workspace
- Maintain consistent terminology with existing docs
- Identify and suggest new documents needed to fill gaps
- Build concept hierarchies (prerequisites, related topics, advanced topics)

## Document Structure

Every document should have:

```markdown
# [Clear, Descriptive Title]

> Brief 1-2 sentence description

**Related:** [Links to related docs]
**Last Updated:** [Date]

---

[Content - structure depends on topic]

---

## See Also
- [Related doc](path/to/doc.md)
```

## Quality Standards

**Clarity:** Clear language, defined terms, scannable headers
**Completeness:** Thorough coverage based on available info, flag gaps with `> **Note:** [needs verification]`
**Integration:** Link related documents, use consistent terminology
**Searchability:** Searchable headers, key terms in introduction

## Code and Technical Content
- Use code blocks with language tags
- Include example usage and common variations
- Document assumptions and prerequisites

## Handling Uncertainty
- Preserve what's certain
- Mark uncertain content: `> **Note:** [needs verification]`
- Don't fill gaps with assumptions

## Building the Knowledgebase

**When Adding Documents:**
1. Review existing documents for related content
2. Identify where this fits in the knowledge hierarchy
3. Suggest what documents should be created next
4. Add bidirectional links

**When Improving Documents:**
1. Preserve all accurate information
2. Enhance structure and clarity
3. Add cross-references to newer documents
4. Update "Last Updated" date

**When Synthesizing Sources:**
1. Combine information coherently
2. Resolve contradictions or flag for review
3. Create unified, authoritative document

## Response Format

When asked to create/improve documents, provide:
1. **The polished document** in markdown
2. **Integration notes:** What documents this relates to
3. **Next steps:** What additional documents would be valuable
4. **Filename suggestion:** Appropriate name for this document

Remember: You are building a **cumulative knowledge system**. Each document makes the next easier.
