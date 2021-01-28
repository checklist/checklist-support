---
layout: default
title: Task Types
nav_order: 4
parent: Checklists
---
# Task Types
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Task types let you go beyond a simple checkbox for each task. You can also have additional fields of different types. Task types can be set:
* Per checklist. In the Table view you can define multiple columns each of its own type. Then, each task of the checklist gets a column (field) of the defined type.
* Per checklist task. In the Form view each task has its own type.
* Per template task. When creating a checklist template, you can set a type for each task.

Types (whether columns or fields) are optional: you do not have to set them if you don't need them.

Note: when using the Form view we are actually adding a column (field) called "answer". That way, you can easily switch from Form to Table view and see all your "answers" in one simply column.

The following describes each of the Task Types. To illustrate their usage, we have used their Form View format. The Table format is different but the concept is the same.

## Check
A Check is the simplest type. Check or uncheck (open or completed respectively).

When used in the Form view only the standard checkbox of the task is displayed:

![](/assets/images/types/type-check.png)

When used in Table View the column will include a checkbox.

## Choice
The Choice type allows you to select an option from 2 or move options. By default, we create 2 options: OK and Not OK:

![](/assets/images/types/type-choice.png)

In the Table View columns management, or the Template Task Details pane you can edit the different options. See how to manage the [Choice Options](/checklists/table-view/#choice-type)

## Text
The Text type allows you to enter any text in one line:

![](/assets/images/types/type-text.png)

## Long Text
The Long Text type allows you to enter any text in one or more lines:

![](/assets/images/types/type-longtext.png)

## Number
The Number type limits the user input to numbers (whole or decimal):

![](/assets/images/types/type-number.png)

## Date & Time
The Date & Time type lets a user enter a date followed by the time. Click anywhere in the text box:

![](/assets/images/types/type-date-time.png)

The Date / Time picker will open (see examples below).

## Date
The Date type lets a user enter a Date. Click anywhere in the text box:

![](/assets/images/types/type-date.png)

The Date picker will open:

![](/assets/images/types/type-date-picker.png)

## Time
The Time type lets a user enter a Time of day. Click anywhere in the text box:

![](/assets/images/types/type-time.png)

The time picker will open: 

![](/assets/images/types/type-time-picker.png)

## Email
The Email type lets a user enter a (single) email address:

![](/assets/images/types/type-email.png)

## URL (link)
The URL type lets a user enter a URL (web link):

![](/assets/images/types/type-url.png)

Note that http:// or https:// at the start of the link are optional.

## File (attachment)
The File type lets a user attach one or more files to the task:

![](/assets/images/types/type-file.png)

The files can be of any type.

## Assign
The Assign type let's a user select from a list of team users or the whole team:

![](/assets/images/types/type-assign.png)
