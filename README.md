# CIBP: Commerce IB Prep (Prompt Development)

ARIN 121 Final Project, Fall 2026. Alex Hunter and Logan Keen, Queen's University.

## The application

CIBP is an investment banking technical interview coach for Queen's Commerce first and second year students who want an IB summer internship but do not know which technical concepts they are missing. A starting survey and a 20 question diagnostic place the student at Beginner, Intermediate or Superday. The app then builds a study plan from the concepts they got wrong, runs short Learn sessions (a reading with a worked example, then questions with one hint) and an Interview Drill, and retests the plan concepts each week.

## Links

| Item | Link |
| --- | --- |
| Build application code (Repository 2) | https://github.com/AlexHunterQueens/CIBP-Build |
| Google AI Studio Build app | https://ai.studio/apps/55ca62ab-5326-4d55-9b2c-5edecfd24792 (opens in AI Studio with a Google account) |
| Published app | Not available. AI Studio Publish requires a billed Google Cloud project, so the workbook shows the payment screen under "Build Publishing Restriction" and links the Build code repository instead, as the GitHub Instructions allow |

## Files

| File | Purpose |
| --- | --- |
| `system-prompt-initial.md` | Initial system prompt (v0), written from the Application Design |
| `system-prompt-cycle-1.md` | Full prompt after Cycle 1: one diagnostic question at a time |
| `system-prompt-cycle-2.md` | Full prompt after Cycle 2: handling "I don't know" and non answers |
| `system-prompt-cycle-3.md` | Full prompt after Cycle 3: fixed plan lengths by placement |
| `system-prompt-cycle-4.md` | Full prompt after Cycle 4: few shot grading examples. This is the prompt given to Build |
| `system-prompt-cycle-5.md` | Full prompt after Cycle 5 (Build retest): Question 1 starts right after the survey. The Build app runs this version |
| `build-prompt.md` | Main prompt used to create the Build interface and workflow |

Each file holds the complete system prompt at that stage. The workbook explains the tests, observations, prompt changes and decisions for each cycle.

Built with Google AI Studio (Playground and Build mode).
