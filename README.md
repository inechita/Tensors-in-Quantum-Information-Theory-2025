# Tensors in Quantum Information Theory

This is the webpage for the doctoral course _Tensors in Quantum Information Theory_, given in spring 2025 at the [LPT Toulouse](https://lpt.univ-tlse3.fr/en/) by [Ion Nechita](https://ion.nechita.net/). 

# Schedule 
There will be 10 lecturs of 2h each, taking place in the **room 20, ground floor of the 3R1 building**, as follows: 

|N.| Date | Topic | 
| ---: | :---: | :--- | 
| [1.](#lecture-1)  | `Mon, March 17th, 2pm-4pm` | *Meet and greet, introduction to tensors, first examples, basics of random matrix theory*
| [2.](#lecture-2)  | `Wed, March 19th, 2pm-4pm` | *Tensors. Graphical notation*
| [3.](#lecture-3)  | `Mon, March 24th, 2pm-4pm` | *Graphical notation in applications. Contracting tensor networks.*
| [4.](#lecture-4)  | `Wed, March 26th, 2pm-4pm` | *The Singular Value Decomposition*
| [5.](#lecture-5)  | `Mon, March 31st, 2pm-4pm` | *Tensor rank*
| [6.](#lecture-6)  | `Wed, April 2nd, 2pm-4pm` | *Tensor norms*
| [7.](#lectures-7-8-9)  | `Mon, April 7th, 2pm-4pm` | *Project choice*
| [8.](#lectures-7-8-9)  | `Wed, April 9th, 2pm-4pm` | *Project work*
| [9.](#lectures-7-8-9)  | `Mon, April 14th, 2pm-4pm` | *Project work*
| [10.](#lecture-10) | `Wed, April 16th, 2pm-4pm` | *Project presentations*
---

# Topics
1. Basics of tensors
2. Graphical notation
3. Tensor ranks 
4. Tensors in quantum information theory 
5. Tensor norms
6. Tensor decompositions
7. Tensor eigenvalues

# Projects

1.	Computational complexity 
  - NP hardness of tensor problems
  - Undecidable tensor problems
2. Quantum Information Theory 
  - Tensor norms for non local games
  - Tensor norms for entanglement
  - Tensor norms for quantum incompatibility and quantum steering
  - Tensor eigenvalues
  - Algorithms for injective and projective norms
3. Tensor networks
  - Contracting tensor networks
  - TensorKrowch https://github.com/joserapa98/tensorkrowch
  - Chapters 3- from [Hand-waving and Interpretive Dance: An Introductory Course on Tensor Networks](https://arxiv.org/abs/1603.03039)
4. ML and NN using tensors
  - AlphaTensor
  - Tensor PCA
  - The transformer architecture


# Lecture notes
... available as we go, either pdfs or notebooks ...

Here are the notes of a series of 3 lectures I gave in February about similar topics: [ICTS 2025 - Tensor norms for quantum entanglement](https://ion.nechita.net/assets/pages/teaching/icts-2025-tensor-norms-for-quantum-entanglement.html). 

## Lecture 1

We discussed some problems in random matrix theory where the notion of rank is important. 

We started with the [Netflix problem](https://www.nytimes.com/2008/11/23/magazine/23Netflix-t.html), aka [matrix completion](https://en.wikipedia.org/wiki/Matrix_completion). The Netflix problem tackles the challenge of predicting missing ratings in a large, sparse user - item matrix by leveraging the assumption that the underlying data is low rank. This low rank assumption implies that there exist only a few latent factors - such as genre preferences, viewing habits, or intrinsic qualities of movies and shows - that largely determine how users rate content. In essence, even though the observable matrix is incomplete and noisy, it is believed that user preferences and item attributes can be effectively captured by a small number of these hidden factors. This compressed representation allows matrix factorization methods to accurately reconstruct the full matrix, making it possible to provide reliable recommendations even from limited data.

We then discussed the basics of [Random Matrix Theory](https://en.wikipedia.org/wiki/Random_matrix), see the [notebook](/assets/basics-of-RMT.ipynb). 

## Lecture 2

[Handwritten notes](/assets/graphical-notation-for-tensors.pdf).

Formal introduction to tensor products, tensors, tensor contraction. [Penrose graphical notation](https://en.wikipedia.org/wiki/Penrose_graphical_notation) for tensors. Applications. 

References for the graphical formalism: 
-  R. Penrose - [Applications of negative dimensional tensors](https://www.mscs.dal.ca/%7Eselinger/papers/graphical-bib/public/Penrose-applications-of-negative-dimensional-tensors.pdf)
-  R. Penrose - The road to reality -> Chapter 12.8
-  J. Bridgeman, C. Chubb - [Hand-waving and Interpretive Dance: An Introductory Course on Tensor Networks](https://arxiv.org/abs/1603.03039)
-  J. Biamonte, V. Bergholm - [Tensor Networks in a Nutshell](https://arxiv.org/abs/1708.00006)
-  J. Taylor - [Graphical tensor notation for interpretability](https://www.lesswrong.com/posts/BQKKQiBmc63fwjDrj/graphical-tensor-notation-for-interpretability) -> discusses Transformers

## Lecture 3

[Handwritten notes](/assets/graphical-notation-for-tensors.pdf).

Continue discussing and applying the graphical formalism. Vectorization. The computational cost of contracting tenor networks: see Section 1.4 [here](https://arxiv.org/abs/1603.03039) and, e.g. [here](https://arxiv.org/abs/quant-ph/0511069) for the important notion of [treewidth](https://en.wikipedia.org/wiki/Treewidth). 

## Lecture 4

[Handwritten notes](/assets/SVD.pdf).

The [Singular Value Decomposition](https://en.wikipedia.org/wiki/Singular_value_decomposition) (here's a [refresher](https://www-users.cse.umn.edu/~lerman/math5467/svd.pdf) on the SVD). 

## Lecture 5

[Handwritten notes](/assets/Tensor-rank.pdf), see also the [ICST lecture notes](https://ion.nechita.net/assets/pages/teaching/icts-2025-tensor-norms-for-quantum-entanglement.html).

The [tensor rank](https://en.wikipedia.org/wiki/Tensor_rank_decomposition) is a notion of fundamental importance in the study of tensors. A good reference for QIT related questions is the paper [Tensor rank and entanglement of pure quantum states](https://arxiv.org/abs/1912.06854) by Bruzda, Friedland, and Życzkowski.

## Lecture 6

[Handwritten notes](/assets/Tensor-norms.pdf), see also the [ICST lecture notes](https://ion.nechita.net/assets/pages/teaching/icts-2025-tensor-norms-for-quantum-entanglement.html).

## Lectures 7-8-9

Project work on the three selected topics:

- TensorKrowch for ground states
- The transformer architecture
- Spectra of random tensor networks

## Lecture 10

The students presented the projects, here are some relevant links to their amazing work: 

- **TensorKrowch for ground states**: [GitHub repository](https://github.com/inechita/tensors2025-project-ground-state-tensor-network) containing slides for the presentation as well as python and Mathematica notebooks. 
- **The transformer architecture**
- **Spectra of random tensor networks**
