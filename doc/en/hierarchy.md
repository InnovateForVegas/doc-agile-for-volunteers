<!--
 Copyright (C) 2024 Innovate for Vegas Foundation
 
 This file is part of doc-agile-for-volunteers.
 
 doc-agile-for-volunteers is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.
 
 doc-agile-for-volunteers is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License
 along with doc-agile-for-volunteers.  If not, see <https://www.gnu.org/licenses/>.
-->

# Issue Hierarchy as used in Agile for Volunteers

A quick search for Agile and related methodologies and how to organize User Stories will reveal a collection of terms used to group and organize user stories for the purposes of Iteration Planning and for connecting User Stories in meaningful ways which make the overarching project, or Initiative, visible to a casual observer.

From Planning and Implementation perspectives, we first define some structure to allow us to Organize. If we were to create an Initiative table or matrix to start, the Planning issue hierarchy may be the Rows of this table, while specific Project Repositories for Implementation might be the Columns.

## Planning

Here we address the *Who*, *What*, and *Why* questions and so these Issues within the Hierarchy are more Abstract and do not aim to spell out specifics. They should be composed to inform any individual contributor considering joining a project or perhaps offering an external contribution of their volunteer time, effort, and expertise.

### Initiative

If we describe a problem to solve, a gap to fill, a question to answer, we have the basis of an *Initiative*. We might begin with a problem statement, general or specific or somewhere in between, and add some initial ideas about what the problem statement might imply and how these implication might give direction to solutions or other outcomes.

From a planning perspective and in our Issue Hierarchy, the Initiative is a single root described with Blue Sky documents and discussion and is more concrete than its constituent Theme(s). As such, there will not typically be an explicit Initiative Issue, and an Initiative should be defined broadly enough so that changes to it will appear within existing Themes, or within added Theme(s). Changing an Initiative otherwise would (or should) have a ripple effect on all aspects of the Initiative once underway.

The *Initiative* itself is embodied in a project repository typically named with an **ov-** prefix, for *Overview,* which on the GitHub platform will contain the Blue Sky documents and discussion, as well as the Issue Hierarchy for Planning, ongoing Discussion, Feature and Theme Requests, the GitHub Project tools, and so on.

### Theme

If our Initiative is a home, a Theme might be a room in that home. As anyone familiar with a Studio Apartment is aware, an Initiative might have only a single *Theme*, or it may have many *Themes*.

The *Theme* is the top of our Issue Hierarchy for our Initiative, each Theme should be as independent of any other Themes in an Initiative as possible, though this as an unattainable goal is not detrimental. Being aware of any interdependence across *Themes* is essential, however.

Over the course of the Initiative Timeline, changes to a Theme may be required as lessons are learned, problem statements are clarified, subtleties realized. Ideally such changes can appear at the Feature or User Story levels to address more specific realizations, but the Theme is always subject to Negotiation just as any other Issue in the Issue Hierarchy.

### Epic

This is a term encountered more frequently in Agile and Agile-adjacent methodologies. We treat an *Epic* as a collection of *Features* that are associated with each other by some measurement and which might be addressed in one or more iterations as a group. This is not a hard and fast requirement by any means, but if this is the basis for forming Epics within the Issue Hierarchy, and if each Epic can be edited to add or remove Features as needed, then an Epic may indeed fit the bill.

If we can assemble an Epic from Features that are logically related (if not interdependent), and if we can organize one or more Iterations to work on a given Epic, we may after one or more Iterations have a completed Epic, which should leave us with one or more Features that are demonstrable, testable, usable, maybe even deployable. It is important to remember that an Epic is Negotiable, as with all Issues in the Issue Hierarchy, and an Epic is not a Race, nor is it something that will be assessed as Pass or Fail. It is a unit of organization and planning.

### Feature

This is often an aspect of an Initiative that is visible or otherwise tangible to an End User, Stakeholder, or Customer. If our Initiative is a Home, and a Theme is a Room, then a *Feature* might be the furniture, the outlets and light switches, the doors, appliances, counter tops, cabinets, drains, and so on.

Describing a *Feature* is something which may require practice, and use of [Ubiquitous Language](glossary.md) will be valuable here as the Initiative progresses with the possibility of additional Civic Volunteers joining the effort for a single pull request, iteration, or deliverable. Remember that if a Feature is initially described in terms overly broad, it is possible and perhaps advisable to split the Feature into multiple Features, and in the other direction it is possible to consolidate overly-specific Features into a Merged Feature.

Continuing with our Room analogy, we may describe a Cabinet Feature and a Counter Top Feature for a Bathroom Theme, and we may at first believe that they could be merged into one Feature, or we may view these as interdependent Features with the added consideration that the Cabinet Feature needs to be completed before the Counter Top Feature can be started (yes?), and so it may be useful to organize these two Features into separate Epics. Ideally, this organization and these relationships will be visible to anyone contributing their time to the Initiative in any capacity (or anyone considering doing so).

### User Story

The usual element of Agile that some are familiar with, by name at least, the *User Story* describes a particular *Feature* from a specific User Perspective. One Feature may have one, two, or more variations based on different use scenarios by different Users.

### External Bug

Perhaps the most familiar term to anyone using any technology, perhaps because *Bugs* are found so often by end users, customers, and people in general.

An End User, Customer, or anyone not familiar with the Initiative in some detail may encounter a problem that leads to an unexpected or undesirable outcome, ranging from a cosmetic interface issue to a data loss or security concern. It is perhaps a better choice to have a customer-facing service, ticketing system, or reporting scheme (including email) to accept descriptions of *Bugs* or similar potential problems so that they might be distilled into addressable *Defects* (see below).

Without familiarity with the overall Initiative structure, it is a certainty that an *External Bug* submission will be anecdotal observation about behavior or outcome, which will require an intake triage process ultimately informing the creation of one or more actual *Defects* as appropriate. It is important to capture the incoming submission and attribution for the purposes of feeding back updates and fixes so that those who take the time to share their concerns and provide useful Bug Reports can be alerted to when *their Bug* is addressed.

## Implementation

Here we address the *When* and *How* questions and so these Issues within the Hierarchy are more Concrete and do aim to describe specific details.

### Project

This is a term often used generically for something we work on, and the same is true here. However, a *Project* in our planning context and issue hierarchy is where we keep track of actual contribution of work, which in the context of a platform like GitHub takes the form of a Repository.

### Task

We can describe a Concrete Implementation of an Abstract Description found in a User Story of a Feature we need in our Initiative, the *Task* is that Concrete Implementation Description.

In a software development context, it is possible, and advisable, to associate actual development work with a particular *Task*, which will make Planning easier over each Iteration. This is also true of a Pull Request if an external contributor would like to add some volunteer effort to the undertaking (this may or may not align with a particular iteration), and in fact these are typical use cases for Task issues in a Project.

In a non-software context, a Task has similar meaning, but its use to keep track of specific implementation is less likely to be directly comparable to the software case. IF it is possible to associate non-software work to a Project Repository Commit, associated with a Task, the task itself could be handled as any software task is, but the actual work (a physical object, a media file, output from third-party tools not-compatible with a tool like git, etc) might exist elsewhere. The goal of using the Task in the Issue Hierarchy is to maintain visibility and observability of the Initiative and its parts, Progress made, and Opportunities to Contribute… in addition to generally keeping track of contributions for progress and attribution.

The *Task* is important. A Task may not be completable in a single or even two Iterations, which may lead to splitting a single Task into one ore more Tasks, or reassessing the Task strategy completely. While completing a Task is a good thing, not-completing a Task is a learning experience and an indication that more consideration is needed for the next try.

### Defect

A *Defect* may be submitted against any Project Repository, in any context, indicating some unexpected, undesirable, or even unpredictable behavior that may lead to some catastrophic failure or some simple usability concern.

Within the Issue Hierarchy, a *Defect* is submitted directly to a particular Project Repository by a fellow team member working directly on the same Project or some other part of the overall Initiative. Ideally such Bug issues will provide enough information to triage and diagnose a potential root cause and solution, so that such effort can become part of an iteration. Note that *Bugs* will, thanks to how time works, become apparent after the iteration in which the cause of the Bug became a part of the project. In other words, a Task completed in one iteration may lead to a Bug in the next or next again iteration, or even later.

The casual user or customer may not be so adept at filing bug reports, thus the *External Bug* as described above is the starting point to capture an external submission, triage the concern, and construct one or more *Defects* in appropriate Project Repositories based upon this external submission.
