# ENS-DDA implimentation
Abstract of the IEEE Paper: In Pareto based multi- and many-objective evolutionary algorithms (MOEAs and MaOEAs), non-dominated sorting is an important step that divides the set of solutions into different disjoint non-dominated fronts. In the last 20 years, there have been various approaches proposed for nondominated sorting. Recently, an approach known as Dominance Degree Approach for Non-Dominated Sorting (DDA-NS) has been proposed. This approach guarantees that the number of floatingpoint comparisons is always bounded by O(MN logN) for N solutions and M objectives, which is not true for various approaches. However, the worst-case time complexity of DDANS is recently proved to be (MN2 + N3). In this paper, we develop an approach on the top of DDA-NS, which also guarantees O(MN logN) floating-point comparisons and its worst-case time complexity is proved to be (MN2) as opposed to O(MN2 + N3) of DDA-NS.
