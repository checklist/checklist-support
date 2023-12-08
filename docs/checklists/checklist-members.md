---
layout: default
title: Checklist Members
nav_order: 1
parent: Checklists
---

# Checklist Members

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

When a checklist is created, the user creating it becomes its owner by default. If the checklist is created from a template or via automation (recipe), then the owner can be different.

## Definitions

### Owners

A checklist can be owned by one or more team members. It cannot be owned by a guest user.

Checklist owners can make any change to the checklist, its meta (structure) or its content.

### Members

Checklist owners can invite other users to collaborate on a checklist. They become Checklist Members. Members don't have the same rights as Owners. They are limited by the "Permissions" setting for the checklist (see below).

## Permissions

Checklist Permissions can be used to limit what Checklist Members are able to do with the checklist. They do NOT limit Checklist Owners

The four permission levels are:

- All
- Content
- Assign
- View

The default permissions level for a newly created checklist is "Content".

See the different levels description below:

### All

If the checklist has the "All" permission then checklist members are virtually the same as owners: they can perform the same actions as owners.

### Content

When a checklist has the permission "Content" then checklist members can only make changes to the **content** of the checklist. They:

- Cannot change the checklist meta (columns)
- Cannot change the checklist name
- Cannot make changes to any of the checklist settings
- Cannot delete the checklist
- Cannot create a template from the checklist
- Cannot create automations
- Cannot change the Checklist View (they can only view the default view of the checklist)
- Cannot manage team members other than remove themselves
- Changes they make to the sort order or filtering are only applicable to them

### Assign

When a checklist has the "Assign" permission then the checklist members can only make changes to the content of tasks assigned to them. All other actions are not available to them.

Members can still remove themselves from the checklist.

### View

When a checklist has the "View" permission then the checklist members can only view the checklist and make **no** changes to it.

Members can still remove themselves from the checklist.

## View Checklist Members

To view the checklist members, click on the "Checklist Members" button at the top right of the screen:

![Checklist Members list](/assets/images/checklists/checklist-members-open.png)

The Checklist Members dialog will open:

![Checklist Members dialog](/assets/images/checklists/checklist-members.png)

At the top you can see who already are members of the checklist. Owners are marked with a checked box.

Below it you will find the permissions of the checklist followed by a drop down to add more members from the team.

Note: if you are not an owner of a checklist, you will not see the Checklist Members button. To remove yourself from a checklist, simply click on the Delete Checklist button from the Checklist Menu.

## Adding members

To add a member to the checklist, you must be a checklist owner. Open the Checklist Members dialog and click on the "Add a Checklist Member" drop down to see which team members are not yet members and can be added:

![Add a Checklist member](/assets/images/checklists/checklist-add-member.png)

You can also add the whole team as a member. This will allow anyone in the team (except for guests) to become members.

Once added, the member can be seen in the members list:

![Checklist member added](/assets/images/checklists/checklist-member-added.png)

## Removing members

To remove a member from a checklist, you must be a checklist owner. If you are trying to remove yourself, there must be another checklist owner (otherwise the checklist will become an orphan).

Open the Checklist Members dialog and click on the Trash icon next to the member you wish to remove:

![Checklist member remove](/assets/images/checklists/checklist-member-remove.png)

The member will be removed and will be added to the "Add a member" dropdown in case you change your mind and we to add them again.

## Updating Ownership

To manage checklist ownership, you must be an owner yourself. Open the Checklist Members dialog:

![Set checklist owner](/assets/images/checklists/checklist-owner-manage.png)

### Adding an owner

To make an existing member into an owner, simply check its "Owner" checkbox.

### Removing an owner

To make an existing owner into a member, simply uncheck its "Owner" checbox.

Note that if there is only one owner for the checklist, that owner's checkbox will be disabled (grayed out) to avoid making the checklist an orphan.

## Setting Permissions level

To change the permissions level of a checklist you must be an owner of the checklist. Open the Checklist Members dialog and click on the members permissions dropdown:

![Set checklist permissions](/assets/images/checklists/checklist-permissions-open.png)

The 4 different levels will be shown:

![Checklist permission levels](/assets/images/checklists/checklist-permissions.png)

Choose the desired permission level.
