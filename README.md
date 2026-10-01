# Agentic-AI-Expense-Auditor
An agentic AI system for expense auditing that enforces policy deterministically and pauses for human approval on anything outside hard rules. Built on LangGraph with durable checkpointing, audits survive a restart and resume days later. The agent's only AI task is drafting a reviewer summary, it never makes the approval call itself.
