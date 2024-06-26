```
# First Paper
```
1) **Paper Title                  :**  Decentralized Federated Learning With Markov Chain Based Consensus for Industrial IoT Networks
2) **Published Journel & Year     :**  IEEE TRANSACTIONS ON INDUSTRIAL INFORMATICS, VOL. 19, NO. 4, APRIL 2023
3) **Proposed Method / Algorithm  :**  An FMMC-based model consensus algorithm is proposed for DFL by formulating the problem of model **consensus as an FMMC problem**.
                                   The consensus matrix is optimized by taking the entire network topology into account to improve the efficiency of collaborative training and reduce the communication time. 
                                   Furthermore, a practical protocol with time slotted channel hopping (TSCH) scheduling policy is adopted to implement the proposed DFL approach.
4) **Compared Approcahes          :**
   1. Metropolis–Hastings
   2. Sum-weight gossip based consensus algorithms perform model aggregation according to the degree of a device.
   3. Laplacian-based constant consensus computes the aggregation weight according to the Laplacian matrix of the entire network.
```
# Second Paper
```

1) **Paper Title                  :**  Adaptive Decentralized Federated Learning in Resource-Constrained IoT Networks
2) **Published Journel & Year     :**  IEEE INTERNET OF THINGS JOURNAL, VOL. 11, NO. 6, 15 MARCH 2024
3) **Proposed Method / Algorithm  :**  A network topology pruning approach by formulating the network topology pruning problem as the regularized version of the **fastest mixing Markov-chain (FMMC) problem**
4) **Compared Approcahes          :**
   1. combined methods as pruning and compression


```
# Third Paper is Matched with our Idea But It was not published yet to any other Journels
```
1) **Paper Title                  :**  OCD-FL: A Novel Communication-Efficient Peer Selection-based Decentralized Federated Learning
2) **Published Journel & Year     :**  ArXiv 2024
3) **Proposed Method / Algorithm  :**  The goal is to efficiently select neighbors for collaboration taking into account the **amount of energy required for transmission as well as the 
                                       knowledge gained by neighbors** as a result of the collaboration.
4) **Compared Approcahes          :**
   1. No Major Comparisons
```
# Fourth Paper is Matched with our Idea 
```
1) **Paper Title                  :**  Joint Consensus Matrix Design and Resource Allocation for Decentralized Learning
2) **Published Journel & Year     :**  IFIP Networking Conference (IFIP Networking), Catania, Italy, 2022.
3) **Proposed Method / Algorithm  :**  The aim of this paper is to accelerate the training process of decentralized ML via joint sparse consensus weight matrix design and communication resource allocation. They propose a novel Communication-Efficient Network Topology (CENT) Algorithm
4) **Compared Approcahes          :**
   1. **Fast linear iterations for distributed averaging (FDLA)  :** The weights are calculated by solving the spectral norm minimization problem. It gives the fastest convergence rate in terms of the number of training iterations.
   2. **Max-degree:** Assign all edges the same weight based on the maximum degree of the graph.
   3. **Metropolis:** Assign each edge a weight based on the maximum degree of its two adjacent workers.
   4. **Best-constant:** Assign all edges the same optimal constant weight based on the eigenvalues of the Laplacian matrix of the graph
```
# Fifth Paper is Matched with our Idea 
```
1) **Paper Title                  :**  Laplacian Matrix Sampling for Communication- Efficient Decentralized Learning
2) **Published Journel & Year     :**  IEEE Journal on Selected Areas in Communications April, 2023.
3) **Proposed Method / Algorithm  :**  The paper proposed a framework and efficient algorithms to design the communication patterns through Laplacian matrix sampling (LMS), which governs not only which nodes should communicate with each other but also what weights the communicated parameters should carry during parameter aggregation.
4) **Compared Approcahes          :**
   1. **Vanilla D-PSGD**  :
   2. **MATCHA** : matching decomposition sampling.
5) **Code Availability**  : https://github.com/sunilanil102/Laplacian-Matrix-Sampling
```
Seminal Work \ Paper \ Root Paper for all the Publications
```
1) **Paper Title                  :**  FASTEST MIXING MARKOV CHAIN ON A GRAPH
2) **Published Journel & Year     :**  Published in SIAM Review 2004 Mathematics
3) **Proposed Method / Algorithm  :**  The problem of assigning probabilities to the edges of the graph in such a way as to minimize the SLEM, i.e., the problem of finding the **fastest mixing Markov chain on the graph**.
4) **Compared Approcahes          :**
   1.  We compare the fastest mixing Markov chain to those obtained using two commonly used heuristics: **The maximum-degree method**, and **The Metropolis-Hastings algorithm**.
```
Seminal Work on Distributed Averaging 
```

1) **Paper Title                  :**  Fast linear iterations for distributed averaging 
2) **Published Journel & Year     :**  Systems & Control Letters 53 (2004)
3) **Proposed Method / Algorithm  :**  speed up interior-point methods for solving the fastest distributed linear iteration problem, for networks with up to a thousand or so edges.
4) **Compared Approcahes          :**
   1.  **Maximum-degree**
   2.  **Local-degree**
   3.  **Best constant**
   4.  **Optimal symmetric**
