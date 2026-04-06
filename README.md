# Analog IC Layout Journey

## Disclaimer
All content in this repository is based on personal learning, academic study, and publicly available knowledge.  
No proprietary, confidential, or company-specific information is included.  

Any designs, examples, or layouts shared here are independently created for educational purposes only.

---

## About
Documenting my journey in analog IC layout design, focusing on clean, matching-aware layouts and understanding how physical implementation impacts circuit behavior.

---

## Focus
- Matching (common-centroid, interdigitation)
- LDE awareness (WPE, LOD)
- Parasitic-aware routing (RC effects)
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
CMOS processing and short channel effects (SCE), and their impact on device behavior.

#### Key Takeaways
- W/L is not only an electrical parameter, but also a physical layout constraint  
- Short channel devices are highly sensitive to process variations  
- Layout must consider parasitics, matching, and LDE effects  

#### My Understanding
Short channel effects are not only device-level concerns.  
They directly influence layout decisions, especially in analog design.  

Using minimum channel length reduces area but increases sensitivity to variation and mismatch.  
For critical analog blocks, longer channel lengths provide more robust matching and layout tolerance.

#### If I Were Designing
For a differential pair:
- I would avoid minimum channel length to reduce mismatch sensitivity  
- I would enforce strict symmetry in device placement  
- I would use common-centroid structures when needed  
- I would consider device environment (edges, proximity → LDE effects)  

#### Questions I’m Investigating
- How does increasing channel length affect mismatch and variability in practice?  
- What is the trade-off between area, parasitics, and matching quality?  
- How do LDE effects (WPE, LOD) vary with device placement?  

---

### Week 2
- (to be updated)

---

## Goal
To build high-quality analog layouts with strong awareness of matching, parasitics, and manufacturability.
