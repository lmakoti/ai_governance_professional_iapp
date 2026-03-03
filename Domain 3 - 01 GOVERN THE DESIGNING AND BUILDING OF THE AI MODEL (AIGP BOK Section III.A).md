# Domain 3: Governing AI Development

## I. Govern The Designing and Building of the AI Model (AIGP BOK Section III.A)

**Status:** `Completed`<br>
**Target:** `02-Mar-2026`

The design and build phase of AI is where governance has its deepest influence. Decisions made here on data selection, model architecture, training methods, and risk controls shape the system’s future reliability, fairness, and compliance. **If governance is weak at this stage, flaws can become hardwired into the model and amplified at scale once deployed.**

### A. Define the business context and use case

Before any technical work begins, governance requires teams to pause and establish a shared understanding of why the AI system is being built and what it is meant to achieve. This alignment anchors every downstream design decision in a framework of legitimacy, accountability, and compliance.

By clarifying the business context at the outset, governance prevents “AI for AI’s sake” and embeds accountability into the foundation of the system.

### B. Perform / Review Impact Assessment

A robust impact assessment doesn’t just catalog risks, it forces an organization to confront the why, how, and who of an AI system. These elements serve as the backbone of a structured, defensible review, ensuring that risks are anticipated, documented, and addressed before deployment.

**Exam Tip:** Impact assessments aren’t just compliance checkboxes, they are strategic safeguards that build trust, enable confident innovation, and prevent costly financial and reputational failures. 

**Exam Scenario:** A case may describe adding new sensitive data or features to a system without updating the impact assessment. The right choice is to refresh the DPIA/AIA so risks are documented, safeguards are applied, and compliance is maintained.

#### Types of Impact Assessments

- **Algorithmic Impact Assessment (AIA):** An AIA is a broader review that goes beyond privacy to examine fairness, bias, transparency, and human rights impacts of an AI system.
- **Data Protection Impact Assessment (DPIA)**: A DPIA is mandated under the **GDPR** (Articles 35–36) whenever the processing of personal data is “likely to result in a high risk to the rights and freedoms of natural persons.”
- **EU AI Act Impact Assessment:** Under the **EU AI Act**, high-risk AI systems, such as those used in critical infrastructure, healthcare, education, or law enforcement, are subject to mandatory conformity assessments.
- **Sector-Specific Assessments:** 

### C. Identify Applicable Laws

#### 1. Privacy and Data Protection Laws

- **Consent and Lawful Basis**: Repurposing customer data collected for billing or support into training material for predictive analytics may violate these rules unless consent is renewed or another lawful ground is documented.
- **Data Minimization and Purpose Limitation:** collect only what is necessary, and use it only for clearly defined purposes.
- **Sensitive and Special Category Data** 
- **Cross-Border Data Transfers**
- **Data Subject Rights:** Some frameworks also grant the right to opt out of automated decision-making. This means AI systems must be designed to accommodate deletion requests, generate explanations for outcomes, and support contestability.
- **Sector-Specific Considerations (HIPAA)**

#### 2. Anti-Discrimination and Employment Laws

AI systems that touch employment, credit, or other opportunity-related decisions fall directly under anti-discrimination and equal opportunity laws. These laws are designed to ensure fairness in access to ***jobs, promotions, housing, and financial services***, and they apply equally when decisions are made or assisted by algorithms.

Anti-discrimination and employment laws make clear that AI cannot be treated as a neutral “black box”; organizations must proactively demonstrate that their systems are fair, lawful, and equitable by embedding these safeguards from the outset.

#### 3. Consumer Protection Laws

Consumer protection laws are built to shield individuals from being misled, manipulated, or harmed by unfair business practices, and those same principles apply to AI-driven products and services.

Consumer protection laws also address the way systems are presented to users. **Dark patterns** (interfaces intentionally designed to manipulate behavior) are under increasing regulatory scrutiny. In the AI context, this might include chatbots that conceal the fact they are automated, or recommendation systems that nudge consumers toward higher-priced options without disclosure.

Consumer-protection laws treat AI as a market-facing product: overpromising, obscuring limits, or using manipulative interfaces can trigger enforcement, lawsuits, and reputational damage, so governance ensures AI is presented honestly, transparently, and fairly.

#### 4. Product Liability and Safety Laws

Product liability and safety laws rest on a simple principle: companies are responsible for making sure their products are safe and reliable before they ever reach consumers. With AI, that responsibility takes on heightened urgency, particularly where system failures can trigger serious consequences such as physical injury, financial loss, or other significant harms.

Governance must ensure that safety requirements are woven into every stage of the AI lifecycle, including system design, model training, validation, deployment, and ongoing monitoring.



#### 7. Governance Role in Identifying Applicable Laws

- **Mapping Jurisdictions**: Governance begins by mapping the geographic scope of the AI system: where it is developed, where it will be deployed, and where its outputs may affect individuals.
- **Identifying Overlapping Laws**: AI systems rarely fall under a single framework. Overlaps are common, such as a system that must comply with both GDPR (data protection) and the EU AI Act (high-risk AI governance).
- **Incorporating Compliance into Design**: Regulatory requirements cannot be bolted on after development. Governance ensures that compliance is translated into design specifications, technical controls, and documentation practices from the outset.
- **Engaging Legal, Compliance, and Risk Functions Early**: Finally, governance mandates cross-functional collaboration. Legal teams interpret the rules, compliance teams operationalize them, risk managers assess trade-offs, and engineers implement technical controls.

**Exam Tip**: Legal mapping during development prevents downstream compliance crises. Embedding regulatory requirements early ensures systems are lawful, defensible, and market-ready. 

**Exam Scenario**: The question might show a company reusing customer data for training without checking whether consent covers the new use. The correct response is to recognize the legal gap, map applicable laws, and ensure compliance before reuse.



### D. Apply Policies, Best Practices, and Ethics in Design/Build

Applying policies, best practices, and ethical considerations ensures AI systems are purposeful, fair, explainable, and accountable from the start.

#### 1. Purpose Definition

The purpose must be stated in precise, plain language that captures what the system is designed to do. This documentation anchors design and deployment decisions and becomes part of the compliance record.

AI systems frequently evolve beyond their original scope, often without the governance needed to ensure new uses are lawful or ethical.

The purpose must be connected to organizational strategy and compliance duties.

#### 2. Requirements Gathering

A well-governed requirements phase prevents misalignment, reduces costly redesigns, and embeds accountability from the outset.

AI systems must be designed to satisfy a spectrum of requirements, not just technical specifications. This means gathering input from engineering teams, compliance officers, legal advisors, ethicists, and business leaders.

For AI, governance expands the scope to include non-functional requirements: fairness, explainability, privacy, security, and robustness. These qualities determine whether the system will be trusted, lawful, and resilient under scrutiny.

Requirements gathering must also account for the perspectives of those who will use, regulate, or be affected by the AI system. This includes employees, customers, auditors, and regulators.

#### 3. Architecture / Model Selection

The choice of architecture and model type is not only a technical decision, it is a governance decision. The architecture determines how the AI system will function, how transparent it will be to stakeholders, and how defensible it will be to regulators.

Different contexts demand different levels of interpretability and complexity. In high-stakes environments such as healthcare diagnostics or credit decisions, governance may favor interpretable models (e.g., decision trees or logistic regression) over complex black-box systems like deep neural networks, **even if the latter offer marginally higher accuracy.**

Pure accuracy is rarely the sole objective in AI governance. Models must also be explainable to regulators and users, robust to adversarial manipulation, and resilient across diverse data inputs.

AI models are resource-intensive, and large-scale training can generate significant environmental and financial costs. Governance increasingly requires considering the sustainability of model choices, balancing performance gains against compute demands and environmental factors.

#### 4. Human Oversight

The level of human oversight required for an AI system should always align with the risk it poses, and governance plays a central role in defining and enforcing that oversight.

In a **Human-in-the-Loop (HITL)** model, a person must review and approve each AI-generated decision before it is finalized. This is common in high-stakes contexts, such as a doctor verifying an AI-assisted medical diagnosis. A **Human-on-the-Loop (HOTL)** approach shifts the role toward *active monitoring* rather than pre-approval. Here, humans continuously observe system outputs and retain the ability to intervene if the system begins to drift or malfunction; for instance, fraud analysts monitoring suspicious transaction alerts in real time. Finally, a **Human-in-Command (HIC)** model ensures that ultimate authority rests with people, even if the AI operates with significant autonomy. This gives designated individuals the power to override or shut down the system altogether if harmful outcomes arise, such as safety officers halting autonomous vehicle operations during an unexpected anomaly.

Oversight is only effective if clear escalation procedures exist. When an AI tool produces questionable outputs, employees must know exactly how to report issues and who is responsible for reviewing them.

#### 5. Data Analysis

Governance ensures datasets are accurate, complete, and representative of the populations or conditions the system will encounter.

Bias may enter through sampling errors, historical inequities, or inappropriate proxies (e.g., using postal codes as stand-ins for socioeconomic status).

Transparency demands that organizations track where data came from, how it was processed, and how it was transformed before training. This “data lineage” allows auditors, regulators, and internal reviewers to understand how outcomes are shaped.

#### 6. Metric and Threshold Evaluation

Governance requires that evaluation goes beyond raw accuracy. Metrics such as precision (avoiding false positives), recall (avoiding false negatives), fairness (ensuring equitable outcomes across groups), and robustness (resilience against adversarial or unexpected inputs) must all be considered.

<img src="https://www.researchgate.net/profile/Angela-Martin-6/publication/358029719/figure/fig2/AS:1115056309846018@1642861549455/Evaluation-metrics-accuracy-precision-recall-F-score-and-Intersection-over-Union.png" style="zoom:50%;" />



Thresholds translate abstract metrics into operational standards. These thresholds determine the acceptable trade-offs between performance and risk.

#### 8. Operational Controls

Policies and principles only become meaningful when they are enforced through practical controls. Operational controls translate governance goals into daily practices that guide how systems are built, modified, and reviewed.

Responsible AI governance begins at the earliest stages of development, requiring both technical and procedural safeguards to ensure systems are built with accountability in mind.

For operational controls to have real value, they must be consistent and verifiable. Governance ensures that controls are applied systematically across projects, not at the discretion of individual teams.

Embedding governance into design and build is not an academic exercise, it is a safeguard against risks that are far more costly and damaging when addressed later.

**Exam Tip**: Embedding policies and ethical standards into design turns abstract principles into technical guardrails, making fairness, explainability, and accountability part of the system’s DNA. 

**Exam Scenario**: An exam prompt could ask what to do when an AI model works well technically but has no transparency or fairness safeguards. The right answer is to apply ethics through documented standards, bias testing, explainability tools, and oversight before release.



### E. Risk Management in AI Design and Build

Risk management is a core duty of AI governance at design/build. It turns scattered worries about probabilistic outputs, changing data, and large-scale deployment into a disciplined process that identifies plausible harms, ranks them, and reduces them before release.

#### 1. Probability–Severity Matrix

A practical starting point is the probability–severity matrix: each identified risk is placed on a grid according to how likely it is to occur and how bad the outcome would be if it did.

Governance makes this exercise repeatable and defensible. Scales are defined upfront (what counts as “likely,” what counts as “severe”), scoring and rationales are recorded, and residual-risk acceptances are owned by the right level of authority.

![](https://www.researchgate.net/publication/362606910/figure/fig1/AS:11431281083834215@1662818201103/Matrix-of-likelihood-of-occurrences-and-severity-of-loss.png)

#### 2. Risk-Mitigation Hierarchy

The risk-mitigation hierarchy provides a stepwise method for addressing AI risks. The principle is simple: tackle risks at their source whenever possible, and rely on human oversight only as a last resort.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/NIOSH%E2%80%99s_%E2%80%9CHierarchy_of_Controls_infographic%E2%80%9D_as_SVG.svg/1920px-NIOSH%E2%80%99s_%E2%80%9CHierarchy_of_Controls_infographic%E2%80%9D_as_SVG.svg.png)

Governance enforces the principle that risks should be mitigated structurally, through elimination, substitution, or engineering, before being passed to human judgment. This approach prevents overreliance on human operators as a “safety net,” which can create fatigue and shift accountability away from design.

#### 3. Stakeholder Mapping

Governance requires a deliberate stakeholder-mapping exercise that identifies who is affected, how they are affected, and what kinds of risks or benefits they may experience. Done well, this widens the lens beyond the development team, reduces blind spots, and lends legitimacy to subsequent risk decisions.

Stakeholder mapping turns fairness into an enforceable control: maintain a living register of affected groups with owners, contact paths, and stated concerns;

**Exluded in notes:** 4. Use-Case Evaluation, 5. Benchmarking, 6. Pre-Deployment Pilots / Testing

**Exam Tip**: Strong risk management in design is proactive, not reactive. By testing assumptions, stress-testing systems, and setting thresholds early, you prevent flaws from being amplified at scale. 

**Exam Scenario**: The scenario might show a team labeling a risk as “high” but proceeding anyway without safeguards. The correct answer is to apply a probability–severity matrix, escalate critical risks, and block launch until mitigation is in place.

### F. Document the Design/Build Process

thorough documentation ensures traceability, accountability, and auditability—allowing regulators, auditors, and stakeholders to verify that compliance and risk management obligations were met.

#### 1. Why Documentation Matters

**Compliance evidence:** Regulators increasingly demand not only outcomes but also evidence of the process that produced them. For example, under GDPR, organizations must maintain Data Protection Impact Assessments (DPIAs) when high-risk personal data processing is involved.

Documentation opens that box by showing how the system was built, what data it used, and why specific decisions were made.

Documentation provides continuity, helping new teams understand why earlier choices were made and ensuring that institutional knowledge is preserved even as personnel change.

#### 2. What to Document

Comprehensive documentation ensures that every decision is transparent, reproducible, and defensible under scrutiny.

Documentation must capture the full set of requirements: technical, legal, ethical, and organizational.

documentation must include data sources, preprocessing steps, quality assessments, and bias testing results.

Documentation should define where and how humans remain accountable. This includes escalation paths, intervention protocols, and assigned roles for monitoring outputs.

#### 3. Tools for Documentation

**Model Cards:** Model cards are concise summaries that describe a model’s purpose, performance, and limitations.

Datasheets for Datasets: Datasheets provide a structured way to document datasets: the raw material for AI.

**System Cards:** While model cards focus on individual models, system cards document the end-to-end AI system, showing how multiple components interact.

**Impact Assessments:** Impact assessments, such as DPIAs under GDPR, Algorithmic Impact Assessments (AIAs), or healthcare-specific reviews under HIPAA, formalize the evaluation of risks. They require teams to document the system’s purpose, risks to individuals and society, and mitigation strategies.

**Version Control Logs:** Version control is essential for traceability. Logs record every change to datasets, models, and risk controls, creating an auditable history of the system’s evolution.





















































































































































