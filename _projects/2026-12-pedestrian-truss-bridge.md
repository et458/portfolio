---
layout: project
title: Pedestrian Truss Bridge Design
description: ENGRD 2020 design project. A 12 m pedestrian truss bridge, sized for minimum weight with a factor of safety of 2
technologies:
  - Statics (method of joints)
  - Unit-load method for deflection
  - Excel
featured: true
image: /assets/images/truss/model/model-side.jpg
imagealt: Side view of a 1:20 cardboard model of a Pratt truss bridge
---

## 1. Idea Sketches

I looked at three common bridge trusses (Pratt, Howe and Warren) and sketched each one before picking a design.

![Hand sketches of truss ideas]({{ '/assets/images/truss/hand/hand-ideas.jpg' | relative_url }})

---

## 2. Given, Find, Plan and Free-Body Diagrams

My full hand-written method, page by page. I wrote every step in symbols, then put the numbers into Excel.

![Method page 1]({{ '/assets/images/truss/hand/method-01.jpg' | relative_url }})

![Method page 2]({{ '/assets/images/truss/hand/method-02.jpg' | relative_url }})

![Method page 3]({{ '/assets/images/truss/hand/method-03.jpg' | relative_url }})

![Method page 4]({{ '/assets/images/truss/hand/method-04.jpg' | relative_url }})

![Method page 5]({{ '/assets/images/truss/hand/method-05.jpg' | relative_url }})

![Method page 6]({{ '/assets/images/truss/hand/method-06.jpg' | relative_url }})

![Method page 7]({{ '/assets/images/truss/hand/method-07.jpg' | relative_url }})

![Method page 8]({{ '/assets/images/truss/hand/method-08.jpg' | relative_url }})

![Method page 9]({{ '/assets/images/truss/hand/method-09.jpg' | relative_url }})

![Method page 10]({{ '/assets/images/truss/hand/method-10.jpg' | relative_url }})

---

## 3. Excel Calculations

All of the calculations are in one Excel workbook that only uses formulas, so changing an input (height, material, tube size) updates every result: [**Download the design workbook (.xlsx)**]({{ '/assets/files/Truss_Bridge_Design.xlsx' | relative_url }})

---

## 4. Final Design

I went with a **Pratt truss**: 12 m long, **2.0 m tall** and 2.0 m wide, split into 6 panels of 2 m. Each of the two side trusses carries half of the 30 kN load (15 kN). In a Pratt truss the long diagonals are in tension, so they can be thin, and only the top chord, end posts and verticals have to resist buckling. The members are **aluminum 6061-T6 square tubes**, all 2 mm thick:

| Member | Tube size |
|---|---|
| Top chord | 50 × 50 mm |
| End posts | 60 × 60 mm |
| Bottom chord | 20 × 20 mm |
| Diagonals | 20 × 20 mm |
| Verticals | 25 × 25 mm |

| Result | Requirement | My design |
|---|---|---|
| Minimum factor of safety | ≥ 2.0 | **2.16** ✅ |
| Midspan deflection | ≤ 25 mm | **14.8 mm** ✅ |
| Total mass (both trusses) | as low as possible | **59 kg** |

![Hand drawing of the final truss]({{ '/assets/images/truss/hand/hand-final-truss.jpg' | relative_url }})

---

*More coming soon: cardboard model and reflection.*
