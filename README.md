# DH-HCRC: Dynamic Heterophilic Hypergraph Community Discovery

A reference implementation of **DH-HCRC** — a dynamic, heterophily-aware
hypergraph community-discovery framework for resource-coordinated, heterogeneous
multi-agent systems (e.g., urban low-altitude UAV swarms).

## Features

- **Dynamic signed hypergraph construction** with four hyperedge types: task,
  communication, resource competition, spatial conflict (Eqs. 5–16).
- **Heterophilic embedding** via a hypergraph convolutional network with
  capability-difference attention (Eqs. 29–30).
- **Log-determinant capability complementarity** for heterophilic grouping
  (Eq. 20).
- **Joint community–resource optimization** with alternating updates
  (Eqs. 23, 26, 27).
- **Heterophilic label propagation** and **local quality-ascent refinement**
  (Eqs. 32–33).
- **Event-triggered K-hop incremental update** for scalability.
- **Resource feedback** that reinforces competition weights on shortage
  (Eq. 35).
- **Distributed gossip implementation** with Metropolis weights (Eq. 36).

## File Structure
