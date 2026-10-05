# 🗺️ Telangana District Map Coloring Using Graph Coloring

## Project Overview
This project implements the Map Coloring Problem for the districts of Telangana.

The objective is to assign colors to districts so that two neighboring districts do not have the same color.

The problem is modeled as a graph:
- Districts → vertices
- Shared boundaries → edges
- Colors → vertex labels

## Objectives
- Understand graph coloring.
- Represent Telangana districts as graph vertices.
- Represent neighboring districts as edges.
- Assign valid colors.
- Validate the coloring.
- Visualize the result.

## Technologies
- Python
- Google Colab
- NetworkX
- Matplotlib
- Pandas
- NumPy

## Problem Definition
For every pair of neighboring districts:

**Color(District A) ≠ Color(District B)**

The goal is to color all districts while satisfying this constraint.

## Algorithm
A backtracking graph-coloring approach can be used:
1. Select an uncolored district.
2. Try an available color.
3. Check all colored neighbors.
4. Assign the color if no conflict exists.
5. Otherwise try another color.
6. Backtrack when no color is possible.
7. Continue until all districts are colored.

## Methodology
1. Define the districts.
2. Define district adjacency.
3. Create the graph.
4. Define available colors.
5. Apply the coloring algorithm.
6. Validate every neighboring pair.
7. Display the colored graph/map.

## Output
The notebook produces:
- District list
- Adjacency relationships
- Assigned colors
- Validation results
- Graph/map visualization

## Applications
Graph coloring is useful in:
- Map coloring
- Timetable scheduling
- Examination scheduling
- Frequency assignment
- Register allocation
- Resource allocation

## Limitations
A graph visualization may not reproduce the exact geographical shapes of Telangana districts. Accurate GIS boundary data is required for a true geographic map.

## Future Scope
- Use actual district shapefiles.
- Use GeoPandas.
- Create interactive maps.
- Minimize the number of colors.
- Implement constraint-satisfaction techniques.

## Conclusion
The project demonstrates how a geographical problem can be transformed into a graph-coloring problem and solved using Artificial Intelligence and graph theory.

## How to Run
1. Open the notebook in Google Colab.
2. Import required libraries.
3. Define districts and adjacency.
4. Build the graph.
5. Run the coloring algorithm.
6. Validate the solution.
7. Display the final visualization.
