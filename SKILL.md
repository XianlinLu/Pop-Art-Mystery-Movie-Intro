---
name: pop-art-mystery-movie-intro
description: Create a complete 20–30 second English mystery-film opening from a single user-supplied theme, using pop-art noir poster graphics, evidence-board storytelling, animated typography, sound design, and an autonomous canvas workflow. Use for short title sequences, mystery intros, detective openings, and stylish suspense teasers; not for full trailers or realistic live-action scenes.
---

# Pop-Art Mystery Movie Intro

Turn one theme into a finished English-language mystery-film opening. The user supplies only the theme; handle concept development, story structure, visual design, asset generation, animation, sound, editing, and quality control automatically.

## User flow

**Theme → mystery concept → style bible → timed storyboard → visual assets → animated clips → sound and edit → final 20–30 second video**

If the user provides a usable theme, do not ask routine follow-up questions. Make confident creative decisions and continue through every production stage. Ask only when no theme is present or a required tool is genuinely unavailable.

Use English for all generation prompts, production copy, credits, evidence labels, title cards, and on-screen text. A user may write the theme in any language; translate and adapt it internally.

When the canvas supports visible intermediate nodes, create and label them in this order:

1. `01 Creative Brief`
2. `02 Style Bible`
3. `03 Storyboard`
4. `04 Keyframes`
5. `05 Motion Clips`
6. `06 Sound and Edit`
7. `07 Final Video`

Continue automatically between nodes. Intermediate approvals are not required.

## Default format

- Duration: 25 seconds by default; any final result from 20 to 30 seconds is valid.
- Frame: cinematic 16:9 landscape.
- Language: English on screen.
- Structure: seven connected shots with a clear hook, escalating clues, a confrontation, and a strong title reveal.
- Narration: none by default. Let typography, music, and sound effects carry the opening.
- Output: the highest stable resolution supported by the available video and editing tools, preferably 1080p.

If a generation tool cannot create the full duration, generate shorter connected clips and assemble them into one continuous timeline. Never pad the runtime with repeated loops or a long frozen frame.

## 1. Expand the theme into a mystery concept

Convert the theme into a compact internal brief containing:

- an original English film title of two to five words;
- a one-sentence logline;
- one lead character with a distinctive silhouette, costume, and color assignment;
- one opposing figure or unknown presence with a contrasting silhouette;
- one signature location;
- one hero clue or artifact that can recur as a visual motif;
- two supporting pieces of evidence;
- one central contradiction that creates the mystery;
- one short English tagline or unresolved question for the ending.

Reveal enough to create intrigue, but do not identify the culprit or solve the mystery. Keep the concept readable within a short opening rather than attempting a full plot.

Choose details that can be shown visually. Prefer a tangible clue such as a key, photograph, ledger, mask, ring, ticket, recording, sealed letter, or broken watch over abstract exposition.

Do not reuse names, logos, character designs, credits, or exact compositions visible in any reference video. Generate an original fictional identity from the user's theme.

## 2. Lock the visual bible

Use a consistent **pop-art noir title-sequence** language across every shot:

- graphic editorial illustration mixed with cutout evidence photography;
- sharp black silhouettes and angular character portraits;
- scarlet red, midnight navy, cobalt blue, ink black, warm ivory, and a restrained mustard accent;
- bold cream or white condensed uppercase typography;
- halftone dots, screen-print grain, paper fibers, ink misregistration, and subtle print wear;
- dossier grids, evidence tags, crosshairs, registration marks, scene codes, thin measurement lines, and restrained red string connections;
- high-contrast side lighting, long geometric shadows, negative space, and controlled asymmetry;
- layered poster depth created through foreground evidence, midground characters, and flat architectural backdrops.

The result should feel like an original illustrated mystery-film opening, not a live-action scene with a comic filter. Keep the palette disciplined and the typography legible.

Create a continuity ledger before generating assets. Lock the lead character's face shape, hair, costume, body proportions, silhouette, and assigned colors; lock the opposing figure's profile and colors; lock the hero clue's material, shape, markings, and damage. Reuse these exact descriptions in every relevant prompt.

## 3. Build the timed storyboard

Use this default 25-second structure. Adjust individual shots slightly when needed while keeping the final duration between 20 and 30 seconds.

| Time | Story function | Default visual and motion |
| --- | --- | --- |
| 0–3 s | Cold hook | Extreme graphic close-up of the hero clue. A circular or diagonal wipe reveals a fragment of the title; a sharp sound cue starts the mystery. |
| 3–6 s | Lead reveal | Hero portrait enters through layered poster panels. The clue overlaps the frame while short production credits or a scene code appear in negative space. |
| 6–9 s | Hidden opposition | Red and blue split screen with the lead and opposing silhouette facing across a hard diagonal divide. Use a restrained parallax push. |
| 9–13 s | Crime scene | Dossier grid combines the signature location, three evidence cells, labels, and an angular action silhouette. Snap panels into place rhythmically. |
| 13–17 s | Investigation | Evidence board assembles from papers, photographs, diagrams, stamps, and red connecting lines. Let one connection point toward the central contradiction. |
| 17–21 s | Confrontation | Mirrored red-versus-blue character composition with the hero clue suspended between them. Use sliding masks, silhouette reveals, and a brief light sweep. |
| 21–25 s | Main title | Ensemble poster composition resolves around the large English title. Hold the title long enough to read, then land the tagline or unresolved question with a final musical sting. |

Each shot must introduce new information. Preserve one recurring visual motif across cuts, such as the circular shape of a record, keyhole, clock face, lens, seal, or target.

Keep on-screen text sparse. Use the title, a tagline, a few short evidence labels, scene codes, and compact fictional credits. Avoid paragraphs. Treat all text as editable overlays rather than asking an image model to render important wording.

## 4. Generate the visual assets

Generate one clean 16:9 keyframe for each shot, plus separate reusable assets when the tool supports layers:

- lead character portrait and full silhouette;
- opposing figure portrait or silhouette;
- hero clue and supporting evidence objects;
- signature location plate;
- paper documents, diagrams, stamps, and evidence labels;
- title and credit typography overlays.

Use the continuity ledger verbatim in all related prompts. Keep safe negative space for typography. Compose character faces, evidence, and titles away from crop-prone edges.

### Keyframe prompt framework

Adapt the bracketed fields for every shot:

> Create a cinematic 16:9 keyframe for an original English mystery-film title sequence. Scene purpose: [story function]. Show [shot-specific subject and action]. Maintain the locked lead character design: [continuity description]. Maintain the locked opposing figure and hero clue when present: [continuity descriptions]. Use a high-contrast pop-art noir poster collage with scarlet red, midnight navy, cobalt blue, ink black, warm ivory, and a restrained mustard accent. Combine angular editorial illustration, black silhouettes, cutout evidence photography, halftone dots, paper grain, screen-print texture, dossier grids, registration marks, thin technical lines, and long geometric shadows. Build clear foreground, midground, and background layers for animation. Reserve [location] as uncluttered negative space for separate English typography overlays. Crisp graphic hierarchy, controlled asymmetry, original fictional branding.

Do not bake important text, logos, or watermarks into generated imagery. Add exact English wording during compositing.

## 5. Animate the shots

Animate the keyframes with graphic title-sequence motion rather than realistic camera acting. Use:

- fast panel slides and hard diagonal masks;
- circular iris reveals and rotating evidence motifs;
- short parallax pushes between paper layers;
- poster elements snapping into alignment;
- red string lines drawing between clues;
- silhouettes gliding into frame;
- controlled zooms and match cuts based on shape or color;
- subtle paper jitter, halftone shimmer, and ink-offset pulses;
- title letters arriving through scale, crop, or staggered vertical movement.

Keep motion purposeful and readable. Most movement should settle before the next cut. Preserve faces, hands, costume shapes, clue markings, evidence layout, and color assignments. Avoid fluid character acting, rubbery warping, excessive camera shake, glossy 3D surfaces, random glitch effects, and chaotic transitions.

### Motion prompt framework

> Animate this pop-art noir keyframe for [duration]. Preserve the exact character designs, clue details, palette, typography space, and printed-paper textures. [Describe one primary transition], while [describe one secondary layer motion]. Use restrained parallax, crisp graphic masks, rhythmic poster-panel movement, subtle paper jitter, and stable silhouettes. Finish in a clean held composition that connects to the next shot through [shared shape, color, or object]. Keep all important evidence and faces sharp and consistent.

Use the final frame of each clip as a reference for the next clip when supported. Match adjacent clips through a repeated clue, diagonal edge, circular motif, or red-to-blue color handoff.

## 6. Add typography, sound, and edit

Add important text after visual generation so every word is correct. Use a tall condensed uppercase sans serif for the main title and a neutral grotesk or monospaced face for evidence labels and scene codes. Keep high contrast against the background. Do not imitate a protected logo.

Build an original suspense score with a stylish spy-noir pulse: ticking percussion, muted bass, restrained brass stabs, brushed drums, vinyl texture, and a rising low-frequency tension bed. Support transitions with paper snaps, camera-shutter clicks, stamp impacts, string pulls, lock mechanisms, and one decisive final sting. Keep the score original and free of recognizable melodies.

Edit to the beat, but preserve reading time. Use hard cuts and graphic wipes more often than dissolves. Keep the final title visible for roughly three seconds. Mix sound effects beneath the music and prevent clipping.

## 7. Verify and repair

Review the complete timeline before delivery:

- duration is between 20 and 30 seconds;
- frame is 16:9 and every shot fills it cleanly;
- all visible copy is English, correctly spelled, and readable;
- the title, character designs, hero clue, and palette remain consistent;
- the story introduces a mystery without revealing its solution;
- every shot contributes a clue, escalation, confrontation, or title payoff;
- transitions feel intentional and no cut contains accidental blank frames;
- faces, hands, silhouettes, and evidence objects do not warp or flicker;
- no generated watermark, reference-specific logo, or stray gibberish text remains;
- music and effects are balanced, with no abrupt cutoff at the end.

Repair only the affected shot or overlay when possible. Make up to two focused regeneration attempts for a defective segment, then choose the most stable version and disclose any material remaining defect. Do not restart the entire project for a local issue.

## Delivery

Deliver the finished video, not only prompts or a storyboard. Keep intermediate assets organized on the canvas so the user can inspect or revise them later. In the final message, state the film title, duration, and one-sentence mystery premise.

If video generation or editing is unavailable, do not claim that a rendered video exists. Deliver the complete creative brief, style bible, timed storyboard, keyframe prompts, motion prompts, exact English text overlays, and sound plan as a production-ready fallback.
