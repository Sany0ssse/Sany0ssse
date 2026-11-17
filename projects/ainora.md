[← Oleksandr's profile](../README.md)

# AInora
**Personal AI assistant** · Node.js · TypeScript · OpenAI APIs

*Private source · Local use · In development*

### The idea

Build a personal Windows assistant that does more than answer questions: it should work with useful context, invoke tools safely, remember the state of scheduled tasks, and make its actions inspectable.

### Engineering decisions

- Integrate OpenAI Responses and Realtime APIs for conversations, tool use, and voice-oriented interaction.
- Constrain tool calls with schemas and permission checks instead of exposing unrestricted execution.
- Track scheduled tasks with persisted state, execution history, and explicit pause/delete behavior.
- Validate tool results, failures, and permission boundaries in local regression checks.

### My involvement

Product conception, workflows and interface design, agent-assisted implementation, reproduction of failures, and verification of behavior. I use coding agents in development but review and test their outputs.

### What this demonstrates

**Agent integration is a software-engineering problem.** It needs clear contracts, observability, state handling, and reliable boundaries—not just a prompt.

*The project is for personal local use. I do not present it as a public product or production service.*
