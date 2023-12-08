---
layout: default
title: Form View
nav_order: 3
parent: Checklist Views
grand_parent: Checklists
---

# Form View
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

In certain situations, merely checking off tasks may not suffice; you might also want to collect data as users progress through a list. This is where the "Form View" proves valuable. You can define various "task types" within this view. For example, the checklist below prompts users to choose from different options, enter text, assign tasks to users, and input a URL:

![Checklist Form View](/assets/images/checklists/checklist-form-view.png)

The Form View is specifically designed to work with a checklist template and is applicable only to checklists created from templates.

Learn more [about templates](/templates).

By default, the Form view is not set for standard checklists; owners can configure which views are available for each checklist. Members who are not owners will not see the View Selector widget, and the Form View will load for them by default.

## Tasks
Each task is presented on its own card, expandable by clicking the down arrow at the top right:

![Task expanded](/assets/images/checklists/checklist-form-view-card-open.png)

1. Task Status
2. Task Name (marked with an asterisk (*) if required)
3. Task Answer (depends on the task type, e.g., Choice, Date, File Attachment)
4. Assigned To
5. Open Toggle (hide/show task details)
6. Task Notes (for the person filling out the checklist)
7. Optional User Notes (notes by the person completing the task)
8. Signature and Update Details
9. Signature Avatar (of the person who last completed the task)

Tasks marked as "required" (excluding Check type) cannot be manually checked/unchecked; users must provide an answer according to the task type.

## Subtasks
Subtasks can be grouped together, with indentation indicating hierarchy.

## Propagation
In the Form View, the template editor empowers the checklist with the ability to propagate completion status both upward and downward, influencing task and checklist statuses based on subtask completion.

### Up Propagation
When all subtasks of a task (or tasks within a checklist) are marked as completed, the parent task is automatically flagged as completed. This effect cascades up to the checklist itself, marking it as completed when all tasks are fulfilled. If a task is in an "open" state, it influences its parent tasks to remain open as well.

### Down Propagation
A task, when marked as completed or open, triggers a status change for all its subtasks.

**Note:** For tasks marked as required, propagation (both upward and downward) has no effect, as these tasks necessitate an answer for completion.

Read more [Task types](/checklists/task-types/)
