# AI-Lab

# 📌 Project Aims
# 🔹 Graph Traversal Algorithms
## 1️⃣ Implement Breadth-First Search (BFS) on a given dataset

### 🔹 Concept  
- BFS is a level-wise traversal technique.  
- It explores all nodes at the current depth before moving deeper.  
- Uses a queue (FIFO - First In, First Out) to process nodes in the order they were discovered.  

### 🔹 Algorithm  
- Initialize an empty queue and a visited set.  
- Add the starting node to the queue and mark it as visited.  
- While the queue is not empty:  
  - Dequeue a node and process it.  
  - Add all its unvisited neighbors to the queue and mark them as visited.  
- Repeat until all reachable nodes are visited.  



## 2️⃣ Implement Depth-First Search (DFS) on a given dataset

### 🔹 Concept  
- DFS is a traversal technique that explores as **deep as possible** before backtracking.  
- It follows a **recursive approach** or uses an **explicit stack (LIFO - Last In, First Out)**.  
- DFS is useful for solving problems like **maze traversal, cycle detection, and topological sorting**.  

### 🔹 Algorithm  
- Initialize an empty **stack** (or use recursion) and a **visited set**.  
- Add the **starting node** to the stack and mark it as visited.  
- While the stack is **not empty**:  
  - Pop a node from the stack and process it.  
  - Add all its **unvisited neighbors** to the stack and mark them as visited.  
- Repeat until all reachable nodes are visited.  

# ♟️ Constraint Satisfaction Problem
3️⃣ Solve the 8-Queens Problem with suitable assumptions
### 🔹 Concept
The 8-Queens Problem is a classic Constraint Satisfaction Problem (CSP) in which 8 queens must be placed on an 8×8 chessboard so that no two queens attack each other.
- A queen can attack another queen if they are:
- In the same row
- In the same column
- On the same diagonal
- The goal is to place all 8 queens on the board without conflicts.

### 🔹 Algorithm (Backtracking Approach)
- Start from the first column (col = 0) and try placing a queen in each row.
- Check if placing the queen is safe (i.e., no other queen attacks it).
- Ensure no other queen exists in the same row, column, or diagonal.
- If safe, place the queen and recursively move to the next column.
- If a column has no valid placement, backtrack (remove the last placed queen and try the next possibility).
- Repeat until all 8 queens are placed successfully.
  
# 📖 Natural Language Processing (NLP) with Open-Source Tools
4️⃣ Introduction to open-source NLP tools like NLTK, spaCy, etc.

# 📝 Text Preprocessing for NLP Applications
5️⃣ Perform text preprocessing on a chosen case study application
-> Implement a program to perform tokenization
-> Eliminate stopwords
-> Apply stemming using NLTK

# 📊 Feature Engineering in NLP
6️⃣ Implement a Python program to compute Term Frequency (TF) and Inverse Document Frequency (IDF)
7️⃣ Perform feature extraction and analysis techniques on processed text

# 🤖 AI Algorithms for NLP Analysis
8️⃣ Develop an NLP-based Spam Filter using Python

# 🏎️ AI-Based Robotics & Decision Systems
9️⃣ Implement the Robot Traversal Problem using Perceptron models and multi-category models

# 🎮 AI in Game Development
🔟 Implement a Tic-Tac-Toe game using Python

# 🏥 Expert Systems & Case Studies
1️⃣1️⃣ Implement AI-driven Expert Systems:
-> Course Advisor Expert System: Performance Assessment in Medical Expert Systems

# Real-World AI Case Studies
1️⃣2️⃣ Implement AI solutions for real-world NLP tasks:
-> Sentiment Analysis using NLP
->Fake News Detection using NLP
