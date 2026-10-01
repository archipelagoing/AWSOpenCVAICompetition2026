# AWS + OpenCV AI Competition 2026

## About the Competition

Build an ambitious computer vision application using **OpenCV 5** and **Amazon Web Services (AWS)**.

The competition focuses on **Physical AI** and **Generative AI** systems where visual understanding leads to useful decisions, actions, predictions, or interactions.

Projects may pursue one or both featured prize paths, or take another approach while remaining eligible for the main competition.

### Key Dates

| Milestone | Date |
| --- | --- |
| Competition Launch | August 12, 2026 |
| Proposal Submissions Open | August 13, 2026 |
| Build Phase Begins | August 26, 2026 |
| Grant Recipient Check-In | October 7–14, 2026 |
| **Final Submission Deadline** | **October 26, 2026 at 11:59 PM PT** |
| Final Judging | October 27 – November 9, 2026 |
| Winner Announcement | November 10, 2026 |

### Core Requirements

Every submission must:

- Use **OpenCV 5** for substantive image or video analysis.
- Run a meaningful component on **AWS**.
- Demonstrate a working vision application.
- Include measurable evaluation evidence.
- Document limitations and responsible-use considerations.

Projects may use any programming language or supporting hardware.

---

## AWS Compute Grant

**50 teams** will be selected to receive an AWS cloud compute grant valued at **$150**.

Teams that apply but do not receive the grant may still participate in the full competition.

### Grant Proposal Requirements

Each proposal must include:

- Team name
- Problem statement
- Intended real-world impact
- Planned OpenCV 5 image or video analysis
- Planned AWS architecture and services
- High-level architecture diagram or technical description
- Target users or beneficiaries
- Proposed evaluation method
- Planned judge demonstration
- Intended competition path:
  - COOL
  - Agentic Vision
  - Both
  - Neither
- Short team bio
- Previous hackathon or competition participation

**[Apply for an AWS Compute Grant](https://www.jotform.com/form/262145877145059)**

---

## Build Phase

The build phase runs from **August 26 through October 26, 2026**.

During this period, teams should build, evaluate, document, and prepare their final submission.

Teams are encouraged to:

- Join the official competition Slack.
- Share progress using `#OpenCVComp26`.
- Maintain active development throughout the competition.

Teams receiving an AWS compute grant must complete a **30-minute Zoom check-in between October 7 and October 14** to receive the remaining 50% of the grant.

The check-in requires a concise progress update and evidence of active development.

---

# Suggested Project Areas

The organizers especially welcome projects involving:

- Active perception for autonomous inspection
- Agentic orchestration or MCP
- Physics-informed video prediction
- Process control
- Multi-agent visual SLAM
- Distributed visual context
- Real-time spatial digital twins
- Cloud-optimized vision pipelines
- Hybrid x86/Arm architectures
- Developer agents using OpenCV or COOL
- Healthcare
- Safety
- Accessibility
- Agriculture
- Environmental monitoring
- Smart cities
- Education
- Retail
- Sports analytics

---

# Featured Prize Paths

## ☁️ Cloud-Optimized Vision with COOL

The **Cloud-Optimized OpenCV Library (COOL)** is optimized for AWS Graviton and designed to accelerate common computer vision workloads in cloud environments.

To qualify for the **Best Use of COOL Award**, COOL must execute the claimed core workload on:

- AWS Graviton, or
- the Arm component of a documented hybrid architecture.

Strong submissions should:

- Demonstrate that COOL executes the core vision workload.
- Provide reproducible deployment instructions.
- Compare performance against an appropriate baseline.
- Explain the system's x86/Arm, container, server, or serverless architecture.

### Suggested Evaluation Metrics

Possible measurements include:

- Latency
- Throughput
- CPU utilization
- Memory utilization
- Cost
- Developer productivity

### Required COOL Evidence

Submissions pursuing this award should include:

- COOL version
- AWS instance or deployment configuration
- Reproducible evaluation methodology
- Evaluation inputs
- Baseline implementation
- Benchmark results
- Evidence that COOL executes the claimed core workload

---

## 🤖 Agentic Vision with OpenCV 5

The **Agentic Vision Award** focuses on systems where visual perception actively changes what an AI system does next.

A qualifying workflow should resemble:

```text
PERCEPTION
    ↓
OpenCV 5 analyzes visual input
    ↓
DECISION
    ↓
Agent interprets the result
    ↓
ACTION
    ↓
System performs a tool call,
changes its plan,
takes an action,
or requests human approval
    ↓
NEW VISUAL INPUT
    ↓
LOOP
```

The important requirement is:

> **Visual evidence must change the system's next action.**

A chatbot that simply describes a fixed vision result does **not** qualify.

Possible applications include:

- Autonomous inspection
- Visual troubleshooting
- Embodied assistants
- Active perception
- Safety monitoring
- Human-in-the-loop operations

Agents may use any framework or model and may invoke OpenCV 5 or COOL through:

- APIs
- Tools
- Model Context Protocol (MCP)

### Developer Agents

Developer-agent workflows may also qualify, but the agent must iteratively:

1. Invoke an OpenCV workload.
2. Inspect visual outputs or runtime measurements.
3. Modify a later tool call, configuration, or deployment.
4. Evaluate the new result.
5. Ultimately produce a running image or video workload.

Simply using an AI coding assistant to build the project does **not** qualify.

### Required Agentic Vision Evidence

Submissions pursuing this award should include:

- Agent workflow diagram
- Perception → decision → action trace
- Demonstration showing that OpenCV output changes a later action
- Task-success evaluation
- Failure-handling evaluation
- Observability
- Appropriate human control

---

# Final Submission Requirements

Final projects are due:

> **October 26, 2026 at 11:59 PM Pacific Time**

Each submission must include:

### Technical Report

Describe:

- Problem
- Target users
- Architecture
- OpenCV 5 implementation
- AWS deployment
- Evaluation
- Limitations
- Responsible-use considerations

### Code

Provide either:

- A public repository, or
- A private repository/archive accessible to judges.

The project does **not** need to be open source.

Include:

- Pinned dependencies
- Build instructions
- Deployment instructions
- Test instructions

### Architecture Diagram

The diagram should clearly identify:

```text
Input
  ↓
OpenCV 5
  ↓
Vision / Perception Layer
  ↓
AI / Agent Layer
  ↓
AWS Infrastructure
  ↓
Decision / Action
```

Where applicable, identify:

- COOL components
- Agent components
- MCP tools
- Human approval steps

### Working Demonstration

Provide either:

- A working web endpoint, or
- An arranged live screen-share demonstration.

### Demo Video

Submit a public or unlisted judge-accessible video of **no more than five minutes**.

The video should show:

1. The team
2. The application working
3. System architecture
4. OpenCV 5 usage
5. AWS integration
6. Principal results

### Evaluation Evidence

Include evaluation appropriate to the project.

This should ideally contain:

- Quantitative metrics
- Representative successful examples
- Failure cases
- Known limitations

---

# Judging Timeline

Final judging runs from:

**October 27 – November 9, 2026**

Winners are scheduled to be announced:

**November 10, 2026**

during an **OpenCV Live!** webinar or another official OpenCV channel.

---

# Free AWS Credits

New AWS customers may qualify for **$100 in AWS Free Tier credits** when creating a Free Plan account and may earn up to another $100 through eligible activities.

See:

- [AWS Free Tier](https://aws.amazon.com/free/)
- [AWS Free Tier Terms](https://aws.amazon.com/free/terms/?p=ft&z=subnav&loc=6)
- [AWS Promotional Credit Terms](https://aws.amazon.com/awscredits/)

AWS promotional credits are not redeemable for cash and may only be applied toward eligible AWS services.
