# Algorithm for Learning Mod-2-MA

The algorithm (written in Java) takes as input a mod-2-MA and prints to stdout the MA obtained after learning the input function through a series of membership and equivalence queries. The motivation behind this algorithm originally arose from Angluin's exact learning model described in her paper "Learning regular sets from queries and counterexamples."

### Format of Input File
The input file is a text document containing the specifications of the target function. It must have the following format (no line separation, characters are space separated, and lines beginning with // are ignored):

Line 1: size of the alphabet

Line 2: characters in the alphabet

Line 3: size of the target function (r)

Line 4: γ of the target function (fy)

Lines 5-end: List of μ's for each character in the alphabet, with each μ appearing in a rxr grid

Example input files can be found in the respository.

In Mod2_MA.java, change the file name in the initialize function to the name of the intended input file.

### Author: Nevin George

### Advisor: Dana Angluin

### References
Amos Beimel, Francesco Bergadano, Nader H. Bshouty, Eyal Kushilevitz, Stefano Varric- chio. Learning functions represented    as multiplicity automata. *J. ACM*, 47(3):506–530, May 2000.

Dana Angluin. Learning regular sets from queries and counterexamples. *Inf. Comput.*, 75(2):87–106, 1987.

Dana Angluin, Timos Antonopoulos, Dana Fisman. Strongly Unambiguous Büchi Automata Are Polynomially Predictable with Membership Queries. *28th International Conference on Computer Science Logic*, 8:1–8:17, 2020.

Michael Thon and Herbert Jaeger. Links Between Multiplicity Automata, Observable Operator Models and Predictive State Representations — a Unified Learning Framework. *Journal of Machine Learning Research*, 16(4):103−147, 2015.
