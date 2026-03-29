# Course Planner & Campus Route Finder

A menu-driven C application. It combines two graph-based features: finding the shortest path between campus buildings using Dijkstra's algorithm, and sorting computer engineering courses by their prerequisites using topological sort.

## How It Was Made

Written in C. The campus map is loaded from a file and represented as a graph (adjacency matrix or adjacency list). Dijkstra's algorithm is then run on the graph to find the shortest path between any two buildings. The course prerequisite data is loaded separately and modeled as a directed acyclic graph, which is then sorted topologically to produce a valid course-taking order.

## Features

- Load campus building distances from `input_buildings.txt` and course prerequisites from `input_courses.txt`
- Find and print the shortest route between two buildings along with the total distance
- Sort courses into a valid study order using topological sort
- Print the topologically sorted course list
