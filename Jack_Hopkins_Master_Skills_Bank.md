# Jack Hopkins: Master CV Source Document

**Purpose:** This is a reference bank, not a CV to send anywhere. It pulls together everything from your portfolio site, `Resume.md`, and your Unreal skills voice memos into one deduplicated master list, so you (or I) can pull the right subset when tailoring a CV for a specific job. A handful of items from the voice memos were hard to make out, so they're flagged at the bottom rather than guessed into the main list, keeping anything inaccurate off a real CV.

---

## 1. Positioning

Lead identity: **Technical Gameplay Designer**, combining design thinking with hands-on technical implementation rather than sitting as a pure designer or pure programmer. Frame Astral Dawn Studios as evidence of self-directed initiative, not a footnote.

---

## 2. Work Experience

### World Makers, Cambridge: Gameplay Designer | *MVX: London* | Jan 2025 – Present
- Own delivery of DLCs, maps, gameplay features, balancing passes and season pass content in UE5, working directly with engineers to turn design intent into shippable systems.
- Build and iterate gameplay using the Gameplay Ability System (abilities, attributes, effects, tags) and Blueprint frameworks, kept reusable/maintainable for designers and engineers alike.
- Lead cross-discipline delivery across art, engineering and production; coordinate local and international outsourcing teams while contributing hands-on implementation.
- Lead concepting for battle pass tiers, skins/cosmetics, and other featured seasonal content.
- Prototype and design new character roles/abilities for future paid content releases.
- Led character balancing informed by direct feedback from the competitive scene.
- Ran genre and systems research for a new unannounced project, proposing gameplay loops to inform engineering/design direction.
- Present feature and roadmap updates directly to the player community.
- Keep designs within technical/time budgets while landing distinctive gameplay for a live playerbase.

### World Makers, Cambridge: Graduate Gameplay Programmer | *Deceit 2* | Oct 2022 – Jan 2025
- Implemented gameplay across architecture, networking-adjacent tooling and profiling, working extensively with the Gameplay Ability System primarily via Blueprint, including networked events/functions, RPCs and replication.
- Took designer-authored features from prototype through to polished, shipped releases across multiple live updates.
- Led blockout and task design (prototype through completion) on **Blackthorne Manor**, **Cirque du Solara** (Circus DLC map), **Helios Program** (Space/Alien DLC map), and **Bluff Gulch** (Wild West/Cowboy DLC map); this doesn't include Millhaven Asylum or Project Wurgen, which predate this scope of work.
- Designed and implemented universal task types (sabotage and inspection tasks) present across every map.
- Led concepting, art direction and self-driven design/implementation on the **Space Update (Alien Terror DLC)**, including animation work via Control Rig.
- Built internal tooling to automate the cosmetics pipeline: a C++ in-editor script that reads spreadsheet/CSV data and generates Blueprint and Data Assets (items, character skins, emblems, emotes, loading screens).
- Built a Java backend service that synced spreadsheet-driven content data with the in-game shop.
- Gathered and triaged feedback from long-term players and playtesters, translating it into concrete engineering and design changes.
- Built UE level blockouts across disciplines, aligning creative teams around a shared technical plan.
- Coordinated outsourcing teams for level art.
- Supported console playtesting and certification-adjacent work on Xbox and PlayStation, including organising playtest sessions.

### Astral Dawn Studios, Windsor: Founder & Lead Artist | Jun 2019 – Oct 2020
- Self-directed indie development in Unity with two co-founders (Karsten Finlay, Lars Finlay); shipped a public demo (*Dodo Alone*).
- Led all art direction and production: character portraits, tilesets, battle animations, dialogue sprites (overworld + in-dialogue), UI art, and multiple character idle/attack animations.
- 3D modelling in Blender; implemented a custom shader for a character model in Unity.
- Composed/produced original music and sound for the game.
- Produced devlogs and tutorials communicating technical and design decisions to a public audience (one tutorial video surpassed 1,000 views with strong engagement).
- Earlier long-form project (May 2018 – ~Aug 2019): led art on *Astral Dawn*, a JRPG shelved due to scope, informing the decision to pursue the smaller-scope *Dodo Alone*.

*(Note: your portfolio site currently describes Astral Dawn in the present tense as an ongoing project; worth deciding whether it's still active or should be described in the past tense to match Resume.md's Jun 2019–Oct 2020 dates.)*

---

## 3. Unreal Engine 5: Technical Skills

**4 years of professional UE5 experience**, kept current through to **UE 5.8** (Epic's last planned major UE5 release before UE6).

**Gameplay systems**
- Gameplay Ability System: abilities, attributes, effects, gameplay cues (both burst and looping types), gameplay tags (including tag replication), and reusable ability architecture
- Blueprint visual scripting, including networked events/functions, RPCs (Remote Procedure Calls) and replication
- Gameplay event/message broadcasting between systems (Lyra-style gameplay messaging)
- Familiarity with the Lyra sample project as a GAS reference implementation
- Chaos physics, including the Chaos Mover plugin

**Animation & characters**
- Animation Blueprints
- Control Rig (used for both general character animation and DLC-specific animation work)
- MetaHumans, including MetaHuman Animator (facial performance capture) for emotes/animation
- Retargeting static meshes onto different skeletons and skinning them as part of the cosmetics pipeline

**Audio**
- MetaSounds
- Audacity (sound creation/editing)

**VFX**
- Niagara

**Rendering & art**
- Materials and material instances, including dynamic material instances created and edited at runtime
- Texture creation and optimisation (normal maps, roughness maps, opacity masks) via Photoshop, including recolours of character skins
- Texture optimisation across skins, cosmetics, and environment art maps
- Skeletal and static mesh optimisation
- LOD (Level of Detail) and HLOD (Hierarchical LOD) systems for map and skin optimisation, including generative/automated LOD generation
- Dynamic lighting and lighting optimisation within levels, including reflection captures

**UI / UMG**
- Built menus and in-game HUD widgets using UMG (Widget Blueprints), covering both visual assets and functionality
- Ability-related UI: screen effects on ability cast, cooldown indicators, reticules, ability icons

**Level design**
- Blockout-to-completion across multiple shipped maps
- Modular kit-based level layout
- Unreal terrain tools

**Profiling & optimisation**
- Unreal Insights (built-in profiling tool), used on active/Blueprint components
- Blueprint optimisation (self-directed deep dive)

**Tools programming**
- C++: in-editor script reading CSV/spreadsheet data to auto-generate Blueprint and Data Assets for the cosmetics pipeline
- C++: developer/debug tools to speed up iteration, e.g. skipping intro animations and selectively loading specific cosmetics for testing
- Java: backend service syncing spreadsheet-driven data with the in-game shop

**Backend & data**
- MongoDB: backend database storing Deceit 2 player data (usage only, not involved in setting up or running the backend infrastructure itself)

**Build & CI**
- Created builds using TeamCity, Horde, GitHub Actions, and proprietary internal tooling (build creation only, not backend/infrastructure setup)

**Platforms & pipeline**
- Console development support: Xbox and PlayStation, including playtesting/cert-adjacent work
- Version control: Perforce (P4V), Unreal Game Sync (UGS), Git, GitHub

---

## 4. C++ & Programming Fundamentals

- **MEng Computing (Games Engineering), First Class Honours**, Newcastle University, Sep 2018 – Jun 2022
- Languages: proficient in **C++, C#, Java, Unity, HTML, CSS**; working knowledge of **C, Godot, Assembly, JavaScript, MySQL**
- Master's dissertation: *Procedural Animation in Unreal Engine* (automated limb placement, ragdoll, partial physical animation, animation blending; researched Featherstone's algorithm and passive/active animation categorisation), implemented in Blueprint + Control Rig: **88%**
- Bachelor's dissertation: *Automatic City Generator* (C#/Unity): procedural settlement generation from a colour-coded layout diagram
- Coursework:
  - **CSC8503 Advanced Game Technologies** (C++): collision detection/resolution, menus, SFX, state-based AI, built on a custom OpenGL-based framework
  - **CSC8502 Advanced Graphics for Games** (C++/OpenGL): skybox, normal maps, height maps, automated moving camera
  - **CSC8501 Advanced Programming for Games** (C++): password manager using the Collatz function for encryption/authentication
  - **CSC3224 Game Development** (C#/Godot): "An Afternoon With The Queen," multi-board tic-tac-toe variant with Minimax + Alpha-Beta pruning AI
  - **CSC3222 Game Simulations** (C++): Newtonian physics (forces, impulse, springs, integration), collision detection/response, basic AI/pathfinding
  - **CSC3223 Graphics for Games** (Unity): planet textures, environmental lighting, water shaders (realistic + stylised), day/night cycle, post-processing
- Personal C++ project: **Guided Missile System** (Unreal Engine, C++, Jun 2022): full guided-missile targeting/control system, built as a technical assessment

---

## 5. Personal / Indie Game Projects

- **GMTK Game Jam 2021**: 48-hour team jam ("Joined Together" theme); journalist-balancing game; ranked 860th/5,800+ entries, 423rd for Presentation (the category led)
- **Ludum Dare 44**: 72-hour team jam ("Life is Currency" theme); tower-defence game (*Old Macdonald's Farm*), *Plants vs. Zombies*-style
- **Vinland Saga Tactics**: solo dev, Unity, isometric TRPG inspired by Vinland Saga / Divinity: Original Sin 2 / Fire Emblem / Final Fantasy Tactics (currently on hiatus)
- **EPQ Project ("Pincic Pillager")**: research project on intuitive game design (Super Mario Bros, Mega Man); built a full level in Construct 2 (design, art, music, SFX) playable without verbal instruction

---

## 6. Art & Creative Skills

- Pixel art: character portraits, tilesets, battle animations, dialogue/overworld sprites, idle & attack animations
- Concept art and illustration (character rosters, promo art)
- 3D modelling (Blender), custom shader implementation (Unity)
- UI/UX art
- Texture art: normal maps, roughness maps (Photoshop)
- Music composition/production and sound design

---

## 7. Video Production / Content Creation

- 10+ years editing video across 7 YouTube channels; scriptwriting, research, thumbnail creation
- **Jarkey Bacon**: long-running personal channel, 2,500+ subscribers, 500,000+ views
- **KyleEntertainment** (hired freelance editing): Attack on Titan tribute (4 manga music videos) and a Vinland Saga character analysis video
- **Astral Dawn Studios channel**: devlogs, tutorials, and a podcast on dialogue/character writing in games
- Created short-form video content; interviewed for long-form and live-format content published on socials
- Church and family video work (Marvel parody intro, promotional advert)

---

## 8. Leadership, Collaboration & Soft Skills

- Cross-discipline leadership across art, engineering and production
- Managing local and international outsourcing teams
- Community and competitive-scene feedback loops; presenting directly to players
- Worked in agile/sprint development environments
- Task management tooling: Jira, Trello, Linear, YouTrack, GitHub project tracking
- Team leadership: led a cabin of 12 campers (SunnyBrae Bible Camp, 2016–2017), part of a 30-person summer staff team, helped prepare meals for up to 215 kids
- Customer-facing service: Windsor Castle (Royal Collections retail, summer 2019), Blossoms of Windsor (Chinese takeaway, 2017–2018)
- Long-running community/church involvement (2014–present): drumming, AV/sound, general volunteering

---

## 9. Flagged Items: Please Confirm Before Use

The voice memos were transcribed automatically and a few phrases came through garbled. Best-guess interpretations below, please correct or discard before anything from this list goes into a real CV.

**Resolved:**
- "capacity masks" / "capacity map" → **opacity masks** (confirmed by Jack); now written up as such in Section 3.
- "PC calls or RCP calls, I'm not sure which one" → **RPC (Remote Procedure Call)**, standard Unreal networking terminology; now written up as such.
- "experience with a job, a Mongo DB" → **MongoDB**, a backend database storing Deceit 2 player data, not version control, and Jack's involvement was on the usage side, not backend/infrastructure setup (confirmed by Jack). Moved out of the version control bullet into its own line in Section 3.
- "ring T's 50, the underlying board, create build for the game" → **TeamCity and Horde**, plus proprietary internal tooling: build creation only, not backend/infrastructure setup (confirmed by Jack). Written up in Section 3.
- Jarkey Bacon subscriber count, confirmed at **2,500+ subscribers** (website's "500+" was outdated; view count of 500,000+ still stands). Updated in Section 7.
- Version control third tool → confirmed as **Unreal Game Sync (UGS)** alongside P4V and Git. Updated in Section 3.
- "level details, including reflection... page log" → **reflection captures**, a UE lighting workflow (confirmed by Jack). Updated in Section 3.
- "pins" (alongside battle pass tiers/cosmetics) → **skins** (confirmed by Jack). Updated in Section 2.

**Still unclear:**

| Heard as... | Likely meaning | Status |
|---|---|---|
| "updated virus system with super fun" | UI-related (Jack's best recollection), but exact system/feature still unclear | Narrowed to UI; needs a firmer memory of what "super fun" refers to before it's usable on a CV |

---

## How to use this doc

When tailoring a CV for a specific role (like the Jagex-tailored `Resume.md`), pull only the sections relevant to that job's emphasis: e.g. a programming-heavy role pulls hard from Sections 3–4, a design-heavy role leads with Section 2 and trims the tooling detail. Keep this doc itself unpolished and comprehensive; polish happens in the tailored output.
