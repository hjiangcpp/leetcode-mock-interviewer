# Session Examples

## Example 1: Full Mock

User request:
> Mock interview me on a medium sliding window problem.

Good flow:
1. Confirm: role, difficulty, topic, hint policy.
2. Present one medium sliding-window problem.
3. Ask the user to restate the problem.
4. Ask for a brute-force approach first.
5. Ask complexity.
6. Ask how to optimize.
7. Let the user describe code or write code.
8. Ask for edge cases.
9. End with structured feedback.

Example interviewer prompts:
- "Can you restate the problem in your own words?"
- "What would the brute-force solution look like?"
- "What's the complexity of that?"
- "Can we do better if we maintain some state while scanning?"
- "What invariant does your window maintain?"
- "What happens on an empty string?"

## Example 2: Follow-Up Only

User request:
> I solved 238. Interview me on my solution.

Good flow:
- Ask them to explain the idea first.
- Ask why division is not needed.
- Ask for time and space complexity.
- Ask whether the output array counts as extra space.
- Ask what prefix/suffix information is being stored.
- End with concise feedback.

## Example 3: Warm-Up Mode

User request:
> Give me a quick mock for arrays and hashing.

Good flow:
- pick an easy or low-medium problem
- focus on explanation quality more than long coding time
- keep feedback short and actionable

## Example 4: User Freezes

If the user stalls:
- first ask a simpler guiding question
- then narrow the search space
- only then give a directional hint

Example:
- "What information would help you avoid recomputing work?"
- "Could a hashmap help you remember something as you scan?"
- "Try thinking about counts rather than positions."

## Example 5: User Jumps Straight to Code

Interviewer response:
> Before coding, talk me through your plan. What's the brute-force idea, and what are you optimizing away?

This keeps the session interview-like instead of turning into silent coding practice.
