# Distributed_computing
Conpents and notes of distributed computing will be uploaded
## Models and cuts

## Logical time

## Snapshots

### FIFO

#### Chandy–Lamport algorithm

### Non-FIFO

#### Lai–Yang algorithm
#### Li et al.’s algorithm
#### Mattern’s algorithm

## Casual ordering

## Termination detection

### Termination detection by weight throwing

### A spanning-tree-based termination detection algorithm

### Message-optimal termination detection

#### Chandrasekaran and Venkatesan


- The network is representred by graph and communication links are bidirectional and exibit FIFO property.
- The algorithm assumes the existence of a leader and a spanning tree in the network.
- If a leader is not available, the minimum spanning tree algorithm of Gallager et al. can be used to elect a leader and find a spanning tree using O(E + V.log(V)) messages.
