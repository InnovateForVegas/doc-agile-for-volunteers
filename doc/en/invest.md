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

# The I.N.V.E.S.T. Acronym for User Stories (and More)

From [Wikipedia - INVEST](https://en.wikipedia.org/wiki/INVEST_(mnemonic)) and various Agile-related resources, as conceived by Bill Wake and speaking directly of Product Backlog Items (PBI) which may be User Stories, but they need not be (and this is how we will apply them, in a larger context):

| Letter | Word          | Expanded                                                                                                      |
|--------|---------------|---------------------------------------------------------------------------------------------------------------|
| **I**  | *Independent* | The PBI should be self-contained.                                                                             |
| **N**  | *Negotiable*  | PBIs are not explicit contracts and should leave space for discussion.                                        |
| **V**  | *Valuable*    | A PBI must deliver value to the stakeholders.                                                                 |
| **E**  | *Estimable*   | You must always be able to estimate the size of a PBI.                                                        |
| **S**  | *Small*       | PBIs should not be so big as to become impossible to plan/task/prioritize within a level of accuracy.         |
| **T**  | *Testable*    | The PBI or its related description must provide the necessary information to make test development possible.  |

The Wikipedia article linked above goes into some detail about each of the elements of this acronym, and is worth reading. Here we can look at our specific use of **INVEST** as applied to our Agile for Volunteers [Issue Hierarchy](hierarchy.md) which is how we construct our set of Product Backlog Items.

For a discussion about these items from the originator, Bill Wake, please visit the first in a series of articles at [XP123 - INVEST in Good Stories, and SMART Tasks](https://xp123.com/invest-in-good-stories-and-smart-tasks/) or visit the See Also links below:

## Planning

It is important to consider at all times the value of Volunteer Time, Effort, and Expertise. Breaking up an Initiative into serviceable units that can be understood, tuned and iterated upon, and converted into actual work and useful outcomes will make a given initiative, and perhaps future initiatives, attractive to Civic Volunteers near *and* far. An external contributor may have a few hours to contribute to an Open Source Community Elevation Effort, why not make the Initiative, its Issue Hierarchy, Iterations, and Tasks visible and observable, so they might consider jumping in some afternoon to make a pull request, or more…

### Independent

- Expanding on [Wikipedia INVEST - Independent](https://en.wikipedia.org/wiki/INVEST_(mnemonic)#Independent)
- See Also [XP123 - Independent Stories in the INVEST Model](https://xp123.com/independent-stories-in-the-invest-model/)

In a software project, we have something called Coupling which can lead to interdependencies between various components, some under control of the development team, some beyond that control, which can lead to road blocks and other challenges making progress.

As we apply Agile for Volunteers to all aspects of our endeavors, including all of the non-software efforts that make up an initiative, we cannot strive for independence so easily. A graphic element may depend on a user interface layout design, which may depend on a software element, which may depend on some localized text, and so on. However, it is important to keep in mind that volunteer time being as rare and valuable as it is, not every interdependent element will be completed or available with every other, so that we should always be planning for our own contribution to stand alone in as much as it can, so that it can fit in with related components if they change or become available much later.

Since we are using our [Issue Hierarchy](hierarchy.md) to define our structured Product Backlog Items, we may find at times that a given Theme, Epic, or Feature may depend on another Theme, Epic, or Feature. While the original use of *Independent* in the context of software PBIs is describing how User Stories should indeed be independent of each other as much as possible, Features should also be independent of one another, Epics should be independent of one another, as should Themes. This is not always practical, or even possible, but if we break our initiatives into these blocks in such a ways as they are not completely interdependent upon each other, we can make the most of the volunteer time, effort, and expertise we have available and apply the completed blocks to our overall initiative progress as they become available.

This will not always work out this way, but thinking about independent components will help if we find some components cannot be.

### Negotiable

- Expanding on [Wikipedia INVEST - Negotiable](https://en.wikipedia.org/wiki/INVEST_(mnemonic)#Negotiable)
- See Also [XP123 - Negotiable Stories in the INVEST Model](https://xp123.com/negotiable-stories-in-the-invest-model/)

Our [Issue Hierarchy](hierarchy.md) is designed to break our initiatives up into broad-to-specific ideas to describe what we want to accomplish and how we might go about that. Since each issue in our hierarchy is editable, each can be tuned based on any negotiation (that is, any discussion in-person or via an attached thread) so that each initiative block is a reasonable representation of the goals of the initiative and the effort that will be expended to achieve them along the initiative timeline.

Any part of an initiative can be negotiated in order to make the part achievable, including splitting up large or more complicated, labor-intensive or resource-hungry components into smaller, more achievable, more manageable blocks (see *Small* below), where some or all split blocks may be deferred into the future if and when more volunteer time and resources might be available. The nature of Civic Volunteerism makes flexibility a primary concern, which we must strive to include in our initiative definitions and planning.

It is important to consider here as well that any part of the initiative is negotiable, whether a software component or any other, and how any components will interact.

### Valuable

- Expanding on [Wikipedia INVEST - Valuable](https://en.wikipedia.org/wiki/INVEST_(mnemonic)#Valuable)
- See Also [XP123 - Valuable Stories in the INVEST Model](https://xp123.com/valuable-stories-in-the-invest-model/)

Volunteer time is Gold, as such we should strive to make each element of our initiative valuable and worthy of this golden time. As well, each block, whether expressed in broad terms as an initiative Theme or as a specific User Story, should add value to the initiative itself, whether in the near term or eventually, so that we are always aiming at using valuable volunteer time, effort, and expertise to develop a valuable initiative outcome.

It is important to note that initiative value may be dependent on the opinions and assessments of end-users, members of a local initiative cohort, or external cohort members, or others. The definition or perhaps magnitude of Value may vary, like User Stories, depending on who is asked. The value of Co-Creation can be seen here, if it is possible to include any or all of the stakeholders or end users in some or all of a design process for an initiative.

### Estimable

- Expanding on [Wikipedia INVEST - Estimable](https://en.wikipedia.org/wiki/INVEST_(mnemonic)#Estimable)
- See Also [XP123 - Estimable Stories in the INVEST Model](https://xp123.com/estimable-stories-in-the-invest-model/)

Humans are not good at estimating the amount of time it will take to do something new, or novel, which make Estimable a controversial part of the INVEST model. In the Agile Methodology origin story, the use of Story Points assigned to User Stories (and/or their associated Tasks, which are a different type of Issue in the Issue Hierarchy) prior to commencing an Iteration is a way to loosely score the amount of effort that may be required to complete a particular story or task given the length of an iteration, so that there is some way to measure effort and outcomes for the team over an iteration. This sounds like time estimation, but…

Since Civic Volunteers are offering their time, effort, and expertise toward a given Initiative, it is important to make an attempt at maximizing the utility derived from that time (effort, and expertise). If we can break up initiative blocks into achievable chunks in the iteration context, we can attempt to make the most of volunteer contribution. Thus, we want to make the most of Volunteer Contribution, not necessarily Initiative Output.

As with the original Agile methodology, our use of a Points system will aim to make the most of the available time, effort, and expertise, in the same scalable, iterable way so that on each iteration we might adjust what constitutes a single Story Point (though this is something of an abstraction), how many Points are assigned to particular User Stories (or Tasks, which are a different type of Issue in the Issue Hierarchy), and how many such Points any contributor to the iteration would like to tackle. The goal is not to complete all of the individual points, it is to help to determine how to make the most of individual contribution by tuning achievable goals.

Story Points as used for Estimation are relative and adjustable, and are not intended to be used for scoring individual participation in a competitive manner.

### Small

- Expanding on [Wikipedia INVEST - Small](https://en.wikipedia.org/wiki/INVEST_(mnemonic)#Small)
- See Also [XP123 - Small – Scalable – Stories in the INVEST Model](https://xp123.com/small-scalable-stories-in-the-invest-model/)

As an Initiative and its Themes move through the Initiative timeline, specifics may change, customer requirements may change, team size may change. This is where it is important to constrain abstract design elements into achievable chunks, so that one overly-complicated Feature or one Epic with too many Features doesn´t become an anchor that drags down progress, which can be somewhat demoralizing for those contributing their volunteer time.

Factoring the Planning Issues in the Hierarchy into Achievable units, which at the User Story level can be Implemented via Tasks within a single Iteration where possible, will make use of valuable volunteer time during any particular Iteration, and will lead to the possibility of at least similar value possibilities in the next Iteration, and so on.

### Testable

- Expanding on [Wikipedia INVEST - Testable](https://en.wikipedia.org/wiki/INVEST_(mnemonic)#Testable)
- See Also [XP123 - Testable Stories in the INVEST Model](https://xp123.com/testable-stories-in-the-invest-model/)

Make sure that the different elements of the Issue Hierarchy include descriptions of outcomes, or Key Results, that will indicate a Theme or Feature does what it should within the Initiative Context, that a reasonable amount of progress was made for the Volunteer Time expended for a particular Epic over some Iterations, and so on.

From a software perspective, a Testable Feature or User Story with descriptive Key Results of Confirmation items will be a useful guide for developing software tests, whether for TDD or for User Level QA Testing, or any variation on attempts to deliver working code to the Initiative and its Team.

From a non-software perspective, any element of an Initiative should have some way of measuring whether it matches the intended Objective and delivers on Key Results, perhaps via outreach to users for feedback, a check against native language speakers to verify language translations, and so on.

Be sure to go beyond “It looks right to me.”
