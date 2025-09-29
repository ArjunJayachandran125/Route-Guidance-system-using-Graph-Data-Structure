# Route Guidance System 

## Overview
This project implements a **Route Guidance System** using **Dijkstra’s shortest path algorithm**.  
It simulates how navigation systems (like Google Maps) calculate the shortest route between locations in a road network.

## Features
- Graph implemented with **adjacency lists**
- Efficient pathfinding using **Dijkstra’s algorithm** (O(E log V))
- Example road network provided in `main.cpp`
- Outputs shortest distance from a **source node** to all other nodes

## Tech Stack
- **C++**
- Graph Data Structures
- STL Priority Queue (min-heap)

## How It Works
1. The road network is represented as a weighted graph.  
2. Each edge corresponds to a road segment with distance as weight.

## Applications
- GPS navigation systems  
- Network routing  
- Logistics & transportation optimization 
