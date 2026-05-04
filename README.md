# Demystified!

A free, installable tool for AI chat platforms that adds a short observation after each response, naming the specific AI mechanics visible in what you just received.


The notes draw on [*Your Chats, Demystified!*](https://chatsdemystified.bigwaves.ca), a plain-language explainer by Big Waves on how these tools work, created to support teams' conversations and plans about how, or if, to integrate these tools in their shared work. AI can be a polarizing topic that feels high stakes, and uncertainty about what it is, or does, can exacerbate these tensions. Why not learn directly from your own chat interactions?

---

## What it does

After each response, the chat tool adds a section called **This chat, demystified.** It identifies which of the following mechanics are visibly at work in that specific response:

- Trained patterns from pretraining
- Post-training behaviour (tone calibration, hedging, pushback)
- Not knowing / not knowing it's not knowing
- Explainability limits
- Context window effects
- Attending to the prompt
- Whose knowledge and whose feedback

The section ends with: *This note is the chat tool interpreting itself: informed, but not a technical readout.*

---

## What's in this repo

- `system-prompt.txt` - the system prompt, ready to paste
- `SKILL.md` - the same content formatted for upload via Claude Cowork's skill interface

---

## Installation

Installation looks a little different depending on which platform you're using, and even within a platform, it can vary by plan or subscription tier. On top of that, these tools are changing fast enough that any instructions we write today may be out of date by the time you read them :) With that caveat, here are the best instructions we could offer at the time of writing.

---

### Claude (claude.ai)  Project instructions

1. Open [claude.ai](https://claude.ai) and navigate to the Project you want to use this in (or create a new one).
2. On the main project page, find the instructions field and paste the contents of `system-prompt.txt`.

The skill will apply to every conversation within that project.

---

### Claude  Cowork (skill upload)

1. In Claude Cowork, open **Customize → Skills → Create skill → Upload a skill**.
2. Upload `SKILL.md` directly.

Once installed, the skill isn't on by default: type `/` in any conversation to see your available skills and activate Demystified! for that session. This is by design: in a task-focused tool like Cowork, you'll want to switch it on when it's useful rather than have it always on.

---

### ChatGPT Project instructions

1. Create a new Project or open an existing one.
2. Select **Project settings** (top right).
3. Paste the contents of `system-prompt.txt` into the instructions field and save.

The skill will apply to every conversation within that project. Note: ChatGPT also has a Custom Instructions option that applies across all chats, but its 1,500-character limit makes it too short for this prompt.

---

### Google Gemini  Gem

Gemini's always-on instructions field (found under Personal Intelligence in Settings) has a character limit that makes it too short for this prompt. However Gemini custom instances, called Gems, are compatible with this custom instruction.

1. Go to [gemini.google.com](https://gemini.google.com) and open the sidebar menu.
2. Select **Gems → My Gems → New Gem**.
3. Paste the contents of `system-prompt.txt` into the instructions field.
4. Name the Gem and save.

To use it, open this Gem from the sidebar rather than starting a regular chat. The instructions will apply to any chat begun within that Gem.

---

### Perplexity

Persistent custom instructions in Perplexity live inside **Spaces**.

1. Create or open a Space.
2. Add the contents of `system-prompt.txt` as the Space's custom instructions.
3. Use that Space for conversations where you want the skill active.

---

### Microsoft Copilot (M365)

Custom instructions in Microsoft Copilot require a Microsoft 365 Copilot license. The free consumer version at copilot.microsoft.com doesn't currently support persistent custom instructions for individual users.

If you have an M365 Copilot license:

1. Go to Copilot Chat and sign in with your work or school account.
2. Select the **...** menu (top right) → **Personalization**.
3. Find the **Custom instructions** tile and select **Edit instructions**.
4. Paste the contents of `system-prompt.txt` and save.

---

## Free to use and share

Demystified! is free. Use it, share it, tell us what you think about it.

Built by [Big Waves](https://bigwaves.ca) with Gemini, Claude, Thaura and Roo Code.