# Demystified!

A free, installable skill for Claude that appends a short observation after each response — naming the specific AI mechanics visible in what you just received.

Not a generic explainer. A notation, specific to this response, in this conversation.

The notes draw on [*Your Chats, Demystified!*](https://chatsdemystified.bigwaves.ca), a plain-language explainer by Big Waves covering how large language models are built, how they work, and why they fail the way they do, which they wrote to support teams' conversations and plans about how, or if, to work with these tools.

---

## What it does

After each response, Claude adds a section called **This chat, demystified.** It identifies which of the following mechanics are visibly at work in that specific response:

- Trained patterns from pretraining
- Post-training behaviour (tone calibration, hedging, pushback)
- Not knowing / not knowing it's not knowing
- Explainability limits
- Context window effects
- Attending to the prompt
- Whose knowledge and whose feedback

The section ends with: *This note is the chat tool interpreting itself: informed, but not a technical readout.*

---

## Installation

### Claude.ai Projects

1. Open or create a Project in Claude.ai
2. Go to **Project instructions**
3. Copy the contents of `system-prompt.txt` and paste it into the instructions field
4. The skill will apply to every conversation in that Project

### Claude Cowork

1. Open Cowork and navigate to your workspace settings
2. Find the system prompt or instructions field
3. Paste the contents of `system-prompt.txt`

### Claude Code (CLAUDE.md)

1. In your project directory, open or create a file called `CLAUDE.md`
2. Paste the contents of `system-prompt.txt` into that file
3. Claude Code will pick it up automatically at the start of each session

---

## Free to use and share

This skill is free. Use it, share it, tell Joanne what you think about it.

Built by [Big Waves](https://bigwaves.ca).
