# AI-assisted development

I build most of these projects with AI coding agents. This page explains what that means, so that nobody has to guess.

## What I do
- Define the product problem, scope and requirements, and decide what is out of scope.
- Choose the architecture, data model, security boundaries and third-party components, usually after comparing options in a written plan.
- Break work into milestones with acceptance criteria and explicit approval gates. Risky steps (real data, signing, releases, publishing, destructive migrations) need a separate approval.
- Review the results, run the checks, test the apps by hand, and accept or reject each milestone.
- Decide what is "done", and record what is **not verified**.

## What AI agents do
- **Planner agent:** drafts plans, alternatives and risk lists for me to approve.
- **Implementation agents** (frontend, backend): write most of the code and tests under these plans. I direct and review them.
- **Independent reviewer:** OpenAI Codex, running read-only, reviews meaningful changes for correctness, security and overstated claims. Verdicts are PASS, PASS WITH ISSUES or BLOCK. Open critical or high findings block a milestone, unless I explicitly accept the risk. Where I have done that, the case study says so.

Tools: Claude Code (Anthropic) as the main coding agent environment, OpenAI Codex as the reviewer, and MCP servers to connect agents to tools.

## What this means for my skills
- I am strongest at **problem framing, system design, integration, verification discipline, and directing AI agents** on real projects.
- I read, review and debug the code in these projects, but I don't claim expert-level hand-written fluency in every language listed. Python appears only as automation and generation scripts written with AI assistance. I don't list SQL as a skill.
- Third-party code (templates, upstream servers, SDKs, sample code) is credited in each case study and not presented as mine.
