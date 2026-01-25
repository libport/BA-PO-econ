> [!NOTE] Abstract
> An overview of business analysis that explains the role of the business analyst, outlines a practical end-to-end process from needs and scope through elicitation, documentation, validation, prioritisation, traceability and change control, and applies these concepts through hands-on labs and scenarios covering process improvement, requirements tooling, gap analysis, and digital transformation.
# Basics of Business Analysis
## Understand the purpose of business analysis
Business analysis is a discipline for identifying business needs and recommending solutions. Solutions may involve software, but can also include process improvement, organisational change, or policy and strategy updates. A business analyst acts as the bridge between stakeholders and delivery teams, translating needs into clear, testable requirements and validating that outcomes align with business goals.
## Follow a practical development pathway
A typical progression moves through increasing autonomy and leadership:
- Junior business analyst: supports requirement gathering, process documentation, and basic data analysis
- Associate business analyst: leads elicitation, produces detailed documentation, coordinates stakeholders
- Senior business analyst: manages complex work, guides juniors, selects approaches and data sources
- Lead or principal business analyst: sets standards, oversees quality, manages budgets and priorities
- Management and executive tracks: portfolio oversight, practice leadership, strategic innovation
## Build the core skill set
Competence depends on balanced capability:
- Analytical skills: data interpretation, critical thinking, problem solving, risk awareness
- Interpersonal skills: facilitation, negotiation, conflict resolution, clear communication
- Delivery skills: structured documentation, prioritisation, validation and testing support
- Technical literacy: systems concepts, data and reporting, and familiarity with common tools and platforms (no coding requirement, but technical fluency helps)
## Use standards and credentials deliberately
BABOK, published by the International Institute of Business Analysis (IIBA), provides a common language, knowledge areas, and techniques for consistent practice. It also supports certification pathways such as ECBA, CCBA, and CBAP. Qualifications can be built through university study, vocational programmes, online learning, and supervised project experience.
## Choose specialisation and adjacent options
Specialisation may be industry-based (finance, healthcare, retail) or solution-based (CRM, ERP, analytics, process improvement). Common adjacent roles include systems analyst, project manager, product manager, process analyst, and data analytics roles.
# Business Analysis Process
## Start with needs and scope
A business analyst begins with a needs assessment: the problem or opportunity is defined, current and future states are compared, options are developed, and a business case recommendation is prepared. Clear scope boundaries are set early so stakeholders understand what is in and out of scope, reducing scope creep.
## Engage stakeholders with intent
Stakeholders are identified and analysed, then a communication approach is agreed. Commitment is built through regular alignment sessions and transparent decision-making, not one-off check-ins.
## Gather requirements systematically
Requirements elicitation relies on multiple techniques to reduce gaps and bias:
- Interviews and workshops for depth and shared understanding
- Surveys for breadth and quantifiable input
- Observation to expose real workarounds and constraints
- Document analysis to anchor discussions in existing process and system reality

Requirements are then documented in appropriate artefacts, such as a BRD for business needs, an FRD or functional specification for system behaviour, plus user stories, use cases, wireframes, or prototypes when clarity benefits.
## Analyse, validate, and prioritise
Analysis checks feasibility (technical, financial, operational), resolves conflicts, and prioritises work. MoSCoW prioritisation: Must have, Should have, Could have, Won’t have. Validation occurs through stakeholder reviews and early prototypes, ensuring requirements are complete, consistent, and value-adding.
## Manage change and traceability through delivery
Execution depends on a traceability structure linking requirements to design, build, and testing, often via a requirements traceability matrix. Change control is applied so requirement updates are reviewed, approved, versioned, and communicated. Post-implementation evaluation measures outcomes against success criteria and secures formal sign-off.
## Use tools to support collaboration
Common tool patterns include Jira for tracking epics, stories, and tasks; Confluence for documentation and decision logs; Excel for matrices and analysis; Visio or Lucidchart for process modelling; Tableau or Power BI for dashboards; and Teams or Slack for day-to-day coordination.

---
## Lab: Visualising and Improving a Business Process
### 1) Capture the current process flow
Begin by writing the “as-is” workflow in plain language, end to end. For the FreakEats scenario, the core sequence is:
1. Customer places an order in the app.
2. Restaurant accepts the order and prepares the meal.
3. Delivery partner is assigned.
4. Delivery partner picks up the meal and delivers it.
### 2) Identify stakeholders and responsibilities
List stakeholders who create, consume, or support the process:
- Customers    
- Restaurant staff
- Delivery partners
- Support team (platform operations)

Add role clarity: restaurant staff manage acceptance and preparation; delivery partners manage pickup and delivery; support handles exceptions (missing items, delays, cancellations).
### 3) Create an as-is process flow diagram in Lucidchart
In Lucidchart, create a blank document and use Flowchart shapes:
- Start/End oval: Start: Customer places an order
- Task rectangle: Restaurant accepts and prepares the order
- Decision diamond: Delivery partner available?
    - Yes path: Task: Platform assigns a driver and estimates pickup time
    - No path: Task: Wait for delivery partner availability, then loop back to the decision
- Task rectangle: Delivery partner arrives at the restaurant
- Task rectangle: Delivery partner picks up the order
- End oval: Order is delivered to the customer
### 4) Find pain points, then propose improvements
Look for delays and rework, especially around the decision point:
- Driver availability bottlenecks
- Inaccurate pickup-time estimates
- Idle time at restaurant during preparation or after meal readiness

Improvements to consider:
- Trigger dispatch immediately after restaurant acceptance
- Add preparation status updates (e.g., “started,” “nearly ready”) to improve ETAs
- Escalation rules for prolonged “No” loops (support intervention, alternative driver pool)
- Customer notifications when assignment delays exceed thresholds
### 5) Visualize the improved process
Update the diagram to show earlier dispatch, real-time status signals, and exception paths (support escalation) to make the “to-be” flow explicit and testable.

---
## Lab: Using Tools for Documenting Requirements
### 1) Establish the BRD as the project blueprint
Start with a Business Requirements Document (BRD) to define business needs, project objectives, scope boundaries, and expected outcomes before development begins. Treat the BRD as the alignment mechanism between stakeholders and the delivery team: one agreed reference for what must be delivered and why.
### 2) Draft the BRD in Microsoft Word
Create a new document, save it with a clear filename, and add the front matter:
- Document title
- Project name
- Date
- Prepared by
- Version
- Short introduction describing the purpose of the BRD

Insert a requirements table with consistent columns:
- Requirement ID
- Title
- Description
- Priority
- Stakeholders
- Functional requirements

Maintain traceability by using one ID scheme throughout (for example, BR-01 to BR-10). Format for readability: centre Requirement ID and Priority, expand rows to fit text, and apply borders or shading as needed.

The inventory management requirement typically involves the store manager and inventory/warehouse staff, while the POS requirement typically involves the store manager and cashiers. Avoid swapping these groups, since it weakens accountability and review quality.
### 3) Translate requirements into Jira Issues
Create a Jira project and enter each business requirement as an Issue for planning and tracking. Select an appropriate issue type:
- Epic for a large requirement that will be decomposed
- Story for a feature delivering user value
- Task for a discrete unit of work

In each Issue description, mirror the BRD structure: details, functional requirements as bullet points, and stakeholders. This keeps Jira work items build-ready and traceable back to the BRD.
### 4) Publish and collaborate in Confluence
Create a Confluence page titled for the BRD, recreate the same requirements table, and publish it to the correct space with appropriate access. Drive review through comments and @mentions, then rely on Page History for version control and auditability as requirements evolve.

---
# Business Analysis Practical Applications
Business analysis provides a structured way to convert organisational challenges into measurable outcomes. Across industries, analysts combine stakeholder collaboration, data-driven methods, and clear requirements to improve decisions, processes, and customer value.
## Cross-industry patterns illustrated by four scenarios
- Retail banking: Analysts diagnose customer experience pain points (slow response, limited channels, low personalisation), then recommend a CRM integrated with analytics to enable targeted products and proactive outreach, reducing churn and improving satisfaction.
- Manufacturing: Analysts map supply-chain workflows, identify bottlenecks, and recommend inventory and integration improvements (advanced inventory management, just-in-time practices, and electronic data interchange) to reduce inventory cost and stockouts while improving fulfilment.
- Healthcare: Analysts lead requirements elicitation for digitising records, recommending an electronic health record system supported by security controls to reduce errors and administrative burden.
- Financial services: Analysts perform gap analysis and requirements gathering to design a centralized business intelligence platform with real-time analytics, improving decision speed and consistency.
## Performing effective gap analysis
Gap analysis compares current performance with a defined future state to identify what prevents the target outcome. A reliable sequence includes:
1. Define the current state (process mapping, data collection, stakeholder interviews).
2. Define the desired future state (SMART goals, benchmarking, shared vision).
3. Identify and prioritise gaps (root cause analysis, impact/urgency ranking).
4. Build and execute an action plan (resources, milestones, change management).
5. Evaluate results (performance measures, feedback, continuous improvement).
## Enabling digital strategy and transformation
Digital strategy aligns digital tools with business objectives; transformation typically progresses from digitization (analog-to-digital) to digitalization (process improvement) to full transformation (business model and operating change). Success depends on customer experience focus, integration with existing systems, and sustained workforce enablement.
## Technology assessment and AI considerations
Technology assessment should cover requirements definition, market research, evaluation, pilot testing, cost-benefit analysis, risk mitigation, roadmap, and ongoing monitoring. AI can accelerate analytics, automation, and decision support, but must be governed for data quality, bias, privacy, and appropriate human oversight; shared data does not automatically become “public domain,” yet sensitive information still requires strict handling policies.

---
## Lab: Creating a Business Analysis Matrix
Use a Business Analysis Matrix to evaluate and prioritise opportunities by plotting two factors: impact (business value) and feasibility (ease of implementation). The result is a four-quadrant view that supports fast, defensible decisions.
### 1) Define the quadrants
Score each opportunity on both dimensions, then place it into one quadrant:
- High impact, high feasibility: prioritise for near-term action
- High impact, low feasibility: plan carefully; stage delivery; secure funding and sponsorship
- Low impact, high feasibility: consider as quick wins or enablers
- Low impact, low feasibility: deprioritise or park pending new evidence
### 2) Build the grid in Excel
1. Open Microsoft Excel and create a blank workbook. Save with a clear name (for example, Business analysis matrix.xlsx).
2. Set axis labels:
    - Cell A2: Feasibility
    - Cells B1:C1 (merged): Impact
    - Cell B2: High, cell C2: Low
    - Cells A3:A5 (merged): High
    - Cells A6:A8 (merged): Low
3. Align labels to centre and middle-align as needed. Add borders to the grid.

Impact across columns (B high, C low) and Feasibility down rows (A3–A5 high, A6–A8 low), the quadrants map as:
- B3:B5 high impact, high feasibility
- C3:C5 low impact, high feasibility
- B6:B8 high impact, low feasibility
- C6:C8 low impact, low feasibility
### 3) Populate the matrix using the hospital scenario
Place opportunities as follows:
- B3:B5: EHR system; telemedicine; automated appointment scheduling
- B6:B8: specialised care expansion; medical research facility; medical tourism expansion
- C3:C5: waiting room comfort; healthier cafeteria options; website upgrade
- C6:C8: niche service (e.g., alternative medicine); luxury VIP wing; solar panels
### 4) Optional export
Export the finished matrix as a PDF via File > Export > Create PDF/XPS for sharing and governance.

---
## Lab: Evaluating Digital Transformation Scenarios
Apply business analysis techniques to assess digital transformation initiatives across retail, healthcare, financial services, and manufacturing. Focus on business context, challenges, objectives, success criteria, and enabling technologies.

### 1) Review the case study and define scope
Read the scenario end to end, then state the transformation goal in one sentence. Capture scope boundaries (what is included and excluded) and the stakeholders affected by change.
### 2) Analyse key challenges
List barriers that could prevent success, grouped by theme:
- Market and customer: e-commerce pressure; rising expectations for seamless omnichannel experiences.
- Process and operations: supply chain speed; multi-site production complexity; data integration.
- Risk and governance: privacy, security, and regulatory obligations; legacy-system constraints; workforce adoption and training.
### 3) State business objectives and measurable success criteria
Write objectives as outcomes (not solutions). Then attach observable success criteria, such as:
- Retail: growth in online sales, higher customer satisfaction, improved supply chain performance.
- Healthcare: reduced diagnostic errors, improved operational efficiency, better patient outcomes and satisfaction.
- Financial services: lower operating costs, faster decisions, stronger security controls, improved customer experience.
- Manufacturing: higher production efficiency, reduced downtime, lower costs, improved product quality.
### 4) Identify key technologies and fit-for-purpose use
Map each objective to technologies that plausibly enable it:
- Cloud platforms to scale digital channels.
- Data analytics and AI/ML for personalisation, fraud detection, predictive maintenance, and optimisation.
- Automation (including RPA) for repetitive processing.
- IoT sensors for real-time equipment data.
- Digital twins to simulate assets and test workflow changes safely.
- Omnichannel integration to unify online and in-store journeys.
### 5) Validate and refine
Compare the analysis against a reference solution, reconcile gaps, and update assumptions. Record open questions and risks, then prioritise follow-up work to protect delivery outcomes.

---