# Day 5 Notes — [24/05/26]

## DSA — Sliding Window Pattern
### Longest Substring Without Repeating (#3)
- Pattern: Sliding Window with HashSet/HashMap
- Expand right always
- Shrink left when duplicate found
- HashMap version: jump left pointer directly
- Time O(n) | Space O(n)

### Longest Repeating Character Replacement (#424)
- Key formula: window_size - max_freq_count <= k
- Track max frequency character in window
- Expand right, shrink left only when invalid
- Time O(n) | Space O(1)

## DA/ML Addition
### SQLZoo Section 5 — Aggregations
- COUNT(*) vs COUNT(column) vs COUNT(DISTINCT col)
- SUM, AVG, MAX, MIN
- GROUP BY — aggregate per group
- HAVING — filter after grouping
- WHERE filters before GROUP BY
- HAVING filters after GROUP BY
- SQL clause order: SELECT FROM WHERE GROUP BY HAVING ORDER BY

### Kaggle Python
- Lesson 1: Variables, arithmetic, print
- Lesson 2: Functions, docstrings, default args

### Titanic EDA Completed
- Family size feature engineered
- Key finding: Small families (2-4) survived most
- Strongest predictor: Pclass (negative), Fare (positive)
- Full summary printed and documented

## Full Stack — DOM Manipulation
### Selecting Elements
- getElementById, querySelector, querySelectorAll
- NodeList vs HTMLCollection
- Convert to array with Array.from() or spread

### Modifying DOM
- textContent vs innerHTML vs innerText
- setAttribute, getAttribute, removeAttribute
- classList: add, remove, toggle, contains
- style (avoid for permanent styles — use classes)

### Creating/Removing
- createElement, appendChild, prepend
- insertAdjacentHTML
- element.remove()
- DocumentFragment for performance

### Events
- addEventListener (always use this)
- Mouse: click, dblclick, mouseenter, mouseleave
- Keyboard: keydown, keyup (use key not keyCode)
- Input: input, change, focus, blur
- Form: submit + preventDefault
- Event bubbling — events travel up DOM
- Event delegation — one listener on parent
- stopPropagation when needed

## Project — Todo App
- Complete CRUD: Add, toggle, delete
- Filter: All / Active / Completed
- localStorage persistence across refreshes
- Event delegation pattern used
- Animation on add and delete
- Empty state messages
- Deployed on GitHub Pages ✅
- Live: https://nitheshkumar-s.github.io/todo-app/

## GitHub Today: 5 commits
## LeetCode Total: 8 problems

## Day 6 Plan
- DSA: #121 Best Time to Buy Stock, #238 revisit
- SQL: SQLZoo Section 6 — JOIN
- JS: Fetch API + Async/Await
- Build: Weather App (real API call)
- Start Node.js basics