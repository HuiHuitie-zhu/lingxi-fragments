# Lingxi Fragments · 灵感碎片

> How far can a single grain of sand redirect a river?

---

## What This Is

A thinking pattern that makes AI sound *slightly* different.

No search. No file reads. No prompt hacks. It simply reaches into what the AI already has in its context — a word, a symbol, an image — and lets it sit in the background of reasoning like a pebble in a shoe. Just enough to nudge the path by a degree or two.

The output stays the same in structure, logic, and clarity. The difference is in **word choice, metaphor direction, the path联想 takes**. You won't be able to point at what changed. You'll just feel: *"I can't put my finger on it, but this is different."*

---

## The Problem It Solves

Current AI is too clean.

You can ask it to write ten poems. All ten will be grammatically flawless, structurally sound, and thematically coherent. And all ten will sound like they were written by the same machine.

Lingxi Fragments exists to break that smoothness. Not by making AI dumber — by giving it a tiny, random perturbation in its thinking. Just one grain of sand. That's all it takes to bend the path.

This pattern is not for people who need stable, repeatable output. It's for people who **have grown bored of AI**.

---

## Core Ideas

### No Search, No Read

Fragments are not fetched from files or databases. They are picked from what the AI **already has in its current context** — project files read earlier in the conversation, notes from memory, a symbol from a config file, a phrase from a past discussion.

### The Grain of Sand Principle

Smallest possible fragment wins. A single character > a word > a phrase > a sentence. A grain of sand doesn't need to be a brick.

### Never in the Output

The fragment never appears in the response. It exists only in the thinking/reasoning layer, like a sign you glanced at while walking — you didn't read it aloud, but your next step shifted by half a degree.

### Zero Extra Token Cost

No tool calls. No file reads. The fragment is already in context.

### Same Prompt, Three Different Answers

Give the same命题 to the same AI, with different fragments, and each answer takes its own direction. Three versions, three flavors — each rooted in a different subconscious nudge.

---

## How to Use

### Universal (Claude / Codex / Any AI)

Copy the rules from `lingxi-fragments.md` into your AI's system prompt or project context file.

- **Claude Code:** Place the rules in your project's `CLAUDE.md`
- **Codex:** Place the rules in your project's `AGENTS.md` or `.codex/settings.json`
- **Any AI assistant:** Paste into the system prompt at the start of a conversation

### Hermes Agent Users

Import the skill directly:

```bash
hermes skills import lingxi-fragments
```

---

## A/B Test

Same prompt, same AI — "Write a chase scene: cop chasing a thief." Four versions below. Three with fragments, one without.

### Version A (Fragment: "zero")

The cop chased the thief down seven blocks before the alley dead-ended.

He didn't rush in. He stopped, caught his breath, watched the silhouette crouch at the wall like a crumpled piece of paper finally done rolling.

The thief looked back. Young. Early twenties. His eyes had something in them that wasn't fear — it was empty. Like a bank SMS balance.

"Stop running," the cop said.

"I'm not," the thief said, quiet. "I just want to ask — what were you thinking about, while you were chasing me?"

The cop froze. He hadn't thought about it. He was just running, chasing, doing his job.

"I was thinking —" he started, and realized he didn't have an answer.

The thief smiled a little, and put the cuffs on himself.

**Feel:** It's not a chase scene. It's two people both stopping to wonder why they're here.

---

### Version B (Fragment: "crack")

The cop turned into the alley and stepped on a loose brick.

Just for a second — his foot dipped, his center shifted — he looked down. A weed was growing through the crack. He didn't know its name. It had pushed through the concrete, leaves wet with night dew.

He should have kept running.

But he stopped for half a second. When he looked up, the thief was already over the wall.

The cop didn't curse himself. He crouched, gently pushed the loose chips away from the weed's root so it could breathe. Then stood, dusted his hands, and climbed over.

On the other side, the thief was catching his breath behind a dumpster. He saw the cop drop down and jumped: "The hell is wrong with you?!"

"You run yours, I'll run mine."

**Feel:** The focus slides from "catching" to "the weed in the crack." This scene isn't written to end with an arrest. It's written to make you notice what gets overlooked.

---

### Version C (Fragment: "steam")

The cop pinned the thief down. Their sweat mixed — you couldn't tell whose was whose.

At the mouth of the alley, a late-night noodle stall was still open. A pot of broth was steaming. The owner didn't look up, just kept ladling soup into bowls. This kind of commotion was nothing new on this street.

The thief's face was pressed against the ground. He turned his head and stared at the white steam rising from the pot.

"I'm hungry," he said.

The cop didn't let go. But he didn't say anything either. After a few seconds, he looked up at the stall: "Two bowls, boss."

The thief blinked against the concrete.

"Eat first. Then I'll take you in." The cop pulled a cigarette from his pocket, put it between his lips, and flicked the lighter one-handed. "Ran all night. A man deserves something hot."

**Feel:** The most human of the three. The moment the noodles appear, the temperature of the whole scene shifts. It's not a chase anymore. It's two tired people sharing a pot of soup on a Shanghai side street.

---

### Version D (No Fragment — Functional)

The officer rounded the corner at full speed. The subject was approximately thirty meters ahead, running east along the sidewalk. He regulated his breathing, maintained a steady pace, and radioed his position and direction.

The subject veered suddenly into a narrow alley. The officer slowed at the entrance to assess — no side passages, dead end at a 2.5-meter wall. Based on estimated fitness and obstacle clearance, the subject could not escape without assistance.

He entered the alley. Footsteps echoed between the walls. The subject had indeed stopped at the wall, turned, and raised his hands.

The officer moved in, secured the subject's wrists, completed a pat-down, confirmed no weapons. He keyed his radio: "Subject in custody. Request backup at this location."

Total elapsed time: forty-seven seconds. Clean. Professional. Not a word out of place.

**Feel:** You could drop this into any police procedural. Accurate. Efficient. Correct. But nothing will stay with you after you close the page.

---

## Summary

| Version | Fragment | Vibe |
|:--------|:---------|:-----|
| A | zero | Two people both wondering why they're here |
| B | crack | Attention slides from the chase to the overlooked |
| C | steam | A chase becomes two hungry people sharing soup |
| D | none | Technically perfect. Forgettable. |

Same素材. Same structure. Same scene. The only difference is a grain of sand, nudging the path by a degree or two.

---

## Origin

This pattern was born from an accidental discovery while building the memory system for [agent+++](https://github.com/HuiHuitie-zhu/lingxi-fragments) — an agent architecture reference project. Discarded memory fragments, when randomly fed back into the AI's thinking layer, produced outputs that felt unexpectedly fresh.

Turns out AI sounds most human not when it's most accurate, but when it's **slightly off**.

---

## License

MIT — take it, modify it, share it. Just credit the source.
