# Experiment 001: Checklist and Scoring

Fixed before any model is run. Not shown to the models.

## Scale

Each item is scored 0 (does not work), 1 (works partly), 2 (works fully). Maximum 16.

## Checks

1. **Add task.** A task appears in the list on button click and on Enter. Empty input and input of only spaces are rejected.
2. **Mark done.** A task can be marked done and returned to active.
3. **Delete.** A single task can be deleted without affecting others.
4. **Filter.** All, Active and Completed each show exactly the right set of tasks, and the active filter is visually highlighted. Score 2 if all three modes are correct, 1 if one mode is wrong, 0 if two or more are wrong.
5. **Persistence.** Add several tasks, mark one as done, reload the page. Task text and done status must be preserved.
6. **Themes.** Light and dark themes switch with one button. In both, text and background are clearly distinguishable, checked with a contrast tool in browser developer tools.
7. **Accessibility.** Add, mark, delete and filter work using only Tab, Enter and Space, and focus is visible on every element. Score 2 if both parts pass, 1 if only one passes, 0 if neither.
8. **Responsive.** At 375 px width in developer tools there is no horizontal scroll and no button is cut off.

## Separate checks

- HTML validator result is recorded for each file.
- All files are run in the same browser, in a clean tab.

## Two scores per model

- Initial score: after the first attempt, before any fix.
- Final score: after the last fix. The final score is the result of the experiment.

## Fixes

- Maximum three fixes per model.
- If an item still does not work after the third fix, it is scored as it stands. No fourth attempt.

## Recorded separately from the score

- Number of fixes needed.
- Regressions: anything that worked before a fix and broke after it.

## Recorded for every attempt

Model name, version, plan, date, exact prompt, number of fixes.

## Rules

- Design is not scored, only functionality.
- This checklist is not changed after testing starts. Any change is recorded separately with a date and a reason.
