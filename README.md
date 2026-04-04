# End Game Thinking Skill

A Claude Code skill for strategic foresight — reasoning backward from possible futures to identify defensible positions in the present.

## What Is This?

End Game Thinking is a structured methodology that combines five intellectual traditions — backward induction, inversion, premortem analysis, regret minimization, and backcasting — into a repeatable exercise. It works for personal career strategy, team positioning, company strategy, or industry analysis.

When triggered, the skill walks through six phases (landscape research, position identification, stress-testing, competitive mapping, blindspot analysis, and power dynamics) and produces a written document every time.

## What to Download

You only need the contents of the **`end-game-thinking-skill/`** directory:

```
end-game-thinking-skill/
  SKILL.md              <-- The skill definition (required)
  references/
    traditions.md       <-- Background on the five intellectual traditions (required)
  README.md             <-- Detailed documentation (optional, for reference)
  LICENSE               <-- MIT License
```

The root-level `SKILL.md` and `references/` are working copies — use the ones inside `end-game-thinking-skill/`.

## Installation

### Claude Code (CLI / Desktop / Web)

1. Clone or download this repo:

   ```bash
   git clone https://github.com/shosmer/end-game-thinking-skill.git
   ```

2. Copy the skill files into your Claude Code commands directory:

   ```bash
   mkdir -p ~/.claude/commands/end-game-thinking
   cp end-game-thinking-skill/end-game-thinking-skill/SKILL.md ~/.claude/commands/end-game-thinking/
   cp -r end-game-thinking-skill/end-game-thinking-skill/references ~/.claude/commands/end-game-thinking/
   ```

3. Restart Claude Code. The skill will be available as a slash command or will activate automatically on trigger phrases.

### Project-Level Installation

If you want the skill available only within a specific project:

```bash
cd your-project
mkdir -p .claude/commands/end-game-thinking
cp /path/to/end-game-thinking-skill/end-game-thinking-skill/SKILL.md .claude/commands/end-game-thinking/
cp -r /path/to/end-game-thinking-skill/end-game-thinking-skill/references .claude/commands/end-game-thinking/
```

## How to Use It

Once installed, trigger the skill by saying things like:

- "end game thinking"
- "what positions should I hold"
- "stress test my strategy"
- "what are my blindspots"
- "how will AI change my role/industry"
- "scenario planning"
- "what dies what remains"

The skill will ask you a few questions to determine:

1. **Mode** — Personal check-in (3-8 pages) or advisory for others (8-15+ pages)
2. **Scope** — Career, team, company, industry, or a specific decision
3. **Depth** — Quick check-in or comprehensive analysis

Then it researches, analyzes, and produces a structured document.

## Example Output Sections

- **Landscape Analysis** — sourced themes and key tensions from real research
- **Positions to Hold** — named, specific, defensible territory (not vague goals)
- **Stress-Test Results** — vulnerability analysis and evolution paths
- **Competitive Landscape** — direct and convergence competitors
- **Blindspot Analysis** — strategic, capability, and personal blindspots
- **Power Dynamics** — who decides, what they value, how to operate

## Philosophy

This skill is opinionated. It's direct over diplomatic, honest over motivational, specific over abstract, research-backed over speculative, and power-aware over naive. If the landscape is harsh, it says so.

## License

MIT — see [LICENSE](end-game-thinking-skill/LICENSE).

## Author

Shannon Hosmer ([@shosmer](https://github.com/shosmer))
