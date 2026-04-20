# Implementation of an abduction algorithm based on MARCO in the CATS solver

Abduction is a type of reasoning that explains observed phenomena by identifying their possible causes (explanations) based on available background knowledge. Methods based on HS-trees belong to the most general approaches, enabling a systematic exploration of the explanation space and the step-by-step computation of all possible explanations. These methods require model computation, which is not a service commonly provided by reasoners. Therefore, we aim to explore an alternative approach inspired by the MARCO algorithm, which does not rely on models.

Main goals of this thesis:

1. Analysis of the state of the art, including the existing abduction tool CATS, the principles of HS-tree-based methods, and the incomplete MergeXplain method.
2. Design and modular implementation of an abduction algorithm inspired by the MARCO algorithm and incorporating the MergeXplain method.
3. Optimisation of the implemented abduction algorithm.
4. Empirical evaluation of the implemented algorithm and its comparison with HS-tree-based methods.

Calendar of completed tasks:
+ studying literature about description logics and ontologies - November 2025
+ studying literature about abduction and tree-based abduction algorithms - December 2025 and January 2026
+ getting to know the CATS solver (structure, classes, workflow) - February 2026
+ implementing/debugging the first version of the new algorithm - March 2026
+ implementing a more effective version of the algorithm + creating unit tests + testing - April 2026

Calendar of planned tasks:
+ design and implement multiple version of the algorithm + testing - May, June 2026
+ test the algorithm on multiple inputs
+ evaluate the performance of the algorithm
+ compare the performance with other methods


The implementation is available as part of the [CATS solver](https://github.com/Comenius-Abduction-Team/CATS-Abduction-Solver).

PDF version of the thesis: 


Literature:
1. Elsenbroich, C., et al., 2006. A case for abductive reasoning over ontologies. In OWLED. Vol. 216 of CEUR-WS
2. Homola, M., et al., 2023. Merge, explain, iterate: A combination of MHS and MXP in an ABox abduction solver. In JELIA. Vol. 14281 of LNCS, Springer Nature
3. Liffiton, M. H., et al., 2016. Fast, flexible MUS enumeration. In Constraints An Int. J., 21(2), pp. 223–250.
4. Shchekotykhin, K. M., et al., 2015. MergeXplain: Fast computation of multiple conflicts for diagnosis. In IJCAI 2015, AAAI Press, pp. 3221–3228.
