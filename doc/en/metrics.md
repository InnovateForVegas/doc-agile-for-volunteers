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

# Metrics: Points and Productivity vs Volunteer Appreciation

One of the least-liked aspects of various implementations of the Agile Method for Software Development (and Extreme Programming before Agile came along), is the vague notion of *Story Points*. As designed, Story Points are intended to provide a coarse measurement of estimable progress, made more useful in short order by adjusting how story point estimations are selected based on previous sprint or iteration progress. Easy!

Or maybe not. Story Points may be useful with a team that tends to work together, so that the point values (which are to be selected and agreed-upon by the team) assigned to tasks (eg implementation of User Stories) will tend to reflect individual and group productivity, which is intended to be useful for the Whole Team (including customers, program managers, et al) to have some idea where the Initiative is in some production timeline. The real goal is a measurement of productivity so that any estimation of milestones, ship dates, and so on can be made in the interest of the placement of the outcome (software product, new version, etc) into the marketplace, or into the hands of the customer, for some predicted business upside(s). A for-profit software company is rightfully focused on such things.

Agile for Volunteers is focused more on appreciating the value of Volunteer Time, Effort, and Expertise, and while Story Points could be useful, they are too often the basis for judging productivity, which is not how we need to measure what we need to measure in Volunteer space. We are not justifying development budgets or fretting over release dates, we are not grading and evaluating contributors based on the number of Story Points they complete over some time interval.

We can leave Story Points to the person who invented them and their use, Ron Jeffries, with his comments from 2019 from his blog, [Story Points Revisited](https://ronjeffries.com/articles/019-01ff/story-points/Index.html).

What we do want and need to accomplish is some measurement of how a cohort of volunteers is able to collaborate so that the time, effort, and expertise contributed by any individual contributors can be measured against the cohort as a whole. Is this a form of evaluation and judgement? No, that is not the intention at all.

## Volunteering Together

One analogy we can make here is any individual activity that we can participate in as a group. Walking, biking, envelope stuffing, or any similar activity where a cohort is doing something, perhaps moving from an origin to a destination or performing some assembly-line-like task. Whatever the activity might be, there may be some cooperation between individuals during, but participation is ultimately a matter of individual contribution of action.

When participating in such group efforts, it is usually a good idea to stick together. To keep pace with the pack, not get too far ahead, avoid falling too far behind. This is ultimately healthy for the pack, or group, or team since the reason we are participating in this effort together is to accomplish our goal together. There is no intent to compete, to arrive at some scoreboard with winners and losers. Indeed, the goal is quite the opposite, to enable individual participants to maintain a pace, to slow down a bit when getting out ahead, and to perhaps analyze a particular situation if we need to catch up.

In an assembly or production line, where the line is split into stations, any particular station should accept an input from the previous station and hand off an output to the next station. There are times when a station takes longer than the station before, which can lead to the stations after falling behind. The solution is usually as simple as increasing the number of stations that take longer (double, for example), so now that station can match the input to the output flow rate. The pack can move along once we pick our pace, the goal is the Initiative, not penalties, not scoring, not winning or losing.

## Torques

We have mentioned the three elements of Volunteer Contribution: Time, Effort, and Expertise. Recall, Agile for Volunteers is intended to work not only for Whole Team, but for Whole Initiative as well, and not every Component of each Initiative is Software, just as there will be members of the Whole Team who are not software developers. Using Story Points for User Stories breaks down pretty quickly once we leave the software development realm.

If we intend to keep track of pacing, first we need to move the measurement point from the User Story (or more generally, the Initiative Planning) side, and to the Implementation (or Component Project Task) side. Sides, really, because any given planning element (Feature or Story, for examples) maybe have more than one Implementation task associated with it. Perhaps we need to 3D Print something, write some software, translate some user interface information into multiple languages, and whatever else comes along. It makes no sense to make any attempt to estimate a User Story in planning when we need to consider the various kinds of tasks of different kinds may be associated with a single User Story.

Take a moment and skim the Wikipedia article on [Torque](https://en.wikipedia.org/wiki/Torque).

The approach we take here is this:

1. Select one or more Tasks to tackle during an Iteration time interval (typically 2 weeks, or 14 days)
2. For each task, estimate how much of *your* effort you feel it will take to complete.
3. With each effort estimate, include an expertise estimate. How well do you know or understand what you´re going to do?
4. At the end of the Iteration, estimate how much of *your* actual effort you expended for the task, or the part of the task you completed (we can split tasks and move the unfinished parts to a later iteration)
5. As well, include an expertise value that you think actually applies (that is, you guessed before the iteration, what do you choose after).
6. Leave the pre-iteration and post-iteration values. Over time, you will have a feeling for how closely you estimate before what you might end up with after.

They values are not scored against you, hang on.

### Effort X Expertise

If you read over that Torque article, or if you are already familiar, you can envision that Effort as a Force (F) that you are applying to the task, which we can envision as a wheel or sprocket perhaps. Your Expertise is the distance (r) from the center of disk to the edge where your Effort (F) is applied. If we multiply these two numbers (well, a vector cross product, simplified to rF sin theta which simplifies to rF at 90 degrees), we get a torque value.

We keep both numbers (Effort, Expertise) for your own trend line, and if multiple people work on a task (together during an iteration or over multiple iterations, or both), we can add torques. No, we do not assume a standard reference or units, some experimentation will help determine whether Effort is some percentage of full range, some fraction of the amount of total effort you had to offer anything through the week… Similarly with Expertise, we can start with a value of 1 if you are able to tackle the challenge, maybe 10 if you are the inventor of a programming language or method of working with solid materials or a licensed language translator… again, we may need to tune these a bit.

With that caveat, Torques can be added, which is how we can make use of these number pairs to get started.

### Time

Volunteer time is perhaps the most valuable if only because we do not get more.

If we multiple Torque by Time, we should end up with some indication how much total effort (scaled by expertise) was contributed.

If we divide Torque by Time, we should end up with some idea how much effort was exerted per unit of time.

These are interesting for different reasons, and so the Time value would be kept separate (if we multiple numbers and only keep the product, we lose the detail. Opaque numbers are not as interesting nor as valuable). The Time can also be used as a base value, such as total iteration time as Time. The units might be Hours, or even Minutes. If we assume that Effort will have some inherent indication of actual or fractional time based on the total iteration Time value, we can keep the math fairly simple and avoid too much vague estimation that requires consensus.

### Output

What we do get with these three numbers (well, two sets of three numbers per person per iteration) should fall within what have referred to as the pace of the pack or team working on something. The Torque values should ideally be reasonably close to each other, if they are not we take a closer look and see what is actually happening.

To create a 2D point cluster we could simply plot the Effort and the Expertise values on a 2D plane, the points should cluster.

Time as a scalar is interesting over time, if we use the same value for all Torques then it will not change the individual points. The Time scalar would be used to examine trends that might be useful to the cohort. It cannot be stressed enough, this is not a rating or scoring system for individual participation or contribution, rather, a way for participants in a cohort (or Team, which we use more frequently, see [Teams](teams.md)) to determine whether they are comfortable with how they are contributing their Time, Effort, and Expertise, to maintain a comfortable pace.

## Examples

<!-- TODO: Create example Torque schemes -->
