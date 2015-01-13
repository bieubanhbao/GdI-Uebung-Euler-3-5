# GdI-Uebung-Euler-3-5
//Auf.3
Der Graph ist ein Digraph und ist nicht vollständig.


stell den Graphen durch:


a) Abbildungen:

G(V,E)


V={0,1,2,3,4,,5,6,7,8,9,10,11}


E={(1,2),(1,3),(1,4),(2,3),(3,6),(4,3),(4,5),(4,7),(5,10),(6,7),(6,11),(7,5),(7,8),(7,9),(8,10),(9,10),(9,11),(10,11)}

b)
*Kantenliste:
???
*Pfeilliste:
  1-->2-->3---4-->5---6-->7-->8---9-->10-->11
  |
  |

c) Adjazenzmatrix:


   1  2  3  4  5  6  7  8  9  10  11
1     7  8  5
2           1
3                 4
4        2     1    3
5                             15 
6                   8             14
7              2        3  2
8                              2
9                              3  20
10                                 1
11 
//alle freie Plätze sind 0.

e)Adjazenzliste:
1| 2| 3| 4| 5| 6| 7| 8| 9| 10| 11|
2  3  6  3 10  7  5 10 10  11  \ 
7  1  4  2 15  8  2  2  3   1
.  \  \  . \   .  .  \   .  \
3        5    11  8     11
8        1     4  3     20
.        .    \   .     \
4        7        9
5        3        2
\        \        \









