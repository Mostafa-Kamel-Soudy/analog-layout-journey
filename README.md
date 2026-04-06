# Analog IC Layout Journey

## Disclaimer
All content in this repository is based on personal learning, academic study, and publicly available knowledge.  
No proprietary, confidential, or company-specific information is included.  

Any designs, examples, or layouts shared here are independently created for educational purposes only.

---

## About
Documenting my journey in analog IC layout design, focusing on clean, matching-aware layouts and their impact on circuit performance.

---

## Focus
- Matching (common-centroid, interdigitation)
- LDE awareness (WPE, LOD)
- Parasitic-aware routing
- Symmetry-driven layout
- Clean DRC/LVS

---

## Tools
- Cadence Virtuoso  
- Synopsys Custom Compiler  
- Mentor Calibre  

---

## Progress

### Week 1 – CMOS & Short Channel Effects

#### Topics Covered
CMOS processing and short channel effects (SCE), and their impact on analog performance.

#### Key Takeaways
- W/L directly affects gain, speed, and matching  
- SCE degrades analog performance (gain, matching)  
- Layout must account for process variations and LDE  

#### My Understanding
Short channel effects are not only device-level concerns.  
They strongly influence layout decisions in analog design.  

Using minimum channel length improves speed but degrades matching and gain.  
For critical analog blocks, longer channel lengths are often preferred.

#### If I Were Designing
For a differential pair:
- Avoid minimum channel length for better matching  
- Use symmetry and common-centroid placement  
- Consider LDE effects near edges  

#### Questions I’m Investigating
- How much does increasing channel length improve matching in practice?  
- What is the real trade-off between area and performance?  
- How do LDE effects vary across layout positions?  

---

### Week 2
- (to be updated)

---

## Goal
To build high-quality analog layouts and grow into a high-performance Analog IC Layout Engineer.
