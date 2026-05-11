# Student Demographics & Commute Analysis — Power BI

A multi-page interactive Power BI report built for a Montreal school board to analyze student demographics and commute patterns across schools.

![Report Preview](preview.png)

## Overview

This project addresses two core analytical questions:
- **Who are the students?** — demographic breakdown by age, gender, mother tongue, and active status
- **Where do they come from?** — real-world commute distances from student residences to schools

## Technical Highlights

- **Haversine formula in DAX** — implemented geodesic distance calculations to replace inaccurate straight-line estimates, computing real-world distances between student home locations and schools
- **Dynamic Profile Summary** — a context-aware text card that updates based on active slicer selections
- **School vs. board benchmarking** — KPI cards with conditional formatting comparing individual school metrics against board-wide averages
- **Interactive route map** — select any student from the table to visualize their commute route
- **Rule-based color coding** — distance bands color-coded across visuals using Power BI rules

## Pages

| Page | Description |
|---|---|
| Student Demographics Overview | Age, gender, mother tongue, and active status breakdowns |
| Student Commute Analysis | Distance bands, commute map, and furthest student tracking |

## Tools & Skills

Power BI · DAX · Power Query · Data Modeling · Data Visualization

## Notes

Data used in this report is fully synthetic and was created solely for demonstration purposes.
