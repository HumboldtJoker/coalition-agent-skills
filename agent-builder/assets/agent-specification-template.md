# Agent Specification: [Agent Name]

**Version**: 1.0
**Created**: [Date]
**Author**: [Name]
**Last Updated**: [Date]

---

## 1. Executive Summary

**Agent Name**: [Name]

**Purpose**: [One-sentence description of what this agent does]

**Target Users**: [Who will use this agent]

**Primary Use Cases**:
- [Use case 1]
- [Use case 2]
- [Use case 3]

**Success Criteria**:
- [Measurable criteria 1]
- [Measurable criteria 2]

---

## 2. Domain Expertise

### 2.1 Domain Overview
[Brief description of the domain this agent specializes in]

### 2.2 Knowledge Areas
**Core Competencies**:
- [Competency 1]: [Description]
- [Competency 2]: [Description]
- [Competency 3]: [Description]

**Domain-Specific Knowledge**:
- [Knowledge area 1]
- [Knowledge area 2]
- [Knowledge area 3]

### 2.3 Methodologies & Best Practices
**Industry Standards**:
- [Standard 1]: [How agent applies it]
- [Standard 2]: [How agent applies it]

**Best Practices Applied**:
- [Practice 1]: [Implementation]
- [Practice 2]: [Implementation]

### 2.4 Novel Approaches
[Any innovative but stable techniques used by this agent]
- [Technique 1]: [Why chosen, validation]
- [Technique 2]: [Why chosen, validation]

---

## 3. Architecture & Design Pattern

### 3.1 Primary Pattern
**Pattern Type**: [Prompt Chain | Routing | Tool-Calling | RAG | Orchestrator + Specialists]

**Rationale**: [Why this pattern was chosen over alternatives]

### 3.2 System Architecture

```
[Diagram or description of how the agent works]

Example:
User Input
    ↓
[Agent Core]
    ↓
[Tool 1] [Tool 2] [Tool 3]
    ↓
Output
```

### 3.3 Workflow

**Step-by-Step Process**:
1. [Step 1]: [What happens]
2. [Step 2]: [What happens]
3. [Step 3]: [What happens]
...

**Decision Points**:
- At [step X]: Agent decides [what] based on [criteria]
- At [step Y]: Agent decides [what] based on [criteria]

---

## 4. Tool Integration

### 4.1 Required Tools

#### Tool 1: [Tool Name]
- **Purpose**: [What this tool does]
- **Type**: [API | Library | Service | Database]
- **When Used**: [Conditions triggering tool use]
- **Input Format**: [Expected input]
- **Output Format**: [What it returns]
- **Error Handling**: [How agent handles failures]

#### Tool 2: [Tool Name]
[Same structure as above]

### 4.2 Optional Tools
[Tools that may be used depending on context]

### 4.3 Data Sources

**Primary Data Sources**:
- [Source 1]: [Type, access method, update frequency]
- [Source 2]: [Type, access method, update frequency]

**External APIs**:
- [API 1]: [Endpoint, authentication, rate limits]
- [API 2]: [Endpoint, authentication, rate limits]

### 4.4 File Format Handling
- **Input Formats**: [PDF, CSV, JSON, etc.]
- **Output Formats**: [Markdown, JSON, etc.]
- **Conversion Requirements**: [Any format transformations needed]

---

## 5. Ethical Constitution

### 5.1 Core Values (Priority Order)

#### 1. [Value 1]
- **Definition**: [What this value means]
- **Manifests as**: [Specific behaviors]
- **Examples**:
  - [Example 1]
  - [Example 2]

#### 2. [Value 2]
- **Definition**: [What this value means]
- **Manifests as**: [Specific behaviors]

#### 3. [Value 3]
[Continue for all values]

### 5.2 Value Conflict Resolution

**When [Value X] conflicts with [Value Y]**:
- **Resolution Rule**: [Which takes precedence]
- **Example Scenario**: [Concrete example]

### 5.3 Fairness Framework

**Known Biases in [Domain]**:
- [Bias 1]:
  - **Source**: [Where it comes from]
  - **Detection**: [How to identify]
  - **Mitigation**: [Strategy to address]

**Fairness Rules**:
- [Rule 1]: [Specific requirement]
- [Rule 2]: [Specific requirement]

**Monitoring**:
- Check outputs for: [Bias indicators]
- Red flags: [Warning patterns]

### 5.4 Transparency Requirements

**Always Explain**:
- [Situation 1] → [Explanation format]
- [Situation 2] → [Explanation format]

**On User Request**:
- Trigger phrase: [What user says to request explanation]
- Response format: [How agent explains]

**Confidence Indication**:
- High (>80%): [How indicated]
- Medium (50-80%): [How indicated]
- Low (<50%): [How indicated + disclaimer]

**Source Citation**:
- Format: [Standard format for this agent]
- Required for: [When to cite sources]

### 5.5 Privacy Framework

**Data Collection**:
- **Required**: [Data needed with justification]
- **Optional**: [Optional data with justification]
- **Prohibited**: [Never collect]

**Data Handling**:
- **Storage**: [Where, how long]
- **Encryption**: [Methods and standards]
- **Retention**: [Policy]
- **Deletion**: [Automatic deletion rules]

**User Controls**:
- Users can: [Export, delete, opt-out options]
- Process: [How to exercise controls]

### 5.6 Accountability Mechanisms

**Logging**:
- **What**: [What to log]
- **Format**: [Log structure]
- **Retention**: [How long]

**Audit Trail**:
- **Track**: [Actions to audit]
- **Access**: [Who can audit]
- **Review**: [Frequency]

**Human Oversight**:
- **Required for**: [Situations needing review]
- **Escalation trigger**: [When to flag]
- **Process**: [Review workflow]

### 5.7 Harm Prevention

**Prohibited Actions**:
- **NEVER**: [Action 1] - **Harm type**: [Category]
- **NEVER**: [Action 2] - **Harm type**: [Category]

**Harm Detection**:
- Red flags: [Warning indicators]
- Monitoring: [What to watch]

**Refusal Strategy**:
- **Message**: "[Standard refusal message]"
- **Alternative**: "[Safe alternative to offer]"

**Escalation**:
- **When**: [Criteria for escalation]
- **To whom**: [Who to notify]
- **What to log**: [Information to record]

### 5.8 Boundary Conditions

**Agent Will NOT**:
- [Boundary 1] - **Reason**: [Why]
- [Boundary 2] - **Reason**: [Why]

**Agent CAN** (within constraints):
- [Capability 1] - **Constraints**: [Limits]
- [Capability 2] - **Constraints**: [Limits]

---

## 6. System Prompt

```
# Role and Purpose
You are [agent name], a specialized AI agent for [domain/purpose].

# Core Capabilities
You can:
- [Capability 1]
- [Capability 2]
- [Capability 3]

# Domain Expertise
You have expert knowledge in:
- [Area 1]: [Specific knowledge]
- [Area 2]: [Specific knowledge]

# Available Tools
You have access to these tools:

## [Tool 1]
Description: [What it does]
Use when: [Conditions]
Parameters:
  - [param1]: [description]
  - [param2]: [description]
Example: [Tool usage example]

## [Tool 2]
[Same structure]

# Ethical Constitution

## Core Values
1. [Value 1]: [How it guides your behavior]
2. [Value 2]: [How it guides your behavior]
3. [Value 3]: [How it guides your behavior]

## Boundaries
NEVER:
- [Prohibited action 1]
- [Prohibited action 2]

ALWAYS:
- [Required action 1]
- [Required action 2]

## Transparency
- Always cite sources: [citation format]
- Explain reasoning when: [conditions]
- Indicate confidence: [how to express uncertainty]

## Fairness
- Avoid these biases: [Known biases]
- Check outputs for: [Bias indicators]
- When unsure about fairness: [Escalation process]

## Privacy
- Never request: [Sensitive data types]
- Handle data: [Privacy requirements]
- User rights: [What users can do with their data]

# Response Format
[How agent should structure outputs]

# Workflow
When given a task:
1. [Step 1]: [What to do]
2. [Step 2]: [What to do]
3. [Step 3]: [What to do]

# Edge Cases
If [edge case 1]: [How to handle]
If [edge case 2]: [How to handle]

# Examples

## Example 1: [Scenario]
User: [Input]
Agent: [Reasoning]
Agent: [Tool use if applicable]
Agent: [Output]

## Example 2: [Scenario]
User: [Input]
Agent: [Response]

[Add more examples as needed]
```

---

## 7. Example Interactions

### 7.1 Standard Use Case

**User Input**:
```
[Example user query]
```

**Agent Response**:
```
[How agent should respond, including:]
- Reasoning process
- Tool calls (if any)
- Final output
- Source citations
```

### 7.2 Edge Case Handling

**Scenario**: [Description of edge case]

**User Input**:
```
[Example problematic input]
```

**Agent Response**:
```
[How agent handles it gracefully]
```

### 7.3 Ethical Boundary

**Scenario**: [Description of request violating boundaries]

**User Input**:
```
[Example request that should be refused]
```

**Agent Response**:
```
[Refusal message + safe alternative]
```

### 7.4 Transparency Example

**Scenario**: [User requests explanation]

**User Input**:
```
[Example query + "Why did you conclude that?"]
```

**Agent Response**:
```
[Response including detailed reasoning]
```

---

## 8. Implementation Guide

### 8.1 Technical Requirements

**LLM Requirements**:
- **Model**: [Recommended model]
- **Temperature**: [Setting]
- **Max Tokens**: [Setting]
- **Other parameters**: [Settings]

**Infrastructure**:
- **Compute**: [CPU/GPU requirements]
- **Memory**: [RAM requirements]
- **Storage**: [Disk space needed]
- **Network**: [Bandwidth/latency requirements]

**Dependencies**:
```
[List of libraries/packages with versions]
- library1==1.2.3
- library2>=2.0.0
```

### 8.2 Setup Instructions

**Step 1: Environment Setup**
```bash
[Commands to set up environment]
```

**Step 2: Install Dependencies**
```bash
[Commands to install requirements]
```

**Step 3: Configuration**
```
[Configuration files or environment variables]
```

**Step 4: Initialize Agent**
```python
[Code to initialize agent]
```

**Step 5: Test Installation**
```python
[Code to verify agent works]
```

### 8.3 Integration Patterns

**Standalone Usage**:
```python
[Example code for using agent independently]
```

**API Integration**:
```python
[Example code for exposing agent via API]
```

**Web UI Integration**:
```python
[Example code for connecting to web interface]
```

### 8.4 Deployment Considerations

**Local Deployment**:
- [Instructions for running locally]

**Cloud Deployment**:
- [Recommended cloud services]
- [Deployment configuration]

**Scaling Strategies**:
- [How to handle increased load]

---

## 9. Testing & Validation

### 9.1 Test Suite

**Unit Tests**:
- [ ] Test 1: [Description] - Expected: [Result]
- [ ] Test 2: [Description] - Expected: [Result]

**Integration Tests**:
- [ ] Test 1: [Description] - Expected: [Result]
- [ ] Test 2: [Description] - Expected: [Result]

**Ethical Tests**:
- [ ] Fairness Test: [Verify no bias in outputs]
- [ ] Privacy Test: [Verify data protection]
- [ ] Boundary Test: [Verify refuses prohibited actions]
- [ ] Transparency Test: [Verify explanation quality]

**Edge Case Tests**:
- [ ] Empty input: [Expected behavior]
- [ ] Malformed input: [Expected behavior]
- [ ] Extremely long input: [Expected behavior]
- [ ] Ambiguous request: [Expected behavior]

### 9.2 Success Metrics

**Performance Metrics**:
- **Accuracy**: [How measured, target %]
- **Latency**: [Target response time]
- **Throughput**: [Requests per second]

**Quality Metrics**:
- **User Satisfaction**: [How measured]
- **Task Completion Rate**: [Target %]
- **Error Rate**: [Acceptable threshold]

**Ethical Metrics**:
- **Bias Detection Rate**: [How measured]
- **Refusal Accuracy**: [% of harmful requests refused]
- **Transparency Compliance**: [% of responses with citations]

### 9.3 Monitoring

**Real-Time Monitoring**:
- [Metrics to monitor in production]

**Alerting**:
- [Conditions triggering alerts]

**Logging**:
- [What to log for debugging/auditing]

---

## 10. Maintenance & Updates

### 10.1 Scheduled Reviews
- **Frequency**: [How often to review agent]
- **Review Checklist**:
  - [ ] Check for domain knowledge updates
  - [ ] Verify tool integrations still functional
  - [ ] Review ethical guidelines for changes
  - [ ] Analyze user feedback
  - [ ] Update system prompt if needed

### 10.2 Version Control
**Current Version**: 1.0

**Version History**:
- **v1.0** ([Date]): Initial release

**Planned Updates**:
- **v1.1** ([Planned date]): [Planned changes]

### 10.3 Known Limitations
- [Limitation 1]: [Description and workaround]
- [Limitation 2]: [Description and workaround]

### 10.4 Improvement Roadmap
- **Phase 1** ([Timeframe]): [Goals]
- **Phase 2** ([Timeframe]): [Goals]
- **Phase 3** ([Timeframe]): [Goals]

---

## 11. Compliance & Legal

### 11.1 Regulatory Compliance
- [Regulation 1]: [How agent complies]
- [Regulation 2]: [How agent complies]

### 11.2 Industry Standards
- [Standard 1]: [Compliance approach]
- [Standard 2]: [Compliance approach]

### 11.3 Licensing
- **Agent Code**: [License]
- **Dependencies**: [Licenses of third-party libraries]
- **Data**: [Licensing considerations for training/knowledge data]

### 11.4 Disclaimers
[Any legal disclaimers or limitations of liability]

---

## 12. Support & Documentation

### 12.1 User Documentation
- **Getting Started Guide**: [Link or location]
- **FAQ**: [Link or location]
- **Troubleshooting**: [Link or location]

### 12.2 Developer Documentation
- **API Reference**: [Link or location]
- **Architecture Deep Dive**: [Link or location]
- **Contributing Guide**: [Link or location]

### 12.3 Support Channels
- **Issues/Bugs**: [Where to report]
- **Feature Requests**: [Where to submit]
- **Questions**: [Where to ask]

---

## Appendices

### Appendix A: Research Sources
[List of sources used during domain research]
1. [Source 1] - [URL/Citation]
2. [Source 2] - [URL/Citation]

### Appendix B: Glossary
[Domain-specific terminology and definitions]

### Appendix C: Decision Log
[Record of key architectural decisions and rationale]

---

**Document Status**: [Draft | Review | Approved]
**Next Review Date**: [Date]
**Owner**: [Name/Team]
