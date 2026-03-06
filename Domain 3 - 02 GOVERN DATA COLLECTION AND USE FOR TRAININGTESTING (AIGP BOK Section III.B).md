# Domain 3: Governing AI Development

## II. GOVERN DATA COLLECTION AND USE FOR TRAINING/TESTING (AIGP BOK Section III.B)

**Status:** `In Progress`<br>
**Target:** `XX-Mar-2026`

This competency emphasizes policies and controls that ensure data is lawfully obtained, ethically sourced, high-quality, representative, and well-documented. It also includes requirements for protecting sensitive information, applying privacy-enhancing techniques, and testing datasets for bias or other risks before use.

### A. Data Governance Requirements

#### 1. Lawful Rights to Collect and Use Data

Governance must begin by verifying that organizations have the lawful rights to collect, process, and use data for training and testing. This means establishing not just technical suitability,

**Considerations**

- Legal Basis for Processing:
- Documenting data provenance
- Licensing and intellectual property rights
- Cross-border data transfers

**Lawful rights to collect and use data** are the entry ticket to responsible AI development. Governance ensures that every dataset is backed by a valid legal basis, documented provenance, confirmed licensing rights, and compliant transfer mechanisms, laying the groundwork for trustworthy and legally defensible AI.

#### 2. Quality Assessment

Governance ensures that datasets are rigorously evaluated for accuracy, completeness, consistency, and timeliness before they are approved for training or testing.

**Considerations**

- Accuracy
- Completeness
- Consistency
- Timeliness

**Quality assessment** ensures that AI systems are built on data that is accurate, complete, consistent, and current. By embedding these standards into governance, organizations prevent flawed datasets from undermining performance, fairness, and trust before models even reach production.

#### 3. Quantity Assessment

Insufficient or unbalanced datasets can undermine performance, fairness, and scalability, leaving systems brittle or biased once deployed.

**Considerations**

- **Sufficiency**: Too little data leads to underfitting, where the model fails to generalize and performs poorly outside of narrow test conditions.
- Balance
- Scalability

Quantity assessment ensures datasets are large enough, balanced enough, and scalable enough to support reliable, fair, and context-appropriate AI systems.

#### 4. Integrity

Data integrity is the backbone of trustworthy AI. Even if data is lawful, high-quality, and sufficient, it loses value if it cannot be trusted to remain secure, consistent, and verifiable.

**Considerations**

- Data Security
- Version control
- Auditability

**Exam Tip:** Integrity safeguards make AI datasets secure, traceable, and defensible. By embedding security, version control, and auditability into governance, organizations protect against both external threats and internal uncertainty, ensuring that the data foundation of AI systems remains trustworthy over time.

#### 5. Fit-for-Purpose

Even when data is lawful, high-quality, sufficient, and secure, it must also be fit for the specific purpose of the AI system. Governance ensures that data is not only technically usable but also relevant, appropriate, and validated against the objectives of the model.

**Considerations**

- Relevance
- Appropriateness
- Validation

Fit-for-purpose assessments ensure that datasets are aligned, appropriate, and validated for the intended AI use case.

#### 6. Governance Role in Data Collection and Use

Governance ensures that data used for training and testing is not only technically sound but also legally compliant, ethically defensible, and transparently documented.

**Considerations**

- Mandating Legal, Ethical, and Quality Reviews
- Establishing Cross-Functional Review Boards
- Documenting Findings in Transparency Tools

**Exam Tip**: Governance ensures datasets have lawful rights, ethical justification, and technical safeguards. Without this, even the best models risk being unusable, unlawful, or indefensible. 

**Exam Scenario**: The exam may describe a high-performing model trained on medical data that was collected without patient consent. The correct response is to recognize that despite its accuracy, the model cannot be deployed unless the dataset has proper legal rights, ethical approvals, and security safeguards in place.



### B. Data Lineage and Provenance

Data lineage (the technical flow of data through systems) and data provenance (the origin and ownership of the data). Together, they provide the audit trail needed to defend data practices to regulators, auditors, customers, and courts.

#### 1. Data Lineage

Data lineage provides the end-to-end record of how data flows through the AI lifecycle, from initial collection all the way to eventual deletion. It captures every step of the process: *ingestion, cleaning, transformation, training, testing, storage, and retirement*.

Governance embeds lineage into AI workflows by requiring formal documentation of all data movements. This often includes maintaining lineage maps that visually represent how data flows from one stage to another. Finally, governance links lineage records directly to model documentation, such as model cards, so that decisions about a model can be traced back to the precise data flows that informed its training.

#### 2. Data Provenance

Data provenance documents the origin, ownership, and collection conditions of the dataset, ensuring that organizations know not just how data moved through their systems, but also where it came from, who owns it, and under what circumstances it was gathered.

Governance requires organizations to systematically record data sources, noting whether information was collected first-hand, purchased from a third-party vendor, or drawn from publicly available repositories.

#### 3. Combined Role of Lineage and Provenance

While lineage and provenance serve different purposes, together they form the full accountability framework for AI data governance. Lineage shows the technical journey of data through systems, while provenance establishes its origins and ownership. Combined,

**Considerations**

- Auditability
- Reproducibility
- Risk management
- Transparency

Lineage and provenance are two sides of the same coin. Lineage traces the “how,” provenance establishes the “where,” and together they provide the evidence needed to ensure AI systems are auditable, reproducible, risk-aware, and transparent.

#### 4. Documentation Tools

Lineage and provenance provide the foundation for accountable AI data practices, but their value depends on being captured and communicated through the right documentation tools.

**Tools**

- Datasheets for datasets
- Lineage graphs
- Metadata repositories
- Audit logs

**Exam Tip**: Lineage tracks the “how” and provenance the “where.” Together they form the audit trail that makes AI data practices accountable, reproducible, and legally defensible. 

**Exam Scenario**: The exam may give you a case where a model produces biased results, and you’re asked how to prove whether the issue came from data preprocessing or from the original dataset. The right move is to point to lineage (the steps taken in preparing and transforming the data) and provenance (the dataset’s original source), which together provide the accountability trail regulators and auditors expect.

### C. Plan and Perform Training & Testing

Governance requires not only that testing occurs, but that it is planned, documented, and reviewed across multiple dimensions.

#### 1. Unit Testing

Unit testing is the first line of defense in ensuring that AI systems function reliably. It *focuses on validating individual components* of the AI pipeline, such as preprocessing modules, feature extraction routines, or algorithmic functions, before they are combined into larger systems.

#### 2. Integration Testing

Integration testing ensures that those components work together as a cohesive system. It *examines the interactions between modules*, such as data ingestion, preprocessing, model training, and output generation, to verify that they connect smoothly and function as intended.

#### 3. Validation Testing

Validation testing evaluates whether the trained model can generalize beyond the data it was trained on. By using *holdout sets, cross-validation, or external validation datasets,* organizations test how the model performs on unseen data, an essential step to prevent overfitting and confirm that results are robust in real-world conditions.

#### 4. Performance Testing

Performance testing evaluates whether an AI system actually *delivers the results it was designed to achieve*. While validation testing ensures generalizability, performance testing focuses on measuring the system against specific, pre-defined metrics that reflect the business, ethical, and regulatory requirements of the use case.

#### 5. Security Testing

Security testing evaluates whether an AI system can withstand deliberate or accidental attempts to compromise it. Unlike traditional software, AI models are vulnerable to unique attack vectors such as adversarial inputs, data poisoning, or model inversion, where attackers exploit the statistical nature of models to manipulate outputs or extract sensitive information.

#### 6. Bias Testing

Bias testing is one of the most critical aspects of AI governance because it evaluates whether a system produces fair and equitable outcomes across different demographic groups or other protected categories.

#### 7. Interpretability / Explainability Testing

Interpretability and explainability testing evaluates whether an AI system’s decision-making can be understood in terms meaningful to stakeholders.

**Exam Tip**: Testing isn’t one-off. It spans unit, integration, validation, performance, security, bias, and explainability checks to prove models are accurate, fair, resilient, and trustworthy. 

**Exam Scenario:** The exam may describe a team that only ran accuracy tests before launch but skipped bias or security checks. The correct answer is to recognize that governance requires ongoing, multi-layered testing, including fairness, robustness, and explainability, not just one-time accuracy tests.



### D. Identify and Manage Issues & Risks During Training/Testing

#### 1. Types of Issues and Risks

Governance plays a key role in ensuring that these challenges are systematically identified, categorized, and resolved rather than ignored or patched in ad hoc ways. By recognizing the types of issues that can arise, organizations can anticipate risks and put processes in place to mitigate them.

**Considerations**

- Data Issues
- Modeling Issues
- Bias and Fairness Issues
- Security Issues
- Operational Issues
- Ethical and Legal Risks

#### 2. Risk Management Practices

Identifying risks during training and testing is only the first step. Organizations must also have structured practices for managing them. Governance ensures that issues are not addressed inconsistently or reactively, but through a disciplined framework that captures, analyzes, prioritizes, remediates, and escalates risks as appropriate.

**Considerations**

- Monitoring and Logging
- Root Cause Analysis
- Risk Prioritisation
- Remediation
- Escalation

Risk management during training and testing only becomes credible when supported by governance. Governance requires that every issue, whether data-related, modeling, fairness, or security, be documented with its root cause, remediation, and outcome, creating a traceable record for regulators, auditors, and future teams.

Managing risks during training and testing is not just about good engineering, it is central to protecting people, ensuring compliance, and safeguarding organizational credibility. Governance transforms risk management from ad hoc fixes into a systematic process that prevents hidden failures, demonstrates due diligence, and builds a culture of continuous improvement.

**Exam Tip**: Governance turns risk handling into a system, not an ad hoc fix. Issues are logged, analyzed, remediated, escalated, and documented so nothing slips through unnoticed. 

**Exam Scenario**: The exam may present a situation where an AI system shows recurring data quality errors, but the team only patches them informally without logging or escalation. The correct answer is to recognize that proper governance requires a structured process, including documenting the issue, analyzing root causes, remediating, and escalating if needed, so risks don’t go untracked.

### E. Document Training/Testing

In AI governance, testing only becomes meaningful when it is accompanied by strong documentation. Records transform testing from an internal exercise into evidence that can be scrutinized, reproduced, and defended. Without them, even the most rigorous evaluation may be dismissed as unverifiable.

**Considerations**

- Validating Outcomes
- Demonstrating Compliance
- Managing Residual Risk
- Documentation Infrastructure























































