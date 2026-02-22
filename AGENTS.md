# AGENTS.md - DSA Solutions Repository

This document helps any AI agent understand how to work with this repository.

## Repository Purpose

This is a DSA (Data Structures & Algorithms) practice repository containing:
- Solutions to LeetCode problems following Striver's SDE Sheet
- Detailed explanations with multiple approaches
- Study plan for interview preparation

## Structure

```
.
├── AGENTS.md              # This file
├── README.md              # Repository overview
├── dsa-study-plan.md      # 24-week study schedule
├── .gitignore             # Ignored files
└── solutions/             # Problem solutions
    ├── TEMPLATE.md        # Solution explanation template
    ├── arrays/
    ├── two-pointers/
    ├── sliding-window/
    ├── linked-lists/
    ├── stacks-queues/
    ├── binary-search/
    ├── trees/
    ├── graphs/
    ├── recursion-backtracking/
    ├── dp/
    ├── tries/
    ├── greedy/
    ├── heaps/
    └── misc/
```

## Solution Format

Each problem solution should have:
1. **README.md** - Detailed explanation
2. **solution.py** - Python code

### Explanation Template Structure

```markdown
# Problem Name

**LeetCode:** [link]
**Difficulty:** Easy | Medium | Hard
**Topic:** [topic]

## Problem Summary
[1-2 sentences]

## Approach 1: [Name]
### Thought Process
### Algorithm
### Code
### Complexity (Time/Space)

## Approach 2: [Alternative]
### When to Use

## Key Insights
```

## Adding New Solutions

1. Create folder in appropriate topic directory:
   ```bash
   solutions/[topic]/[problem-name]/
   ```

2. Copy TEMPLATE.md to that folder as README.md

3. Fill in the explanation and add solution.py

4. Commit with descriptive message:
   ```bash
   git add solutions/[topic]/[problem-name]/
   git commit -m "Add [problem-name] solution"
   git push
   ```

## Study Progress

- See dsa-study-plan.md for the 24-week schedule
- Problems are organized by topic following the study plan
- User tracks progress manually in the study plan file

## Coding Conventions

- Language: Python
- Use meaningful variable names
- Add comments for complex logic
- Include type hints where helpful
- Follow PEP 8 style

## Git Workflow

1. Create a branch for new solutions:
   ```bash
   git checkout -b solution/[topic]/[problem-name]
   ```

2. Commit and push:
   ```bash
   git add .
   git commit -m "Add [problem-name] solution"
   git push -u origin solution/[topic]/[problem-name]
   ```

3. Create PR on GitHub (optional)

## Resources

- Striver's SDE Sheet: https://takeuforward.org/interviews/strivers-sde-sheet-top-coding-interview-problems/
- Striver's DSA Playlist: https://youtube.com/playlist?list=PLgUwDviBIf0rGlzDb1LQBpIyV3O5hE7_
- LeetCode: https://leetcode.com

## Notes for AI Agents

- Do NOT modify AGENTS.md or .gitignore
- Follow the solution template format strictly
- Include multiple approaches when possible
- Always explain time/space complexity
- Keep explanations detailed but clear
- Do not generate or solve actual LeetCode problems - only document/user's own solutions
