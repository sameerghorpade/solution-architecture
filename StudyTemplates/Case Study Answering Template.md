
### ✅ **Solutions Architect Case Study Checklist**

#### **STEP 0: THE OPENING (First 60 Seconds)**
- [ ] **Restate & Align:** "Let me make sure I understand. The core goal is to **[state goal]** because of **[pain point]**, correct?"
- [ ] **Seek Permission:** "Before I propose a solution, may I ask a few clarifying questions?"

#### **STEP 1: CLARIFY & SCOPE (Q&A Phase)**
*(Ask questions from at least 3 categories)*
- [ ] **Business Goals:** Primary driver? (Cost, Speed, Risk, Compliance)
- [ ] **Users & Functions:** Who are they? What are their key tasks?
- [ ] **Non-Functional (RASCAL):** Latency, Availability, Scale, Security needs?
- [ ] **Current State:** What exists today? Biggest pain point?
- [ ] **Constraints:** Timeline, budget, tech mandates?
- [ ] **Scale Estimation:** "To size the solution, what's the **user/transaction volume** and **data size**?" *(CRITICAL ADDITION)*

#### **STEP 2: DEFINE REQUIREMENTS (Your "Part I")**
- [ ] **Business Goal:** State a crisp, one-line *why*.
- [ ] **Functional Requirements:** List 2-3 things the system must *do*.
- [ ] **Non-Functional Requirements:** Define 2-3 measurable **RASCAL** targets.

#### **STEP 3: SIZE THE PROBLEM (Envelope Estimates)**
- [ ] **Perform Quick Math:** Based on answers, estimate **QPS (Queries Per Second)**, **data volume/day**, **peak concurrent users**.
- [ ] **Draw Conclusion:** State what this means for the architecture (e.g., "This is moderate scale, so a managed database is sufficient").

#### **STEP 4: PROPOSE STRATEGY (Your "Part II")**
- [ ] **Architectural Principles:** State 1-2 guiding stars (e.g., "Security-First," "Loose Coupling").
- [ ] **Key Patterns:** Name 1-2 patterns from your **10-Pattern List** that fit the **Problem Family**.

#### **STEP 5: HIGH-LEVEL DESIGN (Your "Part III")**
- [ ] **Phased Approach:** Outline Phase 1 (Pilot/Foundation), Phase 2 (Scale), Phase 3 (Optimize).
- [ ] **Diagram Description:** Describe the boxes and arrows. "Clients → API Gateway → Services..."
- [ ] **First Enabler Feature:** Name the first concrete work item for the backlog.

#### **STEP 6: TECHNOLOGY & EXECUTION (Your "Parts IV & V")**
- [ ] **Technology Selection:** Justify 2-3 key tech choices, linking them to requirements **and scale estimates**.
- [ ] **Risks & Mitigations:** Identify 1-2 key risks and your mitigation plan.
- [ ] **Explicit Trade-off:** State one conscious trade-off (e.g., "We trade initial complexity for long-term agility").
- [ ] **Next Step:** Propose the immediate next action (e.g., "A 2-day discovery sprint").

---

