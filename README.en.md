# Life Compass

English | [中文](README.md)

**See the distance between the life you are living and the life you want.**

Life Compass is a bilingual English and Chinese skill for life exploration and reflection. Starting with the future you do not want, it helps you explore what matters, the person you want to become, and the direction you want to move toward. Action and recurring reviews help you keep learning from real experience.

## Does any of this feel familiar?

- You know something needs to change, but keep telling yourself you will start when life is less busy.
- You set goals, yet day-to-day demands keep pushing important things aside.
- You get things done but feel increasingly unsure whether this is the life you want.
- You try to understand why you are stuck, but reflection turns into self-criticism or another plan you cannot sustain.

Life Compass brings your dissatisfaction, imagined futures, and actual experiences into the same conversation, so you can decide what matters and test your next step.

## What can it help you do?

**Clarify direction.** Begin with an anti-vision—the life you do not want—and explore the values, needs, and vision behind it. The initial questions are direct and challenging: they invite you to consider where an unchanged pattern might lead in two, five, or ten years, and how you might look back at the end of your life.

**See the gap between intentions and actions.** Reviews compare what you said you wanted to do, what actually happened, and the circumstances around it. When a gap repeats, Life Compass points it out and helps you explore why.

**Build self-trust through action.** Turn a direction into a small experiment you choose. Notice what helps, what gets in the way, and what to change. Reviews begin with evidenced progress before addressing gaps.

**Keep your thinking connected.** Save reflections and diagram snapshots locally. Obsidian-compatible note links can connect your vision, experiences, actions, and recurring themes over time. A link is an association to examine, not proof of causation.

## How to get more out of it

### 1. Start with an honest exploration

In a compatible client, try:

~~~text
$life-compass Help me begin my first life exploration.
~~~

Start with the dissatisfaction that matters most to you. The questions can be sharp; take your time, skip one, or pause. Use specific experiences rather than trying to produce a perfect answer. The AI guides and organizes; you decide what is true and important for you.

You can use English or Chinese and switch during a conversation. Both languages continue the same journal and graph; earlier entries and your original words are preserved.

### 2. Turn your vision into an experiment

Choose a direction that matters now. With Life Compass, decide what you are willing to try, when, what might get in the way, and what you want to observe. The action can be small; it should connect to the life you want to move toward.

### 3. Come back and compare intentions with reality

For example, return every two days:

~~~text
$life-compass Help me review: What actually happened with what I planned last time?
~~~

Share what you did, what did not happen, and what occurred outside the plan. Life Compass first identifies supported progress, then addresses gaps. If you keep getting stuck, it considers the goal, task, energy, time, environment, and possible concerns rather than declaring a cause.

### 4. Use the journal and graph to see change over time

Journal entries and diagram snapshots default to `~/Desktop/Life coach/Journal/`; you can choose another location. Open the folder in Obsidian to follow links among related notes. When useful, the skill can create a canvas to explore specific relationships.

Revisit recurring patterns and what is helping. Correct the skill's interpretation whenever needed, and update your vision or goals as you gain experience.

## Installation

Copy the repository's `life-compass` folder to your client's personal skill directory. For Codex, one option is `~/.codex/skills/life-compass/`; then refresh the skill list or open a new chat. Alternatively, ask an AI with local file access to read `life-compass/SKILL.md` and its `references/` directory.

The client needs permission to read and write the relevant local folders. Skill discovery, in-chat diagrams, and Obsidian canvas support vary by client; a path existing does not itself mean the skill is installed or has permissions.

## How to interpret feedback

Life Compass distinguishes **user reports, existing records, inferences, hypotheses to test, recommendations, and unknowns** at key points. “Three records show no action” and “you may fear failure” are different kinds of statements; the latter needs your judgment and further evidence.

It knows only what you share or authorize it to read. It does not make life decisions for you or provide psychological diagnosis or treatment.

## Privacy and reminders

Journal and diagram files are normally stored locally as plaintext. Device backups and existing cloud sync may affect where they are stored; they are not part of the skill and should not be uploaded to the repository. How AI conversations are processed depends on the service used.

Scheduled reminders require a separately configured scheduler and email tool. Installing the skill does not create reminders or guarantee delivery.

## Inspiration and how Life Compass builds on it

The anti-vision exploration draws on Dan Koe's [How to fix your entire life in 1 day](https://letters.thedankoe.com/p/how-to-fix-your-entire-life-in-1), which invites readers to consider an unwanted future, explore a desired future, and choose actions. The initial core questions use the original wording supplied for this project; the two-year scenario is a separate addition.

Life Compass extends that starting point into an ongoing practice:

- **Recurring reflection:** connect your vision, anti-vision, actions, and experiences over time, and update your goals as you learn.
- **Guided conversation:** explore values, real-world constraints, and possible conflicts through questions while retaining control of your decisions.
- **Experiments and adjustment:** recognize supported progress, address recurring gaps directly, and choose a feasible next step.
- **Evidence-aware feedback:** distinguish reports and records from inferences, hypotheses, and unknowns.
- **A local trail:** use a journal, diagram snapshots, and Obsidian-compatible links to revisit and connect your reflections.

These are extensions of the article's practice, not claims that this project invented the underlying ideas of vision or behavior change.
