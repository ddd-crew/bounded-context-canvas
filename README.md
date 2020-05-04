# The Bounded Context Canvas

The Bounded Context Canvas is a collaborative tool for designing and documenting the design of a single bounded context.

A bounded context is a sub-system in a software architecture aligned to a part of your domain ([Link to full definition])

The canvas guides you through the process of designing a bounded context by requiring you to consider and make choices about the key elements of its design, from naming to responsibilities, to its public interface and dependencies.

![alt text](resources/bounded-context-canvas-v3.jpeg "The Bounded Context Canvas V3")

## How to Use

There is no strict rule about the order in which you should fill out the canvas, however, in general it is recommended to start at the top left with the name, move down the left column and then start at the top of the right column.

You may not have all the information you need to complete certain sections of the canvas. In such a case, you'll need to use other modelling techniques to find the information you require. See [DDD Toolbox](https://github.com/ddd-crew/ddd-toolbox) for suggestions.

## Section Definitions

Here is a short explanation of each section of the canvas.

### Name
Naming is hard. Writing down the name of your context and gaining agreement as a team will frame how you design the context.

### Description
A few sentences describing the why and what of the context in business language. No technical details heres.

Writing down the description forces you to clearly articulate fuzzy thoughts and ensure everybody in the team is on the same page.

### Strategic Classification
How important is this context to the success of your organisation? Is it: 

- core domain: a key strategic initiative
- supporting domain: necessary but not a differentiator
- generic: a common capability found in many domains

What role does the context play in your business model:

- revenue generator: people pay directly for this
- engagement creator: users like it but they don't pay for it
- compliance enforcer: ensures laws and legislations are not broken

How evolved is the concept (see [Wardley Maps](https://medium.com/wardleymaps)):

- genesis: new unexplored domain
- custom built: companies are building their own versions
- product: off-the-shelf versions exist with differentiation
- commodity: highly-standardised versions exist 

### Business Decisions
What are the key business rules and policies within this context?

### Ubiquitous Language
What are the key domain terms that exist within this context, and what do they mean?

### Model Traits
How can you characterise the behaviour of this bounded context? Does it receive high volumes of data and crunch them into insights - an analysis context. Or does it enforce a workflow - an execution context.

Think about the best way to describe your context's behaviour, but do not specify architectural patterns here.

Check out [Alberto Brandolini's ideas](http://cyrille.martraire.com/2012/09/collaborative-construction-by-alberto-brandolini/) for inspiration.

### Messages Consumed and Produced
What is the public interface or the contract of your bounded context? Which messages come in and which does it send out?

### Dependencies and Relationships
To create loosely coupled systems it's essential to be wary of dependencies. In this section you should write the name of each dependency and a short explanation of why the dependency exists.

## Additional Resources

- [Bounded Context Canvas V3: Simplifications and Additions](https://medium.com/nick-tune-tech-strategy-blog/bounded-context-canvas-v2-simplifications-and-additions-229ed35f825f)

## Contributors

Thank you to the following individuals who have all contributed to the Bounded Context Canvas:

- [Kacper Gunia](https://github.com/cakper)
- [Kenny Baas](https://github.com/Baasie)
- [Kim Lindhard](https://github.com/kim-lindhard-dfds)
- [Michael Plöd](https://github.com/mploed)
- [Maxime Sanglan-Charlier](https://twitter.com/__maxs__)
- [Nick Tune](https://github.com/ntcoding)

A significant contribution to the Bounded Context Canvas was the inspiration of the [Business Model Canvas](https://www.strategyzer.com/canvas/business-model-canvas).

## Contributions and Feedback

The Bounded Context Canvas is freely available for you to use. In addition, your feedback and ideas are welcome to improve the canvas or to create new versions. 

Feel free to also send us a pull request with your examples.

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg