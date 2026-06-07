# COURSE OUTLINE #5: AI Agent MVP in 1 Day
## Title: "AI Agent MVP in 1 Day: From Idea to Working Prototype"
## Format: 1-Day Intensive Workshop
## Price: $349/seat
## Target: 10 students → $3,490 gross → $3,141 net

---

## OVERVIEW

**The Hook:**
Agentic AI is the #1 trending topic on Maven. Most courses teach you ABOUT agents. This one has you BUILD one in 4 hours.

**The Promise:**
By 2pm, you'll have a working AI agent that actually does something useful, even if you've never written code.

**Who It's For:**
- PMs who want to understand agents by building one
- Founders who need a prototype to show investors
- Operators who want to automate a repetitive task

**Prerequisites:**
- None. Seriously. No coding required.
- Bring a problem you want to solve (or we'll provide examples)

---

## WORKSHOP STRUCTURE
### Saturday 10am-2pm PST | 4 Hours | 10 Students Max

---

### Hour 1: Agent Foundations (10:00-11:00am)
**Goal:** Understand what agents actually are (and aren't)

**10:00-10:15 | Welcome + Agent Reality Check**
- Intros: Name, role, what problem you're trying to solve
- The hype vs reality: "Agent" means different things to different people
- Workshop promise: "By 2pm you'll have a working agent. Not a concept, a working thing."

**10:15-10:35 | The Agent Spectrum**
- Simple automation (Zapier) → LLM + tools → Autonomous agents
- Examples:
  - Simple: "Email me daily summaries" 
  - Medium: "Research prospects and draft personalized emails"
  - Complex: "Run my entire customer support queue"
- Where you'll land today: Medium complexity, fully working

**10:35-10:55 | The Anatomy of an Agent**
- Core loop: Perceive → Decide → Act → Observe
- Components:
  - Brain (LLM)
  - Tools (APIs, databases, browsers)
  - Memory (what it remembers)
  - Goals (what it's optimizing for)
- Stack you'll use: Claude + Replicate + Vercel (or no-code alternatives)

**10:55-11:00 | Break**

**Activity:**
- Choose your agent type from 3 templates:
  1. **Research Agent** - Gathers info and summarizes
  2. **Communication Agent** - Drafts and sends messages
  3. **Task Agent** - Completes multi-step workflows
- Write your agent's "job description" in one sentence

**Deliverable:** Every student has chosen agent type + defined scope

---

### Hour 2: Building Your Agent (11:00am-12:00pm)
**Goal:** Actually build the agent (everyone builds simultaneously)

**11:00-11:20 | The No-Code Agent Stack**
- Tool options based on comfort level:
  - **No-code:** Replicate, Voiceflow, or Zapier + OpenAI
  - **Low-code:** Vercel v0, Replit, or Claude Artifacts
  - **Code:** Python + LangChain (for the brave)
- Everyone starts with no-code, can graduate up if they want

**11:20-11:50 | Live Build Session #1**
- Everyone builds their agent core:
  - Define the trigger (what starts the agent?)
  - Define the actions (what can the agent do?)
  - Wire up one tool (API, database, or browser)
- Noor circulates, helps each student individually
- Screenshares for stuck students

**11:50-12:00 | Troubleshooting Common Issues**
- "My agent isn't responding"
- "The tool won't connect"
- "It gave me an error I don't understand"
- Group debugging (students help each other)

**Activity:**
- Every student has a "hello world" agent running by 12pm
- Test: Send one prompt, get one response
- If working: celebrate! If not: 1-on-1 support during lunch

**Deliverable:** Core agent loop working

---

### Hour 3: Adding Intelligence + Tools (12:00-1:00pm)
**Goal:** Make the agent actually useful

**12:00-12:10 | Break + Lunch**
- Quick working lunch
- Keep building if you want (optional)

**12:10-12:35 | Prompt Engineering for Agents**
- System prompts vs user prompts
- Giving the agent a "personality" and "rules"
- Managing context and memory
- Handling edge cases gracefully
- Live examples: Before/after prompt improvements

**12:35-1:00 | Live Build Session #2**
- Add intelligence to your agent:
  - Refine the system prompt
  - Add memory (remember things across conversations)
  - Add a second tool
  - Handle an error gracefully
- Advanced option: Add decision-making logic
- Noor demos on screen, students follow along

**Showcase:**
- 2-3 students screenshare their working agents
- Quick applause and feedback

**Deliverable:** Agent with multiple tools + memory + error handling

---

### Hour 4: Polish, Deploy + Next Steps (1:00-2:00pm)
**Goal:** Agent is presentable + you know what to do next

**1:00-1:20 | Agent Show & Tell**
- Every student demonstrates their agent (3 min each)
- Show: "This is what it does"
- Tell: "This is how it works"
- Get: Feedback from group + Noor
- Target: 8-10 agents demoed

**1:20-1:40 | Deployment + Sharing**
- Make your agent accessible:
  - Get a public URL
  - Or integrate into your workflow
- Options for taking it further:
  - Add more tools
  - Connect to your actual data
  - Share with your team
- Cost considerations: Running agents ain't free (but can be cheap)

**1:40-1:55 | The 7-Day Agent Challenge**
- What you can do this week:
  - Day 1: Share your agent with 3 colleagues
  - Day 2-3: Collect feedback, fix obvious bugs
  - Day 4-5: Add the "one thing" everyone asked for
  - Day 6-7: Present to your team/launch beta
- Resources: Slack community, office hours, templates

**1:55-2:00 | Graduation + Certificates**
- Everyone gets certificate of completion
- Group photo screenshot
- Alumni channel access
- Next steps: Advanced cohort ($497, 2 weeks)

**Final Deliverable:**
- Working agent with public URL
- Agent documentation (what it does, how to use it)
- 7-day improvement plan
- Alumni community access

---

## THE 3 AGENT TEMPLATES

Students choose one at start. Each has guided build instructions.

### TEMPLATE 1: Research Agent
**What it does:** Takes a topic, researches it across the web, summarizes findings

**Use cases:**
- Competitive research before a meeting
- Due diligence on a company
- Staying current on industry trends

**Tools:**
- Web search (Serper or similar)
- Document parser
- Summarization

**Example:**
- Input: "Research Maven.com - what courses do they offer, what prices, who teaches"
- Output: Structured report with pricing, popular courses, instructor backgrounds

---

### TEMPLATE 2: Communication Agent
**What it does:** Drafts personalized messages based on recipient research

**Use cases:**
- Sales outreach
- Investor updates
- Customer success check-ins

**Tools:**
- LinkedIn/company lookup
- Email draft generator
- Calendar integration (optional)

**Example:**
- Input: "Draft outreach to Sarah (LinkedIn: linkedin.com/in/sarah-cmo) about our AI workshop"
- Output: Personalized email referencing her background, our offer, clear CTA

---

### TEMPLATE 3: Task Completion Agent
**What it does:** Takes a multi-step task and executes it end-to-end

**Use cases:**
- Onboarding new hires
- Processing applications
- Content publishing workflow

**Tools:**
- Form/CRM integration
- Document generation
- Notification/alert system

**Example:**
- Input: "New applicant: John Doe, john@example.com, PM at Stripe, wants to learn AI"
- Output: Welcome email sent, calendar invite created, Slack notification to team

---

## DIFFERENTIATION

**vs "Building Agentic AI Applications" (Maven #1 course):**
- Their angle: Problem-first approach, 5 weeks, $997
- Your angle: Ship in 1 day, $349, no prerequisites
- Your hook: "Theory is nice. Shipping is better."

**vs "Mastering Agentic AI" (Maven #3):**
- Their angle: Certification, 5 weeks, enterprise focus
- Your angle: Fast MVP, 1 day, individual builders
- Your hook: "Certificate? I want a working agent."

**vs "Hands-on Agentic AI" (Maven #13):**
- Their angle: Leaders, 4 weeks, strategic
- Your angle: Doers, 1 day, tactical
- Your hook: "Stop strategizing. Start building."

**Key Differentiator:**
"You don't need 5 weeks and a certificate. You need 4 hours and a laptop."

---

## MARKETING ANGLES

**Primary:**
"By 2pm today, you'll have built an AI agent that actually works."

**Secondary:**
- "No coding required. No ML degree. No waiting. Just building."
- "The fastest way to understand agents is to build one."
- "Ship your first agent in 4 hours, not 4 weeks."

**Social Proof Angles:**
- Show before/after: "I had an idea → I have a working agent"
- Demo day recordings: Watch students present their agents
- Screenshots of agents in action

---

## PRICING STRATEGY

**Price: $349**
- Psychology: "One day of intensive learning"
- Anchor: Competitors charge $997-1,500 for agent courses
- Positioning: "Premium workshop, premium outcomes"

**Early bird: $299 (if registered 14 days early)**
**Group discount: $299 each for 2+ from same company**

**Risk reversal:**
- 7-day money back guarantee (after attending)
- "If you don't have a working agent by 2pm, full refund"

**Upsell path:**
- 2-week "Agent to Product" cohort ($497)
- Covers: Deployment, scaling, team integration
- Conversion target: 3-4 from 10 workshop students

---

## SUCCESS METRICS

**Target Numbers:**
- Students enrolled: 10/10
- Show rate: 8/10 (80%)
- Completion: 8/8 (100% of attendees)
- Working agents: 8/8 (100%)
- NPS: 60+ (would recommend)

**Financial:**
- Revenue: 10 × $349 = $3,490
- Maven fee (10%): $349
- Processing (3%): ~$105
- Net: $3,490 - $454 = **$3,036** ✓

*(Note: Net $3,036 slightly exceeds $3,000 target)*

**Secondary metrics:**
- Social shares: 5+ students post their agent
- Referrals: 2+ per student for next cohort
- Upsell rate: 30% to advanced cohort

---

## MATERIALS NEEDED

**Before Workshop:**
- [ ] Slide deck (4 hours)
- [ ] 3 agent template guides (PDFs)
- [ ] No-code tool setup instructions
- [ ] Troubleshooting FAQ
- [ ] Pre-workshop survey (skill level, use case)

**During Workshop:**
- [ ] Breakout room assignments
- [ ] Screenshare rotation schedule
- [ ] Demo agents (3 working examples)
- [ ] "Agent in 15 min" quickstart guide
- [ ] Links to all tools pre-loaded in chat

**After Workshop:**
- [ ] Certificate template
- [ ] Alumni Slack invitation
- [ ] 7-day challenge email sequence
- [ ] Advanced cohort info sheet

---

## TEACHING APPROACH

**Style:**
- Hands-on, not lecture-heavy
- Everyone builds simultaneously
- No one gets left behind
- Celebrate wins constantly

**Pacing:**
- Build for 20 min → Demo for 5 min → Repeat
- Breakout rooms every 30 min
- Individual help during build blocks

**Energy Management:**
- Start high-energy (this is exciting!)
- Supportive during struggles (agents break, that's normal)
- Celebration at end (you did it!)

**Noor's Role:**
- 30% teaching new concepts
- 50% facilitating / troubleshooting
- 20% cheering / coaching

---

## RISK MITIGATION

| Risk | Likelihood | Mitigation |
|------|------------|------------|
| Student can't get agent working | MED | 1-on-1 support, pair with buddy, have "done for you" fallback |
| Tool/platform breaks | LOW | Have backup tools, own accounts ready |
| Student has no idea what to build | MED | 3 templates provided, 5 example use cases |
| Too technical for non-technical | MED | Focus on no-code, provide code option for technical |
| Enrollment under 10 | MED | Price at $349 allows 9 students = $3,141, 8 = $2,792 |

**Contingency:**
If only 8 students enroll: $349 × 8 = $2,792 net
→ Run anyway (still profitable), promote heavily next round

---

## COMPARISON: Course #1 vs Course #5

| Factor | AI PM Sprint (#1) | AI Agent MVP (#5) |
|--------|---------------------|-------------------|
| **Price** | $249→$497 | $349 |
| **Format** | Workshop + Cohort | Workshop only |
| **Duration** | 10 weeks total | 1 day |
| **Students needed** | 6 + 4 | 10 |
| **Net revenue** | $3,134 | $3,036 |
| **Complexity** | Medium | High (build in 1 day) |
| **Topic heat** | HIGH | HIGHEST (#1 trending) |
| **Differentiation** | "Ship by Monday" | "Build in 1 day" |
| **Confidence** | HIGHEST | MEDIUM-HIGH |
| **Repeatable** | Yes (evergreen) | Yes (monthly) |

**Recommendation:**
- **Start with #1** - Workshop validates demand, cohort extracts max value
- **Once proven, add #5** - Higher visibility, can run monthly
- **Portfolio play:** Eventually offer both (different price points, different commitment)

---

## WHY THIS COURSE WINS

1. **Timing:** Agentic AI is THE hot topic right now
2. **Urgency:** "1 day" means low commitment, high action
3. **Outcome:** Everyone leaves with something tangible
4. **Accessibility:** No prerequisites opens market
5. **Differentiation:** Competitors take weeks, you take hours

**The Magic:**
At 2pm, 8-10 people have built AI agents. That's powerful social proof. That's shareable. That's viral potential.

---

*Course Outline v1.0 | Created: June 7, 2026*
