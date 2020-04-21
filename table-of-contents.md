* Part: Classical topological data analysis
  - Chapter: Hierarchical clustering
    - Agglomerative & divisive algorithms; dendrograms
    - Density functions and merge trees
    - Persistence; HDBSCAN (?)
    - Stability of single-linkage clustering (?)
  - Chapter: Network analysis
    - Relational networks; association networks
    - Euler characteristic; cycle rank
    - Simplicial homology (?)
* Part: Neighborhood-preserving dimensionality reduction
  - Chapter: Multidimensional scaling (Isomap, LLE)
  - Chapter: Stochastic embeddings (SNE & t-SNE)
  - Chapter: Manifold learning (Diffusion maps, UMAP)
* Part: Persistent homology
  - Chapter: Vietoris-Rips and Cech complexes
  - Chapter: Filtrations (lower-star filtration; elder rule; plot types)
  - Chapter: Simplicial maps (?)
  - Chapter: Stability and statistical inference (persistent landscapes)
  - Chapter: Sliding window embeddings (SW1Pers)
* Part: Mapper construction
  - Chapter: Reeb graphs
  - Chapter: Mapper
  - Chapter: Persistence and stability
  - Chapter: Annotation and analysis (variable connectivity; stable paths)
* Part: Real-World Applications
  - Use case: handwriting recognition? (MNIST/EMNIST?)
  - Use case: healthcare TDA dataset(s) (can split into multiple chapters, depending on how many use cases there are and how similar they are to each other)
  - Use case: analyzing vocal folds using SW1Pers

----------
Thoughts:
* For chapters with methods not covered (or not covered well) by an existing R package (e.g. Mapper?), can/should we create appropriate R packages?
	* Matt: I have code I'm working on to do merge tree/Morse theoretic-related algorithms.
* Would be nice to structure book in a way that would make it usable for applied TDA university courses (e.g. exercises at end of each chapter) (maybe with learnr?)

----------
