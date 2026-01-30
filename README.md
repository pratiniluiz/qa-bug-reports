# QA Bug Reports Portfolio

This repository contains reproducible bug reports created as technical QA
practice using real game builds.  
Each case focuses on clear reproduction steps, impact, and evidence.

---

## Bug Case 01 – Item Entity Collision (Minecraft 1.0)

**Game:** Minecraft Java Edition  
**Version:** 1.0 Release  
**Platform:** Windows 11  
**Mode:** Single-player  

### Description
Reproducible issue where dropped items are not repositioned when blocks
are placed above them, resulting in items becoming trapped and uncollectable.

### Steps to Reproduce
1. Create a 1-block-deep hole
2. Drop items at the bottom
3. Place a non-full solid block (e.g. leaves, glass, slab) above the items

### Expected Result
Dropped items should be pushed out of the block and remain collectable.

### Actual Result
Dropped items remain inside the block and cannot be collected.

### Frequency
Always

### Severity
High

### Evidence
🎥 Video (YouTube – Unlisted):  
[https://youtube.com/XXXXXXXX](https://youtu.be/KlnLpIt_F0U)

### Notes
Occurs with leaves, glass, slabs, chests and ice.  
Does not occur with full solid blocks such as dirt or stone.
