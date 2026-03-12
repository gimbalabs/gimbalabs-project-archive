# Tasks - UCSCN Web3 Mentorship Collaboration

This project has an associated Tasks database in Notion.

## Task Database Info

- **Database URL:** https://www.notion.so/1990db6d1d5d81e6bc12d92814c5633a
- **Data Source:** collection://4c38078d-a885-4b9c-8d87-e040bfff6114 (shared Gimbalabs Tasks collection)

## Task Schema

Tasks in this database have the following properties:

| Property | Type | Description |
|----------|------|-------------|
| Task name | Title | The task title |
| Status | Status | Not started, In progress, QA, Blocked, Done, Archived, etc. |
| Assignee | Person | Who is assigned to the task |
| Due | Date | Due date |
| Priority | Select | Low, Medium, High, Unknown |
| Tags | Multi-select | Admin, Non-task, Feature, Bug |
| Sub-tags | Select | Non-critical, Critical, X-Large, Large, Medium, Small |
| Summary | Text | Task summary |
| Project | Relation | Link to parent project |
| Sub-tasks | Relation | Child tasks |
| Parent-task | Relation | Parent task (for subtasks) |
| GitHub Pull Requests | Relation | Linked PRs |
| Task ID | Auto-increment | Unique task identifier |

## Views

1. **Board View** - Kanban board grouped by Status
2. **Tasks View** - Table view with all properties

## Notes

Tasks are filtered to show only those linked to the UCSCN Web3 Mentorship Collaboration project page. To view actual tasks, visit the Notion database URL above.
