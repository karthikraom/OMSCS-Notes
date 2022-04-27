# Lesson 10

In this lesson we will look into two methods for task analysis:

1. Human information processor models >> Processor model
2. Cognitive task analysis >> Predictor Model

## GOMS Model

A human information processor model; it builds off the processor model of the human's role in a system. There are four categories in the GOMS model:

1. Goals
2. Operators - methods have operators.
3. Methods - methods to accomplish a goal
4. Selection rules - users uses to choose the methods.

This model proposes that a human has a set of _goals_ and _methods_ they can choose from to accomplish those goals. Each method is comprised of a series of _operators_ which help carry out that method. Lastly, they use some set of _selection rules_ to help decide what method to choose from.

## Strengths And Weaknesses Of GOMS

Weaknesses of GOMS model:

1. Does not address complexity
2. Assumes user is an expert

Strengths of GOMS model:

1. Formalize user interaction

## Different types of GOMS Models
* KLM GOMS - Keystroke level model - add the time taken for each key stroke and determine the effectivenes.
* CMN GOMS - Card, Moran and Newell GOMS: submethods and conditions.
* NGOMSL - Natural GOMS language - lets us foucs in on cases where we might be asking __too__ much from the users.

## 5 Tips: Developing GOMS Models

1. Focus on small goals
2. Nest goals, not operators
3. Differentiate descriptive and prescriptive - what ppl do or what you want them to do; GOMS is for what ppl __should__ do.
4. Assign costs to operators
5. Use GOMS to trim waste - helps you reduce operators and the costs associated to each operator.

## GOMS to Cognitive Task Analysis

The GOMS model assumes the human is an input-output machine (processor model). However, human reasoning may be too nuanced and complex to be so simplified.

Cognitive task analysis is another way of examining tasks but it puts a much higher emphasis on things like memory, attention, and cognitive load (predictor model).
## Behaviorism Vs Cognitism
Behav: things that we can observe; and says that should be enough.
Cog: can and should get intot the mind of the user.

## Cognitive Task Analysis

Cognitive task analysis are concerned with the underlying thought process associated with performing a task. Most methods follow a particular common sequence:

1. Collecting preliminary knowledge - observe
2. Identify knowledge representations - is there a set of takss to be done in order OR a web of tasks.
3. Apply focused knowledge elicitation methods - what do users actually know?
4. Analyze and verify data acquired
5. Format results for intend application

## Hierarchical Task Analysis
Breaking down into sub tasks has its merits - ploting routes might be useful for driving a car and for walking or running.
* Abstract
* Modularize
* Organize 

This form of task analysis helps us understand what tools might already be available to accomplish certain portions of our task, or how we might design certain things to transfer between different tasks and different contexts.

Hierarchical task analysis strengths:

1. Abstracting out unnecessary details for a certain level of abstraction
2. Modularizing designs or principles so that they can be transferred between different tasks or different contexts
3. Organizing the cognitive task analysis in a way that makes it easier to understand and reason over

## Cognitive Task Analysis Strengths And Weaknesses

Like the GOMS model, cognitive task analysis also have strengths and weaknesses.

Strengths:

1. Emphasizes mental processes - what goes on users head.
2. Formal enough to for interface design

Weaknesses:

1. Time-intensive
2. May deemphasize context
3. Ill-suited for novices - have  a strong model.

### Other frameworks
Processor model:
* KLM, CPM GOMS, NGOMSL
Coginitive Model:
* Critical decision model - focuses on where crti dec are made.
* Task-knowledge structures - focuses on knwldeg.e
* Coginitive FUnction model -focuses on complexity.
* Applied CTA
* SKill based CTA

## Section Quizzes

### Design Challenge: Security System 1

_Morgan will disable the security system in two different ways, try to outline her goals, outcomes, methods, and selection rules_

|                 | Scenario 1              | Scenario 2              |
| --------------- | ----------------------- | ----------------------- |
| Goals           | Disable security system | Disable security system |
| Outcomes        | System disabled         | System disabled         |
| Methods         | Use keypad              | Use remote              |
| Selection Rules | Normal way              | Convenient way          |

### Reflections: Task Analysis

_Given behaviorism (an approach to psychology that emphasizes behavior as a product of stimuli and the environment) and cognitivism (an approach to psychology that emphasizes internal though processes). How much attention should you devote to observable goals, operators, and methods? How much do you devote to understanding internal thought processes like cognition, learning, and memory_?

I think the designer should devote time as 50-50 split between each as understanding in both behaviorism and cognitivism regarding the user as the information will provide useful insight into creating a well-rounded product.

### Design Challenge: Security System 2

_Going back to Morgan disabling the security system in two ways, build a model of the sequence of thoughts going inside the user's head; paying special attention to what she needs to remember at each step of the process_.

| Thoughts | Scenario 1                             | Scenario 2                              |
| -------- | -------------------------------------- | --------------------------------------- |
| 1        | Open door                              | Open door                               |
| 2        | Turn left                              | Take out remote                         |
| 3        | Enter code on security keypad          | Press button to disable security system |
| 4        | Press enter to disable security system |                                         |
