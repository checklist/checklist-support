---
layout: default
title: Search
nav_order: 10
---

# Search

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Checklist Search allows you to efficiently search through your checklists:

![Checklist Search](/assets/images/search/search.png)

To access the search page, click on the Search Menu button in the main navigation:

![Search Menu](/assets/images/search/search-menu.png)

Note that the search is limited to the active team displayed at the top of the search page. If you want to search a different team, switch to that team from the Team menu first.

The search page is divided into two parts: Filters and Results.

## Search Filters

You can filter your search by:

- Text. This includes checklist names, task names, and task notes.
- Folder. Limit your search to a specific folder.
- Template. Limit your search to checklists created from a specific template.
- Assigned to. Limit your search to checklists assigned to a particular user (or the entire team).
- From. Limit your search to checklists created from a certain date.
- To. Limit your search to checklists up until a certain date.
- Archived. Limit your search to checklists:
  - from your archive
  - not in the archive
  - both archived and not archived

Click the Clear button to reset the search and remove any filters.

Click the Search button to perform the search and view the results in the bottom pane.

## Search Results

After clicking on search, Checklist performs a search in our database and returns any matching checklists, showing them in a table with these columns:

- Name. The name of the checklist matching your search.
- Status. The status of the checklist matching your search.
- Created. The date the checklist was created.
- Notes. Any checklist notes.
- Open tasks. The number of open tasks out of the total tasks in the checklist.

At the bottom of the table, you can see a pagination widget:

- Rows per Page: Set how many search results to see at a time.
- Pages: See which page you are on (out of how many).
- Pagination: Use the arrows to paginate back and forth between pages.

## Search Results Actions

Each checklist includes a checkbox allowing you to select it (or click on the row). When checklists are selected, the Actions menu appears at the top right of the results table:

![Search Result Actions](/assets/images/search/search-actions.png)

The menu allows you to:

1. Delete: Delete the selected checklists after confirmation.
2. Archive: Mark selected checklists as archived.
3. Un-Archive: Take selected checklists out of the archive.
4. Export: See below.

Note that archived checklists cannot be edited. To make changes to an archived checklist, you must first take it out of the archive.

## Export Checklists

To export checklists (including attachments), click on the Export button to open the Export Dialog:

![Export Search Results](/assets/images/search/search-export.png)

You can export in the following formats:

- CSV: Comma-separated files. Each checklist will be in a separate file.
- PDF: Each checklist will be in a separate PDF document.
- JSON (with attachments): Not available for the FREE plan.
- JSON (without attachments): Not available for the FREE plan.

We will create the export, zip it into one file, and then send a link to this file (together with an optional message) to the email addresses provided.

Note: Only PRO accounts can select an email and a message. Other users will receive the email in their mailbox.
