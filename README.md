# 1:64 Multi-Stage Spur Gear Gearbox

> **Gear Design · Drivetrain Engineering · FDM Manufacturing · Built & Wired**

Design and complete physical build of a compact multi-stage spur gear gearbox achieving an overall 1:64 reduction ratio, housed in a FDM-printed enclosure and wired with a DC motor. Built to drive a scaled conveyor platform for vehicle testing applications.

---

## Project Overview

| Item | Detail |
|---|---|
| **Gear Type** | Spur gears, multi-stage |
| **Overall Ratio** | 1:64 |
| **Housing** | FDM 3D printed (PLA) |
| **Drive** | DC motor, wired and operational |
| **Application** | Scaled conveyor platform for vehicle testing |
| **Status** | Fully built and functional |

---

## Design Approach

A 1:64 reduction in a compact envelope requires multiple gear stages — each contributing a partial reduction. Stages are stacked to achieve the target ratio without impractically large or small gears. The housing was designed around the gear train, printed in two halves, and fastened with screws through the four corner bosses visible in the photos.

### Architecture

- Multi-stage spur gear train — stages in series
- Each stage ratio selected to balance tooth count, center distances, and load sharing
- Shaft layout minimises moment arm loads on the printed housing walls
- Output shaft protrudes from the top face for conveyor attachment

---

## Gallery

| CAD — Exploded Assembly | CAD — Gear Train Detail |
|---|---|
| ![Exploded](images/WhatsApp%20Image%202026-05-02%20at%2016.57.46%20(2).jpeg) | ![Gear train](images/WhatsApp%20Image%202026-05-02%20at%2016.57.46.jpeg) |

| Built — Front Face | Built — Output Shaft & Wired |
|---|---|
| ![Front](images/WhatsApp%20Image%202026-05-02%20at%2018.48.38.jpeg) | ![Output](images/WhatsApp%20Image%202026-05-02%20at%2018.48.39.jpeg) |

---

## Key Engineering Decisions

- **Module and tooth count** selected for standard tooling compatibility
- **Lewis bending equation** used for tooth stress verification at each stage
- **Center distance** calculated to ensure correct mesh and controlled backlash
- **Housing printed in halves** for gear installation access — bolted shut after assembly
- **Efficiency estimate**: ~96–97% per stage → ~85–88% total across all stages

---

## Skills Demonstrated

`Gear Design` `Drivetrain Engineering` `SolidWorks` `FDM 3D Printing` `Mechanical Calculations` `Assembly & Build` `DC Motor Integration` `Tolerance & Fit`
