# Domain 1: Understanding the Foundations of AI Governance

## III. ESTABLISH POLICIES AND PROCEDURES ACROSS THE AI LIFECYCLE (AIGB BOK Section I.C)

**Status**: `In Progress`  <br>
**Target**: `28-Jan-2026`

### A. Defining Roles and Responsibilities for AI Governance Stakeholders

AI governance only works if it is owned and executed by people, not just written in a policy. To avoid ambiguity, organizations must define who is responsible, accountable, consulted, and informed (RACI) for every stage of the AI lifecycle.

#### 1. Executive Leadership (Board, C-Suite)

They are responsible for approving governance frameworks, allocating budgets, and ensuring the right policies and controls are in place. Without clear direction and commitment from the top, AI governance efforts often lack legitimacy. 

#### 2. AI Governance Committee

The AI Governance Committee acts as the central decision-making and **oversight body for AI use** within the organization. It serves as the link between the vision set by executive leadership and the day-to-day practices carried out by technical and business teams.

#### 3. Ethics Board

The Ethics Board provides specialized oversight for AI projects that carry significant ethical, social, or human rights implications. The Ethics Board’s responsibilities include **reviewing high-risk or high-impact AI use cases**, for example, tools that affect hiring, healthcare decisions, financial eligibility, or law enforcement. Key roles include providing **independent** advice on whether proposed AI systems align with the organization’s stated values

#### 4. Legal, Risk and Compliance Teams

The Legal, Risk, and Compliance functions act as the organization’s regulatory compass for AI. Their core responsibilities include interpreting laws and regulations such as GDPR, HIPAA, the EU AI Act, and state-level privacy rules, as well as standards and frameworks like the NIST AI Risk Management Framework or ISO/IEC AI guidance.

#### 5. Data Scientists/AI Developers

Their role goes beyond writing code or training models; they are responsible for ensuring that governance is woven directly into the design and development process. This concept, sometimes called “governance by design,” means that fairness, transparency, and accountability must be integrated from the earliest stages, not bolted on afterward.

#### 6. IT, Security and Data Governance Teams

The IT, security, and data governance teams are the guardians of the data and infrastructure that power AI systems. Since AI is only as good as the data it is trained and operated on, their role is central to protecting against one of the biggest drivers of AI risk: poor or unsafe data handling. IT, security, and data governance teams form the first line of defense, ensuring that the foundation on which AI is built is strong, secure, and compliant.

#### 7. Business Stakeholders/Product Managers

Business stakeholders and product managers are the bridge between AI technology and organizational value. They define the purpose of AI initiatives and ensure that projects serve both business goals and stakeholder expectations. Their work answers this question: is the AI solving the right problem, delivering measurable value, and doing so responsibly?

#### 8. End Users/Operators

End users are the human checkpoint for AI. Their ability to recognize when AI should be trusted, when it should be questioned, and when it must be overridden ensures that governance principles translate into real-world practice.

#### 9. External Stakeholders (Vendors, Partners, Regulators, Customers)

Vendors and partners must provide transparency into model design, limitations, and terms of use. Regulators issue and enforce compliance obligations, ensuring that AI systems align with laws and societal expectations. Regulations like the EU AI Act, GDPR, or FTC guidance set clear boundaries for responsible AI practices. Customers and end users also play a governance role by providing feedback on system fairness, accuracy, and usability. 

**Exam Tip**: Be prepared to match stakeholder roles with governance responsibilities. For example: 

- Developers → technical safeguards, documentation. 
- Executives → set risk appetite, approve governance. 
- Compliance → align policies with law. 
- Users → escalate anomalies, apply training. 

**Exam Scenario**: An AI hiring tool begins showing signs of bias in screening résumés. Developers notice anomalies in subgroup performance but don’t escalate. Executives are unaware of the issue, compliance hasn’t checked whether anti-discrimination rules apply, and end-users continue to rely on the tool without reporting errors. On the exam, the correct answer is to recognize this as a stakeholder-role alignment problem. Governance requires each group to fulfill its responsibility: developers should document and escalate technical issues, executives should review risks against the organization’s tolerance, compliance should ensure legal obligations are met, and users should be trained to spot and report anomalies.

### B. Cross-Functional Collaboration

AI rarely affects all stakeholders in the same way. By intentionally drawing on diverse perspectives across functions, and at times from communities outside the organization, blind spots are reduced and the risks of overlooking or exacerbating harms are diminished.

### C. Training and Awareness for Stakeholders on AI Terminology, Strategy, and Governance

**Exam Tip**: Think of training and awareness as the bridge between policy and practice. Policies define what needs to happen; training ensures stakeholders understand how to make it happen.

**Exam Scenario**: A hospital deploys an AI system to help prioritize patients. The organization has strong policies in place requiring human oversight for all high-risk cases. However, nurses and staff aren’t trained on how to recognize when the AI is uncertain or how to escalate cases for human review. As a result, staff rely too heavily on the AI’s rankings, and several urgent cases are delayed. On the exam, the correct answer is to recognize this as a training and awareness gap. Policies alone aren’t enough, staff must be trained to apply them in practice. The governance response should emphasize user education, role-specific training, clear escalation procedures, and attestation that training was completed before system access is granted.

### D. Tailoring Governance by Organizational Context

AI governance is not one-size-fits-all. What works for a multinational financial institution will not work for a small start-up or a government agency. For governance to be effective and sustainable, it must be tailored to an:

- Organization’s size
- Maturity
- Industry
- Business model/objectives
- Overall risk appetite.

### E. Differentiating Stakeholders in AI Governance: Developers, Deployers, and Users

**Exam Tip**: The AIGP exam may ask you to match responsibilities to stakeholders. For example: 

- Developer → document data lineage. 
- Deployer → conduct post-market monitoring. 
- User → escalate anomalies or unintended outcomes. 

**Exam Scenario**: An AI image-recognition system is rolled out in a consumer app. During deployment, a regulator asks who is responsible for documenting the training data sources, who should monitor the system once it’s live, and who needs to act if the app starts mis-labeling images in harmful ways. On the exam, the correct answer is to match responsibilities to the right stakeholder. Developers are responsible for documenting the data lineage and system design. Deployers (the company releasing the system) must conduct post-market monitoring to catch problems in real-world use. Users have a role too: they should escalate anomalies or unintended outcomes through the reporting channels provided.























