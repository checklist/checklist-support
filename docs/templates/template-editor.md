---
layout: default
title: Template Editor
nav_order: 1
parent: Templates
---

# Template Editor

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Use the Template Editor to edit your templates.

You can open the template editor by clicking on the [name of the template](/templates/templates/#editing-templates). The Editor will open:

![](/assets/images/templates/template-editor.png)

The Editor layout consists of the following sections:

1. Template Details
2. Adding Tasks
3. Template Tasks

## 1. Template Details

The top section is the template section:
![](/assets/images/templates/template-editor-template.png)

### Back

The back arrow button opens the Template page where you can see all your template.

### Template Name

To update the template name, simply click on it and make your changes. Hit Enter to save or Escape to discard your changes.

### Task Contents Toggle

This toggle lets you decide if the tasks section should show the contents of each task. Task contents are any notes or media (e.g. YouTube videos) you have as part of a task.

Turn this toggle off if you want to see a condensed view of your template.

### Template Settings

Click on the Settings (Gear) icon to view and manage the [template settings](/templates/template-settings).

## 2. Adding Tasks

This section lets you add tasks to your template:

![](/assets/images/templates/template-editor-add-task.png)

Use the text box to add new tasks to your template. Hitting Enter or clicking on the + button will add the task to the template at the cursor (or at the top of the list if no cursor was set). The cursor will also move to the newly added task. You can continously enter task after task without using the mouse. Click on the X to discard any text you entered.

When editing a long template, when scrolling down, the Add Task section "floats" at the top of the page for easy access.

### Task Type

The type of task to be added is shown in the widget to the right of "Add new Task". Click widget drop down to open switch the task type. Read more about [Task Types](/checklists/task-types/).

If your template type is 'Checklist' then type widget is not shown (as this type has only simple tasks).

Tip: The Task type widget will change according to the type of the currently selected task ([cursor](/templates/template-editor#cursor)).

## 3. Template Tasks

This is the main section of the editor where you can see and manage the template's tasks. You can read more about (Task Template)[/templates/template-task].

### Mode

Each task can be in one of 3 modes:

#### Normal

In this mode tasks show their full details:

![](/assets/images/templates/template-editor-task-normal.png)

The following details are shown (when available):

- Name. If the task has a URL set, it will be linkable and open in a new tab)
- Notes.
- Type. The task type will be denoted with an icon
- Required. Required tasks will have a Red left border
- Media. If you have set any media (e.g. images, videos) they will be shown

Clicking on the task will set the cursor to it and effectively switch it to Edit Mode.

#### Condensed

In this mode only basic details are shown:

![](/assets/images/templates/template-editor-task-condensed.png)

The following details are shown (when available):

- Task name. If the task has a URL set, it will be linkable and open in a new tab)
- Type. The task type will be denoted with an icon
- Required. Required tasks will have a Red left border

Clicking on the task will set the cursor to it and effectively switch it to Edit Mode.

#### Edit

When the editor cursor is set to a task it will be displayed in Edit Mode:

![](/assets/images/templates/template-editor-task-edit.png)

Edit mode allows you to make changes to the task and its details. Read more about the (Task Template)[/templates/template-task] features and what they allows you to accomplish.

### Cursor

The "cursor" points to the current task being edited. The cursor can be set:

- by clicking on a task
- by adding a new task (cursor is set to it)

Read more about the (Task Template)[/templates/template-task]

### Actions

To the right of the task (when in Edit mode or "mouse over" the task) you can find the Task Actions:

#### Delete

Click the Delete button to delete the task. Note that no confirmation is required.

#### Duplicate

Click on the Duplicate button to create a copy of the task and any subtasks is may have. The copy is placed Below original task.

#### Subtask

Click on the Subtask button to make the task into a subtask.

Note: The button will be disabled if you cannot subtask the task (e.g. it is the first on the list).

#### UnSubtask

Click on the UnSubtask button to unsubtask a subtask (i.e. bring it a level higher).

Note: The button will be disabled if you cannot unsubtask the task (e.g. it is a the top level).

### Tasks Order

Tasks are ordered as you add them below the cursor. You can re-order tasks by dragging them up or down and dropping them at the required position.

Note: while dragging a task with subtasks, the subtasks are hidden as you cannot move a task into its own subtasks.
