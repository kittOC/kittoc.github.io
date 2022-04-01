#  Why Github Projects and How we intend to use them
This text is addressed to the mentors of the kitt4sme Open Call (OC) projects.

## tldr;
using the `issues` to monitor the progress of the tasks defined in the projects'
workplans; `issues` are also the place to ask technical questions; no code has
to go through this repo (unless it helps with the question)


## Overview of the setup
- **Why on Github**: Because our (project's) technical teams uses it to track
  progress. It is also common practice for software developers to use git-based tools
  hosted by Github or Gitlab. The OC-teams are very likely to be already
  familiar with this approach.
- **What are `issues`**: issues, for kitt4sme OC mentoring, serve two purposes:  

  (1) are `tasks` (pieces of project-work) to be tracked and   
  (2) are the way to communicate 'barriers' (technical problems/ questions). 
  
  The tasks (1) are given in the workplans prepared by each OC-project (each 'Name of the Task' in
  the corresponding tables). The technical questions (2) are described by the
  developers of the OC-project teams and they should address primarily the
  technical team of the kitt4sme project (*the mentors are responsible to do the
  assignment*).
  
  
## How to use the Github Project
One Github project has been created for each OC project. The mentors have been
added to the project. The mentors will need to ask for the Github user names of
the OC projects' representatives and add them to the corresponding repository.
The Github
guide on [this link](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)
describes how to add users to the repository.
- **How to use `issues`**: create an issue for each task from the workplan and
  place it under the `Uncategorized` column. Prioritize them according to the
  rule: 'issues with the most recent deadline go on top'. During your bi-weekly
  meeting with the projects, decide on which of them they will be working on in
  the next couple of weeks. Promote these issues to the `Selected for
  Development` list. The OC-project team is responsible to move them accross the
  board, that is `Doing` & `Done`.
    - If the OC-project team faces a technical issue on which they need support
      from the kitt4sme team, then they visit the `Discussions` under the
      `kittOC/FAQs-and-Technical-issues` and look for a discussion that may
      be already an answer to their question; assuming they do not find
      one, they go through the next steps:  
        1. the OC-project team moves this task to the `Blocked` column
        2. the OC-project team goes in the issue (clicks `Go to issue for full
           details` and describes the problem in technical terms (steps they
           have followed, relevant code snippets, etc.))
        3. the `question` label is assigned to this task
        4. the OC-project team contacts the mentor (via e-mail or by assigning
           the task to the mentor)
        5. the *mentor* assigns this task to the user
           from the project dev. team responsible for the selection and
           prioritization of the questions
- **What should happen after the issue has been assigned**: the user from the
  project dev. team brings the issue to the biweekly sprints of the dev. team
  and assigns it to a member of the dev. team. This member is responsible to
  create a new `Discussions` under the `kittOC/FAQs-and-Technical-issues`
  repository. All OC-project teams need to follow the `Q&A`s in this repository
  **before** asking a new question (simply because it is likely that their
  question has already been answered there).

## Discouraged Practices
- *OC projects adding questions to the `FAQs-and-Technical-issues` board*:
  simply because the kitt4sme technical team does not have the resources to
  monitor the channel for new questions and address them. The result is that
  they remain unanswered
- *OC projects getting in touch with the project's dev. team directly*: the
  mentors are the first point of contact between the OC projects and kitt4sme.
  They are responsible for the communication with the respective partners. This
  structure has been adopted because we need to make the most out of very
  limited resources.
- *Mentors sending every technical question to the tech. team*: the kitt4sme
  platform is based on some common industry practices; the examples prepared by
  the project's technical team are meant to describe the basics of the platform
  composition. kitt4sme has asked (via the Open Calls) from 3d parties (the ones
  selected) to familiarize themselves with the technologies used (it is
  essentially a mini cloud platform) and try to integrate their solutions to the
  mini-platform (described in [this
  documentation](https://github.com/c0c0n3/kitt4sme.live/blob/main/docs/bootstrap.md))
  (reference platform). This is an activity that has to be carried out by the
  project-teams themselves. The kitt4sme technical team will support their
  questions in terms of specific problems and to be more accurate when
  particular technologies/ choices seem to clash. It will not however answer
  questions of the nature 'i tried to do what you describe and it didn't work
  for me, what should i do next?'


## Navigation and Quick Links


- [Discussions
  board](https://github.com/kittOC/FAQs-and-Technical-issues/discussions)
- [Projects list](https://github.com/orgs/kittOC/projects) - find yours here
  (the Kanban board is in your project)
- [Teams list](https://github.com/orgs/kittOC/teams) - no need to use it, but
  you can find your team here
- [Repositories list](https://github.com/orgs/kittOC/repositories) - no need to
  use it, but you can find all the issues that you create from the Kanban board
  living inside your team's repository

**Reminder**: Projects and Teams live on the [level of the
Organization](https://github.com/kittOC) (i.e. kittOC); if you cannot find what
you are looking for, jump to the top level (organization) and search for your
Project there.

## Github guides

- Github Training Guides: [brief
  overview](https://www.youtube.com/watch?v=C6MGKHkNtxU)
- Github Training Guides: [managing
  projects](https://www.youtube.com/watch?v=nI5VdsVl0FM)
- Github Training Guides: [github kanban board (skip to
  3:06-6:30)](https://www.youtube.com/watch?v=ff5cBkPg-bQ)


## Visual reminders
Some snapshots to guide the eye..


#### organization level
![organization_level][organization.level]

#### create a new issue from the Kanban board
![create a new issue from the Kanban board][issue:create2]

#### convert note to issue [step 1]
![convert note to issue][convert:issue0]

#### convert note to issue [step 2]
![convert note to issue][convert:issue]

#### open issue
![open issue][open:issue]

#### access issue history
![issue history][issue:history]

#### create a new issue from the `issues** tab

**Comment***: you don't need to use this way of creating an issue
![create a new issue from the `issues` tab][issue:create1]





[organization.level]: ./how_to_github/organization_level.jpg
[issue:create1]: ./how_to_github/create_issue1.jpg
[issue:create2]: ./how_to_github/create_issue2.jpg
[convert:issue0]: ./how_to_github/convert_issue0.jpg
[convert:issue]: ./how_to_github/convert_issue.jpg
[open:issue]: ./how_to_github/open_issue.jpg
[issue:history]: ./how_to_github/edit_issue.jpg
