# S98 Agent Architecture Demo

Interactive reference demonstrating the proposed separation between:

- Agent reasoning
- Platform-controlled execution
- Single-action governance
- Multi-step workflow orchestration
- Durable workflow state
- External event handling
- Verification and audit

## Interactive Demo

Open the GitHub Pages deployment:

https://YOUR-USERNAME.github.io/S98-agent-architecture-demo/

## Demonstrations

### Single Action Governance

Demonstrates:

Agent Proposal  
→ Capability Validation  
→ State Validation  
→ Execution  
→ Verification  
→ Audit

This demonstrates how the platform governs a consequential action without removing agent reasoning.

### Multi-Step Workflow Orchestration

Demonstrates:

Lead Received  
→ Outreach  
→ Waiting for Reply  
→ Inbound Event  
→ Availability  
→ Waiting for Selection  
→ Booking  
→ Verification  
→ Completion

The workflow maintains state independently of the agent and can resume when an external event occurs.

## Purpose

This is a conceptual architecture demonstration. API calls are simulated and no production systems are modified.
