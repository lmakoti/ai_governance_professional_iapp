# Domain 2: Understanding How Laws, Standards, and Frameworks Apply to AI

## III. MAIN ELEMENTS OF THE EU AI ACT (AIGB BOK Section II.C)

**Status**: `Complete<br>
**Target**: `10-Feb-2026`

The EU Artificial Intelligence Act is the first comprehensive statute to regulate AI as its own legal object. It replaces one-size-fits-all approaches with a risk-based framework that classifies systems by the likelihood and severity of harm and then ties obligations to that risk. In effect, the Act treats AI less like generic software and more like a regulated product class.

it follows the effects of AI systems into the European Union even when the developer is located elsewhere.

> For governance professionals, and for exam purposes, the takeaways are practical: be able to explain how the risk ladder works, identify which party in the supply chain bears which duties, describe the core controls required for high-risk systems (risk management, data governance, documentation, transparency, human oversight, post-market monitoring), and outline how GPAI obligations differ. Mastering this structure allows you to anticipate parallel regimes in other jurisdictions and to design lifecycle controls that will travel well beyond the EU.

### A. Risk classification

#### 1. Prohibited AI (Unacceptable Risk)

Under the EU AI Act, certain AI systems are classified as presenting an unacceptable level of risk because they endanger safety, fundamental rights, or democratic values. These systems are not permitted to be placed on the EU market or deployed within the EU, except in very narrow and specifically authorized circumstances.

> Biometrics surveillance, social scoring, exploitation of vulnerabilities, manipulative AI

#### 2. High-Risk AI

The EU AI Act identifies certain systems as high-risk because they significantly affect fundamental rights, access to essential services, or public safety. These systems are not prohibited outright but are subject to strict compliance requirements before they can be placed on the EU market.

> Critical infrastructure, education and training, essential services, law enforcement and border control and safety-critical products

#### 3. Limited-Risk AI

Some AI systems present risks to consumers but not at a level requiring the full compliance framework of high-risk systems.

> Chatbots, deepfakes & synthetic content

#### 4. Minimal-Risk AI

AI systems that pose little to no threat to individual rights, safety, or critical decision-making fall into the minimal-risk category under the EU AI Act.

> Spam filters, video game AI and recommender systems

### B. Key requirements for high-risk AI systems

#### 1. Risk management

The obligation to manage risk extends across the entire lifecycle, beginning at the design stage and continuing through development, testing, deployment, and post-market monitoring. Organizations must identify foreseeable risks to health, safety, and fundamental rights, evaluate their likelihood and severity, and implement proportionate measures to reduce them.

#### 2. Data governance

Strong data governance begins with traceability. Organizations should document data lineage and provenance so they can explain where data came from, how it was processed, and what checks were performed.

#### 3. Technical documentation

For high-risk AI systems, the EU AI Act requires organizations to maintain comprehensive technical documentation that explains how the system was built, how it is meant to be used, and what safeguards are in place.

#### 4. Conformity assessment

Before a high-risk AI system can be placed on the EU market, it must undergo a conformity assessment to demonstrate compliance with the EU AI Act. This process serves as the AI equivalent of product safety certifications, similar to the CE marking already required for many goods in the EU.

#### 5. Record-keeping

Organizations are required to retain all relevant documentation, such as technical files, risk management records, and conformity assessment reports, for use by regulators or during post-market monitoring.

#### 6. Human oversight

The purpose is to create safeguards against unchecked “black box” autonomy by embedding human judgment into the governance of AI. Oversight can take different forms depending on the context and level of risk:

> - Human-in-the-loop: A human reviews and approves AI decisions before they take effect. 
> - Human-on-the-loop: A human monitors the system in real time and can intervene if necessary. 
> - Human-in-command: A human retains ultimate authority to override or deactivate the system if it behaves improperly.

#### 7. Transparency and notification

For high-risk AI, this means informing users clearly whenever AI, not a human, is making or assisting in decisions. Organizations must also disclose the system’s intended purpose, its boundaries, and any material risks or limitations in its use. In cases where AI generates synthetic content, such as deepfakes, synthetic audio, or text, clear labeling is mandatory so individuals are not misled into believing the output is authentic human-created material.

#### 8. Quality Management

The EU AI Act requires high-risk AI systems to be developed, deployed, and maintained under a structured quality management system (QMS). The purpose is to ensure that compliance and safety are embedded into everyday processes, rather than treated as one-off checks at the end of development.



### C. Distinct requirements for general-purpose AI models

General-Purpose AI (GPAI) refers to models that are trained on broad and diverse datasets and designed for versatility rather than a single narrow task. Unlike domain-specific AI, such as a system built solely for medical diagnostics or credit scoring, GPAI systems are adaptable across multiple contexts, industries, and use cases.

Because GPAI can be repurposed in ways not anticipated by the original developers, the EU AI Act introduces special rules requiring providers to document training data, disclose capabilities and limitations, and provide information that downstream deployers need to comply with their own obligations.

Deployers are responsible for ensuring that their end-use complies with the Act, regardless of whether the base model was originally designed for general or low-risk purposes.

The EU AI Act makes clear that its obligations extend beyond Europe’s borders. Even if a GPAI model is developed outside the EU, the law applies whenever its outputs affect individuals within the EU.

Exam Tips for GPAI: 

- GPAI = foundation/large models with many downstream uses. 
- Providers must ensure transparency, documentation, copyright safeguards. 
- Very large GPAI = extra systemic risk obligations. 
- Exam trigger: If you see “large language model” or “foundation model” → think GPAI rules. 
- Mnemonic: “TDC-S” = Transparency, Documentation, Copyright, Systemic risk.

### D. Enforcement framework and penalties

Enforcement is backed by a tiered system of fines, which scale according to the severity of the violation and the size of the organization.

At the center is the **EU AI Office**, a new centralized authority responsible for coordinating enforcement of the Act at the European level. The Office plays a key role in monitoring risks associated with general-purpose AI (GPAI) and very large systemic models, ensuring that obligations for transparency, documentation, and risk management are upheld across the Union.

Together, the EU AI Office, national regulators, and notified bodies create a layered supervisory system that combines centralized coordination with local enforcement and independent certification. This ensures that high-risk AI systems face rigorous oversight before and after market entry.

The EU AI Act adopts a tiered penalty system similar to the GDPR, with the most severe sanctions reserved for violations that pose the greatest threat to rights and safety. The fines are designed to scale with organizational size and impact, ensuring they are both meaningful and proportionate.

Exam Tips for Enforcement and Penalties: 

EU AI Act fines are tiered: 

- 7% / €35M → prohibited practices.

-  3% / €15M → other compliance failures. 
- 1% / €7.5M → misinformation to regulators. 
- Enforcement = EU AI Office + national authorities + notified bodies. 
- Exam trigger: If question = “who enforces?” → think EU AI Office + national regulators. 
- Mnemonic: “7-3-1 Rule” = 7% for prohibited, 3% for obligations, 1% for misleading info.

### E. Role-based differences

- **Providers**: Under the EU AI Act, providers are the entities that develop an AI system, or a general-purpose AI (GPAI) model, with the intent to place it on the market or put it into service under their own name or brand.
- **Deployers**: Deployers are the entities that use an AI system under their authority, with the important caveat that personal or non-professional use does not fall under this role. In effect, deployers are the businesses, organizations, and institutions that integrate AI into their daily operations to make decisions or deliver services.
- **Importers**: Importers are entities established within the EU that place on the EU market an AI system originally developed outside the EU. Their role is to act as the gateway for foreign-developed systems, ensuring that products entering the EU meet the same standards as those created domestically.
- **Distributors**: Distributors are entities within the EU supply chain, other than providers or importers, that make an AI system available on the market.







































