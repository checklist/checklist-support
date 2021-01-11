---
layout: default
title: Table View
nav_order: 2
parent: Checklist Views
grand_parent: Checklists
---
# Table View
{: .no_toc }


<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

The Table view allows you add additional columns to your checklist and display them in a table format. You can add, remove, hide and customize the type of columns per checklist:

![](/assets/images/checklists/checklist-table-view.png)

## Adding Tasks
Adding tasks in the Table view is similar to [Adding tasks in Checklist View](/checklists/checklist-view/#adding-tasks)

## Editing Task name
To change the task (i.e. its name), simply click on it to enter "Edit Mode":

![](/assets/images/checklists/checklist-table-view-task-edit.png)

## Task Notes
To further elborate on a task, you can add to it Notes. To set new notes, click on the empty "Notes". To edit existing notes, click on them. 

![](/assets/images/checklists/checklist-table-view-task-notes.png)

 The Notes dialog will open:

![](/assets/images/checklists/checklist-table-view-task-notes-open.png)

Enter your notes or make the desired changes and click Save.

## Deleting Tasks
To delete a task click on the Delete button (Trashcan) on the task itself:

![](/assets/images/checklists/checklist-table-view-task-delete.png)

## Columns
The biggest different between Checklist and Table views are "Columns". Columns allow you to add an unlimited number of "fields" (columns) to each task. This means that each task can include more data. Once you add a column, it is available to all tasks on this checklist (even sub or sub sub tasks).

By default, the following fields are created for each checklist:
* Assign
* Due Date
* Attachments
* Priority

Depending on your organization billing plan, you can add more fields or edit existing ones.

### Managing Columns
To manage your checklist columns, click on the Columns button:

![](/assets/images/checklists/checklist-table-view-columns-menu.png)

The Columns Management dialog opens:

![](/assets/images/checklists/checklist-table-view-columns.png)

The dialog shows you which columns have been defined for this checklist. Each columns has:
* a checkbox - this determines whether to show (checked) or hide (unchecked) the column in the table itself 
* name - the name of the columns
* edit button (pencil) - use it to make changes to the column

If you wish to add a column, hit the Add Column button.

### Add / Edit a column
The Add/ Edit Column dialog:

![](/assets/images/checklists/checklist-table-view-column-edit.png)

The dialog includes:
* name - 1-20 alphanumeric characters ( '-' '_' and spaces are allowed)
* type - the column type - [see below](#column-types)
* key - this is automatically generated from the column name. Once set, cannot be changed. 
* description - this is shown as a tooltip with mouse over the column name
* options - only applicable for type Choice. [See below](#choice-type).

### Delete a column
To delete a column:
* open the Columns dropdown by clicking on the Columns button
* click on the Pencil next to the column you wish to delete
* the Edit Column dialog opens
* click on Delete button at the bottom of the dialog

### Column Types
The following column types are available:
* Check
* Choice
* Text
* Long Text
* Number
* Date & Time
* Date
* Time
* Email
* URL (link)
* File (attachment)
* Assign

To change a column type:
* open the Columns Management dialog
* click on the Edit (pencil) button
* on the Column Edit dialog use the Type selector:

![](/assets/images/checklists/checklist-table-view-column-types.png)

### Choice Type
The Choice Type allows users to choose from a number of options. The Priority column is an example of a column using the Choice Type:

![](/assets/images/checklists/checklist-table-view-priority-open.png)

The column is of Choice type with the following options:
* low
* medium
* high

If you try to edit the column you will see at the bottom of the Column Edit dialog the 3 options:

![](/assets/images/checklists/checklist-types-choice-menu.png)

You can:
* click on the option name to edit it
* click on the Trash button to delete an option
* click on the + Add Option button to add a new option
* drag and drop an option to reorder it
* click on the color section of an Optin to get the color picker:

![](/assets/images/checklists/checklist-types-option-color-picker.png)

## Subtasks
Subtasks on Table view is similar to [Checklist View SubTasks](/checklists/checklist-view/#subtasks)

## Task Re-Ordeing
If you wish to change the order of tasks, you can do so by dragging the task and dropping it at the desired new location:

![](/assets/images/checklists/checklist-table-view-dnd.png)

## Density
Depending on your preference, you can increase or decrease the density (how much spacing between table row). Use the toggle below the table:

![](/assets/images/checklists/checklist-table-view-density.png)

The density is stored on your browser and kept between navigation and sessions. It is not saved to the cloud and therefore not shared with others.