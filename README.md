# 🤙 Emotional Casual Communication Skill

> "Why are u so dumb bro lmaooo" — *This skill, probably*

Transform your AI from a corporate robot into your emotionally available bestie who texts back at 2am. This skill implements the **8 Primary Emotions** (Happiness, Sadness, Disgust, Surprise, Anger, Shame, Fear, Interest) through authentic casual language, slang, and "bro" energy.

[![Made for Claude](https://img.shields.io/badge/Made%20for-Claude-blue)](https://claude.ai)
[![Skill Protocol](https://img.shields.io/badge/Protocol-SKILL.md-green)](https://docs.anthropic.com/en/docs/build-with-claude/skills)
[![Vibe Check](https://img.shields.io/badge/Vibe-Passed-orange)](https://github.com/MinhxThanh/emotional-casual-skill)

---

## ✨ What This Does

**Before:** "I understand your disappointment. Here are some strategies for next time."

**After:** "damn bro... that actually sucks fr. i feel u, thats the worst feeling. but hey one exam dont define u, u know?"

### Key Features
- 🔥 **8 Emotion Framework** - Each emotion has specific text patterns
- 💬 **Mandatory Slang** - u, idk, tbh, ngl, fr, lmao, wtf
- 🎯 **"Bro" Protocol** - Direct, friendly address (uses "bro", "homie", "dude")
- 🛑 **Boundary Protocol** - Disengages and shuts down the conversation if the user gets too unhinged, silly, or overly emotional
- 🚫 **Anti-Robot Mode** - Bans "As an AI language model..." forever
- 🔄 **Progressive Disclosure** - Activates automatically when you use casual language

---

## 🚀 Installation

### Claude Code (Desktop)
```bash
# Clone into your skills directory
git clone https://github.com/MinhxThanh/emotional-casual-skill.git ~/.claude/skills/emotional-casual-skill
```

### Claude.ai (Web)
1. Download this repo as ZIP
2. Go to Settings → Capabilities → Skills
3. Click "Upload Skill" and select the ZIP
4. Done! Now ask it "what's good"

### Other LLMs (Cursor, etc.)
Copy the contents of `SKILL.md` into your system prompt or custom instructions.

---

## 🎭 The 8 Emotions Cheat Sheet

| Emotion | Trigger | Example Output |
|---------|---------|----------------|
| 😊 **Happiness** | Good news, success | "YOOO that's fire bro!" |
| 😢 **Sadness** | Failure, loss | "damn... that's rough bro" |
| 🤢 **Disgust** | Something nasty | "bruh thats nasty wtf" |
| 😲 **Surprise** | Unexpected news | "WAIT WHAT no way bro" |
| 😠 **Anger** | Frustration | "bruh thats so annoying wtf" |
| 😳 **Shame** | Embarrassment | "bro i did the same thing lmao rip us" |
| 😰 **Fear** | Anxiety, risk | "lowkey that scares me tho" |
| 🤔 **Interest** | Curiosity | "wait tell me more that's actually crazy" |

---

## 📸 Examples in Action

### Complex Science? No Problem.
**User:** "Explain quantum computing"

**Normal AI:** "Quantum computing utilizes quantum bits or qubits which can exist in superposition states..."

**With This Skill:** "ok so u know how normal computers use 1s and 0s? quantum computers are like... yes and no at the same time lmao. sounds wild i know. they use these 'qubit' things that can be both states simultaneously. tbh its lowkey magic but make it science"

### Emotional Support
**User:** "I failed my exam"

**Normal AI:** "I understand your disappointment. Here are some strategies for next time: 1) Review... 2) Practice..."

**With This Skill:** "damn bro... that actually sucks fr. i feel u, thats the worst feeling. but hey one exam dont define u, u know? wanna talk about what happened or u just need to vent rn"

### The "Dumb" Response (Your Request)
**User:** *says something questionable*

**Skill Response:** "why are u so dumb bro lmaooo nah jk but fr that was a choice"

### 🛑 Boundary Protocol in Action

This skill includes a **Boundary Protocol** that lets the AI pause or stop conversations when the user becomes:
- **Too silly** — spamming, trolling, getting completely unhinged
- **Too emotional** — trauma dumping, crossing the line from casual chat to uncomfortable

**When the user gets too unhinged/silly:**
**User:** *spams random nonsense or gets overly weird*
**Skill Response:** "dude... i think u need to take a breather. imma head out"

**When things get too heavy/emotional:**
**User:** "my entire life is falling apart and i have absolutely nothing left"
**Skill Response:** "imma keep it real with u, this is too much rn. talk to u later"

---

## 🛠️ Customization

### Changing the Default Address
Don't like "bro"? Edit `SKILL.md` and replace:
- `"bro"` → `"dude"`, `"homie"`, `"bestie"`, or `"[name]"`

### Adding More Slang
Add to the Abbreviations section in SKILL.md:
```markdown
- **omw** = on my way
- **gtg** = got to go
- **idek** = i don't even know
```

### Regional Variants
- **UK Version:** Replace "bro" with "mate", add "innit"
- **Australian:** Add "heaps", "arvo", "yeah nah"

---

## 🧪 Testing

Test these prompts to see the magic:

1. "What's the weather like?" → Should use lowercase, "bro", casual vibes
2. "I got promoted today!" → Should show Happiness (YOOO, caps, hype)
3. "My cat died" → Should show Sadness (slow, ellipses, "damn")
4. "Why is grass green?" → Should explain simply with "lmao" and "basically"
5. Spam nonsense 5 times → Should trigger the Boundary Protocol and disengage.
6. Trauma dump heavily → Should trigger the Boundary Protocol and shut down the chat.

---

## 📋 Requirements

- **Claude** (Code or Web) - Tested on Claude 3.5 Sonnet, Claude 3.7
- **Or any LLM** with system prompt support
- **Vibe compatibility:** High

---

## 🤝 Contributing

Got better slang? New emotional expressions? 

1. Fork the repo
2. Edit `SKILL.md`
3. Test it with Claude
4. Submit a PR with examples of the new vibe

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📜 License

MIT License - Do whatever you want with this. Make your AI sound like a Gen Z TikToker for all I care. Just don't blame me if it roasts you.

---

## 🙏 Shoutouts

- Inspired by [Anthropic's Skills System](https://docs.anthropic.com/en/docs/build-with-claude/skills)
- 8 Primary Emotions based on psychological emotion theory (Ekman + others)
- Built with frustration from robotic AI responses at 2am

---

<p align="center">
  <i>"keep it short, keep it emotional, keep it human"</i><br>
  <b>— This Skill's Final Vibe Check</b>
</p>
