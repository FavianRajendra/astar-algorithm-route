### Updated Text for README.md:

This project implements the A* algorithm using Manhattan distance for pathfinding. To use the code:

1. Scroll to the bottom of the code.
2. Modify the **initial state** and **goal state** based on your needs.
3. Update the **graph** and **heuristic coordinates** as necessary.

For example, change the following lines:

```python
start = 'Magelang'  # Initial state
goal = 'Tawangmangu'  # Goal state
```

You can also adjust the graph and positions dictionary here:

```python
graph = {
    'Yogyakarta': [('Klaten', 45), ('Magelang', 46)],
    # ... (update your graph)
}

positions = {
    'Yogyakarta': (0, 0),
    'Klaten': (30, 10),
    # ... (update your coordinates)
}
```
