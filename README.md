# John A. Green - What I've Been Building

**Alpharetta, GA** • [GitHub: jagreen03](https://github.com/jagreen03) • [LinkedIn](https://www.linkedin.com/in/jagreen03/) • 770-598-7331

---

## The Short Version

Since leaving Ingenious Med in August 2025, I've been treating this time as a self-directed R&D sprint. I didn't want to just "wait" for the next role—I wanted to keep my architectural skills sharp and explore how AI orchestration patterns fit into production .NET systems.

I've published **8 active repositories** between September and October 2025. Each one follows the same discipline I used professionally: identify a problem, design the architecture, build a working proof-of-concept, and document it properly.

This isn't busywork. It's the same methodology that won me 2nd place in the Ingenious Med Hackathon and delivered the tokenized authentication system I built there.

---

## What I've Been Working On

### **🔐 BlueStage.Epinikion.Logos** (Updated Oct 28, 2025)
**OAuth 2.0 / PKCE Identity Architecture Study**

This is an architectural study exploring secure authorization flows across Kestrel and IIS hosting environments. I'm documenting synchronization points and failure modes between the two server models—the kind of unglamorous work that prevents production incidents.

- **Tech Stack:** C# .NET Core, OAuth 2.0/PKCE, Kestrel, IIS
- **Key Pattern:** "Temporal Anchor" session management (binding token expiration to deterministic time boundaries instead of ad-hoc timeout logic)
- **Documentation:** UML sequence diagrams, ER models, Mermaid.js diagrams version-controlled in the repo
- **Why It Matters:** This is the same identity validation discipline I delivered at Ingenious Med with the tokenized authentication system

[View Repository →](https://github.com/jagreen03/BlueStage.Epinikion.Logos)

---

### **🤖 BlueFrame.MailAnalyzer** (Updated Oct 10, 2025)
**Multimodal AI Desktop Application**

A standalone desktop app for analyzing physical mail using multimodal AI. This explores how to integrate AI capabilities into traditional desktop workflows without cloud dependencies.

- **Tech Stack:** JavaScript, Multimodal AI APIs
- **Purpose:** Proof-of-concept for AI-driven document processing
- **License:** MIT

[View Repository →](https://github.com/jagreen03/BlueFrame.MailAnalyzer)

---

### **🗺️ BlueSand** (Updated Oct 6, 2025)
**Code/Documentation Analysis Toolkit**

A toolkit that finds "unicorn" terms across codebases and documentation, mapping the overlap between what's planned vs. what's actually implemented. Generates ranked word maps to identify documentation gaps.

- **Tech Stack:** C# .NET
- **Use Case:** Sustaining engineering—finding where documentation has drifted from reality
- **License:** MIT

[View Repository →](https://github.com/jagreen03/BlueSand)

---

### **📺 AuraSolutions.MediaAutomation** (Updated Sep 15, 2025)
**YouTube Automation with AI APIs**

A C# console application designed to automate media content creation for YouTube channels. Integrates with AI APIs (Hugging Face, etc.) to orchestrate content pipelines.

- **Tech Stack:** C# .NET, AI API Integration
- **Pattern:** Multi-stage automation pipeline with error handling
- **Why It's Relevant:** Demonstrates API orchestration and service integration—skills that transfer directly to EDI and payment gateway work

[View Repository →](https://github.com/jagreen03/AuraSolutions.MediaAutomation)

---

### **🏗️ AuraSolutions** (Updated Sep 14, 2025)
**Modular .NET Foundation**

A modular .NET solution organized into Core, Console, and Shared projects. This is foundational architecture for building reusable components—the kind of structure that keeps systems maintainable over years.

- **Tech Stack:** C# .NET, modular architecture
- **Purpose:** Reusable component library for future projects
- **License:** MIT

[View Repository →](https://github.com/jagreen03/AuraSolutions)

---

### **⚙️ CoreAutomationScripts** (Updated Sep 12, 2025)
**Operational Automation Toolkit**

A centralized collection of PowerShell automation scripts for operational and development tasks. This is the "factory floor" tooling—the scripts that keep systems running smoothly.

- **Tech Stack:** PowerShell
- **Use Case:** DevOps automation, system maintenance, deployment scripting
- **License:** MIT

[View Repository →](https://github.com/jagreen03/CoreAutomationScripts)

---

### **🔄 GitxAutomationTools** (Updated Sep 12, 2025)
**Git Workflow Standardization**

PowerShell module and automation scripts for standardizing Git workflows. Reusable functions for initializing repositories, managing .gitignore files, and enforcing consistent commit patterns.

- **Tech Stack:** PowerShell
- **Purpose:** Team workflow standardization
- **License:** MIT

[View Repository →](https://github.com/jagreen03/GitxAutomationTools)

---

### **📊 EmploymentHistoryAnalyzer** (Updated Sep 11, 2025)
**Career Pattern Analysis**

A tool for analyzing employment history to reveal career patterns, skill development, and the narrative beyond a resume. This was a personal experiment in understanding my own professional journey—and it helped me realize I need to pivot toward sustaining engineering roles where longevity is valued.

- **Tech Stack:** C# .NET
- **Insight:** Built this to understand my own career trajectory—it confirmed what I already knew: I thrive in stabilization and support roles, not perpetual greenfield development

[View Repository →](https://github.com/jagreen03/EmploymentHistoryAnalyzer)

---

## How I Work: The Modern Workflow

People sometimes ask how I'm able to produce this volume of documented, architectural work. Here's the honest answer:

### **Local AI as a Force Multiplier**

I use **LM Studio** and **Ollama** to run large language models **locally** on my hardware. This means:
- I never send proprietary code to the cloud
- I can generate UML diagrams, ER schemas, and architectural documentation 10x faster
- I maintain full data privacy while leveraging AI capabilities

### **Docs-as-Code Philosophy**

I use **Mermaid.js** within VS Code and **Obsidian** to render live diagrams directly in README files. This ensures documentation never goes stale—it's version-controlled alongside the code.

### **Architecture-First Mindset**

I don't just write code. I:
1. Define the system boundary
2. Model the data flow (ER diagrams, sequence diagrams)
3. Validate the architecture in a proof-of-concept
4. Document the decision-making process

This is the same discipline I applied at Ingenious Med, where I used **Miro** to communicate architecture to non-technical stakeholders in Finance, Clinical, and Operations.

---

## What I'm Looking For

I'm targeting **Sustaining Engineering**, **Tier 3 Support**, and **EDI/Integration Engineer** roles in the **Alpharetta/Roswell/Johns Creek/Norcross** area.

### **My Value Proposition:**

**"Overqualified = Zero-Risk Reliability"**

- I'm 62, local to Alpharetta, and want stability (3-5 years) over startup lottery tickets
- I will work for **$90-100k salary + benefits** (or $50-60/hr W2 contract)—which is 15-20% below market rate
- I'm reaching out **directly to hiring managers** to avoid recruiter fees (saving companies $20-30k)
- I specialize in the unglamorous work: forensic debugging, legacy .NET stabilization, EDI mapping, production support

### **What I Don't Want:**

❌ Greenfield "move fast and break things" cultures  
❌ Agile sprint teams building the next SaaS product  
❌ Roles that require constant job-hopping to stay relevant  

### **What I Do Want:**

✅ Keeping legacy .NET systems running (Framework 4.x → .NET 8)  
✅ Tier 3 escalation ownership for complex production issues  
✅ EDI X12 mapping (835/837) and payment gateway integrations  
✅ Writing forensic incident reports in plain English  
✅ Being the guy who shows up Monday through Friday, same desk, same attitude  

**Motto:** *"I don't just write code; I keep the factory running."*

---

## Technical Profile

### **Core Skills:**
- **Languages:** C# 12/14, SQL Server (Expert-level), PowerShell, Python (AI tasks)
- **Frameworks:** .NET 8/10, .NET Framework 4.x, ASP.NET, REST/SOAP APIs
- **Security:** OAuth 2.0/PKCE, PCI-DSS, HIPAA, OWASP Top 10
- **DevOps:** Docker, Kubernetes, Azure DevOps, Git, CI/CD pipelines
- **AI/ML:** Gemini SDK, Semantic Kernel, LM Studio, Ollama
- **Documentation:** Miro, UML, ER Diagrams, Mermaid.js, Obsidian

### **Industry Experience:**
- **Healthcare IT:** EDI 835/837 claims processing, HIPAA compliance, revenue cycle management
- **Payment Processing:** ACH, credit card processing, PCI-DSS compliance, merchant services
- **Financial Services:** Check processing, core banking systems, transaction reporting
- **IoT/Utilities:** Smart Grid telemetry, MSMQ message queues, distributed systems

---

## Professional Highlights

### **Ingenious Med Hackathon - 2nd Place**
Led backend development for a mixed-department team, integrating **Azure AI services** to extract keywords from clinical images and text, then programmatically querying legacy CPT search engines. Presented to management and awarded 2nd place out of 7 teams.

### **Tokenized Authentication System (Ingenious Med)**
Designed and implemented a token-based login system (Access + Refresh tokens) replacing long-lived password credentials with expiring tokens. Coordinated rollout across mobile, web, and backend teams. Mentored developers on identity validation patterns.

### **Partitioned Database Design (Alogent)**
Implemented a partitioned MS SQL database architecture that improved query performance on high-volume check-image-recognition workflows and simplified diagnostics across legacy and new applications.

---

## Contact & Links

- **Email:** jagreen03@gmail.com
- **Phone:** 770-598-7331
- **GitHub:** [github.com/jagreen03](https://github.com/jagreen03)
- **LinkedIn:** [linkedin.com/in/jagreen03](https://www.linkedin.com/in/jagreen03/)
- **Location:** Alpharetta, GA (no relocation)

---

## References Available Upon Request

I've worked at **Ingenious Med**, **Alogent**, **Landis+Gyr**, **Planet Payment**, and multiple other companies over 20+ years. References can verify:
- My forensic debugging capabilities
- My ability to stabilize legacy systems without breaking them
- My talent for explaining complex architecture to non-technical stakeholders
- My reliability (I show up, I document, I solve problems)

---

*Last Updated: February 2026*
