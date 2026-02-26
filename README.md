## Project-Management-Tool
In this, we built an AI-first Project Management Tool (along with Figma mockups).

### Detailed Overview

  1. Selected User Persona : Project Manager
  2. Selected Scope of the Tool : Backlog Refinement, Sprint Planning & Estimation
  3. Problem & Opportunity Mapping

| Scope  | Problems | Opportunities |
| ------------- | ------------- | ------------- |
| Backlog Refinement  | Priorities set by urgency instead of feasibility  | Show predicted sprint impact while reordering backlog  |
| Backlog Refinement  | No visibility into sprint capacity impact  | Update capacity usage live as stories move  |
| Backlog Refinement  | Stakeholder pressure overrides data  | Display feasibility signals to support priority decisions  |
| Backlog Refinement  | Downstream dependencies are unclear  | Auto-flag dependency risks during backlog edits  |
| Backlog Refinement  | Trade-offs made blindly  | Preview outcome of each priority change instant  |
| Sprint Planning & Estimation  | Estimates rely on gut feel  | Suggest effort using historical sprint data  |
| Sprint Planning & Estimation  | Dependencies surface too late  | Highlight dependency risks during planning  |
| Sprint Planning & Estimation  | Overcommitment feels unavoidable  | Warn when planned scope exceeds capacity  |
| Sprint Planning & Estimation  | No way to validate sprint feasibility  | Simulate sprint outcome before commitment  |
| Sprint Planning & Estimation  | Risks visible only after sprint starts  | Surface risk signals during planning itself  |

  4. Selected Opportunities : Planning Decisions Blind to Consequences, No Validation Before Sprint Commitment, Historical Data Is Under-utilized
  5. Proposed Solution : ML-Driven Sprint Planning Recommender, Predictive Sprint Health Score, AI Planning Copilot (Chat)
  6. Architecture Diagram of Proposed Solution

<div align='center'>
<img src = 'Architecture Diagram.png' height="300px">
</div>

### Figma Mockup of the Application

- Figma Link : https://swan-class-36114220.figma.site/
- Home Page Dashboard

<div align='center'>
<img src = 'ProAct Software.png' height="300px">
</div>

- Enter Stimulation Mode

<div align='center'>
<img src = 'ProAct Software Stimulation.png' height="300px">
</div>

- Choice between Revert (Go back to main environment), Suggest Another Plan (Next optimum), Deploy (Implement changes to main environment)
