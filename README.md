# edge-caching-simulator
**Project Overview**

The Edge Caching Simulator project simulates various caching strategies (LRU, FIFO, LFU) to optimize content delivery in a content delivery network (CDN). The goal of the project is to evaluate how different caching strategies can reduce latency, improve server efficiency, and enhance user experience by caching frequently requested content at edge servers.

**Features**

Simulates user requests for URLs and caches them using various strategies.
Compares the effectiveness of LRU (Least Recently Used), FIFO (First In, First Out), and LFU (Least Frequently Used) caching strategies.
Measures cache hit/miss ratios and latency reduction.
Visualizes cache performance and other metrics.

**Technologies Used**

Python: The main programming language for building the simulator.
SimPy: For simulating user requests and cache operations.
Matplotlib: For visualizing cache performance metrics.
Redis (optional): For real-world caching simulations (if implemented).
