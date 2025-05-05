# AI-Lab

# 📌 Project Aims
| **S.No** | **Practical Title**              | **Aim / Objective**                                                                                                         |
| :------: | :------------------------------- | :-------------------------------------------------------------------------------------------------------------------------- |
|    1️⃣   | Implement BFS                    | Implement Breadth-First Search (BFS) traversal on a given graph dataset using queue-based level-order traversal.            |
|    2️⃣   | Implement DFS                    | Implement Depth-First Search (DFS) traversal on a given graph dataset using stack or recursion for deep exploration.        |
|    3️⃣   | Solve 8-Queens Problem           | Solve the 8-Queens problem using backtracking to place 8 queens without conflicts on an 8×8 chessboard.                     |
|    4️⃣   | Explore NLP Tools                | Explore and demonstrate open-source NLP libraries such as NLTK and spaCy for text processing tasks.                         |
|    5️⃣   | Perform Text Preprocessing       | Implement tokenization, stopword removal, and stemming using NLTK on a sample text corpus.                                  |
|    6️⃣   | Compute TF & IDF                 | Write a Python program to compute Term Frequency (TF) and Inverse Document Frequency (IDF) for a text dataset.              |
|    7️⃣   | Feature Extraction & Analysis    | Perform feature extraction techniques (word count, n-grams, TF-IDF) and analyze feature importance in text.                 |
|    8️⃣   | NLP-based Spam Filter            | Develop an NLP-based spam filter using machine learning models (Naive Bayes, Logistic Regression) with TF-IDF features.     |
|    9️⃣   | Robot Traversal using Perceptron | Implement robot traversal problem simulation using perceptron and multi-class classification models for movement decisions. |
|    🔟    | Tic-Tac-Toe Game                 | Build a Tic-Tac-Toe game in Python with basic AI and game logic for interactive play.                                       |
|  1️⃣1️⃣  | AI-driven Expert System          | Implement a prototype expert system using AI techniques for automated decision support in a domain.                         |
|  1️⃣2️⃣  | AI for Real-World NLP            | Develop an AI system for real-world NLP tasks (e.g., automated RFP evaluation) using LangChain, RAG, and LLM-based agents.  |

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
In this practical, we explore popular open-source libraries for NLP such as NLTK and spaCy:
- NLTK (Natural Language Toolkit): Provides interfaces and tools for tasks like tokenization, stemming, tagging, parsing, and classification.
- spaCy: An industrial-strength NLP library, known for its speed and efficiency, supporting tasks like named entity recognition, part-of-speech tagging, and dependency parsing.
- Both libraries simplify handling complex NLP pipelines for research and production.

# 📝 Text Preprocessing for NLP Applications
5️⃣ Perform text preprocessing on a chosen case study application
-> Implement a program to perform tokenization
-> Eliminate stopwords
-> Apply stemming using NLTK
Preprocessing is essential to clean and prepare raw text for analysis. In this practical:
- Tokenization: Splitting the text into smaller units like words or sentences.
- Stopword Removal: Eliminating commonly used words that may not be useful for analysis (e.g., "the", "and", "is").
- Stemming: Reducing words to their base or root form (e.g., "running" → "run").
These steps improve the quality of input for NLP models.

# 📊 Feature Engineering in NLP
6️⃣ Implement a Python program to compute Term Frequency (TF) and Inverse Document Frequency (IDF)
Feature engineering helps convert textual data into numerical form for machine learning algorithms.
- Term Frequency (TF): Measures how frequently a word occurs in a document.
- Inverse Document Frequency (IDF): Measures how important a word is across multiple documents.
- TF-IDF helps in highlighting important words in a corpus and is widely used in information retrieval and text mining.

7️⃣ Perform feature extraction and analysis techniques on processed text
In this practical:
- Extract features such as word counts, n-grams, TF-IDF vectors.
- Analyze the importance of features based on frequency, uniqueness, and contribution to classification tasks.
- Feature extraction transforms unstructured text into structured formats suitable for machine learning models.


# 🤖 AI Algorithms for NLP Analysis
8️⃣ Develop an NLP-based Spam Filter using Python
In this practical:
- Use machine learning models (e.g., Naive Bayes, Logistic Regression) to classify emails or messages as spam or ham (not spam).
- Apply preprocessing techniques like tokenization, stopword removal, and TF-IDF feature extraction.
- Train and evaluate models on labeled datasets to detect spam effectively.
Spam filters are an important real-world application of NLP and AI.

# 🏎️ AI-Based Robotics & Decision Systems
9️⃣ Implement the Robot Traversal Problem using Perceptron models and multi-category models
In this practical:
- Simulate robot traversal on a grid using Perceptron models and multi-class classification.
- The perceptron algorithm learns to decide the robot's movement direction based on sensory input. This practical demonstrates how simple AI models can drive decision-making in robotics.


# 🎮 AI in Game Development
🔟 Implement a Tic-Tac-Toe game using Python
In this practical:
- Build a Tic-Tac-Toe game using Python.
- Implement basic game logic, player move validation, win/tie condition checks, and simple AI to play against. This game demonstrates AI logic design in a fun and interactive setting.


# 🏥 Expert Systems & Case Studies and Real-World AI Case Studies
1️⃣1️⃣ Implement AI-driven Expert Systems and 1️⃣2️⃣ Implement AI solutions for real-world NLP tasks:
- Request for Proposal (RFP) evaluation is a time-consuming and error-prone task that often involves manually reviewing lengthy documents against complex eligibility criteria. This traditional process leads to inefficiencies, missed opportunities, and inconsistent compliance assessment.
- To address this, we propose an intelligent, multi-agent system powered by Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to automate and streamline the RFP evaluation workflow.
- Built using Python, LangChain, CrewAI, and LLaMA2, and integrated with ChromaDB for vector-based semantic search, the system employs coordinated AI agents to analyze RFPs, retrieve relevant context, match them against company capabilities, and generate detailed compliance reports. The architecture supports modularity, explainability, and real-time decision-making through an intuitive frontend powered by HTML, CSS, and JavaScript.
-  Experimental results demonstrate a 60% improvement in evaluation speed and an 80% reduction in manual effort, while maintaining accuracy and interpretability. This approach sets the foundation for AI-driven automation in enterprise bidding processes, offering scalability and reliability for government and industrial procurement systems.




