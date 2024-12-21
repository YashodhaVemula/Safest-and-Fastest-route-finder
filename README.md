# Safest-and-Fastest-route-finder
An intelligent navigation system designed to recommend shortest and safest routes within South Bangalore. This project incorporates graph-based algorithms and machine learning to identify optimal paths based on user preferences, including safety features influenced by real-world factors such as crime hotspots, streetlight availability, and crowd density.

Features 💡
  Shortest Path Calculation: Computes the shortest path between a source and destination using Dijkstra's algorithm.
  Safety-Aware Navigation: Includes safety scores derived from crowd-sourced data like streetlight availability, crowd density, and reported incidents.
  Interactive User Input: Users can select routes with or without the safety feature.
  Dynamic Subgraph Creation: Optimized route finding using a localized subgraph of the map.

Technologies Used 🛠️
  Python: Core programming language for logic and algorithms.
  OSMNx: For extracting and analyzing OpenStreetMap data.
  NetworkX: For graph creation and pathfinding.
  Numpy & Pandas: For data manipulation and preprocessing.
  Matplotlib: For visualizing routes (if applicable).

Sample Output 🖥️
  Input: Starting Location: Jayanagar, Destination: Hosakerehalli, Safety Feature: Yes.
  Output: Shortest and safest route details, including step-by-step navigation and distance metrics.

Project Architecture 🏗️
  Data Collection: Uses OpenStreetMap data and crowd-sourced information for safety scoring.
  Graph Construction: Builds road networks with nodes and edges based on geographical data.
  Pathfinding Algorithms: Implements Dijkstra's algorithm for route computation.
  Safety Scoring: Combines safety factors to prioritize safer routes.
  
Future Enhancements 🔮
  Integration with real-time traffic and safety updates.
  Support for multimodal navigation (e.g., public transport).
  Implementation of AR-based navigation interfaces.
  Expansion to other geographical regions.




