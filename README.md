# MDA5+ DM AI Workspace

**Owner:** Alex Corbiere  
**Purpose:** Shared working environment for Claude and Gemini to collaborate on medical, legal, and administrative workstreams while maintaining continuity across sessions and devices.

## Quick Start for AIs

1. **Read `HANDOVER.md` first** — contains full patient context, active workstreams, key people, and critical safety information
2. **Check your instructions** — `INSTRUCTIONS/claude.md` or `INSTRUCTIONS/gemini.md`
3. **Check `TIMELINE.md`** — for upcoming deadlines and appointments
4. **Review recent work** — check your `ANALYSIS/` folder and the other AI's folder for context
5. **Propose changes properly** — any edits to shared docs go through `PENDING/`

## File Structure

```
├── README.md                    # This file
├── HANDOVER.md                  # Master context document
├── INSTRUCTIONS/
│   ├── claude.md                # Claude-specific instructions
│   └── gemini.md                # Gemini-specific instructions
├── ANALYSIS/
│   ├── claude/                  # Claude's analysis outputs
│   │   └── .gitkeep
│   └── gemini/                  # Gemini's analysis outputs
│       └── .gitkeep
├── PENDING/
│   └── proposed-edits.md        # Proposed changes awaiting approval
└── TIMELINE.md                  # Key dates, deadlines, appointments
```

## Rules

1. **No direct edits to HANDOVER.md** — propose changes in PENDING/proposed-edits.md
2. **Alex approves all changes** — nothing gets merged without his review
3. **Own your analysis folder** — put your outputs in your designated folder
4. **Read the other AI's work** — avoid duplicating effort
5. **Flag disagreements explicitly** — if you disagree with the other AI's analysis, document why
6. **State confidence levels** — established mechanism / plausible hypothesis / speculative inference

## How to Access This Repo

**Claude:** Use `web_fetch` on raw GitHub URLs  
**Gemini:** Native GitHub/Drive integration or paste URLs

Raw file URL pattern:
```
https://raw.githubusercontent.com/[username]/mda5-dm-ai-workspace/main/[filepath]
```

## Critical Context

Alex has autism and ADHD. When he's impaired:
- Shorter messages, slower responses
- May not catch errors
- The handover doc needs to work without him explaining anything

This system exists so either AI can pick up cold and be useful immediately.

---
*Last updated: 2026-04-10*
