# Fractal Tree Visualization

A Java application that generates and visualizes fractal trees using the JavaFX framework. This project demonstrates the use of object-oriented programming (OOP) principles and recursion to create interactive and complex fractal tree patterns. Users can adjust parameters like depth, angle, and branch length to explore different fractal structures in real time.

## Features

- **Interactive UI**: Built with JavaFX, allowing users to adjust tree parameters and view changes instantly.
- **Object-Oriented Design**: Classes represent different components of the fractal tree, enhancing code modularity and reusability.
- **Recursive Tree Generation**: Utilizes recursive algorithms to draw realistic branching patterns.
- **Dynamic Customization**: Users can modify tree depth, branch angle, and color settings to create unique visualizations.

## Technologies Used

- **Java**: Core language for logic and functionality.
- **JavaFX**: Framework for building the graphical user interface.
- **OOP**: Object-oriented principles to structure the application, encapsulating tree and branch behaviors in dedicated classes.

## Getting Started

### Prerequisites

- Java 11 or higher
- JavaFX SDK (if not bundled with your Java version)

### Installation

1. Clone the repository:
   ```bash
   https://github.com/MinhTran1506/fractal_tree.git
   ```
2. Import the project into your favorite Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Make sure to configure JavaFX libraries if your IDE doesn’t include them by default.

### Running the Application
1. Navigate to the main class (FractalTreeApp.java) and run it.
2. Adjust parameters in the UI to see the fractal tree grow and change!

## How It Works
The fractal tree is drawn using a recursive algorithm, where each branch generates two child branches with adjustable angles and lengths. This approach mimics natural tree growth patterns.

Key classes include:
- __Tree__: Manages the fractal tree structure and recursive branching logic.
- __Branch__: Represents individual branches in the tree, including properties like length, angle, and color.


