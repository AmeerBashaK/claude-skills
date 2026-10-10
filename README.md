# Claude Skills: Documentary, Motion & Graphic Design

A set of [Claude](https://claude.ai) Agent Skills for planning, designing and animating presenter-led
explainer documentaries in the Vox / Aevy TV tradition, plus the graphic design fundamentals behind them.

## Documentary and motion
| Skill | What it does |
|---|---|
| [`explainer-documentary`](skills/explainer-documentary/SKILL.md) | Format, cold opens, story structure, writing voice and a scene-by-scene plan |
| [`vox-collage-design`](skills/vox-collage-design/SKILL.md) | Design system: paper textures, cutouts, colour, typography, hand-drawn marks, scene layouts |
| [`vox-after-effects-recipes`](skills/vox-after-effects-recipes/SKILL.md) | Exact After Effects settings and expressions for Vox-style motion, camera rigs, transitions, finishing |
| [`cinematography-for-ai`](skills/cinematography-for-ai/SKILL.md) | Camera moves and their intent, composition, lenses, and prompts for AI video tools |

## Graphic design fundamentals
| Skill | What it does |
|---|---|
| [`design-principles`](skills/design-principles/SKILL.md) | C.R.A.P., hierarchy, white space, balance, colour, UI/UX, Laws of UX, process and a good-vs-bad critique checklist |
| [`typography`](skills/typography/SKILL.md) | Typeface choice, pairing, sizes, leading, line length, kerning, type systems, common faults, logos and lettering |
| [`layout-composition`](skills/layout-composition/SKILL.md) | Eye flow, grid types and when to use them, leverage points, rhythm, friction, the LIFT check |

## Motion styles
| Skill | What it does |
|---|---|
| [`swiss-style-motion`](skills/swiss-style-motion/SKILL.md) | Swiss / International Typographic Style in motion: grid-locked movement, beat-locked timing, snap easing, signature moves, After Effects and GSAP recipes |
| [`pop-art-motion`](skills/pop-art-motion/SKILL.md) | Pop art in motion: Ben-Day dots, halftone, thick outlines, Warhol plates and grids, comic SFX, overshoot pops, impact frames, dot wipes, After Effects and GSAP recipes |
| [`flat-2d-motion`](skills/flat-2d-motion/SKILL.md) | Flat 2D illustration and animation: geometric construction, 60-30-10 palettes, cel shading, easing, overlap, morphs, draw-ons, idle loops, parallax, Duik rigging, After Effects and GSAP recipes |
| [`clay-3d-motion`](skills/clay-3d-motion/SKILL.md) | Clay 3D: plasticine forms and materials, miniature lighting, smooth claymorphism and stop-motion claymation (on twos, boiling surfaces), Blender, After Effects and Higgsfield recipes |
| [`glassmorphism-motion`](skills/glassmorphism-motion/SKILL.md) | Glassmorphism: frosted panels, Apple-style Liquid Glass (refraction, specular, gooey merges) and 3D glass; contrast rules, living backgrounds, parallax, light sweeps; After Effects, CSS/GSAP and Blender recipes |
| [`y2k-chrome-motion`](skills/y2k-chrome-motion/SKILL.md) | Y2K chrome: liquid metal type, iridescent and holo gradients, bubble forms, sparkles and flares; sheen sweeps, mercury morphs, chrome spins, glitch cuts; After Effects, Blender, CSS/GSAP and Higgsfield recipes |
| [`synthwave-motion`](skills/synthwave-motion/SKILL.md) | Synthwave / Outrun: neon grids, segmented sun, wireframe mountains, 80s chrome and neon type, VHS; endless drive, beat pulses, neon ignition, title slams; After Effects, Blender, CSS/GSAP and Higgsfield recipes |
| [`risograph-motion`](skills/risograph-motion/SKILL.md) | Risograph: 2-3 translucent spot inks, overprint, misregistration, grain and paper; stepped timing, registration drift, ink-pass reveals, paper-feed transitions; After Effects, Photoshop/Illustrator, CSS/GSAP and Higgsfield recipes |
| [`particle-motion`](skills/particle-motion/SKILL.md) | Particles: dust, sparks, confetti, plexus, flow fields, logo formation, disintegration; design rules (hierarchy, density, size tiers, lifecycle) and force-driven motion; After Effects, Blender Geometry Nodes, Canvas/Three.js and Higgsfield recipes |
| [`neo-brutalism-motion`](skills/neo-brutalism-motion/SKILL.md) | Neo-brutalism: thick outlines, hard zero-blur shadows, flat clashing colour, big quirky type; press-into-shadow, slams, sticker slaps, marquees, cursor clicks; After Effects, CSS/GSAP and Higgsfield recipes |
| [`bauhaus-motion`](skills/bauhaus-motion/SKILL.md) | Bauhaus: primaries and black, circle/square/triangle, asymmetric diagonals, lowercase geometric type; shapes as actors, compass construction, tile cascades, Albers colour shifts; After Effects, CSS/GSAP and Higgsfield recipes |
| [`vaporwave-motion`](skills/vaporwave-motion/SKILL.md) | Vaporwave: pastel neon, statues, Windows 95 UI, Japanese/fullwidth text, checker floors, lo-fi VHS; slowed dreamy loops, statue spins, error cascades, echo trails; After Effects, Blender, CSS/GSAP and Higgsfield recipes |
| [`pixel-art-motion`](skills/pixel-art-motion/SKILL.md) | Pixel art: native-res grids with integer scaling, limited palettes, clean lines, dithering; frame-by-frame timing by holds, whole-pixel motion, sub-pixel animation, palette cycling, hit flashes; Aseprite, After Effects, Blender, canvas, Python cleanup and Higgsfield recipes |

The documentary skills hand off to each other: **plan** (explainer-documentary) → **look** (vox-collage-design) →
**motion** (vox-after-effects-recipes) → **shots** (cinematography-for-ai). The design skills apply to all of them.

## Install

**Claude Code:** copy a skill folder into `~/.claude/skills/` (all projects) or `.claude/skills/`
(one project).

```bash
git clone https://github.com/AmeerBashaK/claude-skills.git
cp -r claude-skills/skills/* ~/.claude/skills/
```

**Claude.ai / Claude desktop:** zip a skill folder (the zip must contain `<skill-name>/SKILL.md`) and
upload it in Customize → Skills.

## Sources

Distilled from studying public tutorials and documentaries, including createdaley's After Effects
tutorials, Mapal, Nijat Ibrahimli, StudioBinder's Shot List series, Dan Kieft's AI camera prompts,
a Claude + Higgsfield Vox tutorial by Joseph | Video Editing, Aevy TV documentaries, The Futur (Chris Do,
Matthew Encina, Gemma O'Brien), Satori Graphics, Jesse Showalter, Kole Jain, Juxtopposed, Envato Tuts+,
DesignSpo, Kittl, GraphiqVibe and the Laws of UX by Jon Yablonski. The Swiss style skill draws on the work
of Josef Müller-Brockmann, Armin Hofmann, Emil Ruder and Mat Voyce, and on design-history write-ups. The pop art skill draws on the work of Roy Lichtenstein,
Andy Warhol, Richard Hamilton and their peers, via museum and school education material. The flat 2D skill draws on the IBM Design Language flat illustration
guidelines, Linearity, Icons8 and RxLaboratory's Duik. The clay 3D skill draws on BlenderNation and Blender Bazaar
clay tutorials, Kin Klei, Marmoset and classic claymation (Aardman, Laika, Will Vinton). The glassmorphism skill draws on IxDF, Axess Lab and coverage
of Apple's Liquid Glass design language. The Y2K chrome skill draws on Y2K Futurism write-ups (Webflow, Grapheine,
Made Good Designs), Motion Array and BlenderNation. The synthwave skill draws on PremiumBeat, RetroShaper,
Signalnoise and synthwave genre history. The risograph skill draws on Moniker Press, the SAIC Service Bureau and
University riso guides, and riso-simulation write-ups. The particle skill draws on tutvid, BlenderNation's
Simulation Nodes series, Unity and Vizrt docs, Reynolds' boids and curl-noise literature. The neo-brutalism skill draws on SVGator, Made Good Designs, the
Design Style Guide, Mailchimp and neubrutalism UI component libraries. The Bauhaus skill draws on The Art Story, the V&A, Letterform Archive,
the Getty and the work of Bayer, Kandinsky, Albers, Moholy-Nagy and Schlemmer. The vaporwave skill draws on USC's Understanding
Vaporwave, the Mutual Images Journal, Grinnell's subculture notes and AEJuice. The pixel art skill draws on
Adafruit, Pixel Joint, Tiny Warrior Games, Aseprite docs and Adobe community notes on nearest-neighbour scaling. The skills contain original summaries
and techniques, not copies of the source material.

## License

Dual-licensed under [MIT](LICENSE-MIT) or [GPL-3.0](LICENSE-GPL), at your option.
