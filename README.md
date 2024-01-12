Dijkstra's Shortest Path Implementation
Overview
This Python implementation demonstrates the efficiency of Dijkstra's algorithm, providing a powerful tool for finding the shortest path between nodes in a graph. This project is ideal for applications in route planning and network optimization.

Features
Interactive Input: Easily define distances between specified vertices through interactive user input.
Priority Queue Optimization: Utilizes the heapq module for efficient priority queue operations, enhancing overall algorithm performance.
Optimal Path Extraction: The implementation includes a mechanism to extract and analyze the optimal path between nodes.
Versatile and Adaptable: Designed to handle various graph scenarios, making it a flexible solution for different use cases.
Usage
Clone the repository: git clone [repository-url]
Navigate to the project directory: cd dijkstra-shortest-path
Run the script: python dijkstra.py
Input
Follow the prompts to enter distances for the specified connections when running the script.

Example
python
Copy code

# Define connections

connections = ['AB','AD', 'BD', 'BE', 'EF', 'FC', 'EC', 'DE', 'DF']

# Enter distances interactively

# ...

# Run Dijkstra's algorithm

# ...

# Display results

# ...

Performance
Time Complexity: O((V + E) log V)
Space Complexity: O(V)
