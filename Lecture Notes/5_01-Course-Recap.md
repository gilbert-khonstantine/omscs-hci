# 5.1 Course Recap

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 695–713)  
*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

## Contents
- [Introduction](#introduction)
- [Recap: HCI Principles](#recap-hci-principles)
- [Recap: Feedback Cycle](#recap-feedback-cycle)
- [Recap: Direct Manipulation and Invisible Interfaces](#recap-direct-manipulation-and-invisible-interfaces)
- [Recap: Human Abilities](#recap-human-abilities)
- [Recap: Design Principles and Heuristics](#recap-design-principles-and-heuristics)
- [Recap: Mental Models and Representations](#recap-mental-models-and-representations)
- [Recap: Task Analysis](#recap-task-analysis)
- [Recap: Distributed Cognition](#recap-distributed-cognition)
- [Recap: HCI Methods](#recap-hci-methods)
- [Recap: Ethics and Human Research](#recap-ethics-and-human-research)
- [Recap: Needfinding and Requirements Gathering](#recap-needfinding-and-requirements-gathering)
- [Recap: Design Alternatives](#recap-design-alternatives)
- [Recap: Prototyping](#recap-prototyping)
- [Recap: Evaluation](#recap-evaluation)
- [Recap: HCI and Agile Development](#recap-hci-and-agile-development)
- [Exploring HCI: Recap](#exploring-hci-recap)
- [Conclusion](#conclusion)

## Introduction

We’ve reached the end of our HCI course. To close things off, let’s briefly recap what we’ve covered. The purpose of this lesson isn’t just to give you an inventory of the course content. The real reason is to give us an excuse to have this cool inception effect over here.

No, really it’s to repeat it again to load it into your working memory one more time. After all, we know that the more often you load some content into short-term memory, the more strongly it remains in long-term memory. That was a principle we learned in the lesson on human abilities, and it covers why we start and end every lesson by repeating the material that will be covered. Each repeat loads it into your short-term memory one more time, further solidifying it. So to close this course, we’ll do this one more time, although we hope that you’ll come back again and again to watch some of the material when you need a refresher.

## Recap: HCI Principles

Our first unit was the unit on design principles. To start that unit off, we began by investigating the process of identifying a task. We discussed how a task is not just the actions that a user performs, but it’s the combination of their motivations, their goals, the context, and so on. We emphasized that we’re not just interface designers, we’re task designers. We design tasks, and then design the interfaces that make those tasks possible. We then explored three views on the user’s role in a task. We might view them as an information processor, like another computer in the system. We might view them as a predictor, someone operating a mental model of the system. We might view them as a participant, someone working in a larger context beyond just our interface. Finally, we discussed how the views we take inform the designs we create.

## Recap: Feedback Cycle

We started the first unit by discussing feedback cycles. Feedback cycles, as we discussed, are ubiquitous in all areas of life. They’re how we learn and adapt to our environments, and so they’re also how we learn and adapt to the interfaces available to us. We then described the two parts of feedback cycles. Gulfs of execution covered how users go from personal goals to external actions. Gulfs of evaluation covered how the users then evaluated whether the results of those actions met their goals. We can describe basically all of HCI as designing ways to bridge these two gulfs: helping users accomplish their goals more easily, and helping users understand that their goals have been accomplished more quickly.

## Recap: Direct Manipulation and Invisible Interfaces

We then moved on to direct manipulation, which was one way to create interfaces with very short gulfs of execution and evaluation. Direct manipulation involved creating interfaces where the user felt like they were directly interacting with the object of the task. Instead of typing commands or selecting operators, they would more physically participate with the interface. The goal of this, and really of any good interface design, was to create interfaces that become invisible. Invisible interfaces are those that allow the user to focus completely on the task instead of on the interface. We noted that nearly any interface can become invisible when the user has enough practice and expertise, but our goal is to create interfaces that vanish sooner by good design.

## Recap: Human Abilities

We’re discussing human-computer interaction, and that means we have to understand the human portion of the equation. So, we also took a crash course toward some basic psychology. We broke the human down into three systems: perception, cognition, and the motor system. With perception, we covered the strengths and limitations of the human visual, auditory, and kinesthetic senses. We discussed how each can be useful for different kinds of information. Then, we discussed some of the limitations to human cognition. We focused on memory: how many things can be stored at a time, and how things can be stored more permanently. We also discussed the notion of cognitive load. We focused especially on how we should use our interfaces to reduce the user’s cognitive load. Finally, we discussed the limitations of the human motor system, especially how those limitations change with age or in the presence of distractions. We’re designing for humans, so these limitations and advantages are key to how we design our interfaces.

## Recap: Design Principles and Heuristics

Human-computer interaction has a long and rich history, initially drawing from human factors engineering before becoming a field of its own. During that history, it’s developed lots of principles and heuristics for how to design good interfaces. Lots and lots and lots, in fact. Literally thousands. In this lesson, we covered fifteen of the most significant ones, drawn from four sets of design principles. We covered the principles of Don Norman, Jakob Nielsen, Larry Constantine, Lucy Lockwood, and the Centre for Universal Design. Among these, I would argue the most significant principles were Affordances, Mappings, and Constraints. Affordances are parts of interfaces that, by their design, tell the user what to do. A good mapping tells the user what the effect of that interaction will actually be. Constraints ensure that the user only chooses to do the correct things. With those three combined, as well as the other heuristics, we can create interfaces that vanish between the user and the task very quickly.

## Recap: Mental Models and Representations

Every one of our users has some mental understanding of their task, as well as where our interfaces fit in that task. We call that their mental model. They use that mental model to simulate and predict the effects of certain actions. Our goal is for the user’s mental model to match the reality of the task and the interface. To accomplish that, we try to design representations with clear mappings to the underlying task. That’s how we can ensure the user’s mental model of the system is accurate and useful. We discussed mistakes, which are errors that occur based on inaccurate mental models, and we discussed slips, which are errors that occur despite accurate mental models. We also talked about a couple of the challenges that can arise in trying to help users build accurate mental models. One of those was called expert blind spot, which occurs when we lose sight of our own expertise and forget what it’s like to be a novice. And the other was learned helplessness, which is when users learn that they have no real ability to accomplish their goals because of a broken feedback cycle. In designing representations that lead to accurate mental models, we need to make sure to avoid both of these.

## Recap: Task Analysis

We’ve discussed repeatedly that HCI is in large part about understanding tasks. As designers, we design tasks that feature interfaces, not just interfaces alone. To accomplish that, it’s important to have a very clear understanding of the task for which we’re designing. Toward that end, we discussed task analysis. Task analyses are ways of breaking down tasks into formal workflows to aid the design process. We covered two general kinds of task analyses. Information processor models, like the GOMS model, focus on the user’s goals, operators, and methods. They’re concerned primarily with what we can observe. Cognitive task analyses, on the other hand, try to get inside the user’s head and understand the thought process in the task as well. Both of these approaches are valuable to designing good tasks with usable interfaces.

## Recap: Distributed Cognition

Earlier, we discussed the idea of cognitive load. Cognitive load was the principle that humans have a set amount of cognitive resources, and if they’re overloaded, their performance suffers and they get frustrated. So, how do we reduce the user’s cognitive load? Well we can make the task easier, sure, but we can also add to their cognitive resources. That’s the principle of distributed cognition: the interactions of humans and artifacts together have more cognitive resources than individuals. Devices and interfaces can exhibit cognitive properties like memory and reasoning, offloading those demands from the user. We also discussed three related theories: social cognition, situated action, and activity theory. All three of these put a strong emphasis on the context of a task, whether it be the physical context, social context, or societal context.

## Recap: HCI Methods

The design principles unit of the course covered the fundamental principles and ideas developed over decades of work in this space. However, we can’t create good interfaces just by applying old principles to new problems. Those old principles can help us make progress much faster, but to design good interfaces, we have to involve the user. That’s perhaps the most important principle of HCI: user- centered design. User-centered design advocated keeping the user at the heart of all our design activities. For us, that isn’t just the person using the tool, but it’s also the people affected by the tool’s very existence. To keep the user in mind, we use an iterative design life cycle that focuses on getting feedback from the user early and often. The methods of that life cycle were the core of the methods unit of the course.

## Recap: Ethics and Human Research

When we’re doing research in HCI, we have access to some pretty sensitive personal data about our participants. There are huge ethical considerations around privacy and coercion that we have to keep in mind when participating in the design life cycle. So, we discussed the role of institutional review board, or IRB, for university research. They oversee studies and make sure we’re preserving our participants’ rights. They also make sure that the benefits of our research outweigh the risks, and as part of that, they help ensure our methods are sound enough to have benefits in the first place. We also discussed how industry doesn’t have the same kind of oversight. However, some companies have partnered with universities to participate with their IRBs, while others have formed internal IRBs. All of this is driven by t he need to preserve the rights of our users. That’s a key part of user-centered design.

## Recap: Needfinding and Requirements Gathering

The first stage of the design life cycle was needfinding. Needfinding was how we developed a keen understanding of the needs of our users. One of the biggest mistakes a designer can make is assuming they already understand the user and the task before ever interacting with them. There are several questions about the user we need to answer before we’re ready to start designing. So, to get a good understanding of the u-ser and the task, we discussed several methods. We might start with methods that have little direct interaction with users, like watching them in the wild or trying out the task ourselves. We might use those to inform more targeted needfinding exercises, like interviews, focus groups, and surveys. By combining multiple needfinding approaches, we can build a strong model of the user and the task that will help us design usable interfaces.

## Recap: Design Alternatives

Once we have a solid understanding of the user and the task, we want to start brainstorming possible designs. The important thing here is to make sure we don’t get fixated on one idea too early. That sort of tunnel vision risks missing lots of fantastic ideas. So, we want to make sure to engage in a well- defined brainstorming process. I recommend starting that with individual brainstorming, then setting up a group brainstorming session that ensures everyone’s ideas are heard. From there, we proposed some different ideas on how to explore those design alternatives, through methods like personas, scenarios, and timelines. Our end goal here was to arrive at a set of designs worth moving on to the prototyping stage.

## Recap: Prototyping

In user-centered design, our goal is to get user feedback early and often. So, once we have some design alternatives, our goal is to get them in front of users as quickly as possible. That’s the prototyping stage, where we take those design alternatives and build prototypes we can show to users. At first, those prototypes might be very low-fidelity. We might start by just describing or drawing the designs. Those are verbal or paper prototypes. We want to keep our designs easy to revise. We might even revise the prototypes live while working with users. As we get more and more feedback, we build higher-fidelity prototypes to explore more detailed questions about our designs. We might use wireframes or set up live simulated demos. At every stage of the way, we design our prototypes in a way to get the user’s view and inform the next iteration of the design life cycle.

## Recap: Evaluation

The goal of the design life cycle is to get frequent user feedback. Or, to put it differently, to frequently evaluate our interface ideas. Frequent, rapid feedback cycles are important for users of our interfaces, and they’re also important to us as designers of interfaces. That’s where evaluation comes into play. Once we’ve designed an interface, whether it’s just an idea in our head or a full-fledged working version, it’s time to evaluate it with users. Early on, that may be qualitative evaluation to get the full picture of the user experience. Later, that might be empirical evaluation, to more formally capture the results of the interface. Along the way, we might also employ predictive evaluation to try to anticipate how users will react to our designs. These methods are the foundation of user-centered design: design that features frequent user evaluation of our ideas.

## Recap: HCI and Agile Development

Traditional HCI can be a slow, deliberate process, fed by constant interaction with users as we slowly ramp up the fidelity of our prototypes. In the past, that was because every phase of the process was expensive: development, distribution, evaluation, and updates were all expensive. But now, in some contexts, those steps have become much, much cheaper. Some web development can be done with drag-and-drop interfaces. We can now distribute applications to millions of users essentially for free. We can pull back enormous quantities of live data from them. We can push updates to all of them in real time. Given all that, sometimes it might be more prudent to put together working versions quickly to start getting real user data faster. So, we also discussed agile methods for development while keeping an eye on the design life cycle. These methods aren’t appropriate for all contexts, especially those with high costs of failure, but for many contexts they can really increase the iteration speed of our design life cycle.

## Exploring HCI: Recap

Over the course of our conversations, I’ve asked you to revisit the area of HCI in which you’re most interested during each topic. I’ve asked you to brainstorm how the various design principles and theories apply to the area you chose. I’ve asked you to think of a design life cycle that would support developing in that chosen application area. We’ve also given you lots of information to read about your chosen area. You have all the tools necessary to start developing. I’m looking forward to seeing what you come up with.

## Conclusion

One of the famous models for communicating is to tell them what you’re going to tell them, tell them, then tell them what you told them. That’s what we’ve done, at several levels of abstraction. At the beginning of the course, we told you the overall structure of the course. Within each unit, we outlined the content of the unit. Within each lesson, we previewed the content of that particular lesson. Then we delivered the content. Then, we summarized each the lesson. Then, we summarized each unit. Now, we’ve summarized again the course as a whole. So, we’re done, right? ...not quite. There are two other useful things to cover: the closely related fields to HCI, and where you might want to go next.
