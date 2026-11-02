# Experiment 001: Checklist and Scoring

Fixed before any model is run. Not shown to the models.

## Scale

Each item is scored 0 (does not work), 1 (works partly), 2 (works fully). Maximum 16.

## Checks

1. **Add task.** A task appears in the list on button click and on Enter. Empty input and input of only spaces are rejected.
2. **Mark done.** A task can be marked done and returned to active.
3. **Delete.** A single task can be deleted without affecting others.
4. **Filter.** All, Active and Completed each show exactly the right set of tasks. The active filter is visually highlighted.
5. **Persistence.** After a page reload, task text and done status are preserved.
6. **Themes.** Light and dark themes switch with one button. Both are readable.
7. **Accessibility.** Add, mark, delete and filter work using only Tab, Enter and Space. Focus is visible on every element.
8. **Responsive.** At 375 px width in developer tools there is no horizontal scroll and no button is cut off.

## Separate checks

- HTML validator result is recorded for each file.
- All files are run in the same browser, in a clean tab.

## Recorded separately from the score

- Number of fixes needed (maximum three per model).
- Regressions: anything that worked before a fix and broke after it.
- Items that worked on the first attempt.

## Recorded for every attempt

Model name, version, plan, date, exact prompt, number of fixes.

## Rules

- Scores are counted after the last fix.
- Design is not scored, only functionality.
- This checklist is not changed after testing starts. Any change is recorded separately with a date and a reason.
