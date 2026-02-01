# Domain 1: Understanding the Foundations of AI Governance

## III. ESTABLISH POLICIES AND PROCEDURES ACROSS THE AI LIFECYCLE (AIGB BOK Section I.C)

**Status**: `Completed`  <br>
**Target**: `29-Jan-2026`

AI governance is not a one-time event; it is a continuous process that must extend across the entire lifecycle of an AI system. From the moment a use case is proposed through data collection, model design, testing, deployment, monitoring, and eventual retirement, organizations need clear policies and repeatable procedures to guide decision-making, ensure accountability, and reduce risk.

### A. Policies for Oversight and Accountability Across Lifecycle Stages

#### 1. Use case assessment

Policies at this stage serve to filter out applications that are unlawful, unethical, or misaligned with organizational strategy. Every proposed use case should be backed by a clear business justification and an explanation of how it supports broader objectives.

#### 2. Risk Management

Policies in this area provide a standardized approach for identifying, assessing, and mitigating risks across the lifecycle of the system.

#### 3. Ethics by Design

Policies on ethics by design ensure that principles such as fairness, accountability, transparency, and human-centricity are woven into the foundation of every system. To make these principles tangible, design documentation should explicitly address how ethical requirements are being met.

#### 4. Data Acquisition and Use

Policies in this area establish the guardrails for lawful, ethical, and responsible use of data throughout the AI lifecycle. First, organizations must ensure that every dataset has a lawful basis for collection, whether through informed consent, contractual rights, or another valid legal ground. Privacy by design principles should guide data practices, emphasizing minimization, purpose limitation, and, where appropriate, anonymization to protect individual rights.

#### 5. Model Development

Policies at this stage ensure that those choices are accountable, transparent, and reliable. Governance requires more than technical performance; it requires a disciplined process that can be explained, reproduced, and trusted.

#### 6. Training and Testing

Policies at this stage create consistency in how models are evaluated and ensure that only systems meeting defined standards move forward.

Testing results must be carefully documented, including any corrective actions taken in response to identified issues. This creates an auditable trail of accountability and ensures that lessons learned can inform future model development.

#### 7. Deployment and Monitoring

Policies in this stage ensure that deployment is handled safely and that the system continues to perform reliably over time.

#### 8. Documentation and Reporting

Policies at this stage ensure that every decision, test, and corrective action can be reconstructed and evaluated if questions arise. Comprehensive documentation should be required at every stage of the lifecycle, from early impact assessments and design records to testing logs, monitoring results, and retraining reports.

Audit trails must be maintained in a way that makes them accessible to compliance teams, auditors, and regulators, ensuring that governance is not just asserted but demonstrable.

#### 9. Incident Management

Policies in this area ensure that when issues arise, they are detected quickly, escalated through proper channels, investigated thoroughly, and remediated effectively. Clear definitions are the first step. Incidents should be categorized in advance, whether a bias event, security breach, model failure, or misuse, so that teams understand the nature and severity of what they are addressing.



**Exam Tip**: Think of lifecycle governance as a chain: if one link (like data governance or monitoring) is weak, the entire governance program is compromised. Policies must cover every stage to be effective. 

**Exam Scenario**: A financial services company builds an AI system for loan approvals. The team invests heavily in data governance, making sure the training data is well-documented and bias-tested. They also publish clear policies and train staff on proper use. However, once the system is deployed, they skip post-market monitoring because they assume the controls at launch are enough. Months later, unnoticed drift in the live data begins to skew approvals, disproportionately rejecting applicants from certain demographics. On the exam, the correct answer is to recognize this as a lifecycle governance failure. Even though the data and policy links in the chain were strong, the missing link, continuous monitoring, compromised the entire governance program. The governance response should stress that policies and controls must be applied consistently across all stages of the AI lifecycle to prevent gaps from undermining the whole system.



### B. Updating Privacy and Security Policies for AI

#### 1. Why updates are necessary

- Data driven AI
- Opacity
- Dynamic risks
- Regulatory shift

#### 2. Privacy policy updates for AI

- Lawful basis for data use (processing)
- Purpose limitation
- Data minimisation
- Sensitive data handling
- Individual rights management
- Privacy impact assessments (AI Specific Privacy Impact Assessment - AIPAs)
- Retention and Deletion

#### 3. Security policy updates for AI

- Data provenance and lineage
- Model security
- Access controls
- Monitoring and logging
- Incident response
- Third party risk
- Watermarking and detection

#### 4. Integration with broader governance

Revised policies should align directly with existing enterprise risk management (ERM) frameworks, embedding AI-specific risks into the same processes that oversee financial, operational, and compliance risks. They should also connect with information security management systems (ISMS), such as those based on ISO/IEC 27001, so that AI is treated as part of the broader security posture rather than as an exception.



**Exam Tip**: Be prepared to distinguish between updating existing policies (e.g., extending privacy impact assessments to cover AI) and creating new policies (e.g., adversarial defense standards). The exam will likely test your ability to identify how AI changes privacy and security obligations. 

**Exam Scenario**: A hospital introduces an AI system that predicts patient readmissions. The compliance team extends its existing privacy impact assessment (PIA) process to include the AI’s use of sensitive health data, an example of updating existing policies. However, the system is later targeted with adversarial prompts that trick it into revealing personal details. Because the hospital had no adversarial defense policy in place, the issue wasn’t caught until after a regulator raised concerns. On the exam, the correct answer is to recognize the distinction: privacy risks required extending an existing policy (PIAs), while adversarial attacks required creating a new policy standard. Governance must cover both, updating legacy processes where AI intensifies old risks, and designing new policies where AI introduces novel ones.



### C. Third-Party Risk Policies

#### 1. Procurement policies

Procurement policies should begin with vendor due diligence. Vendors must be required to disclose model provenance, data sources, bias testing results, limitations, and compliance with applicable laws. These disclosures allow organizations to make informed decisions before integration. Policies must also embed contractual safeguards, including liability allocations, indemnification, warranties, security obligations, and audit rights. Contracts become the vehicle through which governance expectations are enforced.

In addition, procurement should include transparency requirements. Vendors should provide documentation such as model cards or system cards, along with commitments to ongoing monitoring and reporting. 

**Model Card Template:** https://huggingface.co/docs/hub/en/model-cards

#### 2. Supply chain policies

Policies begin with supply chain mapping, requiring organizations to maintain visibility into the origin of datasets, models, and underlying infrastructure. With this transparency, potential weaknesses can be identified early rather than discovered only after harm occurs.

#### 3. Human Resources policies

At the core are acceptable use policies that specify which AI tools may, and may not, be used in the workplace. These rules prevent staff from turning to unvetted systems that could introduce security or compliance risks. Complementing this, mandatory training and awareness programs ensure that everyone understands responsible AI use, privacy obligations, and the procedures for reporting concerns.

#### 4. Governance implications

Third-party relationships often represent the weakest link in AI governance. A single vendor’s failure to comply with regulations, a supplier providing a biased dataset, or an employee misusing a generative AI tool can undermine even the most carefully designed internal framework.

**Exam Tip**: Remember the three pillars of third-party risk: 

- Procurement → Vendor transparency and contracts. 
- Supply chain → End-to-end visibility and monitoring. 
- HR → Training, acceptable use, and contractor oversight. 

**Exam Scenario**: A defense contractor deploys an AI tool purchased from a vendor. During an audit, regulators find gaps on three fronts. First, procurement only checked pricing and features but failed to secure strong vendor contracts with transparency on data use. Second, the supply chain was not monitored end-to-end, so a subcontractor quietly swapped in an open-source model with unclear licensing. Third, HR provided no training or oversight for contractors, and one used the tool outside approved use cases. On the exam, the correct answer is to connect these failures to the three pillars of third-party risk: procurement, supply chain, and HR. Governance requires vendor due diligence and contracts, visibility into all upstream and downstream dependencies, and training plus oversight of employees and contractors.























