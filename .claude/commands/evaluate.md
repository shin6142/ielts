Evaluate the user's IELTS writing response based on the official IELTS band descriptors.

## Instructions

1. First, use the Glob tool to find all markdown files in `writing/practices/` directory
2. Use the AskUserQuestion tool to ask the user which file they want to evaluate, showing the available files as options
3. Read the selected file and find the "# My Response" or "## My Response" section(s)
4. Read the evaluation principles from `/Users/shin.yamaga/ielts/writing/evaluation_principles.md`
5. Evaluate the writing based on the four official IELTS criteria:
   - Task Achievement/Response (25%)
   - Coherence & Cohesion (25%)
   - Lexical Resource (25%)
   - Grammatical Range & Accuracy (25%)
6. Use the Edit tool to append the evaluation and improved version to the selected markdown file

## Output to Append to File

Append the following sections to the end of the selected file:

```
---

## Evaluation

### Overall Band Estimate: X.0/9

### Detailed Scores

| Criteria | Band | Feedback |
|----------|------|----------|
| Task Achievement | X/9 | [specific feedback] |
| Coherence & Cohesion | X/9 | [specific feedback] |
| Lexical Resource | X/9 | [specific feedback] |
| Grammatical Range & Accuracy | X/9 | [specific feedback] |

### Strengths
- [List what was done well]

### Areas for Improvement
- [List specific issues with examples from the text]

### Key Corrections
- [Show key corrections with original → corrected format]

---

## Improved Version

[Write the full improved version of the response with **bold** for corrections and ~~strikethrough~~ for original errors]

**(Estimated Band Score: X.0)**
```
