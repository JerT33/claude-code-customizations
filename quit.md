---
description: Gracefully wrap up the session with summary, prompt evaluation, and learning capture
allowed-tools: Read, Write, Edit, Bash, AskUserQuestion
---

# Session Wrap-Up

Perform a complete session wrap-up by executing these steps in order:

## Step 1: Session Summary

Analyze this conversation and create a summary:
- **Accomplishments**: What was completed this session (bullet list)
- **Key Decisions**: Important choices or directions taken
- **Context**: Any important background established

## Step 2: Prompt Evaluation

Follow the evaluation instructions in @~/.claude/commands/evaluate-prompts.md

## Step 3: Unfinished Items

List any:
- Incomplete todos from the session
- Work started but not finished
- Questions raised but not resolved
- Follow-ups needed

## Step 4: Save Session Log

Generate a timestamp and a 2-3 word summary of the session topic.

---
description: Gracefully wrap up the session with summary, prompt evaluation, and learning capture
allowed-tools: Read, Write, Edit, Bash, AskUserQuestion
---

# Session Wrap-Up

Perform a complete session wrap-up by executing these steps in order:

## Step 1: Session Summary

Analyze this conversation and create a summary:
- **Accomplishments**: What was completed this session (bullet list)
- **Key Decisions**: Important choices or directions taken
- **Context**: Any important background established

## Step 2: Prompt Evaluation

Follow the evaluation instructions in @~/.claude/commands/evaluate-prompts.md

## Step 3: Unfinished Items

List any:
- Incomplete todos from the session
- Work started but not finished
- Questions raised but not resolved
- Follow-ups needed

## Step 4: Save Session Log

Generate a timestamp and a 2-3 word summary of the session topic.

---
description: Rate and analyze your prompts from this session with improvement suggestions
---

# Prompt Evaluation

Analyze the user's prompts from this conversation. Be concise.

## Output

### Overall Score
```
Score: X.X/5
Prompts evaluated: N
High: X | Low: X
```

### Bottom 1-3 Prompts
Only the 1-3 weakest prompts:

```
"[truncated prompt]..." → X/5
Issue: [One sentence]
Better: "[Rewritten version]"
```

Skip this section if all prompts scored 4+.

### Quick Improvements
1-2 short phrases (not full sentences). Example: "Be more specific", "Avoid vague 'this'"

## Guidelines
- Skip trivial prompts ("yes", "thanks", "okay")
- Brief prompts are fine when context is established
- Focus only on prompts where improvement would have meaningfully helped
