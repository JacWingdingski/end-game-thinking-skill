# End Game Thinking

A Claude skill for strategic foresight — reasoning backward from possible futures to identify defensible positions in the present.

## What It Does

End Game Thinking is a structured methodology that combines five intellectual traditions into a repeatable exercise:

| Tradition | The Move |
|-----------|----------|
| **Backward Induction** | Reason from end states backward to determine optimal present action |
| **Inversion** | Ask "how could I guarantee failure?" to reveal what to avoid |
| **Premortem** | Assume the project has already failed — identify what went wrong |
| **Regret Minimization** | Project to your future self — what would you regret NOT doing? |
| **Backcasting** | Define the desired future, then work backward to map the path |

It works through six phases — landscape research, position identification, stress-testing, competitive mapping, blindspot analysis, and power dynamics — and produces a written document every time.

## Use Cases

- **Personal career strategy** — figure out which positions to build before the landscape shifts
- **Team positioning** — help your team claim defensible territory as AI reshapes work
- **Company strategy** — stress-test strategic bets against harder futures
- **Industry analysis** — map where an industry is headed and what survives

## Two Modes

**Personal Check-In:** A focused 3-8 page document for your own strategic thinking — career, skills, investments, life decisions.

**Advisory:** A comprehensive 8-15+ page document for presenting to others — suitable for sharing with teams, leadership, or clients.

## Installation

### As a Claude Code Skill

Copy the `SKILL.md` and `references/` directory into your Claude Code skills folder:

```bash
# Clone this repo
git clone https://github.com/shosmer/end-game-thinking-skill.git

# Copy into your Claude Code skills directory
cp -r end-game-thinking-skill/SKILL.md ~/.claude/skills/end-game-thinking/
cp -r end-game-thinking-skill/references ~/.claude/skills/end-game-thinking/
```

### As a Cowork Plugin Skill

Place the files in your Cowork skills directory following the [plugin structure](https://docs.claude.com).

## Triggers

The skill activates on phrases like:

- "end game thinking" / "endgame"
- "what positions should I hold"
- "how do I prepare for AI"
- "stress test my strategy"
- "what are my blindspots"
- "scenario planning"
- "what dies what remains"
- "how will AI change my role/industry"

## Example Output

The skill produces structured documents covering:

1. **Landscape Analysis** — sourced themes and key tensions from real research
2. **Positions to Hold** — named, specific, defensible territory (not vague goals)
3. **Stress-Test Results** — vulnerability analysis and evolution paths for each position
4. **Competitive Landscape** — direct and convergence competitors
5. **Blindspot Analysis** — strategic, capability, and personal blindspots
6. **Power Dynamics** — who decides, what they value, and how to operate within reality

## Philosophy

This skill is opinionated:

- **Direct over diplomatic.** It names things plainly.
- **Honest over motivational.** If the landscape is harsh, it says so.
- **Specific over abstract.** Every position and recommendation is concrete enough to act on.
- **Research-backed over speculative.** It cites real sources, not vibes.
- **Power-aware.** It doesn't pretend the world is a meritocracy.

## References

The `references/traditions.md` file contains detailed background on each intellectual tradition — origins, key practitioners, how they work, and how they integrate in the methodology.

## License

MIT License — see [LICENSE](LICENSE).

## Author

Shannon Hosmer ([@shosmer](https://github.com/shosmer))
