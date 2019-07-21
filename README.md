# Freiburg RNA algorithms for teaching

This repository contains the Javascript and Html sources for various
algorithms related to RNA structure and RNA-RNA interaction prediction.
Furthermore, we provide interactive implementations for general
sequence alignment approaches.

All approaches are [available in the Freiburg RNA Teaching webserver](http://rna.informatik.uni-freiburg.de/Teaching/).

- **General sequence alignment approaches**
  - **pairwise alignment**
    - [Needleman-Wunsch](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Needleman-Wunsch) (global, linear gap costs, quadratic space)  (see [js](js/needleman_wunsch.js))
    - [Hirschberg](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Hirschberg) (global, linear gap costs, linear space)  (see [js](js/hirschberg.js))
    - [Gotoh](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Gotoh) (global, affine gap costs)  
    (see [js](js/gotoh.js))
    - [Waterman-Smith-Beyer](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Waterman-Smith-Beyer) (global, arbitrary gap costs)  (see [js](js/waterman_smith_beyer.js))
    - [Smith-Waterman](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Smith-Waterman) (local, linear gap costs)  (see [js](smith_waterman.js))
    - [Arslan-Egecioglu-Pevzner](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Arslan-Egecioglu-Pevzner) (local, linear gap costs, normalized score)  (see [js](js/arslan_egecioglu_pevzner.js))
    - [Gotoh (Local)](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Gotoh%20(Local)) (local, affine gap costs)  (see [js](js/gotoh_local.js))
  - **multiple alignment**
    - [Feng-Doolittle (Gotoh-based)](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Feng-Doolittle) (progressive, affine gap costs)  (see [js](js/feng_doolittle.js))
    - [Iterative Refinement (Feng-Doolittle-based)](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Iterative%20Refinement) (progressive, affine gap costs, iterative refinement)  (see [js](js/iterative_refinement.js))
    - [Notredame-Higgins-Heringa (t-coffee)](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Notredame-Higgins-Heringa) (progressive, data-derived scoring)  (see [js](js/notredame_higgins_heringa.js))
- **Agglomerative Clustering**  (see [js](js/agglomerative_clustering.js))
  - [Complete Linkage](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Agglomerative%20Clustering) (Furthest Neighbour)
  - [Neighbour-Joining](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Agglomerative%20Clustering) (Nearest Neighbour on clusters)
  - [Single Linkage](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Agglomerative%20Clustering)  (Nearest Neighbour on elements between two different clusters)
  - [Unweighted Pair Group Method with Arithmetic Mean (UPGMA)](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Agglomerative%20Clustering) (Group Average or Average Linkage)
  - [Weighted Pair Group Method with Arithmetic Mean (WPGMA)](http://rna.informatik.uni-freiburg.de/Teaching/index.jsp?toolName=Agglomerative%20Clustering) (Simple Average)



