# Trémaux's Algorithm Simulator

An interactive web-based simulator demonstrating **Trémaux's Algorithm**, a classical maze-solving method invented by Charles Pierre Trémaux.  
This app provides a visual and step-by-step explanation of how the algorithm works, allowing users to explore different maze layouts and understand the traversal process.

---

## 🚀 Features
- **Multiple Maze Templates**: Choose from 20+ predefined mazes (e.g., Simple Cross, Classic Maze, Zig-Zag, Labyrinth, etc.).
- **Interactive Controls**:
  - Select maze layout
  - Choose a starting position by clicking on the maze
  - Start the simulation automatically
  - Step through the algorithm one move at a time
  - Reset and try again
- **Visual Feedback**:
  - **Walls** (dark blocks)
  - **Unvisited paths** (light blocks)
  - **Current position** (red marker)
  - **Visited once** (blue rectangle outline)
  - **Visited twice** (orange cross mark)
- **Algorithm Explanation Panel**: Step-by-step rules, status updates, and legend.

---

## 📖 About Trémaux's Algorithm
Trémaux's algorithm is a guaranteed maze-solving method that:
1. Marks each passage upon first visit.
2. Prefers unvisited paths, then once-visited paths if necessary.
3. Avoids passages visited twice unless no other choice exists.
4. Backtracks when dead ends are encountered (marking paths as visited twice).
5. Eventually finds an exit (if one exists).

**Note**: This method always guarantees an escape but not the shortest path.

---

## 🛠️ Getting Started

### Prerequisites
- A modern browser (Chrome, Firefox, Edge, Safari)
- No server required — this is a pure **HTML, CSS, JavaScript** app.

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/tremaux-maze-simulator.git
    ```
2. Navigate into the project folder:
   ```bash
   cd tremaux-maze-simulator
   ```
3. Open index.html in your browser:


## 🎮 Usage

1. Select a maze from the dropdown menu.

2. Click on the maze to set the starting position.

3. Use the controls:
   ```bash
   Start Algorithm Demo → Runs the full simulation
   Move Step Forward → Manually step through each move
   Reset → Restart and pick a new maze/starting point
   ```

4. Observe how Trémaux’s algorithm solves the maze step by step.
   

## 🧩 Example Mazes

- Simple Cross
- Classic Maze 1 & 2
- Multiple Paths
- Dead End Trap
- Concentric Rings
- Zig Zag Path
- Checkerboard with Passages
- The Serpent’s Coil
- The Gridlock
- The Cloverleaf
- and more...


## 📸 Screenshots

Some screenshots of the demo 
[Pic 1](Demo1.png)

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.


## 👨‍💻 Author

Developed by [Bhaumik Yadav](https://www.linkedin.com/in/theprofessional-bhaumik-yadav/) 

✨ Inspired by Charles Pierre Trémaux’s classical maze-solving algorithm.
