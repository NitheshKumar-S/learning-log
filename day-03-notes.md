# Day 3 Notes — [20/05/2026]

## DSA
### Valid Anagram (#242)
- Approach 1: sorted(s) == sorted(t) → O(n log n)
- Approach 2: HashMap frequency count → O(n)
- Approach 3: Counter(s) == Counter(t) → cleanest
- Key insight: Anagrams have identical character frequencies

### Valid Palindrome (#125)
- Approach 1: Clean string then compare reverse → O(n) time O(n) space
- Approach 2: Two pointers → O(n) time O(1) space
- Key insight: Two pointers skip non-alphanumeric chars in place

## DA/ML Addition
### SQLZoo Section 3 — SELECT from Nobel
- All 13 exercises complete
- New SQL learned:
  - LIKE 'Sir%' — pattern matching
  - NOT LIKE — exclusion pattern
  - IN (1984, 1985) — multiple value check
  - ORDER BY yr DESC — descending sort
  - Combining AND/OR with parentheses

### Titanic EDA Started
- Loaded dataset — 891 rows, 12 columns
- Missing values: Age (177), Cabin (687), Embarked (2)
- Survival rate: 38.4%
- Key finding: Women survived at much higher rate than men
- Built first 2 visualizations

## Full Stack
### CSS Foundations
- Box model: content → padding → border → margin
- Specificity: inline(1000) > ID(100) > class(10) > element(1)
- display: block vs inline vs inline-block vs none

### CSS Flexbox
- Container: display:flex, justify-content, align-items, flex-wrap
- Items: flex-grow, flex-shrink, flex-basis, align-self, order
- Real patterns: navbar, card grid, centering, sidebar layout
- Completed flexboxfroggy.com — all 24 levels

### CSS Grid
- grid-template-columns, grid-template-rows
- repeat(), fr units, minmax()
- grid-area for named areas
- auto-fit with minmax for responsive grids
- Completed cssgridgarden.com — all 28 levels

### Project
- html-css-practice page completely styled
- Professional look with CSS variables
- Hover effects, transitions
- Responsive with media queries

## GitHub Today
- dsa-practice: 2 commits (Anagram, Palindrome)
- html-css-practice: 2 commits (CSS styling, responsive)
- learning-log: this commit + Titanic notebook
- Total: 5 commits today ✅

## Strongest concept today
I learnt Basic Two pointer technique

## Still unclear
python functions and css style

## Day 4 Plan
- DSA: #238 Product of Array Except Self
- DSA: #36 Valid Sudoku
- SQL: SQLZoo Section 4 — SELECT within SELECT
- HackerRank SQL Basic certificate (take it tonight)
- Full Stack: JavaScript starts — variables, data types, functions
- Build: First JS file, run in Node.js and browser