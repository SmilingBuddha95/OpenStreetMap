OpenStreetMap Project - README
# OpenStreetMap Pathfinding Project
This repository contains the implementation of the A* search algorithm as part of the Udacity C++ Nanodegree. The project demonstrates how to find the shortest path between two points on a map using OpenStreetMap data.
## Project Files
1. **main.cpp**:
- Entry point of the application.
- Initializes the project, loads OpenStreetMap data, and runs the A* search algorithm.
2. **model.cpp & model.h**:
- Defines the Model class responsible for parsing OpenStreetMap data. - Handles the data structures that represent the map (nodes and ways).
3. **render.cpp & render.h**:
- Manages rendering of the map and path visualization.
- Ensures graphical representation for validating the pathfinding process.
4. **route_model.cpp & route_model.h**:
- Extends the Model class with route-planning features. - Supports node searching and A* implementation.
5. **route_planner.cpp & route_planner.h**:
- Implements the A* search algorithm.
- Handles heuristic calculations, node expansions, and finalizing the path.
## How to Run the Project
### Prerequisites
- C++17 compliant compiler (GCC or Clang) - CMake for building the project
### Steps
1. Clone the repository:
```
git clone https://github.com/SmilingBuddha95/OpenStreetMap.git cd OpenStreetMap
```
2. Build the project: ```
mkdir build cd build cmake .. make
```
3. Run the executable:
``` ./pathfinder

```
### Input Data
- Requires OpenStreetMap data in XML format. Sample map files can be downloaded from the OpenStreetMap website.
## Future Enhancements
- Performance optimization of A* algorithm.
- Implementation of alternative algorithms for comparison.
## License
This project is licensed under the MIT License.
