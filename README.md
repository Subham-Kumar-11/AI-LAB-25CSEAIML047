# AI LAB - 25CSEAIML047

This repository contains the complete laboratory experiments, source code, and verified execution outputs for the **Artificial Intelligence Laboratory (AI Lab)** coursework.

---

## 📌 Student Details
- **Student Name / Registration**: `25CSEAIML047`
- **Department**: Computer Science and Engineering (AI & ML)
- **Repository URL**: [https://github.com/Subham-Kumar-11/AI-LAB-25CSEAIML047](https://github.com/Subham-Kumar-11/AI-LAB-25CSEAIML047)

---

## 📚 List of Experiments

| Exp No. | Experiment Title | Algorithm / Topic | Source Code | Output Document |
|:-------:|:-----------------|:------------------|:-----------:|:---------------:|
| 1 | Water Jug Problem | State Space Search (BFS) | [`Water_jug.py`](./Water_jug.py) | [`01_Water_jug_output.txt`](./outputs/01_Water_jug_output.txt) |
| 2 | Tic-Tac-Toe Game | Game Playing & Board Evaluation | [`Tic_Tac_Toe.py`](./Tic_Tac_Toe.py) | [`02_Tic_Tac_Toe_output.txt`](./outputs/02_Tic_Tac_Toe_output.txt) |
| 3 | Travelling Salesperson Problem (TSP) | Combinatorial Optimization / Search | [`Travel_Space.py`](./Travel_Space.py) | [`03_Travel_Space_output.txt`](./outputs/03_Travel_Space_output.txt) |
| 4 | Block World Problem | Goal State Planning (BFS) | [`Block_World_Problem.py`](./Block_World_Problem.py) | [`04_Block_World_Problem_output.txt`](./outputs/04_Block_World_Problem_output.txt) |
| 5 | Depth Limited Search & Uniform Cost Search | Uninformed & Cost-Optimal Search | [`DLS_UCS.py`](./DLS_UCS.py) | [`05_DLS_UCS_output.txt`](./outputs/05_DLS_UCS_output.txt) |
| 6 | Breadth-First Search (BFS) | Graph Traversal (Queue) | [`BFS.py`](./BFS.py) | [`06_BFS_output.txt`](./outputs/06_BFS_output.txt) |
| 7 | Depth-First Search (DFS) | Graph Traversal (Stack) | [`DFS.py`](./DFS.py) | [`07_DFS_output.txt`](./outputs/07_DFS_output.txt) |
| 8 | A* Search Algorithm | Informed / Heuristic Search ($f=g+h$) | [`A-Star.py`](./A-Star.py) | [`08_A_Star_output.txt`](./outputs/08_A_Star_output.txt) |
| 9 | 8-Queens Problem | Backtracking & Constraint Satisfaction | [`8_Queen.py`](./8_Queen.py) | [`09_8_Queen_output.txt`](./outputs/09_8_Queen_output.txt) |
| 10 | Hill Climbing Algorithm | Local Search & Optimization | [`Hill_Climbing.py`](./Hill_Climbing.py) | [`10_Hill_Climbing_output.txt`](./outputs/10_Hill_Climbing_output.txt) |
| 11 | Minimax Algorithm | Adversarial Game Tree Search | [`Min_Max_Algorithm.py`](./Min_Max_Algorithm.py) | [`11_Min_Max_Algorithm_output.txt`](./outputs/11_Min_Max_Algorithm_output.txt) |
| 12 | Alpha-Beta Pruning | Adversarial Search Optimization | [`Alpha_Beta_Pruning_Function.py`](./Alpha_Beta_Pruning_Function.py) | [`12_Alpha_Beta_Pruning_output.txt`](./outputs/12_Alpha_Beta_Pruning_output.txt) |

> 📄 **Consolidated Record**: A combined text document with all experiment outputs is available at [`EXPERIMENT_OUTPUTS.txt`](./EXPERIMENT_OUTPUTS.txt).

---

## 🚀 How to Run the Experiments

Make sure you have Python 3 installed. You can clone the repository and run any experiment file directly from the terminal:

```bash
# Clone the repository
git clone https://github.com/Subham-Kumar-11/AI-LAB-25CSEAIML047.git

# Navigate into the project folder
cd AI-LAB-25CSEAIML047

# Run any experiment (e.g. 8-Queens problem)
python 8_Queen.py

# Run A* Search
python A-Star.py

# Run Block World Problem
python Block_World_Problem.py
```

---

## 📂 Repository Structure

```
AI-LAB-25CSEAIML047/
├── 8_Queen.py                      # 8-Queens Problem using Backtracking
├── A-Star.py                       # A* Search Algorithm
├── Alpha_Beta_Pruning_Function.py  # Alpha-Beta Pruning Algorithm
├── BFS.py                          # Breadth-First Search
├── Block_World_Problem.py          # Block World Problem using BFS
├── DFS.py                          # Depth-First Search
├── DLS_UCS.py                      # Depth Limited Search & Uniform Cost Search
├── Hill_Climbing.py                # Hill Climbing Algorithm
├── Min_Max_Algorithm.py            # Minimax Algorithm
├── Tic_Tac_Toe.py                  # Tic-Tac-Toe Game
├── Travel_Space.py                 # Travelling Salesperson Problem
├── Water_jug.py                    # Water Jug Problem using BFS
├── EXPERIMENT_OUTPUTS.txt          # Consolidated outputs of all 12 experiments
├── README.md                       # Repository documentation and experiment index
├── .gitignore                      # Python bytecode and ignore rules
└── outputs/                        # Individual experiment outputs in text format
    ├── 01_Water_jug_output.txt
    ├── 02_Tic_Tac_Toe_output.txt
    ├── 03_Travel_Space_output.txt
    ├── 04_Block_World_Problem_output.txt
    ├── 05_DLS_UCS_output.txt
    ├── 06_BFS_output.txt
    ├── 07_DFS_output.txt
    ├── 08_A_Star_output.txt
    ├── 09_8_Queen_output.txt
    ├── 10_Hill_Climbing_output.txt
    ├── 11_Min_Max_Algorithm_output.txt
    └── 12_Alpha_Beta_Pruning_output.txt
```