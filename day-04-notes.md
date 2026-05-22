# Day 4 Notes — [22/05/2026]

## DSA
### Product of Array Except Self (#238)
- Approach: Prefix + Suffix products
- Pass 1: left to right building prefix products
- Pass 2: right to left multiplying suffix products
- No division needed
- Time O(n) | Space O(1) extra

### Valid Sudoku (#36)
- Track: 9 row sets, 9 col sets, 9 box sets
- Box index formula: (row//3)*3 + (col//3)
- Time O(81) = O(1) | Space O(81) = O(1)

## DA/ML Addition
### SQLZoo Section 4 — Subqueries
- Subquery in WHERE clause
- ALL() keyword
- Correlated subqueries
- Key pattern: inner query runs first

### Titanic EDA Extended
- Survival by class: 1st class ___%, 3rd class ___%
- Age median filled missing values
- Correlation heatmap built
- Strongest correlation with survival: ___

### HackerRank SQL Certificate
- SQL Basic certificate taken and passed ✅
- Added to LinkedIn and resume

## Full Stack — JavaScript
### Variables
- const > let > var
- Always use === not ==
- Type coercion: "5"+3="53", "5"-3=2

### Functions
- Declaration, Expression, Arrow, IIFE
- Default params, rest params
- Higher order functions

### Scope + Closures
- Block scope: let/const
- Function scope: var (avoid)
- Closures: inner function remembers outer variables

### Arrays
- map, filter, reduce, find, some, every
- Chaining: filter().sort().map()
- Spread, destructuring

### Objects
- Dot vs bracket notation
- Optional chaining ?.
- Nullish coalescing ??
- Object.keys/values/entries

## Project
- Interactive page with filters, dark mode, typing animation
- Contact form with validation
- DSA progress tracker
- Deployed on GitHub Pages ✅
- Live URL: https://nitheshkumar-s.github.io/html-css-practice/

## Commits Today: 5+
## Total LeetCode: 6 problems

## Day 5 Plan
- DSA: #238 Product Array, #3 Longest Substring
- SQL: SQLZoo Section 5 — SUM and COUNT
- JS: DOM Manipulation complete
- JS: Events — click, input, keyboard
- Build: Dynamic todo list with localStorage