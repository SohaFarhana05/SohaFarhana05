<h1 align="center"><b>Hi , I'm <span style="background: linear-gradient(45deg, #1e3a8a, #3b82f6, #60a5fa, #93c5fd); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Soha Farhana</span> </b><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>


## My portfolio website - [Portfolio](https://sohafarhana05.github.io/Portfolio/)

<!-- Animated About Me -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=60A5FA&center=true&vCenter=true&width=500&lines=Data+Science+Student+%40+IIT+Madras;Computer+Science+%40+NIT+Andhra+Pradesh;Machine+Learning+Enthusiast;Full+Stack+Developer;Google+Girl+Hackathon+Semi-finalist;JPMC+Code+for+Good'25+Semi-finalist;ML+Intern+%40+IIIT+Hyderabad;Mathematics+Enthusiast" alt="Typing SVG" />
</p>

- 🔭 I'm currently working on modification of my passion project - **Resume Analyzer**
- 🌱 I'm currently learning the holy grail for cs - **PDSA** and also to make **good websites**.
- 📚 Building my **DSA knowledge** with deep understanding - check out my [learning guide](#-dsa-learning-journey) below!
- 🧮 I'm passionate about **Mathematics** - achieved 99.999 percentile in JEE Main Math!
- 💬 Ask me about **anything**.
- 📫 How to reach me: My email - **sohafarhana@gmail.com**
- 😄 Pronouns: **She/Her**
- ⚡ Fun fact: I was born on the **same day as Sundar Pichai**.

## About me

### 🎓 Education
| Name of the college                   | Stream            | Year      | Status |
|---------------------------------------|-------------------|-----------|--------|
| Indian Institute of Technology, Madras | Data Science      | 2024-2028 | 🎯 Current |
| National Institute of Technology, Andhra Pradesh | Computer Science  | 2022-2026 | 🎯 Current |
| Narayana Junior College               | MPC               | 2020-2022 | ✅ Completed |

### 🏆 Achievements

* 🎯 **JEE Advanced Qualified** - Achieved **99.999 percentile** in JEE Main Mathematics.
* 🥈 **Semi-finalist** at the **Google Girl Hackathon 2025**.
* 🥈 **Semi-finalist** at **JPMC Code for Good'25**.
* ⭐ **4 star** in Python, Java, C, SQL in **Hackerrank**.

### 💼 Experience
* 🤖 **Machine Learning Intern** at **International Institute of Technology, Hyderabad** *(June 2025-Sep 2025)*
* 🧠 **AI Intern** at **Infosys SpringBoard** *(Dec 2024 - Mar 2025)*
* 👥 **Co-Secretary** at **CSE Association at NIT Andhra Pradesh** *(Oct 2023 - Sep 2025)*

---

## 📚 DSA Learning Journey

> **Philosophy**: Understanding over Memorization. This guide focuses on building intuition and deep comprehension of data structures and algorithms.

### 🎯 Why Learn DSA?
- **Problem-Solving Skills**: DSA teaches you how to break down complex problems into manageable pieces
- **Efficiency Matters**: Learn to write code that scales from 100 to 1 million users
- **Interview Preparation**: Master the concepts that top tech companies evaluate
- **Better Developer**: Understand what happens under the hood of libraries and frameworks

---

### 📖 Learning Path

#### 🌟 Phase 1: Foundations - Understanding Complexity

<details>
<summary><b>Time & Space Complexity Analysis</b></summary>

**Why it matters**: Before optimizing, you need to measure. Complexity analysis helps you compare solutions objectively.

**Key Concepts**:
- **Big O Notation**: Upper bound - worst case scenario
- **Big Ω (Omega)**: Lower bound - best case scenario  
- **Big Θ (Theta)**: Tight bound - average case

**Common Complexities** (from best to worst):
```
O(1)         - Constant      : Array access, hash table lookup
O(log n)     - Logarithmic   : Binary search, balanced BST operations
O(n)         - Linear        : Single loop, linear search
O(n log n)   - Linearithmic  : Efficient sorting (merge sort, quick sort)
O(n²)        - Quadratic     : Nested loops, bubble sort
O(2ⁿ)        - Exponential   : Recursive fibonacci without memoization
O(n!)        - Factorial     : Generating all permutations
```

**Space Complexity**: Memory used by your algorithm
- Input space: Memory for input data (usually not counted)
- Auxiliary space: Extra memory used by algorithm (this is what we analyze)

**Practice Thinking**: 
- Look at each loop: Is it O(n)?
- Nested loops: Usually O(n²)
- Divide and conquer: Often O(log n) or O(n log n)
- Recursive calls: Draw the recursion tree

</details>

<details>
<summary><b>How to Approach a Problem</b></summary>

**Step-by-step Problem Solving Framework**:

1. **Understand**: Read carefully, identify inputs/outputs, ask clarifying questions
2. **Examples**: Work through 2-3 examples manually, including edge cases
3. **Brute Force**: Start with the simplest solution that works (even if slow)
4. **Optimize**: Look for patterns, redundant work, better data structures
5. **Code**: Write clean, readable code with good variable names
6. **Test**: Test with your examples + edge cases (empty, single element, duplicates)

**Common Optimization Patterns**:
- Use hash tables to trade space for time (O(n) space to reduce O(n²) time)
- Two pointers to avoid nested loops
- Sorting first can simplify many problems
- Binary search when dealing with sorted data
- Dynamic Programming for overlapping subproblems

</details>

---

#### 🧱 Phase 2: Fundamental Data Structures

<details>
<summary><b>1. Arrays & Strings</b></summary>

**Conceptual Understanding**:
- Contiguous memory locations with constant-time access
- Fixed size (in most languages) or dynamic (like Python lists/Java ArrayLists)

**Why use Arrays?**
- Fast access: O(1) to get any element by index
- Cache-friendly: Elements are stored together in memory
- Simple to use and understand

**Common Patterns**:
- **Two Pointers**: For sorted arrays or palindromes (O(n) instead of O(n²))
- **Sliding Window**: For subarrays/substrings with specific properties
- **Prefix Sum**: For range sum queries
- **Kadane's Algorithm**: Maximum subarray sum

**When to use Strings**:
- Text processing, pattern matching
- String manipulation is array manipulation with characters

**Common Pitfalls**:
- Strings are immutable in many languages (Java, Python) - concatenation is O(n)
- Use StringBuilder/StringBuffer for multiple concatenations

**Time Complexities**:
- Access: O(1)
- Search: O(n)
- Insertion/Deletion at end: O(1) amortized (dynamic arrays)
- Insertion/Deletion in middle: O(n)

</details>

<details>
<summary><b>2. Linked Lists</b></summary>

**Conceptual Understanding**:
- Nodes connected by pointers/references
- Each node contains data + reference to next node
- Types: Singly, Doubly, Circular

**Why use Linked Lists?**
- Dynamic size: Grows/shrinks easily
- Efficient insertion/deletion at any position (if you have the pointer)
- No wasted memory from pre-allocated space

**When NOT to use**:
- Need random access (O(n) instead of O(1))
- Memory overhead from storing pointers
- Not cache-friendly

**Key Techniques**:
- **Fast & Slow Pointers** (Floyd's): Detect cycles, find middle
- **Dummy Head**: Simplifies edge cases (empty list, single node)
- **Reverse in-place**: Use three pointers (prev, current, next)

**Common Problems**:
- Detect cycle, find cycle start
- Merge two sorted lists
- Reverse a linked list
- Find nth node from end (two pointers)

**Time Complexities**:
- Access: O(n)
- Search: O(n)
- Insertion/Deletion (with pointer): O(1)
- Insertion/Deletion (without pointer): O(n)

</details>

<details>
<summary><b>3. Stacks</b></summary>

**Conceptual Understanding**:
- LIFO (Last In, First Out) - like a stack of plates
- Think "undo" functionality or function call stack

**Core Operations**:
- Push: Add to top - O(1)
- Pop: Remove from top - O(1)  
- Peek: Look at top - O(1)

**When to use Stacks**:
- Need to reverse something
- Parsing expressions (balanced parentheses)
- Backtracking problems
- DFS (Depth-First Search) implementation
- Function call management

**Classic Problems**:
- **Balanced Parentheses**: Push opening, pop on closing
- **Next Greater Element**: Stack keeps potential candidates
- **Evaluate Postfix/Prefix**: Stack for operands
- **Stock Span Problem**: Days until previous higher price
- **Implement Min Stack**: Track minimum in O(1)

**Implementation**:
- Array-based or Linked List-based
- Most languages have built-in stack (Python list, Java Stack)

</details>

<details>
<summary><b>4. Queues</b></summary>

**Conceptual Understanding**:
- FIFO (First In, First Out) - like a line at a counter
- Think ticket systems, printer queue, BFS

**Core Operations**:
- Enqueue: Add to rear - O(1)
- Dequeue: Remove from front - O(1)
- Peek: Look at front - O(1)

**Types**:
- **Simple Queue**: Basic FIFO
- **Circular Queue**: Efficient space usage
- **Deque** (Double-ended): Add/remove from both ends
- **Priority Queue**: Elements have priorities (usually implemented with heap)

**When to use Queues**:
- BFS (Breadth-First Search) traversal
- Level-order tree traversal
- Request handling (first-come-first-served)
- Scheduling algorithms

**Classic Problems**:
- BFS in graphs/trees
- Sliding window maximum (using deque)
- Generate binary numbers from 1 to n
- Level order traversal

**Implementation**:
- Array with two pointers (circular)
- Linked List (most flexible)
- Python: collections.deque, Java: Queue interface

</details>

---

#### 🌳 Phase 3: Tree & Graph Structures

<details>
<summary><b>5. Trees</b></summary>

**Conceptual Understanding**:
- Hierarchical structure with root and children
- Each node has at most one parent
- No cycles (unlike graphs)

**Types**:
- **Binary Tree**: Each node has at most 2 children
- **Binary Search Tree (BST)**: Left < Root < Right
- **Balanced Trees**: AVL, Red-Black (height difference ≤ 1)
- **Heap**: Complete binary tree with heap property
- **Trie**: Prefix tree for strings

**Binary Search Tree - Deep Dive**:

*Why BST?*
- Combines benefits of arrays (fast search) and linked lists (fast insertion/deletion)
- Search/Insert/Delete: O(log n) average, O(n) worst case
- Balanced BSTs guarantee O(log n): AVL trees, Red-Black trees

*BST Operations*:
- **Search**: Compare with root, go left or right
- **Insert**: Find position, add as leaf
- **Delete**: Three cases (leaf, one child, two children)

**Tree Traversals** (CRITICAL to understand):

```
        1
       / \
      2   3
     / \
    4   5
```

- **Preorder** (Root-Left-Right): `1,2,4,5,3` - Used for copying trees
- **Inorder** (Left-Root-Right): `4,2,5,1,3` - BST gives sorted order!
- **Postorder** (Left-Right-Root): `4,5,2,3,1` - Used for deleting trees
- **Level-order** (BFS): `1,2,3,4,5` - Used for level-by-level processing

**Key Patterns**:
- **Recursion**: Most tree problems are naturally recursive
- **DFS**: Preorder/Inorder/Postorder (use stack or recursion)
- **BFS**: Level-order (use queue)
- **Two trees**: Often need to compare node by node

**Common Problems**:
- Validate BST
- Lowest Common Ancestor (LCA)
- Maximum/Minimum depth
- Check if balanced
- Serialize/Deserialize tree
- Path sum problems

**Time Complexities** (BST):
- Search/Insert/Delete: O(log n) average, O(n) worst
- Traversal: O(n)

</details>

<details>
<summary><b>6. Heaps</b></summary>

**Conceptual Understanding**:
- Complete binary tree with heap property
- **Max Heap**: Parent ≥ Children (root is maximum)
- **Min Heap**: Parent ≤ Children (root is minimum)

**Why use Heaps?**
- Get min/max in O(1)
- Insert/delete in O(log n)
- Perfect for priority-based problems

**Implementation**:
- Usually as array: For node at index i:
  - Left child: 2i + 1
  - Right child: 2i + 2
  - Parent: (i-1)/2

**Core Operations**:
- **Insert**: Add at end, bubble up - O(log n)
- **Extract Min/Max**: Remove root, move last to root, bubble down - O(log n)
- **Peek**: See root - O(1)
- **Heapify**: Convert array to heap - O(n)

**When to use Heaps**:
- K largest/smallest elements
- Continuous median from stream
- Merge K sorted lists/arrays
- Scheduling with priorities
- Dijkstra's shortest path

**Classic Problems**:
- Kth largest element
- Merge K sorted lists
- Find median from data stream
- Top K frequent elements
- Meeting rooms II

</details>

<details>
<summary><b>7. Hash Tables</b></summary>

**Conceptual Understanding**:
- Maps keys to values using hash function
- Goal: O(1) average lookup, insert, delete

**How it works**:
1. Hash function converts key to array index
2. Store value at that index
3. Handle collisions (chaining or open addressing)

**Why use Hash Tables?**
- Fastest lookup: O(1) average
- Great for "seen before" problems
- Counting frequencies
- Two-sum type problems

**Collision Resolution**:
- **Chaining**: Each bucket is a linked list
- **Open Addressing**: Find next empty slot

**When to use**:
- Need fast lookup/insertion
- Counting occurrences
- Checking for duplicates
- Group anagrams
- Two sum, three sum problems

**Limitations**:
- No ordering (use TreeMap/SortedDict if needed)
- Space overhead
- Hash function quality matters

**Common Patterns**:
- **Frequency Map**: Count occurrences
- **Seen Set**: Check if element exists
- **Index Map**: Store index of elements for two-sum
- **Group by Key**: Group anagrams, phone numbers

**Time Complexities**:
- Average: O(1) for search/insert/delete
- Worst case: O(n) (poor hash function or many collisions)

</details>

<details>
<summary><b>8. Graphs</b></summary>

**Conceptual Understanding**:
- Vertices (nodes) connected by edges
- Can have cycles (unlike trees)
- Can be directed or undirected

**Representations**:
- **Adjacency Matrix**: 2D array, O(V²) space, O(1) edge lookup
- **Adjacency List**: Array of lists, O(V+E) space, O(degree) edge lookup
- Most problems: Use adjacency list (more space-efficient)

**Types**:
- **Directed vs Undirected**: One-way vs two-way edges
- **Weighted vs Unweighted**: Edges have costs or not
- **Cyclic vs Acyclic**: Has cycles or not (DAG = Directed Acyclic Graph)

**Graph Traversals**:

**DFS (Depth-First Search)**:
- Go deep before going wide
- Use stack (or recursion)
- Applications: Detect cycles, topological sort, connected components

**BFS (Breadth-First Search)**:
- Level by level exploration
- Use queue
- Applications: Shortest path (unweighted), level-based problems

**When to use which**:
- BFS: Shortest path, level-order, minimum steps
- DFS: Path existence, cycles, connected components, backtracking

**Advanced Algorithms**:
- **Dijkstra**: Shortest path in weighted graph (non-negative weights)
- **Bellman-Ford**: Shortest path with negative weights
- **Floyd-Warshall**: All pairs shortest path
- **Kruskal/Prim**: Minimum spanning tree
- **Topological Sort**: Linear ordering of DAG vertices

**Common Patterns**:
- **Visited Set**: Avoid infinite loops in cycles
- **Parent Map**: Track path for reconstruction
- **Distance/Level Map**: Track shortest distance

**Classic Problems**:
- Number of islands
- Clone a graph
- Course schedule (topological sort)
- Word ladder
- Shortest path in maze
- Detect cycle

</details>

---

#### ⚡ Phase 4: Algorithms

<details>
<summary><b>9. Searching Algorithms</b></summary>

**Linear Search**:
- Check each element: O(n)
- Use when: Small array or unsorted data

**Binary Search** (IMPORTANT):
- Only works on sorted data
- Divide and conquer: O(log n)

**Template**:
```python
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    
    while left <= right:
        mid = left + (right - left) // 2  # Avoid overflow
        
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1  # Search right half
        else:
            right = mid - 1  # Search left half
    
    return -1  # Not found
```

**Binary Search Variations**:
- Find first/last occurrence
- Find insertion position
- Search in rotated sorted array
- Find peak element
- Search in 2D matrix

**When to think Binary Search**:
- Sorted array
- Search space can be divided
- Monotonic function (increases/decreases)
- "Minimum/maximum value such that condition holds"

</details>

<details>
<summary><b>10. Sorting Algorithms</b></summary>

**Why learn sorting?**
- Preprocessing step for many algorithms
- Understanding efficiency trade-offs
- Interview classic

**Comparison-based Sorts**:

**Bubble Sort**: O(n²)
- Repeatedly swap adjacent elements if wrong order
- Simple but inefficient
- Good for: Nearly sorted data, educational purposes

**Selection Sort**: O(n²)
- Find minimum, move to front, repeat
- Never use in practice (no advantages)

**Insertion Sort**: O(n²)
- Build sorted array one element at a time
- Good for: Small arrays, nearly sorted data
- Used in: TimSort (Python/Java) for small segments

**Merge Sort**: O(n log n)
- Divide array, sort halves, merge
- Stable, predictable performance
- Drawback: O(n) extra space
- Good for: Linked lists, external sorting

**Quick Sort**: O(n log n) average, O(n²) worst
- Pick pivot, partition, recurse
- In-place, cache-friendly
- Used by: Most standard library sort functions
- Randomize pivot to avoid worst case

**Heap Sort**: O(n log n)
- Build max heap, extract max repeatedly
- In-place, guaranteed O(n log n)
- Not stable, not cache-friendly

**Non-comparison Sorts**:

**Counting Sort**: O(n + k)
- Count occurrences of each value
- Good when range (k) is small

**Radix Sort**: O(d × n)
- Sort digit by digit
- Good for: Fixed-length integers/strings

**When to use what**:
- General purpose: Quick Sort or Merge Sort
- Stable sort needed: Merge Sort
- Small arrays: Insertion Sort
- Integers in small range: Counting/Radix Sort

</details>

<details>
<summary><b>11. Recursion & Backtracking</b></summary>

**Recursion - Understanding the Concept**:
- Function calling itself with smaller input
- Base case: When to stop
- Recursive case: Break problem into smaller problems

**Three Laws of Recursion**:
1. Must have base case
2. Must change state and move toward base case
3. Must call itself

**Thinking Recursively**:
- Don't trace execution in your head (trust the recursion)
- Define: What should this function do?
- Base case: Simplest input
- Recursive case: How to break into smaller problems?

**Common Patterns**:
- Divide and conquer (merge sort, binary search)
- Tree traversal (naturally recursive)
- Backtracking (generate all solutions)

**Backtracking - Systematic Exploration**:
- Try all possibilities
- Abandon path when it can't lead to solution
- "Build solution piece by piece"

**Backtracking Template**:
```python
def backtrack(state, choices):
    if is_valid_solution(state):
        output(state)
        return
    
    for choice in choices:
        make_choice(state, choice)
        backtrack(state, remaining_choices)
        undo_choice(state, choice)  # KEY: Backtrack!
```

**Classic Backtracking Problems**:
- Generate all permutations/combinations
- N-Queens problem
- Sudoku solver
- Word search in grid
- Generate parentheses
- Subset sum

**Optimization - Memoization**:
- Cache results to avoid recomputation
- Turns many exponential problems into polynomial

</details>

<details>
<summary><b>12. Dynamic Programming (DP)</b></summary>

**What is DP?**
- Optimization technique for overlapping subproblems
- "Fancy recursion with memory"

**When to use DP**:
1. **Optimal Substructure**: Optimal solution contains optimal solutions to subproblems
2. **Overlapping Subproblems**: Same subproblems solved multiple times

**Two Approaches**:

**Top-Down (Memoization)**:
- Start with big problem, break down
- Use recursion + cache
- More intuitive, easier to write

**Bottom-Up (Tabulation)**:
- Start with smallest problems, build up
- Use iteration + table
- More efficient (no recursion overhead)

**DP Thinking Process**:
1. **Define state**: What information do I need to know?
2. **Find recurrence**: How does state[i] relate to previous states?
3. **Base cases**: What are the simplest cases?
4. **Order of computation**: Bottom-up order
5. **Answer location**: Where is final answer?

**Classic DP Problems**:

**1. Fibonacci** (Introduction):
- State: dp[i] = ith Fibonacci number
- Recurrence: dp[i] = dp[i-1] + dp[i-2]

**2. Climbing Stairs**:
- State: dp[i] = ways to reach step i
- Recurrence: dp[i] = dp[i-1] + dp[i-2]

**3. Coin Change**:
- State: dp[i] = min coins to make amount i
- Recurrence: dp[i] = min(dp[i - coin] + 1) for all coins

**4. Longest Common Subsequence (LCS)**:
- State: dp[i][j] = LCS length of s1[0..i] and s2[0..j]
- Recurrence: 
  - If s1[i] == s2[j]: dp[i][j] = dp[i-1][j-1] + 1
  - Else: dp[i][j] = max(dp[i-1][j], dp[i][j-1])

**5. Knapsack Problem**:
- State: dp[i][w] = max value using first i items with weight limit w
- Classic optimization problem

**DP Patterns**:
- **Linear DP**: 1D array (Fibonacci, house robber)
- **2D DP**: 2D array (LCS, edit distance, knapsack)
- **State Machine DP**: Different states (stock buy/sell)
- **Interval DP**: Subproblems are intervals (burst balloons)

**Space Optimization**:
- Often only need previous row/column
- Reduce O(n²) space to O(n)

</details>

<details>
<summary><b>13. Greedy Algorithms</b></summary>

**What is Greedy?**
- Make locally optimal choice at each step
- Hope it leads to globally optimal solution

**Key Difference from DP**:
- Greedy: Make irrevocable choice (can't backtrack)
- DP: Consider all options

**When does Greedy work?**
- Problem has **greedy choice property**: Local optimal → Global optimal
- Problem has **optimal substructure**
- Must prove correctness! (Exchange argument, contradiction)

**Common Greedy Patterns**:

**1. Interval Scheduling**:
- Sort by end time, pick non-overlapping
- Example: Meeting rooms, activity selection

**2. Fractional Knapsack**:
- Sort by value/weight ratio
- Take items greedily

**3. Huffman Coding**:
- Build optimal prefix-free code
- Use min heap for frequencies

**4. Minimum Spanning Tree**:
- Kruskal: Sort edges, add if no cycle
- Prim: Grow tree from starting vertex

**Classic Problems**:
- Jump game
- Gas station
- Assign cookies
- Partition labels
- Minimum arrows to burst balloons

**How to identify Greedy problems**:
- "Minimum/maximum"
- Sorting often helps
- Can you prove local optimal = global optimal?

**Common Mistake**:
- Assuming greedy works without proof
- Test with counter-examples!

</details>

<details>
<summary><b>14. Two Pointers & Sliding Window</b></summary>

**Two Pointers Technique**:

**When to use**:
- Array/string problems with pairs or partitions
- Can reduce O(n²) to O(n)

**Patterns**:

**1. Opposite Direction**:
- Start from both ends, move toward center
- Use cases: Two sum (sorted array), palindrome check, container with most water

**2. Same Direction** (Fast & Slow):
- Both start at beginning, move at different speeds
- Use cases: Remove duplicates, linked list cycle, move zeros

**3. Sliding Window** (Special case):
- Fixed or variable size window
- Use cases: Maximum sum subarray, longest substring without repeating characters

**Sliding Window Deep Dive**:

**Fixed Size Window**:
```python
# Max sum of k consecutive elements
for i in range(k):
    window_sum += arr[i]

max_sum = window_sum
for i in range(k, n):
    window_sum += arr[i] - arr[i - k]  # Slide
    max_sum = max(max_sum, window_sum)
```

**Variable Size Window**:
```python
# Longest substring without repeating
left = 0
seen = set()

for right in range(n):
    while s[right] in seen:
        seen.remove(s[left])
        left += 1  # Shrink window
    seen.add(s[right])
    max_length = max(max_length, right - left + 1)
```

**When to use Sliding Window**:
- Contiguous subarray/substring
- "Longest/shortest/maximum/minimum"
- Can maintain window state efficiently

**Classic Problems**:
- Maximum sum of k consecutive elements
- Longest substring without repeating characters
- Minimum window substring
- Permutation in string
- Fruits into baskets

</details>

---

#### 🎓 Phase 5: Advanced Topics

<details>
<summary><b>15. Bit Manipulation</b></summary>

**Why learn Bit Manipulation?**
- Space-efficient (one bit per boolean)
- Fast operations (CPU-level)
- Interview favorite

**Basic Operations**:
- `&` AND: Both bits 1 → 1
- `|` OR: At least one bit 1 → 1
- `^` XOR: Different bits → 1 (same → 0)
- `~` NOT: Flip bits
- `<<` Left shift: Multiply by 2
- `>>` Right shift: Divide by 2

**Useful Tricks**:
- Check if odd: `n & 1 == 1`
- Check if power of 2: `n & (n-1) == 0`
- Set ith bit: `n | (1 << i)`
- Clear ith bit: `n & ~(1 << i)`
- Toggle ith bit: `n ^ (1 << i)`
- Get ith bit: `(n >> i) & 1`

**XOR Properties** (Very useful):
- `a ^ a = 0` (same numbers cancel)
- `a ^ 0 = a` (identity)
- `a ^ b ^ a = b` (commutative)

**Classic Problems**:
- Single number (XOR all, pairs cancel)
- Missing number
- Counting bits
- Reverse bits
- Hamming distance

</details>

<details>
<summary><b>16. Trie (Prefix Tree)</b></summary>

**What is Trie?**
- Tree structure for storing strings
- Each path represents a word
- Share common prefixes

**Why use Trie?**
- Fast prefix search: O(m) where m is string length
- Autocomplete functionality
- Spell checkers
- IP routing

**Operations**:
- Insert: O(m)
- Search: O(m)
- Prefix search: O(p + n) where p is prefix length, n is results

**When to use**:
- Dictionary operations
- Autocomplete
- Prefix matching
- Word games (Boggle, Scrabble)

**Classic Problems**:
- Implement Trie
- Word search II
- Design search autocomplete
- Replace words
- Longest word in dictionary

</details>

<details>
<summary><b>17. Union Find (Disjoint Set)</b></summary>

**What is Union Find?**
- Data structure to track connected components
- Two operations: Union (connect) and Find (which set?)

**Why use Union Find?**
- Dynamic connectivity queries
- Detect cycles in undirected graph
- Find connected components efficiently

**Optimizations**:
- **Path Compression**: Flatten tree on Find
- **Union by Rank**: Attach smaller tree under larger

**Time Complexity**:
- With optimizations: O(α(n)) ≈ O(1) amortized
- α(n) is inverse Ackermann function (grows extremely slowly)

**When to use**:
- Connected components in dynamic graph
- Kruskal's MST algorithm
- Network connectivity
- Percolation problems

**Classic Problems**:
- Number of islands
- Friend circles
- Redundant connection
- Accounts merge
- Most stones removed

</details>

<details>
<summary><b>18. Segment Trees & Fenwick Trees</b></summary>

**What are they?**
- Advanced data structures for range queries
- Update and query in O(log n)

**Segment Tree**:
- Binary tree where each node represents range
- Use cases: Range sum, range minimum/maximum, range updates

**Fenwick Tree (Binary Indexed Tree)**:
- More space-efficient than segment tree
- Use cases: Range sum, point updates
- Easier to implement but less flexible

**When to use**:
- Multiple range queries/updates
- Array won't be rebuilt frequently
- Need better than O(n) for each query

**Classic Problems**:
- Range sum query mutable
- Count of smaller numbers after self
- Range minimum query

</details>

---

### 🎯 Practice Strategy

**1. Learning Phase** (Understanding):
- Read solution AFTER trying yourself (at least 30 mins)
- Understand WHY the approach works
- Identify the pattern/technique used

**2. Pattern Recognition**:
- Group similar problems
- Create a "pattern catalog" in your mind
- "This looks like two pointers", "This needs DP"

**3. Spaced Repetition**:
- Review problems after 1 day, 1 week, 1 month
- Redo problems you struggled with
- Build long-term retention

**4. Mock Interviews**:
- Practice explaining your thought process
- 45-minute time limit
- Speak while coding

**5. Difficulty Progression**:
- Week 1-2: Easy problems only (build confidence)
- Week 3-4: 80% Easy, 20% Medium
- Week 5-8: 50% Easy, 50% Medium
- Week 9+: 20% Easy, 60% Medium, 20% Hard

---

### 📚 Recommended Resources

**Books**:
- *Grokking Algorithms* by Aditya Bhargava (Visual, beginner-friendly)
- *Cracking the Coding Interview* by Gayle Laakmann McDowell (Interview prep)
- *Introduction to Algorithms* by CLRS (Comprehensive, academic)
- *Algorithm Design Manual* by Steven Skiena (Practical, with war stories)

**Online Platforms**:
- **LeetCode**: Best for interview prep, discuss solutions
- **HackerRank**: Good for beginners, structured learning paths
- **Codeforces**: Competitive programming, harder problems
- **NeetCode**: Curated list of 150 problems covering all patterns

**Video Resources**:
- Abdul Bari (Algorithms) - Excellent explanations
- William Fiset (Data Structures) - Detailed implementations
- NeetCode (LeetCode solutions) - Clean code, clear explanations
- Back to Back SWE - In-depth problem solving

**Visualization Tools**:
- VisuAlgo - Visualize algorithms step-by-step
- Algorithm Visualizer - Interactive algorithm animations

---

### 💡 Key Takeaways

1. **Understand, don't memorize**: Focus on WHY, not just HOW
2. **Pattern recognition**: Most problems are variations of common patterns
3. **Start simple**: Brute force first, then optimize
4. **Practice consistently**: 1-2 problems daily > 20 problems once a week
5. **Learn from mistakes**: Review wrong approaches, understand why they fail
6. **Explain out loud**: If you can't explain it, you don't understand it
7. **Code by hand**: Interview conditions - practice without IDE

**Remember**: Every expert was once a beginner. Progress > Perfection! 🚀

</details>

---

<!-- Connect with me -->
<h3 align="center">🌐 Connect with me:</h3>
<p align="center">
  <a href="https://sohafarhana05.github.io/Portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:sohafarhana@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/sohafarhana/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/SohaFarhana05" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<!-- Inspirational Quote -->
<div align="center">
  <h3 style="color: #60a5fa;">💭 My Philosophy</h3>
  <p style="font-style: italic; font-size: 18px; color: #93c5fd; max-width: 600px; margin: 0 auto;">
    "Practice makes progress, not perfection. But when you practice with purpose and passion, excellence becomes inevitable."
  </p>
  <p style="color: #60a5fa; font-weight: bold;">- Soha Farhana</p>
</div>

<!-- Footer Message -->
<p align="center">
  <i>✨ Every visitor makes this profile more special! Thanks for stopping by! ✨</i><br>
  <i>💝 If you like my work, consider giving it a ⭐!</i>
</p>

---

<p align="center">
  <i>Built with 🩵 by Soha Farhana</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer"/>
</p>
