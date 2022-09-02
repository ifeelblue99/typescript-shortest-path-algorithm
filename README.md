# typescript-shortest-path-algorithm

this is a path finder algorithm based on BFS
it uses an Map as adjacency
- ex list:
```typescript
Map {
  0 => Array [
    1,
  ],
  1 => Array [
    0,
    6,
  ],
  .
  .
  .
  11 => Array [
    10,
    6,
    16,
  ],
  13 => Array [
    18,
  ],
  .
  .
  .
  38 => Array [
    39,
    33,
  ],
  39 => Array [
    38,
  ],
}

```
- usage:
```typescript
  const path = shortestPath(adjacencyList, 0, 39);

  returns -> Array [ 1,  6,  11,  12,  17,  22,  23,  24,  29,  34,  39] // start(0) is excluded

```
