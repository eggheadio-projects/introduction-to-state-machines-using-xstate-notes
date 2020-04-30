<h1 align="center"><a href="https://egghead.io/courses/introduction-to-state-machines-using-xstate"> Introduction to State Machines Using XState </a></h1>

<p align="center"><img src="https://d2eip9sf3oo6c2.cloudfront.net/series/square_covers/000/000/403/thumb/IntroxState_1000.png" width="300"/></p>

[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Instructor

- [Kyle Shevlin](https://egghead.io/instructors/kyle-shevlin)

## Description
The difficulty of managing state is one of the primary reasons our applications become so complex. We try and manage this complexity with a lot of booleans, somewhat semantic variables like `isLoading`, `wasFetched`, and `hasError`, and over-engineered systems that are _still_ full of bugs. Surely, there's a better way.

That better way is *state machines*.

State machines formalize how we define and transition through the states of our application and give us ultimate control of the most complex parts of our apps.

In this course, we will explore the problems state machines purport to solve, like boolean explosion. We'll try to solve it our own way first, get so far, and then demonstrate how state machines get us all the way. After that, we'll dive into the XState library, JavaScript's premiere state machine library, to learn its API and how to use it to solve our problems.

By the time you're done taking this course, you should have a solid education about state machines and be able to start applying them


## Table of Contents

- [01. Course Intro and Overview](01_xstate-course-intro-and-overview.md)
- [02. Eliminate Boolean Explosion by Enumerating States](02_javascript-eliminate-boolean-explosion-by-enumerating-states.md)
- [03. Replace Enumerated States with a State Machine](03_xstate-replace-enumerated-states-with-a-state-machine.md)
- [04. Use an Interpreter to Instantiate a Machine](04_xstate-use-an-interpreter-to-instantiate-a-machine.md)
- [05. Use XState Viz to Visually Develop and Test Your Machine](05_xstate-use-xstate-viz-to-visually-develop-and-test-your-machine.md)
- [06. Add Actions to Transitions to Fire Side Effects](06_xstate-add-actions-to-transitions-to-fire-side-effects.md)
- [07. Trigger Actions When Entering and Exiting a XState State](07_xstate-trigger-actions-when-entering-and-exiting-a-xstate-state.md)
- [08. Replace Inline Functions with String Shorthands](08_xstate-replace-inline-functions-with-string-shorthands.md)
- [09. Use Internal Transitions in XState to Avoid State Exit and Re-Entry](09_xstate-use-internal-transitions-in-xstate-to-avoid-state-exit-and-re-entry.md)
- [10. Send Events to the Machine with the XState Send Action Creator](10_xstate-send-events-to-the-machine-with-the-xstate-send-action-creator.md)
- [11. Track Infinite States with with XState Context](11_xstate-track-infinite-states-with-with-xstate-context.md)
- [12. How Action Order Affects Assigns to Context in a XState Machine](12_xstate-how-action-order-affects-assigns-to-context-in-a-xstate-machine.md)
- [13. Use Activities in XState to Run Ongoing Side Effects](13_xstate-use-activities-in-xstate-to-run-ongoing-side-effects.md)
- [14. Conditionally Transition to States with Guards in XState](14_xstate-conditionally-transition-to-states-with-guards-in-xstate.md)
- [15. Simplify State Explosion in XState through Hierarchical States](15_xstate-simplify-state-explosion-in-xstate-through-hierarchical-states.md)
- [16. Multiple Simultaneous States with Parallel States](16_xstate-multiple-simultaneous-states-with-parallel-states.md)
- [17. Recall Previous States with XState History States Nodes](17_xstate-recall-previous-states-with-xstate-history-states-nodes.md)
- [18. Use XState Null Events and Transient Transitions to Immediately Transition States](18_xstate-use-xstate-null-events-and-transient-transitions-to-immediately-transition-states.md)
- [19. Delay XState Events and Transitions](19_xstate-delay-xstate-events-and-transitions.md)
- [20. Invoking a Promise for Asynchronous State Transitions in XState](20_xstate-invoking-a-promise-for-asynchronous-state-transitions-in-xstate.md)
- [21. Invoke Callbacks to Send and Receive Events from a Parent XState Machine](21_xstate-invoke-callbacks-to-send-and-receive-events-from-a-parent-xstate-machine.md)
- [22. Invoke Child XState Machines from a Parent Machine](22_xstate-invoke-child-xstate-machines-from-a-parent-machine.md)

## Contribute

- These are community notes that I hope everyone who studies benefits from.
- If you notice areas that could be improved please **feel free to open a PR**!

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):
<table>
  <tr>
  <td align="center"><a href="https://github.com/doingandlearning"><img src="https://avatars2.githubusercontent.com/u/8320213?s=400&u=091f53ddb85c741ef9509d21e4dc3ab178288634&v=4" width="100px;" alt=""/><br /><sub><b>Kevin Cunningham</b></sub></a><br /><a href="#content-doingandlearning" title="Content">🖋</a>  
  </td>
  <td align="center"><a href="https://github.com/lsminter"><img src="https://avatars2.githubusercontent.com/u/26470581?s=400&u=89e0c4f7db5c054125a372dc17b4590e297ac20d&v=4" width="100px;" alt=""/><br /><sub><b>Lucas Minter</b></sub></a><br /><a href="#review-lsminter" title="Review">👀</a>  </td>
    </td>
</table>
