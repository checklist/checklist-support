---
layout: default
title: Search
nav_order: 8
---
# Dashboard
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Checklist Search allows you to search your checklists:

![](/assets/images/search/search.png)

To access the search page, click on the Search Menu button on the main navigation:

![](/assets/images/search/search-menu.png)

Note that search is limited to the active team which is displayed at the top of the search page. If you wish to search a different team, first switch to that team from the Team menu.

The search page is divided into 2 parts: Filters and Results:

## Search Filters
You can filter your search by:

* Text. This includes: checklist names, task names and task notes.
* Folder. Limit your search to a specific folder
* Template. Limit your search to checklists which were created from a specific template
* Assigned to. Limit your search to checklists assigned to a particular user (or entire team)
* From. Limit your search to checklists from a certain date
* To. Limit your search to checklist up until a certain date
* Archived. Limit your search checklists: 
  * from your archive
  * not in the archive
  * both archived and not archived

Click the Clear button to reset the search and remove any filters.

Click the Search button to perform the search and view the search results in the bottom pane:

## Search Results

Once you click on search, Checklist performs a search in our database and returns any matching checklists showing them in a table including these columns:

* Name. This is the name of the checklist matching your search
* Status. This is the status of the checklist matching your search
* Created. The date the checklist was created
* Notes. Any checklist notes
* Open tasks. This shows the number of open tasks out of the total of tasks in the checklists.

At the bottom of the table you can see a pagination widget:
* Rows per Page: you can set how many search results to see at a time
* Pages. you can see which page you are on (out of hwo many)
* Pagination - use the arrows to paginate back and forth between pages

## Search Results Actions

Each checklist will include a checkbox which allows you to select it (or by clicking on the row). When there are selected checklsit, the Actions menu will show at the top right of the results table:

![](/assets/images/search/search-actions.png)

The menu allows you to:
1. Delete. This will delete (after confirmation) the selected checklists
1. Archive. Mark your checklists as archived. 
1. Un-Archive. Take your checklists out of the archive.
1. Export. See below

Note that archived checklists cannot be edited. To make changes to an archived checklist you must first take it out of the archive.

## Export Checklists
If you wish to export the checklists (as well as any attachments), click on the Export button to open the Export Dialog:

![](/assets/images/search/search-export.png)

You can export in the following formats:
* CSV - comma separated files. Each checklist will be in a separate file
* PDF - each checklist will be in a separate PDF document
* JSON (with attachments)
* JSON (without attachments)

We will create the export and zip it into one file and then send a link to this file (together with the optional message) to the email addresses provided. 

Note: only PRO accounts can select an email and a message. Other users will get the email to their own mailbox.