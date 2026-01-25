>[!NOTE] Abstract
>These notes explain how generative AI can support business analysis by drafting and analysing requirements and process models with structured prompting and human quality controls, then extends into practical stakeholder communication templates tailored to executive, technical, end user, and cross-functional audiences.
# Requirements Elicitation and Documentation with Generative AI
Generative AI can accelerate business analysis by converting unstructured inputs into structured artefacts, surfacing gaps early, and suggesting options for exploration. Strong results come from combining AI speed with disciplined review, clear documentation standards, and transparent stakeholder communication.

This tutorial outlines practical ways to use AI for requirements work, process modelling, and data analysis, plus prompt patterns and quality controls that keep outputs trustworthy.
## 1) Address common pressure points in requirements work
Traditional requirements gathering relies on interviews, workshops, document analysis, and observation. These methods work, yet common constraints reduce effectiveness:
- Requirement gaps caused by incomplete information
- Conflicting perspectives that need reconciliation
- Tight deadlines that limit exploration
- Information overload that hides key needs

Use AI to speed up first drafts and pattern detection, not to replace judgement.
## 2) Use AI across the requirements lifecycle
### Discovery
Scan policies, regulations, legacy specifications, and meeting notes to propose explicit and implicit requirements. Request:
- Numbered requirements with short, testable wording
- Source traceability back to the original text
- Assumptions and information gaps

Treat implicit requirements as hypotheses and validate them with stakeholders.
### Documentation
Draft consistent artefacts:
- User stories with acceptance criteria
- Use cases with alternate and exception flows
- Functional and non-functional requirements grouped by domain
- Standardised language aligned to a glossary

Consistency reduces review time and improves handover quality.
### Analysis
Ask AI to highlight:
- Conflicts between modules or teams
- Ambiguity and vague language
- Missing edge cases, error handling, or decision outcomes
- Coverage gaps against a chosen framework

Resolve issues through targeted clarification sessions before build begins.
### Traceability
Use AI to propose links between objectives, requirements, design elements, test cases, and releases. Confirm links inside delivery tools and treat AI suggestions as a starting point only.
## 3) Automate extraction with four prompting techniques
### Direct extraction prompting
Request explicit requirements plus inferred implications. Improve reliability by specifying:
- Output format with ID, type, and priority
- Source anchors for each item
- Missing information and clarifying questions
### Transformation prompting
Convert unstructured notes into structured formats, such as interview notes into user stories and Given, When, Then criteria. Always request a final list of unresolved gaps.
### Comparative analysis
Compare documents or modules to identify contradictions, overlaps, integration points, and dependency risks. Use the output to run cross-team alignment workshops and agree on a single source of truth.
### Requirements classification
Ask AI to classify requirements by functional or non-functional and by quality attribute, then apply MoSCoW priorities.
## 4) Apply prompt patterns that improve accuracy
### Context-rich prompting
Provide business objectives, target users, constraints, system landscape, and regulatory rules. Without context, AI outputs sound polished yet miss key realities.
### Format prompting
State the artefact, level of detail, and conventions, for example BPMN with swimlanes, a flowchart for executives, or a fixed user story template.
### Incremental refinement
Build outputs in passes:
1. Draft the core set or flow.
2. Add decisions, business rules, and exceptions.
3. Add integrations, inputs, and outputs.
4. Run an ambiguity and conflict check.
5. Apply glossary and formatting.
## 5) Maintain quality with a human review framework
AI outputs must pass human checks that test quality, not style.

Validation checkpoints:
- Clarity: one meaning and one scope per requirement
- Testability: acceptance criteria can be verified
- Completeness: key inputs, outputs, and outcomes are present
- Consistency: terminology matches the glossary
- Alignment: each item supports a real business need
- Traceability: sources and links are recorded

Maintain an audit trail noting where AI drafted content and where edits occurred.
## 6) Generate process maps from narratives, then improve the process
AI can convert a narrative into a process model quickly. Request identification of actors, activities, decisions, inputs, outputs, and system interactions. Ask for multiple notations when the audience differs:
- BPMN for technical teams and automation
- Swimlanes for cross-functional ownership
- Flowcharts for training and executive overviews
- UML activity diagrams for system-focused discussion

Use AI for gap analysis by asking for missing decision outcomes, unclear ownership, and bottlenecks. Validate with participant walk-throughs.
## 7) Improve processes with AI-assisted options and comparisons
Ask AI to propose improvement options, then evaluate feasibility and impact:
- Remove redundant approvals for low-risk work with selective auditing
- Merge duplicate reviews under a single checklist and cross-trained roles
- Run steps in parallel where dependencies allow
- Automate rule-based decisions and routine data transfer
- Add real-time status updates to reduce enquiry load

Request a before-and-after comparison using cycle time, resourcing, error rate, cost impact, and customer experience indicators. Follow with a phased roadmap including prerequisites, training, risks, and success measures.
## 8) Extend AI into data analysis and visualisation
Use AI to propose segments, anomalies, and likely drivers, then validate against the data. Favour:
- Context-rich prompts with objectives and thresholds
- Incremental exploration from broad patterns to root causes
- Multi-perspective analysis across financial, operational, customer, and risk angles

For visualisation, request chart suggestions based on relationship type and audience, plus design guidance that reduces clutter and improves accessibility. Treat correlations as signals that require further investigation.
## 9) Use a hybrid integration pattern with Excel and BI tools
Follow a hybrid workflow:
- Human-led context setting: objectives, business rules, and quality criteria
- AI-assisted processing: cleaning suggestions, pattern discovery, draft visuals
- Human-guided interpretation: validation and narrative framing
- Collaborative output: stakeholder-ready formatting

Quality controls include verifying field definitions, spot-checking calculations, validating business logic, and confirming relevance to the decision question.
## Checklist for safe, effective use
- Start with objectives, constraints, and a domain glossary.
- Request traceability, gaps, and clarifying questions in every output.
- Use iterative refinement, not single-shot prompts.
- Run stakeholder walk-throughs for requirements and process models.
- Communicate AI usage transparently to maintain trust.
# Implementing AI in Business Analysis Workflows
Effective stakeholder engagement depends on delivering the same message in forms that suit different audiences. Leaders want decisions and impact. Technical teams want scope, interfaces, and constraints. End users want clear guidance and support. Mixed groups need structured reviews and timely escalation.
## 1) Lock in audience and purpose
Before drafting, define:
- Audience: executive sponsor, technical delivery, end users, or cross-functional group
- Purpose: inform, decide, coordinate, train, review, or escalate

Capture a short brief to keep all versions consistent:
- Context and objective
- Action required, owner, and deadline
- Evidence, risks, and dependencies
## 2) Executive communications
Executive messages should be concise and decision-focused.

Executive summary update:
- Subject: [initiative] – decision needed by [date]
- Opening: recommendation plus decision required and deadline
- Key findings: three to four bullets with quantified impact where possible
- Recommended action: next steps, owners, and success measures

Project status update:
- Health label: Green, Amber, or Red
- Progress highlights since the previous update
- Two or three issues needing sponsor attention, with recommended resolution
- Milestones due in the next 30 days, plus decisions required
## 3) Technical team communications
Technical messages need precision and a clear impact statement.

Requirements change notice:
- Change summary, source, and approval status
- Impact on scope, timeline, and resourcing
- Requirements added, modified, or removed, plus affected components
- Testing expectations and revised milestones

Integration requirements note:
- Systems involved, business purpose, and data flow direction
- Interface approach, authentication, and security controls
- Data mapping rules and error handling approach
- Performance targets and validation scenarios
## 4) End user communications
End user messages should be practical and jargon-free.

System change notification:
- What is changing and when
- Benefits and workflow impact
- Preparation plan: training, job aids, and support contacts
- Next steps and feedback channels

Training announcement:
- Purpose, audience, and outcomes
- Format, dates, registration, and prerequisites
- Follow-up resources and support
## 5) Cross-functional communications
Requirements review agenda:
- Purpose, items under review, decisions required, and approval criteria
- Materials to review in advance
- Discussion questions and a method for capturing actions, owners, and due dates

Issue escalation note:
- Issue description and impact
- Options considered with trade-offs
- Recommendation, required approvals, and decision deadline
## 6) Audience adaptations and AI prompt patterns
Adaptation rules:
- Non-technical audiences: prioritise outcomes and trade-offs
- Technical audiences: prioritise specifications and test impact
- Decision makers: lead with recommendation and deadline
- Implementers: lead with requirements detail and coordination steps

AI prompt patterns:
```text
Analyse the needs of [role] about [topic], then recommend a format and key messages.
Adapt this [content type] for [audience], adjusting detail while keeping facts aligned.
Create executive, technical, and end user versions from one shared brief.
```
## 7) Quality control and continuous improvement
Before sending:
- Language matches the audience
- Facts, dates, owners, and actions are correct
- Risks, dependencies, and next steps are explicit

Track feedback and update templates as stakeholder preferences and organisational context change.