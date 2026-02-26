# Domain 3: Governing AI Development

## I. Govern The Designing and Building of the AI Model (AIGP BOK Section III.A)

**Status:** `In Progress`<br>
**Target:** `XX-Feb-2026`

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

































































































































































