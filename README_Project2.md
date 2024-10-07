
# **Project 2: Gossip and Push-Sum Algorithm Simulations**

## **Team Members**
- **Sneha Edupuganti**
- **Varshini Kopparla**

## **What is Working**
- **Implementation of Gossip Algorithm** for information propagation.
- **Implementation of Push-Sum Algorithm** for sum computation.
- **Experimentation** with the following topologies:
  - Full Network
  - 3D Grid
  - Line
  - Imperfect 3D Grid
- **Measurement of convergence times** for each topology and algorithm.
- **Generation of dependency graphs** for convergence time vs number of nodes.

## **Largest Network Tested**
- **Full Network:** 10,000 nodes
- **3D Grid:** 10,000 nodes
- **Line Topology:** 10,000 nodes
- **Imperfect 3D Grid:** 10,000 nodes

## **Instructions to Run the Project**
**Input:** The input provided (as command line to your project2) will be of the form:
```
./ponyproject_2.exe <numNodes> <topology> <algorithm>
```
Where:
- `numNodes`: Number of actors involved.
- `topology`: One of `full`, `3D`, `line`, `imp3D`.
- `algorithm`: One of `gossip`, `push-sum`.

Example:
```
./ponyproject_2.exe 10000 full gossip
```

**Output:** The program will print the amount of time it took to achieve convergence of the algorithm.

## **Requirements**
- **The project is implemented exclusively using actors in Pony.**
- **The program uses System.currentTimeMillis to measure convergence time.**
