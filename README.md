# Behance-Like Website Block Scheme

```mermaid

graph TB;

subgraph cluster_Sun
  A[Behance Logo]
end

subgraph cluster_Planets
  B[Discover]
  C[Featured]
  D[Projects]
  E[Creative Fields]
  F[Jobs]
end

subgraph cluster_Moons
  G[Projects Category 1]
  H[Projects Category 2]
  I[Projects Category 3]
  J[Projects Category 4]
  K[Projects Category 5]
end

A -->|Sunlight| B;
A -->|Sunlight| C;
A -->|Sunlight| D;
A -->|Sunlight| E;
A -->|Sunlight| F;

B --> G;
B --> H;
C --> I;
D --> J;
D --> K;
end



```

