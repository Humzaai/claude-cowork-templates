# Prompt Engineering Library
**Save as:** `templates/02-prompt-engineering-library.md`
**Purpose:** Your personal library of proven prompts. Add to it as you discover what works.

---

## HOW TO USE THIS FILE
Claude should reference these patterns when helping you build or improve a prompt.
Update this file whenever you find a prompt structure that consistently delivers good results.

---

## CORE PROMPT STRUCTURES

### The Role + Task + Format Prompt
```
You are a [role].
Your task is to [specific task].
Output format: [describe the format exactly].
Context: [any relevant background].
```

### The Chain of Thought Prompt
```
Before answering, think step by step:
1. What is being asked?
2. What do I know about this topic?
3. What are the possible approaches?
4. Which approach is best and why?
Then give your final answer.
```

### The Critique Prompt
```
Review this [document/plan/idea].
List:
- What works well and why
- What is weak and why
- The 3 most important improvements
Be specific. Do not be vague.
```

### The Rewrite Prompt
```
Rewrite this in my voice.
My voice is: [describe in 3-5 words]
Do not change the meaning.
Do not add information I did not include.
Keep the structure but improve the language.
Original: [paste text]
```

### The Research Summary Prompt
```
Research [topic].
I need:
1. The core concept in plain language
2. The 5 most important facts
3. Current debates or controversies
4. Practical implications for [my field]
5. 3 sources worth reading
Do not pad. Be dense with useful information.
```

### The Idea Generation Prompt
```
Generate 20 ideas for [topic/problem].
Criteria:
- Each idea must be [criteria 1]
- Each idea must be [criteria 2]
After listing all 20, rank the top 5 and explain why.
```

### The Persona Prompt
```
You are [specific expert persona].
You have [X years] of experience in [field].
You are known for [characteristic approach].
With that context, [the task].
```

---

## MY BEST PROMPTS BY CATEGORY

### Writing
[Paste your best writing prompts here as you discover them]
-

### Research
[Paste your best research prompts here]
-

### Brainstorming
[Paste your best ideation prompts here]
-

### Editing and Reviewing
[Paste your best editing prompts here]
-

### Analysis
[Paste your best analysis prompts here]
-

---

## PROMPTING PRINCIPLES I FOLLOW
1. Be specific about the output format — vague instructions produce vague results
2. Give examples when style matters — show Claude what good looks like
3. Tell Claude what NOT to do, not just what to do
4. Use numbered lists for multi-part requests
5. Ask for a draft first, then iterate — never expect perfection in one shot
6. When output is off, describe what is wrong specifically, not just "this is bad"
7. Longer context produces better output for complex tasks
8. One task per prompt — do not stack multiple unrelated requests

## AI PROMPTS FOR PROMPT BUILDING
- "Help me build a prompt for [task]. My goal is [outcome]. The output format I need is [format]."
- "This prompt is not working: [paste prompt]. What is wrong with it and how should I fix it?"
- "Generate 5 variations of this prompt, each using a different approach: [paste prompt]"
