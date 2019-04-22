# Working on Epics

This document outlines the process for tracking progress for an epic.

## What is an Epic?

We use the term "epic" to represent work on a feature or workflow that satisfies
this criteria:

 - requires tracking a large number of issues
 - can be shipped to users over a number of releases
 - there is expected to be iteration and learning as the feature is worked on
 - requires co-ordination with engineering and product to determine what
   gets worked on and when

## Setup

### 0. Identifying

**destkop/engineering**, **@desktop/product** and **@desktop/design** should
co-oridinate during release planning to identify these epics and document the
high-level goals for what problem is being addressed. This will likely require
user research, designs and scoping of work to determine what can be shipped.

### 1. Create project board

With the epic is identified and the prerequisite information ready, the project
board to track the work should be created. Ensure it is named something that
is discoverable for contributors.

The project board should contain columns representing important goals, which
will require input from engineering and product teams.

Some examples of goals:

 - **a MVP milestone** - what's the minimum set that is needed to show a
 solution to others?
 - **beta milestones** - what things need to ship after the initial MVP?
 - **production milestones** - what things are needed to ship this to the world?
 - **future work** - what things are important to the problem and should be kept
 in mind in the medium term?

Other columns that might appear in the project board:

 - **Unclear** - issues with feedback that needs to be investigated
 - **Nice to have** - issues that feel valuable but aren't yet associated with a
 goal

The list of goals/columns will likely differ between epics, and will likely
change over time as the work evolves and things are learned about the problem
and solutions.

### 2. Sketch out tasks

The next step is to sketch out a rough list of issues that represent the work
required.

The actual process for defining these tasks will be up to the engineer(s)
involved with the work, but **@desktop/product** should provide input to ensure
things are organised in a way that makes sense to them.

### 3. Initial planning

With the initial scope defined, the engineer(s) should add each issue associated
with the epic to the most suitable columns in the project board. The goal here
is to have a starting point to discuss with **@desktop/product** about how the
work will be tackled.

## Progress Updates

With that initial setup ready, and **@desktop/product** has endorsed the plan,
engineering work can commence and pull requests should be opened for review.

There should be periodical meetings to review and update the project board. The
goal of these meetings should be:

 - check in with how progress is tracking with respect to the planned releases
 - identify problems related to shipping and evaluate options
 - discuss new issues or feedback since the last meeting and prioritize (or
 defer) the work

## Wrap up

_TODO_
