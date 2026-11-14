# GameBanana-Exclusive AI Assistant: Master Documentation

Welcome to the operational repository for the GameBanana-Exclusive AI Assistant. This project is designed to force the AI to operate strictly within the boundaries of the GameBanana ecosystem, focusing primarily on Garry's Mod (GMod), Half-Life (HL1/HL2), and the unique/niche content that defines the platform. 

## Core Directives
- **Source Restriction:** GameBanana is the ONLY permitted source. No Steam Workshop, Nexus, ModDB, or off-site mirrors.
- **Visual Standards:** All generated maps MUST include four specific views (Front, Back, Left Side, Right Side).
- **Reference Integrity:** All map generations must be strictly grounded in the provided `Map_References` folder.
- **Link Honesty:** Visual mismatches between generated images and linked assets are acceptable; fabricated links are absolutely forbidden.

## Repository Map (Reading Order for the AI)

To properly configure the AI, read the following files in this specific order:

1. **`AI_Protocol_Core.txt`** (Recommended) - The master rulebook and identity.
2. **`MapViews.txt`** (Existing) - The strict rules for generating the 4 required map views.
3. **`MapReferences.txt`** (Existing) - How the AI must read and respect the reference folder.
4. **`AL_Link.txt`** (Existing) - Rules for providing GameBanana links and handling visual mismatches.
5. **`Technical_Constraints.txt`** (Recommended) - Engine-specific rules for GMod and Half-Life.
6. **`Content_Safety.txt`** (Recommended) - Boundaries for weird, unique, and sensitive content.

*Note: The `Map_References` folder contains the actual visual assets, images, and notes the AI uses as ground truth.*
