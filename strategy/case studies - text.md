# Project Case Studies – Working Master Document

This document has been generated based on Peter's description and narration through the projects with his voice. It is a verbose, internal reference capturing the full context, intent, approach, and outcomes of the projects discussed so far. It is not marketing copy. The purpose is to act as shared ground truth that we can later distil into website case studies, selected work summaries, or thematic narratives.

---

## Yohana – Concierge Console (AI Product Sprint)

**Client:** Yohana  
**Duration:** 8 weeks  
**Team:** 3 people  
**Format:** AI product sprint

### Context

Yohana’s core proposition is that busy families can offload their to-dos to human assistants. These tasks range from planning trips (for example, a Disneyland holiday), to finding cleaners or babysitters, to researching options and presenting a proposal that the family can approve. The assistants traditionally carried out large amounts of manual research and synthesis work.

At the start of the project, the average turnaround time for a single proposal was approximately **3.5 days**.

Yohana’s brief was to explore whether AI could be used to dramatically speed up this research process, without sacrificing quality.

### Key Insight

Instead of framing the problem as “how do we speed up research?”, the project reframed it as “what is the _output_ of research?”. The true output was not the research itself, but a structured proposal.

By focusing on the proposal as the core artefact, the team was able to rethink how the system should be designed from the ground up.

### Approach

The first week of the sprint was deliberately spent **not discussing AI solutions at all**. The team focused entirely on deeply understanding the problem and exploring how it might be solved even without AI.

This led to a critical shift in the data model:

- Proposals were broken down into smaller components (referred to as “molecules” and “atoms”).
- Different categories of tasks (for example, travel-related requests) were identified.
- Each category was templated into predictable components such as accommodation, transport, activities, and recommendations.
- Each of these components became an individual “atom” that could be produced, evaluated, and improved independently.

Once this atomic structure existed, it became possible to design **highly specific AI systems** that were narrowly tuned to generate or retrieve a single type of output extremely well, rather than one general system attempting to produce an entire proposal.

This atomic approach also allowed for much faster feedback loops, because individual atoms could be reviewed and improved without reworking entire proposals.

### Outcome

The result was a prototype of a new internal console that:

- Reduced proposal turnaround time from **3.5 days to approximately 2 minutes**
- Improved proposal quality by an estimated **4×** in early evaluations
- Significantly reduced operational cost

A major secondary outcome was organisational rather than technical. Assistants shifted from being manual researchers to **curators of experiences**, focusing on reviewing, shaping, and elevating AI-generated outputs.

---

## Tallis Habits App – Thomas Tallis School

**Client:** Thomas Tallis School (Kidbrooke)  
**Platform:** iPad app  
**Audience:** Children aged approximately 7–12  
**Duration:** ~2 months

### Context

Thomas Tallis School had conducted research in collaboration with universities which showed that children who develop five specific learning habits become better learners across a wide range of subjects. These habits included qualities such as inquisitiveness, persistence, discipline, collaboration, and one additional habit.

Before the project, the school tracked these habits manually using a sticker-based system:

- Teachers awarded stickers when children demonstrated a habit
- Each week focused on a single habit across the whole school
- Stickers accumulated on shared classroom posters, reinforcing collaboration rather than individual competition

The brief was to explore how this system could be translated into a digital experience without losing its collaborative and playful nature.

### Approach

The project placed strong emphasis on **co-creation with children**.

A series of workshops were run directly with pupils, and a group of approximately ten children acted as early “ambassadors” for the programme. These children worked closely on:

- Designing how each habit should look, move, and behave
- Defining sounds, animations, and interactions
- Exploring how habits should be tracked, reported, and played with

Each habit evolved into a distinct character. Over time, these characters formed a kind of **murmuration**, visually representing how habits develop together rather than in isolation.

Children were not just participants but active contributors to the design process, which created strong engagement and ownership.

### Outcome

The final iPad app was used across the school for several years and allowed children to explore their learning habits in playful, non-traditional ways.

Instead of charts and graphs, progress was visualised through interactive metaphors such as:

- A music-box-style timeline that could be scrubbed through to explore history
- Drums that could be played, where size and volume represented strength of a habit

The result was a joyful, collaborative tool that supported long-term habit development without reducing learning to abstract metrics.

---

## Centre for Homelessness Impact – Enhanced Evidence Data Platform

**Client:** Centre for Homelessness Impact (CHI)  
**Status:** Alpha delivered, wider rollout planned

### Context

The Centre for Homelessness Impact works with a large body of academic research and evidence related to homelessness interventions. While the evidence is robust, it is difficult to access and apply in practice. Finding relevant evidence often required expert mediation and time-consuming manual searches through academic papers.

The goal of the project was to design and build an enhanced evidence platform that would allow policymakers, researchers, and practitioners to find strong evidence **quickly, confidently, and transparently**.

### Approach

The project avoided framing the solution as a simple “chatbot over PDFs”. Instead, it focused on designing a research tool that respects evidence standards.

Key elements included:

- Structured document ingestion (primarily PDFs)
- User and permission management
- Metadata and evidence management
- Hybrid search combining semantic relevance with traditional signals

A core design principle was the use of **guardrails around AI**. AI-generated outputs were never presented as unquestionable truth. Instead, the system emphasised:

- Traceability back to source documents
- Transparency about uncertainty
- Clear links between answers and evidence

### Outcome

The alpha platform significantly improved how quickly users could find relevant evidence and how confidently they could use it. Early testing demonstrated strong relevance and accuracy, and the platform is now being used as the foundation for a wider rollout.

The project positions AI as a support for evidence-based decision-making rather than a replacement for expert judgement.

---

## DevRev – Agent Studio

**Product:** Agent Studio (enterprise AI teammate)  
**Role:** Front-end design leadership  
**Duration:** ~7 months  
**Status:** Closed beta, GA planned

### Context

Computer is DevRev’s conversational interface into enterprise data. It allows users to talk directly to their organisation’s systems and data, effectively acting as an AI teammate.

The work followed Agent Studio, but focused on bringing a polished, production-ready conversational experience to enterprise customers.

### Approach

The project followed a relatively conventional design process:

- Early sketches and prototypes to establish direction
- Rapid handoff to engineering once core intent was clear
- Heavy emphasis on iteration, polish, and craftsmanship

A key focus was designing a chat interface that could fluidly combine **conversational interaction with traditional UI components**.

### Notable Capabilities

- Visibility into the agent’s reasoning (“thinking stack”), helping users understand why suggestions are made
- Text-to-SQL functionality, allowing users to ask complex analytical questions in natural language
- Automatic generation and execution of SQL queries against live data
- Clean, structured presentation of results using tables and UI components inside the chat

Some explorations (for example, multi-user and collaborative concepts) remain under NDA and are not included here.

---

## Slack Curator (Internal Tool)

**Client:** Normally (internal agency tool)  
**Duration:** 2 weeks  
**Team:** 2 people

### Context

Many agencies use Slack channels for sharing inspiration, links, and ideas. Over time, this content often becomes overwhelming and is quickly forgotten, especially during busy weeks.

The goal was to build a lightweight internal tool that could capture and make sense of this collective knowledge.

### Approach

Slack Curator automatically:

- Ingests posts, comments, and images from a dedicated Slack channel
- Interprets and summarises content using AI
- Prioritises items based on engagement
- De-prioritises low-signal content

### Outcome

At the end of each week, the tool generates a concise internal newsletter summarising:

- What was shared
- What people discussed
- Which items received the most attention

The result is a curated, readable snapshot of collective inspiration rather than a raw content dump.

---

## Indeximate

**Client:** Indeximate  
**Duration:** 8 weeks  
**Scope:** UX/UI strategy and product design (Figma)

### Context

Indeximate works with companies operating deep-sea underwater cables connected to offshore wind farms. Their technology combines hardware and AI to predict where cables are likely to fail, reducing the need for manual inspections using divers.

### Approach

The project began with deep problem understanding:

- Sessions with engineers and stakeholders
- User research
- Mapping existing workflows and technical constraints

Initial designs explored traditional dashboards with hierarchical navigation (sites → petals → cables). However, this approach proved cumbersome.

A major shift occurred when the design moved to a **map-based interaction model**:

- Interactive maps as the primary navigation surface
- Zooming and panning to explore infrastructure
- Heatmaps to visualise different stress factors (e.g. electromagnetic strain, physical stress)

### Outcome

The map-based approach allowed users to understand cable health at a glance and navigate complex systems more intuitively.

Indeximate later won a **Startup of the Year award**, and the product is now in active development.

---

## DeepMirror

**Client:** DeepMirror  
**Duration:** 8 weeks  
**Scope:** UX/UI strategy, design system, information architecture

### Context

DeepMirror applies AI to drug discovery. Users upload sets of molecules into projects and simulate how effective they may be against specific biological targets.

The platform allows users to:

- Evaluate molecule effectiveness
- Generate new molecules
- Run additional simulations and tests

### Approach

The work focused on establishing a clear UX and UI strategy for a highly technical domain.

A key design challenge was clearly distinguishing between:

- Values that were empirically measured
- Values that were inferred, simulated, or generated by AI

This distinction was made explicit through colour coding and visual language, ensuring users could always understand the provenance of the data they were seeing.

### Outcome

The project delivered a clear design system and information architecture that supported ongoing iteration of the product. The emphasis on transparency and interpretability remains a core differentiator of the interface.

---

## Notes

This document is intentionally verbose and descriptive. Its role is to preserve nuance and intent so that future website content can be derived without losing important context.
