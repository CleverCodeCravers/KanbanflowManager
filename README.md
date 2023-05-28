# KanbanflowManager
A support application that helps with the management of a kanbanflow based board

Date: 28.05.2023
Responsible: Stefan Hoffmann

## Process

- [DOING] Problem Description
- [ ] Requirements-Draft
- [ ] System-Environment Graph/Architecture (Flow Design)
- [ ] Graph of interactions (Flow Design)
- [ ] Broad Design (Flow Design)
- [ ] in-depth design where necessary (Flow Design)

## Background / Problem

We work with a [kanbanflow based](https://kanbanflow.com) board. The board has several columns that cover our process.
The board at the moment contains 177 tasks in 12 process steps.
During the week about 50 tasks will enter and exit the board again (as completed). 

The managers tasks are:
- Be informed about the tasks on the board.
- Make sure, that for every task it is clear what is to do next. (Prioritize)
- Make sure our developer(s) know that it is clear what they need to do next.
- Collect reports from our developer(s) about progress.
  - Make sure the tasks for the developer(s) are not too big, so that progress reports are regularily going out.
  - Keep a time plan / forecast for the currently running projects up-to-date.

That is a lot to keep in mind and we do not perform optimally. Still, this is necessary to deliver good results.

We think that the problem is, that the job contains so many different areas and topics that it is really hard for the management to give attention to everything that wants some.

## Current Situation

- In the recent weeks our performance measured by general EFP and "Task Count completed" in projects is dropping.
- We start more and more long running tasks without completing the currently running ones. 
- Somehow we always end up in situations where the attention of the management has ignored a thing that is currently needed. This creates blocking situations where the team waits for the management to compensate for the issue. E.g. we encountered the following problems:
  - build system maintainance is bad, windows updates are blocking our systems
  - The long term developers work on tasks that span several weeks (the splitting into smaller tasks does not work). That is why they do not complete any tasks in our measurement system.
  - we have meetings with other departments about important topics, but those topics are not the ones that we currently have to work on. We only have a meeting then perform 1-3 small tasks in that area and then we have other problems to deal with (even higher fragmentation of work)

At the moment we do not have a way to systemize the way the management works and to balance the attention.

## Target Situation

The management has an effective way to drive the assignment of attention to the important areas.

This way we assure that the following things are true in order:

1. Our build systems are operational.
2. Our long term developer(s) always have small tasks that they work on.
3. The management will react to new mails and new incoming support cases.
  1. Assign an EFP value.
  2. Assign a time estimate.
4. Management free to work on own development tasks for 25 Minutes.
5. Check all rules again.

When a rule above another rule is not true anymore, the managements task is to work on that until it is true again.

## Immediate Measures

- [ ] An immediate measure would be a simple "gong" app, that would remind management when another round is due.

## Root Cause Analysis

- Logic trees, probably Current Reality Tree or Future Reality Tree
- 5-Why method
- Fishbone diagram / Ishikawa diagram (Man, Method, Machine, Material, Environment -> Effect)
- Fault Tree Analysis (Suggested by Jens)
	  
## Problem Solution / Countermeasures / Action Plan

- Brainstorming: Establish and evaluate solution alternatives, as well as select
- Small PDCA cycles
- Could contain table: What, Who, When, Status, Effectiveness

## Success Measurement

- Starting from the initial state, what are the progress and possibly the final measurement.
- How much have we improved?

## Standardization and Knowledge Transfer

- How do we anchor the solutions in our daily work routines?
