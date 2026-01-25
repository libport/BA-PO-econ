# Business Analysis: Process Modeling & Requirements Gathering

> [!NOTE]
> These notes introduce core business analysis concepts and the BABOK framework, then provides practical guidance on modelling, process mapping, and requirements elicitation and management to support effective solution delivery.

## Business Analysis Overview and BABOK
Building reliable solutions takes more than collecting a few requests and handing them to a delivery team. A disciplined business analysis approach provides structure, shared language, and repeatable checkpoints that keep work aligned to business goals. The BABOK framework groups that work into knowledge areas supported by techniques, competencies, and perspectives, plus the Business Analysis Core Concept Model (BACCM) that keeps attention on change, need, stakeholders, value, solutions, and context.
### 1) Anchor work with the six core concepts
Use BACCM as a quick diagnostic tool throughout an initiative.

- Change: the transformation required to address a problem or seize an opportunity.
- Need: the issue to resolve or the outcome to achieve.
- Stakeholder: any person or group affected by the change, or able to influence it.
- Value: the benefit gained, including financial outcomes, risk reduction, or improved experience.
- Solution: the product, service, or process that meets the need.
- Context: the environment, constraints, and conditions that shape decisions.

Capture these six items on a single page early, then revisit them at each major decision point.
### 2) Plan and monitor analysis work to prevent drift
Business analysis planning and monitoring organises analysis activities so work is delivered on time and within scope. Five tasks cover the essentials.
#### Plan the business analysis approach
Select an approach that fits uncertainty and delivery style.

- Predictive: best when requirements are largely stable and upfront definition is feasible.
- Adaptive: best when requirements evolve and feedback loops are essential.
- Hybrid: combines upfront structure with iterative refinement.

Define techniques and deliverables at this stage. Techniques include interviews, workshops, surveys, and observation. Deliverables commonly include requirements specifications, user stories, models, and reports.
#### Plan stakeholder engagement
Identify stakeholders, assess influence and interest, and plan interactions.

- Map stakeholders by influence, interest, and impact.
- Decide communication frequency and channels.
- Set expectations for responsiveness, review cycles, and decision points.
#### Plan governance
Governance defines how decisions are made and how changes are handled.

- Assign decision authority for scope, priorities, and acceptance.
- Define a change control process that evaluates impact before approval.
- Establish review and sign-off steps for requirements and key artefacts.
#### Plan information management
Information management keeps analysis assets accessible and current.

- Define naming conventions, folder structures, and templates.
- Decide storage locations such as a document repository or shared drive.
- Set rules for versioning, access, and update cadence.
#### Identify performance improvements
Treat analysis as a practice that can be measured and improved.

- Define success measures such as stakeholder satisfaction, clarity of requirements, and adherence to timelines.
- Review outcomes and rework levels.
- Implement improvements through training, process updates, or tooling changes.
### 3) Elicit information and collaborate to maintain alignment
Elicitation gathers information. Collaboration keeps people aligned and committed.
#### Collaboration concepts to apply
- Active listening and frequent feedback to reduce misunderstanding.
- Teamwork with clear roles and responsibilities.
- Negotiation and conflict resolution to reconcile competing priorities.
- Transparent decision making that records rationale.
- Problem solving that targets root causes, not symptoms.
#### Techniques that support collaboration
- Workshops for shared discovery and rapid alignment.
- One-on-one interviews for depth and sensitive topics.
- Surveys for breadth across large groups.
- Prototypes and mock-ups to validate understanding early.
- Collaboration tools such as shared documents, chat platforms, and task boards to keep context visible.

Capture decisions, actions, and open questions at the end of every session, then circulate notes quickly.
### 4) Analyse requirements and define design options
Requirements Analysis and Design Definition (RADD) turns raw input into clear requirements and viable solution options.
#### Specify and model requirements
Choose modelling methods that match the audience and problem.

- Use cases describe how actors achieve a goal through interactions with a system.
- User stories capture value in a short format and suit iterative delivery.
- Process flow diagrams show steps, hand-offs, and decision points.
- Data models clarify entities, relationships, and business rules.
#### Verify and validate
Verification checks quality. Validation checks relevance.

- Verify completeness, consistency, and testability.
- Validate alignment to business goals and stakeholder outcomes.
- Remove conflicts and ambiguous wording.
- Confirm acceptance criteria where delivery teams need clarity.
#### Define and assess solution options
Generate options rather than locking onto the first idea.

- Compare build versus buy, or in-house versus third-party integration.
- Evaluate feasibility, cost, risk, and benefits.
- Recommend an option with a clear rationale tied to value.
### 5) Manage requirements across their lifecycle
Requirements Life Cycle Management (RLCM) keeps requirements coherent from inception to retirement.
#### Establish and maintain traceability
Traceability links requirements to sources, design elements, test cases, and delivered outcomes. A traceability matrix makes impact analysis faster when change requests arrive.
#### Prioritise and maintain
Prioritisation balances value, risk, dependencies, and effort. MoSCoW is a common technique.

- Must have: essential for release.
- Should have: important but can wait if constrained.
- Could have: desirable enhancements.
- Won’t have: explicitly out of scope for now.

Maintenance includes regular review and updates so requirements remain accurate as context shifts.
#### Assess changes and obtain approval
Change control evaluates impact on scope, timeline, and budget before acceptance. Formal approval checkpoints reduce churn and protect alignment.
### 6) Align analysis to strategy
Strategy analysis ensures analysis work supports organisational direction.

- Current state analysis: document how work happens today, including processes, systems, and pain points.
- Future state definition: describe the desired outcome aligned to mission and vision.
- Risk assessment: identify obstacles that could block progress and plan mitigation.
- Change strategy: create a roadmap from current to future state with milestones, resources, and sequencing.

Support this work with techniques such as SWOT, PESTLE, balanced scorecards, Porter’s five forces, and facilitated brainstorming.
### 7) Evaluate solutions after delivery
Solution evaluation checks whether the implemented solution delivers the expected value.
#### Measure solution performance
Define metrics before measurement.

- Quantitative: cost savings, cycle time reduction, throughput, error rates.
- Qualitative: user satisfaction, usability, perceived confidence.

Collect data through surveys, interviews, system logs, and operational reports. Compare results to benchmarks and look for trends over time.
#### Assess limitations
Identify issues that reduce value, then analyse root causes. Also assess enterprise constraints such as culture, capability, and resourcing that may limit effectiveness even when the solution is sound.
#### Recommend value-increasing actions
Propose improvements and prioritise them by impact and feasibility. Build an action plan with owners, timelines, and measures to confirm improvement.

### 8) Select a perspective that fits context
Perspectives provide context-specific guidance rather than separate methods.

- Agile: iterative delivery, frequent feedback, and adaptation.
- Business intelligence: data collection, analysis, and visualisation to drive decisions.
- Information technology: alignment to the system development lifecycle and technical constraints.
- Business architecture: aligning structure, processes, and information to strategy.
- Business process management: designing, monitoring, and improving processes.

Select a primary perspective based on constraints and goals, then borrow techniques from others when needed.
### 9) Use tools that match the work
Tools should reduce friction, not create it.

- Documentation: word processors for specifications and reports.
- Analysis: spreadsheets for profiling and quick checks, plus SQL for database queries.
- Requirements and delivery tracking: Jira or similar tools for backlogs, epics, and status.
- Visual modelling: diagramming tools for flowcharts, BPMN, UML, ERDs, and wireframes.
- Reporting and visualisation: BI tools such as Power BI or Tableau.
- Collaboration: chat, video meetings, and shared drives with clear version control.
- Feedback: survey tools that capture responses into structured tables for analysis.

Standardise templates and naming conventions so artefacts remain easy to find and reuse.
## Agile Business Analysis and Modeling Techniques
Modelling and agile artefacts reduce ambiguity by turning goals into clear visuals, concise requirements, and repeatable working routines. The guidance below covers UML fundamentals, use cases and actors, use case diagrams, user stories, backlog refinement, core ceremonies, SDLC awareness, and the complementary use of ERDs and DFDs.
### 1) Use UML as a shared language
Unified Modeling Language (UML) is a standard way to specify, visualise, construct, and document software system artefacts. Its main purpose is communication across mixed audiences and durable documentation for maintenance.

Key concepts:
- Actor: an external entity that interacts with the system, including people, organisations, devices, or other systems.
- Use case: a goal-focused capability described from an actor’s perspective.
- Class: a blueprint defining attributes and operations.
- Object: a specific instance of a class with concrete values.

Diagram families:
- Structural diagrams describe what the system is, such as class, component, and deployment views.
- Behavioural diagrams describe what the system does, such as use case, activity, and sequence views.
### 2) Write use cases that clarify goals and boundaries
A use case explains how an actor interacts with a system to achieve a goal. Use cases clarify functional requirements and support design and testing.

Core components:
- Title: concise and goal-based, such as Purchase product.
- Actors: primary actor plus supporting actors or external systems.
- Preconditions: what must be true before the flow begins.
- Main flow: standard steps that achieve the goal.
- Alternate flows: valid variations caused by user choice or expected conditions.
- Exception flows: failure behaviour such as payment rejection.
- Postconditions: the state after completion, including stored records and notifications.

Example outline for Purchase product:
1. Browse catalogue and select an item.
2. Add item to cart and review cart.
3. Proceed to checkout and enter shipping details.
4. Provide payment details and submit.
5. System processes payment and confirms the order.

Alternate flow: item out of stock triggers a message and blocks checkout for that item.  
Exception flow: payment fails, then prompt for retry or a different method.  
Postconditions: order stored, confirmation displayed, confirmation email sent.

Quality rules:
- Prefer plain, specific language over jargon.
- Capture alternate and exception flows, not only the happy path.
- Review with business, delivery, and test roles so wording is testable.
### 3) Identify and define actors with discipline
Actors represent roles, not job titles. A single person can play multiple actor roles across scenarios.

Actor types:
- Primary actors initiate a use case to achieve a goal.
- Supporting actors provide services or information required by the system.
- External systems exchange data through integration.

Identification steps:
1. Confirm system purpose and boundary.
2. List user groups and interacting systems.
3. Identify goals per group.
4. Categorise actors per use case.
5. Validate with stakeholders and adjust.

A useful actor definition includes a name, description, goals, and key interactions.
### 4) Create use case diagrams for scope and alignment
Use case diagrams provide a visual summary of interactions and system scope.

Core elements:
- Actors outside the system boundary.
- Use cases inside the boundary, named with verb-based labels.
- Relationships between actors and use cases.

Relationship types:
- Association: actor participates in a use case.
- Include: a required sub-process reused by multiple use cases, such as Process payment.
- Extend: optional behaviour under conditions, such as Apply discount during a promotion.

Scenario types that sit behind the diagram:
- Basic flow: standard success path.
- Alternate flow: a variation that remains valid.
- Exception flow: failure and recovery behaviour.

Diagram tips:
- Keep diagrams high level and keep detail in use case text.
- Group related use cases to avoid crossed lines.
- Use consistent naming, such as View products, Place order, Process payment.
### 5) Capture agile requirements with user stories
User stories are short, value-focused requirements written in simple language.

Format:
As a [role], I want [goal] so that [benefit].

Acceptance criteria turn a story into a testable agreement. Use Given, When, Then statements.

Example criteria for login:
- Given valid credentials, when Login is selected, then the account dashboard is displayed.
- Given invalid credentials, when Login is selected, then an error message is displayed and access is denied.

Quality check with INVEST:
- Independent, Negotiable, Valuable, Estimable, Small, Testable.
### 6) Maintain the product backlog through refinement
The product backlog is a prioritised list of work items such as features, defects, technical tasks, and research. Refinement keeps near-term items ready for sprint planning.

Refinement loop:
1. Review new items and confirm intent.
2. Reorder based on value, risk, urgency, and dependencies.
3. Add detail to near-term items and keep future items high level.
4. Split large items into smaller stories that fit a sprint.
5. Add acceptance criteria to items likely to enter the next sprint.
6. Estimate effort using a consistent technique such as planning poker.

Common pitfalls:
- Over-detailing everything. Focus on the next few sprints.
- Unclear items. Add examples, rules, and acceptance criteria before estimating.
- Low engagement. Timebox sessions and rotate facilitation.
### 7) Run ceremonies with a clear purpose
Sprint planning:
- Review the top backlog items and confirm readiness.
- Define a sprint goal that states the intended outcome.
- Select items based on capacity and historical velocity.
- Break selected items into tasks and identify dependencies and risks.

Timeboxing guideline: about two hours of planning per week of sprint duration.

Daily stand-ups:
- Share progress, next steps, and blockers.
- Keep the session under 15 minutes.
- Park problem solving for follow-up discussions.

Retrospectives:
- Set the stage, gather data, decide actions, and close with a summary.
- Produce specific improvement actions with owners and a check-in date.

Alternatives include asynchronous updates, Kanban flow checks, after-action reviews, and project post-mortems.
### 8) Use SDLC awareness to align analysis and delivery
The Software Development Life Cycle (SDLC) provides a shared view of software work.

Phases:
- Planning, analysis, design, development, testing, deployment, maintenance.

Common models:
- Waterfall: sequential and stable, but less flexible to change.
- Agile: iterative and adaptive with frequent feedback.
- Spiral: iterative with strong risk management.

Tool categories:
- Tracking tools such as Jira or Trello.
- Modelling tools such as Lucidchart.
- Collaboration tools for shared documents and decisions.
### 9) Strengthen analysis with ERDs and DFDs
Entity Relationship Diagrams (ERDs) clarify data structure.
- Entities, attributes, relationships.

Data Flow Diagrams (DFDs) clarify how information moves and where processing occurs.
- Processes, data flows, data stores, external entities.

ERDs answer what data exists and how it relates. DFDs answer how data moves through the system. Used together, they improve documentation, communication, and the ability to spot inefficiency.
## Process Modeling Methodologies and Advanced Techniques
Complex operations rarely improve through guesswork. Clear process models expose how work flows, where it slows down, and which changes create measurable value. This tutorial covers process mapping techniques, advanced BPMN with swimlanes, selecting modelling tools, spotting inefficiencies, optimising processes, and implementing automation. It also includes applied lab-style workflows for order management and loan processing analysis.
### 1) Model processes to create shared understanding
Process models turn informal knowledge into a visible description of work. Aim for models that are:
- Clear for technical and non-technical stakeholders
- Complete, with start and end points, key tasks, decisions, and hand-offs
- Consistent in symbols and naming
- Current, reflecting real practice rather than outdated policy

Practical outcomes to target:
- Alignment across departments on responsibilities and sequence
- Fast discovery of bottlenecks and rework loops
- Reliable documentation for training, audits, compliance, and change management
### 2) Use flowcharts and process maps for quick clarity
A process map shows steps and the flow of tasks or information. A flowchart is a specific type of process map that relies on standard symbols.

Common symbols:
- Start or end: rounded rectangle or oval
- Activity: rectangle
- Decision: diamond
- Flow direction: arrow
- Input or output: parallelogram

A simple build method:
1. Define scope with a clear first step and last step.
2. List tasks in plain language, one action per step.
3. Insert decisions where outcomes diverge.
4. Connect with arrows and keep a consistent reading direction.
5. Validate with stakeholders, then version and publish.
### 3) Map complex processes with the right technique
Complex processes often need more than a basic flowchart. Select a technique that matches purpose and audience.
#### Swimlane diagrams
Use for cross-functional workflows where responsibility and hand-offs matter most. Lanes make ownership visible, which makes delays easier to diagnose.
#### SIPOC
SIPOC stands for Suppliers, Inputs, Process, Outputs, and Customers. It provides a high-level overview that is useful at the start of analysis or when scope needs fast alignment.

A quick SIPOC build:
- Suppliers: who provides inputs, such as vendors or upstream teams
- Inputs: what is received, such as parts, data, or requests
- Process: the major steps, usually five to seven
- Outputs: what is produced, such as approved loans or shipped orders
- Customers: who receives outputs, internal or external
#### Value stream mapping
Value stream mapping distinguishes value-adding activities from waste, such as waiting, rework, over-processing, and unnecessary movement. Use it when lead time reduction is a key goal.
#### BPMN
Use BPMN when events, integrations, and branching logic are complex and need a standard notation that scales.
#### Applying any technique to a complex process
Follow a repeatable approach:
1. Define boundaries to avoid scope creep.
2. Gather information through interviews, observation, and existing documentation.
3. Draft the first version quickly, then validate with process participants.
4. Refine naming, decision logic, and hand-offs until the model reads cleanly.
5. Use the model to identify improvements, then track outcomes with metrics.
### 4) Apply BPMN when a flowchart is not enough
Business Process Model and Notation (BPMN) is a standard graphical representation for specifying business processes in a workflow. BPMN is useful when processes include multiple events, integrations, and structured decision logic.

Core BPMN elements:
- Events: circles that represent triggers or outcomes
- Activities: rounded rectangles for tasks
- Sequence flows: arrows for execution order
- Gateways: diamonds for branching and merging
- Data objects: information required or produced by tasks
### 5) Use swimlanes to show responsibility clearly
A swimlane diagram organises activities into lanes, where each lane represents a participant such as a role, team, or department. Swimlanes make hand-offs visible, which helps diagnose delays and miscommunication.

Swimlane components:
- Lanes for participants
- Activities placed in the lane that performs them
- Sequence flows across lanes to reveal hand-offs
- Gateways for decision points
- Events for start, intermediate, and end triggers

Example order fulfilment flow:
- Customer: place order
- Sales: verify payment, notify customer
- Warehouse: prepare shipment, update inventory
- Delivery: deliver product

Add a gateway after payment verification:
- Payment rejected: notify customer and stop or return to correction
- Payment approved: continue to fulfilment
### 6) Use advanced BPMN techniques for complex behaviour
Advanced techniques reduce clutter and represent real-world conditions.
#### Subprocesses
A subprocess groups related activities under a single labelled container. Use subprocesses to hide detail while keeping the overall diagram readable.
#### Exclusive gateways
Exclusive gateways represent a decision where only one path can be taken.
#### Parallel gateways
Parallel gateways represent paths that proceed at the same time, such as packaging work and customer notification running concurrently.
#### Event-based gateways
Event-based gateways select a path based on which event occurs first, not which condition evaluates to true.
#### Data objects
Data objects represent data needed or generated by tasks, such as an application form, credit report, or approval letter.
### 7) Choose the right process modelling tool
Tool selection affects adoption and quality. Evaluate tools against the needs of the team and the organisation.

Key factors:
- Ease of use: intuitive interface, templates, drag-and-drop
- Collaboration: real-time editing and easy sharing
- Integration: compatibility with tools such as Jira and SharePoint
- Customisation: ability to tailor templates and notations
- Cost and licensing
- Support: documentation, training, and community

Common options:
- Lucidchart and Microsoft Visio for fast diagramming
- Miro for collaborative workshops
- Bizagi for BPMN and workflow orientation
- ARIS or SAP Signavio for enterprise process governance
- Draw.io for a free, lightweight option
### 8) Document processes with best-practice discipline
High-quality documentation is objective, current, and easy to navigate. Aim for artefacts that stakeholders can trust months later.

Practical principles:
- Keep diagrams simple and clean
- Use standard notation consistently, such as BPMN, SIPOC, or flowcharts
- Avoid jargon and prefer plain language
- Involve stakeholders who perform the work
- Use version control and record change notes in the header
- Set a review cadence so documentation stays current

A fast validation routine:
- Walk through the model step-by-step with a small group.
- Confirm each decision point has clear outcomes.
- Confirm each hand-off has a named sender and receiver.
- Confirm required data objects are present where decisions depend on them.
### 9) Identify common process inefficiencies
Inefficiencies often fall into repeatable patterns.

Common issues:
- Redundant steps, such as unnecessary approvals
- Bottlenecks created by limited capacity or scarce skills
- Excessive hand-offs that cause delay and miscommunication
- Inconsistent procedures across teams
- Poor communication and missing status updates
- Manual, error-prone tasks and repeated data entry
- Lack of training on tools and rules
- Missing metrics that prevent improvement tracking
### 10) Analyse a process to pinpoint root causes
A structured analysis method prevents premature solutions.

Step-by-step analysis:
1. Identify the process to analyse with clear boundaries.
2. Map the current state using a flowchart, swimlane, SIPOC, or BPMN.
3. Collect data, such as time per step, error rates, and volumes.
4. Analyse flow for queues, rework, and waiting time.
5. Engage stakeholders to validate findings and constraints.
6. Develop improvements, then implement and monitor results.

Use the five whys technique to drill into root causes:
- Define the problem.
- Ask why, record the answer, and repeat until an actionable cause emerges.

Example chain for late loan processing:
1. Delay occurred because documents were submitted late.
2. Documents were late because required documents were unclear.
3. Requirements were unclear because instructions were outdated.
4. Instructions were outdated because no review process existed.

Root cause is missing governance for updating instructions.
### 11) Optimise processes with measurable objectives
Process optimisation improves efficiency and effectiveness by making work faster, more cost-effective, and more reliable. Optimisation must be measurable so success can be verified.

Core concepts:
- Process mapping and bottleneck identification
- Clear objectives, such as reducing wait time from 10 minutes to 5 minutes at peak
- Performance analysis based on data and feedback
- Implementation through workflow redesign or enabling technology
- Continuous monitoring and adjustment

Common optimisation techniques:
- Lean: remove waste and focus on value-added activities
- Six Sigma: reduce defects and variability using data-driven improvement
- Business Process Re-engineering (BPR): redesign from the ground up when incremental change is insufficient
### 12) Re-engineer processes when incremental change fails
BPR targets step-change improvements in cycle time, quality, cost, and customer experience.

BPR steps:
1. Identify critical processes with high error rates or long delays.
2. Analyse the current process with maps and metrics.
3. Redesign by removing unnecessary steps and applying enabling technology.
4. Implement with training, updated roles, and system changes.
5. Monitor performance and refine.

Common challenges:
- Resistance to change
- High initial cost
- Complexity and disruption risk

Mitigate these with involvement, communication, pilots, and careful cutover planning.
### 13) Implement process automation with a controlled approach
Process automation uses technology to perform tasks with minimal human intervention. It improves speed, reduces error, supports scaling, and can strengthen compliance through audit trails.

Key concepts:
- Workflow automation: tasks triggered automatically when conditions are met
- Robotic Process Automation (RPA): software bots mimic human actions across applications
- Business Process Management (BPM): model, monitor, and improve processes through tooling and governance
- Integration: connect tools to existing systems for seamless data flow

Implementation steps:
1. Identify candidates such as repetitive, high-volume tasks.
2. Evaluate tools for integration, scalability, and cost.
3. Design the workflow with steps, decision points, and data flow.
4. Implement and test thoroughly, including exception handling.
5. Monitor efficiency gains, error rates, and feedback, then optimise.

Example automation: invoicing
- Select invoicing software and templates.
- Integrate with sales systems to auto-generate invoices on purchase.
- Track time saved and accuracy, then refine templates and rules.

Other common automation patterns include onboarding checklists, inventory updates, and first-line support chatbots.
### 14) Close with continuous improvement
Treat process work as a cycle. Maintain a rhythm of mapping, measuring, improving, automating where stable, and monitoring outcomes. Clear models plus measurable metrics create a practical path from confusion to control. Maintain momentum through regular review.
## Requirements Management and Elicitation Techniques
Successful delivery depends on clear requirements, shared understanding, and controlled change. Requirements work is not a single meeting or a single document. It is a lifecycle that starts with identifying the right stakeholders, continues through elicitation and analysis, and is sustained through prioritisation, traceability, and ongoing validation.

This tutorial summarises practical techniques and habits for gathering, documenting, and managing requirements in a way that supports delivery teams and protects business value.
### 1) Identify stakeholders early and keep the list current
Stakeholders are individuals or groups affected by an initiative, or able to influence its outcome. Stakeholder identification is a foundation activity because requirements quality depends on the right voices being heard.
#### Stakeholder categories
- Internal stakeholders: staff, team members, managers, executives, operational roles, and internal support teams.
- External stakeholders: customers, suppliers, partners, regulators, and the public where relevant.
#### A simple identification and analysis routine
1. Brainstorm a long list of potential stakeholders with the project team.
2. Categorise by internal or external, then capture each role and expected involvement.
3. Map stakeholders by influence and interest:
	   - High influence and high interest: key players who need close engagement.
	   - High influence and low interest: keep satisfied and informed without overload.
	   - Low influence and high interest: keep informed and consult for insight.
	   - Low influence and low interest: monitor with minimal effort.
4. Review the map at key milestones, because influence and interest can shift as scope, timelines, or impacts change.

A lightweight engagement plan helps maintain consistency. Define communication channels, frequency, decision points, and escalation paths per stakeholder group.
### 2) Choose elicitation techniques to match the situation
Elicitation gathers information about needs, constraints, and expectations. No single technique is sufficient for every context. Better results come from combining methods and triangulating findings.

Common elicitation techniques:
- Interviews for depth and nuance.
- Workshops for collaboration and fast alignment.
- Surveys for breadth and quantitative signals.
- Observation for real behaviour in real context.
- Prototypes for visual validation and early feedback.
- Document analysis for policy, regulation, and existing process evidence.

Select at least three techniques for most initiatives, then use findings from one technique to challenge assumptions formed in another.
### 3) Conduct interviews that produce actionable detail
Interviews provide an in-depth view of stakeholder goals, pain points, and constraints. A good interview is structured enough to stay on track, yet flexible enough to follow important leads.
#### Interview types
- Structured interviews use a fixed set of questions for consistency.
- Semi-structured interviews combine prepared questions with follow-up probes.
- Unstructured interviews are conversational and exploratory, useful when the problem is not well understood.

Semi-structured interviews often provide the best balance for business analysis because they support comparability while still allowing discovery.
#### Preparation checklist
- Identify the stakeholder and clarify the role in the process or system.
- Define objectives, such as clarifying pain points, validating assumptions, or exploring solution options.
- Draft questions that align to objectives and avoid unnecessary scope.
- Schedule a suitable time and choose a setting that supports focus and privacy.
- Request consent for note taking and recording where recording is permitted.
#### Question design that avoids dead ends
Favour open-ended questions that begin with what and how, since they prompt explanation and examples. Use follow-up probes to move from general statements to specifics.

Examples:
- What steps occur from request to completion in the current process?
- How does the team decide priority when multiple requests arrive at once?
- What is the most common reason work needs to be redone?
- Can a recent example illustrate where the process worked well?

Use why questions with care. They are useful for uncovering root causes, yet can sound accusatory. A safer framing is: What drives that decision, or What factors lead to that outcome.

Avoid leading questions that steer the answer. Replace “Do staff find this feature beneficial” with “What has been the experience with this feature”.
#### Rapport and active listening
Rapport increases candour and detail. Maintain a respectful, conversational tone, acknowledge expertise, and summarise key points to confirm understanding. Track time and close on schedule, then capture next steps and follow-up questions.
#### After the interview
Convert notes into a structured format, then look for patterns across interviews. Validate interpretations with stakeholders, especially where ambiguity exists. Follow up quickly while context is fresh.
### 4) Use observation to uncover real behaviour and hidden constraints
Observation provides a first-hand view of work as it is performed. It helps reveal informal practices, workarounds, and friction points that may not surface in interviews.

Observation approaches:
- Direct observation: watch tasks as they occur without participating.
- Participant observation: perform parts of the process to experience constraints.
- Shadowing: follow a role over time to capture context switching and hand-offs.
- Video observation: record sessions where permitted, then review for patterns.
#### Best practices for observation
- Define objectives before observing, such as understanding hand-offs or tool usage.
- Obtain permissions and explain the purpose to reduce anxiety.
- Take notes on actions and context, including interruptions, delays, and dependencies.
- Debrief after observation to validate findings and collect explanation for observed behaviour.

Observation supports process mapping, user-centric design, and change management by showing what actually happens rather than what policy claims should happen.
### 5) Design surveys that produce reliable, useful data
Surveys collect input efficiently across large groups. They work well for validating assumptions, measuring preferences, and gathering feedback at scale.
#### Survey design steps
1. Define objectives and the decisions the survey will inform.
2. Identify the audience and segment where needed, since sponsors, end users, and technical teams focus on different concerns.
3. Choose question types:
	   - Closed-ended questions for simple analysis, such as rating scales.
	   - Multiple-choice questions for forced selection.
	   - Open-ended questions for qualitative detail.
	   - Ranking questions for priority insights.
4. Keep surveys short and focused. Aim for a completion time of 10 to 15 minutes.
5. Pilot test with a small representative group to find confusing wording or technical issues.
6. Distribute via appropriate channels such as email, survey platforms, or controlled in-person collection.
7. Monitor response rates and send reminders, then analyse trends and themes.

Incentives can raise participation, but ensure incentives are appropriate and do not pressure responses.
### 6) Use prototypes to refine requirements through visible feedback
Prototypes allow stakeholders to see and interact with concepts before requirements are finalised. This reduces misunderstandings and expensive change later.

Prototype types:
- Low-fidelity prototypes: sketches, wireframes, basic mock-ups, fast to change.
- High-fidelity prototypes: interactive, closer to the final product, useful for usability feedback.
- Throwaway prototypes: built to learn, then discarded.
- Evolutionary prototypes: refined iteratively and may become the final solution.

Best practices:
- Define prototype objectives, such as testing a flow or clarifying terminology.
- Involve stakeholders early and run regular feedback cycles.
- Record insights and decisions, then update requirements accordingly.
- Use workshops where participants interact with prototypes and propose improvements.
### 7) Understand and document different requirement types
Clear categorisation improves analysis and reduces mismatch during delivery.

Requirement categories:
- Business requirements: high-level goals and outcomes, such as increasing sales by 20% in one year.
- Stakeholder requirements: needs of specific groups, such as finance reporting or marketing campaign tooling.
- Functional requirements: what the system must do, such as product search or secure payment processing.
- Non-functional requirements: quality attributes, such as performance, security, usability, and reliability.
- Transition requirements: conditions needed to move from current to future state, such as training, data migration, and deployment planning.
- Regulatory requirements: legal and industry standards that must be met.

Non-functional requirements should include measurable targets where possible, such as response time, availability, or supported concurrency, rather than vague phrasing.
### 8) Document requirements so delivery teams can build and test
Documentation is the bridge between stakeholder intent and implementation. Use clear language, logical structure, and agreed acceptance criteria.
#### Documentation principles
- Use plain language and minimise jargon.
- Group requirements logically and maintain a consistent numbering scheme.
- Include acceptance criteria that define how completion will be validated.
- Use visual aids such as diagrams, flowcharts, and mock-ups to clarify complex behaviour.
- Implement version control to track changes and avoid conflicting documents.
- Schedule regular reviews so documentation stays accurate as the project evolves.

Acceptance criteria can be expressed as testable statements. For user stories, a common structure is Given, When, Then.
### 9) Prioritise requirements with transparent techniques
Prioritisation aligns scope to value, feasibility, and urgency. It also sets expectations when time and budget are constrained.

Common prioritisation techniques:
- MoSCoW:
	  - Must have: essential for release or compliance.
	  - Should have: important but not vital for the first release.
	  - Could have: desirable enhancements that can be deferred.
	  - Won’t have: explicitly out of scope for the current iteration.
- Kano model:
	  - Basic needs, performance needs, excitement needs.
- Weighted scoring:
	  - Score requirements against criteria such as value, risk reduction, and cost of delay, then apply weights.
- 100-point method:
	  - Allocate a fixed pool of points across requirements to expose relative priority.
### 10) Maintain traceability to control change and assure coverage
Traceability tracks requirements from origin through design, build, and testing. It supports change impact analysis, quality assurance, and compliance.

Types of traceability:
- Forward traceability links requirements to design, development, and test assets.
- Backward traceability links delivered components back to approved requirements.
- Bidirectional traceability supports both directions and is most useful for change control.

Common tool support includes Jira, Azure DevOps, IBM Engineering Requirements Management DOORS, Helix RM, and ReqView. Tool choice matters less than consistent linking practice, clear naming, and regular updates.
### 11) Facilitate workshops to elicit and validate as a group
Workshops are efficient for gathering and validating requirements because they bring stakeholders together in a structured environment.

A repeatable workshop structure:
1. Define goals and the specific decisions required.
2. Select a diverse group of stakeholders and set participation guidelines.
3. Create a timed agenda with topics, activities, and breaks.
4. Use techniques such as brainstorming, affinity mapping, storyboarding, and basic prototyping.
5. Capture decisions, assumptions, and action items with a dedicated note taker.
6. Distribute notes promptly and schedule follow-up sessions for unresolved issues.

Effective facilitation encourages balanced participation, keeps discussion on scope, and uses visual aids to maintain shared context.
### 12) Apply systems analysis to connect requirements to real operating context
Systems analysis studies a business system by examining how components interact. A business system includes people, processes, technology, and information.

Key system concepts:
- Inputs: resources or data entering the system.
- Processes: activities performed on inputs.
- Outputs: products or outcomes produced.
- Feedback: signals that indicate performance and whether outputs meet objectives.
- Boundaries: what is inside the analysis scope and what is outside.
- Environment: external factors such as regulations, market conditions, and competitors.

A practical system analysis sequence:
1. Identify the problem or opportunity.
2. Gather data through interviews, surveys, observation, and document review.
3. Analyse the current system for bottlenecks and gaps.
4. Design improvements and assess feasibility.
5. Implement with training and communication support.
6. Monitor performance and refine.

Business rules are constraints and policies that guide behaviour. Translate business rules into clear, testable specifications so delivery teams can implement them correctly.
### Checklist for day-to-day practice
- Maintain a living stakeholder list and engagement plan.
- Combine interviews, observation, and workshops for depth and alignment.
- Use surveys to validate assumptions and measure preference at scale.
- Apply prototyping to reduce ambiguity in flows and terminology.
- Write requirements in plain language with testable acceptance criteria.
- Prioritise transparently and revisit priorities when context changes.
- Maintain traceability links from requirements through tests and delivery.
- Treat documentation as a controlled asset with versioning and review.