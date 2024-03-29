# Dijkstra Visualization

![Game screenshot](https://imgur.com/GpQizxc.png)
## About
<p align="center">
  <b>Dijkstra's Shortest Path First algorithm implementation</b><br>
  <a href="https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm"><img src="https://upload.wikimedia.org/wikipedia/commons/5/57/Dijkstra_Animation.gif"></a>
</p>

[GameOn Production](https://www.gameonproduction.com/) test task source code

This project is an implementation of the [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm) and also my dive into developing tools under Unity Editor API


## Installation
1. [Download](https://github.com/cornflux-cmd/dijkstra-visualization/releases/latest) the latest version of the package
2. Import the package into your project
3. See [Usage](#usage)

## Usage
### Editor
1. Create your own **Graph** by dragging its prefab onto the scene or use *Demo* scene
2. Drag **Vertices** prefab onto the **Graph** in Hierarchy, making them its children
3. Connect the **Vertices'** by specifying connections in each **Vertex's** corresponding component  
**Note:** you only need to connect **Vertices** ONCE, algorithm will sync all pairs
4. Under **Shortest Path** component on the **Graph** specify *Start* and *Finish* vertices
5. The **Shortest Path** will be highlighted with Green color, starting *Edge* will be marked Red  
**Note:** if you want to unpair the **Vertices** (remove an *Edge* from the **Graph**), you have to remove both of them from each other's connections list

### Runtime
Not yet fully supported, try at your own risk

*Visual design inspired by [EmpireWorld's implementation](https://github.com/EmpireWorld/unity-dijkstras-pathfinding)*
