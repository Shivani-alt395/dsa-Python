# dsa-python

My Data Structures & Algorithms practice in Python, organized by problem-solving pattern.

**Goal:** land an SDET/SDE internship at a product-based company by April 2027.

- LeetCode: https://leetcode.com/u/shivaniv1402/
- LinkedIn: https://www.linkedin.com/in/kumari-shivani-verma-/?isSelfProfile=true

## Progress

| Topic | Solved | Easy | Medium | Hard |
|---|---|---|---|---|
| Arrays & Hashing | 0 | 0 | 0 | 0 |
| Two Pointers | 0 | 0 | 0 | 0 |
| Sliding Window | 0 | 0 | 0 | 0 |
| Stack | 0 | 0 | 0 | 0 |
| Binary Search | 0 | 0 | 0 | 0 |
| Linked List | 0 | 0 | 0 | 0 |
| Trees | 0 | 0 | 0 | 0 |
| Heap / Priority Queue | 0 | 0 | 0 | 0 |
| Graphs | 0 | 0 | 0 | 0 |
| Dynamic Programming | 0 | 0 | 0 | 0 |
| Backtracking | 0 | 0 | 0 | 0 |
| **Total** | **0** | **0** | **0** | **0** |

_Last updated: YYYY-MM-DD_

## Repo structure

```
dsa-python/
├── README.md
├── .gitignore
├── wrong_list.md
├── arrays_hashing/
├── two_pointers/
├── sliding_window/
├── stack/
├── binary_search/
├── linked_list/
├── trees/
├── heap/
├── graphs/
├── dp/
└── backtracking/
```

Files are named `<leetcode_number>_<problem_name>.py`, for example `001_two_sum.py`.

## File format

Every solution starts with a short header:

```python
# LeetCode 1: Two Sum
# Pattern: Hash map (complement lookup)
# Time: O(n) | Space: O(n)
# Note: Check the map before inserting to avoid reusing the same element

def two_sum(nums, target):
    seen = {}
    for i, n in enumerate(nums):
        if target - n in seen:
            return [seen[target - n], i]
        seen[n] = i
```

## How I use this repo

1. Solve the problem on my own first (brute force, then optimize).
2. Save the solution under its pattern folder with the header above.
3. If I needed hints or got it wrong, add it to [`wrong_list.md`](wrong_list.md).
4. Redo the wrong list every week and re-solve from scratch without looking.
5. Commit after every session with a clear message, e.g. `add: two sum (hash map)`.

## Patterns covered

- [ ] Hash map / set
- [ ] Two pointers
- [ ] Sliding window
- [ ] Prefix sum
- [ ] Stack / monotonic stack
- [ ] Binary search
- [ ] Linked list (fast/slow pointers, reversal)
- [ ] Tree traversals (DFS / BFS)
- [ ] Heap / top-K
- [ ] Graph traversal (BFS / DFS, union-find, topological sort)
- [ ] Dynamic programming
- [ ] Backtracking

## Roadmap

| Phase | Months | Focus |
|---|---|---|
| 1 | Oct-Nov 2026 | Foundations: arrays, strings, hashing, two pointers, sliding window |
| 2 | Nov-Dec 2026 | Linked lists, stacks, queues, trees, heaps, binary search |
| 3 | Dec-Jan 2027 | Graphs, intro to DP, backtracking, weekly contests |
| 4 | Jan-Feb 2027 | Advanced DP, tries, bit manipulation, revision |
| 5-6 | Feb-Apr 2027 | Timed practice, mock interviews, applications |

## Other repos

- Test automation framework (Python, pytest, Playwright): _coming soon_
- API testing project: _coming soon_

## Resources

- [NeetCode 150](https://neetcode.io)
- [Striver's A2Z DSA Sheet](https://takeuforward.org)
- [LeetCode](https://leetcode.com)
- [Test Automation University](https://testautomationu.com)
