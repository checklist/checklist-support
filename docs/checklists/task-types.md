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
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Task types extend beyond a simple checkbox for each task, allowing for additional fields of different types. These types can be configured in various ways:

- Per checklist: In the Table view, multiple columns can be defined, each with its own type, and each task gets a column of the defined type.
- Per checklist task: In the Form view, each task has its own type.
- Per template task: When creating a checklist template, a type can be set for each task.

Types, whether columns or fields, are optional; you don't have to set them if not needed.

Note: In the Form view, a column (field) called "answer" is added. This way, you can easily switch from Form to Table view and see all your "answers" in a single column.

The following describes each of the Task Types, illustrated using their Form View format. The Table format is different, but the concept remains the same.

## Check
A Check is the simplest type, allowing you to check or uncheck (mark as open or completed).

- In the Form view, only the standard checkbox of the task is displayed:

![Task Check Type](/assets/images/types/type-check.png)

- In Table View, the column includes a checkbox.

## Choice
The Choice type enables the selection of an option from two or more options. By default, two options are created: OK and Not OK.

![Task Choice Type](/assets/images/types/type-choice.png)

In Table View columns management or the Template Task Details pane, you can edit different options. See how to manage [Choice Options](/checklists/table-view/#choice-type).

## Text
The Text type allows you to enter any text in one line:

![Task Text Type](/assets/images/types/type-text.png)

## Long Text
The Long Text type allows you to enter any text in one or more lines:

![Task Long Text Type](/assets/images/types/type-longtext.png)

## Number
The Number type limits user input to numbers (whole or decimal):

![Task Number Type](/assets/images/types/type-number.png)

## Date & Time
The Date & Time type lets a user enter a date followed by the time. Click anywhere in the text box:

![Task Date Time Type](/assets/images/types/type-date-time.png)

The Date/Time picker will open (see examples below).

## Date
The Date type lets a user enter a date. Click anywhere in the text box:

![Task Date Type](/assets/images/types/type-date.png)

The Date picker will open:

![Task Date Picker](/assets/images/types/type-date-picker.png)

## Time
The Time type lets a user enter a time of day. Click anywhere in the text box:

![Task Time Type](/assets/images/types/type-time.png)

The Time picker will open:

![Task Time Picker](/assets/images/types/type-time-picker.png)

## Email
The Email type lets a user enter a (single) email address:

![Task Email Type](/assets/images/types/type-email.png)

## URL (link)
The URL type lets a user enter a URL (web link):

![Task Link Type](/assets/images/types/type-url.png)

Note that http:// or https:// at the start of the link is optional.

## File (attachment)
The File type lets a user attach one or more files to the task:

![Task File Type](/assets/images/types/type-file.png)

The files can be of any type.

## Assign
The Assign type lets a user select from a list of team users or the whole team:

![Task Assign Type](/assets/images/types/type-assign.png)
