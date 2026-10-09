# Claude Skills: Documentary & Motion Design

A set of [Claude](https://claude.ai) Agent Skills for planning, designing and animating
presenter-led explainer documentaries in the Vox / Aevy TV tradition.

| Skill | What it does |
|---|---|
| [`explainer-documentary`](skills/explainer-documentary/SKILL.md) | Format, cold opens, story structure, writing voice and a scene-by-scene plan |
| [`vox-collage-design`](skills/vox-collage-design/SKILL.md) | Design system: paper textures, cutouts, colour, typography, hand-drawn marks, scene layouts |
| [`vox-after-effects-recipes`](skills/vox-after-effects-recipes/SKILL.md) | Exact After Effects settings and expressions for Vox-style motion, camera rigs, transitions, finishing |
| [`cinematography-for-ai`](skills/cinematography-for-ai/SKILL.md) | Camera moves and their intent, composition, lenses, and prompts for AI video tools |

The skills hand off to each other: **plan** (explainer-documentary) â†’ **look** (vox-collage-design) â†’
**motion** (vox-after-effects-recipes) â†’ **shots** (cinematography-for-ai).

## Install

**Claude Code:** copy a skill folder into `~/.claude/skills/` (all projects) or `.claude/skills/`
(one project).

```bash
git clone https://github.com/AmeerBashaK/claude-skills.git
cp -r claude-skills/skills/* ~/.claude/skills/
```

**Claude.ai / Claude desktop:** zip a skill folder (the zip must contain `<skill-name>/SKILL.md`) and
upload it in Customize â†’ Skills.

## Sources

Distilled from studying public tutorials and documentaries, including createdaley's After Effects
tutorials, Mapal, Nijat Ibrahimli, StudioBinder's Shot List series, Dan Kieft's AI camera prompts,
a Claude + Higgsfield Vox tutorial by Joseph | Video Editing, and Aevy TV documentaries. The skills
contain original summaries and techniques, not copies of the source material.
