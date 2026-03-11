# How To Use This Skill

## The intended workflow

This skill is not meant to analyze once and disappear.

Use it as a control layer while Long Da executes the project.

## Loop

### 1. Define the project
Ask the skill to clarify:
- users
- roles
- core scenario
- main loop
- MVP
- explicit non-goals

### 2. Let the skill identify the current stage
It should determine whether the project is in:
- definition
- breakdown
- core-loop build
- collaboration completion
- management enhancement
- experience refinement
- deployment
- delivery packaging

### 3. Ask for exactly one current highest-priority task
The skill should output:
- current stage
- current highest-priority task
- what not to do now
- acceptance criteria

### 4. Let Long Da implement only that scope
Do not expand sideways.
Do not start future features early.

### 5. Return for acceptance and correction
After implementation, use the skill to decide:
- did the task really pass?
- what is still broken?
- what is the minimum correction?
- can the project move to the next stage?

### 6. Repeat until delivery
Continue the loop:
- task
- implementation
- acceptance
- correction
- next task

## Golden rule

Do not optimize based on curiosity.
Optimize based on delivery impact.

## Typical prompts

### Start a project
```text
Use project-from-idea-to-product to define this project and give me the current highest-priority task.
```

### Continue a project
```text
Use project-from-idea-to-product to judge the current stage, decide whether the current work passed acceptance, and give only the next highest-priority task.
```

### Correct drift
```text
Use project-from-idea-to-product to identify whether we are overfitting on detail, and pull the project back to the current delivery goal.
```
