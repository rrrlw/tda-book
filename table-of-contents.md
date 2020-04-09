* Part: Classical topological data analysis
  - Chapter: Hierarchical clustering
  - Chapter: Relational network analysis
  - Chapter: Association network analysis
  - Chapter: Merge Trees
	  - Section: Basic Morse theory  
  	- Section: Super and sub level sets 
  	- Section: Merge trees (relationships to reeb graphs)
		- Section: Relationship to clustering
* Part: Neighborhood-preserving dimensionality reduction
  - Chapter: Understanding the basics
  - Chapter: Popular algorithms (UMAP, HDBSCAN, lle, sneer, Rtsne; smallvis; multiple chapters?)
  - Chapter: Basic applications
* Part: Persistent Homology (Vietoris-Rips, lower-star filtration)
  - Chapter: Understanding the basics (filtrations?)
  - Chapter: Computation (TDAstats?)
  - Chapter: Visualization (TDAstats/ggtda?)
  - Chapter: Inference (TDAstats/TDA?)
  - Chapter: Basic Applications (differentiating sample point clouds (circ2d vs unif2d)?)
* Part: Time Series analysis 
	- Chapter: Basics (Fourier decomposition)
	- Chapter: Classical Signal analysis (ARIMA, moving average, etc.)
	- Chapter: Slidding window embeddings
	- Chapter: SW1Pers and relationship back to PH
* Part: Reeb graph (Matt: maybe this should be a section as part of the basics to Mapper?)
  - Chapter: Understanding the basics
  - Chapter: Computation
  - Chapter: Visualization
  - Chapter: Inference/Other?
  - Chapter: Basic Applications
* Part: Mapper algorithm
  - Chapter: Understanding the basics
  - Chapter: Computation
  - Chapter: Visualization
  - Chapter: Inference/Other?
  - Chapter: Basic Applications
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
