# Closest Pair Problem Using Divide and Conquer

This repository contains a Python implementation of the **Closest Pair Problem** using the **Divide and Conquer** approach. The algorithm efficiently finds the pair of points in a 2D plane that are closest to each other by recursively dividing the points into smaller subsets and merging them.

## Algorithm Breakdown:
1. **Mergesort**: First, the set of points is sorted based on the x and y coordinates using mergesort.
2. **Divide and Conquer**: The sorted points are divided into two subsets, and the closest pair is found recursively.
3. **Brute Force for Base Case**: For small subsets (size <= 3), the closest pair is found using brute force.
4. **Efficient Checking for Split**: The algorithm checks for pairs of points that cross the dividing line.

## Results:
- The closest pair of points is found, and their Euclidean distance is calculated.
- A plot is generated to visualize the points and the closest pair.

## Example Output:
The algorithm will print the distance and the two closest points in the set, as well as a plot showing the points and the closest pair.

## Requirements:
- Python 3.x
- `matplotlib` library for plotting

## How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/closest_pair_problem.git
2. Run the script:
   ```bash
   python closest_pair_using_divide_and_conquer.py
