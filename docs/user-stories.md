# User Stories — TaskFlow

> As a busy student and freelancer, I want to create, organise and prioritise my
> tasks in one place, so that I can focus on the most important work and never
> miss a deadline.

## Detailed stories

### US-1 — Create a task
**As a** user,
**I want** to create a task with a title, description, priority and due date,
**so that** I can plan my work.

**Acceptance criteria**
- The title is required.
- The task appears in the list immediately after validation.
- The task is stored in local storage.

### US-2 — Edit a task
**As a** user,
**I want** to edit an existing task,
**so that** I can keep its information up to date.

**Acceptance criteria**
- All fields can be modified.
- Changes are saved and displayed immediately.

### US-3 — Delete a task
**As a** user,
**I want** to delete a task,
**so that** my list stays clean.

**Acceptance criteria**
- The task is removed from the list and from local storage.

### US-4 — Mark a task as done
**As a** user,
**I want** to mark a task as done or not done,
**so that** I can track my progress.

**Acceptance criteria**
- The task is visually struck through when done.
- The statistics are updated.

### US-5 — Filter tasks
**As a** user,
**I want** to filter tasks by status (all / active / completed),
**so that** I can focus on what remains to be done.

**Acceptance criteria**
- Only the tasks matching the selected filter are displayed.

### US-6 — Search tasks
**As a** user,
**I want** to search tasks by title,
**so that** I can find a task quickly.

**Acceptance criteria**
- The list is filtered as the user types.

### US-7 — View statistics
**As a** user,
**I want** to see the number of total, active and completed tasks,
**so that** I can measure my productivity.

**Acceptance criteria**
- The counters update after every action.
