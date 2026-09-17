# Case Portfolio — Izramor

*Russian version below the divider.*

12 cases in two tracks: **dev** — engineering projects, **creative** — AI-assisted creative R&D. Numbers come
from git history, project files and scripts; where data does not exist, the text says so. No personal data,
passwords or private network addresses are included.

## Positioning

- **Looking for:** [role — to be filled in by the author]
- **Specialisation:** [to be filled in by the author]
- **Format:** [to be filled in by the author]
- **Open to:** [to be filled in by the author]

## About

Author of 12 personal projects brought to a working state: a two-way audio baby monitor running on a home PC,
a public ESKD knowledge base with an AI note pipeline, a production pipeline for a game project with a
self-trained LoRA, and a prompt system for a portable AI assistant. Works with local models and GPUs, Windows
automation, CI, and documentation as part of delivery.

## Two tracks

- **cases/dev/** — engineering projects: services in production use, tools, production pipelines.
- **cases/creative/** — AI-assisted creative work: language models, narrative design, game systems.

Every case exists in two languages: the English and Russian files sit side by side, marked with .en and .ru
suffixes in the file name.
Type: **product** — in use by real users, **method** — a repeatable production approach, **tool** — a set of
utilities, **demo** — a public showcase. Rating shows how mature the result is today.

### Case groups

Navigation by topic — a case may belong to several groups; this is a reading aid, not a taxonomy:

- **Echelon Beyond** — dev/04, dev/05, dev/07.
- **Prompt engineering and AI collaboration** — creative/01, creative/04, dev/02.
- **Everyday products** — dev/01, dev/02.
- **Game systems** — dev/03, creative/02, creative/03, creative/06.

### Dev cases (cases/dev/)

| № | Case | Type | Rating | File |
|---|---|---|---|---|
| 01 | Videokamera (baby monitor on a home PC) | product | in use, 18 commits, runs at home | [dev/01-videokamera.en.md](cases/dev/01-videokamera.en.md) |
| 02 | Between the Lines of the Blueprint — knowledge base for a drawing checker | product (public) | in use, 53 commits, live site | [dev/02-normcontrol-kb.en.md](cases/dev/02-normcontrol-kb.en.md) |
| 03 | Through the Ripple — mini-game (easter egg /echelon) | demo | in use, 1,893 lines of JavaScript, public | [dev/03-echelon-mini-game.en.md](cases/dev/03-echelon-mini-game.en.md) |
| 04 | Echelon Beyond — world, 18 volumes, assets | method (private project) | docs and production ready, game code not started | [dev/04-echelon-beyond.en.md](cases/dev/04-echelon-beyond.en.md) |
| 05 | Orchestrating Cline for art and music | method | working: own LoRA, ~300 tracks, 141 menu frames | [dev/05-cline-art-music.en.md](cases/dev/05-cline-art-music.en.md) |
| 06 | Print layout for books and manuals | tool | working: 194 PDFs rebuilt with print margins | [dev/06-txt-to-docx.en.md](cases/dev/06-txt-to-docx.en.md) |
| 07 | Pipeline "phone → laptop → home PC" | tool | working at home, 68 automation files | [dev/07-echelon-remote-pipeline.en.md](cases/dev/07-echelon-remote-pipeline.en.md) |

### Creative cases (cases/creative/)

| № | Case | Type | Rating | File |
|---|---|---|---|---|
| 01 | Lorien — a portable AI personality | R&D / method | ongoing: 6 crystal versions, 4 assistant roles | [creative/01-lorien.en.md](cases/creative/01-lorien.en.md) |
| 02 | D&D module "Curse of Discord in the Snowy Valley" | R&D / table materials | completed: 9 NPCs, 4 locations, 3 scenarios | [creative/02-dnd-module.en.md](cases/creative/02-dnd-module.en.md) |
| 03 | Tavern Tales — balancing a card roguelike | R&D / method | prototype: formulas, balance tables, economy | [creative/03-tavern-tales.en.md](cases/creative/03-tavern-tales.en.md) |
| 04 | Prompt engineering for creative AI projects | method (cross-cutting) | ongoing: 6 techniques plus emotional layer control | [creative/04-prompt-engineering.en.md](cases/creative/04-prompt-engineering.en.md) |
| 06 | Adapting D&D 5e to the custom world of Echelon Beyond | R&D / rules hacking | completed: 4 races, 4 classes, bestiary, 1 session | [creative/06-dnd-adaptation.en.md](cases/creative/06-dnd-adaptation.en.md) |

The former case "Emotional design in AI stories" was archived as
`cases/creative/05-emotional-design.md.archived` and merged into case 04 (section "Emotional layer control");
the reason is in `_archive/05-emotional-design/REASON.md` (Russian only).

Cases cross-reference each other: every file has a "Related cases" section (inside a track — direct links,
across tracks — through `../dev/` and `../creative/`).

## Skills

Skill levels are derived from case metrics (volume of work, presence of checks, reaching real use) — the
reasoning behind each level is in the skill file itself.

| Skill | Track | Level | Where it is confirmed |
|---|---|---|---|
| [AI agent orchestration](skills/ai-orchestration.en.md) | cross-cutting | advanced | dev/04 (51 agent commits, AGENTS.md), dev/02 (HANDOFF.md, issue pipeline), dev/07, creative/04; including teaching the agent to drive external tools: image generation, LoRA training, music, LLM providers |
| [Cline as a tool orchestrator](skills/cline-as-tool-orchestrator.en.md) | cross-cutting | advanced | dev/05 (Fooocus, kohya_ss, ACE-Step), dev/07 (Ollama, LM Studio), dev/02 (DeepSeek in CI), dev/04 (AGENTS.md) |
| [Local services: HTTPS, auth, WebRTC](skills/fullstack-local.en.md) | dev | confident | dev/01 (HTTPS 8443, Basic Auth, WebRTC, Windows service), dev/02 (live site with CI), dev/03, dev/07 |
| [Windows automation and CI](skills/automation.en.md) | cross-cutting | confident | dev/01 (18 tools, scheduled tasks), dev/06 (22 scripts, 194 PDFs), dev/07 (68 files), dev/02 (Actions), dev/04 |
| [Content pipeline: text → site → print](skills/content-pipeline.en.md) | cross-cutting | confident | dev/02 (128 notes, link audit), dev/06 (print-ready set), dev/04 (18 volumes), dev/03 |
| [Consistent visual style (LoRA + prompts)](skills/visual-style.en.md) | dev | confident | dev/05 (LoRA, 18 prompt iterations, 141 frames), dev/04 (art rules) |
| [Local AI on 8 GB of VRAM](skills/local-ai-gpu.en.md) | dev | advanced | dev/05 (11x and 1.8x training speed-up, two LoRAs, ~300 tracks), dev/07 (local LLMs) |
| [Remote access and home infrastructure](skills/remote-access.en.md) | dev | confident | dev/07 (68 files, 6 documents), dev/01 (outside access), dev/04 (source-of-truth rule) |
| [Prompt engineering](skills/prompt-engineering.en.md) | cross-cutting | advanced | creative/01 (6 crystal versions, 4 roles), creative/04 (6 techniques), dev/02 (AI pipeline), dev/05 (prompts as files in git, 18 iterations), dev/04 (agent rules) |
| [Narrative design](skills/narrative-design.en.md) | creative | confident | creative/02 (9 NPCs, 4 locations, 3 scenarios), creative/01, creative/04, creative/03, dev/04 (18 volumes), dev/03 (lore notes) |
| [Game design](skills/game-design.en.md) | creative | confident | creative/03 (weights 2/5/8, progression, formulas, balance tables), creative/02 ("Shards of Faith"), dev/03 (1,893-line game), dev/04 (TASKS.md, volume VII) |

## Aggregate metrics

Counted only from verifiable sources: git history (log --shortstat, shortlog), file metrics (file and line
counts) and tool inventories.

| Metric | Value | Source |
|---|---|---|
| Cases in the portfolio | 12: 7 dev + 5 creative | portfolio structure |
| Commits | 128 in external repositories (103 of them authored by me) + 64 in the portfolio itself | PetCam 18/54, Echelon Beyond 37/57, normcontrol-kb 48/53; portfolio — local git history |
| Unique files touched | 604 | 40 + 218 + 346 (external repositories) |
| Lines of code and documents | +76,039 / −7,943 | sum over three repositories (author commits) |
| Scripts and tools built | ≈ 290 | 18 (camera) + 22 (print layout) + 232 (game project: generation, diagnostics, delivery) + ~20 (knowledge base) |
| External tools wired into Cline | 5+ | Fooocus, kohya_ss, ACE-Step, Ollama, LM Studio |
| Automated checks and tests | ≈ 24 | 6 (camera) + 14 (print layout checks) + 3 mandatory + one unit test (knowledge base) + LoRA A/B test |
| Data processed by scripts | 194 PDFs, ~300 audio files, 128 knowledge base notes | cases dev/02, dev/05, dev/06 |
| Creative artifacts | 6 crystal versions and 4 assistant roles; 9 NPCs, 4 locations, 3 scenarios; 5 card types with weights 2/5/8 and 2 formulas; 4 races, 4 classes and a bestiary | cases creative/01–04 and 06 |
| Time spent | 2.5 hours confirmed (camera follow-up work); creative projects ran for about a year, hours not documented | author's data |
| AI cost | $0.70 (DeepSeek, camera); local models and subscriptions — spend not documented | author's data |
| Users | 2 for the everyday product (parents), 1 for the knowledge base, 1 for the game project | cases dev/01, dev/02, dev/04 |
| Public URLs | 2 (knowledge base site and the easter egg) | cases dev/02, dev/03 |

## Contacts and links

| What | Link |
|---|---|
| GitHub | https://github.com/frinog1-a11y |
| Between the Lines of the Blueprint | https://frinog1-a11y.github.io/normcontrol-kb/ |
| Mini-game (easter egg) | https://frinog1-a11y.github.io/normcontrol-kb/echelon |
| Local projects | C:\PetCam, C:\EchelonBeyond, C:\Normcontrol-KB (private, details on request) |
| This portfolio | C:\Portfolio (git repository, local history) |

## Not included (and why)

Reconnaissance found more on disk than went into the cases. Nothing was dropped silently — here is what stayed
out and why:

| Found | Why it is not a case |
|---|---|
| C:\monaw-main — a desktop AI agent for Windows with tools, memory and MCP | third-party open-source project, only deployed locally; no author changes in its history |
| amnezia-client-dev, amneziawg-windows-client-master123 | third-party VPN client sources, no author changes found |
| Ren'Py scripts in backups (two files, 783 and 883 lines) and an installed Ren'Py SDK | too little data: unclear whether the visual novel prototype was finished (possibly an early prototype of the game project) |
| Everwind, installed games, Nexus, mod tools | games and utilities, not development work |
| Ender3V3SE_Firmware | 3D printer firmware, no author changes found |
| inetpub (IIS), Reference (image collection) | traces of deployed tools and materials with no link to the projects |
| Screenshots and demo videos of the projects | not found in any folder — they have to be captured from scratch |

## To confirm with the author

1. **The "TXT → DOCX for book printing" script.** What was found is a pipeline of 22 scripts: TXT → tables → PDF
   and DOCX → PDF, plus rebuilding PDFs with mirrored margins. There is no separate "TXT → DOCX" step — perhaps it
   refers to another script that is not on this PC.
2. **Are there other projects** outside C:\ (another drive or the laptop)? The portfolio covers this PC only.
3. **Should the portfolio be published,** and where: a separate repository with GitHub Pages, a private archive,
   or local only.
4. **What may be disclosed:** names of people and organisations, device names, spending figures, the contents of
   private project documents.
5. **The Ren'Py prototype:** two scripts with a main menu screen — an abandoned experiment, part of the game
   project, or separate work?
6. **Materials for assets:** are there ready screenshots or screen recordings that can be attached?

## Roadmap

An honest roadmap for both tracks, ordered by usefulness.

Portfolio-wide:

1. **Screenshots and demo videos.** The assets/ folder holds only a checklist: no camera UI frames, no knowledge
   base or graph screenshots, no mini-game gameplay capture, no gallery of the best art frames. Cheapest and most
   visible improvement.
2. **A reader-friendly version of the cases.** Today it is Markdown with numbers; a single page or a PDF would help
   when sending the portfolio to people without Git.
3. **Usage metrics.** Not collected: knowledge base traffic, the number of tasks submitted through the form, motion
   events recorded by the camera.
4. **Publishing the portfolio.** Not done yet: the repository is local. Options — a separate repository with GitHub
   Pages, a private archive on request, or sending it to devices.
5. **Aligning the ratings.** Five skills are marked "advanced" — a public release should have them confirmed by an
   outside look (code review of the service, the tools and the prompt templates).

Dev track:

6. **A playable game demo.** Echelon Beyond has no working scene yet: documentation and assets only. Until the first
   Godot scene exists, the case remains a "method", not a "product".
7. **A public repository for the game (maybe).** Requires de-identifying the infrastructure docs (device addresses,
   private network) and keeping heavy assets out of git.
8. **A link to the music.** ~300 generated tracks exist locally; the portfolio has no listenable sample — a few
   selected tracks need hosting.

Creative track:

9. **Metrics for the creative cases.** Hours, text volume, the number of sessions and players were not tracked (the
   projects ran for about a year) — worth capturing from now on.
10. **Publish the crystal template.** A de-identified "memory crystal" template as open-source material is the most
    portable artifact of the creative track.
11. **A playable prototype of Tavern Tales.** Build a card set and run sessions so that balance moves from formulas
    to measured statistics.
12. **Playtest the D&D module.** Record a session, collect feedback on difficulty and pacing, add handouts (maps,
    NPC cards).
13. **De-identified examples from the emotional layer work.** Two or three public examples plus a formal privacy
    checklist for personal material.

## How to read this portfolio

- Start with the case tables above: "product" means it is used by people, "method" is an approach, "tool" is a set
  of utilities, "demo" is a public showcase, "R&D" is a creative experiment.
- Every case has a "Metrics" section (numbers from real sources, and where they are missing the text says so) and a
  "Limitations" section — that section is considered the most important one.
- Creative cases end with a disclaimer about AI-assisted collaboration.
- In skill files, the "Level" section justifies the rating with numbers, and "Where it is confirmed" points to
  specific dev and creative cases.

---

# Портфель кейсов — Израмор

*(Русская версия. Английская — выше разделителя; файлы существуют в двух вариантах — с суффиксами .en и .ru.)*




# Портфель кейсов — Израмор

12 кейсов в двух направлениях: **dev** — технические проекты, **creative** — творческие AI-проекты.
Числа взяты из git-истории, файлов и скриптов; где данных нет — так и написано. Личные данные,
пароли и адреса приватных сетей в портфель не включены.

## Позиционирование

- **Ищу:** [роль — заполняет автор]
- **Специализация:** [заполняет автор]
- **Формат:** [заполняет автор]
- **Открыт к:** [заполняет автор]

## Кто такой Израмор

Автор 12 личных проектов, доведённых до рабочего состояния: видеоняня с двусторонним звуком
на домашнем ПК, публичная база знаний по ЕСКД с ИИ-конвейером наполнения, производственный
контур игрового проекта с обученной LoRA и система промптов для переносимого ИИ-ассистента.
Работает с локальными моделями и GPU, автоматизацией Windows, CI и документацией как частью поставки.

## Два направления

- **cases/dev/** — технические проекты: работающие сервисы, инструменты, производственные конвейеры.
- **cases/creative/** — творческие AI-проекты: работа с языковыми моделями, нарратив, геймдизайн.

Тип: **продукт** — работает для реального пользователя, **метод** — воспроизводимый производственный
подход, **инструмент** — набор утилит, **демо** — публичная демонстрация.
Оценка — зрелость результата на сегодня.

### Группы кейсов

Навигация по смысловым группам — кейс может входить в несколько групп, это способ читать портфель,
а не классификация:

- **Echelon Beyond** — dev/04, dev/05, dev/07.
- **Prompt-инженерия и AI-коллаборация** — creative/01, creative/04, dev/02.
- **Бытовые продукты** — dev/01, dev/02.
- **Игровые системы** — dev/03, creative/02, creative/03, creative/06.

### Dev-кейсы (cases/dev/)

| № | Кейс | Тип | Оценка | Файл |
|---|---|---|---|---|
| 01 | Видеокамера (видеоняня на домашнем ПК) | продукт | работает, 18 коммитов, эксплуатация дома | [dev/01-videokamera.md](cases/dev/01-videokamera.ru.md) |
| 02 | «Между строк чертежа» — база знаний нормоконтролёра | продукт (публичный) | работает, 53 коммита, живой сайт | [dev/02-normcontrol-kb.md](cases/dev/02-normcontrol-kb.ru.md) |
| 03 | Мини-игра «Сквозь Зыбь» (пасхалка /echelon) | демо | работает, 1 893 строки JS, открыта публично | [dev/03-echelon-mini-game.md](cases/dev/03-echelon-mini-game.ru.md) |
| 04 | Echelon Beyond — мир, 18 томов, ассеты | метод (приватный проект) | документация и производство готовы, код игры не начат | [dev/04-echelon-beyond.md](cases/dev/04-echelon-beyond.ru.md) |
| 05 | Оркестрация ИИ для арта и музыки | метод | работает: своя LoRA, ~300 треков, 141 кадр меню | [dev/05-cline-art-music.md](cases/dev/05-cline-art-music.ru.md) |
| 06 | Печатная вёрстка книг и руководств | инструмент | работает: 194 PDF пересобраны с полями под печать | [dev/06-txt-to-docx.md](cases/dev/06-txt-to-docx.ru.md) |
| 07 | Пайплайн «телефон → ноутбук → домашний ПК» | инструмент | работает дома, 68 файлов автоматизации | [dev/07-echelon-remote-pipeline.md](cases/dev/07-echelon-remote-pipeline.ru.md) |

### Творческие кейсы (cases/creative/)

| № | Кейс | Тип | Оценка | Файл |
|---|---|---|---|---|
| 01 | «Лориэн» — переносимая личность ИИ | R&D / метод | ongoing: 6 версий кристаллов, 4 роли ассистента | [creative/01-lorien.md](cases/creative/01-lorien.ru.md) |
| 02 | D&D-модуль «Проклятие Раздора в Снежной Долине» | R&D / материал для стола | завершён: 9 NPC, 4 локации, 3 сценария | [creative/02-dnd-module.md](cases/creative/02-dnd-module.ru.md) |
| 03 | «Таверные Саги» — баланс карточного рогалика | R&D / метод | прототип: формулы, таблицы баланса, экономика | [creative/03-tavern-tales.md](cases/creative/03-tavern-tales.ru.md) |
| 04 | Prompt-инженерия для творческих AI-проектов | метод (сквозной) | ongoing: 6 приёмов + управление эмоциональным слоем | [creative/04-prompt-engineering.md](cases/creative/04-prompt-engineering.ru.md) |
| 06 | Адаптация D&D 5e под кастомный мир Echelon Beyond | R&D / rules hacking | завершён: 4 расы, 4 класса, бестиарий, 1 сессия | [creative/06-dnd-adaptation.md](cases/creative/06-dnd-adaptation.ru.md) |

Бывший кейс «Эмоциональный дизайн в AI-историях» вынесен в `cases/creative/05-emotional-design.md.archived`
и объединён с кейсом 04 (раздел «Управление эмоциональным слоем»): причина — в `_archive/05-emotional-design/REASON.md`.

Кейсы ссылаются друг на друга: связи проставлены в каждом файле в разделе «Связанные кейсы»
(внутри направления — прямыми ссылками, между dev и creative — через `../dev/` и `../creative/`).

## Навыки

Оценка уровня выведена из метрик кейсов (объём работы, наличие проверок, доведение
до эксплуатации) — обоснование цифрами в каждом файле навыка.

| Навык | Направление | Уровень | Где подтверждён |
|---|---|---|---|
| [Оркестрация ИИ-агентов](skills/ai-orchestration.ru.md) | сквозной | продвинутый | dev/04 (51 агентский коммит, AGENTS.md), dev/02 (HANDOFF.md, конвейер из issue), dev/07, creative/04; включая обучение агента работе с внешними инструментами: генерация изображений, обучение LoRA, музыка, LLM-провайдеры |
| [Оркестрация Cline для внешних инструментов](skills/cline-as-tool-orchestrator.ru.md) | сквозной | продвинутый | dev/05 (Fooocus, kohya_ss, ACE-Step), dev/07 (Ollama, LM Studio), dev/02 (DeepSeek в CI), dev/04 (AGENTS.md) |
| [Локальные сервисы: HTTPS, auth, WebRTC](skills/fullstack-local.ru.md) | dev | уверенный | dev/01 (HTTPS 8443, Basic Auth, WebRTC, служба), dev/02 (живой сайт с CI), dev/03, dev/07 |
| [Автоматизация Windows и CI](skills/automation.ru.md) | сквозной | уверенный | dev/01 (18 инструментов, задачи), dev/06 (22 скрипта, 194 PDF), dev/07 (68 файлов), dev/02 (Actions), dev/04 |
| [Контент-пайплайн: текст → сайт → печать](skills/content-pipeline.ru.md) | сквозной | уверенный | dev/02 (128 заметок, аудит связей), dev/06 (печатный комплект), dev/04 (18 томов), dev/03 |
| [Единый визуальный стиль (LoRA + промты)](skills/visual-style.ru.md) | dev | уверенный | dev/05 (LoRA, 18 итераций промта, 141 кадр), dev/04 (регламент арта) |
| [Локальный ИИ на 8 ГБ видеопамяти](skills/local-ai-gpu.ru.md) | dev | продвинутый | dev/05 (ускорение обучения в 11x и 1,8x, две LoRA, ~300 треков), dev/07 (локальные LLM) |
| [Удалённый доступ и домашняя инфраструктура](skills/remote-access.ru.md) | dev | уверенный | dev/07 (68 файлов, 6 документов), dev/01 (доступ извне), dev/04 (правило источника истины) |
| [Prompt-инженерия](skills/prompt-engineering.ru.md) | сквозной | продвинутый | creative/01 (6 версий кристаллов, 4 роли), creative/04 (6 приёмов), dev/02 (ИИ-конвейер), dev/05 (промты как файлы в git, 18 итераций), dev/04 (правила для агента) |
| [Нарративный дизайн](skills/narrative-design.ru.md) | creative | уверенный | creative/02 (9 NPC, 4 локации, 3 сценария), creative/01, creative/05, creative/03, dev/04 (18 томов), dev/03 (лорные записки) |
| [Геймдизайн](skills/game-design.ru.md) | creative | уверенный | creative/03 (веса 2/5/8, прогрессия, формулы, таблицы баланса), creative/02 («Осколки Веры»), dev/03 (игра на 1 893 строки), dev/04 (TASKS.md, том VII) |

## Суммарные метрики

Считано только по подтверждённым источникам: git-история (log --shortstat, shortlog),
файловые метрики (ls/line counts), списки инструментов.

| Параметр | Значение | Откуда |
|---|---|---|
| Проектов в портфеле | 12 кейсов: 7 dev + 5 creative | структура портфеля |
| Коммитов | 128 во внешних репозиториях (из них 103 авторских) + 25 в самом портфеле | PetCam 18/54, Echelon Beyond 37/57, normcontrol-kb 48/53; портфель — локальная git-история |
| Уникальных файлов под правкой | 604 | 40 + 218 + 346 (внешние репозитории) |
| Строк кода и документов | +76 039 / −7 943 | сумма по трём репозиториям (авторские коммиты) |
| Скриптов и инструментов создано | ≈ 290 | 18 (видеокамера) + 22 (вёрстка) + 232 (проект игры: генерация, диагностика, доставка) + ~20 (база знаний) |
| Инструментов, подключённых к Cline | 5+ | Fooocus, kohya_ss, ACE-Step, Ollama, LM Studio |
| Автопроверок и тестов | ≈ 24 | 6 (видеокамера) + 14 (проверки вёрстки) + 3 обязательных + юнит-тест (база знаний) + A/B-тест LoRA |
| Данных обработано скриптами | 194 PDF, ~300 музыкальных файлов, 128 заметок базы знаний | кейсы dev/02, dev/05, dev/06 |
| Творческие артефакты | 6 версий кристаллов и 4 роли ассистента; 9 NPC, 4 локации, 3 сценария; 5 типов карт с весами 2/5/8 и 2 формулы; 4 расы, 4 класса и бестиарий | кейсы creative/01–04 и 06 |
| Время работы | подтверждено 2,5 ч (сопровождение видеокамеры); творческие проекты длились около года, часы не задокументированы | данные автора |
| Стоимость ИИ | $0,70 (DeepSeek, видеокамера); локальные модели и подписки — расход не задокументирован | данные автора |
| Пользователей | 2 в бытовом продукте (родители), 1 в базе знаний, 1 в проекте игры | кейсы dev/01, dev/02, dev/04 |
| Публичных URL | 2 (сайт базы знаний и пасхалка) | кейсы dev/02, dev/03 |

## Контакты и ссылки

| Что | Ссылка |
|---|---|
| GitHub | https://github.com/frinog1-a11y |
| Сайт «Между строк чертежа» | https://frinog1-a11y.github.io/normcontrol-kb/ |
| Мини-игра (пасхалка) | https://frinog1-a11y.github.io/normcontrol-kb/echelon |
| Локальные проекты | C:\PetCam, C:\EchelonBeyond, C:\Normcontrol-KB (приватные, детали по запросу) |
| Этот портфель | C:\Portfolio (git-репозиторий, локальная история) |

## Не включено в портфель (и почему)

Во время разведки по диску нашлось больше, чем вошло в кейсы. Ничего из этого не выброшено
молча — вот что и почему осталось за рамками:

| Найдено | Почему не стало кейсом |
|---|---|
| C:\monaw-main — настольный ИИ-агент для Windows с инструментами, памятью и MCP | сторонний открытый проект, только развёрнут локально; авторских изменений в истории нет |
| amnezia-client-dev, amneziawg-windows-client-master123 | чужие исходники VPN-клиента, авторских правок не найдено |
| Ren'Py-скрипты в бэкапах (два файла 783 и 883 строки) и установленный Ren'Py SDK | данных мало: непонятно, доведён ли прототип визуальной новеллы (возможно, ранний прототип проекта игры) |
| Everwind, установленные игры, Nexus, мод-инструменты | это игры и утилиты, а не разработка |
| Ender3V3SE_Firmware | прошивка 3D-принтера, авторских правок не найдено |
| inetpub (IIS), Reference (подборка картинок) | следы развёрнутых инструментов/материалов без связи с проектами |
| Скриншоты и видео проектов | не найдены ни в одной папке — нужно снимать заново |

## Что нужно уточнить у автора

1. **Скрипт «TXT → DOCX для печати книг».** Найден конвейер из 22 скриптов: TXT → таблицы → PDF
   и DOCX → PDF, плюс пересборка PDF с зеркальными полями. Отдельного шага «TXT → DOCX» нет —
   возможно, имелся в виду другой скрипт, которого нет на этом ПК.
2. **Есть ли ещё проекты** вне C:\ (второй диск или ноутбук) — портфель собран только по этому ПК.
3. **Публиковать ли портфель** и куда: отдельный репозиторий с GitHub Pages, приватный архив
   или оставить локально.
4. **Что можно раскрывать:** имена людей и организаций, названия устройств, суммы расходов,
   содержание приватных документов проекта игры.
5. **Ren'Py-прототип:** два скрипта с экраном главного меню — это заброшенный эксперимент,
   часть проекта игры или отдельная работа?
6. **Материалы для assets:** есть ли готовые скриншоты/записи экрана, которые можно приложить.

## Чего ещё нет, но будет

Честный roadmap по обоим направлениям, по порядку полезности.

Общее для портфеля:

1. **Скриншоты и демо-видео.** Папка assets/ пока содержит только чек-лист: нет кадров интерфейса
   видеокамеры, скриншотов базы знаний и графа связей, записей прохождения мини-игры, галереи
   лучших кадров арт-пайплайна. Это самое дешёвое и самое заметное улучшение.
2. **Читательская версия кейсов.** Сейчас это markdown с числами; для отправки людям без Git
   полезна одна страница или PDF-версия портфеля.
3. **Метрики использования.** Не собираются: посещаемость сайта базы знаний, число задач,
   пришедших через форму, число событий движения, зафиксированных видеокамерой.
4. **Публикация портфеля.** Пока не выполнялась: репозиторий локальный. Варианты — отдельный
   репозиторий с GitHub Pages, приватный архив по запросу или отправка на устройства.
5. **Выравнивание оценок.** Пять навыков помечены «продвинутый» — при публикации стоит
   подтвердить их внешним взглядом (ревью кода сервиса, инструментов и шаблонов).

Dev-направление:

6. **Играбельное демо игры.** По Echelon Beyond нет ни одной рабочей сцены: только документация
   и ассеты. До первой сцены на Godot кейс остаётся «методом», а не «продуктом».
7. **Публичный репозиторий игры (возможно).** Требует обезличивания инфраструктурной
   документации (адреса устройств, приватная сеть) и отделения тяжёлых ассетов.
8. **Ссылка на музыку.** ~300 сгенерированных треков существуют локально; в портфеле нет
   ни одного прослушиваемого примера — нужен хостинг для нескольких отобранных треков.

Творческое направление:

9. **Метрики творческих кейсов.** Часы, объёмы текста, число партий и игроков не собирались
   (проекты длились около года) — по ходу работы есть смысл фиксировать их сразу.
10. **Опубликовать шаблон кристаллов.** Обезличенный шаблон «кристалла памяти» как open-source
    материал — самый переносимый артефакт творческого направления.
11. **Играбельный прототип «Таверных Саг».** Собрать набор карт и прогнать партии, чтобы баланс
    из формул превратился в проверенную статистику.
12. **Плейтест D&D-модуля.** Записать партию, собрать замечания по сложности и темпам, добавить
    раздаточные материалы (карты, карточки NPC).
13. **Обезличенные примеры эмоционального дизайна.** 2–3 примера, которые можно показывать
    публично, плюс формализованный чеклист приватности для личного материала.

## Как читать этот портфель

- Начните с таблиц кейсов выше: «продукт» — то, что работает у людей, «метод» — подход,
  «инструмент» — утилиты, «демо» — публичная витрина, «R&D» — творческий эксперимент.
- В каждом кейсе есть раздел «Метрики» (числа из источников, а где их нет — «не задокументировано»)
  и «Что не получилось» — раздел с ограничениями считается самым важным.
- Творческие кейсы дополнительно заканчиваются дисклеймером об AI-assisted коллаборации.
- В файлах навыков раздел «Уровень» объясняет оценку цифрами, а не словами, а раздел
  «Где подтверждено» ведёт в конкретные кейсы dev и creative.

