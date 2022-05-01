# Week 7

> Ten questions on each test will be based on these readings. From the perspective of the test, your emphasis in reading these papers should be in getting a sufficient understanding of the material to answer high-level questions about the paper, as well as to be able to find answers quickly for more specific questions.

## What Do Prototypes Prototype

> Houde, S., & Hill, C. (1997). What do prototypes prototype? In M. Helandar, T.K. Landaeur, & P. Prabhu (Eds). Handbook of Human-Computer Interaction, 2. (pp. 367-381). Elsevier Science.

Topic: to establish a model that describes any prototype in terms of the artifact being designed, rather than the prototype’s incidental attributes.

Paper aims to focus more attention on fundamental questions about the interactive system being designed: What role will the artifact play in a user’s life? How should it look and feel? How should it be implemented?

By focusing on the purpose of the prototype—that is, on what it prototypes—we can make better decisions about the kinds of prototypes to build.

### The Problem With Prototypes

It is difficult for designers to communicate clearly about prototypes to such a broad audience. It is challenging to build prototypes which produce feedback from users on the most important design questions.

### What Is A Prototype

What is significant is not what media or tools were are used to create them, but how they are used by a designer to explore or demonstrate some aspect of the future artifact.

### Definitions

- **Artifact** - the interactive system being designed
- **Prototype** - any representation of a design idea, regardless of medium
- **Designer** - anyone who creates a prototype in order to design, regardless of job title
- **Model**:
  - **Role** - refers to questions about the function that an artifact serves in a user’s life—the way in which is it useful to them
  - **Look and feel** - denotes questions about the concrete sensory experience of using an artifact—what the user looks at, feels, and hears while using it
  - **Implementation** - refers to questions about the techniques and components through which an artifact performs its function

## Prototyping Tools And Techniques

> Beaudouin-Lafon, M., & Mackay, W. (2003). Prototyping tools and techniques. Human Computer Interaction-Development Process. (pp. 101-142).

Topic: tools and techniques for using prototypes to design interactive systems. The goal is to illustrate how they can help designers generate and share new ideas, get feedback from users or customers, choose among design alternatives, and articulate reasons for their final choices.

### What Is A Prototype

- **Prototype** - a concrete representation of part or all of an interactive system; a tangible artifact, not an abstract description that requires interpretation

We can look at prototypes as both concrete artifacts in their own right or as important components of the design process. When viewed as artifacts, successful prototypes have several characteristics:

- _Support creativity_, helping the developer to capture and generate ideas, facilitate the exploration of a design space and uncover relevant information about users and their work practices
- _Encourage communication_, helping designers, engineers, managers, software developers, customers and users to discuss options and interact with each other
- _Permit early evaluation_ since they can be tested in various ways, including traditional usability studies and informal user feedback, throughout the design process

We can analyze prototypes and prototyping techniques along four dimensions:

- **Representation** - describes the form of the prototype, e.g., sets of paper sketches or computer simulations; online vs offline.
- **Precision** - describes the level of detail at which the prototype is to be evaluated; e.g., informal and rough or highly polished; what is considered is upto the evaluation, but whats left out is up for debate.
- **Interactivity** - describes the extent to which the user can actually interact with the prototype; e.g., watch-only or fully interactive;
   * Fixed; Fixed path; open (vertical) prototype 
- **Evolution** - describes the expected life-cycle of the prototype, e.g. throwaway(rapid) or iterative(working on a spc. task) or evolutionalty.



### Precision

> Although it may seem contradictory, a detailed representation need not be precise. This is an important characteristic of prototypes: those parts of the prototype that are not precise are those open for future discussion or for exploration of the design space

### Interactivity

> A critical role for an interactive system prototype is to illustrate how the user will interact with the system. While this may seem more natural with on-line prototypes, in fact it is often easier to explore different interaction strategies with off-line prototypes.

### Prototypes and the design process
**Participatory** : User is part of the design
**User Centered**: user is part of the whole dev cycle.

### Exploring The Design Space

All designers work with constraints: not just limited budgets and programming resources, but also design constraints. These are not necessarily bad: one cannot be creative along all dimensions at once. However, some constraints are unnecessary, derived from poor framing of the original design problem

Some of the most effective design solutions derive from a more careful understanding and reframing of the design brief.

Prototypes aid designers in both aspects of working with a design space: generating concrete representations of new ideas and clarifying specific design directions.

## Horizontal Prototypes

The purpose of a horizontal prototype is to develop one entire layer of the design at the same time.

## Vertical Prototypes

The purpose of a vertical prototype is to ensure that the designer can implement the full, working system, from the user interface layer down to the underlying system layer. Usally throw away;
## Task based prototype
Task specifict
## Scenario based 
Considers task and the context.


### Off-line Rapid Prototyping Techniques

There are four types covered in this paper:

1. Paper and pencil
2. Mock-ups
3. Wizard of Oz
4. Video prototyping

### On-line Rapid Prototyping Techniques

There are three types covered in this paper:

1. Non-interactive simulations : Animation
2. Interactive simulations: Figma
3. Scripting languages: JS?

5. Iterative prototypes

### 5. Iterative prototypes
## 5.1 Software tools
# Graphical libraries and Window systems
Graphical libraries underlie all the other tools presented in this section. Their main purpose is to provide the developer with a hardware-independent, and sometimes
cross-platform application programming interface (API) for drawing on the screen. They can be separated into two categories: direct drawing and scene-graph based.
# User interface toolkits
User interface toolkits are probably the most widely used tool nowadays to implement applications. All three major platforms (Unix/Linux, MacOS and Windows) come with at least one standard UI toolkit. The main abstraction provided by a UI toolkit is the widget. A widget is a software object that has three facets that closely match the __MVC model: a presentation, a behavior and an application interface__. Part of widget - 
* Callback
* Active variables
* Listensers.

# User interface builders

## 5.2 Software environments
# Application F/W
Mac, windows 
# Model based
Model-based tools take the other approach, starting with the functional core and domain objects, and working their way towards the user interface and the presentation
# User interface development environments (IDE)

### 6. Evolutionary Prototypes
## 6.1 Software architectures
MVC 
Presentation-Abstraction-Control model (PAC)
A variant of MVC, called MVP (Model-View-Presenter),
## 6.2 Design Patterns  
because user input should drive the system’s reactions. Unfortunately, more often than not, the functional core also needs to be in control. This is especially
common when creating user interfaces for legacy applications. In the Seeheim and Arch models, it is often believed that control is located in the dialog controller
when in fact these architecture 

> Design patterns have emerged in recent years as a way to capture effective solutions to recurrent software design problems. It is interesting to note than many of these patterns come from interactive software, and most of them can be applied to the design of interactive systems. Most patterns for interactive systems are behavioral patterns, i.e. patterns that describe how to implement the control structure of the system.

### Summary

> Prototypes, because they are concrete and not abstract, provide a rich medium for exploring a design space. They suggest alternate design paths and reveal important details about particular design decisions. They force designers to be creative and to articulate their design decisions. Prototypes embody design ideas and encourage designers to confront their differences of opinion. The precise aspects of a prototype offer specific design solutions: designers can then decide to generate and compare alternatives. The imprecise or incomplete aspects of a prototype highlight the areas that must be refined or require additional ideas.

On another note regarding prototypes:

> Perhaps most important, prototypes provide one of the most effective means for designers to communicate with each other, as well as with users, developers and managers, throughout the design process.
