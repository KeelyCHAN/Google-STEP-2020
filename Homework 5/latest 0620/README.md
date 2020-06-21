Algorithms
====
### BF.ipynb
Brute-force algorithm by permutations. (For case 0 and case 1)<br>
Advantage: guaranteen to find the best tour.
### Greedy.ipynb
Greedy algorithm (without improvement). Check all different start cities. <br>
### Greedy+2opt(basic).ipynb
Above greedy algorithm with 2-opt improvement. <br>
Set the best tour in greedy.ipynb as the initial tour. Randomly choose 2 unconnected edges and flip them. If the total distance decreases, update new tour. Repeat the operations for max_count (self-defined) loops.
### Greedy+2opt(improved)-1.ipynb
Above greedy algorithm with 2-opt improvement. (Only apply on case 0 - case 4, due to limits of excution time)<br> 
For each city: <br>
1. Choose it as the start city. <br>
2. Find an initial tour by greedy algorithm. <br>
3. Search overlapped edges and flip them. <br>
4. Repeat until no overlapped edges. <br>
### Greedy+2opt(improved)-2.ipynb
Above greedy algorithm with 2-opt improvement. <br>
Set the best tour in greedy.ipynb as the initial tour. Apply 2-opt improvement as Greedy+2opt(improved)-1.ipynb.
### SA algorithm

Best Score (up to now)
===
### Case 0
3291.62 by BF algorithm <br>
### Case 1
3778.71 by BF algorithm <br>
### Case 2
4494.42 by greedy + 2opt (basic) <br>
### Case 3
8354.03 by greedy + 2opt (basic) <br>
### Case 4
11393.00 by greedy + 2opt (improved)-1 <br>
### Case 5
22806.48 by greedy + 2opt (improved)-2 <br>
### Case 6
44881.59 by greedy + 2opt (improved)-2 <br>
