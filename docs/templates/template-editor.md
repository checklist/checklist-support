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

The Template Editor is where you can "edit the template" - name, add tasks, reorder tasks and more. To start editing a template, click on the [Pencil button](/templates/templates/#editing-templates). The Editor will open:

![](/assets/images/templates/templates-editor.png)

The Editor layout consists of:
1. Template Name
2. Add Task
3. Tasks
4. Details Pane

## 1. Template Name
In this section you can see the name of the template. You can also click on the Pencil to switch the Details Pane to the Template Details ([see below](#template-details)).

## 2. Add Tasks
This section lets you add tasks as well as setting the type of task to be added:

![](/assets/images/templates/templates-editor-add-task.png)

Start typing the name of the task in the "Add a new task" text box. As you start typing, if you change your mind, you can click the X button to delete the current text you have entered. 

The type of task to be added is shown in the widget to the right. It will automatically switch to the type of the task that is currently selected (if any) in the list of tasks. You can click on the widget to open the different types and select one. Read more about [Task Types](/checklists/task-types/).

When you have entered the task name and have the desired type selected either hit Enter on your keyboard or click on the + button to add the task. The task will be added just below the selected task (or at the top of the list if no tasks are selected) and the focus (selection) will move to it. You can continously enter task after task without using the mouse.

Note that on long templates, the Add Task section "floats" at the top of the page for easy access. 

## 3. Tasks 
This is the main section of the editor in which you can see the tasks of the template. You can:
* edit the task name by clicking on the name and entering Edit Mode. Make your changes and click Enter, Tab or anywhere outside the textbox to save. Click ESC to discard your changed
* click anywhere on a task (beyond any of its widgets) to select it. A selected task will have its details open in the Details Pane on the right
* drag and drop a task to reorder it
* make a task into a subtask by clicking on the ">" button 
* making a subtask back into a task (unsubtask) by clicking on the "<" button
* deleting a task by clicking on the Trashcan button

## 4. Details Pane
The Details Pane allows you to see 
* the Template Details - when the template is selected via the Pencil button
* the Task Details - when a task is selected

### Template Details
After selecting the template and the Template Details Pane showing, you can view and make changes to the following:

#### Template Name
Click anywhere on the template name to enter "Edit mode" where you can rename the template. If happy with the change hit Enter, Tab or click anywhere outside the textbox. If you are unhappy and wish to discard your changes, hit ESC.

#### Template Notes
The template notes will be copied to the checklist notes. If you are manually running a template (i.e not via schedule), you can still make changes to the notes beforehand.

To add/ edit notes:
* click on the "Template Notes" placeholder or the existing notes to enter "Edit Mode"
* enter your notes or change the existing notes
* if happy with your changes hit Enter, Tab or click with the mouse anywhere outside the textbox and your changes will be saved
* if unhappy with your changes, hit ESC to discard them

#### Sharing
By default, only you have access to the template. If you want to share it with your team, you can do so by toggling the Team Sharing toggle button.

Sharing is on when the toggle is orange (and to the right) and off when grey (and to the left).

#### Checklist View
You can set which views will be available for users of the checklists created. This is similar to the [View Selector](/checklists/checklists/#checklist-view-selector) of the Checklist Page.

#### Propagation
Propagation refers to how parent and child tasks should behave when they are completed. Read more about [task propagation](/checklists/form-view/#propagation). These two setting control the setting of checklists created from this template.

### Task Details
After selecting a task, the Task Details are shown in the Details Pane:

![](/assets/images/templates/templates-editor-task-details.png)

You can now view the task details as well as make changes:

#### Task notes
The task notes will be copied to the checklist task notes. To add/ edit notes: 
* click on the "Task Notes" placeholder or the existing notes to enter "Edit Mode"
* enter your notes or change the existing notes
* if happy with your changes hit Enter, Tab or click with the mouse anywhere outside the textbox and your changes will be saved
* if unhappy with your changes, hit ESC to discard them

#### Task Type
You can view and make changes to the current task type via the Type Selector. Read more about [Task Types](/checklists/task-types/).

#### Required
If you want to require users to fill out the task answer according to its type, you can require them to do so by toggling the Required widget to on.

Note: since the Check type does not have an answer, it is not possible to set it as required.

#### Assign
You can assign task to specific users in your team or the entire team. When the checklist is created from the template, we will set the task to the assigned user.

Note: if when creating the checklist (run) the user no longer has access to the team, the task will not be assigned to any user.

#### Task Options
This is applicable for tasks where the Choice type was selected. You can add, edit, remove and reorder the different options. See more about the [Choice Type](/checklists/task-types/#choice).

#### Due Date
Just like checklist tasks, you can also set a due date for template tasks. Unline checklists though, you cannot set a specific time as that is not known when editing the template (remember that you will trigger the template manually or automatically and only then will the template turn into a checklist). Therefore, we set a relative due date. That is relative to the time we will actually trigger the template. This can be in minutes, hours or days.

E.g. if you have an Office Opening template which is triggered daily at 09:30 and is assigned to the office manager. The first task on the template may be "open doors" and you can set a due date of 15 minutes. If the office manager does not check the task by 09:45, a notification will be issued.

To set a due date, focus on the task and click on the 'set due date' link:

![](/assets/images/templates/template-task-due-date.png)

This will open the due date settings:

![](/assets/images/templates/template-task-due-date-edit.png)

You can select from the days, hours or minutes drop downs and then click Save to confirm. You can use multiple selections (e.g. for 2 hours and 30 minutes). You can see your selection:

![](/assets/images/templates/template-task-due-date-saved.png)

Next time you trigger the template, the due date for the task will be automatically set from the time of template triggering.