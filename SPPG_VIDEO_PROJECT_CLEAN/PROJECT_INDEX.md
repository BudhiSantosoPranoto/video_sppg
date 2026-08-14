# SPPG VIDEO PROJECT — DOCUMENT CONTROL

## Purpose
This folder is the single working structure for the SPPG × HYDRO × The New eSpring™ video project.

## Rule
**One document = one canonical filename.**

Do not create duplicate variants such as:
- UPDATED.md
- UPDATED2.md
- FINAL.md
- FINAL_FINAL.md

When content changes, update the canonical file in place and increment its Revision number.

## Canonical Documents

### 00_MASTER
- `MASTER_BLUEPRINT.md` — project source of truth.

### 01_VISUAL
- `VISUAL_BIBLE.md` — visual rules and locked visual language.

### 02_SCRIPT
- `SHOT_LIST.md` — shot-by-shot structure.
- `VOICE_OVER_SCRIPT.md` — synchronized narration.

### 03_AI_PROMPTS
- `AI_PROMPT_PACK.md` — production prompts derived from all upstream documents.

### 04_ASSETS
- `CHARACTER_MASTER/` — approved character references.
- `PRODUCT_MASTER/ESPRING/` — approved New eSpring references.
- `PRODUCT_MASTER/HYDRO/` — approved HYDRO references.
- `SHOT_REFERENCES/` — separate visual references for individual shots.

### 05_PRODUCTION
- production checklist, approvals, generated media tracking, and final delivery notes.

## Dependency Chain

MASTER_BLUEPRINT
        ↓
VISUAL_BIBLE
        ↓
SHOT_LIST + VOICE_OVER_SCRIPT
        ↓
AI_PROMPT_PACK
        ↓
SHOT_REFERENCES / GENERATED ASSETS
        ↓
VIDEO EDIT

## Synchronization Protocol

Before changing any downstream document:
1. Identify what changed upstream.
2. Check all dependent documents.
3. Update every affected canonical file.
4. Increment revision numbers.
5. Re-check product facts, claims, emotional sequence, CTA, and asset references.
6. Do not generate final production assets while documents conflict.

## Current Locked Concepts

- Food-vs-water logical contrast before the emotional sequence.
- `JERNIH ≠ OTOMATIS AMAN`.
- Child reflection sequence.
- **RELA → TEGA → silence** emotional peak.
- Character Master locked.
- New eSpring Product Master locked.
- HYDRO is treated as condition-based pre-treatment; exact HF model details require source verification.
- Laboratory strategy is `CLAIM → TEST → PROOF`.
- No fabricated laboratory result may be presented as actual.
- WhatsApp contact is in the video description.
- Copyright: Budhi Santoso Pranoto.

## Current Unresolved Items

- Exact HF 4000 / HF 6000 / HF 8000 technical distinctions: verify against official HYDRO catalogue before model-specific claims.
- Hero SPPG Kitchen: not yet locked.
- Final shot references: not yet locked.

## Revision Convention

- Major concept change: 2.0
- Significant structural change: 1.x
- Minor wording/prompt adjustment: 1.x
- Asset replacement: document revision only if the visual rule/reference itself changes.

Never encode revision numbers into canonical filenames.
