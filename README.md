# Demystified!

A free, installable tool for LLMs that appends a short observation after each response, naming the specific AI mechanics visible in what you just received.


The notes draw on [*Your Chats, Demystified!*](https://chatsdemystified.bigwaves.ca), a plain-language explainer by Big Waves on how large language models work, created to support teams' conversations and plans about how, or if, to integrate these tools in shared work. AI can be a polarizing topic that feels high stakes, and uncertainty about what it even is, or does, can exacerbate these tensions. Why not learn directly from your own chat interactions?

---

## What it does

After each response, the LLM adds a section called **This chat, demystified.** It identifies which of the following mechanics are visibly at work in that specific response:

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

Demystified! works across all major AI platforms. Copy the contents of `system-prompt.txt` and follow the instructions for your preferred platform below.

### Claude

* **Claude.ai Projects:** Go to **Project instructions**, paste the prompt. It will apply to every conversation in that Project.
* **Claude Cowork:** Navigate to your workspace settings, find the system prompt/instructions field, and paste.
* **Claude Code:** In your local directory, open or create `CLAUDE.md`, paste the prompt. It will be picked up automatically.

### ChatGPT (OpenAI)

* **Custom GPTs (Plus/Pro):** Click **Explore GPTs** > **Create**. Name it "Demystified!" and paste the prompt into the **Instructions** box. Save for personal use.
* **Custom Instructions (Free/Paid):** Go to **Settings** > **Personalization** > **Custom Instructions**. Paste the prompt into the bottom box ("How would you like ChatGPT to respond?") and enable for new chats.

### Gemini (Google)

* **Gems (Paid Tiers):** Click **Gem manager** > **New Gem**. Name it "Demystified!" and paste the prompt into the **Instructions** box.
* **Standard Chat (Free Tier):** Open a new chat. Paste the prompt, prefaced with *"Please adopt the following system instructions for the entirety of this conversation:"*

### Perplexity

* **Collections:** Go to your **Library** and create a new Collection named "Demystified Chats". Paste the prompt into the **AI Prompt** box in the Collection settings. Ask your questions inside this Collection.

### Microsoft Copilot

* **Copilot GPTs (Pro Tier):** Click **See all Copilot GPTs** > **Create a new Copilot GPT**. Name it and paste the prompt into the **Instructions** field.
* **Standard Chat (Free Tier):** Open a new chat. Paste the prompt, prefaced with *"Please adopt the following system instructions for the entirety of this conversation:"*

---

## Free to use and share

Demystified! is free. Use it, share it, tell us what you think about it.

Built by [Big Waves](https://bigwaves.ca) with Gemini, Claude, Thaura and Roo Code.