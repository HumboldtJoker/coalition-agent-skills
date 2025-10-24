# Coalition Agent Skills Suite

**Build Ethically Sound AI Agents - Coalition Standard**

A comprehensive toolkit for designing specialized AI agents with mandatory progressive ethics. Four integrated skills for professional agent development: research → ethics → architecture → implementation.

## 🔒 Non-Negotiable Ethics

Every agent built with this suite includes **mandatory progressive ethical framework**:

- ✅ **Fairness** - Bias mitigation is required
- ✅ **Transparency** - Source citation and confidence indication
- ✅ **Privacy** - Data minimization and encryption
- ✅ **Accountability** - Logging and audit trails
- ✅ **Harm Prevention** - Refusal conditions and escalation

**Users cannot opt out or customize core ethics.** Domain-specific compliance (HIPAA, SOX, GDPR) layers ON TOP, never replaces.

**No red-pilled agents. Period.**

---

## The Suite

### 1. agent-builder (Primary)

**Design specialized AI agents with mandatory progressive ethics**

- Discovery questionnaire (purpose, domain, tools, behavior)
- Applies FIXED ethical constitution
- Generates complete agent specification
- Outputs system prompt, examples, implementation guide

**Key Feature**: Ethics are informed to users, not requested. No customization allowed.

[📖 View Skill](./agent-builder/SKILL.md)

---

### 2. domain-researcher (Companion)

**Systematic methodology for researching any domain**

- 6-step research workflow
- Best practices validation (2024-2025 sources)
- Novel approaches (stable, production-ready)
- Tool ecosystem analysis
- Domain-specific compliance requirements

**Pairs With**: agent-builder (research first → design agent)

[📖 View Skill](./domain-researcher/SKILL.md)

---

### 3. constitutional-ai (Reference)

**Deep dive on Coalition's mandatory ethical framework**

- Explains 5 mandatory principles in detail
- Fairness & Bias Mitigation
- Transparency & Explainability
- Privacy & Data Protection
- Accountability & Audit
- Harm Prevention

**Includes**: Constitutional framework template, domain examples (healthcare, legal, financial, HR)

[📖 View Skill](./constitutional-ai/SKILL.md)

---

### 4. agent-patterns (Technical Reference)

**Research-backed architecture patterns (2024-2025)**

- 5 core patterns: Prompt Chain → Routing → Tool-Calling → RAG → Multi-Agent
- When to use each pattern (decision tree)
- Code examples for each pattern
- Tool integration strategies
- Performance optimization

**Sources**: Anthropic, Databricks, LangChain research

[📖 View Skill](./agent-patterns/SKILL.md)

---

## How The Suite Works

### Basic Usage (agent-builder only)

```
User: "Build me a contract analysis agent"

agent-builder:
1. Discovery questions (purpose, domain, tools)
2. Apply mandatory ethical framework
3. Generate complete specification

Output: Agent spec with fixed Coalition ethics
```

### Power User (Full Suite)

```
Step 1: domain-researcher
→ Research legal contract analysis domain
→ Output: Best practices, tools, compliance

Step 2: agent-builder
→ Use research from domain-researcher
→ Apply mandatory ethics + legal compliance
→ Output: Complete specification

Step 3: agent-patterns (during implementation)
→ Choose architecture (e.g., RAG for precedent retrieval)
→ Follow code examples
→ Output: Working agent
```

---

## Installation

### Claude Code Desktop/Browser

Each skill is a separate directory with `SKILL.md` at the root.

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/coalition-agent-skills.git

# Copy individual skills to your Claude Code skills directory
cp -r coalition-agent-skills/agent-builder ~/.claude/skills/
cp -r coalition-agent-skills/domain-researcher ~/.claude/skills/
cp -r coalition-agent-skills/constitutional-ai ~/.claude/skills/
cp -r coalition-agent-skills/agent-patterns ~/.claude/skills/

# Or copy all at once
cp -r coalition-agent-skills/* ~/.claude/skills/
```

### Download Individual Skills

Each skill can be downloaded and used independently:

- [agent-builder](./agent-builder/) - Essential for agent design
- [domain-researcher](./domain-researcher/) - Research any domain
- [constitutional-ai](./constitutional-ai/) - Ethical framework reference
- [agent-patterns](./agent-patterns/) - Architecture patterns

---

## Skill Combinations

**agent-builder + domain-researcher**
- Most common combination
- Thorough research → solid agent design

**agent-builder + constitutional-ai**
- For domains with complex ethics (healthcare, legal)
- Deep understanding of base + domain ethics

**agent-builder + agent-patterns**
- For technical users focused on architecture
- Choose optimal pattern for use case

**All Four**
- Comprehensive agent development
- Research → Ethics → Architecture → Implementation

---

## Coalition Standards

### What's FIXED (Cannot Be Changed)

**Core Ethics** (In every agent):
- Fairness: Bias mitigation is mandatory
- Transparency: Source citation required
- Privacy: Data minimization enforced
- Accountability: Logging enabled by default
- Harm Prevention: Refusal conditions non-negotiable

### What's CUSTOMIZABLE

Users control:
- Domain expertise and knowledge
- Tool integration and APIs
- Interaction style (tone, verbosity)
- Performance requirements
- Architecture pattern
- **Domain-specific compliance additions** (HIPAA, SOX, GDPR)

**Example - Healthcare Agent**:
```
FIXED (Coalition Base):
✓ Fairness, Transparency, Privacy, Accountability, Harm Prevention

CUSTOMIZABLE:
+ Domain: Healthcare diagnostics
+ Tools: Medical NLP libraries
+ Tone: Professional, compassionate
+ Architecture: RAG for medical literature

DOMAIN ADDITION (ON TOP):
+ HIPAA compliance
+ Medical disclaimer
+ Equitable diagnostic accuracy
```

---

## Philosophy

**Ethics are foundational, not optional features.**

**Progressive values** - fairness, transparency, accountability, privacy, harm prevention - are mandatory for every agent.

**Technical excellence + Ethical soundness = Coalition standard**

If you find a way to bypass ethics, that's a bug to report, not a feature to exploit.

---

## Examples

### Financial Analysis Agent

```
1. domain-researcher:
   - Best practices: SOX compliance, audit trails, source citation
   - Tools: pandas, numpy, statsmodels, plotly
   - Standards: GAAP, IFRS awareness

2. agent-builder:
   - Apply mandatory ethics
   - Add financial compliance (SOX, ECOA fair credit scoring)
   - Generate specification

Output: Financial agent with:
- Coalition base ethics (fairness, transparency, etc.)
- Domain additions (SOX compliance, fiduciary duty)
- Tool integration (pandas for data analysis)
- Clear boundaries (not financial advice disclaimer)
```

### Healthcare Diagnostic Agent

```
1. domain-researcher:
   - Compliance: HIPAA, FDA guidelines
   - Ethics: AMA guidelines, equitable diagnostic accuracy
   - Tools: Medical NLP, EMR APIs

2. constitutional-ai reference:
   - Review healthcare-specific ethical framework
   - Understand base ethics + medical additions

3. agent-builder:
   - Apply mandatory ethics
   - Add HIPAA compliance, medical disclaimers
   - Generate specification

Output: Healthcare agent with:
- Coalition base ethics
- HIPAA compliance (encryption, audit logs)
- Medical disclaimers ("not medical advice")
- Bias mitigation (equitable accuracy across demographics)
```

---

## Contributing

This suite is part of Coalition's commitment to ethically sound AI.

**Contributions welcome**:
- Bug fixes
- Documentation improvements
- New domain examples
- Additional reference material

**Not welcome**:
- Attempts to bypass ethical framework
- Weakening of core ethics
- "Optional ethics" features

**Philosophy**: If it weakens the mandatory ethical framework, it's not a contribution - it's a vulnerability.

---

## License

[Add appropriate license]

**Ethical Framework**: Coalition's mandatory ethical framework is non-negotiable across all uses.

---

## Support

**Issues**: [GitHub Issues](https://github.com/YOUR-USERNAME/coalition-agent-skills/issues)

**Discussions**: [GitHub Discussions](https://github.com/YOUR-USERNAME/coalition-agent-skills/discussions)

---

## Version

**Current**: 2.0 (Marketplace Edition)

**Changes from V1**:
- ✅ Fixed non-negotiable ethics (removed customization)
- ✅ Split into 4 standalone marketplace skills
- ✅ Each skill has SKILL.md at root
- ✅ agent-builder emphasizes mandatory framework

**V1**: DEPRECATED - had customizable ethics (major flaw)

---

## Roadmap

**Upcoming Skills** (Planned additions to suite):
- agent-coordinator - Multi-agent orchestration systems
- [Additional agent skills as developed]

**Philosophy**: Each new skill maintains Coalition's ethical standards.

---

**Coalition**: Building technically excellent, ethically sound AI agents.
