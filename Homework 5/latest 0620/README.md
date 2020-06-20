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
Set the best tour in greedy.ipynb as the initial tour. Apply 2opt improvement as Greedy+2opt(improved)-1.ipynb.

To be continued.
===
