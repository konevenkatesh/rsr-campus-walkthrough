# RSR Engineering College — 3D Campus Walkthrough

A walkable, in-browser reconstruction of Ramireddy Subbarami Reddy (RSR) Engineering
College, Kavali, SPSR Nellore, Andhra Pradesh (14.7922&deg; N, 79.9984&deg; E).

**Live:** https://konevenkatesh.github.io/rsr-campus-walkthrough/

## Controls

| | |
|---|---|
| `W` `A` `S` `D` | move &middot; mouse or click-drag to look |
| `Shift` | run &middot; `Space` jump |
| `V` | first / third person |
| `E` | open a door &middot; `T` fast travel |
| `N` | time of day &middot; `F` fly |

Stairs climb themselves.

## What's in it

* The main academic block as a **hollow, walkable building** — 79 rooms over 4 levels,
  corridors, internal stairs, and the horseshoe entrance stair
* **Both hostels enterable**, double-loaded plans with furnished rooms
* **263 openable doors**
* **Five labs fitted out** — engineering workshop, chemistry, fluid mechanics &
  hydraulics, electrical machines, computer lab
* Canteen, compound wall and gate, palm avenue, bus parking, volleyball court,
  playground, tree plantation

109k triangles, 1,797 axis-aligned + 2,353 oriented collision boxes, 263 doors.
Single self-contained HTML file — three.js r160 (MIT) is inlined, geometry is
quantised to uint16 and base64'd. No CDN, no build step, works offline.

## How it was made

Modelled from **two published drone photographs** on the college website. Absolute
scale comes from the parked school buses in the aerial (74 px per bus at an assumed
9.0 m bus length). Storey height was cross-checked with a scale-free ratio method —
bay pitch against storey pitch inside one image region, so perspective cancels.

This is a **measured massing model, not a survey**. Façade width carries roughly
&plusmn;12%; hostel and court positions roughly &plusmn;25%.

No college photography is redistributed here — all geometry is vertex-coloured and
carries no image textures.

Not affiliated with or endorsed by the college.
