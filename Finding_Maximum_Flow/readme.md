
**Ford-Fulkerson Algorithm:**

1. **Input:**
   - Graph G with vertices V and edges E.
   - Each edge (u, v) has a capacity c(u, v).
   - Source vertex s and sink vertex t.

2. **Initialization:**
   - Initialize the flow f(u, v) for all edges to 0.
   - Create a residual graph R with the same vertices as G.

3. **While there exists an augmenting path P from s to t in R:**
   - Find an augmenting path P using BFS or DFS in R.
   - Determine the bottleneck capacity, which is the minimum capacity of the edges in path P.

4. **Update the flow:**
   - Increase the flow along each edge of P by the bottleneck capacity.
   - Decrease the residual capacity of forward edges in P by the bottleneck capacity.
   - Increase the residual capacity of backward edges in P by the bottleneck capacity.

5. **Output:**
   - Repeat steps 3-4 until no augmenting path exists.
   - The maximum flow is the sum of flow leaving the source vertex s in the residual graph R.

