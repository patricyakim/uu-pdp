# Indonesia Upstream Oil & Gas
## UU PDP & Cybersecurity Opportunity Intelligence
**Industry-wide Intelligence | Sales & Account Manager Edition | 11 November 2026**

> **Purpose.** This is a sales-intelligence playbook for account managers engaging Indonesian upstream oil and gas contractors (KKKS). It connects Indonesia's Personal Data Protection Law (UU PDP) with upstream operating context, potential risk areas, stakeholder conversations, and cybersecurity opportunities.
>
> **Important limitation.** This document is not a legal opinion, compliance certification, or assertion that every KKKS has the risks described. Regulatory interpretation and PP 33/2026 details must be validated against the authentic promulgated text and current sector-specific rules before being used in formal legal advice or a customer compliance proposal.

## Executive brief

UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi (UU PDP) is relevant to a KKKS when it processes personal data in its business and operational activities. The law is not an oil-and-gas-specific regulation, but upstream companies are not exempt merely because they operate under a cooperation contract. The applicable obligations depend on the actual processing activity and whether the KKKS acts as a personal data controller, processor, or in another role.

Potentially relevant data domains include:
- Employee and candidate information managed by HR.
- Contractor and subcontractor workforce information.
- Health and occupational safety information.
- Identity, visitor, access-control, CCTV, and potentially biometric data.
- User accounts, logs, email, and other IT records that identify individuals.
- Community engagement and complaint-handling information.
- Personal data handled by vendors, cloud providers, parent-company systems, and other service providers.

The commercial opportunity is not simply to sell DLP or SOC. It is to help customers understand what personal data they process, where it resides, who can access it, how it is shared with third parties, and how incidents are detected and handled.

### Five sales takeaways

1. KKKS may act as controller or processor depending on the actual processing arrangement.
2. Workforce, contractor, HSE, physical-access, and vendor ecosystems are useful discovery areas.
3. Health and biometric data require particular attention because they are categories of specific personal data under the law.
4. Vendor and cross-border processing arrangements create governance and security questions.
5. Privacy obligations need operational controls and evidence; buying a security product alone does not establish compliance.

**Commercial positioning:** Help KKKS build visibility and control over personal data, govern access and third-party processing, and improve incident readiness. Do not use fear-based selling or imply that every customer is non-compliant.

## 1. Regulatory intelligence

### 1.1 UU No. 27 Tahun 2022

UU PDP regulates personal data processing, data subject rights, controller and processor obligations, cross-border transfers, administrative sanctions, and specified criminal offences. It has been in force since 17 October 2022.

Relevant provisions for sales discovery:

| Provision | Subject | Potential business / technology discussion |
|---|---|---|
| Article 16 | Personal data processing principles | Data lifecycle and governance |
| Article 20 | Lawful basis for processing | Lawful-basis mapping |
| Articles 21–24 | Information and consent | Privacy notices and consent management |
| Articles 25–26 | Children's data and specific personal data | Sensitive-data governance |
| Articles 27–31 | Data subject rights | Data subject request workflows |
| Article 34 | DPIA for high-risk processing | Privacy impact assessment |
| Articles 35–39 | Security and confidentiality | Security architecture and access governance |
| Articles 40–44 | Termination, deletion, destruction | Retention and secure deletion |
| Article 46 | Personal data breach notification | Incident response and notification workflow |
| Article 47 | Accountability | Audit evidence and compliance reporting |
| Articles 51–52 | Controller–processor relationship | Vendor and processor governance |
| Articles 53–54 | Personal data protection officer / function | PPDP operating model |
| Article 56 | Cross-border transfer | International data governance |
| Article 57 | Administrative sanctions | Legal and financial risk management |

The table is an issue-spotting guide, not a substitute for reading the complete law and its implementing regulations.

### 1.2 Controller and processor roles

- **Controller (Pengendali Data Pribadi):** determines the purpose and exercises control over personal data processing.
- **Processor (Prosesor Data Pribadi):** processes personal data on behalf of and under the instructions of a controller.

A KKKS may be a controller for its employee or contractor-related processing, depending on the facts. A technology vendor may be a processor for some services, but vendor status alone does not determine the role for every processing activity. Map each activity, purpose, instruction, and contract.

### 1.3 DPIA — Article 34

A data protection impact assessment is required for high-risk processing. The statutory indicators include processing specific personal data, large-scale processing, systematic monitoring, use of new technology, matching or combining data, and automated decision-making with significant effects.

Examples to assess in an upstream context:
- Biometric access control used across multiple facilities.
- Large-scale processing of employee and contractor health information.
- Systematic monitoring of workforce locations or activities.
- Combining identity, access, HR, and HSE datasets.
- Automated decisions that significantly affect individuals.

These are candidate scenarios for assessment, not automatic legal conclusions. The actual purpose, scale, data types, and impact must be examined.

### 1.4 PPDP / DPO — Articles 53 and 54

The obligation to appoint a personal data protection officer or function applies when one or more statutory criteria are met. Constitutional Court Decision No. 151/PUU-XXII/2024 changed the interpretation of the conjunction in Article 53(1)(b) so that the criteria are not read as necessarily cumulative. Sales should not assert that every KKKS must appoint a DPO without assessing the statutory conditions.

### 1.5 PP No. 33 Tahun 2026

PP No. 33 Tahun 2026 is identified as an implementing regulation for UU PDP. The prior research briefing stated an effective date of 16 January 2027, while some secondary material reportedly stated 15 January 2027. **Resolve this discrepancy using the authentic promulgated text, especially its closing and transitional provisions, before repeating the date in customer-facing legal material.**

Before formal use, validate the exact PP provisions concerning:
- Processing records and accountability.
- DPIA and high-risk processing.
- Data subject rights.
- Controller and processor responsibilities.
- PPDP/DPO requirements.
- Breach response and notifications.
- Cross-border transfers.
- Transitional and effective-date provisions.

Do not position January 2027 as the date on which all UU PDP obligations first begin. UU PDP has already been in force.

### 1.6 Cross-border processing

Article 56 regulates transfer of personal data outside Indonesia subject to its statutory conditions. Do not claim that all data must be hosted in Indonesia or that using an overseas cloud service is automatically unlawful. The actual transfer, recipient, safeguards, and applicable conditions must be evaluated.

## 2. Upstream operating context

The upstream operating environment can involve corporate offices, onshore and offshore facilities, field locations, contractors, subcontractors, service providers, parent-company systems, and integrated technology platforms. The actual structure varies by KKKS and asset.

### 2.1 Operating ecosystem

Use this as a discovery model, not as a universal organization chart:

- **KKKS / operator:** corporate, IT, HR, HSE, operations, procurement.
- **Workforce:** employees, expatriates, specialists, temporary personnel.
- **Contractors:** drilling, maintenance, EPC, logistics, and other services.
- **Facilities:** offices, camps, onshore and offshore installations.
- **Technology:** HRIS, ERP, HSE platforms, access control, CCTV/VMS, cloud, IT and OT environments.
- **Data lifecycle:** collection → storage → access → sharing → monitoring → retention → deletion.

### 2.2 Personal data landscape

| Domain | Potential personal data | Systems that may be involved |
|---|---|---|
| HR | Identity, payroll, family, CV | HRIS, ERP |
| HSE | Health and incident information | HSE platforms |
| Physical access | Identity, photo, biometrics, visitor records | Access control |
| Workforce management | Shift, schedule, location | Workforce systems |
| Contractor management | Contractor worker identity and credentials | Vendor management |
| Security | CCTV footage and visitor logs | VMS, access systems |
| IT operations | User accounts, logs, email, identifiers | IAM, SIEM, endpoint |
| Community relations | Complainant and beneficiary information | CRM, community platforms |
| Finance | Bank details and individual vendor data | ERP, finance systems |

Not every record in these systems is personal data. Reservoir, seismic, production, and engineering data are not automatically personal data merely because they are operational data.

## 3. Sector risk intelligence

The following are **risk hypotheses to validate**, not claims that every KKKS experiences them.

| Risk hypothesis | Potential impact | Discovery question |
|---|---|---|
| HR data accessible to too many users | Unauthorized disclosure | Who has access to HR databases? |
| Contractor data copied by vendors | Reduced control over onward use | How is vendor access and download activity monitored? |
| Medical records stored in shared locations | Exposure of health information | How is HSE data classified and restricted? |
| Contractor accounts remain active after offboarding | Unauthorized access | How are joiner-mover-leaver processes handled? |
| Personal data processed by global systems | Cross-border transfer and governance questions | Where is data processed and who receives it? |
| Data breach is not detected quickly | Delayed incident response | Does SOC monitor personal-data exfiltration scenarios? |
| CCTV or biometrics deployed without impact review | High-risk processing may be overlooked | Has the processing been assessed for DPIA? |
| Retention is not consistently applied | Unnecessary continued storage | How are retention and secure deletion controlled? |

### Risk-to-opportunity mapping

| Problem hypothesis | Potential solution |
|---|---|
| Unknown locations of personal data | Data discovery and DSPM |
| No sensitivity classification | Data classification |
| Uncontrolled data movement | DLP and encryption |
| Excessive access | IAM, IGA, PAM |
| Limited vendor oversight | Third-party risk management |
| Weak incident detection | SIEM, UEBA, SOC, SOAR |
| Inadequate governance evidence | GRC and privacy management |
| Limited cloud visibility | CSPM, CNAPP, cloud security |

A risk does not necessarily require a new product. Process improvements, configuration changes, training, contractual controls, and existing-tool optimization may be sufficient.

## 4. Cybersecurity opportunity portfolio

### A. Advisory and assessment
- UU PDP readiness assessment.
- Personal data inventory.
- Data-flow mapping.
- DPIA support.
- Security control assessment.
- Third-party risk assessment.

**Commercial model:** consulting engagement, assessment project, workshop.

### B. Data protection
- Data discovery.
- Data classification.
- DLP.
- Data Security Posture Management (DSPM).
- Encryption and key management.
- Database security.

**Commercial model:** licensing, implementation, integration, managed service.

### C. Cybersecurity infrastructure
- IAM and IGA.
- PAM and MFA.
- SIEM and SOAR.
- EDR/XDR.
- Cloud security.

**Commercial model:** implementation, integration, subscription.

### D. Managed security services
- Managed SOC.
- MDR.
- Managed DLP.
- Vulnerability management.
- Incident response retainer.
- Continuous control monitoring.

**Commercial model:** recurring managed services and annual contracts.

### Example opportunity: Workforce and Contractor Data Protection

**Business driver:** KKKS may manage employee and contractor information across multiple systems and organizations.

**Problem hypothesis:** there may be limited consolidated visibility into data locations, access rights, use, and onward sharing.

**Evidence to request:** HRIS and contractor-management architecture, data flows, vendor list, access policies, classification and retention policies.

**Solution concept:** data discovery + classification + IAM + DLP + third-party risk assessment.

**Potential sponsors:** HR, IT Security, Legal/Compliance.

**Next action:** cross-functional discovery with HR, IT, and Compliance.

## 5. Stakeholder and buying-centre map

| Function | Potential role | Conversation entry |
|---|---|---|
| CISO | Risk owner / technical sponsor | Cybersecurity exposure |
| CIO / IT Director | Executive sponsor | Enterprise IT governance |
| Legal | Regulatory advisor | UU PDP and contracts |
| Compliance | Compliance owner | Regulatory readiness |
| DPO / PPDP | Privacy governance | DPIA and processing records |
| HR | Data/process owner | Workforce data |
| HSE | Data/process owner | Health data |
| Procurement | Commercial gatekeeper | Vendor governance |
| Internal Audit | Independent assurance | Evidence and control effectiveness |
| OT / Operations | Operational stakeholder | Site access and IT/OT security |

Distinguish the problem owner, technical evaluator, and economic buyer. They may be different people.

A possible engagement path:
1. Enter through Legal, Compliance, HR, HSE, or IT.
2. Discover the process and business problem.
3. Validate technical context with CISO, IT, cloud, application, or OT teams.
4. Develop a business case with the sponsor and budget owner.
5. Validate procurement, vendor eligibility, and contracting route.

## 6. Customer discovery playbook

Do not ask every question in one meeting. Select questions according to the stakeholder and conversation.

### Opening questions
1. How is the company approaching UU PDP implementation?
2. Is there a program to map personal data processed across business units?
3. Is PDP implementation led by Legal, Compliance, IT, or a cross-functional team?
4. Is there an integrated implementation roadmap?

### Domain questions

| Domain | Discovery question |
|---|---|
| Data inventory | Does the company know where personal data is stored? |
| Classification | Are health and biometric data specially classified? |
| Access governance | How is contractor access managed? |
| DLP | Is personal-data movement through email and cloud controlled? |
| Cloud | Is any personal data processed by global systems outside Indonesia? |
| Vendor | Do vendors processing personal data undergo security assessment? |
| Incident response | Are personal-data breach scenarios included in incident response plans? |
| DPIA | Which systems have been assessed for high-risk processing? |
| Audit | How is evidence of control implementation retained? |

### Questions that reveal business needs
- Which processes are still manual?
- Is it difficult to consolidate information across systems?
- Are there open audit findings?
- Can vendors provide evidence of security controls?
- Are HR, HSE, or access-control systems being upgraded?
- Is there an internal target to close specific gaps before 2027?

### Qualification signals

| Customer signal | Interpretation | Sales action |
|---|---|---|
| Requests assessment | Need becoming concrete | Scope an assessment |
| Mentions audit finding | Acknowledged issue | Identify finding and owner |
| Requests integration | Technical need | Involve solution architect |
| Has DLP already | Expansion or optimization possible | Validate coverage and gaps |
| Upgrading HRIS | Change window | Engage on data protection design |
| No vendor inventory | Governance need may exist | Offer discovery |
| No clear owner | Opportunity not mature | Identify cross-functional sponsor |

Do not mark an opportunity qualified until there is an acknowledged problem, relevant stakeholder, defined need, and plausible commercial path.

## 7. Customer conversation guide

### CISO / IT Director

**Opening:**  
“We are studying how UU PDP affects upstream oil and gas operators. One area that stands out is the complexity of managing employee and contractor data across HR, HSE, access control, and contractor-management systems.”

**Discovery:**  
“With data distributed across these systems, how does the company maintain visibility over where personal data resides and who can access it?”

**Follow-up:**  
“Is there consolidated visibility into storage locations, classification, and access rights?”

**Potential solution discussion:** data discovery, DSPM, DLP, IAM, security monitoring.

### Legal / Compliance

**Opening:**  
“We are following the implementation of UU PDP and PP 33/2026 and how companies translate privacy obligations into operational controls.”

**Discovery:**  
“Does Compliance work directly with IT to map processing activities, including those performed by vendors and contractors?”

**Follow-up:**  
“How are DPIAs, processing records, and evidence of controls documented?”

**Potential solution discussion:** privacy management, GRC, data mapping, DPIA support, third-party risk management.

### HR / HSE

**Opening:**  
“Workforce data management in upstream operations can involve employees, contractors, subcontractors, and personnel at operating sites.”

**Discovery:**  
“How does the company protect health, identity, and access information when it is used across several systems and by third parties?”

**Potential solution discussion:** data protection, encryption, IAM, DLP, vendor security assessment.

## 8. Objection handling

| Customer statement | Suggested response |
|---|---|
| “We already have DLP.” | “Good. Does it cover endpoints, email, cloud, and systems used by contractors?” |
| “We already have SOC.” | “Do the monitoring use cases include personal-data exfiltration and account misuse?” |
| “We appointed a DPO.” | “How is that function connected to IT, HR, HSE, and vendor management?” |
| “Our data is in the cloud.” | “Has the company mapped processing locations, access, and cross-border transfer arrangements?” |
| “We are already compliant.” | “How does the company evidence control effectiveness and processing accountability?” |
| “We have no budget.” | “Could we start with a focused workshop or assessment to identify where investment is actually needed?” |
| “This belongs to Legal, not IT.” | “The legal interpretation should be led by the relevant function. We can help translate the obligations into technology and operational controls with IT.” |

Do not argue with the customer or imply non-compliance. Explore what has and has not been addressed.

## 9. 30/60/90-day account development plan

### Days 1–30: Intelligence and access
- Identify 5–10 KKKS accounts for initial research.
- Map corporate profile and operating footprint.
- Identify stakeholders and potential entry points.
- Prepare a regulatory briefing.
- Conduct initial meetings.
- Record pain points and hypotheses.

**Outputs:** target-account list, account intelligence, stakeholder map, meeting notes, initial opportunity hypotheses.

### Days 31–60: Discovery and validation
- Conduct customer discovery.
- Run a UU PDP briefing or workshop.
- Meet IT and Compliance stakeholders.
- Map preliminary systems and data flows.
- Validate solution fit.
- Identify budget owners and procurement paths.

**Outputs:** discovery report, workshop results, preliminary data landscape, solution concept, commercial intelligence.

### Days 61–90: Opportunity conversion
- Scope an assessment proposal.
- Present a solution architecture.
- Develop a business justification.
- Validate procurement and delivery requirements.
- Identify delivery partners and service model.
- Enter qualified opportunities into the pipeline.

**Outputs:** proposal, technical concept, business case, procurement strategy, delivery plan, qualified opportunity.

### Sales KPIs
- Account coverage.
- Stakeholder coverage.
- Discovery completion.
- Validated customer problems.
- Assessment or project conversion.
- Qualified pipeline value.

Targets should be set by the sales organization based on its account capacity and baseline performance; do not treat illustrative account counts as market statistics.

## 10. KKKS account research template

For each account, capture:

| Category | Information |
|---|---|
| Corporate profile | KKKS name, operator, parent company, working area |
| Operating footprint | Onshore/offshore, facilities, offices, locations |
| Workforce | Employees, contractors, subcontractors |
| Business applications | HRIS, HSE, ERP, access control |
| Cloud environment | Cloud provider, global systems, hosting |
| Cybersecurity | SOC, SIEM, IAM, DLP, EDR, PAM |
| Privacy governance | PPDP/DPO, policies, DPIA |
| Vendor ecosystem | IT vendors, cloud vendors, service providers |
| Stakeholders | CISO, CIO, Legal, Compliance, HR, HSE |
| Procurement | Procurement entity, vendor eligibility, sourcing route |
| Opportunity | Pain point, evidence, sponsor, solution concept |
| Next action | Owner, timeline, target meeting |

### Account opportunity record

Use this sequence for every opportunity:

**Business Driver → Problem → Evidence → Stakeholder → Solution → Commercial Path → Next Action**

Do not treat a hypothesis as a confirmed customer problem until validated.

## 11. Market-entry strategy

Three engagement paths can be developed:

### Path 1 — PDP Readiness and Data Protection Assessment
Entry through Legal, Compliance, HR, and IT. The goal is to understand the customer's environment and identify implementation needs.

### Path 2 — Cybersecurity Modernization
Connect data protection needs to IAM, DLP, SIEM, SOC, cloud security, and security architecture. The goal is to develop technology implementation opportunities.

### Path 3 — Managed Data Protection and Security Services
Offer monitoring, incident response, managed DLP, and continuous security assessment. The goal is to develop long-term services and recurring revenue.

### Strategic recommendation

The market opportunity is broader than DLP or SOC. Build customer relationships through workforce data protection, data governance, and third-party data security, then develop validated requirements into cybersecurity implementation and managed services.

Avoid:
- Offering every cybersecurity product at once.
- Assuming KKKS customers are non-compliant.
- Claiming all upstream operational data is personal data.
- Promising legal compliance through technology implementation alone.
- Assuming every KKKS has the same structure, systems, or requirements.

## 12. Evidence registry and research validation

### Primary legal and institutional sources to validate and maintain

1. UU No. 27 Tahun 2022 — official text and status through the Indonesian government legal database / JDIH.
2. JDIH Komdigi — official UU PDP text and implementing regulations.
3. Constitutional Court Decision No. 151/PUU-XXII/2024 — interpretation of Article 53(1)(b).
4. PP No. 33 Tahun 2026 — authentic promulgated text, including effective-date and transitional provisions.
5. Permen ESDM No. 2 Tahun 2022, as amended by Permen ESDM No. 15 Tahun 2025 — institutional and upstream context.
6. Constitutional Court Decision No. 137/PUU-XXIII/2025 — cross-border transfer provision.

### Validation checklist before customer-facing legal use

- Verify the authentic PP 33/2026 text, including commencement and transitional provisions.
- Validate provisions on processing records, DPIA, PPDP/DPO, data subject rights, breach notifications, and cross-border transfers.
- Check the latest status of the PDP supervisory institution and implementing regulations.
- Review relevant upstream sector rules and the customer's cooperation contract.
- Validate controller and processor roles for each actual processing scenario.

**Research limitation:** This playbook is a structured sales analysis, not a fully sourced legal memorandum. The exact PP 33/2026 clause-level analysis and current status of implementing regulations must be completed from primary official sources before formal legal reliance.

## 13. Source links

- [UU No. 27 Tahun 2022 — BPK Legal Database](https://peraturan.bpk.go.id/)
- [JDIH Kementerian Komunikasi dan Digital](https://jdih.komdigi.go.id/)
- [Mahkamah Konstitusi — Putusan 151/PUU-XXII/2024](https://www.mkri.id/)
- [Kementerian ESDM](https://www.esdm.go.id/)
- [JDIH Kementerian ESDM](https://jdih.esdm.go.id/)
- [SKK Migas](https://www.skkmigas.go.id/)

> **Source discipline:** prefer authentic legal texts, official JDIH records, court decisions, and government publications. Secondary commentary can help identify issues but should not replace primary sources. Record publication date, access date, exact provision, and confidence for each material claim.

---

**Document status:** Industry-wide sales intelligence draft  
**Research cut-off:** 11 November 2026  
**Audience:** Sales / Account Manager  
**Scope:** Indonesian upstream oil and gas / KKKS  
**Use:** Customer discovery, account planning, opportunity development  
**Disclaimer:** Not legal advice, compliance certification, or a representation of any specific KKKS's control environment.
