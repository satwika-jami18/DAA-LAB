Practical 1:

Summary :
The practical involved implementing five different sorting algorithms: Selection Sort, Insertion Sort, Bubble Sort, Merge Sort,and Quick Sort using Python. Each algorithm accepted user input, sorted the given array, displayed the sorted output, measured the execution time, and presented its time and space complexities. The practical helped compare the efficiency of different sorting techniques and understand their behavior under various input conditions. It also demonstrated that simple sorting algorithms are easier to implement but less efficient for large datasets, whereas divide-and-conquer algorithms such as Merge Sort and Quick Sort provide significantly better performance.

Conclusion :
The practical was successfully completed by implementing and analyzing multiple sorting algorithms. It was observed that 
Selection Sort, Insertion Sort, and Bubble Sort generally have O(n²) time complexity (except the best case of Insertion and 
Bubble Sort, which is O(n)), making them suitable only for small datasets. Merge Sort consistently performs in O(n log n) timewith additional memory usage, while Quick Sort provides excellent average-case performance of O(n log n) with a worst-case complexity of O(n²). Overall, the practical enhanced the understanding of sorting techniques, algorithm analysis, execution time measurement, and the importance of selecting an appropriate algorithm based on problem requirements

Practical 2:

Summary :
This practical successfully implemented and analyzed two fundamental searching algorithms: Sequential Search and Binary Search. Both algorithms were developed in Python to search for a user-specified element, display the search result, measure the execution time, and analyze their theoretical time complexities. Sequential Search performs a linear scan by checking each element one after another, making it suitable for both sorted and unsorted datasets. In contrast, Binary Search operates only on sorted arrays and follows the divide-and-conquer approach by repeatedly dividing the search space into two halves until the desired element is found. The practical clearly demonstrated the working process, efficiency, and performance differences between the two algorithms. It also emphasized the importance of selecting an appropriate searching technique based on the size and organization of the data to achieve better computational efficiency.

Conclusion :
The implementation of Sequential Search and Binary Search was completed successfully, and both algorithms accurately searched for the required element. The practical showed that Sequential Search is simple and suitable for small or unsorted datasets, while Binary Search is more efficient for sorted datasets because it reduces the search space at each step. The comparison of their execution time and time complexity highlighted the advantages and limitations of each algorithm. Overall, this experiment improved the understanding of searching techniques and emphasized the importance of choosing the appropriate algorithm to achieve efficient and faster data retrieval.


Practical 3:

Summary:
Max Heap Sort is an efficient comparison-based sorting algorithm that uses the Max Heap data structure to arrange elements in ascending order. The algorithm first converts the given array into a Max Heap, where the largest element is always present at the root. The root element is then exchanged with the last element, and the remaining heap is rearranged using the heapify operation. This process is repeated until all elements are sorted. The implemented program accepts input from the user, performs Max Heap Sort without using built-in sorting functions, displays the sorted array, and measures the execution time.

Conclusion:
The implementation of Max Heap Sort demonstrates the effective use of the heap data structure for sorting elements. The algorithm has a best-case, average-case, and worst-case time complexity of O(n log n), making its performance consistent even for large input sizes. The algorithm can also be implemented in-place, which reduces the need for additional memory. By implementing Max Heap Sort manually and measuring its execution time, we can understand both the working principle of heap-based sorting and its computational efficiency. Overall, Max Heap Sort is a reliable and efficient sorting technique for applications where consistent performance is important.


Practical 4 

Summary :
In this practical, the factorial of a given number was implemented using two different approaches: iterative and recursive methods. The program accepts input from the user and calculates the factorial using both techniques. The execution time of each method is measured using Python's time functions to compare their practical performance. The time complexity of both methods is O(n). However, the iterative method requires O(1) space, while the recursive method requires O(n) space because of the recursive function call stack. This practical helps in understanding how different programming approaches can solve the same problem and how their :
efficiency can be analyzed.

Conclusion :
The factorial program was successfully implemented using both iterative and recursive techniques. Both approaches provide the correct factorial result, but their memory requirements are different. The iterative approach is more memory-efficient because it does not create multiple function calls, whereas the recursive approach is simpler and demonstrates the concept of recursion clearly. By measuring execution time and analyzing time and space complexity, we gained a better understanding of algorithm efficiency and performance analysis.


Practical 7 

Summary :
In this practical, the Making Change Problem was implemented using the Dynamic Programming approach. The program accepts the coin denominations and target amount as input from the user and determines the minimum number of coins required to make the given amount. A dynamic programming table is used to store previously calculated results and avoid repeated computations. The execution time of the algorithm is also measured to analyze its practical performance. The time complexity of the solution is O(n × A) and the space complexity is O(A), where n is the number of coin denominations and A is the target amount.

Conclusion :
The Making Change Problem was successfully solved using Dynamic Programming. The approach efficiently finds the minimum number of coins by breaking the problem into smaller subproblems and storing their results for future use. This avoids unnecessary repeated calculations and improves efficiency compared with a simple recursive approach. The execution time, time complexity, and space complexity were analyzed to understand the performance of the algorithm. Thus, this practical helped in understanding the concept of Dynamic Programming and its application in solving optimization problems efficiently.

Practical 6

Summary :
The Chain Matrix Multiplication problem was implemented using the Dynamic Programming technique. The program accepts the number and dimensions of matrices as user input and determines the optimal order of matrix multiplication. Instead of performing the actual matrix multiplication, it calculates the minimum number of scalar multiplications required for different possible orders and selects the most efficient one. The program also displays the optimal parenthesization and measures the execution time. The algorithm has a time complexity of O(n³) and a space complexity of O(n²).

Conclusion :
Thus, the Chain Matrix Multiplication problem was successfully solved using Dynamic Programming. By storing previously calculated results and reusing them, the algorithm avoids repeated calculations and efficiently finds the minimum multiplication cost. The experiment demonstrates how Dynamic Programming can significantly improve the efficiency of problems having overlapping subproblems and optimal substructure. The execution time also helps in analyzing the practical performance of the algorithm.

Practical 10:

Summary :
Kruskal’s Algorithm is a greedy approach used to find the Minimum Spanning Tree (MST) of a weighted graph. It starts by sorting all the edges from the smallest weight to the largest. Then, it picks the edges one by one, making sure that no selected edge creates a cycle. The Union-Find technique is used to check for cycles efficiently. This process continues until all vertices are connected with the minimum possible total cost.

Conclusion :
In this implementation, Kruskal’s Algorithm successfully finds the Minimum Spanning Tree by selecting the most suitable edges while avoiding unnecessary cycles. It is simple, efficient, and useful for problems where we need to connect different points with minimum total cost, such as network design, roads, and communication systems. The algorithm has a time complexity of O(E log E), mainly because the edges need to be sorted.

Practical 9:

Summary :
Prim’s Algorithm is a greedy algorithm used to find the Minimum Spanning Tree (MST) of a weighted, connected graph. It starts from any one vertex and gradually connects the remaining vertices by choosing the minimum-weight edge at each step. The algorithm makes sure that each new edge connects a visited vertex to an unvisited vertex, so unnecessary cycles are avoided. In the implementation, the graph is represented using an adjacency list, and the selected edges are stored to form the MST.

Conclusion:
In this implementation, Prim’s Algorithm successfully connects all the vertices with the minimum possible total cost. It is easy to understand because it grows the MST step by step from a starting vertex. Prim’s Algorithm is useful in real-world applications such as computer networks, road connections, and communication systems, where we need to connect multiple points while keeping the overall cost low. The simple implementation used here has a time complexity of O(V²).
