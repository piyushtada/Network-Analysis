# remove selfloops
```python
loops = list(nx.selfloop_edges(G))
G.remove_edges_from(loops)
```