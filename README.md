

# **Code Clash - Lovely Professional University**
## **Team Introduction**

We are grateful for the opportunity to participate in the **Code Clash** event at **Lovely Professional University**. Our team consists of two members:

- **Chettim Chetty Hemasri**
- **Ranveer Singh**

We are third-year students from the **SRM Institute of Science and Technology, Kattankulathur**, pursuing our degrees in **Computer Science and Engineering**.

This event provided us with a chance to showcase our problem-solving skills, collaborate as a team, and learn new techniques to tackle complex coding challenges.

---

## **Problem Overview and Approach**

### **1. Binary Sort**
In this problem, we were tasked with sorting an array of integers using an efficient sorting algorithm. We decided to implement **Binary Sort**, which is a more efficient variation of the traditional **Insertion Sort**. 

#### **Approach:**
- Traditional insertion sort compares the current element to all previous elements in the array to find the correct position. This leads to O(n) time complexity for each insertion.
- We optimized this by using **Binary Search** to find the correct insertion point, reducing the time complexity from O(n) to O(log n) when finding the position.
- After finding the correct insertion position, the remaining steps followed the classic insertion sort — shifting elements and placing the current element in its correct position.

#### **Why it’s effective:**
- **Efficiency:** Binary Insertion Sort improves the traditional Insertion Sort by reducing the time spent finding the position, making it more efficient for moderately sized arrays. This approach is particularly effective when dealing with smaller or nearly sorted arrays.
- **Simplicity:** Despite the optimization, the approach remains simple and easy to implement, ensuring the code remains understandable and maintainable.

### **2. Magical Subarray**
The problem asked us to find the maximum number of treasures (`'T'`) in a connected region of a grid while navigating through obstacles (`'#'`).

#### **Approach:**
- We used **Depth-First Search (DFS)** to traverse the grid. The idea was to explore all possible paths starting from the given point, counting the treasures along the way, and backtracking when a dead-end (obstacle or visited cell) is encountered.
- For each valid move, we kept track of the number of treasures found and compared it with the maximum count so far. This ensured that we were always keeping track of the best solution.

#### **Why it’s effective:**
- **Exploration Efficiency:** DFS allows us to explore each path exhaustively, ensuring that we don’t miss any potential treasure-containing regions.
- **Backtracking:** By using backtracking, we avoid revisiting cells and ensure that all connected regions are considered.
- **Scalability:** DFS can efficiently handle even larger grids, ensuring that we can find the maximum treasures even in complex grid layouts.

### **3. String Transformation Journey**
In this challenge, the goal was to transform one word into another, changing one character at a time while ensuring that each intermediate word is a valid word in the given list.

#### **Approach:**
- We decided to use **Breadth-First Search (BFS)** because it’s well-suited for problems involving finding the shortest path or transformation. Each word transformation is treated as a step in a graph, and BFS ensures that we find the shortest transformation sequence.
- The core idea was to check whether two words differ by exactly one character (i.e., they are adjacent). From the starting word, we explored all possible adjacent words in the word list using BFS until we reached the target word.
- We tracked visited words to avoid revisiting them and causing unnecessary loops.

#### **Why it’s effective:**
- **Shortest Path Guarantee:** BFS guarantees that the first time we reach the target word, it’s through the shortest sequence of transformations.
- **Optimization:** By using BFS, we ensure that we explore all possible transformations level by level, preventing redundant checks and making the search more efficient.
- **Simplicity and Accuracy:** BFS is a natural fit for this problem, ensuring correctness while also optimizing the search process.

### **4. Optimal Office Collaboration Schedule**
This problem required us to minimize isolation in a schedule where each member of a team must meet members from other teams over several weeks. The isolation is defined as the maximum gap between any two consecutive meetings or the gap between the first and last meetings of any pair of employees.

#### **Approach:**
- We started by ensuring that the number of weeks (`w`) was sufficient to accommodate all necessary meetings. If `w` was too small to allow each team member to meet all other team members, we immediately output "infinity."
- Then, we used a **round-robin assignment strategy** to assign members to different weeks. In this strategy, each member meets with others in a cyclic order, ensuring that each pair meets at least once over the available weeks.
- We calculated the **minimum isolation** by dividing the number of weeks by the number of team pairs, ensuring that no member is isolated for too long.

#### **Why it’s effective:**
- **Optimal Distribution:** The round-robin strategy ensures that team members are distributed across weeks as evenly as possible, minimizing isolation.
- **Scalability:** This approach is scalable for larger values of `n` and `w`, ensuring that the solution remains efficient even as the number of teams and weeks grows.
- **Simplicity:** The method is straightforward and intuitive, ensuring that the schedule is as balanced as possible with minimal computational overhead.

---

## **Linked List Problem**

The linked list problem involved implementing a **Singly Linked List** with operations such as appending, prepending, inserting after a node, deleting a node, updating node data, and printing the list. The main idea was to work with pointers to dynamically manage the list.

### **Approach:**
- **Singly Linked List Structure:** We defined a `Node` class with `data` and `next` attributes to represent each element in the list. The head pointer points to the first node in the list.
- We implemented various operations like:
  - **appendNode()**: Adds a new node to the end of the list.
  - **prependNode()**: Adds a new node at the beginning of the list.
  - **insertNodeAfter()**: Inserts a new node after an existing node.
  - **deleteNodeByKey()**: Deletes a node with a specific key.
  - **updateNodeByKey()**: Updates a node’s data given a key.
  - **print()**: Prints all the nodes in the list.

### **Why it’s effective:**
- **Dynamic Memory Allocation:** Singly Linked Lists are dynamic in nature, meaning the list can grow and shrink as needed without a fixed size.
- **Efficiency:** Operations like insertion and deletion can be performed in O(1) time, making the list more efficient in certain use cases compared to arrays.
- **Flexibility:** Linked lists are useful in scenarios where memory usage needs to be optimized or when the size of the list is unpredictable.

---

## **Conclusion**
This coding challenge was a great learning opportunity for our team. Each problem provided us with a unique chance to apply different algorithms and data structures, such as **DFS**, **BFS**, **Binary Search**, **Round-Robin scheduling**, and **Linked Lists**, to real-world problems. Through collaboration and careful consideration of the problem constraints, we were able to find effective and optimized solutions for all the challenges presented to us.

We hope our approach showcases our problem-solving skills and ability to adapt to different algorithmic challenges efficiently. We also believe that these solutions are not only correct but also optimized, ensuring scalability and minimal computational overhead.

---

### **Acknowledgements**
We would like to express our gratitude to the organizers of **Code Clash** at **Lovely Professional University** for providing us with this enriching experience. This challenge has enhanced our understanding of various algorithms and has been an excellent opportunity to work together as a team. We look forward to participating in future coding competitions and applying the knowledge gained here.

---

