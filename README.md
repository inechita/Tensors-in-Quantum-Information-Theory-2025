# Tensors in Quantum Information Theory

This is the webpage for the doctoral course _Tensors in Quantum Information Theory_, given in spring 2025 at the [LPT Toulouse](https://lpt.univ-tlse3.fr/en/) by [Ion Nechita](https://ion.nechita.net/). 

# Schedule 
There will be 10 lecturs of 2h each, taking place in the **room 20, ground floor of the 3R1 building**, as follows: 

|N.| Date | Topic | 
| ---: | :---: | :--- | 
| 1.  | `Mon, March 17th, 2pm-4pm` | *Meet and greet, introduction to tensors, first examples, basics of random matrix theory*
| 2.  | `Wed, March 19th, 2pm-4pm` | *Tensors. Graphical notation*
| 3.  | `Mon, March 24th, 2pm-4pm` | 
| 4.  | `Wed, March 26th, 2pm-4pm` | 
| 5.  | `Mon, March 31st, 2pm-4pm` | 
| 6.  | `Wed, April 2nd, 2pm-4pm` | 
| 7.  | `Mon, April 7th, 2pm-4pm` | 
| 8.  | `Wed, April 9th, 2pm-4pm` | 
| 9.  | `Mon, April 14th, 2pm-4pm` | 
| 10. | `Wed, April 16th, 2pm-4pm` | 
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
- NP hardness of tensor problems 
- Undecidable tensor problems 
- Tensor norms for non local games
- Tensor norms for entanglement
- Tensors norms for quantum incompatibility and quantum steering
- Graphical interactive tensor networks + randomness
- AlphaTensor
- Tensor eigenvalues
- TensorKrowch https://github.com/joserapa98/tensorkrowch
- Algorithms for injective norm 
- Algorithms for projective norm
- Contracting tensor networks 
- Tensor PCA

# Lecture notes
... available as we go, either pdfs or notebooks ...

Here are the notes of a series of 3 lecturs I gave in February about similar topics: [ICTS 2025 - Tensor norms for quantum entanglement](https://ion.nechita.net/assets/pages/teaching/icts-2025-tensor-norms-for-quantum-entanglement.html). 

## Lecture 1

People's tensors

***

We also discussed some problems in random matrix theory where the notion of rank is important. 

We started with the Netflix problem, aka [Matrix completion](https://en.wikipedia.org/wiki/Matrix_completion). The Netflix problem tackles the challenge of predicting missing ratings in a large, sparse user-item matrix by leveraging the assumption that the underlying data is low rank. This low rank assumption implies that there exist only a few latent factors—such as genre preferences, viewing habits, or intrinsic qualities of movies and shows—that largely determine how users rate content. In essence, even though the observable matrix is incomplete and noisy, it is believed that user preferences and item attributes can be effectively captured by a small number of these hidden factors. This compressed representation allows matrix factorization methods to accurately reconstruct the full matrix, making it possible to provide reliable recommendations even from limited data.

We then discussed the basics of [Random Matrix Theory](https://en.wikipedia.org/wiki/Random_matrix), see the notebook. 



