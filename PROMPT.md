# Experiment 001: Prompt

This prompt is sent unchanged to every model, in a new chat with no memory and no custom instructions. The checklist is not shown to the models.

## Prompt

Create a single-file task manager web app in HTML, CSS and JavaScript in one file. No external libraries. It must add tasks by button and Enter key. Reject empty input. Mark tasks done and undo. Delete a single task. Filter All, Active, Completed. Save tasks in localStorage. Switch light and dark themes. Be fully keyboard-accessible with visible focus. Be responsive on mobile with no horizontal scroll.

## Rules for fixes

- A fix is one message to the model describing the bug, without suggesting a solution.
- Maximum three fixes per model.
- If a fix breaks something that worked before, it is recorded as a regression.
