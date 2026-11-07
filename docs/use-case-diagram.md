# Use Case Diagram — TaskFlow

```mermaid
flowchart LR
    User([User])

    subgraph TaskFlow["TaskFlow Application"]
        UC1([Create a task])
        UC2([Edit a task])
        UC3([Delete a task])
        UC4([Mark a task as done / not done])
        UC5([Filter tasks: all / active / completed])
        UC6([Search tasks by title])
        UC7([View statistics])
        UC8([Persist tasks in local storage])
    end

    User --> UC1
    User --> UC2
    User --> UC3
    User --> UC4
    User --> UC5
    User --> UC6
    User --> UC7

    UC1 -.->|include| UC8
    UC2 -.->|include| UC8
    UC3 -.->|include| UC8
    UC4 -.->|include| UC8
```

## Actors

| Actor | Description |
|-------|-------------|
| **User** | The person who manages his or her tasks. |
| **Local Storage** | System actor that persists the tasks in the browser. |

## Use cases

| Use case | Description |
|----------|-------------|
| Create a task | Add a new task with a title, description, priority and due date. |
| Edit a task | Modify the information of an existing task. |
| Delete a task | Remove a task permanently. |
| Mark a task as done | Toggle the completion status of a task. |
| Filter tasks | Display all, active or completed tasks. |
| Search tasks | Find a task by its title. |
| View statistics | Display total, active and completed counters. |
| Persist tasks | Save and load the task list from local storage. |
