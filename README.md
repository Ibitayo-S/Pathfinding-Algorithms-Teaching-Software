# Pathfinding Algorithms Teaching Software

An interactive tool for teaching Dijkstra's and A* pathfinding algorithms, built as an A-Level Computer Science NEA (Non-Exam Assessment) project.

## Overview

This project visualises how Dijkstra's algorithm and A* find the shortest path through a graph, so students can see the algorithm's decision-making step by step rather than just reading pseudocode. It was trialled with over 600 students at Caistor Grammar School, with over 90% reporting improved understanding of the algorithm.

## Features

- Step-by-step visualisation of Dijkstra's algorithm and A* search
- Dynamic generation of adjacency matrices from user-defined parameters, so graphs can be created on the fly rather than hardcoded
- Route calculation and comparison on real-world map data, letting users see how algorithm efficiency differs between Dijkstra's and A*
- CSV-based data handling (via Pandas) for storing and querying route calculation results
- Statistics tracking to compare algorithm performance across runs

## Tech Stack

- Python
- Matplotlib (visualisation and animation)
- Pandas (CSV data handling and querying)
- NumPy (numerical computation)
- OSMnx (real-world street network and map data)

## Project Structure

```
MainMenu.py                        # Entry point and main menu
Algorithms.py                      # Dijkstra's and A* implementations
Animation.py                       # Visualisation and animation logic
NetworkGenerator.py                # Generates adjacency matrices / graphs from parameters
DijkstrasDemonstrationWindow.py    # UI window for the Dijkstra's demonstration
MapDemonstrationWindow.py          # UI window for real-world map path comparison
DataStructures.py                  # Core data structures used by the algorithms
Forms.py                           # UI forms/input handling
Statistics.py                      # Tracks and compares algorithm performance
Utilities.py                       # Shared helper functions
```

## Getting Started

### Prerequisites

- Python 3.x
- pip

### Installation

```bash
git clone https://github.com/Ibitayo-S/Pathfinding-Algorithms-Teaching-Software.git
cd Pathfinding-Algorithms-Teaching-Software
pip install matplotlib pandas numpy osmnx
```

### Running

```bash
python MainMenu.py
```

## Background

This was built as a Computer Science NEA project, then extended and deployed as a teaching aid in a school setting. It was designed for students with no prior algorithms background, so the visualisation prioritises clarity over performance.

## License

Open source and available for anyone to explore, use, or build on.
