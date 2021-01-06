---
layout: default
title: Team Members
nav_order: 3
parent: Teams
---
# Team Members
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Invite colleagues, customers, suppliers, friends and family to collaborate with you on getting things done! 

Membership is always within the context of a Team (and not organization). 

Once you have invited a user and they have accepted, you can fine tune their access to team resources by assigning them 1 or more roles (see [#understanding-roles](below)).

## Inviting a Member
To invite someone to be team member, navigate to that team and scroll down to the "Invite a member" section:

![](/assets/images/teams/members-invite.png)

Enter the email address of the person you wish to invite and hit the "Invite" button. We will send an invitation email to that person asking them to confirm. If they do not already have a Checklist account, they will be asked to first create one. 

Once confirmed, they will be added to the team and shown on your team page.

## Viewing Members
To view team members, navigate to the Team page and scroll down until you reach the "Team Members" section:

![](/assets/images/teams/members-view.png)

All team members, including those who are pending, will be shown in the table. Member who are still pending will only show their email address as they have not confirmed yet.

If you are a team admin, you are also able to manage the memebrs.

## Removing a Member
Team admins can remove members from the team. There must be at least one ADMIN member left. If an admin wished to remove themselves from the team, and they are currently the only admin, they must first make another user into an admin. They can then remove themselves.

An organization owner can always act as a team admin.

Non-admin user may remove themselves from the team even if they are not admins. They cannot perform any other member management action.

## Updating Member Roles
To manage the roles of a specific member, navigate to the Team page and scroll down to the "Team Members" section. On the row of the member you wish to manage, click on the existing roles to open the roles dropdown:

![](/assets/images/teams/members-roles.png)

Check or an uncheck the roles you wish to change. When ready, click anywhere on the screen (or hit Esc) to close the dropdown.

You must be an admin in order to change member roles. You cannot change the roles of Members who are still pending.

## Understanding Roles
Below is an explanation of each role. Please note that the roles are cummulative. E.g. an editor can edit templates but cannot trigger (run) them unless they also have the runner role.

Users may have no roles and are then just a team member. They can create checklists and work with them normally.

### Admin
Team admins can:
* manage the team name
* manage members (invite, remove, update roles)
* update the team timezone

Only organization admins can delete a team.

### Editor
Team editors have read/ write access to the team's templates. They can:
* view all team templates
* create new templates
* edit existing templates (of the team)
* delete a template

### Runner
Team runners are responsible for running (triggering) templates manually. They can
* From team Dashboard page view all team templates which are marked with a star
* From the team Dashboard run any "star"ed template (trigger)

### Guest
Guests play a special role:
* They do not have access to the list of Team members (i.e they cannot see who is on the team)
* They cannot have any other role other than guest

