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

<div style="display:flex; gap:12px; overflow-x:auto; scroll-snap-type:x mandatory; padding-bottom:8px;">
  <img src="{{ '/assets/images/truss/hand/method-01.jpg' | relative_url }}" alt="Method page 1 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-02.jpg' | relative_url }}" alt="Method page 2 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-03.jpg' | relative_url }}" alt="Method page 3 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-04.jpg' | relative_url }}" alt="Method page 4 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-05.jpg' | relative_url }}" alt="Method page 5 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-06.jpg' | relative_url }}" alt="Method page 6 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-07.jpg' | relative_url }}" alt="Method page 7 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-08.jpg' | relative_url }}" alt="Method page 8 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-09.jpg' | relative_url }}" alt="Method page 9 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
  <img src="{{ '/assets/images/truss/hand/method-10.jpg' | relative_url }}" alt="Method page 10 of 10" style="flex:0 0 60%; max-width:60%; scroll-snap-align:center; border:1px solid #ccc;">
</div>

*Pages 1–10: scroll or swipe sideways →*

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

## 5. Cardboard Model

I built a 1:20 scale cardboard model of the final truss. At that scale the 12 m span is 60 cm and the 2 m height is 10 cm. It shows the shape and member layout and was not load tested.

<video controls muted playsinline width="360" src="{{ '/assets/videos/model-walkaround.mp4' | relative_url }}"></video>

![Model side view]({{ '/assets/images/truss/model/model-side.jpg' | relative_url }})

![Model front view]({{ '/assets/images/truss/model/model-front.jpg' | relative_url }})

![Model top view]({{ '/assets/images/truss/model/model-top.jpg' | relative_url }})

---

## 6. Reflection

This project was hard to get started on, but once I got going and made a few mistakes, it started to click. I began by looking up truss designs online and picking three familiar ones (Pratt, Howe and Warren), then chose two main materials, steel and aluminum, to compare. Using Excel the way we learned in class made the rest much simpler. I could set up every equation with formulas and let the spreadsheet do the math, which made it easy to test different heights, materials and tube sizes. The trickiest part was the drawings and making sure my trusses were correct, especially getting every FBD and force direction right before trusting the numbers.

I really enjoyed building the cardboard model. It's precisely to scale (1:20), and it helped me visualise what was happening in the structure: which members are squeezed and which are pulled. The hardest part of the build was keeping everything perfectly aligned. If I did this again, I would load-test the model to compare it with my calculations.

---

## AI Usage Statement

*To be completed.*
