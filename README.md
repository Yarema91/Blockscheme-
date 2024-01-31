# Behance-Like Website Block Scheme

```mermaid
graph TD;

subgraph cluster_Home
  A[Home]
  B[Discover]
  C[Following]
end

subgraph cluster_Projects
  D[Projects]
  E[Works in Progress]
  F[Collections]
  G[Curated Galleries]
end

subgraph cluster_Create
  H[Start a Project]
  I[Upload]
end

subgraph cluster_Profile
  J[Profile]
  K[My Projects]
  L[Liked Projects]
  M[Following]
  N[Followers]
end

subgraph cluster_Jobs
  O[Jobs]
  P[Hiring]
end

subgraph cluster_Notifications
  Q[Notifications]
end

subgraph cluster_Search
  R[Search]
end

A -->|Navigation| B;
A -->|Navigation| C;
B -->|Sub-navigation| G;
B -->|Sub-navigation| D;
D -->|Sub-navigation| E;
D -->|Sub-navigation| F;
C -->|Sub-navigation| G;
B -->|Sub-navigation| R;
A -->|Navigation| H;
H -->|Sub-navigation| I;
A -->|Navigation| J;
J -->|Sub-navigation| K;
J -->|Sub-navigation| L;
J -->|Sub-navigation| M;
J -->|Sub-navigation| N;
A -->|Navigation| O;
O -->|Sub-navigation| P;
A -->|Navigation| Q;


```

