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
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Sometimes it is not sufficient to just check tasks off of a list. You would like to also collect data as users go through the list. This is where the "Form View" becomes useful. You can defined "task types". For example the following checklist asks the user to choose from different choicesm, enter text, assign to users and enter a URL:

![Checklist Form View](/assets/images/checklists/checklist-form-view.png)

The Form View is used together with a checklist template. You can use it ONLY on checklists that were created from templates. 

Learn more [about templates](/templates).

Checklist owners can set which view is available per checklist. By default, the Form view will not be set for standard checklists as it is only applicable to those created from templates. 

Members who are not owners will not see the View Selector widget and the Form View will load for them by default.

## Tasks
Each task is placed on its own card. The cards can be "opened" by clicking on the down arrow at the top right of the card:

![Task expanded](/assets/images/checklists/checklist-form-view-card-open.png)

1. Task Status
2. Task Name. If the task is marked as required, an asterisk (*) will be shown after it
3. Task Answer - this depends on the task type. E.g. Choice, Date, File attachment
4. Assigned - who is this task assigned to
5. Open toggle - hide/ show the details part of the task (notes, updated by)
6. Task Notes - these are notes **FOR** the person filling out the checklist
7. Optional User Notes - these are notes **BY** the person completing the task
8. Signature - Update by who and when
9. Signature Avatar - The avatar of the person who last completed the task

Tasks which are not marked as required can also be marked as completed directly via their checkbox.

Tasks which are marked as "required" (and are not of type Check) cannot be manually checked/ unchecked. The user must fill out the answer according to its type.

## Subtasks
It is possible to group a set of tasks together as subtasks (just like in other views). Subtasks are indented to the right. Sub-subtasks are indendent further and so on.

## Propagation
The template editor can mark the checklist with propagation up or down. This has the following effect:
* Up. Once all subtasks of a task (or tasks of a checklist) are completed, the parent task is also marked as completed. This "propagates" all the way to the checklist itself which will be marked as completed if all its tasks are completed. If a task is marked as open, it will mark all its parents as open as well.
* Down. A task which is marked as completed or open will change the status of all of its sub tasks.

Note: for tasks which are required, propagation (UP and DOWN) will not have an effect as the task itself is required and an answer must be provided for it to be completed.

## Task Types

Read more [Task types](/checklists/task-types/)