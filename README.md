# Mini-projet-solveur-DPLL-r-cursif

                Mini-projet 1 : solveur DPLL récursif


Objectif du mini-projet
-----------------------

Le but du mini-projet est d'implémenter un solveur DPLL récursif en
OCaml.



Tester le mini-projet
----------------------

Outre les sept exemples de test inclus dans dpll.ml (exemple_3_13,
exemple_7_3, exemple_7_5, exemple_7_9, accessibilite, grammaire et
coloriage), vous pouvez utiliser le Makefile en appelant

  make

pour compiler un exécutable natif et le tester sur des fichiers au
format DIMACS. 


Par exemple :

./dpll chemin/vers/sudoku-4x4.cnf

devrait répondre

SAT
-111 -112 113 -114 -121 -122 -123 124 -131 132 -133 -134 141 -142 -143 -144 -211 212 -213 -214 221 -222 -223 -224 -231 -232 -233 234 -241 -242 243 -244 311 -312 -313 -314 -321 322 -323 -324 -331 -332 333 -334 -341 -342 -343 344 -411 -412 -413 414 -421 -422 423 -424 431 -432 -433 -434 -441 442 -443 -444 0


