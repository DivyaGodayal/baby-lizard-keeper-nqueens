# baby-lizard-keeper
#You are a zookeeper in the reptile house. One of your rare South Pacific Tufted Wizzo lizards (Tufticus Wizzocus) has just had several babies. Your job is to find a place to put each baby lizard in a nursery.
#However, there is a catch, the baby lizards have very long tongues. A baby lizard can shoot out its tongue and eat any other baby lizard before you have time to save it. As such, you want to make sure that no baby lizard can eat another baby lizard in the nursery (burp).
#For each baby lizard, you can place them in one spot on a grid. From there, they can shoot out their tongue up, down, left, right and diagonally as well. Their tongues are very long and can reach to the edge of the nursery from any location.

#In addition to baby lizards, your nursery may have some trees planted in it. Your lizards cannot shoot their tongues through the trees nor can you move a lizard into the same place as a tree. As such, a tree will block any lizard from eating another lizard if it is in the path. Additionally, the tree will block you from moving the lizard to that location.

 
#You will write a program that will take an input file that has an arrangement of trees and will output a new arrangement of lizards (and trees; as already mentioned, you can’t move the trees) such that no baby lizard can eat another one. You will be required to create a program that finds the solution. To find the solution you will use the following algorithms:
#- Breadth-first search (BFS)
#- Depth-first search (DFS)
#- Simulated annealing (SA).
