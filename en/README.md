# Portfolio of Izramor

**Russian version (source of truth):** [../README.md](../README.md)

12 cases in two tracks: **dev** — engineering projects, **creative** — AI-assisted creative R&D.
Numbers come from git history, project files and scripts; where data does not exist, the text says so.
No personal data, passwords or private network addresses are included in this portfolio.

## Positioning

- **Looking for:** [role — to be filled in by the author]
- **Specialisation:** [to be filled in by the author]
- **Format:** [to be filled in by the author]
- **Open to:** [to be filled in by the author]

## Who is Izramor

Author of 12 personal projects brought to a working state: a two-way audio monitor running on a home PC,
a public ESKD knowledge base with an AI Note pipeline, a production pipeline for a game project with a
self-trained LoRA, and a prompt system for a portable AI assistant. Works with local models and GPUs,
Windows automation, CI, and documentation as part of delivery.

## Two tracks

- **cases/dev/** — engineering projects: services in production use, tools, production pipelines.
- **cases/creative/** — AI-assisted creative work: language models, narrative design, game systems.

Type: **product** — in use by real users, **method** — a repeatable production approach,
**tool** — a set of utilities, **demo** — a public showcase. Rating shows how mature the result is today.

### Case groups

Navigation by topic — a case may belong to several groups; this is a reading aid, not a taxonomy:

- **Echelon Beyond** — dev/04, dev/05, dev/07.
- **Prompt engineering and AI collaboration** — creative/01, creative/04, dev/02.
- **Everyday products** — dev/01, dev/02.
- **Game systems** — dev/03, creative/02, creative/03, creative/06.

### Dev cases (cases/dev/)

| № | Case | Type | Rating | File |
|---|---|---|---|---|
| 01 | Videokamera (baby monitor on a home PC) | product | in use, 18 commits, runs at home | [dev/01-videokamera.md](cases/dev/01-videokamera.md) |
| 02 | "Between the Lines of a Drawing" — knowledge base for a drawing checker | product (public) | in use, 53 commits, live site | [dev/02-normcontrol-kb.md](cases/dev/02-normcontrol-kb.md) |
| 03 | Mini-game "Through the Rift" (easter egg /echelon) | demo | in use, 1,893 lines of JS, public | [dev/03-echelon-mini-game.md](cases/dev/03-echelon-mini-game.md) |
| 04 | Echelon Beyond — world, 18 volumes, assets | method (private project) | docs and production ready, game code not started | [dev/04-echelon-beyond.md](cases/dev/04-echelon-beyond.md) |
| 05 | Orchestrating AI for art and music | method | working: own LoRA, ~300 tracks, 141 menu frames | [dev/05-cline-art-music.md](cases/dev/05-cline-art-music.md) |
| 06 | Print layout for books and manuals | tool | working: 194 PDFs rebuilt with print margins | [dev/06-txt-to-docx.md](cases/dev/06-txt-to-docx.md) |
| 07 | Pipeline "phone → laptop → home PC" | tool | working at home, 68 automation files | [dev/07-echelon-remote-pipeline.md](cases/dev/07-echelon-remote-pipeline.md) |

### Creative cases (cases/creative/)

| № | Case | Type | Rating | File |
|---|---|---|---|---|
| 01 | "Lorien" — a portable AI personality | R&D / method | ongoing: 6 crystal versions, 4 assistant roles | [creative/01-lorien.md](cases/creative/01-lorien.md) |
| 02 | D&D module "The Curse of Discord in the Snow Valley" | R&D / table material | finished: 9 NPCs, 4 locations, 3 scenarios | [creative/02-dnd-module.md](cases/creative/02-dnd-module.md) |
| 03 | "Tavern Tales" — balancing a card roguelike | R&D / method | prototype: formulas, balance tables, economy | [creative/03-tavern-tales.md](cases/creative/03-tavern-tales.md) |
| 04 | Prompt engineering for creative AI projects | method (cross-cutting) | ongoing: 6 techniques + emotional layer control | [creative/04-prompt-engineering.md](cases/creative/04-prompt-engineering.md) |
| 06 | Adapting D&D 5e to the custom world of Echelon Beyond | R&D / rules hacking | finished: 4 races, 4 classes, bestiary, 1 session | [creative/06-dnd-adaptation.md](cases/creative/06-dnd-adaptation.md) |

The former case "Emotional design in AI stories" was archived as
`cases/creative/05-emotional-design.md.archived` and merged into case 04 (section
"Emotional layer control"); the reason is in `_archive/05-emotional-design/REASON.md`.

Cases cross-reference each other: every file has a "Related cases" section (inside a track — direct
links, across tracks — through `../dev/` and `../creative/`).

## Skills

Skill levels are derived from case metrics (volume of work, presence of checks, reaching real use) —
the reasoning behind each level is in the skill file itself.

| Skill | Track | Level | Where it is confirmed |
|---|---|---|---|
| [AI agent orchestration](skills/ai-orchestration.md) | cross-cutting | advanced | dev/04 (51 agent commits, AGENTS.md), dev/02 (HANDOFF.md, issue pipeline), dev/07, creative/04; including teaching the agent to drive external tools: image generation, LoRA training, music, LLM providers |
| [Cline as tool orchestrator](skills/cline-as-tool-orchestrator.md) | cross-cutting | advanced | dev/05 (Fooocus, kohya_ss, ACE-Step), dev/07 (Ollama, LM Studio), dev/02 (DeepSeek in CI), dev/04 (AGENTS.md) |
| [Local services: HTTPS, auth, WebRTC](skills/fullstack-local.md) | dev | confident | dev/01 (HTTPS 8443, Basic Auth, WebRTC, Windows service), dev/02 (live site with CI), dev/03, dev/07 |
| [Windows automation and CI](skills/automation.md) | cross-cutting | confident | dev/01 (18 tools, scheduled tasks), dev/06 (22 scripts, 194 PDFs), dev/07 (68 files), dev/02 (Actions), dev/04 |
| [Content pipeline: text → site → print](skills/content-pipeline.md) | cross-cutting | confident | dev/02 (128 notes, link audit), dev/06 (print-ready set), dev/04 (18 volumes), dev/03 |
| [Consistent visual style (LoRA + prompts)](skills/visual-style.md) | dev | confident | dev/05 (LoRA, 18 prompt iterations, 141 frames), dev/04 (art rules) |
| [Local AI on 8 GB of VRAM](skills/local-ai-gpu.md) | dev | advanced | dev/05 (11x and 1.8x training speed-up, two LoRAs, ~300 tracks), dev/07 (local LLMs) |
| [Remote access and home infrastructure](skills/remote-access.md) | dev | confident | dev/07 (68 files, 6 documents), dev/01 (outside access), dev/04 (source-of-truth rule) |
| [Prompt engineering](skills/prompt-engineering.md) | cross-cutting | advanced | creative/01 (6 crystal versions, 4 roles), creative/04 (6 techniques), dev/02 (AI pipeline), dev/05 (prompts as files in git, 18 iterations), dev/04 (agent rules) |
| [Narrative design](skills/narrative-design.md) | creative | confident | creative/02 (9 NPCs, 4 locations, 3 scenarios), creative/01, creative/04, creative/03, dev/04 (18 volumes), dev/03 (lore notes) |
| [Game design](skills/game-design.md) | creative | confident | creative/03 (weights 2/5/8, progression, formulas, balance tables), creative/02 ("Shards of Faith"), dev/03 (1,893-line game), dev/04 (TASKS.md, volume VII) |

## Summary metrics

Counted only from verifiable sources: git history (log --shortstat, shortlog), file metrics
(file counts and line counts), tool inventories.

| Metric | Value | Source |
|---|---|---|
| Cases in the portfolio | 12: 7 dev + 5 creative | portfolio structure |
| Commits | 128 in external repositories (103 of them authored by me) + portfolio's own history | PetCam 18/54, Echelon Beyond 37/57, normcontrol-kb 48/53; portfolio — local git history |
| Unique files touched | 604 | 40 + 218 + 346 (external repositories) |
| Lines of code and documents | +76,039 / −7,943 | sum over three repositories (author commits) |
| Scripts and tools built | ≈ 290 | 18 (camera) + 22 (print layout) + 232 (game project: generation, diagnostics, delivery) + ~20 (knowledge base) |
| External tools wired into Cline | 5+ | Fooocus, kohya_ss, ACE-Step, Ollama, LM Studio |
| Automated checks and tests | ≈ 24 | 6 (camera) + 14 (print layout checks) + 3 mandatory + one unit test (knowledge base) + LoRA A/B test |
| Data processed by scripts | 194 PDFs, ~300 audio files, 128 knowledge base notes | cases dev/02, dev/05, dev/06 |
| Creative artefacts | 6 crystal versions and 4 assistant roles; 9 NPCs, 4 locations, 3 scenarios; 5 card types with weights 2/5/8 and 2 formulas; 4 races, 4 classes and a bestiary | cases creative/01–04 and 06 |
| Time spent | 2.5 hours confirmed (camera follow-up work); creative projects ran for about a year, hours not documented | author's data |
| AI cost | $0.70 (DeepSeek, camera); local models and subscriptions — spend not documented | author's data |
| Users | 2 for the everyday product (parents), 1 for the knowledge base, 1 for the game project | cases dev/01, dev/02, dev/04 |
| Public URLs | 2 (knowledge base site and the easter egg) | cases dev/02, dev/03 |

## Contacts and links

| What | Link |
|---|---|
| GitHub | https://github.com/frinog1-a11y |
| "Between the Lines of a Drawing" site | https://frinog1-a11y.github.io/normcontrol-kb/ |
| Mini-game (easter egg) | https://frinog1-a11y.github.io/normcontrol-kb/echelon |
| Local projects | C:\PetCam, C:\EchelonBeyond, C:\Normcontrol-KB (private, details on request) |
| This portfolio | C:\Portfolio (git repository, local history) |

## Not included in the portfolio (and why)

Reconnaissance found more on disk than went into the cases. Nothing was dropped silently —
here is what stayed out and why:

| Found | Why it is not a case |
|---|---|
| C:\monaw-main — a desktop AI agent for Windows with tools, memory and MCP | third-party open-source project, only deployed locally; no author changes in its history |
| amnezia-client-dev, amneziawg-windows-client-master123 | third-party VPN client sources, no author changes found |
| Ren'Py scripts in backups (two files, 783 and 883 lines) and an installed Ren'Py SDK | too little data: unclear whether the visual novel prototype was finished (possibly an early prototype of the game project) |
| Everwind, installed games, Nexus, mod tools | games and utilities, not development work |
| Ender3V3SE_Firmware | 3D printer firmware, no author changes found |
| inetpub (IIS), Reference (image collection) | traces of deployed tools and materials with no link to the projects |
| Screenshots and demo videos of the projects | not found in any folder — they have to be captured from scratch |

## Open questions for the author

1. **The "TXT → DOCX for book printing" script.** What was found is a pipeline of 22 scripts:
   TXT → tables → PDF and DOCX → PDF, plus rebuilding PDFs with mirrored margins. There is no
   separate "TXT → DOCX" step — perhaps it refers to another script that is not on this PC.
2. **Are there other projects** outside C:\ (another drive or the laptop)? The portfolio covers
   this PC only.
3. **Should the portfolio be published,** and where: a separate repository with GitHub Pages,
   a private archive, or local only.
4. **What may be disclosed:** names of people and organisations, device names, spending figures,
   the contents of private project documents.
5. **The Ren'Py prototype:** two scripts with a main menu screen — an abandoned experiment,
   part of the game project, or separate work?
6. **Materials for assets:** are there ready screenshots or screen recordings that can be attached?

## What is still missing

An honest roadmap for both tracks, ordered by usefulness.

Portfolio-wide:

1. **Screenshots and demo videos.** The assets/ folder still holds only a checklist: no camera UI
   frames, no knowledge base or graph screenshots, no mini-game gameplay capture, no gallery of the
   best art frames. Cheapest and most visible improvement.
2. **A reader-friendly version of the cases.** Today it is markdown with numbers; a single page
   or a PDF would help when sending the portfolio to people without Git.
3. **Usage metrics.** Not collected: knowledge base traffic, number of tasks submitted through the
   form, motion events recorded by the camera.
4. **Publishing the portfolio.** Not done yet: the repository is local. Options — a separate
   repository with GitHub Pages, a private archive on request, or sending it to devices.
5. **Aligning the ratings.** Five skills are marked "advanced" — a public release should have them
   confirmed by an outside look (code review of the service, the tools and the prompt templates).

Dev track:

6. **A playable game demo.** Echelon Beyond has no working scene yet: documentation and assets only.
   Until the first Godot scene exists, the case remains a "method", not a "product".
7. **A public repository for the game (maybe).** Requires de-identifying the infrastructure docs
   (device addresses, private network) and keeping heavy assets out of git.
8. **A link to the music.** ~300 generated tracks exist locally; the portfolio has no listenable
   sample — a few selected tracks need hosting.

Creative track:

9. **Metrics for the creative cases.** Hours, text volume, number of sessions and players were not
   tracked (the projects ran for about a year) — worth capturing from now on.
10. **Publish the crystal template.** A de-identified "memory crystal" template as open-source
    material is the most portable artefact of the creative track.
11. **A playable prototype of "Tavern Tales".** Build a card set and run sessions so that balance
    moves from formulas to measured statistics.
12. **Playtest the D&D module.** Record a session, collect feedback on difficulty and pacing, add
    handouts (maps, NPC cards).
13. **De-identified examples from the emotional layer work.** Two or three public examples plus a
    formal privacy checklist for personal material.

## How to read this portfolio

- Start with the case tables above: "product" means it is used by people, "method" is an approach,
  "tool" is a set of utilities, "demo" is a public showcase, "R&D" is a creative experiment.
- Every case has a "Metrics" section (numbers from real sources, and where they are missing the text
  says so) and a "What did not work" section — the limitations section is considered the most important one.
- Creative cases end with a disclaimer about AI-assisted collaboration.
- In skill files, the "Level" section justifies the rating with numbers, and "Where it is confirmed"
  points to specific dev and creative cases.



