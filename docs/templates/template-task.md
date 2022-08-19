---
layout: default
title: Template Task
nav_order: 3
parent: Templates
---

# Template Task

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Beyond the Template Task name, there are other field which you can set on a task. Those can be used in different use cases.

## Task Name

The task name is a required field. You set it when you create a task. You can make changes to it by clicking on the task name entering into Edit Mode. Make any changes and hit Enter to save them. Click Escape if you want to discard your changes.

## Task Notes

You can add notes to your tasks. These can serve as additional information to the person using the checklist. To add notes, click on the "Click to add task notes" link:

![](/assets/images/templates/template-editor-task-notes.png)

Click Save to confirm and save your notes. Click Cancel to discard your changes.

## Link

You can add a link to a task to provide users with additional information to complete the task. Click on the 'Click to add a link' link to enter or edit the task Link:

![](/assets/images/templates/template-editor-task-url.png)

Enter the URL link and hit Enter to save it. If the link is not a valid URL, Checklist will not allow you to save it. Click Escape to disard your changes.

Once you have a link, and when not in Edit Mode, the task name will be "linkable" allowing you to click on it and open the link in a new tab.

If you are in Normal Mode (i.e. not Condensed) and the url links to supported media type (e.g image, video) the media will be shown between the task name and any notes. For example, in the following (vehicle inspection checklist)[https://checklist.com/vehicle-inspection-checklist] the first task is used to inspect the VIN. We want to show the user an example VIN so that they can enter validate it:

![](/assets/images/templates/template-editor-task-normal.png)

## Task Type

You can view and make changes to the current task type via the Type Selector:

![](/assets/images/templates/template-editor-task-type.png)

Read more about [Task Types](/checklists/task-types/).

If the select task type has additional settings (for example Choice type), those will be displayed in Edit Mode for you to update:

![](/assets/images/templates/template-editor-task-type-choice.png)

## Required

If you want to require users to fill out the task answer according to its type, you can require them to do so by toggling the Required field to "On".

Note: since the Check type does not have an answer, it is not possible to set it to Required.

## Assign

You can assign task to specific users in your team or the entire team. When the checklist is created from the template, the task will be assign to the assigned user(s). To set the Assigned click on 'Click to assign':

![](/assets/images/templates/template-editor-task-assign.png)

Any "checked" contacts will be assigned this task.

Tip: for quick selection and closing of the Assign dialog, click on the person name and not the checkbox.

Note: if when creating the checklist (Run) the user no longer has access to the team, the task will not be assigned to that user.

## Due Date

Just like checklist tasks, you can also set a due date for template tasks. Unlike checklists though, you cannot set a specific time as that is not known when editing the template (remember that you will trigger the template manually or automatically and only then will the template turn into a checklist). Therefore, we set a relative due date. That is relative to the time the template is triggered. This can be in minutes, hours or days.

E.g. if you have an Office Opening template which is triggered daily at 09:30 and is assigned to the office manager. The first task on the template may be "open doors" and you can set a due date of 15 minutes. If the office manager does not check the task by 09:45, a notification will be issued.

To set a due date, focus on the task and click on the 'set due date' link:

![](/assets/images/templates/template-task-due-date.png)

This will open the due date settings:

![](/assets/images/templates/template-task-due-date-edit.png)

You can select from the days, hours or minutes drop downs and then click Save to confirm. You can use multiple selections (e.g. for 2 hours and 30 minutes). You can see your selection:

![](/assets/images/templates/template-task-due-date-saved.png)

Next time you trigger the template, the due date for the task will be automatically set from the time of template triggering.

### Due Date Alarm

If a due date has passed and the task is not yet completed, then the person assigned to it (usually the same as the checklist assignee) receives a notification. In some cases, you may wish for a manager to receive an alarm notification that the task has not been completed (this is in addtion to the assignee). An example can be a store opening checklist when the first task has not been completed indicating the possibility that no one came to open the store.

To add an alarm notification, click to set alarm recipients:

![](/assets/images/templates/template-task-due-date-alarm.png)

You can choose the whole team (always the first option) or someone specific. Multiple selections can be made.

Tip: click on a checkbox to select multiple users. Click anywhere else on the line to select that person only and close the popup.
