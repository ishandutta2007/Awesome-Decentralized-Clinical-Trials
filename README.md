# Awesome-Decentralized-Clinical-Trials

# Top Decentralized Clinical Trials (DCT) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Remote Patient Engagement, eConsent, ePRO/eCOA & Decentralized Trial Orchestration*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Decentralized Clinical Trials (DCT)**. These tools help sponsors, CROs, and research sites run trials remotely—enabling patients to participate from home through eConsent, ePRO/eCOA, telemedicine, and direct-to-patient supply.

**Examples** include Medable, Science 37, THREAD Science, Curebase, Clario, Signant Health, Castor, Veeva Vault, Oracle Clinical One, and ObvioHealth (the category leaders).

**Open-source emphasis**: DCT has a **focused and emerging open-source ecosystem**. **Arcwell** (Apache 2.0) is a production-deployed open-source clinical research platform with **eCOA/ePRO within EDC** and a rules engine handling **4,000+ custom clinical rules** at a neonatal resuscitation unit . **PROACT 2.0** (Mozilla Public License) is a purpose-built open-source patient-doctor communication app for cancer trials, tested at Istituto Nazionale dei Tumori with six language support . **Pryv.io** is a Digital Public Good for personal data lifecycle management and decentralized trial consent . This section documents these focused solutions honestly.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Medable](https://www.medable.com/)**
  Decentralized clinical trial platform with eConsent, ePRO, eCOA, and remote data collection. Supports BYOD (bring your own device) and patient-centric trial design. Approximately 1 million patients enrolled.

- **[Science 37](https://www.science37.com/)**
  Metasite unified platform for virtual clinical trials. Enables remote participation through eConsent, ePRO, telemedicine, and scheduling in a single app-based experience.

- **[THREAD Science](https://www.threadresearch.com/)**
  Decentralized clinical trial platform with ePRO, eCOA, remote patient monitoring, and virtual visit tools. Focused on bringing clinical research into patient homes.

- **[Curebase](https://www.curebase.com/)**
  Decentralized clinical trial platform with eConsent, ePRO, and telemedicine capabilities.

- **[Clario](https://clario.com/)**
  Clinical endpoint technology provider with eCOA, ePRO, and cardiac safety solutions. Formed from ERT and Bioclinica merger.

- **[Signant Health](https://www.signanthealth.com/)**
  Clinical outcome assessment specialist with eCOA, eConsent, and ePRO. Deep expertise in instrument design and linguistic validation.

- **[Castor](https://www.castoredc.com/)**
  Clinical research platform with EDC, eConsent, ePRO, and decentralized trial tools. Popular with academic and investigator-initiated research.

- **[Veeva Vault](https://www.veeva.com/)**
  Veeva's clinical suite includes Vault EDC, CTMS, and eTMF with multi-tenant SaaS architecture. **No-code form designer** eliminates custom programming for study builds. **1,000+ clinical studies** initiated on Vault EDC, with **eight top-20 pharma companies** standardized on it .

- **[Oracle Clinical One](https://www.oracle.com/)**
  Unified eClinical platform with EDC, RTSM, and clinical data management. Self-service, configurable design with direct-to-patient supply management .

- **[ObvioHealth](https://www.obviohealth.com/)**
  Decentralized clinical trial platform focused on patient engagement and remote data collection.

## Open-Source GitHub Projects

### Clinical Research Platforms

- **[Arcwell](https://github.com/arcweb/arcwell)**
  **Production-deployed open-source clinical research platform (Apache 2.0).** Released by Arcweb Technologies in October 2024. Enables healthcare organizations to design, build, and deploy clinical trials and wellness protocols with a **robust rules engine** for autonomous clinical operations and decision support . **Successfully implemented at two healthcare institutions**: Perelman School of Medicine at University of Pennsylvania used Arcwell for a clinical trial evaluating a patient navigation tool for antepartum anemia; another organization built a custom decision support tool handling **4,000+ custom clinical rules** . **Conducts eCOA and ePRO within EDC**—studies can graduate on the same infrastructure . **Apache 2.0 license** drastically reduces vendor lock-in and total cost of ownership .

- **[PROACT 2.0](https://github.com/Proact2)**
  **Purpose-built open-source patient-doctor communication app for clinical trials (Mozilla Public License 2.0).** Developed at Fondazione IRCCS Istituto Nazionale Tumori in Milan, in collaboration with The Christie Manchester, within the **UpSMART Accelerator project** funded by Cancer Research UK and Italian/Spanish cancer associations . **Core features**: Secure text, audio, and video messaging between patients and healthcare providers; **non-urgent information exchange** for adverse events and side effects; **questionnaire and survey submission** via Analyst Console for research purposes . **Six languages supported**: Italian, English, German, French, Spanish, Dutch . **Tested in clinical trial** at the Institute with plans for broader deployment . **Tech stack**: .NET6, C#, Xamarin for mobile, React.js for control panel, hosted on Microsoft Azure (Europe) .

### Consent & Data Management

- **[Pryv.io](https://github.com/pryv/open-pryv.io)**
  **Digital Public Good for personal data lifecycle management and decentralized clinical trials.** Recognized by the **Digital Public Goods Alliance** (UN-endorsed initiative) . Empowers CROs and Pharma to design and run **decentralized, remote clinical trials** . **Cross-Account Messaging & Consent (CMC)** plugin enables secure, federated consent flows between different Pryv hosts, with consent lifecycle events (request, accept, refuse, revoke) and chat/system messaging anchored to counterparty streams . **Consent management** follows the **GConsent ontology**, tracking states including explicitly given, implicitly given, withdrawn, expired, invalidated, refused, and requested . Supports **GDPR, HIPAA, and Swiss data protection law** compliance. **HL7 FHIR**, SNOMED CT, and LOINC interoperability standards supported . **Open source, containerized** for local or cloud deployment .

- **[e-consent (vectis-lab)](https://github.com/vectis-lab/e-consent)**
  Early-stage eConsent implementation with separate modules for clinical, gene-trustee, and participant interfaces. Uses Auth0 for authentication. **Last updated November 2021** . **Not production-ready**—historical reference only.

### Blockchain-Based Trial Registries

- **[Trustdose-u2u](https://github.com/anushree-0805/trustdose-u2u)**
  **Decentralized, transparent, and immutable clinical trial registry built on Flow blockchain.** Uses Cadence smart contracts for on-chain trial registration, IPFS for document storage, and React + Vite frontend. Provides immutable audit trail of updates and public view for regulators and stakeholders . **Experimental/early-stage**—October 2025.

- **[TrialNet](https://projectcatalyst.io/funds/13/cardano-use-cases-concept/trialnet-open-source-clinical-trials-powered-by-aiken)**
  **Open-source clinical trials platform powered by Aiken on Cardano.** Project Catalyst Fund 13 concept. Uses smart contracts for secure, transparent clinical trial data management. Team combines medical sciences PhD and Cardano engineering expertise . **Early-stage/planned**—awaiting funding milestone completion.

### Additional Strong Open-Source Options

- **Full Clinical Platform**: **Arcwell** (Apache 2.0, production-deployed, eCOA/ePRO within EDC, rules engine) .
- **Patient Communication**: **PROACT 2.0** (MPL-2.0, text/audio/video messaging, six languages, cancer trials) .
- **Consent & Data**: **Pryv.io** (Digital Public Good, GConsent ontology, cross-account messaging) .
- **Blockchain Registries**: **Trustdose-u2u** (Flow blockchain, IPFS) , **TrialNet** (Cardano/Aiken, early-stage) .

**Frameworks for building custom systems**: Combine **Arcwell** for the core clinical research platform with eCOA/ePRO and rules engine, **PROACT 2.0** for patient-provider communication in oncology trials, **Pryv.io** for consent management and decentralized data lifecycle, and **Trustdose-u2u** for immutable trial registry on blockchain. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Decentralized clinical trial platforms handle sensitive patient health data; ensure compliance with 21 CFR Part 11, ICH-GCP, HIPAA, GDPR, and applicable regional regulations.
- **Open-source reality**: The open-source ecosystem for decentralized clinical trials is **emerging but production-capable**. **Arcwell** is the standout—production-deployed at two healthcare institutions with eCOA/ePRO within EDC and a rules engine handling thousands of clinical rules . **PROACT 2.0** provides a purpose-built, six-language patient communication app tested in cancer trials . **Pryv.io** is a Digital Public Good with mature consent management and cross-account messaging . However, **commercial platforms** (Medable, Science 37, THREAD, Clario) provide **integrated decentralized trial orchestration, global support infrastructure, and comprehensive patient services** that open-source alternatives cannot match without significant institutional investment. The open-source path is most viable for **specific DCT components (eConsent, ePRO, patient communication, consent management)** or **organizations with strong engineering and clinical informatics capacity**.
