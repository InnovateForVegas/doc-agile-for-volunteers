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

# Agile for Volunteers Process

## Specifications vs User Stories

One of the core principles of Agile is to factor development into independent components and progress through these components to advance toward a completed form of the overall Initiative. The Initiative itself will almost certainly go though an evolutionary development cycle over its lifetime, but at any given time the Themes and Features that are the Initiative, from the customer point of view, are described in our [Issue Hierarchy](hierarchy.md), to provide context and loose definition for those implementing the pieces.

In our overall infrastructure scheme, the ov- repositories in GitHub, which are Initiative Overview components, fill the role of loose specification and the starting point (and storage location) of the Theme, Epic, Feature, and User Story Backlog. In the early days of an Initiative lifecycle, there is no code (or very little), likely no visualization, no content, no artwork… nothing. The Initiative Overview is a starting point with initial Blue Sky Ideation that is mostly normative, in that it is describing at a high level what the Initiative could or should be, and what the top-level parts might be, but this is not to be taken as the final roadmap for any Initiative or related Project component.

The User Stories, in keeping with the Agile method and workflow, are where we begin to spell out what a User might expect in a more granular, detailed way. While the ov- ideation documents provide a big-picture, there is no intention to make the description of the Initiative parts there, the actual parts to create and assemble. This is where Features and User Stories come into play, and even then a User Story is a more specific guide. Ultimately the individuals implementing Initiative and Project components (the User Stories and related implementation Tasks) collaborate with peers, other members of related teams, and customers, as development of the Initiative and its component Projects proceeds in a collaborative and iterative journey toward elements that do what they are supposed to do.

Does this sound vague? That is okay, because Volunteers are not putting in 40+ hours per week in exchange for a paycheck, and as empowered members of an Initiative Team (or Teams), each individual contributor plays a part in crafting what we implement and ultimately deploy to the world (software or otherwise).

## Customers

Use of the term *Customer* may seem odd if you believe a customer in the context of an Initiative is similar to a customer in a retail business setting. This is not always the case (though it sometimes is).

If you are working on a part of an Initiative or particular Project component, and another individual or team depends on your work, they are your customers. If your progress depends on the work and progress of another individual or team, you are their customer. If a person who uses Smart Calendar features needs to use an API, view a Calendar web page, or use these tools in other ways as a programmer or as someone who needs to know where they are going and at what time, these are customers. A customer has needs and expectations, and the are understood and addressed through a collaborative effort that includes comprehension and communication, along the development process.

### Internal Customers

As mentioned, your customers may be fellow volunteers working on related components, so that the collaboration process may be easier, or move more quickly, because we may all be working in familiar territory, we may know each other, and we may have the overall goals (the Capstone Initiative and its various related component Initiatives and Projects, for examples) mapped out for all to see, making our individual contributions a bit easier to understand and communicate.

Working with our internal customers will provide opportunities to collaborate more closely than we might with external customers, so that someone working on one project (a customer of yours) could collaborate with you on solving a problem, implementing a User Story, changing some details… they are part of your team, and we can take advantage of a whole-team approach with serious wins!

### External Customers

As our Initiatives and Projects become more visible, they will capture the interest of municipal partners, other open source developers, and perhaps most interesting, our friends and neighbors in our communities around us. As we become more visible, it makes sense that we involve our customers in the process so that what we develop can meet their needs, and maybe impress them a bit. This is how volunteer efforts become shining examples of work completed on a CV, and maybe even actual jobs, whether for other companies, or your own.

External customers are more likely to guide the Features and User Stories that make up the Themes of an Initiative, without joining in on actual work as we might internally. Still, a customer wants or even needs what you are working on, and as a responsible professional, one of your goals should be to meet or exceed those expectations, and keep your External Customers in the discussion along the way as much as they can be, though probably not quite as much as you can with Internal Customers.

### Co-Creation

Sometimes a *Customer* is not going to be quite so closely involved with describing and planning Initiative components. However, anyone who needs or wants what we are working on will tend to have an opinion or feedback, or maybe a good idea that we had not considered, or a bad idea that we should still consider (though maybe not as much). If we use the more familiar definition of *Customer* you had in mind before you read this section, then you have almost certainly encountered an unhappy customer who would be happy if whatever it is they want or need would work the way they want or need it to. If only there was some way for the customer to talk to the people making this thing, the fix might be obvious, or maybe it is more subtle, either way it is all too common for customers to become frustrated with their wants and needs ignored. We can tackle that.

You can visit this article, [Co-Creation](https://www.interaction-design.org/literature/topics/co-creation) and find this serviceable definition:

> Co-creation is the practice of collaborating with other stakeholders to guide the design process. Participants with different roles align and offer diverse insights, usually in facilitated workshops.

Our Internal and External Customers are stakeholders, but so are the people you have never met and may never speak to or interact with directly, but who have those wants and needs. Can they participate in the process we are describing here? Absolutely. Are they always enabled to do so? Well, we are going to make that a priority.

Elevating our community is one of our goals, including our community in our efforts is a win-win proposal.

## Iterations (aka Sprints)

The typical Agile workflow, in whatever variation you may have come across it or participated in it, involves the assumption that participants are working on their User Stories (or tasks, defects, other backlog items, etc) on a regular basis, reachable for stand-up meetings, collaborative discussions, pair programming, ideation on a design concept, and so on (coding or creating, it is a question of focus). In our Volunteer Agile scheme, we cannot possibly depend on consistent and predominant attention, focus, and effort. The path to completing Iterations will not benefit nearly so much from tuning of expectations and work progress. Since we are not a software company, our open source initiatives can proceed without the pressure of release dates and milestone constraints.

However, our internal customers are probably your fellow customers, and other people working on your project, possibly as a part of your team, and while everybody involved might be a volunteer, it is important to remember that *everybody else* is also a volunteer, which means all involved must arrive at commitment consensus. As part of a team, your effort may add to the effort of others, while your lack of effort may subtract from theirs. As we move through each successive iteration on a project timeline, we will all learn what individuals and teams can accomplish together and at what rate. This helps set expectations not only for Internal and External Customers, but also for the other members of your project team, and for yourself.

The specifics of Agile Iterations are beyond the scope of this document, and given the challenges of coordinating volunteer time and effort, we will need to collaborate and experiment a bit with what works and what might work better.

## Integration

Whether you are developing software or working on content or designing logo or user interface elements, or any of a myriad of items that make up a real Initiative, you will most likely need to make what you have completed fit into a Component Project with the work that others have completed. Sometimes, changes take place in small ways here and there, but which add up to a system that suddenly does not work. We need to avoid that, because volunteer time is difficult to come by, and we should try to spend it on progress, not error correction. Communication and clear Visibility and Observability can make a substantial difference here.

### Intra-iteration

Through each iteration interval, the members of the iteration Team need to commit at the very least to finishing and submitting the parts they take on back to the Component Project on which they are working (where their particular Task(s) are found) and making sure everything still fits together. In other words, it is going to cost time and effort of others any time a start does not include a finish, even for small Tasks and certainly for larger Tasks, so it is important to, at the very least, complete even one of the Tasks (or Defects) you commit to working on, integrating it back in to the Component Project for that iteration.

Anyone who is actively participating in an Iteration can, and should, integrate their work directly into the project. This applies to code, and any other project elements (not only the coders, but everybody!), and so members of a team should consider their efforts subject to continuous integration through the iteration interval. By integrating continuously, and testing your changes before and the integrated outcome after, you can be a part of advancing the Component Project(s) forward.

### Extra-iteration

Contributing to a Component Project outside of direct participation during an iteration is possible, and possibly appreciated, by way of a Pull Request to the Component Project repository, which can be considered during or after a current Iteration interval (or at a convenient time if there is no current Iteration).

By way of example, a suggested change to a piece of artwork or other content element(s) by an internal or external customer, fellow open source developer from parts unknown, or anyone else, can be submitted to the project team any time, with integration at their discretion, which might include rejection outright. Similar criteria are assumed as in the Intra-iteration scenarios you may encounter, except that the Extra-iteration contributions may or may no fit into the Iteration goals, or they may not work at all. Or they may be perfect.

## Stand-ups and Meet-ups

One of the core human principles of Agile is the notion that co-location and frequent interaction is a net win at every turn, from enabling spontaneous or more-easily-scheduled collaborations to casual off-topic conversations to general team building and cementing cross-function familiarity over time. In a formal workplace, or even a virtual workplace in interesting times or with remote participation as a norm, daily stand-up meetings are easy to integrate into a work day and the project workflow. They are not always appreciated, but they are more easily integrated.

In the case of a team of volunteers, even if that team is atomic for an iteration interval, it is far more difficult to ask for, and receive, a daily time commitment for stand-up meetings, however brief. It is reasonable to have monthly project meetups, but month-long iterations are almost certainly too long to maintain attention. To strike a balance between progress and flexibility, iterations of 2 weeks in time are the default, with sync meetings at the 1-week mark (assessing progress, adjusting and tweaking and whatnot), while a monthly meetup could be used as time to work in person and work on Initiative Planning across various existing and new Component Projects, etc.

We can encourage Atomic Teams to meet when they can, at some geographically convenient location at times that work for pairs or the whole Atomic Team, or online with chat or screen sharing or other forms of collaboration that enable interpersonal engagement along the way.

This aspect of Agile Methodology, for our applications, will most likely prove to be the most challenging to get right, with the largest opportunity for return on investment against the highest barriers.

Worthy of more, visit [Meetings](meetings.md)…
