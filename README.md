# Architecture Decision Records

Documentation on creating and storing architecture_decision_records (ADRs) on a project

## What is an Architecture Decision Record or ADR?

Architectural conversations and white boarding sessions only take us so far. We need to remember the key decisions and the motivation for them. However, no one wants to take the time to write them down and usually the documents are never updated.

The answer to the question is ADRs. The question: what is the smallest amount of documentation required, that remains effective, and maintainable?

The Alexandrian Pattern example shows how we can create a simple text file that describes the set of forces and a single decision on one problem. We would create an ADR for each key question that must be answered for our application.

## What happens without ADRs?
There are two choices for the employee that is new to the project.

1. Blindly accept the decisions
2. Blindly change it.

Default acceptance might work but doesn't allow a review of the system and the identification of things that the team should change. This can also cause teams that are afraid to change anything. The system is never updated and becomes a big ball of mud. Failing due to Fear!

Blindly changing things can have a bigger impact and undo months of work or break an entire system.

It is important to understand the motivations and not just the code itself. Recommending any design, code, or tool without the context is dangerous and can undermine the ability to create a great system.



## A decision is worth documenting if
1. You spent lots of time on it
2. The decision is critical to achieving a requirement
3. The outcome or options are confusing at first
4. The decision has a widespread impact
5. The decision is difficult to undo
