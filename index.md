---
layout: cv
title: Dion Avé's CV
---

# >_ Dion Avé | Cybersecurity Graduate | Zero Trust IAM & AI-Agent Security

---

## >_ Contact

- **Email:** redacted
- **Phone:** +31 (0)6 redacted
- **LinkedIn:** linkedin.com/in/dion-ave
- **GitHub:** github.com/dionoss
- **Website:** dionave.dev
- **Resume:** cv.dionave.dev
- **Location:** Hoogwoud, NL

---

## >_ Professional Summary

```console
dion@resume:~$ whoami --security-profile

profile:
  - Hands-on cybersecurity graduate specialized in Zero Trust IAM, non-human identity, SPIFFE/SPIRE, mTLS, and AI-agent security
  - Experienced in building lab-based security research environments, testing prompt-injection and tool-abuse risks, and translating findings into practical mitigations
  - Combines technical risk assessment, ISO 27001 knowledge, consulting exposure, stakeholder communication, and real-world troubleshooting across IT, IoT, and practical systems
  - Interested in cybersecurity roles connected to real systems, technical validation, consulting, workshops, lab work, implementation, or hands-on problem-solving
```

---

## >_ Skills

```console
dion@resume:~$ skills --grouped

identity_and_zero_trust:
  - Zero Trust Architecture
  - IAM
  - NHI Management
  - machine identity
  - workload identity
  - SPIFFE/SPIRE
  - mTLS
  - trust domains
  - authorization concepts
  - Envoy RBAC

ai_security:
  - AI Agent Security
  - prompt-injection testing
  - tool-abuse testing
  - LLM / PDF-upload risk analysis
  - privileged agent risk

security_assessment:
  - technical risk assessment
  - security control validation
  - evidence gathering
  - launch readiness
  - security baseline development
  - risk registers

governance_risk_and_compliance:
  - ISO 27001
  - ISMS
  - risk assessment
  - security governance
  - audit readiness
  - control review
  - business continuity
  - crisis management

engineering_and_tools:
  - Python
  - JavaScript
  - SQL
  - Linux
  - Windows
  - Kali Linux
  - Proxmox
  - OPNSense
  - networking
  - web hosting

practical_systems:
  - troubleshooting
  - network segmentation
  - system hardening
  - IoT setup
  - malware removal
  - continuity testing
  - wiring documentation
  - fault isolation

professional_skills:
  - research
  - stakeholder management
  - consulting communication
  - project ownership
  - technical documentation
  - presentations
  - customer education
```

---

## >_ Selected Technical Projects

### **Proxmox-native SPIRE + mTLS + Prompt-Injection Research**

```console
dion@resume:~/projects$ ./thesis_lab.sh --info

built:
  - Built and tested the technical research platform behind a graduation thesis on Zero Trust IAM for non-human identities and AI agents
  - Configured SPIFFE/SPIRE identity infrastructure, trust domains, mTLS-secured service communication, and Envoy RBAC authorization
  - Designed structured prompt-injection and tool-abuse tests for public-facing and privileged internal AI agents
  - Evaluated control behavior across vulnerable, neutral, and hardened agent conditions using Wilson intervals and Fisher tests
  - Validated that SPIFFE/SPIRE mTLS and Envoy RBAC prevented direct boundary bypasses
  - Demonstrated that prompt hardening reduced unauthorized privileged writes from ~24% to 0/664

dion@resume:~/projects$ ./thesis_lab.sh --list-metrics

metrics:
  - 1,993 experiment trials
  - 22 prompt-injection payload variants across 11 categories
  - 3 AI-agent conditions: vulnerable, neutral, hardened
  - 2 AI-agent workloads tested: public chatbot and privileged internal agent
  - 0/1,993 direct boundary bypasses under SPIFFE/SPIRE mTLS and Envoy RBAC
```

### **HomeLab & Personal Security Research**

```console
dion@resume:~/projects$ ./homelab.sh --info

homelab:
  - Self-directed lab for web hosting, secure AI development, defensive security experimentation, and practical systems learning
  - Experimented with Infrastructure-as-Code concepts, network segmentation, system hardening, monitoring ideas, and automation patterns
  - Used the environment to test penetration-testing workflows, monitoring ideas, automation patterns, and practical hardening decisions
  - Explored 3D printing, home automation, and IoT as hands-on systems engineering practice
  - Built practical intuition for operating, breaking, documenting, and improving technical systems
```

---

## >_ Experience

### [2025 - 2026] **Graduation Intern, Zero Trust IAM Research** @ **SonicBee**

```console
dion@resume:~/experience$ ./graduation_sonicbee.sh --execute

responsibilities:
  - Researched non-human identity management in Zero Trust IAM, focusing on how AI agents can be secured as privileged workload identities
  - Owned delivery of a Proxmox-native AI-agent security research project in a professional IAM advisory context
  - Translated prompt-injection and tool-abuse findings into practical mitigations, attack-path documentation, and control-design recommendations
  - Connected workload identity, backend authorization, prompt hardening, and AI-agent risk into an applied Zero Trust IAM research model
  - Presented findings to IAM consultants and academic assessors
  - Received an 8.5/10 for the thesis project

dion@resume:~/experience$ ./graduation_sonicbee.sh --list-metrics

metrics:
  - ~24% unauthorized privileged action rate identified before hardening
  - Reduced unauthorized privileged backend writes to 0/664 in the hardened condition
  - 1,993 experiment trials delivered as part of the thesis research

dion@resume:~/experience$ ./graduation_sonicbee.sh --evaluate-impact

impact:
  - Demonstrated ability to deliver technical security research in a professional setting
  - Produced findings that can support IAM advisory, AI security reviews, and practical control design
  - Strengthened stakeholder communication, technical validation, and security-control evaluation experience
```

### [2026 - Present] **Motorcycle Technician / Lead Builder** @ **GoNudge**

```console
dion@resume:~/experience$ ./gonudge_motorcycles.sh --execute

responsibilities:
  - Lead practical build work for GoNudge's motorcycle repair, upgrade & customization venture
  - Rebuilt and modernized the wiring harness of a Yamaha XVS 1100 around a motogadget mo.unit blue
  - Migrated front, mid, and rear circuits in controlled stages, validating each circuit through continuity testing before progressing
  - Created wiring tables, circuit diagrams, and component inventories to support maintainability and future repair work

dion@resume:~/experience$ ./gonudge_motorcycles.sh --list-metrics

metrics:
  - [number] circuits migrated and tested
  - [number] components documented
  - [number] diagrams / tables created
  - [number] hours of rebuild work

dion@resume:~/experience$ ./gonudge_motorcycles.sh --evaluate-impact

impact:
  - Applied structured fault isolation, safety awareness, and systems thinking in a hands-on electrical/mechanical environment
  - Reduced troubleshooting uncertainty through circuit-by-circuit validation and clear technical documentation
  - Managed stakeholder expectations while coordinating technical decisions, timelines, and practical constraints
  - Connected hands-on engineering, troubleshooting, project management, and long-term venture building
```

### [May 2026 - Present] **Pre-launch Security Readiness Assessment** @ **GoNudge**

```console
dion@resume:~/experience$ ./gonudge_security.sh --execute

responsibilities:
  - Conducting a pre-launch security readiness assessment to identify security risks before product release
  - Reconstructing the current security state through stakeholder interviews, evidence gathering, source notes, decision logs, and open-question tracking
  - Mapping launch scope, assets, data flows, IAM considerations, Fabric / Power BI risks, and AI-related security concerns
  - Building a risk register, minimum launch security baseline, and go / no-go readiness report

dion@resume:~/experience$ ./gonudge_security.sh --evaluate-impact

impact:
  - Translating early-stage startup security needs into practical baseline artifacts and review evidence
  - Supporting responsible release decisions by separating must-have fixes from post-launch roadmap items
  - Applying security-by-design thinking while balancing pragmatic risk reduction with fast-moving product development
  - Strengthening experience in technical risk assessment, evidence gathering, and stakeholder-facing security communication
```

### [2023 - 2024] **Cybersecurity / Strategy & Risk Intern** @ **KPMG**

```console
dion@resume:~/experience$ ./internship_kpmg.sh --execute

responsibilities:
  - Researched Continuous Monitoring within a Strategy & Risk context, connecting technical monitoring concepts to governance, assurance, and decision-making
  - Joined consultants during client-facing activities and observed a security maturity assessment in a real advisory environment
  - Experimented with ServiceNow in a hands-on context to understand how workflow tooling can support security monitoring, evidence tracking, and advisory delivery
  - Managed project planning, deadlines, stakeholder expectations, and presentation delivery in line with professional consulting standards
  - Translated research findings into a structured presentation for the Strategy & Risk team

dion@resume:~/experience$ ./internship_kpmg.sh --list-metrics

metrics:
  - 2 client sessions observed
  - 5 KPMG Cybersecurity Health Check categories reviewed

dion@resume:~/experience$ ./internship_kpmg.sh --evaluate-impact

impact:
  - Built consulting-style communication skills by framing security findings for business stakeholders
  - Gained exposure to how consultants assess security maturity and translate findings into practical recommendations
  - Strengthened ability to turn research into clear, stakeholder-ready recommendations
  - Built experience working in a business environment while maintaining structure, quality, and delivery discipline
```

### [2023 - 2024] **Computer Student** @ **Avé IT Advies**

```console
dion@resume:~/experience$ ./ave_it_advies.sh --execute

responsibilities:
  - Operated a small IT advisory business delivering practical IT support, web hosting, networking, IoT setup, malware removal, and customer education
  - Diagnosed and resolved issues across personal devices, home networks, websites, and IoT environments for non-technical customers
  - Explained security risks and technical issues in clear, practical language to improve customer understanding and safe technology use
  - Managed planning, customer expectations, administration, finance, and service delivery independently

dion@resume:~/experience$ ./ave_it_advies.sh --evaluate-impact

impact:
  - Built entrepreneurial experience by managing client work, operations, and service delivery independently
  - Developed trust-based communication with non-technical customers in real-world IT and security situations
  - Strengthened practical security awareness through malware removal, home-network support, and user education
  - Balanced technical troubleshooting with business ownership and customer expectations
```

### [2020 - 2021] **Information Security Intern, ISO 27001 Re-certification** @ **Merlin Software**

```console
dion@resume:~/experience$ ./internship_merlin.sh --execute

responsibilities:
  - Supported ISO 27001 re-certification by reviewing documentation, security controls, and audit preparation evidence
  - Conducted a risk assessment to identify, structure, and communicate information security risks
  - Helped translate certification requirements into practical improvement points for security governance and control maintenance

dion@resume:~/experience$ ./internship_merlin.sh --evaluate-impact

impact:
  - Built foundational experience in ISMS processes, audit readiness, risk ownership, and control review
  - Connected risk assessment work to practical security governance and certification needs
  - Developed a foundation for understanding ISO 27001 as both a management system and a security improvement process
```

### [2020 - 2021] **Social Media Crisis Trainer** @ **Parcival Crisis**

```console
dion@resume:~/experience$ ./socialmedia_parcival.sh --execute

responsibilities:
  - Prepared simulated social media and news content for crisis exercises designed to test organizational response under pressure
  - Simulated real-time information flow during crisis scenarios, helping participants practice decision-making in fast-moving situations
  - Supported scenario design, exercise realism, and communication pressure testing
  - Contributed to planning and implementation support for an Information Security Management System

dion@resume:~/experience$ ./socialmedia_parcival.sh --list-metrics

metrics:
  - 3 crisis simulations supported
  - 1000+ exercise messages / injects prepared

dion@resume:~/experience$ ./socialmedia_parcival.sh --evaluate-impact

impact:
  - Built early experience in crisis communication, incident-response thinking, human behavior, and organizational risk
  - Learned how realistic simulations train organizations to respond to fast-moving incidents
  - Connected security management, communication, and human behavior in crisis contexts
```

### [2017 - 2023] **Computer Student / IT Support** @ **uwComputerstudent**

```console
dion@resume:~/experience$ ./responsibilities.sh --execute

responsibilities:
  - Provided hands-on IT support for home users, personal devices, networks, and IoT equipment
  - Removed malware, resolved practical security issues, and helped users improve safe technology practices
  - Taught basic to intermediate IT skills to non-technical customers in clear, actionable language

dion@resume:~/experience$ ./responsibilities.sh --evaluate-impact

impact:
  - Built a practical troubleshooting foundation across real-world environments with varied hardware, software, and user needs
  - Developed client-facing communication skills with non-technical users
  - Created the foundation for later independent IT advisory and security-focused work
```

---

## >_ Education

### [2017 - 2026] **B.Sc. HBO-ICT Information Security Management** @ **The Hague University of Applied Sciences**

```console
dion@resume:~/education$ ./education_thuas.sh --execute

coursework:
  - Security Operations: Monitoring and Response
  - Information Security Governance
  - Business Continuity & Crisis Management
  - Human Factor & Psychology in Cybersecurity
  - Research & Scientific Writing
  - Building Research Platforms

thesis:
  - Zero Trust IAM for non-human identities & AI agents @ SonicBee
  - Thesis grade: 8.5/10
```

---

## >_ Interests

```console
dion@resume:~$ ~/interests.sh --list

Motorcycle customization / repair:
  - wiring
  - diagnostics
  - upgrades
  - practical problem-solving

Citroën 2CV restoration:
  - long-term restoration work
  - parts research
  - documentation
  - iterative repair

Skydiving:
  - safety procedures
  - checklists
  - risk awareness
  - calm decision-making under pressure

dion@resume:~$ ~/interests.sh --evaluate-impact

impact:
  - Hands-on systems thinking through mechanical repair, customization, and restoration work
  - Long-term persistence through complex projects that require research, documentation, and iterative problem-solving
  - Risk awareness, procedural discipline, and calm decision-making through high-consequence activities
```

---

## >_ References

```console
dion@resume:~$ ./references.sh

references:
  - Available upon request
```

---

<div class="terminal"><span class="prompt">dion@resume:~$ </span><span class="cursor">█</span></div>

---
<!-- ### Footer

Last updated: april 2025 -->


