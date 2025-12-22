
<img width="919" height="844" alt="{64024C97-DAFD-4E4E-959C-D2FF7E9639F5}" src="https://github.com/user-attachments/assets/17995ccf-0279-4614-895a-862fa6271d0f" />

# Automated Warehouse Sorting and Routing System

This project simulates an automated warehouse robot system that sorts and routes items based on priority. It visualizes robots navigating a grid-based warehouse, picking up items, and delivering them to designated locations while avoiding obstacles and handling random failures.

## Features

*   **Robot Simulation:** Robots with battery levels, movement states (Idle, Moving, Picking, Dropping), and random failure simulation.
*   **Warehouse Layout:** A 2D grid layout with aisles, storage shelves, and loading zones.
*   **Task Scheduling:** Assigns tasks to robots based on item priority (Urgent vs. Regular).
*   **Path Optimization:** Uses the A* algorithm for shortest path finding.
*   **Real-Time Visualization:** Uses `matplotlib` to animate the simulation, showing robots, items, paths, and status updates.
*   **Edge Cases:** Simulates robot breakdowns and self-repair attempts.

## Requirements

*   Python 3.x
*   `numpy`
*   `matplotlib`

## Installation

1.  Clone the repository or download the source code.
2.  Install the required dependencies:

    ```bash
    pip install numpy matplotlib
    ```

## Usage

Run the simulation script:

```bash
python robot_simulation.py
```

## Simulation Details

*   **Blue Circles:** Active Robots.
*   **Red Circles:** Broken Robots.
*   **Orange Squares:** Urgent Items.
*   **Green Squares:** Regular Items.
*   **Yellow Lines:** Planned paths for robots.
*   **Black Blocks:** Shelves/Obstacles.

The simulation runs for a set number of frames. You can adjust parameters like `GRID_SIZE`, `NUM_ROBOTS`, and `NUM_ITEMS` in the `robot_simulation.py` file.
