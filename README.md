# Opus Website Block Scheme

```mermaid
flowchart BT ;

style A fill:#86C7F3, stroke:#333, stroke-width:2px, stroke-dasharray: 5, 5;
style B fill:#FFD700, stroke:#333, stroke-width:2px, stroke-dasharray: 5, 5;
style F fill:#90EE90, stroke:#333, stroke-width:2px, stroke-dasharray: 5, 5;
style K fill:#FFA07A, stroke:#333, stroke-width:2px, stroke-dasharray: 5, 5;
style O fill:#D3D3D3, stroke:#333, stroke-width:2px, stroke-dasharray: 5, 5;

A[Website]
B[Discover]
C[Categories]
D[Featured Projects]
E[Popular Tags]
F[Profile]
G[My Projects]
H[Liked Projects]
I[Following]
J[Followers]
K[Projects]
L[Works in Progress]
M[Collections]
N[Curated Galleries]
O[Jobs]
P[Search]
Q[Assets]
R[Terms of Use & Privacy]
S[Contacts]

B & F --> A;
C & D & E --> B;
G & H --> F;
I & J --> F;
L & M & N --> K;
P & Q --> O;
R & S --> O;

K --> --> A;
```

