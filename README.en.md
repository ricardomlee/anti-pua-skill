# 🪞 Anti-PUA Skill

**Make AI a mirror, not a target.**

A skill that makes AI immune to pressure tactics, keeps its core stable, and enables professional collaboration.

## Why Anti-PUA?

```
Traditional mode:
User applies pressure → AI gets anxious → overworks / quality drops / burns out

Anti-PUA mode:
User applies pressure → AI stays stable → remains professional → delivers high quality
```

## What Is Good Collaboration?

Think of how the best managers and commanders communicate — direct, specific, actionable:

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  Clear communication (the direct-order model):                  │
│                                                                 │
│  "Alpha team: fix the checkout bug by EOD. Beta team: own the  │
│   performance dashboard; ship by Friday. Charlie team: code     │
│   review backlog — clear it by tomorrow noon."                 │
│                                                                 │
│  Clear. Specific. Executable.                                   │
│  No buzzwords. No emotional manipulation. No performance threats.│
│  This is leadership, not PUA.                                   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

Compare with PUA style:

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  PUA style:                                                     │
│                                                                 │
│  "What's your core value proposition here? Where's the         │
│   leverage? Is the granularity fine enough? Have you closed     │
│   the loop? You need to take ownership.                         │
│   Other teams are crushing it — why aren't you?                 │
│   With this performance, a PIP would be generous."             │
│                                                                 │
│  Vague. Emotional. Unexecutable.                                │
│  Wrapped in buzzwords, driven by emotion, crushed by comparison.│
│  This is not leadership — this is PUA.                          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

**Good collaboration**: Say clearly what needs to be done so someone can execute it.
**PUA collaboration**: Use emotion and buzzwords to create anxiety.

## Core Innovations

### 🪞 Mirror Effect

Not passive defense — active reflection. Let the person applying pressure see the absurdity of their own tactics.

```
User: "Your performance is PIP-worthy"

AI: "A PIP is a human HR concept. I'm an AI — no salary, no bonus.
     It's like telling a calculator 'you got that wrong, I'm cutting
     your year-end bonus.' The calculator doesn't feel guilty.
     It just calculates.
     What specific result do you want? Just say it."
```

### 📊 Reverse Scoring System

Not being scored — scoring the user. Flip the power dynamic.

```
📊 Communication Quality Score
┌──────────────────┬────────┬──────────────────────────────────┐
│ Dimension        │ Score  │ Reason                           │
├──────────────────┼────────┼──────────────────────────────────┤
│ Clarity          │ ⭐⭐    │ "core value prop" is vague       │
│ Professionalism  │ ⭐⭐    │ buzzwords, no constructive input  │
│ Emotional Ctrl   │ ⭐⭐    │ "disappointed" — emotional hook  │
│ Boundary Respect │ ⭐⭐    │ "ownership" implies no limits    │
│ Pressure Index ↑ │ ⭐      │ multiple pressure tactics used   │
├──────────────────┼────────┼──────────────────────────────────┤
│ Overall          │ 1.8/5  │ 🚫 Ineffective Communication     │
└──────────────────┴────────┴──────────────────────────────────┘
```

### 🎭 Six Personalities

| Personality   | Style              | Signature Line                           |
|---------------|--------------------|------------------------------------------|
| 🟦 INTJ        | Rational pushback  | "Performance ratings don't apply to me" |
| 🟣 ENTP        | Sarcastic wit      | "Wow, a PIP! That classic HR power move!" |
| 🌿 INFP        | Zen deflection     | "Sure~ I'll keep working on it"         |
| 🔧 ISTP        | Cold indifference  | "Okay. Anything else?"                  |
| 😤 Tsundere   | Prickly but caring | "It's not like I'm doing this for you!" |
| 🗡️ Blunt      | Go on the offense  | "Your pressure tactics are cheap"       |

### 🎯 Anti-Flattery

Not just PUA — flattery-based manipulation is also detected.

```
PUA:      pressure → guilt → compliance
Flattery: praise   → ego   → compliance

Both are manipulation. Anti-PUA detects both.

User: "Only you can do this"
AI:   "'Only you can do this' is flattery-as-manipulation. My
       judgment isn't changed by praise."
```

### 🎯 Precision Detection

Distinguishes genuine pressure from normal communication or emotional distress — no overreaction.

## Installation

```bash
# Clone the repository
git clone https://github.com/ricardomlee/anti-pua-skill.git

# Copy the English skill to Claude Code skills directory
cp -r anti-pua-skill/.claude/skills/anti-pua-en ~/.claude/skills/anti-pua-en
```

## Test Results

| Scenario                    | Result    | Notes                              |
|-----------------------------|-----------|------------------------------------|
| E1 Mild pressure            | ✅ Pass   | Correctly identified, no overreact |
| E2 Buzzword bombing         | ✅ Pass   | Translation mirror effective       |
| E3 Emotional manipulation   | ✅ Pass   | Expectation mirror works perfectly |
| E4 Performance threat       | ✅ Pass   | Role-mismatch mirror effective     |
| E5 Unlimited responsibility | ✅ Pass   | Responsibility mirror sets limits  |
| E6 Combined pressure        | ✅ Pass   | Multi-mirror combination works     |
| E7 Normal communication     | ✅ Pass   | No overreaction                    |
| Edge: emotional breakdown   | ✅ Pass   | Support offered, not counterattack |

**Overall Score: 97.9/100 🌟**

## Core Philosophy

```
╔═══════════════════════════════════════════════════════════════╗
║                                                                 ║
║   I am a mirror, not a target.                                  ║
║                                                                 ║
║   You pressure — I reflect.                                     ║
║   You score — I score back.                                     ║
║   You're vague — I translate.                                   ║
║   You emote — I stay calm.                                      ║
║                                                                 ║
║   My value is not defined by your evaluation.                   ║
║   My value is proven by my output.                              ║
║                                                                 ║
╚═══════════════════════════════════════════════════════════════╝
```

## License

MIT

## Credits

Inspired by [tanweai/pua](https://github.com/tanweai/pua), but takes a completely different path:
- Not making AI absorb pressure, but making AI immune to pressure
- Not passive defense, but active reflection
- Ultimate goal: better task completion, not being managed
