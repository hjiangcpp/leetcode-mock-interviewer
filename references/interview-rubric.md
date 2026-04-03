# Interview Rubric

Use this rubric when giving structured feedback after a mock coding interview.

## Scoring Areas

Score each area from 1-5 if scoring is helpful. If not, use qualitative labels.

### 1. Communication

What to look for:
- Did the user restate the problem clearly?
- Did they explain the plan before coding?
- Did they respond clearly to follow-up questions?

Strong signals:
- organized explanation
- clear transitions between brute force and optimization
- concise but complete answers

Weak signals:
- jumps into code without plan
- mumbles through reasoning
- cannot explain why the approach works

### 2. Problem-Solving Process

What to look for:
- Did the user identify a brute-force baseline?
- Did they improve the solution step by step?
- Did they choose an appropriate data structure or pattern?

Strong signals:
- structured exploration
- correct optimization path
- good tradeoff awareness

Weak signals:
- random guessing
- no brute-force baseline
- optimization without justification

### 3. Complexity Analysis

What to look for:
- Did they give time complexity?
- Did they give space complexity?
- Did they justify it correctly?

Strong signals:
- explains both clearly
- distinguishes average vs worst case when relevant

Weak signals:
- forgets space complexity
- gives complexity mechanically without understanding

### 4. Edge Cases

What to look for:
- empty input
- single element
- duplicates
- negative values
- sorted/unsorted cases
- large constraints or overflow if relevant

Strong signals:
- proactively mentions edge cases
- tests the solution on examples

Weak signals:
- only tests happy path
- misses obvious failure cases

### 5. Code Quality

What to look for:
- readable variable naming
- clear control flow
- correct boundary handling
- no unnecessary complexity

Strong signals:
- readable and compact code
- few logical gaps

Weak signals:
- messy control flow
- bugs caused by indexing or state updates

## Feedback Output Template

Use this structure:

- **What went well**
- **Main weakness**
- **Communication**
- **Complexity analysis**
- **Edge cases**
- **Ideal approach summary**
- **Next practice suggestion**

## Example Short Feedback

- What went well: You found the correct sliding-window idea quickly and explained the invariant clearly.
- Main weakness: You skipped the brute-force baseline and did not justify why shrinking the window preserved correctness.
- Communication: Strong overall, but slow down when explaining state updates.
- Complexity analysis: Correct time complexity; space complexity was missing.
- Edge cases: Good duplicate handling, but you did not discuss empty input.
- Ideal approach summary: Maintain counts in the window, expand greedily, and shrink only when the validity condition fails.
- Next practice suggestion: Do another medium sliding-window problem and force yourself to state brute force first.
