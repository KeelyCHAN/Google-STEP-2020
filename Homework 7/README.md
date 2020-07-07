TSP improvemnt
=====

### TSP greedy
1. Apply greedy algorithm for each cities (as starting point) to obtain an initial tour. <br>
2. Detect overlapped edges and switch them <br> to obtain an improved tour. <br>
3. Compare the improved tour for each start city to find the best tour. <br>

### TSP sa
1. Apply greedy algorithm for a random city (as starting point) to obtain an initial tour. <br>
2. Optimize the initial tour by sa algorithm to obtain an improved tour. <br>
3. Apply 2-opt to the improved tour to find the best tour. <br>
