# Degrees: Finding the Shortest Path Between Actors

This project implements a search algorithm to find the shortest "degree of separation" between any two actors using the IMDb dataset. The challenge is to model the network of actors and movies as a graph and then use an efficient algorithm to find the shortest path between any two nodes.

This project was developed as part of Harvard's CS50's Introduction to Artificial Intelligence with Python course.

## Demo

Below is a sample run to find the connection between Tom Hanks and Kevin Bacon:

![Loading data... Data loaded. Name: Tom Hanks ID: 102, Name: Tom Hanks, Birth: 1956 Name: Kevin Bacon ID: 102, Name: Kevin Bacon, Birth: 1958 2 degrees of separation. 1: Tom Hanks and Gary Sinise starred in Apollo 13 2: Gary Sinise and Kevin Bacon starred in Apollo 13](democs50degrees.png)

*(Tip: Run the program in your terminal, take a screenshot of the output, and replace this text block with your image!)*

## Concepts and Technologies

- **Python**
- **Data Structures:** Modeling the problem using **Graphs**.
- **Algorithm:** Implementation of **Breadth-First Search (BFS)** to guarantee the shortest path.
- **Data Handling:** Loading, parsing, and structuring data from CSV files.

## 🚀 How to Run This Project

1.  **Clone the repository** (if you haven't already).
2.  **Navigate to the project folder.**
3.  **Run the program** from your terminal, specifying the data directory (`small` or `large`):
    ```bash
    python degrees.py large
    ```
4.  Follow the prompts in the terminal to enter the names of the two actors.

## Project Structure

- **`degrees.py`**: Contains the main logic for the search algorithm (`shortest_path`) and the code to interact with the user.
- **`util.py`**: Provides the helper data structures `Node`, `StackFrontier`, and `QueueFrontier`.
- **`/large` & `/small`**: Directories containing the IMDb datasets.
