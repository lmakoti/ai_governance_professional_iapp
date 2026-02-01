# Domain 2: Understanding How Laws, Standards, and Frameworks Apply to AI

## I. HOW EXISTING DATA PRIVACY LAWS APPLY TO AI (AIGB BOK Section II.A)

**Status**: `In Progress`  <br>
**Target**: `1-Feb-2026`

AI governance cannot exist in a vacuum. It must operate within the legal, regulatory, and standards-based environments that shape how AI is designed, deployed, and managed. Tools such as the **OECD AI Principles, the NIST AI Risk Management Framework, and ISO/IEC standards** provide guidance in how AI should be treated for legal and ethical compliance. 

AI does not exempt organizations from privacy obligations, it intensifies them. By applying data protection rules to AI contexts, organizations can reduce regulatory exposure, protect individuals from harm, and demonstrate trustworthiness to customers and regulators alike

### A. Notice, Choice/Consent, and Purpose Limitation in AI Contexts

#### 1. Notice

Notice means giving individuals clear, accessible information about how their data is being collected, used, and shared. Organizations should provide layered notices, offering simple, high-level explanations for end users and more detailed technical documentation for experts and regulators.

#### 2. Choice and Consent

Choice and consent focus on giving individuals meaningful control over whether and how their data is used. This principle becomes complicated in the AI context. Consent may not be truly informed if it is drafted too broadly, particularly when the future uses of data are uncertain.

Where obtaining meaningful consent is impractical, organizations may need to rely on alternative lawful bases for processing, such as legitimate interests or contractual necessity, but they must document and justify those choices.

#### 3. Purpose Limitation

Purpose limitation requires that data be collected only for explicit, specified purposes and not reused in ways that are incompatible with those purposes.

Before data or models are repurposed, organizations should conduct compatibility assessments to determine whether the new use aligns with the original intent and with applicable laws.



### B. Data Minimization and Privacy by Design for AI

#### 1. Data minimisation in AI

Data minimization requires that organizations collect and process only the information necessary for a clearly defined and declared purpose.

Feature selection techniques should be applied to limit variables to those truly necessary for the stated purpose, and the inclusion of sensitive or special category data should be prohibited unless it is strictly essential and permitted by law.

#### 2. Privacy by Design (PbD) in AI

Privacy by Design means embedding privacy protections directly into the design, development, and deployment of AI systems rather than bolting them on after the fact. This principle is particularly important in AI because probabilistic outputs, model drift, and evolving system behaviour introduce risks that traditional IT systems may not face.

#### 3. The intersection of data minimisation and PbD

Data minimization and Privacy by Design (PbD) are closely connected. Minimization sets the boundary: organizations should only collect and use the data that is necessary for a specific purpose. PbD ensures that boundary is enforced by embedding minimization into the system’s architecture, workflows, and policies.



### C. Controller Obligations in AI Contexts

#### 1. PIAs/Impact Assessments

Privacy Impact Assessments (PIAs), also known in the GDPR as Data Protection Impact Assessments (DPIAs), are tools for evaluating risks to individuals’ rights before personal data is processed.

#### 2. Processor management

Processor management becomes even more critical. Contracts must address AI-specific risks, such as prohibiting processors from reusing training data for unrelated purposes, requiring transparency in how data is handled, and ensuring processors uphold fairness and security standards.

#### 3. Cross-border data transfers

Cross-border data transfers occur when personal data is moved outside the jurisdiction where it was originally collected, for example, from the EU to the United States. Privacy laws require that such transfers be supported by lawful mechanisms to protect individuals’ rights.

#### 4. Data Subject Rights (Data Subject Access Requests - DSARs)

Individuals have legally protected rights over their personal data, including the ability to access it, correct inaccuracies, request deletion, transfer it to another service (portability), or object to certain processing.

#### 5. Incident management

Incident management requires organizations to have clear processes for identifying, responding to, and remediating security or privacy incidents.

#### 6. Breach notification

Breach notification requires data controllers to alert regulators, and in some cases, affected individuals, when a personal data breach occurs.

Legal timeframes still apply. For example, under the GDPR, a controller must notify the supervisory authority within 72 hours of becoming aware of a breach.

#### 7. Record keeping

Record-keeping is a core obligation for controllers, requiring them to maintain detailed documentation of their data processing activities.

Strong governance means keeping audit-ready documentation, such as model cards, data lineage reports, and monitoring records, so regulators and stakeholders can verify compliance.



### D. Special / Sensitive Data Requirements

AI systems often depend on special categories of personal data, such as biometrics, health records, or racial/ethnic identifiers, that carry heightened legal and ethical obligations. Because misuse can result in lasting harm, global privacy laws (e.g., GDPR Article 9, HIPAA, LGPD) impose stricter safeguards when this type of data is processed.

Data may only be processed for the purpose originally disclosed, and any repurposing without renewed consent or another lawful basis undermines both compliance and trust.































































