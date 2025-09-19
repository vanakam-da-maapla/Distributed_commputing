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
Let p i(t) denote the state (active or idle) of process p i at instant t and c ij (t)
denote the number of messages in transit in the channel at instant t from
process pi to process p j . A distributed computation is said to be terminated
at time instant t0 iff:
∀i p i t0 = idle ∧ ∀i j c ij t0 = 0


### A spanning-tree-based termination detection algorithm

### Message-optimal termination detection
