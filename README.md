# mini-canvas-lab

## 🎯 Core Features
- **User Management**: Track user to-do lists, add/complete assignments.
- **Assignment Management**: Assign tasks to users, track submissions via linked lists.
- **Submission Tracking**: Store all submissions for each assignee in a linked list (latest submission at the end).
- **Memory Safety**: Properly manage dynamic arrays and linked lists (no memory leaks, no use-after-free).

## 🛠️ How to Compile & Run
### Compile (in `lab2/` directory):
```bash
clang++ -std=c++11 -Werror=vla src/main.cpp src/assignment.cpp src/user.cpp -o lab2
