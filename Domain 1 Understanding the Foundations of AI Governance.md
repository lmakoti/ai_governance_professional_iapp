# Domain 1: Understanding the Foundations of AI Governance



## I. Understand What AI Is and Why It Needs Governance (AIGP BoK Section I.A)

**Status**: `Completed` 
**Target**: `27-Jan-2026`

**Artificial intelligence (AI)** is a broad field that covers a range of systems, from narrow machine learning models that classify emails as spam to large language models capable of generating text, images, and code.

> **Governance** begins with recognising AI’s unique traits: its reliance on massive, often sensitive datasets, its **probabilistic** rather than **deterministic** outputs, and its capacity to operate **autonomously**. Together, these traits make AI both powerful and potentially harmful if not carefully managed.

### A. Generally Accepted Definitions and Types of AI

AI refers to systems that perform tasks that traditionally require human intelligence, such as reasoning, problem-solving, learning, and decision-making.

Ai based on the context, can be grouped in a variety of ways; this can also be determined by the kind of organisation:

#### 1. Capability

| Type of AI                            | Use Case                                                     |
| ------------------------------------- | ------------------------------------------------------------ |
| Artificial Narrow Intelligence (ANI)  | perform one specific task and do it very well (classify spam mail, detect credit card fraud) |
| Artificial General Intelligence (AGI) | emulate human thinking and learning, and work well across different types of tasks. (theoretical, does not exist yet) |
| Artificial Superintelligence (ASI)    | outsmart humans in every possible way, from creativity, innovation and problem-solving. |

#### 2. Functionality/Method

| Type of AI        | Use Case                                                     |
| ----------------- | ------------------------------------------------------------ |
| Reactive Machines | They can analyse and act on a situation, but do not have a historical context to act based on previous information/situations. |
| Limited Memory AI | They are generally a step up from reactive machines; they can use short-term memory to make informed decisions, but still rely on responding to a situation in a reactive manner. (Self-driving cars) |
| Theory of Mind AI | They can adjust to provide relevant responses based on things like emotional cues from a person, or read a person's intention, then adjust their response to fit the context. |
| Self-Aware AI     | They are fully aware of external information and also have their own emotions, needs and goals. This would technically be within the realm of AGI and ASI, so far, the speculation is that this would never exist (but never say never, that's what I at least think). |

#### 3. Learning paradigm/ML approach

| Type of AI             | Use Case                                                     |
| ---------------------- | ------------------------------------------------------------ |
| Supervised learning    | learns from labelled data and then can act on a new set of data to classify accordingly (spam mail, loan approvals). |
| Unsupervised learning  | learns from unlabelled data to find patterns on its own through groupings and clustering (AlphaGo, Anomaly detection, investment signals  & classification) |
| Reinforcement learning | learns from trial and error, for each correct item learned/actioned, it gets a form of reward; if it fails, then it gets penalised. (Self-driving vehicles, recommender systems - Netflix, Spotify, trading/investments). |
| Generative AI          | learns from training data and is able to generate new or modified content in the form of text, images, music or code/programming. |

#### 4. Technology

- Natural Language Processing (translation of human language to produce text/speech etc.)

- Computer vision (Medical image analysis, self-driving cars)
- Robotics (AI combined with machines, moving in the physical world)
- Expert Systems (Rule-based and stored knowledge actors)
- Speech Recognition and Generation (Spoken words can be converted to text for interpretation also for generation like in Siri/Alexa)



###  B. Risks and Harms Posed by AI to Individuals, Groups, Organizations, and Society

#### 1. Risk to individuals

AI systems introduce different types of risk to individuals directly using these tools or those who are affected by their use, even without explicit consent. The systems tend to perpetuate **bias and discrimination** based on their training data, although this may not even be intentional, and the impact may adversely affect people. The consequences could range from racially motivated exclusions to being marginalised out of jobs they qualify for based on a faulty educational setting tool meant to screen applicants.

Some risks extend to **privacy violations,** which may bring into the public domain personally identifiable information (PII), endangering people's safety. In some cases, if a listening tool leaks conversational information meant to be private, then there is a reputational risk to affected individuals, which may compromise their integrity.

Social media can also be exploited to serve as a tool in which automated AI bots and algorithms can use targeted ads or political ideologies to influence users and thus rob them off their free will and **autonomy**, this is a very manipulative trade but large organisations that buy and sell data have been caught out doing this malpractice in cases such as the Cambridge Analytica scandal case (https://www.bbc.co.uk/news/technology-64075067), the company in 2018 harvested user personal data from Facebook users and build psychological profiles that were used to to influence the 2016 U.S presidential elections, the settlement amount paid by Meta the Facebook's parent company was $725M.

There are also critical **safety** concerns with domains in which AI systems have been allowed to make potential life or death decisions. In self-driving cars if a vehicle makes a mistake, such as misinterpretation of a road signal or in healthcare, where a recommendation for a particular treatment may endanger a patient's life if not all elements were unfortunately not all factored in.

#### 2. Risk to Groups or Communities

Communities and societies are never impacted the same way by AI; there is **unequal impact** across different areas. This can span applications of AI in sectors such as education, where training data from privileged schools may be used to generalise when certain policies are made,  only to negatively impact poorly funded, low-income schools which less resources.

Another issue linking to **bias and discrimination** is when data used to train AI models underrepresents certain members of the wider public, failing to factor in their financial behaviours or general welfare situation. This leads to an unfair **exclusion,** creating barriers to access and opportunities

A failure in the workings of how these AI tools make decisions, which is their lack of transparency and explainability, usually leads to **an erosion of trust**, because the authorities or people who deploy the models usually fail to explain to people how or why the decisions were made.

#### 3. Risks to Organisations

- Operational risks
- Reputational risks
- Legal and regulatory risks
- Security risks

#### 4. Risks to Society at Large

- Misinformation and disinformation (Deepfakes)
- Job displacement (Automation)
- Amplifying inequality (Matthew principle)
- Loss of human oversight (Excessive reliance on AI, Loss of accountability)
- Systemic or existential risks (AI-driven cyberattack, International air traffic control)

**Exam Tip**: Always think about risk in terms of who is harmed: 

- **Individuals** → privacy loss, biased decisions. 
- **Groups** → discrimination, exclusion. 
- **Organisations** → legal trouble, reputation damage, poor decisions. 
- **Society** → misinformation, inequality, or large-scale risks that affect everyone.



### C. Unique Characteristics of AI That Require Strong Governance

#### 1. Complexity

**Exam Tip**: Complexity is about the internal structure (too many layers and parameters to follow), not visibility. 

**Exam Scenario**: An AI governance team is asked to review a medical diagnostic model. The developers argue it is “transparent” because they published full documentation and user-facing explanations. However, the model itself has hundreds of hidden layers and billions of parameters, making its internal decision path impossible to trace or fully understand. The correct answer is to recognise that complexity refers to the model’s structure, its size and depth, not whether the organisation is willing to share information. Transparency can exist alongside complexity, but complexity itself still limits interpretability.

#### 2. Opacity

**Exam Tip**: Opacity is about the lack of visibility (the model doesn’t show its reasoning, even if you wanted to check). This is different from complexity, which is about size and detail (the model has so many layers and parameters that its reasoning is too complicated to follow). 

**Exam Scenario**: A bank deploys an AI tool to decide whether customers qualify for loans. The model is relatively small and not overly complex, but the vendor does not provide transparency into how it makes decisions. Loan officers only see “Approved” or “Denied” with no explanation of which factors were considered or how they were weighed. The correct answer is to recognize this as opacity: the problem isn’t that the model is too large or complicated to understand, but that the reasoning is hidden from view, leaving decision-makers without visibility into how outcomes are reached.

#### 3. Autonomy

**Exam Tip**: Autonomy is different from risks like complexity or opacity. Complexity and opacity make AI hard to understand, but autonomy raises the risk that AI acts without human approval. Remember: autonomy = independence of action, which makes governance about control and accountability. 

**Exam Scenario**: A hospital tests an AI-powered triage system for emergency rooms. In the pilot, the AI only recommends which patients should be seen first, and nurses make the final call. Later, the system is upgraded so that it can automatically assign patients to treatment rooms without staff confirmation. The correct answer is to recognise this as an autonomy issue. The risk isn’t about understanding how the model works (complexity/opacity), but about the AI now acting independently, making decisions without human approval. Governance must focus on controls, oversight, and clear accountability before allowing autonomous action.

#### 4. Speed and Scale

**Exam Tip**: If you see “speed and scale” on the test, think small error → big harm quickly. The governance answer will almost always involve real-time monitoring, escalation procedures, and rapid response.

**Exam Scenario**: A financial services company deploys an AI model that automatically approves small-dollar loans. During testing, it performed well. But once live, a data error causes the model to misclassify applicants, approving risky borrowers and denying qualified ones. Because the system processes thousands of applications per hour, the error spreads rapidly, leading to regulatory complaints and financial losses within a single day. The correct answer is to connect this to speed and scale: a small error became a big problem very quickly. Governance requires real-time monitoring to catch errors early, clear escalation paths to decision-makers, and rapid response procedures (such as pausing approvals or rolling back to a safe mode) before harms multiply.

#### 5. Potential for Harm or Misuse

- **Misinformation:** False content + **No intent to harm**.
- **Disinformation:** False content + **Intent to harm**.
- **Malinformation:** **Genuine/True content** + Intent to harm (e.g., leaking private information, taking quotes out of context to damage a reputation). 

**Exam Tip**: “Potential for harm or misuse” = intentional weaponisation (like deepfakes or autonomous weapons) plus unintended consequences (like biased policing). On the test, look for governance responses such as ethical reviews, use-case vetting, and harm-reduction frameworks. 

**Exam Scenario**: A city police department considers deploying an AI facial recognition tool to identify suspects in crowded public spaces. While the vendor claims high accuracy, testing shows error rates are higher for women and minority groups. Civil liberties groups also warn that the system could be misused for surveillance beyond its stated purpose. The correct answer is to tie this to “potential for harm or misuse.” This risk covers both unintended consequences (biased policing outcomes) and intentional weaponisation or misuse (expanded surveillance without oversight). Governance requires ethical review boards, strict use-case vetting, and harm-reduction frameworks to decide whether the deployment is acceptable, and if so, under what safeguards.

#### 6. Data Dependency

**Exam Tip**: Data dependency = “bad data = bad AI.” Look for governance solutions like lineage, provenance, quality checks, and legal compliance. 

**Exam Scenario**: A bank deploys an AI system to evaluate loan applications. Later, it’s discovered that the training data excluded applicants from certain neighbourhoods, and the addresses used in the live system correlate heavily with race and income. As a result, qualified applicants are being unfairly denied loans. The correct answer is to recognise this as a data dependency problem: the AI is only as good as the data it was trained on (“bad data = bad AI”). Governance requires data lineage and provenance tracking, quality checks to detect bias or gaps, and compliance with laws like ECOA or fair lending rules.

#### 7. Probabilistic vs Deterministic Outputs

Traditional software is **deterministic**, which means the same input will always produce the same output.

AI systems, on the other hand, are often **probabilistic**. This means their results are based on probabilities rather than fixed rules, so the same input may lead to slightly different outputs each time.

**Exam Tip**: Deterministic = “always the same.” Probabilistic = “may vary.” On the exam, link probabilistic outputs to governance needs like transparency, confidence calibration, and expectation management. 
**Exam Scenario**: An e-commerce site uses two AI systems. The first system calculates sales tax. Every time it runs, the answer is identical for the same input. The second system recommends products. If the same user refreshes the page, the suggestions change slightly each time. On the test, the correct answer is to spot that the tax system is deterministic (always the same output for the same input), while the recommendation engine is probabilistic (outputs may vary). Governance for probabilistic systems requires transparency, calibrated confidence or probability scores, and setting user expectations so they don’t assume the output is fixed truth.

#### 8. Adaptability as a Risk Multiplier

**Exam Tip**: Adaptability = “learning drift.” On the exam, if a system changes behaviour after retraining or exposure to new data, the governance answer should involve monitoring, drift detection, and retraining safeguards. 
**Exam Scenario**: A hospital deploys an AI system to recommend medication dosages. At launch, it performs well on the validation set. Six months later, doctors notice the recommendations have started to change in subtle ways, leading to dosage errors. Investigation shows the model had been retrained with new hospital data that contained labelling errors, which shifted its behaviour. On the test, the correct answer is to recognise this as an adaptability risk (learning drift). The governance response should involve continuous monitoring, drift detection tools, retraining safeguards, and formal approval gates before updated models are pushed live.

### D. Principles of Responsible AI

#### 1. Fairness

**Exam Tip**: Fairness = bias prevention. Look for answers about diverse data, fairness testing, and impact reviews. 

**Exam Scenario**: An AI recruiting tool is trained mostly on résumés from one region and university system. When deployed, it consistently favors applicants from that background while disadvantaging equally qualified candidates from other schools and regions. On the test, the correct answer is to recognize this as a fairness issue (bias in data and outcomes). The governance response should include diverse training data, fairness testing across subgroups, and impact reviews before and after deployment.

#### 2. Safety and Reliability

**Exam Tip**: Safety = reliable performance under stress. Governance responses usually involve testing, monitoring, or fail-safes. 

**Exam Scenario**: An AI-powered medical triage system performs well during normal patient loads but begins misclassifying urgent cases when emergency room visits surge after a natural disaster. On the exam, the correct answer is to recognize this as a safety issue (failure under stress). The governance response should involve stress testing, continuous monitoring, and fail-safes such as human review or automatic fallback modes during overload conditions.

#### 3. Privacy and Security

**Exam Tip**: Privacy = lawful and ethical data use. Security = technical protection. Both may appear separately on the exam. 

**Exam Scenario**: A hospital uses an AI system to monitor patient vital signs. The system functions well, but two issues arise: the hospital reuses patient data for marketing without consent, and hackers break into the system to steal the same data. The correct answer recognises this as both a privacy issue (unlawful or unethical reuse of data) and a security issue (failure to technically protect data from intrusion). The governance response should involve consent and purpose limitations for privacy, and strong access controls, encryption, and monitoring for security.

#### 4. Transparency and Explainability

**Transparency** means being open about how the system was built and how it’s used—its purpose, the kind of data it learns from, and its limits. **Explainability** means giving a plain-English reason for an outcome so a non-expert can understand it.

**Exam Tip**: Transparency = open process. Explainability = understandable outputs. Don’t confuse the two. 

**Exam Scenario:** A bank deploys an AI loan approval system. The bank publishes full documentation about how the system was built, what data sources it uses, and how it’s monitored. However, when an applicant is denied a loan, the system can only output a numeric score without explaining the specific reasons behind the decision. On the exam, the correct answer is to recognize this as a transparency success (open process is documented) but an explainability failure (outputs aren’t understandable to the affected individual). The governance response should involve explainability measures such as feature attribution, plain-language explanations, or appeal processes.

#### 5. Accountability

**Exam Tip**: Accountability = who is responsible when AI goes wrong. Look for governance tied to roles, audits, and redress. 

**Exam Scenario:** A city deploys an AI traffic management system that controls stoplights in real time. One day, a malfunction causes gridlock and several accidents, but when investigators ask who is responsible, the vendor, the city IT team, or the transportation department, no one has a clear answer. On the exam, the correct answer is to recognize this as an accountability issue. The governance response should involve assigning clear roles and responsibilities, maintaining audit trails, and ensuring redress mechanisms so responsibility is traceable when failures occur.

#### 6. Human-Centricity

**Exam Tip**: Human-centricity = AI should serve people, not replace them. Look for human oversight and alignment with human values. 

**Exam Scenario**: A bank introduces an AI loan approval system that makes fully automated decisions without human review. Several applicants are wrongly denied, and when they ask for explanations, the system can’t provide reasons and no human staff are involved in appeals. On the exam, the correct answer is to recognize this as a human-centricity issue. The governance response should involve requiring human oversight, ensuring appeal and redress processes, and aligning decision-making with human values so the system serves people rather than replacing them.

































