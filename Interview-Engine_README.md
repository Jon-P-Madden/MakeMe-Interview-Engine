# Make Me! Interview Prep Engine

**Make Me! Interview Prep Engine** is a planned AI-assisted preparation tool that will turn resume and application context into interview-ready stories, answers, and talking points.

Part of the **Make Me!** career tools suite - built by a Senior Technical Program Manager to solve real job search problems with practical AI-assisted workflows.

Strong interviews do not start from scratch. They start from the story the user has already built.

![Make Me! Interview Prep Engine](Screenshot.png)

---

## What This Will Demonstrate

- A planned workflow for moving from application context to interview preparation
- AI-assisted question generation based on role, resume, and job description context
- Structured STAR story development
- Role-specific talking point generation
- Interview prep that connects to the user's existing resume and application materials
- A later-stage career workflow that complements the built Make Me engines

---

## The Problem

Many candidates prepare for interviews by searching generic question lists. That can help, but it often misses the actual context: the user's resume, the target role, the company, the job description, and the story they need to tell.

The hardest part is not simply predicting questions. It is turning real experience into clear examples, confident answers, and memorable talking points that fit the role.

---

## The Planned Solution

The Interview Prep Engine is planned to support a structured preparation workflow:

1. Capture the user's resume, profile, job description, company context, and interview type
2. Generate likely questions based on the role and application context
3. Help shape STAR stories from the user's actual experience
4. Draft answers for prompts like "Tell me about yourself" and "Why this company?"
5. Create role-specific talking points and preparation notes
6. Highlight areas the user should review before the interview

The intended result is a focused prep guide grounded in the user's real background and target opportunity.

---

## Design Constraints (Intentional)

- Planned engine; not active in the current prototype suite
- Intended to build on existing resume and application context
- Designed for preparation guidance, not automated interviewing
- Expected to remain user-reviewed and user-edited
- Intended to avoid generic interview advice where role-specific context is available

---

## Planned Capabilities

### Interview Context

- Resume and profile intake
- Job description context
- Company information
- Target role
- Interview type
- Recruiter or hiring manager notes when available

### Question Generation

- Likely recruiter screen questions
- Behavioral interview questions
- Role-specific interview questions
- Technical or program-management prep prompts where relevant

### Story Development

- STAR story bank
- "Tell me about yourself" answer
- "Why this company?" answer
- Experience-to-question mapping
- Talking points tied to the user's positioning

### Prep Output

- Interview prep guide
- Likely questions
- Story prompts and answer drafts
- Company-specific notes
- Areas to prepare for

---

## Planned Architecture

```text
User Browser
  |
  v
Interview Prep Workflow (planned)
  |
  +--> Resume/profile/application context
  |
  +--> Job and company intake
  |
  +--> Interview question and story-generation workflow
  |       |
  |       v
  |   Runtime-selected AI provider/model
  |
  v
Interview prep guide, STAR stories, talking points, and answer drafts
```

The planned engine is expected to reuse profile, resume, application, and job-description context from the broader Make Me suite once those shared systems are mature enough to support it.

---

## Setup

This engine is planned and is not yet active as a standalone workflow. Setup instructions will be added when the engine is implemented.

---

## Known Limitations

- The engine is planned and not currently implemented.
- Current documentation describes intended product scope, not active functionality.
- Generated interview materials, once implemented, will still require user review and practice.
- Company-specific prep will depend on the quality of user-provided context or future research integrations.

---

## Tech Stack

Planned to align with the existing Make Me prototype stack:

- Vanilla HTML / CSS / JavaScript
- Browser `localStorage`
- Runtime AI provider/API key input
- No backend in the initial prototype unless the suite architecture changes

---

## Roadmap

- Define the interview prep specification
- Build structured interview context intake
- Generate role-specific question sets
- Add STAR story development workflow
- Connect prep to Application Engine records
- Support saved interview prep guides

---

## Part of the Make Me! Suite

| Engine | Tool | Purpose |
|--------|------|---------|
| Engine 1 | **Make Me! Resume Positioning Engine** | Build a strategically positioned resume from raw career history |
| Engine 2 | **Make Me! Application Engine** | Analyze job postings, tailor application materials, generate cover letters, and track applications |
| Engine 3 | **Make Me! LinkedIn Optimization Engine** | Optimize LinkedIn profiles for recruiter searchability and credibility |
| Engine 4 | **Make Me! Interview Prep Engine** | Planned engine for interview questions, STAR stories, and role-specific prep |
| Engine 5 | **Make Me! Salary Negotiation Engine** | Planned engine for compensation strategy, counteroffers, and negotiation messaging |
| Engine 6 | **Make Me! Recruiter Outreach Engine** | Planned engine for recruiter, referral, and networking outreach |

---

## Why This Exists

Interview prep should not feel disconnected from the rest of the job search. The user's resume, application, target role, and company context already contain the raw material for strong answers.

This engine exists to help users turn that raw material into stories they can actually say out loud: specific, relevant, credible, and aligned with the opportunity in front of them.

- **Prep design** - connects interview answers to real resume and application context
- **AI as interpreter** - planned model output will shape experience into likely questions and stories
- **Workflow thinking** - questions, stories, talking points, and prep gaps in one flow
- **Constraint-driven architecture** - planned to follow the suite's browser-first, local-first pattern

---

## License

**PolyForm Noncommercial 1.0.0** — free for noncommercial use.

You can use, modify, and share this software for personal, educational, research, or charitable purposes. Commercial use requires a separate license.

See [LICENSE](LICENSE) for the full terms, or visit [polyformproject.org/licenses/noncommercial/1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/) for the official text.

For commercial licensing inquiries, contact [MaddenJonP@gmail.com](mailto:MaddenJonP@gmail.com).

---

*Built by Jonathan Madden*
*[LinkedIn](https://linkedin.com/in/jonathan-p-madden) - [github.com/Jon-P-Madden](https://github.com/Jon-P-Madden)*
