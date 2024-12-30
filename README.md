

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
The first challenge involved sorting an array of integers using a modified binary insertion sort. The idea was to use binary search to find the correct position for the element, reducing the time complexity of finding the right insertion point from O(n) to O(log n).

We implemented the binary sort by:
- Iterating over each element starting from the second element.
- Using binary search to determine where the element should be inserted.
- Shifting the elements accordingly and placing the element in the correct position.

This approach optimized the traditional insertion sort, making it more efficient.

### **2. Magical Subarray**
In the second challenge, we were tasked with finding the maximum number of treasures (`'T'`) in a connected region of a grid. The grid also contains obstacles (`'#'`), and we were to perform a depth-first search (DFS) to explore the grid and find the connected components containing treasures.

To solve this:
- We used DFS to traverse the grid from the starting point.
- We maintained a count of treasures encountered during the traversal.
- We backtracked after visiting all valid neighbors to ensure all possible paths were explored.

This method allowed us to find the connected region with the maximum treasures efficiently.

### **3. String Transformation Journey**
In the third problem, we were asked to transform one word into another by changing one character at a time, such that each intermediate word is also in the given list of words. We used a **breadth-first search (BFS)** approach to find the shortest transformation sequence.

The key idea was:
- Check if two words are adjacent by ensuring only one character differs.
- Use BFS to explore the possible transformations, starting from the initial word and adding neighbors to the queue.
- Track visited words to avoid cycles and ensure the shortest path is found.

### **4. Optimal Office Collaboration Schedule**
The fourth challenge required us to minimize the isolation between team members while scheduling meetings. The goal was to ensure that each team member meets with others in the fewest number of weeks, given constraints on the number of weeks available.

We approached this problem by:
- First, ensuring that the number of weeks (`w`) was sufficient to accommodate all necessary meetings.
- Distributing the team members over the weeks using a round-robin strategy to minimize isolation.
- Calculating the minimum isolation by dividing the weeks by the number of team pairs and ensuring no member is left out.

This strategy allowed us to generate an optimal schedule where isolation was minimized.

---

## **Linked List Problem**

We will update this section with the code for the linked list solution once it is ready.

---

## **Conclusion**
This was a great learning experience, and we enjoyed working together to solve these challenges. Each problem provided us with a unique opportunity to apply different algorithms and techniques, helping us improve our coding skills and problem-solving abilities.
We hope our solutions are both efficient and effective, showcasing our approach to optimizing traditional algorithms.

---

### **Acknowledgements**
We would like to thank the organizers of **Code Clash** at **Lovely Professional University** for this opportunity. It was an enriching experience, and we look forward to participating in more such events in the future.
