# Resume Review — Ishaan Kohli
> Goal: Get selected at top-tier companies (FAANG, Stripe, Databricks, etc.)
> Standard: Brutally honest. Every weakness is a rejection risk.

---

## Status Tracker

| Area | Status | Priority |
|------|--------|----------|
| Missing Meta FTE role | ✅ Info collected | CRITICAL |
| Yellowbrick end date wrong | ✅ Info collected (Nov 2025) | CRITICAL |
| Weak/unquantified bullets | ❌ Not done | HIGH |
| No resume summary | ❌ Not done | HIGH |
| VMware intern bullet impact | ❌ Not done | MEDIUM |
| Vague VMware FTE start date | ❌ Not done | LOW |
| No projects section | ❌ Not done | LOW |

---

## CRITICAL — Fix Before Anything Else

### 1. Meta FTE Role is Missing
Your current job at Meta (Dec 2025–Present) is completely absent.
This is your single most valuable credential right now and it's not on your resume.
A recruiter looking at this thinks you're still at a 100-person data warehouse company.
**Action:** Add Meta SWE role with title, dates, and bullets. Needed from Ishaan: title, team, and work done so far.

### 2. Yellowbrick Still Says "Present"
You left Yellowbrick. The resume says you're still there.
If a recruiter cross-references this with LinkedIn, it looks like a lie.
**Action:** Update end date. Needed from Ishaan: exact end date.

---

## HIGH — Will Cost You Offers

### 3. Bullets Describe Tasks, Not Impact
Top companies screen for scope and impact, not just what you built.
The question every bullet must answer: "So what? How many people/systems/dollars did this affect?"

**Yellowbrick — Kubernetes Operator**
- Current: "reducing manual provisioning time by 50%"
- Problem: 50% of what baseline? For how many engineers? How many instances?
- Fix needed: Add scale context. e.g. "...reducing provisioning time from X hrs to Y min across Z engineers"

**Yellowbrick — Upgrade mechanism**
- Current: "reduced downtime to near-zero"
- Problem: "near-zero" is vague and unverifiable. Screams that you don't know the real number.
- Fix needed: Actual before/after. e.g. "from ~4hr maintenance windows to <5 min rolling upgrades"

**Yellowbrick — Autoscaler**
- Current: "Engineered a Multi-Cloud Node Group autoscaler for Yellowbrick Compute Clusters."
- Problem: One sentence, no metric, no outcome. This is likely your most technically complex work at Yellowbrick and it has the weakest bullet.
- Fix needed: Cost savings? Latency improvement? Scale (nodes, clusters, cloud spend)?

**Meta Intern — Hours saved**
- Current: "saving 5–7 employee hours per week"
- Problem: This is embarrassingly small for a Meta-scale system. WhatsApp Web has 100M+ users. What was the user-facing impact? What was the business analytics impact?
- Fix needed: Find a bigger number. User reach, data volume, latency, adoption rate. 5-7 hrs/week is a junior freelancer metric.

**Meta Intern — 100% test coverage**
- Current: "Achieved 100% unit test and e2e test coverage"
- Problem: This is not an achievement. This is a checkbox. Every company expects tests. Remove or replace entirely.
- Fix needed: Replace with something that shows real impact from the pipeline going live.

**VMware FTE — Kafka consumer balancing**
- Current: "Implemented a Kafka Consumer balancing algorithm...to reduce network bandwidth maximization"
- Problem: No metric. "Reduce network bandwidth maximization" doesn't even make grammatical sense as an outcome.
- Fix needed: Actual throughput numbers, latency reduction, cost savings, number of clusters affected.

**VMware FTE — ETL pipeline redesign**
- Current: "increase scalability and reusability"
- Problem: "Scalability and reusability" are buzzwords. Not measurable, not verifiable.
- Fix needed: Ingestion volume before/after, latency before/after, or number of teams that adopted it.

**VMware Intern — Bug fixes**
- Current: "leading to increased visibility and 5 critical bug fixes"
- Problem: You built the tool that found bugs. That's great. But "5 bug fixes" as the headline outcome is weak — the real story is what those bugs were costing the system.
- Fix needed: What was broken? What was the downstream impact of fixing those 5 bugs?

### 4. No Summary Section
Top companies process hundreds of resumes. A 2-line summary at the top tells the recruiter immediately who you are and what you're targeting. Without it, they have to piece together your story themselves — and they won't.
- You are: a backend/infra engineer with 6+ years, now at Meta, with deep Kubernetes/cloud/distributed systems experience.
- That story is not obvious from scanning the resume cold.
**Action:** Write a 2-line summary. Needed from Ishaan: what roles/companies are you targeting?

---

## MEDIUM — Will Hurt in Competitive Situations

### 5. VMware Intern Bullet Is One-Dimensional
The intern role at VMware has one bullet. It ends with "5 critical bug fixes."
For a role that ran 6 months, one bullet with a weak outcome makes it look like you did very little.
Either strengthen the single bullet dramatically or cut the role entirely and save space for better content.

### 6. Skill Section Is Unstrategic
The skills section is honest but not optimized.
- "OOPs" should be "OOP" — looks like a typo.
- "Agile Software Development" wastes a slot. Everyone claims this. Remove it.
- Missing: Prometheus, Grafana, CI/CD (if applicable) — common infra skills that ATS systems scan for.
- Consider reordering to lead with your strongest/most relevant skills for the roles you're targeting.

---

## LOW — Polish Items

### 7. VMware FTE Start Date Is Vague
Current: "2019 – Aug 2021". The start month is missing. Looks careless.
Fix: "Aug 2019 – Aug 2021" (or whatever the actual start month was).

### 8. No Projects Section
You have a GitHub (i5haan). If there's anything notable there — even one solid project — it should be on the resume.
Open source contributions, personal tools, anything that shows you code outside of work.
If there's nothing notable, skip it.

---

## Pending Information Needed from Ishaan

- [ ] Meta FTE: exact title, team (optional), and 2-3 things worked on (even rough notes)
- [ ] Yellowbrick: exact end date
- [ ] Yellowbrick autoscaler: any metrics? (cost, scale, latency)
- [ ] Yellowbrick upgrade mechanism: before/after downtime numbers
- [ ] Meta intern: any user-facing or data-scale metrics beyond the hours saved?
- [ ] VMware Kafka: any throughput/latency numbers?
- [ ] Target roles/companies: so we can tailor the summary

---

## Rewrite Log

| Bullet | Original | Rewritten | Status |
|--------|----------|-----------|--------|
| Meta FTE — build graph filtering | ❌ Missing | ✅ Done | Ready |
| Yellowbrick — autoscaler | One sentence, no metric | ✅ Approved | Done |
| Yellowbrick — upgrade mechanism | "near-zero", no context | ✅ Approved | Done |
| Yellowbrick — Kubernetes Operator | "50%", no context | ✅ Approved | Done |
| Yellowbrick — E2E test framework | Generic "platform services" | ✅ Approved | Done |
| VMware — ETL pipeline | "scalability and reusability" buzzwords | ✅ Approved | Done |
| VMware — Kafka consumer balancing | No metric, bad grammar | ✅ Approved | Done |
| VMware — Graviton 2 migration | New bullet added | ✅ Approved | Done |
| Yellowbrick — end date | "Present" | "Jun 2023 – Nov 2025" | Ready |

---

## Approved Rewrites

### Meta SWE (Dec 2025 – Present) — Wearables Infra
- Implemented build graph filtering for test selection across the wearables device fleet, eliminating ~30K redundant tests per day (~20% of 150–180K daily tests) and reducing device-hours by 10%.

### Yellowbrick — Autoscaler (replace existing bullet)
- Engineered a Multi-Cloud Node Group autoscaler supporting heterogeneous hardware profiles (x86/ARM, high-CPU/memory/network) across per-customer private deployments on AWS, GCP, and Azure — eliminating manual node group provisioning, automating node lifecycle and cleanup, and removing dependency on generic cloud autoscalers.
