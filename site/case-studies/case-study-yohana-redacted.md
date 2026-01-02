# AI-Powered Concierge console

Transforming concierge assistants with AI from researchers into experience curators

![Hero image – anonymised]()

What if we built for the _output_, not the process? Proposal creation dropped from ~3.5 days to ~2 minutes. Estimated quality improved ~4×. Assistants could focus on curating experiences – not hunting for information.

> _Note:_ Some details have been anonymised due to confidentiality agreements. The work and outcomes are presented without client-identifying information.

## At a glance

![Stats image – anonymised]()

- **Client:** Consumer family concierge startup – helping busy families fulfil tasks and plans via human assistants
- **Format:** Extended AI Product Sprint (12 weeks)
- **My role:** product & tech lead – strategy, UX, prototyping
- **Team:** focused squad of 3 (me, product designer, PM)
- **Delivered:** working concierge console prototype (demo-ready), plus technical proof-of-concepts and design artefacts outlining an implementation roadmap and next steps

## The problem

Concierge assistants were spending ~3.5 days researching, vetting, and assembling proposals for customers – slow, expensive, and inconsistent under load. Free-form proposals were also hard to review, get feedback on, and iterate on.

## The key insight – “the output is the proposal”

![Proposal builder – anonymised]()

The breakthrough wasn’t “build an AI search tool”. It was recognising that the core unit of work is a **proposal artefact** – and that proposals can be structured.

We spent the first week focusing on the _why_ rather than jumping straight to the _how_. Instead of optimising research, we looked at what assistants were actually producing and what made it take so long.

### Atomic proposals

![Atomic model – anonymised]()

By breaking proposals into structured templates composed of reusable components (“atoms” and “molecules”), we reduced research time, improved consistency, and created tighter feedback loops. Combined with rich customer context, the console could generate personalised drafts that were easy to refine in minutes, not days.

## What we designed and built

- **End-to-end concierge console prototype** that streamlined the workflow from request intake → research → structured draft proposal → assistant curation → final delivery (with a live demo environment)
- **Structured proposal model** (templates composed of reusable atoms/molecules) to standardise output and enable rapid iteration
- **Human-in-the-loop review controls** (edit, approve, regenerate sections) so assistants stayed in charge of quality
- **A set of technical POCs** exploring multiple approaches to retrieval and generation (including hybrid search patterns)
- **An interactive demo of a hybrid recommendation library + generative layer**, designed with feedback capture in mind from day one

## Outcomes

- **Speed:** proposal creation time: ~3.5 days → ~2 minutes
- **Quality:** ~4× estimated improvement via structure, reuse, and clearer review loops
- **Operational impact:** fewer human hours per proposal – assistants shifted to higher-value work (curation, customer interaction)

## Timeline

During discovery we identified the key building blocks of design and functionality. We then ran design and prototyping in parallel, with each workstream informing the other.

- **Weeks 1–2:** immersion, problem framing, workflow mapping, early sketches
- **Weeks 3–4:** data-model reframing, stakeholder validation, engineering alignment
- **Weeks 4–11:** rapid end-to-end prototyping + smaller technical POCs, iteration with real concierge flows, UX/UI refinement
- **Week 12:** demo, handover, and next-phase roadmap

## What I learned

- **Problem before tech:** model the artefact and UX first – then apply AI. It’s easier to design around constraints once you know what you’re actually building.
- **Speed only matters if quality holds:** better specificity produces better outputs – and reduces the need for endless regeneration.
- **Reusable atoms compound over time:** a library of atoms/molecules accelerates assembly, improves consistency, and makes feedback capture simpler – and the benefits stack with every request.

## CTA

If your team spends days researching and packaging information into proposals, recommendations, or reports, structured output design can collapse that cycle dramatically. I’d love to share what we learned and how a similar approach might apply in your context.

Say hello.
