**Martin Cook's personal portfolio.** Projects and course repos, all non-commercial and none of them client work.

- **Projects** apply what the courses taught. Each carries the same artefacts, from strategy and a PRD to costing, a moat and evals, so a reader sees the full reasoning and the projects can be compared by how they were built, from product thinking and a PRD before any code to building first and documenting on the way. Four of the five are private, because they are personal tools, games and course work rather than products; their layout is shown below.
- **Course repos** are my Product School submissions, kept exactly as submitted. They are the templates the projects take their structure from, and a build type of their own: built to a course template, module by module. They read as course work and are not updated after submission.

### Projects

| Project | Build type | What it shows |
|---|---|---|
| [graph-risk-evals](https://github.com/igoko-consulting/graph-risk-evals) | Product thinking first: the problem space and a two-day discovery sprint, then build and iterate | For fraud and AML detection on one public Bitcoin dataset, invest in graph-derived features, not graph models. The features beat a tuned tabular baseline by a small margin; a graph neural network did not. Pre-registered and reproducible, costs modelled. [Decision matrix](https://github.com/igoko-consulting/graph-risk-evals#the-decision-matrix) |
| Tango (private) | PRD and research first: deep input cycles before any build, then build and iterate | A web app to capture and review Argentine tango sequences: both roles on one timeline, drawn as numbered footprints and tagged by teaching system. Its data was checked by rule-based validators before any app code existed. For my own use only. In progress. |
| [Worldie](https://worldie-football.vercel.app) (private) | Some research and known wants, mixing ideas from older and newer games, then prototype and iterate | A retro arcade football game for browser, iPhone, iPad and Mac, built by Claude Code in phases, each signed off after a playtest. First version complete. |
| [Slapsies](https://slapsies.vercel.app) (private) | Build first: minimal input, inspired by several games, quick and light, documented on the way | A light 2D fighting game whose characters are everyday pet peeves, built the same way. In progress. |
| AI Trip Copilot (private) | Course work adapted: the AI Product Management and AI Product Strategy courses applied to one product, then laid out on the project template | The travel-disruption copilot from the AI Product Strategy course repo below, with its prototype and strategy in one place. Fictional: scripted data, modelled figures, role-played user sessions. Scored against its golden test case, the prototype gets the final answer right but fails three of nine steps. |

Code and a short write-up for each private project are available on request.

### How a project is laid out

The four private projects share one layout, kept in a private template drawn from Worldie, the first of them. Each chapter names the course repo it mirrors, and a chapter is filled only when the work behind it exists, so an empty one says so rather than being padded.

```
01-the-bet         strategy one-pager, diagnostic, teardown, business case
02-strategy        decision matrix, gated roadmap, OKRs
03-prd             PRD by requirement ID, versions never overwritten
04-ux              user flows and feel gaps
05-agents          specs for the build's agents, with dry-run traces
06-evals           eval stack, failure taxonomy, judge calibration, rubric
07-orchestration   build across Claude Code sessions, team charter
08-ai-feature      prompt, RAG PRD, trust gaps, trajectory evals
09-the-moat        data flywheel and kill switch
10-the-margin      per-phase metrics, build and AI costs
11-the-contract    golden dataset, reliability contract, guardrails
12-the-pitch       pitch page and demo script
13-go-to-market    positioning, messaging, pricing (applied exercise)
stakeholders       role-played reviews of the PRD, with an objection log
docs               spec, decisions, progress, playtest notes, learnings
CLAUDE.md          working rules for the Claude Code sessions
```

When a course finishes, its sections are mapped into the template once, then retrofitted into each project the same way. graph-risk-evals came before the template and keeps its own layout.

### Course repos

| Course | Repository | What was submitted |
|---|---|---|
| AI Evals | [ai-evals](https://github.com/igoko-consulting/ai-evals) | HOLD on Ascend IQ, a fictional market-intelligence agent: a failure audit, an eval suite, judge calibration and release gates. [Ship-or-hold memo](https://github.com/igoko-consulting/ai-evals/blob/main/06-culture/ship-hold-memo.md) |
| Agentic Loops for PMs | [pm-os-agent](https://github.com/igoko-consulting/pm-os-agent) | Cortex, an agent that drafts a weekly leadership update, checks it against the evidence it pulled and stops at a human because no tool can post. Never run on real data. |
| AI Product Management | [juno-pm](https://github.com/igoko-consulting/juno-pm) | A spec for Juno, a copilot that turns Slack, Jira and Notion escalations into a cited priority for RocketShip, the course's fictional company, from prompting through a RAG PRD, agent design and evals. Not run on a live model. |
| AI Product Strategy | [my-AI-product-strategy](https://github.com/igoko-consulting/my-AI-product-strategy) | Strategy for a hypothetical travel-disruption copilot, my own idea: the bet, moat, margin, eval contract, guardrails and pitch. Figures modelled; no traveller or carrier has been asked. |
| Product Leadership | [product-leadership](https://github.com/igoko-consulting/product-leadership) | One bet for Fable Growth, a fictional wellness app, from strategy and OKRs to a business case with a kill criterion. [Business case](https://github.com/igoko-consulting/product-leadership/blob/main/05-business-case/business-case.md) |
| Go-to-Market | [roamly-gtm-strategy](https://github.com/igoko-consulting/roamly-gtm-strategy) | Strategy, competition, positioning, messaging and pricing for Roamly Groups, a fictional group-booking feature, where each chapter's test, mostly in two AI models, changed an earlier answer. |
| Claude Code for Product Managers | [claude-code-for-pm-workspace](https://github.com/igoko-consulting/claude-code-for-pm-workspace) | Discovery to prototype for Nudge, a fictional personal-finance app, run from Claude Code: a PRD, role-played stakeholder reviews and an HTML prototype. |
