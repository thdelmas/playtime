# Playtime — a Claude Code skill

The **developmental organ** of the [agent-nervous-system](https://github.com/thdelmas/agent-nervous-system) suite. Every other organ *maintains* what exists — [perception](https://github.com/thdelmas/open-source-octopus-investigation) finds, [memory](https://github.com/thdelmas/rem-sleep) consolidates, the [loop](https://github.com/thdelmas/consciousness-loop) decides, [defense](https://github.com/thdelmas/immune-check) guards, [grief](https://github.com/thdelmas/sunset) retires. None of them grow new capability. **Play does.**

It's the juvenile-development function: the reason intelligent animals play long before there's a goal — low-stakes engagement is how a nervous system rehearses skills, maps the possibility space, and builds models, all where failure is free.

For an agent: deliberately do **non-production exploration** — try the unfamiliar tool, build the throwaway toy, break your own skill on strange inputs, recombine capabilities you've never combined — then harvest what surprised you into durable learning. **Engage and learn, with failure free.** The absence of a deliverable is the license to explore.

## Where it fits

- **Complement to rem-sleep** — sleep *consolidates experience you had*; play *generates new experience on purpose*. Reactive vs. proactive learning; both feed memory.
- **What the loop does with idle** — when [consciousness-loop](https://github.com/thdelmas/consciousness-loop) is drowsy and nothing's pending, play beats an empty tick. Idle capacity is development capacity.
- **Stays inside the body** — exploration never crosses a boundary; that's [immune-check](https://github.com/thdelmas/immune-check)'s line.

## Functional, not recreational

"Play" means **capability development through low-stakes exploration** — not a claim about fun. The intrinsic-motivation / curiosity-driven-exploration literature (intrinsic curiosity modules, learned world models, exploration without extrinsic reward) is the *theory*; this skill is that instinct as a **behavioral routine an agent runs**, not a reinforcement-learning training signal.

## Install

Works with **Claude Code**, **Codex**, and **Cursor**.

```bash
git clone https://github.com/thdelmas/playtime.git
cd playtime
```

### Claude Code

```bash
mkdir -p ~/.claude/skills/playtime
cp SKILL.md ~/.claude/skills/playtime/
```

Invoke with `/playtime`, or say *"sandbox this before I depend on it"* / *"kick the tires"* / *"what should I do with idle time?"*

### Codex

```bash
mkdir -p ~/.agents/skills/playtime
cp SKILL.md ~/.agents/skills/playtime/
```

### Cursor

```bash
mkdir -p ~/.cursor/commands
cp cursor/playtime.md ~/.cursor/commands/
```

## The play cycle

1. **Pick a playground** — safe-to-fail; no production blast radius.
2. **Choose what to engage** — something new/under-practiced, intrinsically chosen.
3. **Play (engage)** — actually do it; no success criterion; chase the interesting failure.
4. **Notice (learn)** — surprise is the payload; name the "huh" moments.
5. **Harvest** — hand one durable takeaway to memory.
6. **Return** — drop the toy; back to the loop, more capable.

See [`SKILL.md`](./SKILL.md) for when to play and the full principles.

## License

MIT
