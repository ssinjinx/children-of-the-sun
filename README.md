# Children of the Sun

A book project managed with the Book Production Pipeline.

## Project Status

**Current Phase:** 2 - Development (Complete)  
**Next Action:** Move to Phase 3 - Drafting

## Series Information

**Book:** 2 of the Shetu Chronicles  
**Preceded by:** Slave to the Gods  
**Working Title:** Children of the Sun  
**Target Length:** 90,000 words  
**Genre:** Dark Fantasy / Mythological Romance

**Format:** Continuous manuscript (no chapters) — scene breaks only

## The Story

Two years after the revolution, Ra and Issah face their greatest challenge yet: parenthood. Their child is the first human-Shetu hybrid, and everyone wants to control them. As the old world burns and a new one struggles to be born, Ra must make the ultimate sacrifice to protect his family.

## Quick Links

- [Ideation](book-bible/01-ideation.md)
- [Characters](book-bible/02a-characters.md)
- [World](book-bible/02b-world.md)
- [Outline](book-bible/02c-outline.md)
- [Draft Status](book-bible/03-draft-status.md)

## Directory Structure

```
.
├── book-bible/          # Planning documents
│   ├── 01-ideation.md
│   ├── 02a-characters.md
│   ├── 02b-world.md
│   ├── 02c-outline.md
│   └── 03-draft-status.md
├── sections/            # Draft sections (for organization only)
├── manuscript/          # Final continuous manuscript (no chapters)
├── story-bible/         # Character deep dives from Book 1
├── world-building/      # World bible from Book 1
├── .learnings/          # Consistency tracking
├── production/          # Output files (ebook, audiobook)
└── README.md            # This file
```

**Note:** This book is written as a continuous narrative. The "sections" folder is for drafting organization only. Final manuscript has no chapter headings — just scene breaks (`***`) for transitions.

## Development Complete

✅ Phase 1: Ideation — Core concept, themes, hook  
✅ Phase 2A: Characters — Returning and new cast  
✅ Phase 2B: World — Post-revolution Egypt, hybrid biology  
✅ Phase 2C: Outline — 28-section structure with arcs  

## Next Steps

1. **Phase 3: Drafting** — Write sections 1-28 as continuous prose
2. Use Arcee AI model for generation
3. Track progress in 03-draft-status.md
4. Update .learnings/ with new details
5. Merge sections into single manuscript file

## Scripts

```bash
# Check project status
python3 ~/.openclaw/workspace/skills/book-production-pipeline/scripts/status_check.py /path/to/children-of-the-sun

# Generate audiobook (when manuscript is ready)
python3 ~/.openclaw/workspace/skills/book-production-pipeline/scripts/audiobook_generator.py \
    --manuscript manuscript/children-of-the-sun.md \
    --output production/audiobook/
```

## License

All content © 2026. All rights reserved.

---

*"The light of the gods is fading. But new lights are being lit."*
